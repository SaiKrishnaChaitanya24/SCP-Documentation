Usage Notes
===========

Command-Line Arguments
----------------------

.. list-table::
   :header-rows: 1

   * - Argument
     - Description
   * - ``-s``
     - Input subject name
   * - ``-t``
     - Raw T1 Image
   * - ``-g``
     - Tractography algorithm, either probabilistic IFOD2 (Default) or deterministic SD_STREAM
   * - ``-o``
     - Output Directory
   * - ``-A``
     - Angle threshold for tractography. Default: 60
   * - ``-p``
     - Phase encoding value
   * - ``-l``
     -  Step size for tractography, in mm. Default: 1
   * - ``-n``
     - Number of seeds per voxel. Default: 250
   * - ``-P``
     - Enable PFT (backtracking). 
   * - ``-K``
     -  Keep the whole brain track file, in tck format. 
   * - ``-T``
     - Keep the whole brain track file, converted to .trk format. 
   * - ``-a``
     -  affine .mat file from DTI space to T1(Freesurfer) space. 
   * - ``-d``
     - DWI
   * - ``-i``
     -  inverse warp in DTI space that matched T1 to EPI distorted DTI. 
   * - ``-m``
     - DWI space mask. 
   * - ``-f``
     -  Topup flag to be set to 'True' only used for Topup
   * - ``-r``
     - T1 image.
   * - ``-b``
     - Freesurfer labels file. 


Expected Arguments
------------------

For ``notopup``:
   - ``-s``
   - ``-t``
   - ``-a``
   - ``-d``
   - ``-m``
   - ``-o``
   - ``-i``   
   - ``-r``

For ``topup``:
   - ``-s``
   - ``-t``
   - ``-a``
   - ``-d``
   - ``-m``
   - ``-o``
   - ``-f``
   - ``-r``
   - ``-b``

Optional commands are - -P, -K, -T, -A, -l, -g, -n

Index
==================

* :doc:`index`
* :doc:`RunningSCP`
* :ref:`search`

# FixControlPropertyBold
This is a workaround for Microsoft Dynamamics AX 2012 R3 kernel bug. Sometimes axapta client (ax32.exe) corrupts font on an opened form for all controls. Font becomes extrabold, text in controls does not fit. It is very inconvenient). The fix suggests a trick (make all controls bold and then make them unbold) to fix an interface for an opened form (withaout close and open form again). 

## Setup
1. Import FixControlPropertyBold_MRC.xpo
2. Modify your SysSetupForm form according to description in job_FixControlPropertyBold_MRC  job.

### Discussion : 
https://axforum.info/forums/showthread.php?p=440659#post440659
https://axforum.info/forums/showthread.php?p=432392#post432392

## License
The FixControlPropertyBold source code in this repo is available under the MIT license. See [License.txt](LICENSE.txt).

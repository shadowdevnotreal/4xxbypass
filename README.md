<p align="center">
4xxbypass
</p>

<p align="center">
4XX Bypass and exploit tool
</p>


<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/43219706/216733814-26945b8b-0454-4194-bc70-0441802a6c71.png">
</p>

https://user-images.githubusercontent.com/43219706/216746649-8ccecacc-9813-4130-8881-07ea596a1cc6.mov


<a href="https://www.buymeacoffee.com/diatasso" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Book" style="height: 40px !important;width: 145px !important;" ></a>

## Tool to bypass 403/401.
This script contain all the possible techniques to do the same. Performing HTTP status code checks on a list of URLs. It uses `cURL` to send HTTP requests to the specified URLs and analyzes the response to determine the status code and payload. Based on the status code, the script will print a message indicating the status and additional information, such as redirect location, if applicable. The results of the scan are appended to a file named "scan_results.txt".
## It will follow redirects, if any.

**NOTE** : 
* If you see multiple [200 Ok]/bypasses as output, you must check the Content-Length.
* If the content-length is same for multiple [200 Ok]/bypasses means false positive.
* Reason can be "301/302" or "../" [Payload] DON'T PANIC.
* Script will print `cURL` PAYLOAD if possible bypass found.


## Features
* Menu to control the different modules.
* Cleaner Script to strip out the garbage from the output file.
* Exploit Script to auto Exploit for you.


## Installation

```sh
1. Download or clone repository.
2. Move to your desired location (Make sure to the script and files are in the same location).
3. chmod +x *.sh on the folder.
4. ./wttb.sh to run the code.
NOTE: You will need `cURL` but it is usually in most OS now.
```
## License
GNU Affero General Public License v3.0

Donations to my broke a$$:
* Bitcoin (BTC) Address: bc1qa27kjjqacshg3szwvr5rr48dfwfdfrtyu8agd4

## Credits to: Dheeraj Madhukar for the original code!
https://github.com/Dheerajmadhukar/4-ZERO-3

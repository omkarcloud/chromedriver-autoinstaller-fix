# chromedriver-autoinstaller-fix

# DEPRECATED! The Official Respository [chromedriver-autoinstaller](https://github.com/yeongbin-jo/python-chromedriver-autoinstaller) has now been updated to address the issues with Chrome 115. We recommend using the official repository as it is better maintained than current chromedriver-autoinstaller-fix repository. You can find it [here](https://github.com/yeongbin-jo/python-chromedriver-autoinstaller)

The library `chromedriver-autoinstaller-fix` addresses and resolves certain issues present in the original [python-chromedriver-autoinstaller](https://github.com/yeongbin-jo/python-chromedriver-autoinstaller).

## Installation

```bash
pip install chromedriver-autoinstaller-fix
```

## Usage
Just type `import chromedriver_autoinstaller_fix` in the module you want to use chromedriver.

## Example
```
from selenium import webdriver
import chromedriver_autoinstaller_fix


chromedriver_autoinstaller_fix.install()  # Check if the current version of chromedriver exists
                                      # and if it doesn't exist, download it automatically,
                                      # then add chromedriver to path

driver = webdriver.Chrome()
driver.get("http://www.python.org")
assert "Python" in driver.title
```

## Would appreciate a Star :)

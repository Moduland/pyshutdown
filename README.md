# pyshutdown

----------
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/sepandhaghighi/pyshutdown/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/sepandhaghighi/pyshutdown/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/sepandhaghighi/pyshutdown/badges/build.png?b=master)](https://scrutinizer-ci.com/g/sepandhaghighi/pyshutdown/build-status/master)
[![PyPI version](https://badge.fury.io/py/shutdown.svg)](https://badge.fury.io/py/shutdown)	
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/sepandhaghighi/pyshutdown/blob/master/LICENSE)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/478dc165527b4c2fb67a336d7c88e7cd)](https://www.codacy.com/app/sepand-haghighi/pyshutdown?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=sepandhaghighi/pyshutdown&amp;utm_campaign=Badge_Grade)

						
Python shutdown library


Version : V1.1			
		

[Download](https://github.com/sepandhaghighi/pyshutdown/archive/v1.1.zip)

----------
## Installation ##
From source file :

`git clone https://github.com/sepandhaghighi/pyshutdown.git`
						
 `python setup.py install`

From PyPI:	
						
 `pip install shutdown`						

## Usage ##
- import shutdown lib `from shutdown import *`
- shutdown function `shutdown(time=your_time,force=False,warning_off=False)`
- restart function `restart(time=your_time,force=False)`
- hibernate function `hibernate(force=False)`
- logoff function `logoff(force=False)`
- cancel any shutdown process `cancel()`
![](http://www.shaghighi.ir/pyshutdown/shutdown.gif)

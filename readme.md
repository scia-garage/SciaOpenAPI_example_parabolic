- install python 3.7
- install python.net 
	- download https://ci.appveyor.com/project/pythonnet/pythonnet/branch/master/job/aqi7eyx1j0gcxcs0/artifacts
	- setup.py build
	- setup.py install
- write code
	- reference the Scia.OpenAPI.dll
			clr.AddReference(r"C:\SCIA\GIT\SEN\A\Bin\release32\Scia.OpenAPI.dll")

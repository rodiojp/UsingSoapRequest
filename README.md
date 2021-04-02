# UsingSoapRequest
Using Svcutil.exe to Generate a Client Class
Once you have set your environment variable, use Svcutil.exe to generate a client class. To do this, run the following from the command prompt:

svcutil /t:code /messageContract http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL /out:CountryInfoService.cs /config:CountryInfoService.config /namespace:*,UsingSoapRequestSvcUtil.CountryInfoService


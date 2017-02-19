# Google Translator

Documentation 

First download the script and copy it to your project folder

import the package by 

           import gtranslate

Initialize the translator module from the package

           translator_module = gtranslate.module("--API_KEY--")

Now use translate function with target parameter for successful translation

           translated_text = translator_module.translate("--TARGET LANGUAGE CODE--", "--TEXT TO BE TRANSLATED--")
           
 
 Note : Google Cloud Services restrict free access to certain limit. 'Daily Limit Exceeded' is a normal output for any unpaid services. Enable billing in your API console to avoid the error.

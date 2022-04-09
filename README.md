# sCountryCode-
#AutoIt3Wrapper_Au3Check_Parameters=-d -w 1 -w 2 -w 3 -w- 4 -w 5 -w 6 -w- 7  Local $sCountry = "Fiji" ConsoleWrite("ISO Country Code: " &amp; _CountryNameToISO($sCountry) &amp; @CR)  Func _CountryNameToISO($sCountry)     Local $sCountryCode     ;names and codes according to     ;http://www.iso.org/iso/country_codes/iso_3166_code_lists/country_names_and_code_elements.htm     ;updated in December 2013     If $sCountry = "AFGHANISTAN" Then $sCountryCode = "AF"     If $sCountry = "ÅLAND ISLANDS" Then $sCountryCode = "AX"     If $sCountry = "ALBANIA" Then $sCountryCode = "AL"     If $sCountry = "ALGERIA" Then $sCountryCode = "DZ"     If $sCountry = "AMERICAN SAMOA" Then $sCountryCode = "AS"     If $sCountry = "ANDORRA" Then $sCountryCode = "AD"     If $sCountry = "ANGOLA" Then $sCountryCode = "AO"     If $sCountry = "ANGUILLA" Then $sCountryCode = "AI"     If $sCountry = "ANTARCTICA" Then $sCountryCode = "AQ"     If $sCountry = "ANTIGUA AND BARBUDA" Then $sCountryCode = "AG"     If $sCountry = "ARGENTINA" Then $sCountryCode = "AR"     If $sCountry = "ARMENIA" Then $sCountryCode = "AM"     If $sCountry = "ARUBA" Then $sCountryCode = "AW"     If $sCountry = "AUSTRALIA" Then $sCountryCode = "AU"     If $sCountry = "AUSTRIA" Then $sCountryCode = "AT"     If $sCountry = "AZERBAIJAN" Then $sCountryCode = "AZ"     If $sCountry = "BAHAMAS" Then $sCountryCode = "BS"

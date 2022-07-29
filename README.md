#### Download
curl https://www.ecfr.gov/api/versioner/v1/full/2022-07-14/title-14.xml > /tmp/title-14.xml
#### Validate
xmllint --schema 14.xsd /tmp/title-14.xml --noout

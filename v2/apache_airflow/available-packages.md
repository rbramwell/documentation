---
title: Standard Available Packages
sidebar: platform_sidebar
---
Because each task is run in an individual Docker container, the available Python packages are set at the platform level. While you can add custom packages and remove unnecessary packages in our Enterprise Edition, our Cloud Edition comes with a standard set of packages available to all customers.

## Requesting a New Package
The Astronomer team is happy to add additional packages you need for your workflows. If you would like to have a package added, please just message us via the in-app chat with the package name. Note that because these packages will become standard for all customers using our Cloud Edition, we default to using the most recent version of the package.

## Currently Available Packages
-e git+https://github.com/astronomerio/incubator-airflow@astronomer-fixes-182#egg=apache-airflow[s3,postgres,mysql,mssql,password]   
-e git+https://github.com/astronomerio/simple-salesforce@master#egg=simple-salesforce   
-e git+https://github.com/astronomerio/PyPardot4.git#egg=pypardot

addict==2.1.0   
avro-python3==1.8.2  
backports.ssl-match-hostname==3.5.0.1  
beautifulsoup4==4.6.0    
bingads==11.5.2   
boa-str==1.0.1   
boto3==1.4.6   
botocore==1.6.8   
boxsdk==1.5.3   
cairocffi==0.8.0   
CairoSVG==2.0.3   
certifi==2017.7.27.1   
cffi==1.10.0   
chardet==3.0.4   
contextlib2==0.5.5   
coverage==4.4.1   
cryptography==1.7.2   
cssselect==1.0.1   
cssselect2==0.2.0   
cycler==0.10.0   
decorator==4.1.2   
docker-py==1.8.1   
docutils==0.14   
enum34==1.1.6   
facebookads==2.9.2   
flatten-json==0.1.6   
gensim==3.3.0   
google-api-core==0.1.4   
google-api-python-client==1.6.5   
google-cloud==0.30.0   
googleads==8.1.0   
html5lib==0.999999999   
http-parser==0.8.3   
httplib2==0.10.3   
idna==2.6   
ijson==2.6   
ipython-genutils==0.2.0   
jmespath==0.9.3   
jsonschema==2.6.0   
jupyter-core==4.3.0   
lxml==3.8.0   
marshmallow==2.13.6   
matplotlib==2.0.2   
nbformat==4.4.0   
nose2==0.6.5   
numpy==1.13.1   
oauth2client==4.1.2   
olefile==0.44   
openpyxl==2.4.8   
oauth2==1.9.0.post1   
pandas-gbq==0.2.1   
paramiko==2.4.0   
Pillow==4.2.1   
plotly==2.0.15   
pyasn1==0.3.4   
pyasn1-modules==0.1.4   
pycodestyle==2.3.1   
pycparser==2.18   
pydash==4.2.1   
pymesos==0.2.14   
pymongo==3.5.1   
pymssql==2.1.3   
pyodbc==4.0.21   
pyOpenSSL==17.2.0   
pyparsing==2.2.0   
Pyphen==0.9.4   
python-dateutil==2.6.1   
python-decouple==3.1   
python-intercom==3.1.0   
pytz==2017.2   
raven==6.1.0   
requests==2.18.4   
rsa==3.4.2   
s3transfer==0.1.11   
scikit-learn==0.19.1   
scipy==0.19.1   
singer-python==5.0.12   
six==1.10.0   
sklearn-pandas==1.6.0   
slackclient==1.0.7   
smart_open==1.5.5   
suds-jurko==0.6   
tap-github==0.2.3   
tap-fixerio==0.1.2   
target-csv==0.2.4   
target-gsheet==0.2.5   
target-json==0.0.11   
target-s3==0.1.0   
tinycss==0.4   
tinycss2==0.6.0   
traitlets==4.3.2   
twarc==1.3.4   
tweepy==3.5.0   
uritemplate==3.0.0   
urllib3==1.22   
WeasyPrint==0.40   
webencodings==0.5.1   
websocket-client==0.44.0   

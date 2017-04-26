# Capsule CRM - API Test

## Requirements

First of all I strongly suggest you to create a **virtual environment**:

    virtualenv env
    source env/bin/activate

Install the requirements (Be aware to have the virtualenv activated):
    
    pip install -r requirements
    
To have authenticated access to the API you need to create a custom TOKEN. Of course the production TOKEN must be secret!
You can create a personal TOKEN in your **Preferences** under the voice **API Authentication Tokens**.

You need to copy the file **secret.example** with a new name **secret**. Change inside this file the voice **TOKEN** with your token.

    cp secret.example secret
    vim secret

## Start

After the installation run on your terminal:

    jupyter notebook

And here we go!

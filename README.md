# TenantUnionPlus
A project for CS411.

A database-driven, web-based application that helps students of UIUC find ideal apartments.

Flask is used as the web framework.

server.py is the file where most parts of the code are.


# To start:
<!-- 0. run
    `source .bashrc`
    `export LC_ALL=en_US.utf-8`
    `export LANG=en_US.utf-8` -->
1. Goto TenantUnionPlus
2. run
    <!-- `npm -g install phantomjs-prebuilt` -->
    `pip install -r requirements.txt`
3. run the following:
    `pip install --editable .`
4. Goto TenantUnionPlus/TenantUnionPlusServer
5. run
    `export FLASK_APP=server.py`
    `export FLASK_DEBUG=true` // don't do this when launching the website to public.
    `flask run`
    `flask initdb`
OR: `python main.py`

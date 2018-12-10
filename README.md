# Installing locally from source

- Initialize a virtual env and activate it.

- then run from the package dierctory run
    
        > pip install -e .

# Usage

In the root \_\_init\_\_.py or any app initialization function do

    from flask import Flask
    from flask_tracer import FlaskTracer

    app = Flask(__name__)
    # initialize it like this
    FlaskTracer(app)


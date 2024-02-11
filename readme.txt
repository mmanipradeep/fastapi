C:\Users\mmani\OneDrive\Desktop\fastapi\fastapi-example> python -m uvicorn app.main:app --reload
pip install fastapi
pip install virtualapi
python -m venv fastapienv
activate  uvicorn server 
https://github.com/HighnessAtharva/fastapi-kimo/tree/master

11 feb 2024

pip install fastapi pymongo uvicorn starlette pydantic

pip install pytest 




BSON - Binary serialization format that is used in MongoDB for efficient data storage and retrieval. It comes bundled with PyMongo.
FastAPI - Web framework for creating Python APIs that offer high performance, automatic validation, interactive documentation, and support for async operations.
PyMongo -  Official MongoDB driver for Python. It serves as a high-level API for integrating MongoDB within Python.
Uvicorn - Primary ASGI server that improves application performance. It is responsible for server startup.
Starlette - ASGI framework that powers FastAPI and allows rapid prototyping development.
Pydantic - Integrated data validation and parsing library. We need it to create interactive API documentation while automatically validating incoming request data and enforcing data type rules.


python -m uvicorn main:app --reload
# Flask

#### Running flask applicaiton

```
$ python app.py
```

Things to consider
1. Preproces pipeline should match the one while training
2. Image formats should be decoded and put in the format our model takes as input
3. Once the values are predicted, the output should be in the required format.

**Note:** The default host and port is: `127.0.0.1:5000`

#### Request using curl

Sending an image to the server using POST request at a given url

```
$ curl -F "images@=sample.jpg" http://127.0.0.1:5000/predict/
```

#### Request using curl

You can use POSTMAN to make requests. check for details at ` https://www.postman.com/ `



#### Note
1. For serving with environment with GPU (Optional) set environment variable
> `$ export TF_FORCE_GPU_ALLOW_GROWTH=true`

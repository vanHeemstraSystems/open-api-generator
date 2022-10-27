# 100 - Create a New API

## 100 - Browse Swagger Hub

Go to the Swagger Hub (create an account if you do not already have an account) at https://app.swaggerhub.com/welcome

## 200 - Create a New API

On the landing page, choose to **Create a New API**

**NOTE**: For demonstration purposes we are going to (re-)create the example API called "**Petstore**" as can be seen at https://petstore3.swagger.io/api/v3/openapi.json

Enter a unique name for your API and select a Template. Select 'None' for a Blank API.

```
Owner: SOME_ORGANIZATION
```

*NOTE*: We created the SOME_ORGANIZATION organization beforehand, choose whichever name you have created instead.

```
Project: --- None ---
```

As we do not have a project yet, we cannot select a project, so the value will be *None*.

```
Specification: OpenAPI 3.0.x
```

```
Template: None
```

None, since we will be creating the API from scratch, not from a template.

```
Name: Petstore_3.0
```

```
Version: 1.0.0
```

```
Title: Petstore
```

```
Description: A Petstore
```

```
Visibility: Private
```

As long as we are in the creating phase of this API we will keep it ```Private``. This can be switched to ```Public``` at anytime.

```
Auto Mock API: Off
```

Confirm the form by clicking the button **Create API**.

## 300 - Edit the New API

With the Petstore API created in previous step, we will now see the following at https://app.swaggerhub.com/apis/SOME_ORGANIZATION/Petstore_3.0/1.0.0

```
openapi: 3.0.0
info:
  version: 1.0.0
  title: Petstore
  description: A Petstore
paths: {}  
```



*More following ...*

# HTTP Status Codes

This is a list of essential HTTP status codes

> Note: It is not a complete list but only the most important ones

## **200 OK**

- The request was successful

## **201 Created**

- The request was successful and a resource was created as a result

### 204 No Content

- The request was successful, but there is no representation to return (i.e. the response is empty)

### 301, 308 Permanent Redirect

- The requested resource has been assigned a new permanent URI

### 302, 307 Temporary Redirect

- The requested resource resides temporarily under a different URI

## **400 Bad Request**

- The request could not be understood or was missing required parameters

## **401 Unauthorized**

- Authentication failed or user does not have permissions for the requested operation

## **403 Forbidden**

- Authentication succeeded, but authenticated user does not have access to the requested resource

## **404 Not Found**

- The requested resource could not be found

### 410 Gone

- The requested resource is no longer available

## **500 Internal Server Error**

- An error occurred on the server

### 503 Service Unavailable

- The server is currently unavailable (overloaded or down for maintenance)

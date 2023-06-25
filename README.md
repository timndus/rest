# API Routes Documentation

This document provides an overview of the API routes and endpoints for managing comments, verified comments, and rejected comments.

## About This Document

This markdown file serves as a reference guide for developers working with the API. It outlines the available routes, HTTP methods, and parameters for each route. The document is structured into sections based on the different controllers responsible for handling the requests.

Each section includes the following details for each route:

- **HTTP Method**: The HTTP method used to interact with the route (e.g., GET, POST, PATCH, DELETE).
- **Route**: The URL path for accessing the route.
- **Parameters**: The parameters required or optional for the specific route.

# Comment Routes

## commentController@store
- **POST**: `/comment`
- Parameters:
  - `productId: 1`
  - `text: something`

## commentController@index
- **GET**: `/comment`
- **GET**: `/comment?productId=1`
- **GET**: `/comment?userId=1`
- **GET**: `/comment?productId=1&userId=1`

## commentController@show
- **GET**: `/comment/1`

## commentController@destroy
- **DELETE**: `/comment/1`

## commentController@update
- **PATCH**: `/comment/1`

---

# Verified Comment Routes

## verifiedComment@store
- **POST**: `/verified-comment`
- Parameters:
  - `id: 1`
  - `note: something`

## verifiedComment@index
- **GET**: `/verified-comment`
- **GET**: `/verified-comment?productId=1`
- **GET**: `/verified-comment?userId=1`
- **GET**: `/verified-comment?productId=1&userId=1`

## verifiedComment@show
- **GET**: `/verified-comment/1`

## verifiedComment@destroy
- **DELETE**: `/verified-comment/1`

## verifiedComment@update
- **PATCH**: `/verified-comment/1`
- Parameters:
  - `note: something1`

---

# Rejected Comment Routes

## rejectedComment@store
- **POST**: `/rejected-comment`
- Parameters:
  - `id: 1`
  - `reason: something`

## rejectedComment@index
- **GET**: `/rejected-comment`
- **GET**: `/rejected-comment?productId=1`
- **GET**: `/rejected-comment?userId=1`
- **GET**: `/rejected-comment?productId=1&userId=1`

## rejectedComment@show
- **GET**: `/rejected-comment/1`

## rejectedComment@destroy
- **DELETE**: `/rejected-comment/1`

## rejectedComment@update
- **PATCH**: `/rejected-comment/1`
- Parameters:
  - `reason: something1`

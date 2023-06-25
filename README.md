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

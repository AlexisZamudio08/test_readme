# FASTAPI Employee API

## This is a simple API for managing employees.

### This API support the following operations:
    READ: Return the list of employees.
    CREATE: Create a new employee.
#### Get all employees

```http
  GET /api/employees
```

| Parameter  | Type     | Description                 |
| :--------  | :------- | :-------------------------  |
| `api_key`  | `string` | **Required**. Your API key  |


#### POST employee

```http
  POST /api/employee
```

| Parameter  | Type     | Description                 |
| :--------  | :------- | :-------------------------  |
| `emp_name` | `string` | **Required**. Employee name |
| `emp_id`   | `int`    | **Required**. Employee id   |

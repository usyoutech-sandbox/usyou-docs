# Variables And Methods

The following document outlines the naming conventions that we follow at US&YOU LLC for variables and methods.

> **Note:** If the framework or tool you are using has specific naming conventions, you should follow those conventions instead of the ones outlined here.
{style="note"}

> **Warning:** Make sure to notify us if you use a different naming convention for variables and methods.
{style="warning"}


## Variable naming conventions

- Use lowercase letters for variable names.
- Use camelCase for variable names.
- Use descriptive names for variables.
- Avoid using special characters in variable names.
- Avoid using spaces in variable names.
- Avoid using abbreviations in variable names.
- Use the appropriate data type for the variable type.
- Use the following variable naming convention for different variable types:

  - **String variables**: `firstName`, `lastName`, `emailAddress`
  - **Number variables**: `age`, `height`, `weight`
  - **Boolean variables**: `isTrue`, `hasValue`, `isValid`
  - **Array variables**: `userList`, `productList`, `orderList`
  - **Object variables**: `userObject`, `productObject`, `orderObject`
  - **Function variables**: `getUserData`, `getProductData`, `getOrderData`
  - **Global variables**: `globalVariable`, `globalObject`, `globalFunction`
  - **Local variables**: `localVariable`, `localObject`, `localFunction`
  - **Constant variables**: `PI`, `E`, `G`, `SPEED_OF_LIGHT`
  - **Private variables**: `_privateVariable`, `_privateObject`, `_privateFunction`
  - **Protected variables**: `protectedVariable`, `protectedObject`, `protectedFunction`
  - **Public variables**: `publicVariable`, `publicObject`, `publicFunction`
  - **Static variables**: `staticVariable`, `staticObject`, `staticFunction`
  - **Final variables**: `finalVariable`, `finalObject`, `finalFunction`
  - **Instance variables**: `instanceVariable`, `instanceObject`, `instanceFunction`
  - **Class variables**: `classVariable`, `classObject`, `classFunction`
  - **Interface variables**: `interfaceVariable`, `interfaceObject`, `interfaceFunction`
  - **Abstract variables**: `abstractVariable`, `abstractObject`, `abstractFunction`
  - **Enum variables**: `enumVariable`, `enumObject`, `enumFunction`
  - **Annotation variables**: `annotationVariable`, `annotationObject`, `annotationFunction`
  - **Exception variables**: `exceptionVariable`, `exceptionObject`, `exceptionFunction`
  - **Error variables**: `errorVariable`, `errorObject`, `errorFunction`
  - **Warning variables**: `warningVariable`, `warningObject`, `warningFunction`
  - **Info variables**: `infoVariable`, `infoObject`, `infoFunction`
  - **Debug variables**: `debugVariable`, `debugObject`, `debugFunction`
  - **Trace variables**: `traceVariable`, `traceObject`, `traceFunction`
  - **Log variables**: `logVariable`, `logObject`, `logFunction`

### Examples {id="examples_variable"}

**Good**: `firstName`, `lastName`, `emailAddress`, `age`, `height`, `weight`, `isTrue`, `hasValue`, `isValid`, `userList`, `productList`, `orderList`, `userObject`, `productObject`, `orderObject`, `getUserData`, `getProductData`, `getOrderData`, `globalVariable`, `globalObject`, `globalFunction`, `localVariable`, `localObject`, `localFunction`, `PI`, `E`, `G`, `SPEED_OF_LIGHT`, `_privateVariable`, `_privateObject`, `_privateFunction`, `protectedVariable`, `protectedObject`, `protectedFunction`, `publicVariable`, `publicObject`, `publicFunction`, `staticVariable`, `staticObject`, `staticFunction`, `finalVariable`, `finalObject`, `finalFunction`, `instanceVariable`, `instanceObject`, `instanceFunction`, `classVariable`, `classObject`, `classFunction`, `interfaceVariable`, `interfaceObject`, `interfaceFunction`, `abstractVariable`, `abstractObject`, `abstractFunction`, `enumVariable`, `enumObject`, `enumFunction`, `annotationVariable`, `annotationObject`, `annotationFunction`, `exceptionVariable`, `exceptionObject`, `exceptionFunction`, `errorVariable`, `errorObject`, `errorFunction`, `warningVariable`, `warningObject`, `warningFunction`, `infoVariable`, `infoObject`, `infoFunction`, `debugVariable`, `debugObject`, `debugFunction`, `traceVariable`, `traceObject`, `traceFunction`, `logVariable`, `logObject`, `logFunction`

**Bad**: `FirstName`, `LastName`, `EmailAddress`, `Age`, `Height`, `Weight`, `IsTrue`, `HasValue`, `IsValid`, `UserList`, `ProductList`, `OrderList`, `UserObject`, `ProductObject`, `OrderObject`, `GetUserData`, `GetProductData`, `GetOrderData`, `GlobalVariable`, `GlobalObject`, `GlobalFunction`, `LocalVariable`, `LocalObject`, `LocalFunction`, `Pi`, `E`, `G`, `SpeedOfLight`, `_PrivateVariable`, `_PrivateObject`, `_PrivateFunction`, `ProtectedVariable`, `ProtectedObject`, `ProtectedFunction`, `PublicVariable`, `PublicObject`, `PublicFunction`, `StaticVariable`, `StaticObject`, `StaticFunction`, `FinalVariable`, `FinalObject`, `FinalFunction`, `InstanceVariable`, `InstanceObject`, `InstanceFunction`, `ClassVariable`, `ClassObject`, `ClassFunction`, `InterfaceVariable`, `InterfaceObject`, `InterfaceFunction`, `AbstractVariable`, `AbstractObject`, `AbstractFunction`, `EnumVariable`, `EnumObject`, `EnumFunction`, `AnnotationVariable`, `AnnotationObject`, `AnnotationFunction`, `ExceptionVariable`, `ExceptionObject`, `ExceptionFunction`, `ErrorVariable`, `ErrorObject`, `ErrorFunction`, `WarningVariable`, `WarningObject`, `WarningFunction`, `InfoVariable`, `InfoObject`, `InfoFunction`, `DebugVariable`, `DebugObject`, `DebugFunction`, `TraceVariable`, `TraceObject`, `TraceFunction`, `LogVariable`, `LogObject`, `LogFunction`

## Method naming conventions

- Use lowercase letters for method names.
- Use camelCase for method names.
- Use descriptive names for methods.
- Avoid using special characters in method names.
- Avoid using spaces in method names.
- Avoid using abbreviations in method names.
- Use the appropriate return type for the method type.


### Examples {id="examples_method"}

**Good**: `getUserData`, `getProductData`, `getOrderData`, `setUserData`, `setProductData`, `setOrderData`, `addUserData`, `addProductData`, `addOrderData`, `deleteUserData`, `deleteProductData`, `deleteOrderData`, `updateUserData`, `updateProductData`, `updateOrderData`, `validateUserData`, `validateProductData`, `validateOrderData`, `getUserList`, `getProductList`, `getOrderList`, `setUserList`, `setProductList`, `setOrderList`, `addUserList`, `addProductList`, `addOrderList`, `deleteUserList`, `deleteProductList`, `deleteOrderList`, `updateUserList`, `updateProductList`, `updateOrderList`, `validateUserList`, `validateProductList`, `validateOrderList`, `getUserObject`, `getProductObject`, `getOrderObject`, `setUserObject`, `setProductObject`, `setOrderObject`, `addUserObject`, `addProductObject`, `addOrderObject`, `deleteUserObject`, `deleteProductObject`, `deleteOrderObject`, `updateUserObject`, `updateProductObject`, `updateOrderObject`, `validateUserObject`, `validateProductObject`, `validateOrderObject`, `getUserFunction`, `getProductFunction`, `getOrderFunction`, `setUserFunction`, `setProductFunction`, `setOrderFunction`, `addUserFunction`, `addProductFunction`, `addOrderFunction`, `deleteUserFunction`, `deleteProductFunction`, `deleteOrderFunction`, `updateUserFunction`, `updateProductFunction`, `updateOrderFunction`, `validateUserFunction`, `validateProductFunction`, `validateOrderFunction`

**Bad**: `GetUserData`, `GetProductData`, `GetOrderData`, `SetUserData`, `SetProductData`, `SetOrderData`, `AddUserData`, `AddProductData`, `AddOrderData`, `DeleteUserData`, `DeleteProductData`, `DeleteOrderData`, `UpdateUserData`, `UpdateProductData`, `UpdateOrderData`, `ValidateUserData`, `ValidateProductData`, `ValidateOrderData`, `GetUserList`, `GetProductList`, `GetOrderList`, `SetUserList`, `SetProductList`, `SetOrderList`, `AddUserList`, `AddProductList`, `AddOrderList`, `DeleteUserList`, `DeleteProductList`, `DeleteOrderList`, `UpdateUserList`, `UpdateProductList`, `UpdateOrderList`, `ValidateUserList`, `ValidateProductList`, `ValidateOrderList`, `GetUserObject`, `GetProductObject`, `GetOrderObject`, `SetUserObject`, `SetProductObject`, `SetOrderObject`, `AddUserObject`, `AddProductObject`, `AddOrderObject`, `DeleteUserObject`, `DeleteProductObject`, `DeleteOrderObject`, `UpdateUserObject`, `UpdateProductObject`, `UpdateOrderObject`, `ValidateUserObject`, `ValidateProductObject`, `ValidateOrderObject`, `GetUserFunction`, `GetProductFunction`, `GetOrderFunction`, `SetUserFunction`, `SetProductFunction`, `SetOrderFunction`, `AddUserFunction`, `AddProductFunction`, `AddOrderFunction`, `DeleteUserFunction`, `DeleteProductFunction`, `DeleteOrderFunction`, `UpdateUserFunction`, `UpdateProductFunction`, `UpdateOrderFunction`, `ValidateUserFunction`, `ValidateProductFunction`, `ValidateOrderFunction`


## Exceptions

> **Note:** For DTOs, use the following naming convention:
> 
> `data_transfer_object`
> 
> This is only for DTOs from API requests and responses.
{style="note"}

> **Note:** For routes, use the following naming convention:
> 
> `route-name`
{style="note"}




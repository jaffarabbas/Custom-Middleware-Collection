
## Global Exception Handler Middleware

For handling exception in webapi globally 

```
app.UseGlobalErrorHandler();
```


## Validate JWT Token Middleware

For Validating Token on api hit

```
app.UseValidateTokenHandler(builder.Configuration?.GetSection("JWTSetting")?.GetValue<string>("securitykey")!);
```


## Global Exception Handler Middleware

For handling exception in webapi globally 

```http
app.UseGlobalErrorHandler();
```

## Validate JWT Token Middleware

For Validating Token on api hit

```http
app.UseValidateTokenHandler(builder.Configuration?.GetSection("JWTSetting")?.GetValue<string>("securitykey")!);
```

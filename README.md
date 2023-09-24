
## Global Exception Handler Middleware

For handling exception in webapi globally 

```
app.UseGlobalErrorHandler();
```


## Validate JWT Token Middleware

For Validating Token on api hit 

## Faq

This Middleware is for simple JWT token validation not for role base authentication

```
app.UseValidateTokenHandler(builder.Configuration?.GetSection("JWTSetting")?.GetValue<string>("securitykey")!);
```

## Tech Stack

**Client:** .Net Core 7



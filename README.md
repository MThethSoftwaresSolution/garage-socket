## Paygate Bouncer

This service ensures that you don't miss the Paygate POST `Notify` data.

```xml 
<Redirect>
    <NotifyUrl>https://garage-uat.azurewebsites.net/#/secured-garage/notify</NotifyUrl>
    <ReturnUrl>https://garage-uat.azurewebsites.net/#/secured-garage/return</ReturnUrl>
</Redirect>
```

### NotifyUrl
This is the URL on your site that PayHost will post the final transaction result to. 
This attribute must only be passed if you intend to use PayHost with 3D Secure using PayGate’s MPI or PayHost redirect solution.

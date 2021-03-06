---
title: 'View'
linkTitle: 'View'
description: >
  Learn how to inspect a secret.
---

## Function

```go
func (svc *SecretService) Get(engine, sType, org, name, secret string) (*library.Secret, *Response, error)
```

{{% alert color="info" %}}
For more information, you can view our [go documentation](https://godoc.org/github.com/go-vela/sdk-go/vela#SecretService.Get).
{{% /alert %}}

## Parameters

The following parameters are used to configure the endpoint:

| Name     | Description                |
| -------- | -------------------------- |
| `engine` | name of engine for secret  |
| `sType`  | name of type of secret     |
| `org`    | name of organization       |
| `name`   | name of repository or team |
| `secret` | name of secret             |

## Permissions

COMING SOON!

## Responses

| Status Code | Description                                         |
| ----------- | --------------------------------------------------- |
| `200`       | indicates the request has succeeded                 |
| `401`       | indicates the user does not have proper permissions |

## Sample

{{% alert color="warning" %}}
This section assumes you already know how to authenticate with the SDK.

To authenticate with the SDK, please review the [authentication documentation](/docs/sdk/go/authentication/).
{{% /alert %}}

You can find an example of this function [here](https://godoc.org/github.com/go-vela/sdk-go/vela#example-SecretService-Get).

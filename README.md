# dnspod
dnspod dns provider for Caddy

==============

These providers can be used to help solve the ACME DNS challenge by plugging them into Caddy 0.9 and newer:

```go
import _ "github.com/mukaiu/caddy-dnspod"
```

You can then use this in your Caddyfile with the `tls` directive like so:

```plain
tls {
	dns <provider>
}

Set environment DNSPOD_API_KEY with your account token

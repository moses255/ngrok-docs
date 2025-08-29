<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-08-29T10:07:53Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2tqobeytoktbfxbsg.local-ngrok-cname.com",
      "created_at": "2025-08-29T10:07:53Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31xO5W2gT6k5FvxvVwr0iTtXQMc",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31xO5W2gT6k5FvxvVwr0iTtXQMc"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_31xO5JXnkVhjYxE3rXKmmLHpTjV",
        "uri": "https://api.ngrok.com/tls_certificates/cert_31xO5JXnkVhjYxE3rXKmmLHpTjV"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2tqobeytoktbfxbsg.local-ngrok-cname.com",
      "created_at": "2025-08-29T10:07:52Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31xO5RL0gVGdgMa774qRYzhOwN8",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31xO5RL0gVGdgMa774qRYzhOwN8"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-29T10:07:22Z",
      "description": "Your dev domain",
      "domain": "real-neatly-ladybird.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31xO1YEynlYeMhqngeJbUhEEZY5",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31xO1YEynlYeMhqngeJbUhEEZY5"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```

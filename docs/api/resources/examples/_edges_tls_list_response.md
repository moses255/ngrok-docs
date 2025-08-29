<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-29T10:08:21Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_31xO90uYOGQdvFNxorL92t8sqlC",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31xO90uYOGQdvFNxorL92t8sqlC"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_31xO7ShFazX32QOJn7XOZsJog0L",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_31xO7ShFazX32QOJn7XOZsJog0L"
        },
        "enabled": true
      },
      "created_at": "2025-08-29T10:08:09Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_31xO7WtJVkM9oCDQVNlFj67IoNb",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31xO7WtJVkM9oCDQVNlFj67IoNb"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```

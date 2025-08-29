<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-29T10:08:14Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_31xO7X99qvKKbZTpPhZcnDObW5r",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31xO7X99qvKKbZTpPhZcnDObW5r"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31xO8AHB1wyJboeQ3fhjk9FbwA4",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-29T10:08:14Z",
      "uri": "https://api.ngrok.com/endpoints/ep_31xO8AHB1wyJboeQ3fhjk9FbwA4",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-29T10:08:12Z",
      "hostport": "2ef15b041d7c.ngrok.paid:443",
      "id": "ep_31xO7rxZ2ZCZYw0c7Qq1OIdLXaD",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_31xO19HNjFNspBByhRAhWgJBHJz",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://2ef15b041d7c.ngrok.paid",
      "tunnel": {
        "id": "tn_31xO7rxZ2ZCZYw0c7Qq1OIdLXaD",
        "uri": "https://api.ngrok.com/tunnels/tn_31xO7rxZ2ZCZYw0c7Qq1OIdLXaD"
      },
      "tunnel_session": {
        "id": "ts_31xO7rjKX4RqsuBJcisbWxZb09T",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_31xO7rjKX4RqsuBJcisbWxZb09T"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-29T10:08:12Z",
      "upstream_url": "http://localhost:80",
      "url": "https://2ef15b041d7c.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-29T10:08:09Z",
      "domain": {
        "id": "rd_31xO7X99qvKKbZTpPhZcnDObW5r",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31xO7X99qvKKbZTpPhZcnDObW5r"
      },
      "edge": {
        "id": "edgtls_31xO7WtJVkM9oCDQVNlFj67IoNb",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_31xO7WtJVkM9oCDQVNlFj67IoNb"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31xO7QpBiiUqD8fXhfHPGwd6BiU",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-29T10:08:09Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```

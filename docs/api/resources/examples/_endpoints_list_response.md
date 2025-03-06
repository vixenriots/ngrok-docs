<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-03-06T10:14:28Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2twH9HIjAWYZOFtNirEDGMiYcXx",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2twH9HIjAWYZOFtNirEDGMiYcXx"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2twH9sC7lyelUcFzmbSAaWGi6PJ",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-03-06T10:14:28Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2twH9sC7lyelUcFzmbSAaWGi6PJ",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-06T10:14:27Z",
			"hostport": "df7354d83711.ngrok.paid:443",
			"id": "ep_2twH9mrdqn8n3ENcipGH7Fwr8DZ",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2twH7L21ijQufZ77JLWW1ahzcQp",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://df7354d83711.ngrok.paid",
			"tunnel": {
				"id": "tn_2twH9mrdqn8n3ENcipGH7Fwr8DZ",
				"uri": "https://api.ngrok.com/tunnels/tn_2twH9mrdqn8n3ENcipGH7Fwr8DZ"
			},
			"tunnel_session": {
				"id": "ts_2twH9k2b5R1JhExOQAJrJQ2m0nO",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2twH9k2b5R1JhExOQAJrJQ2m0nO"
			},
			"type": "ephemeral",
			"updated_at": "2025-03-06T10:14:27Z",
			"upstream_url": "http://localhost:80",
			"url": "https://df7354d83711.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-06T10:14:24Z",
			"domain": {
				"id": "rd_2twH9HIjAWYZOFtNirEDGMiYcXx",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2twH9HIjAWYZOFtNirEDGMiYcXx"
			},
			"edge": {
				"id": "edgtls_2twH9J80barXEMKXQr4nKvAMWoW",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2twH9J80barXEMKXQr4nKvAMWoW"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2twH9KV5rm9dC7pzGjlmiOzY1xa",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-03-06T10:14:24Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```

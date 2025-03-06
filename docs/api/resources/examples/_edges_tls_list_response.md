<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-03-06T10:14:34Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2twHAglTCaTm0s1p2s7aHEKWc3o",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2twHAglTCaTm0s1p2s7aHEKWc3o"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2twH9GkLFBZE2UHW9n8TJyh6l4C",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2twH9GkLFBZE2UHW9n8TJyh6l4C"
				},
				"enabled": true
			},
			"created_at": "2025-03-06T10:14:23Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2twH9J80barXEMKXQr4nKvAMWoW",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2twH9J80barXEMKXQr4nKvAMWoW"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```

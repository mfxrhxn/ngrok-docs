<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-01T10:06:24Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pbvRvoZSdcgXytG3UBUEBoXkDG",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pbvRvoZSdcgXytG3UBUEBoXkDG"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pbvQEWcGYN6QX632lpudkGPBG3",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pbvQEWcGYN6QX632lpudkGPBG3"
				},
				"enabled": true
			},
			"created_at": "2024-12-01T10:06:11Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pbvQLDBef7TfhQKxbL0HZMB29c",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pbvQLDBef7TfhQKxbL0HZMB29c"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```

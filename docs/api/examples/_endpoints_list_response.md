<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-01T10:06:15Z",
			"hostport": "410f434c063d.ngrok.paid:443",
			"id": "ep_2pbvQjLXfWXc3fzK67qxoJavA3G",
			"name": "command_line",
			"principal": {
				"id": "usr_2pbvOI7jRxTIJebfSTATPOaUttz",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://410f434c063d.ngrok.paid",
			"tunnel": {
				"id": "tn_2pbvQjLXfWXc3fzK67qxoJavA3G",
				"uri": "https://api.ngrok.com/tunnels/tn_2pbvQjLXfWXc3fzK67qxoJavA3G"
			},
			"tunnel_session": {
				"id": "ts_2pbvQnK77XKwnq6yJHGj7V6DFZM",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pbvQnK77XKwnq6yJHGj7V6DFZM"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-01T10:06:15Z",
			"upstream_url": "http://localhost:80",
			"url": "https://410f434c063d.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-01T10:06:12Z",
			"domain": {
				"id": "rd_2pbvQG3R0NJbjDSyC2YG2gsQsq1",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pbvQG3R0NJbjDSyC2YG2gsQsq1"
			},
			"edge": {
				"id": "edgtls_2pbvQLDBef7TfhQKxbL0HZMB29c",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pbvQLDBef7TfhQKxbL0HZMB29c"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pbvQQvhwTbKol2YbnZQXVKpfEF",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-01T10:06:12Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```

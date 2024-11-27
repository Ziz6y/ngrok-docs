<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-11-27T10:07:12Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pQd3MvRA8y6dII9USb75KQZeJV",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pQd3MvRA8y6dII9USb75KQZeJV"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pQd1tVBq19qgD5sMxhcVKDYvtd",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pQd1tVBq19qgD5sMxhcVKDYvtd"
				},
				"enabled": true
			},
			"created_at": "2024-11-27T10:07:01Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pQd1vrX0dhyoKgORjqU69a09b0",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pQd1vrX0dhyoKgORjqU69a09b0"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```

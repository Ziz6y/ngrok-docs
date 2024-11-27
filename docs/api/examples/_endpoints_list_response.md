<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-11-27T10:07:01Z",
			"domain": {
				"id": "rd_2pQd20qm1NYlrLiHt4umfhJmOC5",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pQd20qm1NYlrLiHt4umfhJmOC5"
			},
			"edge": {
				"id": "edgtls_2pQd1vrX0dhyoKgORjqU69a09b0",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pQd1vrX0dhyoKgORjqU69a09b0"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pQd21BOe9se6BcM0zfdb7oOHN6",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-11-27T10:07:01Z"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-11-27T10:07:04Z",
			"hostport": "1e5f1e82a806.ngrok.paid:443",
			"id": "ep_2pQd2IlpGjtL4WCSXAv9unjvvYD",
			"name": "command_line",
			"principal": {
				"id": "usr_2pQczxWAKslcYlshp5l1M2Ndftf",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://1e5f1e82a806.ngrok.paid",
			"tunnel": {
				"id": "tn_2pQd2IlpGjtL4WCSXAv9unjvvYD",
				"uri": "https://api.ngrok.com/tunnels/tn_2pQd2IlpGjtL4WCSXAv9unjvvYD"
			},
			"tunnel_session": {
				"id": "ts_2pQd2IQ0nltZPMioB7Rwkzjlbjm",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pQd2IQ0nltZPMioB7Rwkzjlbjm"
			},
			"type": "ephemeral",
			"updated_at": "2024-11-27T10:07:04Z",
			"upstream_url": "http://localhost:80",
			"url": "https://1e5f1e82a806.ngrok.paid"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```

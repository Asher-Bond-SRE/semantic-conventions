<!-- NOTE: THIS FILE IS AUTOGENERATED. DO NOT EDIT BY HAND. -->
<!-- see templates/registry/markdown/attribute_namespace.md.j2 -->

# SignalR

## SignalR Attributes

SignalR attributes

| Attribute | Type | Description | Examples | Stability |
|---|---|---|---|---|
| <a id="signalr-connection-status" href="#signalr-connection-status">`signalr.connection.status`</a> | string | SignalR HTTP connection closure status. | `app_shutdown`; `timeout` | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |
| <a id="signalr-transport" href="#signalr-transport">`signalr.transport`</a> | string | [SignalR transport type](https://github.com/dotnet/aspnetcore/blob/main/src/SignalR/docs/specs/TransportProtocols.md) | `web_sockets`; `long_polling` | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |

---

`signalr.connection.status` has the following list of well-known values. If one of them applies, then the respective value MUST be used; otherwise, a custom value MAY be used.

| Value  | Description | Stability |
|---|---|---|
| `app_shutdown` | The connection was closed because the app is shutting down. | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |
| `normal_closure` | The connection was closed normally. | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |
| `timeout` | The connection was closed due to a timeout. | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |

---

`signalr.transport` has the following list of well-known values. If one of them applies, then the respective value MUST be used; otherwise, a custom value MAY be used.

| Value  | Description | Stability |
|---|---|---|
| `long_polling` | LongPolling protocol | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |
| `server_sent_events` | ServerSentEvents protocol | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |
| `web_sockets` | WebSockets protocol | ![Stable](https://img.shields.io/badge/-stable-lightgreen) |

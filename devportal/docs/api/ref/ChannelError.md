---
id: ChannelError
sidebar_label: ChannelError
title: ChannelError
hide_title: true
---
# `ChannelError`

```typescript
enum ChannelError {
  NoChannelFound = "NoChannelFound",
  AccessDenied = "AccessDenied",
  CreationFailed = "CreationFailed"
}
```

Contains constants representing the errors that can be encountered when calling channels using the [`joinChannel`](DesktopAgent#joinchannel) or [`getOrCreateChannel`](DesktopAgent#getorcreatechannel) methods, or the [`getCurrentContext`](Channel#getcurrentcontext), [`broadcast`](Channel#broadcast) or [`addContextListener`](Channel#addcontextlistener) methods on the `Channel` object.

#### See also
* [`DesktopAgent.joinChannel`](DesktopAgent#joincannel)
* [`DesktopAgent.getOrCreateChannel`](DesktopAgent#getorcreatechannel)
* [`Channel.broadcast`](Channel#broadcast)
* [`Channel.addContextListener`](Channel#addcontextlistener)
* [`Channel.getCurrentContext`](Channel#getcurrentcontext)
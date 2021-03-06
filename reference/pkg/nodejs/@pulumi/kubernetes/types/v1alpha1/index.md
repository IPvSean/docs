---
title: Module types/v1alpha1
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../../index.html">@pulumi/kubernetes</a> &gt; <a href="../index.html">types</a> &gt; v1alpha1

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#isAuditSink">function isAuditSink</a>
* <a href="#isAuditSinkList">function isAuditSinkList</a>
* <a href="#AuditSink">interface AuditSink</a>
* <a href="#AuditSinkList">interface AuditSinkList</a>
* <a href="#AuditSinkSpec">interface AuditSinkSpec</a>
* <a href="#Policy">interface Policy</a>
* <a href="#ServiceReference">interface ServiceReference</a>
* <a href="#Webhook">interface Webhook</a>
* <a href="#WebhookClientConfig">interface WebhookClientConfig</a>
* <a href="#WebhookThrottleConfig">interface WebhookThrottleConfig</a>

<a href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts">types/input.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="isAuditSink">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4499">function <b>isAuditSink</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>isAuditSink(o: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>

</div>
<h2 class="pdoc-module-header" id="isAuditSinkList">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4533">function <b>isAuditSinkList</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>isAuditSinkList(o: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>

</div>
<h2 class="pdoc-module-header" id="AuditSink">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4472">interface <b>AuditSink</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

AuditSink represents a cluster level audit sink

<h3 class="pdoc-member-header" id="AuditSink-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4479">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>apiVersion?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='s2'>"auditregistration.k8s.io/v1alpha1"</span>&gt;;</pre>

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

</div>
<h3 class="pdoc-member-header" id="AuditSink-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4487">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>kind?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='s2'>"AuditSink"</span>&gt;;</pre>

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

</div>
<h3 class="pdoc-member-header" id="AuditSink-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4490">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>metadata?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#ObjectMeta'>ObjectMeta</a>&gt;;</pre>
</div>
<h3 class="pdoc-member-header" id="AuditSink-spec">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4495">property <b>spec</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>spec?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#AuditSinkSpec'>AuditSinkSpec</a>&gt;;</pre>

Spec defines the audit configuration spec

</div>
</div>
<h2 class="pdoc-module-header" id="AuditSinkList">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4506">interface <b>AuditSinkList</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

AuditSinkList is a list of AuditSink items.

<h3 class="pdoc-member-header" id="AuditSinkList-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4518">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>apiVersion?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='s2'>"auditregistration.k8s.io/v1alpha1"</span>&gt;;</pre>

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

</div>
<h3 class="pdoc-member-header" id="AuditSinkList-items">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4510">property <b>items</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>items: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#AuditSink'>AuditSink</a>&gt;[]&gt;;</pre>

List of audit configurations.

</div>
<h3 class="pdoc-member-header" id="AuditSinkList-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4526">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>kind?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='s2'>"AuditSinkList"</span>&gt;;</pre>

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

</div>
<h3 class="pdoc-member-header" id="AuditSinkList-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4529">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>metadata?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#ListMeta'>ListMeta</a>&gt;;</pre>
</div>
</div>
<h2 class="pdoc-module-header" id="AuditSinkSpec">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4540">interface <b>AuditSinkSpec</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

AuditSinkSpec holds the spec for the audit sink

<h3 class="pdoc-member-header" id="AuditSinkSpec-policy">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4544">property <b>policy</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>policy: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#Policy'>Policy</a>&gt;;</pre>

Policy defines the policy for selecting which events should be sent to the webhook required

</div>
<h3 class="pdoc-member-header" id="AuditSinkSpec-webhook">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4549">property <b>webhook</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>webhook: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#Webhook'>Webhook</a>&gt;;</pre>

Webhook to send events required

</div>
</div>
<h2 class="pdoc-module-header" id="Policy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4557">interface <b>Policy</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

Policy defines the configuration of how audit events are logged

<h3 class="pdoc-member-header" id="Policy-level">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4562">property <b>level</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>level: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

The Level that all requests are recorded at. available options: None, Metadata, Request,
RequestResponse required

</div>
<h3 class="pdoc-member-header" id="Policy-stages">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4567">property <b>stages</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>stages?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</pre>

Stages is a list of stages for which events are created.

</div>
</div>
<h2 class="pdoc-module-header" id="ServiceReference">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4575">interface <b>ServiceReference</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

ServiceReference holds a reference to Service.legacy.k8s.io

<h3 class="pdoc-member-header" id="ServiceReference-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4579">property <b>name</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>name: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

`name` is the name of the service. Required

</div>
<h3 class="pdoc-member-header" id="ServiceReference-namespace">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4584">property <b>namespace</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>namespace: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

`namespace` is the namespace of the service. Required

</div>
<h3 class="pdoc-member-header" id="ServiceReference-path">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4589">property <b>path</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>path?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

`path` is an optional URL path which will be sent in any request to this service.

</div>
</div>
<h2 class="pdoc-module-header" id="Webhook">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4597">interface <b>Webhook</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

Webhook holds the configuration of the webhook

<h3 class="pdoc-member-header" id="Webhook-clientConfig">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4601">property <b>clientConfig</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>clientConfig: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#WebhookClientConfig'>WebhookClientConfig</a>&gt;;</pre>

ClientConfig holds the connection parameters for the webhook required

</div>
<h3 class="pdoc-member-header" id="Webhook-throttle">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4606">property <b>throttle</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>throttle?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#WebhookThrottleConfig'>WebhookThrottleConfig</a>&gt;;</pre>

Throttle holds the options for throttling the webhook

</div>
</div>
<h2 class="pdoc-module-header" id="WebhookClientConfig">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4614">interface <b>WebhookClientConfig</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

WebhookClientConfig contains the information to make a connection with the webhook

<h3 class="pdoc-member-header" id="WebhookClientConfig-caBundle">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4619">property <b>caBundle</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>caBundle?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

`caBundle` is a PEM encoded CA bundle which will be used to validate the webhook's server
certificate. If unspecified, system trust roots on the apiserver are used.

</div>
<h3 class="pdoc-member-header" id="WebhookClientConfig-service">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4629">property <b>service</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>service?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='#ServiceReference'>ServiceReference</a>&gt;;</pre>

`service` is a reference to the service for this webhook. Either `service` or `url` must be
specified.

If the webhook is running within the cluster, then you should use `service`.

Port 443 will be used if it is open, otherwise it is an error.

</div>
<h3 class="pdoc-member-header" id="WebhookClientConfig-url">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4653">property <b>url</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>url?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

`url` gives the location of the webhook, in standard URL form (`scheme://host:port/path`).
Exactly one of `url` or `service` must be specified.

The `host` should not refer to a service running in the cluster; use the `service` field
instead. The host might be resolved via external DNS in some apiservers (e.g.,
`kube-apiserver` cannot resolve in-cluster DNS as that would be a layering violation).
`host` may also be an IP address.

Please note that using `localhost` or `127.0.0.1` as a `host` is risky unless you take
great care to run this webhook on all hosts which run an apiserver which might need to make
calls to this webhook. Such installs are likely to be non-portable, i.e., not easy to turn
up in a new cluster.

The scheme must be "https"; the URL must begin with "https://".

A path is optional, and if present may be any string permissible in a URL. You may use the
path to pass an arbitrary string to the webhook, for example, a cluster identifier.

Attempting to use a user or basic auth e.g. "user:password@" is not allowed. Fragments
("#...") and query parameters ("?...") are not allowed, either.

</div>
</div>
<h2 class="pdoc-module-header" id="WebhookThrottleConfig">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4661">interface <b>WebhookThrottleConfig</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

WebhookThrottleConfig holds the configuration for throttling events

<h3 class="pdoc-member-header" id="WebhookThrottleConfig-burst">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4665">property <b>burst</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>burst?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span>&gt;;</pre>

ThrottleBurst is the maximum number of events sent at the same moment default 15 QPS

</div>
<h3 class="pdoc-member-header" id="WebhookThrottleConfig-qps">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/types/input.ts#L4670">property <b>qps</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>qps?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span>&gt;;</pre>

ThrottleQPS maximum number of batches per second default 10 QPS

</div>
</div>

# Behavior Summary [2023-12-19 13:05:09 UTC]


## Workload Information 
>**Cluster**:   
>**Namespace**:   
>**Type/Name**: statefulset/N/A  

### Process/File Summary

<table><tr><th>Source Path</th><th>Destination Path</th><th>Delta</th></tr><tr><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl_child_setup</code></td><td><code><strong>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/inet_gethost</strong></code></td><td>

```diff
-/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/inet_gethost
```
</td></tr><tr><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl_child_setup</code></td><td><code><strong>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/this_is_ghost_now</strong></code></td><td>

```diff
+/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/this_is_ghost_now
```
</td></tr><tr><td><code>/bin/dash</code></td><td><code><strong>/usr/bin/basename</strong></code></td><td>

```diff
-/usr/bin/basename
```
</td></tr><tr><td><code>/bin/dash</code></td><td><code><strong>/usr/whcihbin/basename</strong></code></td><td>

```diff
+/usr/whcihbin/basename
```
</td></tr><tr><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code></td><td><code><strong>/usr/bin/dirname</strong></code></td><td>

```diff
-/usr/bin/dirname
```
</td></tr><tr><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code></td><td><code><strong>/usr/dustbin/dirname</strong></code></td><td>

```diff
+/usr/dustbin/dirname
```
</td></tr></table>

### Ingress Connections

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Delta</th></tr><tr><td><code>TCPv6</code></td><td><code>N/A</code></td><td><code><strong>10.4.3.119</strong></code></td><td><code>5672</code></td><td>

```diff
-10.4.3.119
```
</td></tr>
<tr><td><code>TCPv6</code></td><td><code>N/A</code></td><td><code><strong>10.4.3.8000</strong></code></td><td><code>5672</code></td><td>

```diff
+10.4.3.8000
```
</td></tr>
</table>

### Egress Connections

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Delta</th></tr><tr><td><code>UDP</code></td><td><code><strong>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</strong></code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
-/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp
```
</td></tr>
<tr><td><code>UDP</code></td><td><code><strong>/opt/japanwhojapani/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</strong></code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
+/opt/japanwhojapani/erlang/lib/erlang/erts-14.1.1/bin/beam.smp
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>127.0.0.1</code></td><td><code><strong>8000</strong></code></td><td>

```diff
+8000
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code><strong>127.0.0.1</strong></code></td><td><code>4369</code></td><td>

```diff
-127.0.0.1
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code><strong>127.0.1.1</strong></code></td><td><code>4369</code></td><td>

```diff
+127.0.1.1
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code><strong>127.0.2.1</strong></code></td><td><code>4369</code></td><td>

```diff
+127.0.2.1
```
</td></tr>
<tr><td><code>UDP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
-0
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code>127.0.2.1</code></td><td><code><strong>4369</strong></code></td><td>

```diff
+4369
```
</td></tr>
<tr><td><code><strong>UDP</strong></code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
-UDP
```
</td></tr>
<tr><td><code><strong>TCP</strong></code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code>127.0.2.1</code></td><td><code>4369</code></td><td>

```diff
+TCP
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code><strong>127.0.3.1</strong></code></td><td><code>4369</code></td><td>

```diff
+127.0.3.1
```
</td></tr>
<tr><td><code><strong>TCP</strong></code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code>127.0.4.1</code></td><td><code>4369</code></td><td>

```diff
+TCP
```
</td></tr>
<tr><td><code>TCP</code></td><td><code><strong>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</strong></code></td><td><code>127.0.4.1</code></td><td><code>4369</code></td><td>

```diff
+/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code></td><td><code><strong>127.0.4.1</strong></code></td><td><code>4369</code></td><td>

```diff
+127.0.4.1
```
</td></tr>
<tr><td><code>UDP</code></td><td><code>/opt/bitnami/erlang/lib/the-lang-lol/erts-14.1.1/bin/erlexec</code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
+0
```
</td></tr>
<tr><td><code><strong>UDP</strong></code></td><td><code>/opt/bitnami/erlang/lib/the-lang-lol/erts-14.1.1/bin/erlexec</code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
+UDP
```
</td></tr>
<tr><td><code>UDP</code></td><td><code><strong>/opt/bitnami/erlang/lib/the-lang-lol/erts-14.1.1/bin/erlexec</strong></code></td><td><code>N/A</code></td><td><code>N/A</code></td><td>

```diff
+/opt/bitnami/erlang/lib/the-lang-lol/erts-14.1.1/bin/erlexec
```
</td></tr>
</table>

<hr>

## Workload Information 
>**Cluster**:   
>**Namespace**:   
>**Type/Name**: statefulset/N/A  

### Ingress Connections

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Delta</th></tr><tr><td><code><strong>SOME_TCP</strong></code></td><td><code>N/A</code></td><td><code>10.4.2.92</code></td><td><code>8301</code></td><td>

```diff
+SOME_TCP
```
</td></tr>
<tr><td><code>TCPv6</code></td><td><code>N/A</code></td><td><code><strong>10.4.1.110</strong></code></td><td><code>8301</code></td><td>

```diff
-10.4.1.110
```
</td></tr>
<tr><td><code>TCPv6</code></td><td><code>N/A</code></td><td><code><strong>10.4.1.765423</strong></code></td><td><code>8301</code></td><td>

```diff
+10.4.1.765423
```
</td></tr>
</table>

### Egress Connections

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Delta</th></tr><tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>10.4.2.92</strong></code></td><td><code>8301</code></td><td>

```diff
-10.4.2.92
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>1.0.0.2</strong></code></td><td><code>8301</code></td><td>

```diff
+1.0.0.2
```
</td></tr>
</table>

<hr>

## Workload Information 
>**Cluster**:   
>**Namespace**:   
>**Type/Name**: deployment/N/A  

### Ingress Connections

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Delta</th></tr><tr><td><code><strong>WHATDIDYOUSAY</strong></code></td><td><code>N/A</code></td><td><code>10.4.3.99</code></td><td><code>80</code></td><td>

```diff
-WHATDIDYOUSAY
```
</td></tr>
<tr><td><code><strong>ISAIDPROTOCOL</strong></code></td><td><code>N/A</code></td><td><code>10.4.3.99</code></td><td><code>80</code></td><td>

```diff
+ISAIDPROTOCOL
```
</td></tr>
<tr><td><code><strong>TCP</strong></code></td><td><code>N/A</code></td><td><code>10.4.2.47</code></td><td><code>80</code></td><td>

```diff
-TCP
```
</td></tr>
<tr><td><code><strong>UDP</strong></code></td><td><code>N/A</code></td><td><code>10.4.2.47</code></td><td><code>80</code></td><td>

```diff
+UDP
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>10.4.2.175</strong></code></td><td><code>80</code></td><td>

```diff
-10.4.2.175
```
</td></tr>
<tr><td><code>TCPv6</code></td><td><code>N/A</code></td><td><code><strong>10.4.2.800</strong></code></td><td><code>80</code></td><td>

```diff
+10.4.2.800
```
</td></tr>
<tr><td><code><strong>TCP</strong></code></td><td><code>N/A</code></td><td><code>10.4.2.175</code></td><td><code>80</code></td><td>

```diff
-TCP
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>10.4.3.37</strong></code></td><td><code>8000</code></td><td>

```diff
-10.4.3.37
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>10.4.3.69</strong></code></td><td><code>8000</code></td><td>

```diff
+10.4.3.69
```
</td></tr>
</table>

<hr>

## Workload Information 
>**Cluster**:   
>**Namespace**:   
>**Type/Name**: deployment/N/A  

### Egress Connections

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Delta</th></tr><tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>52.217.12.92</strong></code></td><td><code>443</code></td><td>

```diff
-52.217.12.92
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>54.231.165.33</strong></code></td><td><code>443</code></td><td>

```diff
-54.231.165.33
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>52.217.89.140</strong></code></td><td><code>443</code></td><td>

```diff
-52.217.89.140
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>3.5.10.16</strong></code></td><td><code>8908</code></td><td>

```diff
-3.5.10.16
```
</td></tr>
<tr><td><code><strong>TCP</strong></code></td><td><code>N/A</code></td><td><code>54.231.169.89</code></td><td><code>443</code></td><td>

```diff
-TCP
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>52.216.44.217</strong></code></td><td><code>443</code></td><td>

```diff
+52.216.44.217
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>54.231.169.89</code></td><td><code><strong>443</strong></code></td><td>

```diff
-443
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>52.217.93.196</code></td><td><code><strong>443</strong></code></td><td>

```diff
-443
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>10.4.12.68</code></td><td><code><strong>5432</strong></code></td><td>

```diff
+5432
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>3.5.25.182</code></td><td><code><strong>443</strong></code></td><td>

```diff
-443
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>172.20.135.200</code></td><td><code><strong>8200</strong></code></td><td>

```diff
+8200
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>52.217.196.225</code></td><td><code><strong>443</strong></code></td><td>

```diff
-443
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code>172.20.3.44</code></td><td><code><strong>8000</strong></code></td><td>

```diff
+8000
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>52.217.129.105</strong></code></td><td><code>443</code></td><td>

```diff
+52.217.129.105
```
</td></tr>
<tr><td><code>TCP</code></td><td><code>N/A</code></td><td><code><strong>54.231.169.89</strong></code></td><td><code>443</code></td><td>

```diff
+54.231.169.89
```
</td></tr>
</table>

<hr>

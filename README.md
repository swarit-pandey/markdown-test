# Report [2023-12-20 08:26:17 UTC]


### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-user-mgmt  
>**Type/Name**: deployment/user-management-service  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.6	 
```
</td><td>
<code>8081</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.6</code>
</td><td>

```diff
+ 8081	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCPv6	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.6</code>
</td><td>
<code>8081</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.135	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.135</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.146</code>
</td><td>
<code>15006</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.146	 
```
</td><td>
<code>15006</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.146</code>
</td><td>

```diff
+ 15006	 
```
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.12.68	 
```
</td><td>
<code>5432</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.12.68</code>
</td><td>

```diff
+ 5432	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.135</code>
</td><td>
<code>8081</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.135	 
```
</td><td>
<code>8081</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.135</code>
</td><td>

```diff
+ 8081	 
```
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Bind Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>Bind Port</th><th>Bind Address</th></tr><tr><td>
<code>AF_INET</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.6	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_INET</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 0	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_INET	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-vulnerability-scanner  
>**Type/Name**: deployment/vulnerability-scanner  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 18.214.194.113	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>18.214.194.113</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>18.214.194.113</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /usr/bin/docker	 
```
</td><td>
<code>18.232.172.199</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/docker</code>
</td><td>

```diff
+ 18.232.172.199	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.95.117.170	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-mongodb  
>**Type/Name**: statefulset/accuknox-dev-mongodb-rs0  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.232.137	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.110.33</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.110.33</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.58	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.101.185	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.104.90	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.96.58	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.176.33	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.88.75	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.233.33	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.88.83	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.104.74	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 16.12.66.49	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.99.73	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.99.49	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.88.130	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.178.33	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.110.105	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.105.9	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.93.9	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.106.17	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 16.12.65.25	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.142.17	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.105.233	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.94.57	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.80.194	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.88.170	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.202	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.110.33	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-agents  
>**Type/Name**: deployment/discovery-engine  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>8090</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 8090	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCPv6	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>8090</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: kubecost  
>**Type/Name**: deployment/kubecost-cost-analyzer  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.92.195.242	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>3.5.78.122</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.5.78.122</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.92.226.130	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.81.112	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.92.211.130	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.78.195	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.79.125	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.87.117	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.218.220.201	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.138.132.185	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.77.132	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.80.161	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.92.148.178	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 54.239.39.230	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 209.54.181.194	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 99.77.60.116	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.94.214.88	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.95.127.139	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 99.78.176.232	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.78.122	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: splunk-operator  
>**Type/Name**: statefulset/splunk-s1-standalone  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>

```diff
+ /usr/bin/bash	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/bash</code>
</td><td>

```diff
+ /sbin/ldconfig	 
```
</td><td>Allow</td></tr></table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>/opt/splunk/bin/python3.7m</code>
</td><td>

```diff
+ 44.194.123.38	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/splunk/bin/python3.7m</code>
</td><td>
<code>44.194.123.38</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>/opt/splunk/bin/python3.7m</code>
</td><td>
<code>44.194.123.38</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /opt/splunk/bin/python3.7m	 
```
</td><td>
<code>44.194.123.38</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy  
>**Type/Name**: deployment/celery  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.30.132	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>16.182.65.240</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>16.182.65.240</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.217.170.89	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.35.33	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.35.57	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.217.170.81	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.35.41	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.35.65	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.30.116	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.35.73	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.30.124	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.35.49	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.30.148	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.216.30.156	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/lib/git-core/git-remote-https</code>
</td><td>

```diff
+ 140.82.114.3	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /usr/lib/git-core/git-remote-https	 
```
</td><td>
<code>140.82.114.3</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 35.167.7.190	 
```
</td><td>
<code>587</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>35.167.7.190</code>
</td><td>

```diff
+ 587	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.46.159.95	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 16.182.65.240	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy  
>**Type/Name**: deployment/uwsgi  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 18.217.128.146	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>18.217.128.146</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.200.216</code>
</td><td>
<code>7687</code>
</td><td>
<code>accuknox-dev-neo4j</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 172.20.200.216	 
```
</td><td>
<code>7687</code>
</td><td>
<code>accuknox-dev-neo4j</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.200.216</code>
</td><td>

```diff
+ 7687	 
```
</td><td>
<code>accuknox-dev-neo4j</code>
</td><td>
<code>Service</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: statefulset/loki-read  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.74	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.100.138</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.100.138</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.97.9	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.179.137	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.234	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.138	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-mongodb  
>**Type/Name**: deployment/percona-server-mongodb-operator  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.176.201	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.176.201</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.176.201</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-vault  
>**Type/Name**: statefulset/vault  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.248	 
```
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vulnerability-scanner</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.164</code>
</td><td>

```diff
+ 8200	 
```
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
+ TCPv6	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.164</code>
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.154	 
```
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vulnerability-scanner</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.164	 
```
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: test-dev2  
>**Type/Name**: deployment/dev2  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.26	 
```
</td><td>
<code>4369</code>
</td><td>
<code>test-dev2</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.26</code>
</td><td>

```diff
+ 4369	 
```
</td><td>
<code>test-dev2</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.26</code>
</td><td>
<code>4369</code>
</td><td>
<code>test-dev2</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 140.82.113.5	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>140.82.113.5</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-pulsar  
>**Type/Name**: statefulset/pulsar-proxy  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.26	 
```
</td><td>
<code>6650</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.26</code>
</td><td>

```diff
+ 6650	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.26</code>
</td><td>
<code>6650</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: statefulset/loki-write  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.98.89	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.106.57</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.106.57</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.101.209	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.97.241	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.130	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.176.209	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.101.73	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.98.1	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.97.193	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.97.97	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.88.106	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.162	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 16.12.64.233	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 16.12.65.1	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 16.12.65.201	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.143.25	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.97.153	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.141.81	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.233.17	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.98.41	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.80.59	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.177.145	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.176.185	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.102.193	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.100.66	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.104.10	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.176.1	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.98.217	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.106.57	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

### Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-neo4j  
>**Type/Name**: statefulset/my-neo4j-release  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.250	 
```
</td><td>
<code>7687</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.250</code>
</td><td>

```diff
+ 7687	 
```
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
+ TCPv6	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.250</code>
</td><td>
<code>7687</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

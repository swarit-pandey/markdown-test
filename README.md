# Behavior Summary [2023-12-20 02:13:26 UTC]


## Workload Information 
>**Cluster**: default  
>**Namespace**: cattle-system  
>**Type/Name**: deployment/rancher-webhook  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.33	 
```
</td><td>
<code>9443</code>
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
<code>10.4.2.175</code>
</td><td>

```diff
+ 9443	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.175</code>
</td><td>
<code>9443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>9443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-vulnerability-scanner  
>**Type/Name**: deployment/vulnerability-scanner  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>

```diff
+ /home/vuln-scanner/main	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>

```diff
- /home/what-scanner-bro?/main	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>

```diff
+ /bin/sh	 
```
</td><td>
<code>/usr/bin/docker</code>
</td><td>Allow</td></tr><tr><td>

```diff
- /bin/sh	 
```
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>Allow</td></tr></table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>

```diff
- /usr/local/bin/trivy	 
```
</td><td>
<code>104.16.104.207</code>
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
+ /usr/local/bin/trivy	 
```
</td><td>
<code>140.82.112.33</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 44.196.174.155	 
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
+ 172.20.54.233	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>
<code>44.196.174.155</code>
</td><td>

```diff
- 443	 
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
<code>172.20.54.233</code>
</td><td>

```diff
+ 6650	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/docker</code>
</td><td>
<code>142.251.177.82</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>N/A</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>
<code>169.254.169.254</code>
</td><td>

```diff
- 80	 
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
<code>18.189.66.244</code>
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
<code>/usr/local/bin/trivy</code>
</td><td>
<code>104.16.103.207</code>
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
+ 142.251.4.82	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 34.224.219.70	 
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
<code>/usr/local/bin/trivy</code>
</td><td>
<code>34.224.219.70</code>
</td><td>

```diff
- 443	 
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
<code>172.20.135.200</code>
</td><td>

```diff
+ 8200	 
```
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 3.213.18.40	 
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
+ 142.251.177.82	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- UDP	 
```
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
- 34.224.219.70	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 54.156.243.51	 
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
+ 44.219.3.189	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>18.189.66.244</code>
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 34.203.80.76	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
+ 104.16.104.207	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 18.235.212.116	 
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
<code>/usr/bin/docker</code>
</td><td>

```diff
- 34.226.69.105	 
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
+ 142.250.191.202	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 3.219.239.5	 
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
+ 142.250.191.138	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 142.250.111.82	 
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
<code>/usr/bin/docker</code>
</td><td>

```diff
- 142.250.111.82	 
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
<code>/usr/bin/docker</code>
</td><td>

```diff
+ 142.251.178.82	 
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
+ 18.189.66.244	 
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
+ 172.217.1.106	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
+ 185.199.108.154	 
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
+ 172.217.4.202	 
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
- 172.217.4.42	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
+ 104.18.37.147	 
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
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
- 20.109.50.235	 
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
+ 172.217.0.170	 
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
<code>/usr/local/bin/trivy</code>
</td><td>
<code>185.199.109.154</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>
<code>169.254.169.254</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/trivy</code>
</td><td>

```diff
+ 140.82.112.33	 
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
+ 172.217.5.10	 
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
<code>/usr/local/bin/trivy</code>
</td><td>
<code>140.82.113.34</code>
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
<code>/usr/local/bin/trivy</code>
</td><td>
<code>140.82.113.34</code>
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
+ 142.250.190.10	 
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
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy  
>**Type/Name**: deployment/uwsgi  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>10.4.12.68</code>
</td><td>
<code>5432</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.12.68</code>
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
- 5432	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
+ 172.20.121.200	 
```
</td><td>
<code>5671</code>
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.121.200</code>
</td><td>

```diff
+ 5671	 
```
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.7.196</code>
</td><td>
<code>6379</code>
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
+ 10.4.7.196	 
```
</td><td>
<code>6379</code>
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
<code>10.4.7.196</code>
</td><td>

```diff
+ 6379	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: kubecost  
>**Type/Name**: deployment/kubecost-cost-analyzer  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.126	 
```
</td><td>
<code>9003</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.126</code>
</td><td>

```diff
+ 9003	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.126</code>
</td><td>
<code>9003</code>
</td><td>
<code>kubearmor</code>
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
+ 3.5.85.149	 
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
<code>3.5.85.149</code>
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
<code>3.5.85.149</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.92.138.242</code>
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
<code>52.92.138.242</code>
</td><td>

```diff
- 443	 
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
- 52.92.129.26	 
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
+ 3.5.81.107	 
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
- 3.5.83.148	 
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
+ 52.92.129.178	 
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
- 18.189.215.161	 
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
+ 52.92.194.2	 
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
- 3.5.84.126	 
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
+ 3.5.76.212	 
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
+ 172.20.0.1	 
```
</td><td>
<code>443</code>
</td><td>
<code>default</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.5.84.214	 
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
+ 3.5.86.133	 
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
+ 3.5.76.194	 
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
+ 52.92.248.34	 
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
+ 52.46.64.63	 
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
- 209.54.182.49	 
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
+ 99.77.62.124	 
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
- 99.77.60.116	 
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
- 54.240.249.157	 
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
- 99.83.81.17	 
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
+ 52.46.96.130	 
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
- 52.119.174.12	 
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
- 54.239.39.230	 
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
- 99.78.180.158	 
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
+ 99.77.60.114	 
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
+ 52.94.137.27	 
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
- 52.94.141.14	 
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
+ 52.94.181.41	 
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
+ 103.8.174.238	 
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
+ 52.92.146.122	 
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
+ 99.78.180.185	 
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
- 52.92.194.186	 
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
+ 52.46.159.174	 
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
- 172.20.0.1	 
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
+ 99.78.244.123	 
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
- 52.218.180.177	 
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
- 3.5.85.147	 
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
- 52.218.132.89	 
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
+ 52.95.80.15	 
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
- 52.92.176.58	 
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
- 3.5.83.194	 
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
- 52.92.238.18	 
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
- 52.92.234.162	 
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
- 52.218.238.17	 
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
- 52.218.182.177	 
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
- 52.218.220.25	 
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
- 3.5.76.139	 
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
+ 52.95.127.183	 
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
- 52.218.246.73	 
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
+ 99.78.180.194	 
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
- 52.92.208.130	 
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
+ 3.5.78.113	 
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
- 99.83.80.157	 
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
+ 52.92.192.106	 
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
+ 52.218.242.209	 
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
+ 52.92.131.250	 
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
+ 52.92.243.194	 
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
+ 3.5.87.65	 
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
+ 3.5.83.0	 
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
- 52.94.184.151	 
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
+ 52.92.229.98	 
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
+ 52.92.195.250	 
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
+ 52.218.233.41	 
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
- 52.95.127.226	 
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
+ 18.223.144.213	 
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
- 99.78.176.224	 
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
+ 52.94.138.238	 
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
- 99.78.180.181	 
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
- 52.46.155.190	 
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
+ 99.77.62.126	 
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
+ 176.32.118.39	 
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
+ 99.78.132.94	 
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
+ 99.82.187.134	 
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
+ 209.54.182.73	 
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
- 99.83.80.155	 
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
- 52.92.176.114	 
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
- 52.92.240.202	 
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
+ 99.78.178.214	 
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
- 52.92.139.98	 
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
+ 52.119.175.10	 
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
- 52.92.228.66	 
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
- 52.218.232.9	 
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
- 52.92.132.34	 
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
- 52.92.177.162	 
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
- 52.92.209.2	 
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
+ 52.95.122.167	 
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
- 52.218.232.113	 
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
+ 15.221.11.13	 
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
- 52.95.20.2	 
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
+ 52.92.211.234	 
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
- 209.54.180.217	 
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
+ 3.5.78.179	 
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
+ 3.5.78.148	 
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
- 67.220.228.6	 
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
+ 52.92.131.202	 
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
+ 3.5.77.186	 
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
+ 52.92.146.234	 
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
+ 52.218.133.146	 
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
+ 3.5.82.200	 
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
+ 3.5.79.14	 
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
+ 52.92.195.130	 
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
+ 52.92.138.82	 
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
- 15.221.12.231	 
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
+ 52.92.153.106	 
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
- 99.83.82.21	 
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
- 52.92.165.2	 
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
+ 54.239.55.167	 
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
- 52.218.250.161	 
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
+ 99.82.185.0	 
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
- 52.218.133.26	 
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
+ 15.221.8.221	 
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
- 3.5.80.162	 
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
+ 67.220.226.86	 
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
- 52.218.178.129	 
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
+ 52.46.142.79	 
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
- 52.92.195.162	 
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
+ 52.95.18.3	 
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
- 52.92.164.210	 
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
- 52.92.210.234	 
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
+ 52.94.176.190	 
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
- 52.218.232.241	 
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
+ 99.78.178.221	 
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
+ 52.94.141.13	 
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
- 15.221.8.216	 
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
+ 209.54.182.94	 
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
+ 99.77.62.122	 
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
+ 3.5.87.191	 
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
+ 52.92.145.122	 
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
+ 52.92.228.194	 
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
- 99.77.58.84	 
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
+ 3.5.84.153	 
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
+ 3.5.83.196	 
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
- 52.94.137.29	 
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
+ 52.92.209.114	 
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
+ 3.5.80.204	 
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
- 99.78.176.225	 
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
+ 52.218.213.81	 
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
+ 52.92.237.122	 
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
+ 3.5.81.142	 
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
+ 3.5.84.135	 
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
- 209.54.180.155	 
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
+ 3.13.212.34	 
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
- 52.92.211.26	 
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
+ 52.92.232.50	 
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
- 52.92.241.98	 
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
+ 3.23.174.39	 
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
- 52.218.246.145	 
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
<code>3.5.78.195</code>
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
<code>3.5.78.195</code>
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
+ 52.95.20.2	 
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
+ 52.94.138.247	 
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
+ 54.239.23.99	 
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
+ 15.221.12.227	 
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
+ 52.46.142.40	 
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
+ 52.94.181.146	 
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
+ 54.239.37.252	 
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
+ 3.5.85.49	 
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
+ 3.5.81.164	 
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
+ 52.218.152.217	 
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
+ 52.92.238.234	 
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
+ 3.5.82.187	 
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
+ 52.218.216.161	 
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
+ 52.92.139.74	 
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
+ 52.92.179.210	 
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
+ 52.92.209.162	 
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
+ 52.92.224.90	 
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
+ 52.92.137.210	 
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
+ 52.95.127.227	 
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
+ 52.95.35.53	 
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
+ 52.94.184.146	 
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
+ 99.83.82.12	 
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
+ 99.77.62.123	 
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
+ 52.94.233.135	 
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
+ 99.77.62.120	 
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
+ 3.5.83.224	 
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
+ 52.92.147.194	 
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
+ 52.92.196.194	 
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
+ 52.92.152.74	 
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
+ 3.5.80.102	 
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
+ 52.92.251.146	 
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
+ 52.218.234.121	 
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
+ 3.5.84.125	 
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
+ 3.5.83.13	 
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
+ 52.92.195.218	 
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
+ 3.5.77.154	 
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
+ 3.132.161.117	 
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
+ 52.92.209.234	 
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
+ 52.119.187.3	 
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
+ 99.83.80.154	 
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
+ 99.78.180.158	 
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
+ 52.94.136.219	 
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
+ 52.94.214.27	 
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
+ 99.77.58.83	 
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
+ 209.54.182.67	 
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
+ 54.239.37.253	 
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
+ 52.92.147.218	 
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
+ 52.92.239.106	 
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
+ 52.92.225.154	 
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
+ 52.218.228.9	 
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
+ 52.92.147.10	 
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
+ 3.5.79.152	 
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
+ 52.119.164.21	 
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
+ 52.46.150.99	 
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
+ 99.77.60.113	 
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
+ 52.95.16.2	 
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
+ 52.95.119.101	 
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
+ 52.218.197.57	 
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
+ 52.92.146.202	 
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
+ 3.5.83.199	 
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
+ 52.92.194.210	 
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
+ 52.218.182.89	 
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
+ 3.5.85.169	 
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
+ 52.218.132.49	 
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
+ 3.5.79.171	 
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
+ 209.54.182.34	 
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
+ 52.94.137.21	 
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
+ 15.221.11.26	 
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
+ 103.8.174.239	 
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
+ 99.78.178.238	 
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
+ 54.240.195.243	 
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
+ 52.94.184.137	 
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
+ 3.5.76.197	 
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
+ 3.5.84.167	 
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
+ 3.5.86.214	 
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
+ 52.218.235.65	 
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
+ 52.92.136.114	 
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
+ 52.92.137.42	 
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
+ 3.5.76.198	 
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
+ 52.92.243.50	 
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
+ 52.92.164.82	 
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
+ 52.92.194.146	 
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
+ 3.5.83.189	 
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
+ 52.92.179.82	 
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
+ 3.19.192.161	 
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
+ 52.218.180.145	 
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
+ 54.239.28.168	 
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
+ 99.83.81.11	 
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
+ 67.220.226.66	 
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
+ 52.94.141.11	 
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
+ 99.78.178.225	 
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
+ 15.221.12.154	 
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
+ 15.221.8.219	 
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
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-label-service  
>**Type/Name**: deployment/labelmanagement  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.101</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.101</code>
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
+ UDP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- UDP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- ./etc/istio/proxy/XDS	 
```
</td><td>
<code>N/A</code>
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
+ 172.20.16.197	 
```
</td><td>
<code>15012</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>./etc/istio/proxy/XDS</code>
</td><td>
<code>N/A</code>
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
<code>172.20.16.197</code>
</td><td>

```diff
+ 15012	 
```
</td><td>
<code>istio-system</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>./etc/istio/proxy/XDS</code>
</td><td>
<code>N/A</code>
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
<code>172.20.16.197</code>
</td><td>
<code>15012</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 172.20.16.197	 
```
</td><td>
<code>15012</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ ./etc/istio/proxy/XDS	 
```
</td><td>
<code>N/A</code>
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
<code>172.20.16.197</code>
</td><td>

```diff
- 15012	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>./etc/istio/proxy/XDS</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.16.197</code>
</td><td>
<code>15012</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>./etc/istio/proxy/XDS</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prom-adap-prometheus-adapter  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.119	 
```
</td><td>
<code>6443</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.119	 
```
</td><td>
<code>6443</code>
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

```diff
+ 10.4.2.33	 
```
</td><td>
<code>6443</code>
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
<code>10.4.3.119</code>
</td><td>

```diff
+ 6443	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.119</code>
</td><td>
<code>6443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>UDP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.190.247</code>
</td><td>
<code>9090</code>
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
+ 172.20.190.247	 
```
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.190.247</code>
</td><td>

```diff
+ 9090	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.190.247</code>
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.0.1</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>default</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.0.1</code>
</td><td>
<code>443</code>
</td><td>
<code>default</code>
</td><td>
<code>Service</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-policy-storage-service  
>**Type/Name**: deployment/policy-storage-service  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.167	 
```
</td><td>
<code>15021</code>
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
+ 10.4.2.126	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.126	 
```
</td><td>
<code>15021</code>
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
+ 10.4.3.167	 
```
</td><td>
<code>15021</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.126</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.126</code>
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.125	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.200</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.200	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.6	 
```
</td><td>
<code>8080</code>
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
+ 8080	 
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
<code>8080</code>
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
+ 10.4.3.168	 
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
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.200</code>
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.43	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-istio-ext-authz</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.43</code>
</td><td>

```diff
+ 8000	 
```
</td><td>
<code>accuknox-dev-istio-ext-authz</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.125	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.200</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.200	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-fluentd-cloudwatch  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
- UDP	 
```
</td><td>
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>3.128.56.177</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.128.56.177</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.176	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.132	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.135	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.161	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.150	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.142	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.177	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.177	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.161	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.179	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.132	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.147	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.182	 
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
- 3.128.56.179	 
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
+ 3.128.56.140	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.150	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.154	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.156	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.147	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.175	 
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
<code>3.128.56.175</code>
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
<code>3.128.56.175</code>
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.176	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.179	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.182	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.156	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
- 3.128.56.154	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.142	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: statefulset/pmm  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.66	 
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
+ 10.4.3.204	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.73	 
```
</td><td>
<code>443</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>9093</code>
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
+ 10.4.3.66	 
```
</td><td>
<code>443</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>42001</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 9093	 
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
<code>10.4.3.204</code>
</td><td>
<code>80</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
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
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 42001	 
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
<code>42001</code>
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
<code>10.4.3.204</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>kubearmor</code>
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
+ 127.0.0.1	 
```
</td><td>
<code>5432</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>::1</code>
</td><td>

```diff
+ 9090	 
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 8880	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>159.135.194.176</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>147.135.54.159</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>147.135.54.159</code>
</td><td>

```diff
- 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>67.219.144.68</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>34.120.177.193</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>9090</code>
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
<code>127.0.0.1</code>
</td><td>
<code>9093</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
- 127.0.0.1	 
```
</td><td>
<code>3000</code>
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
<code>185.199.108.133</code>
</td><td>

```diff
- 443	 
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 42000	 
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
- 127.0.0.1	 
```
</td><td>
<code>42000</code>
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
+ 34.96.126.106	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>N/A</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>208.76.253.18</code>
</td><td>

```diff
- 80	 
```
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

```diff
+ ::1	 
```
</td><td>
<code>9090</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- UDP	 
```
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>::1</code>
</td><td>
<code>9090</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>

```diff
- 147.135.54.159	 
```
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>

```diff
+ 67.219.144.68	 
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
<code>/usr/bin/python2.7</code>
</td><td>

```diff
+ 67.219.148.142	 
```
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>

```diff
+ 35.180.43.213	 
```
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>208.76.253.18</code>
</td><td>

```diff
+ 80	 
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
<code>/usr/bin/python2.7</code>
</td><td>
<code>38.145.60.20</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>N/A</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>

```diff
+ 147.75.199.223	 
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
<code>/usr/bin/python2.7</code>
</td><td>
<code>38.145.60.20</code>
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
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>

```diff
+ 134.195.207.11	 
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
+ 127.0.0.1	 
```
</td><td>
<code>42001</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 42001	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python2.7</code>
</td><td>

```diff
+ 38.145.60.20	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: statefulset/loki-read  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>3100</code>
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

```diff
+ 10.4.3.84	 
```
</td><td>
<code>7946</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.84	 
```
</td><td>
<code>7946</code>
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

```diff
+ 10.4.3.82	 
```
</td><td>
<code>3100</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.207</code>
</td><td>

```diff
- 9095	 
```
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
<code>10.4.2.189</code>
</td><td>

```diff
+ 3100	 
```
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

```diff
- 10.4.1.232	 
```
</td><td>
<code>7946</code>
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

```diff
+ 10.4.2.232	 
```
</td><td>
<code>3100</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.207	 
```
</td><td>
<code>9095</code>
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

```diff
+ 10.4.2.189	 
```
</td><td>
<code>3100</code>
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
<code>10.4.2.232</code>
</td><td>

```diff
+ 3100	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.232</code>
</td><td>
<code>3100</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.50	 
```
</td><td>
<code>9095</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.50</code>
</td><td>

```diff
+ 9095	 
```
</td><td>
<code>accuknox-loki</code>
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
<code>16.12.65.129</code>
</td><td>

```diff
- 443	 
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
<code>10.4.1.50</code>
</td><td>

```diff
+ 7946	 
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
+ 10.4.1.50	 
```
</td><td>
<code>9095</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.50	 
```
</td><td>
<code>7946</code>
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
- 127.0.0.1	 
```
</td><td>
<code>5778</code>
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
+ 10.4.2.207	 
```
</td><td>
<code>9095</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.111.137</code>
</td><td>

```diff
- 443	 
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
<code>10.4.3.236</code>
</td><td>

```diff
+ 9095	 
```
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 52.219.111.137	 
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
+ 10.4.3.236	 
```
</td><td>
<code>9095</code>
</td><td>
<code>accuknox-loki</code>
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
<code>52.219.141.25</code>
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
+ 52.219.141.25	 
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
<code>10.4.3.236</code>
</td><td>

```diff
- 9095	 
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
<code>52.219.177.9</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.109.113	 
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
- 52.219.94.201	 
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
+ 52.219.94.129	 
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
- 52.219.101.217	 
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
+ 127.0.0.1	 
```
</td><td>
<code>5778</code>
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
<code>52.219.101.217</code>
</td><td>

```diff
- 443	 
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 5778	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.207</code>
</td><td>
<code>9095</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.177.177</code>
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
- 52.219.177.97	 
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
+ 52.219.102.105	 
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
- 52.219.110.73	 
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
+ 52.219.94.113	 
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
+ 52.219.95.1	 
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
- 10.4.1.50	 
```
</td><td>
<code>9095</code>
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
+ 52.219.98.233	 
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
- 16.12.65.73	 
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
+ 52.219.93.233	 
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
- 52.219.177.161	 
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
+ 52.219.111.49	 
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
- 52.219.92.225	 
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
+ 52.219.109.105	 
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
- 52.219.106.145	 
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
+ 52.219.233.25	 
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
- 52.219.110.9	 
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
+ 52.219.107.1	 
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
- 52.219.109.137	 
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
+ 52.219.93.1	 
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
- 52.219.177.41	 
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
+ 52.219.98.49	 
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
- 10.4.3.236	 
```
</td><td>
<code>9095</code>
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
+ 52.219.177.9	 
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
- 52.219.92.41	 
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
+ 52.219.108.241	 
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
- 52.219.111.25	 
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
+ 52.219.104.226	 
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
- 52.219.93.41	 
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
+ 52.219.106.153	 
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
- 52.219.97.33	 
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
+ 52.219.177.57	 
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
- 52.219.109.81	 
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
+ 52.219.108.73	 
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
- 52.219.104.42	 
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
- 52.219.94.81	 
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
+ 52.219.92.225	 
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
+ 52.219.110.161	 
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
- 52.219.232.241	 
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
+ 52.219.178.225	 
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
- 52.219.98.249	 
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
+ 16.12.65.241	 
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
+ 52.219.110.97	 
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
- 52.219.111.49	 
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
+ 52.219.98.193	 
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
- 52.219.104.226	 
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
+ 52.219.106.177	 
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
+ 16.12.65.209	 
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
+ 52.219.107.9	 
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
- 52.219.109.233	 
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
+ 52.219.177.33	 
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
- 52.219.97.217	 
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
+ 52.219.92.121	 
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
- 52.219.107.73	 
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
+ 52.219.177.113	 
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
- 52.219.101.129	 
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
+ 52.219.102.89	 
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
- 52.219.96.249	 
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
+ 52.219.96.218	 
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
- 52.219.109.193	 
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
+ 52.219.109.81	 
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
+ 52.219.88.226	 
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
- 52.219.100.122	 
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
- 52.219.80.154	 
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
+ 52.219.177.217	 
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
- 52.219.177.145	 
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
+ 52.219.93.121	 
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
- 52.219.176.97	 
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
+ 52.219.94.49	 
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
+ 52.219.177.97	 
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
- 52.219.106.1	 
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
+ 52.219.97.177	 
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
- 16.12.64.137	 
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
+ 52.219.179.233	 
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
- 52.219.94.9	 
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
+ 52.219.105.97	 
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
- 52.219.95.41	 
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
+ 16.12.65.89	 
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
- 52.219.232.193	 
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
+ 52.219.141.49	 
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
- 52.219.232.1	 
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
+ 52.219.111.241	 
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
- 52.219.233.17	 
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
+ 52.219.92.97	 
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
- 52.219.109.169	 
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
+ 52.219.97.49	 
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
- 52.219.106.81	 
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
+ 52.219.110.17	 
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
+ 52.219.98.169	 
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
- 52.219.94.97	 
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
+ 52.219.94.17	 
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
- 52.219.100.138	 
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
- 52.219.110.233	 
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
+ 52.219.92.145	 
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
- 52.219.88.178	 
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
+ 52.219.98.249	 
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
- 52.219.100.50	 
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
+ 52.219.96.186	 
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
- 52.219.177.89	 
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
+ 52.219.93.73	 
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
+ 52.219.106.169	 
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
+ 52.219.110.193	 
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
- 52.219.178.113	 
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
+ 52.219.110.129	 
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
- 52.219.97.225	 
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
- 52.219.93.57	 
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
+ 16.12.64.81	 
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
- 52.219.110.217	 
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
+ 52.219.101.241	 
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
+ 52.219.92.33	 
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
- 52.219.111.249	 
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
+ 52.219.233.89	 
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
- 52.219.102.113	 
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
+ 52.219.103.17	 
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
- 52.219.178.57	 
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
+ 52.219.105.153	 
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
- 52.219.92.105	 
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
+ 52.219.88.146	 
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
+ 52.219.179.193	 
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
- 52.219.108.25	 
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
+ 52.219.110.217	 
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
- 52.219.178.81	 
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
+ 52.219.179.217	 
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
- 16.12.64.217	 
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
+ 52.219.178.201	 
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
- 52.219.105.225	 
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
+ 52.219.92.153	 
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
- 52.219.142.17	 
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
+ 52.219.94.209	 
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
- 52.219.97.209	 
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
+ 52.219.93.81	 
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
- 52.219.93.25	 
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
+ 52.219.108.201	 
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
- 52.219.110.137	 
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
+ 52.219.100.114	 
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
- 52.219.106.97	 
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
+ 16.12.66.9	 
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
- 16.12.65.153	 
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
+ 52.219.106.241	 
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
- 52.219.177.225	 
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
+ 52.219.109.65	 
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
- 52.219.178.201	 
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
+ 52.219.94.185	 
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
- 52.219.88.75	 
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
+ 16.12.64.153	 
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
- 52.219.177.81	 
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
+ 16.12.65.225	 
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
- 52.219.102.65	 
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
+ 52.219.232.153	 
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
- 16.12.65.9	 
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
+ 52.219.103.49	 
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
- 52.219.103.1	 
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
+ 52.219.177.105	 
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
+ 52.219.95.33	 
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
- 52.219.179.233	 
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
+ 16.12.64.145	 
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
- 52.219.96.218	 
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
+ 52.219.93.25	 
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
- 52.219.103.17	 
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
- 52.219.233.97	 
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
+ 52.219.93.57	 
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
- 52.219.178.233	 
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
+ 52.219.178.89	 
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
- 52.219.102.1	 
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
+ 52.219.106.209	 
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
- 52.219.94.17	 
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
+ 52.219.177.153	 
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
- 52.219.109.161	 
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
+ 52.219.178.161	 
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
- 52.219.111.81	 
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
+ 52.219.233.49	 
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
- 52.219.98.105	 
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
+ 52.219.108.233	 
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
+ 52.219.98.97	 
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
- 52.219.178.17	 
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
+ 16.12.64.209	 
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
- 52.219.94.25	 
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
+ 52.219.94.201	 
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
- 52.219.176.185	 
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
+ 52.219.111.97	 
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
- 52.219.110.113	 
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
+ 52.219.93.177	 
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
+ 16.12.64.113	 
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
- 52.219.179.17	 
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
+ 52.219.141.89	 
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
- 52.219.233.1	 
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
+ 52.219.105.57	 
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
- 16.12.64.225	 
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
+ 52.219.176.49	 
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
+ 52.219.94.153	 
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
- 52.219.178.89	 
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
+ 52.219.232.129	 
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
- 52.219.108.57	 
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
+ 52.219.110.145	 
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
- 52.219.177.241	 
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
+ 52.219.178.129	 
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
- 52.219.93.121	 
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
+ 52.219.102.169	 
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
- 52.219.178.249	 
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
+ 52.219.92.41	 
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
- 52.219.84.186	 
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
+ 52.219.111.65	 
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
- 52.219.94.241	 
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
+ 52.219.84.83	 
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
+ 52.219.105.121	 
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
- 52.219.179.105	 
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
+ 52.219.102.185	 
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
- 16.12.65.137	 
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
- 52.219.92.129	 
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
- 52.219.111.57	 
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
+ 52.219.179.41	 
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
- 52.219.92.201	 
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
+ 52.219.232.233	 
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
- 52.219.99.73	 
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
+ 52.219.109.73	 
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
+ 52.219.232.193	 
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
- 52.219.178.41	 
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
+ 52.219.102.233	 
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
- 52.219.105.153	 
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
+ 52.219.109.169	 
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
- 52.219.178.209	 
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
+ 52.219.142.57	 
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
- 52.219.101.201	 
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
+ 16.12.64.185	 
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
- 16.12.65.49	 
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
+ 52.219.105.209	 
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
+ 52.219.88.91	 
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
- 52.219.104.114	 
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
+ 52.219.99.17	 
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
- 52.219.110.65	 
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
+ 52.219.100.154	 
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
- 52.219.97.161	 
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
+ 52.219.103.41	 
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
- 52.219.94.113	 
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
+ 52.219.179.25	 
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
- 52.219.102.129	 
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
+ 52.219.141.41	 
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
+ 52.219.93.137	 
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
- 52.219.98.73	 
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
+ 52.219.109.225	 
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
- 52.219.97.97	 
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
+ 52.219.143.33	 
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
- 52.219.104.234	 
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
- 52.219.110.145	 
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
+ 52.219.95.9	 
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
- 52.219.143.25	 
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
+ 52.219.142.81	 
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
- 52.219.97.25	 
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
+ 52.219.96.90	 
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
- 52.219.232.209	 
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
+ 52.219.108.17	 
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
- 52.219.108.145	 
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
+ 52.219.109.161	 
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
- 52.219.141.25	 
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
+ 52.219.177.161	 
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
- 52.219.103.9	 
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
+ 52.219.100.249	 
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
- 52.219.103.81	 
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
+ 52.219.109.41	 
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
- 52.219.94.89	 
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
+ 52.219.102.17	 
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
- 52.219.176.65	 
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
+ 52.219.102.121	 
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
- 52.219.176.113	 
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
+ 52.219.92.17	 
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
- 52.219.108.97	 
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
+ 52.219.177.177	 
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
- 16.12.65.145	 
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
+ 52.219.109.137	 
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
- 52.219.108.65	 
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
+ 52.219.100.170	 
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
+ 52.219.232.17	 
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
- 52.219.177.49	 
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
- 52.219.179.89	 
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
+ 52.219.233.65	 
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
- 52.219.94.177	 
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
+ 52.219.96.26	 
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
- 52.219.99.25	 
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
+ 52.219.232.217	 
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
- 52.219.109.201	 
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
+ 52.219.142.33	 
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
- 52.219.109.89	 
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
+ 52.219.101.249	 
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
- 52.219.108.185	 
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
+ 52.219.179.169	 
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
- 52.219.176.105	 
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
+ 16.12.65.97	 
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
- 52.219.93.193	 
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
- 16.12.65.57	 
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
+ 16.12.64.169	 
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
- 16.12.64.17	 
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
+ 52.219.101.65	 
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
- 52.219.142.65	 
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
+ 52.219.93.145	 
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
+ 52.219.94.25	 
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
- 16.12.64.233	 
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
+ 16.12.64.17	 
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
- 52.219.110.169	 
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
+ 52.219.92.169	 
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
+ 52.219.143.49	 
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
- 52.219.232.9	 
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
+ 52.219.176.41	 
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
- 52.219.178.137	 
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
+ 52.219.177.81	 
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
- 52.219.143.73	 
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
+ 16.12.65.185	 
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
- 52.219.105.41	 
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
+ 52.219.108.25	 
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
- 52.219.94.65	 
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
+ 52.219.102.49	 
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
- 16.12.64.89	 
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
+ 52.219.94.241	 
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
- 52.219.105.249	 
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
+ 52.219.176.121	 
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
- 52.219.101.41	 
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
+ 52.219.179.73	 
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
- 52.219.92.169	 
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
+ 52.219.233.9	 
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
+ 52.219.108.137	 
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
- 52.219.109.121	 
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
+ 52.219.141.17	 
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
- 52.219.110.209	 
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
- 52.219.179.201	 
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
+ 52.219.232.201	 
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
- 52.219.178.193	 
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
+ 52.219.108.129	 
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
- 52.219.232.57	 
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
+ 52.219.177.73	 
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
- 52.219.176.201	 
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
+ 52.219.107.17	 
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
- 52.219.233.9	 
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
- 16.12.64.241	 
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
- 52.219.110.177	 
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
+ 52.219.92.73	 
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
- 52.219.101.97	 
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
+ 52.219.108.177	 
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
- 52.219.108.73	 
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
+ 52.219.176.169	 
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
+ 52.219.92.65	 
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
- 52.219.176.177	 
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
+ 52.219.176.73	 
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
- 52.219.104.130	 
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
- 52.219.111.17	 
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
- 52.219.177.249	 
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
+ 52.219.108.57	 
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
- 52.219.109.65	 
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
+ 52.219.108.121	 
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
+ 52.219.177.49	 
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
- 52.219.102.33	 
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
+ 52.219.99.33	 
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
- 52.219.109.97	 
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
+ 52.219.111.249	 
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
- 52.219.177.209	 
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
+ 52.219.110.113	 
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
- 52.219.98.121	 
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
+ 52.219.177.201	 
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
- 52.219.106.65	 
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
+ 52.219.101.33	 
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
- 52.219.101.33	 
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
- 52.219.92.113	 
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
+ 52.219.108.97	 
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
- 52.219.110.249	 
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
+ 52.219.98.137	 
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
- 52.219.88.146	 
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
+ 52.219.178.169	 
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
- 52.219.88.210	 
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
- 16.12.64.129	 
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
+ 16.12.65.137	 
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
+ 52.219.111.89	 
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
+ 52.219.110.41	 
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
- 16.12.64.177	 
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
+ 52.219.94.233	 
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
- 52.219.100.10	 
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
+ 52.219.178.249	 
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
- 52.219.102.161	 
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
+ 16.12.64.225	 
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
- 52.219.109.73	 
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
+ 52.219.94.9	 
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
- 52.219.142.49	 
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
+ 52.219.84.91	 
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
- 16.12.65.105	 
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
+ 52.219.96.82	 
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
- 52.219.102.25	 
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
+ 52.219.178.25	 
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
- 52.219.108.89	 
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
+ 52.219.102.25	 
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
- 52.219.111.9	 
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
+ 52.219.106.113	 
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
- 52.219.177.1	 
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
+ 52.219.104.194	 
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
+ 52.219.93.33	 
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
+ 52.219.233.57	 
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
- 52.219.94.105	 
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
+ 52.219.233.41	 
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
- 52.219.94.153	 
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
+ 52.219.178.209	 
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
- 52.219.97.105	 
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
+ 52.219.110.1	 
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
- 52.219.92.233	 
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
+ 16.12.64.9	 
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
- 52.219.177.129	 
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
+ 52.219.110.137	 
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
- 52.219.107.81	 
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
+ 52.219.99.9	 
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
- 52.219.109.25	 
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
+ 52.219.95.17	 
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
- 52.219.97.49	 
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
+ 52.219.104.241	 
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
- 52.219.110.121	 
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
+ 52.219.103.1	 
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
- 52.219.107.25	 
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
+ 52.219.101.89	 
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
- 52.219.176.169	 
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
+ 52.219.108.249	 
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
- 52.219.109.105	 
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
- 52.219.101.241	 
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
+ 52.219.143.9	 
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
+ 52.219.178.41	 
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
- 52.219.110.185	 
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
+ 52.219.143.41	 
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
- 52.219.88.162	 
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
+ 52.219.84.122	 
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
- 52.219.177.113	 
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
+ 52.219.108.105	 
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
- 52.219.97.9	 
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
+ 52.219.94.97	 
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
- 52.219.232.137	 
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
+ 52.219.177.233	 
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
- 52.219.94.217	 
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
+ 52.219.109.89	 
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
- 52.219.93.153	 
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
+ 52.219.92.217	 
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
+ 52.219.94.121	 
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
- 52.219.233.49	 
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
+ 52.219.142.65	 
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
- 52.219.104.50	 
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
+ 52.219.93.241	 
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
+ 52.219.232.209	 
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
- 52.219.88.234	 
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
+ 52.219.177.225	 
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
+ 52.219.104.2	 
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
- 52.219.104.218	 
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
+ 52.219.178.137	 
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
- 52.219.110.225	 
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
+ 52.219.178.65	 
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
- 52.219.143.65	 
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
+ 52.219.101.113	 
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
- 16.12.64.113	 
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
+ 52.219.108.161	 
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
- 52.219.141.65	 
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
+ 16.12.65.57	 
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
- 16.12.64.25	 
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
+ 52.219.99.65	 
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
- 52.219.108.17	 
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
+ 16.12.64.193	 
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
- 52.219.97.73	 
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
+ 52.219.109.209	 
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
- 52.219.106.185	 
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
+ 52.219.179.49	 
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
- 52.219.99.89	 
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
+ 52.219.93.201	 
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
+ 52.219.93.129	 
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
- 52.219.102.193	 
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
+ 52.219.232.49	 
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
- 52.219.102.217	 
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
+ 52.219.111.81	 
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
- 52.219.95.33	 
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
+ 52.219.178.81	 
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
- 52.219.141.81	 
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
+ 52.219.102.225	 
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
- 52.219.179.217	 
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
+ 52.219.97.145	 
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
+ 52.219.179.89	 
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
- 52.219.143.1	 
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
+ 52.219.110.25	 
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
- 52.219.98.81	 
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
+ 52.219.110.9	 
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
+ 52.219.92.129	 
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
- 52.219.110.105	 
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
+ 52.219.104.146	 
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
- 52.219.94.57	 
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
+ 52.219.233.1	 
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
- 16.12.65.249	 
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
+ 52.219.111.17	 
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
- 52.219.108.81	 
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
+ 52.219.232.1	 
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
- 52.219.95.17	 
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
+ 52.219.102.249	 
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
- 16.12.64.41	 
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
+ 52.219.178.105	 
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
- 52.219.93.177	 
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
+ 52.219.111.9	 
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
- 52.219.232.249	 
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
+ 52.219.179.153	 
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
- 52.219.106.137	 
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
+ 52.219.107.89	 
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
+ 52.219.109.57	 
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
+ 52.219.109.17	 
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
- 52.219.108.169	 
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
- 52.219.84.130	 
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
+ 52.219.109.129	 
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
- 52.219.232.201	 
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
+ 52.219.141.65	 
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
+ 52.219.84.138	 
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
- 52.219.111.1	 
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
+ 52.219.108.217	 
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
+ 52.219.178.97	 
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
+ 52.219.107.25	 
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
- 52.219.179.97	 
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
+ 16.12.64.161	 
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
- 52.219.92.89	 
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
- 52.219.110.25	 
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
+ 52.219.96.74	 
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
- 52.219.179.9	 
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
+ 52.219.98.17	 
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
- 52.219.109.1	 
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
+ 52.219.103.81	 
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
- 52.219.80.67	 
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
+ 52.219.88.194	 
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
+ 52.219.232.9	 
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
- 52.219.176.209	 
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
+ 52.219.105.177	 
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
- 52.219.141.1	 
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
+ 52.219.106.137	 
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
- 52.219.103.89	 
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
+ 52.219.99.89	 
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
- 52.219.93.105	 
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
+ 52.219.177.65	 
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
- 52.219.100.186	 
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
+ 52.219.142.9	 
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
- 52.219.96.146	 
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
+ 52.219.98.201	 
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
- 52.219.233.41	 
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
+ 52.219.107.81	 
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
- 34.96.126.106	 
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
+ 52.219.111.105	 
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
- 52.219.93.17	 
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
+ 52.219.105.249	 
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
+ 52.219.110.81	 
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
- 52.219.102.145	 
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
+ 52.219.101.137	 
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
- 52.219.176.17	 
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
+ 52.219.98.241	 
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
+ 52.219.104.178	 
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
+ 52.219.80.210	 
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
- 52.219.102.249	 
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
+ 52.219.106.193	 
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
- 52.219.107.65	 
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
+ 52.219.110.169	 
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
- 16.12.65.169	 
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
+ 52.219.179.177	 
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
- 52.219.110.193	 
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
+ 52.219.109.241	 
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
+ 52.219.80.202	 
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
- 52.219.232.169	 
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
+ 52.219.179.33	 
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
- 16.12.64.193	 
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
+ 16.12.66.25	 
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
- 16.12.66.41	 
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
+ 52.219.107.65	 
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
- 52.219.92.177	 
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
- 16.12.65.185	 
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
+ 52.219.93.97	 
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
- 52.219.80.170	 
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
+ 52.219.98.161	 
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
- 52.219.142.41	 
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
+ 52.219.110.57	 
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
- 52.219.105.161	 
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
+ 52.219.93.65	 
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
- 52.219.177.25	 
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
+ 52.219.97.225	 
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
- 52.219.176.57	 
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
+ 52.219.100.226	 
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
- 52.219.110.161	 
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
+ 52.219.96.42	 
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
+ 52.219.233.73	 
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
- 52.219.178.25	 
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
+ 52.219.179.57	 
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
+ 52.219.106.161	 
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
- 52.219.107.41	 
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
+ 52.219.94.65	 
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
- 16.12.64.153	 
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
+ 52.219.177.121	 
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
- 52.219.176.9	 
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
- 52.219.108.161	 
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
+ 52.219.178.1	 
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
- 52.219.106.17	 
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
+ 52.219.232.73	 
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
- 52.219.107.1	 
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
+ 52.219.104.34	 
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
- 52.219.109.153	 
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
+ 52.219.108.1	 
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
- 52.219.93.81	 
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
+ 52.219.104.186	 
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
- 52.219.179.193	 
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
+ 52.219.178.193	 
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
- 52.219.102.201	 
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
+ 52.219.80.91	 
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
- 52.219.142.89	 
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
+ 52.219.108.153	 
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
- 52.219.177.137	 
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
+ 52.219.93.89	 
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
- 52.219.232.41	 
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
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 52.219.108.233	 
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
+ 16.12.64.89	 
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
- 52.219.233.25	 
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
+ 52.219.94.225	 
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
- 52.219.176.225	 
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
+ 52.219.232.145	 
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
- 52.219.94.161	 
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
+ 16.12.64.249	 
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
- 52.219.93.217	 
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
+ 16.12.64.217	 
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
- 52.219.102.81	 
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
+ 52.219.111.57	 
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
- 52.219.109.129	 
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
+ 52.219.106.233	 
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
+ 52.219.141.9	 
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
- 52.219.106.209	 
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
+ 52.219.104.138	 
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
- 52.219.109.145	 
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
+ 16.12.65.9	 
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
+ 52.219.179.9	 
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
- 52.219.179.113	 
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
+ 52.219.92.81	 
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
- 52.219.177.33	 
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
+ 52.219.84.130	 
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
- 52.219.179.137	 
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
+ 52.219.142.41	 
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
+ 52.219.94.177	 
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
- 52.219.232.17	 
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
+ 52.219.103.9	 
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
- 52.219.177.217	 
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
+ 52.219.80.83	 
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
- 52.219.110.1	 
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
+ 52.219.232.177	 
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
- 52.219.179.49	 
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
+ 52.219.106.41	 
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
+ 16.12.65.81	 
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
- 52.219.179.145	 
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
+ 52.219.100.26	 
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
- 52.219.100.202	 
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
+ 16.12.66.17	 
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
- 52.219.105.185	 
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
+ 52.219.177.185	 
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
- 52.219.102.209	 
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
+ 52.219.177.41	 
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
- 52.219.110.49	 
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
+ 52.219.178.185	 
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
- 52.219.179.161	 
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
+ 52.219.179.17	 
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
- 52.219.232.161	 
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
+ 52.219.103.25	 
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
+ 52.219.98.209	 
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
- 52.219.98.9	 
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
+ 52.219.176.193	 
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
- 52.219.178.169	 
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
+ 52.219.97.105	 
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
- 52.219.106.57	 
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
+ 52.219.100.2	 
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
- 52.219.98.217	 
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
+ 52.219.233.81	 
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
- 52.219.232.217	 
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
+ 52.219.178.217	 
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
- 52.219.104.66	 
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
+ 52.219.141.57	 
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
- 52.219.94.129	 
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
+ 52.219.179.65	 
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
- 52.219.178.153	 
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
+ 52.219.92.113	 
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
+ 52.219.176.57	 
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
- 52.219.102.169	 
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
+ 52.219.105.225	 
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
- 16.12.65.201	 
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
+ 52.219.143.65	 
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
- 16.12.66.57	 
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
+ 52.219.104.202	 
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
- 16.12.65.233	 
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
+ 16.12.65.153	 
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
- 52.219.102.153	 
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
+ 16.12.64.137	 
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
- 16.12.66.9	 
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
- 52.219.93.9	 
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
+ 52.219.105.25	 
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
- 52.219.178.97	 
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
+ 52.219.97.17	 
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
- 16.12.65.161	 
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
+ 52.219.108.89	 
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
- 16.12.64.161	 
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
+ 52.219.233.105	 
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
- 52.219.177.233	 
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
+ 52.219.99.1	 
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
- 52.219.232.185	 
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
+ 52.219.101.105	 
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
- 52.219.94.49	 
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
+ 52.219.100.218	 
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
- 52.219.92.241	 
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
+ 52.219.93.185	 
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
- 52.219.88.218	 
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
+ 52.219.102.153	 
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
- 52.219.232.129	 
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
+ 52.219.177.89	 
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
- 52.219.98.193	 
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
+ 52.219.143.57	 
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
- 52.219.106.217	 
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
+ 52.219.179.81	 
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
- 16.12.64.121	 
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
+ 52.219.177.129	 
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
- 52.219.92.73	 
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
+ 16.12.66.1	 
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
- 52.219.97.89	 
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
+ 52.219.232.225	 
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
- 52.219.109.57	 
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
+ 16.12.64.1	 
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
- 52.219.102.233	 
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
+ 52.219.92.193	 
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
- 52.219.80.138	 
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
+ 52.219.109.233	 
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
- 52.219.99.9	 
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
+ 16.12.65.217	 
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
- 52.219.106.121	 
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
+ 52.219.102.73	 
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
- 52.219.93.241	 
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
+ 52.219.98.65	 
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
- 52.219.92.17	 
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
+ 52.219.98.153	 
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
- 52.219.93.209	 
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
+ 52.219.101.129	 
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
- 52.219.108.9	 
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
+ 52.219.176.65	 
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
- 52.219.176.161	 
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
+ 52.219.103.33	 
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
- 52.219.80.146	 
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
+ 52.219.84.59	 
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
- 52.219.100.234	 
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
+ 52.219.110.153	 
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
- 52.219.179.33	 
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
+ 52.219.80.170	 
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
- 16.12.64.9	 
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
+ 52.219.104.50	 
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
+ 52.219.94.137	 
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
- 52.219.233.57	 
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
+ 52.219.106.225	 
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
- 52.219.99.41	 
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
+ 52.219.93.249	 
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
- 52.219.102.121	 
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
+ 52.219.177.137	 
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
- 52.219.178.145	 
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
+ 52.219.177.241	 
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
- 52.219.96.90	 
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
+ 16.12.66.33	 
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
- 52.219.96.202	 
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
+ 52.219.176.113	 
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
- 52.219.80.122	 
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
- 52.219.110.97	 
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
- 52.219.104.10	 
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

```diff
- 52.219.84.226	 
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
+ 52.219.102.217	 
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
+ 52.219.98.121	 
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
- 52.219.93.65	 
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
+ 52.219.232.241	 
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
+ 16.12.65.121	 
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
+ 52.219.105.169	 
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
- 52.219.106.225	 
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
+ 52.219.105.41	 
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
- 52.219.84.114	 
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
+ 52.219.142.49	 
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
- 52.219.92.249	 
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
+ 52.219.176.177	 
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
- 52.219.141.73	 
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
+ 52.219.92.177	 
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
- 52.219.109.209	 
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
+ 52.219.176.97	 
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
- 16.12.65.193	 
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
+ 52.219.92.161	 
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
- 52.219.102.49	 
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
+ 52.219.177.209	 
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
- 52.219.109.177	 
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
+ 52.219.80.51	 
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
+ 52.219.104.154	 
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
- 52.219.176.233	 
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
+ 16.12.64.177	 
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
- 52.219.99.49	 
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
+ 52.219.101.97	 
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
+ 52.219.94.249	 
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
- 52.219.99.81	 
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
+ 52.219.110.233	 
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
+ 52.219.93.161	 
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
- 52.219.84.51	 
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
+ 52.219.80.234	 
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
- 52.219.100.26	 
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
+ 52.219.93.17	 
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
- 52.219.178.121	 
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
+ 52.219.102.97	 
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
- 16.12.64.1	 
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
+ 52.219.106.217	 
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
- 52.219.100.178	 
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
+ 52.219.103.57	 
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
- 52.219.92.153	 
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
+ 52.219.178.145	 
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
+ 52.219.94.33	 
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
+ 52.219.109.201	 
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
- 52.219.176.1	 
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
+ 52.219.94.161	 
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
- 52.219.176.217	 
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
+ 52.219.178.17	 
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
- 52.219.178.161	 
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
+ 52.219.109.177	 
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
- 52.219.178.73	 
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
+ 52.219.93.105	 
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
- 52.219.178.33	 
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
+ 52.219.110.177	 
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
- 52.219.80.178	 
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
+ 52.219.99.81	 
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
- 52.219.176.153	 
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
+ 52.219.108.65	 
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
- 52.219.104.202	 
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
+ 52.219.178.153	 
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
- 52.219.84.178	 
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
+ 52.219.106.9	 
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
+ 52.219.97.89	 
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
+ 52.219.178.113	 
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

```diff
- 52.219.177.121	 
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
+ 52.219.105.89	 
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
- 52.219.94.249	 
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
+ 52.219.88.98	 
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
- 52.219.111.97	 
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
+ 52.219.108.185	 
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
- 52.219.179.169	 
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
+ 52.219.177.17	 
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
- 52.219.105.73	 
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
+ 52.219.94.105	 
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
- 52.219.94.225	 
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
+ 52.219.177.249	 
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
- 52.219.233.105	 
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
+ 52.219.101.169	 
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
- 52.219.100.66	 
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
+ 16.12.65.41	 
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
- 52.219.176.249	 
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
+ 52.219.176.145	 
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
- 52.219.106.193	 
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
+ 52.219.108.225	 
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
- 52.219.106.241	 
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
+ 52.219.93.113	 
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
+ 52.219.94.81	 
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
- 52.219.178.49	 
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
+ 52.219.176.9	 
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
- 52.219.80.98	 
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
+ 52.219.103.89	 
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
- 52.219.88.91	 
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
+ 52.219.95.41	 
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
- 52.219.102.105	 
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
+ 16.12.65.113	 
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
- 52.219.105.177	 
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
- 52.219.92.33	 
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
+ 52.219.104.98	 
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
- 52.219.88.226	 
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
- 52.219.94.33	 
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
+ 52.219.98.225	 
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
+ 52.219.108.209	 
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
+ 52.219.92.89	 
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
- 52.219.105.169	 
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
+ 52.219.106.33	 
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
- 52.219.232.225	 
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
+ 52.219.97.217	 
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
- 52.219.93.129	 
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
+ 52.219.176.153	 
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
- 52.219.178.9	 
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
+ 52.219.97.33	 
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
+ 52.219.100.90	 
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
+ 52.219.102.9	 
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
- 52.219.94.73	 
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
- 52.219.92.81	 
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
+ 52.219.92.185	 
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
- 52.219.232.145	 
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
+ 52.219.110.65	 
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
- 52.219.101.249	 
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
+ 52.219.110.121	 
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
- 52.219.108.177	 
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
+ 52.219.102.81	 
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
- 52.219.106.129	 
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
+ 16.12.65.105	 
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
- 52.219.179.57	 
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
- 52.219.143.41	 
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
+ 52.219.178.233	 
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
- 52.219.108.241	 
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
+ 52.219.97.81	 
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
- 52.219.84.202	 
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
+ 52.219.95.25	 
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
- 52.219.101.81	 
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
+ 52.219.104.58	 
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
- 52.219.101.25	 
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
+ 52.219.179.121	 
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
+ 52.219.88.218	 
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
- 52.219.179.177	 
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
+ 52.219.110.249	 
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
- 52.219.107.33	 
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
+ 16.12.65.233	 
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
+ 52.219.97.121	 
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
- 52.219.142.73	 
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
+ 52.219.108.9	 
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
+ 52.219.106.145	 
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
- 52.219.97.1	 
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
+ 52.219.110.185	 
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
- 16.12.66.49	 
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
+ 16.12.65.177	 
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
- 52.219.108.201	 
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
+ 52.219.98.185	 
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
- 52.219.94.145	 
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
+ 52.219.101.233	 
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
- 52.219.106.249	 
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
+ 52.219.93.217	 
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
- 52.219.179.73	 
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
+ 52.219.84.210	 
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
- 52.219.178.105	 
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
+ 52.219.80.75	 
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
- 52.219.98.161	 
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
+ 52.219.102.65	 
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
- 16.12.65.81	 
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
+ 52.219.111.121	 
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
- 52.219.102.41	 
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
+ 52.219.178.73	 
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
- 52.219.111.89	 
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
+ 52.219.106.81	 
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
+ 52.219.232.57	 
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
- 16.12.65.25	 
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
+ 52.219.104.18	 
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
- 52.219.142.25	 
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
+ 52.219.176.225	 
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
- 52.219.93.1	 
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
+ 52.219.84.218	 
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
- 16.12.65.113	 
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
+ 52.219.101.193	 
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
+ 52.219.232.185	 
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
- 52.219.109.49	 
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
+ 52.219.96.34	 
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
- 52.219.99.33	 
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
+ 52.219.101.9	 
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
- 52.219.103.49	 
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
+ 52.219.105.49	 
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
- 52.219.110.41	 
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
+ 52.219.80.178	 
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
- 52.219.99.57	 
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
- 52.219.177.17	 
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
+ 52.219.96.241	 
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
- 52.219.103.25	 
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
+ 52.219.99.57	 
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
- 52.219.109.33	 
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
+ 52.219.80.67	 
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
- 52.219.110.129	 
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
+ 52.219.102.201	 
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
- 52.219.176.33	 
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
+ 52.219.105.201	 
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
+ 52.219.103.65	 
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
- 52.219.92.25	 
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
+ 52.219.179.161	 
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
- 52.219.108.121	 
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
+ 52.219.106.97	 
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
- 52.219.110.201	 
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
+ 52.219.107.73	 
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
- 52.219.178.185	 
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
+ 52.219.143.1	 
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
+ 52.219.109.25	 
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
+ 52.219.104.42	 
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
- 52.219.93.145	 
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
+ 52.219.102.209	 
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
- 52.219.177.73	 
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
+ 52.219.108.33	 
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
- 52.219.94.41	 
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
+ 52.219.179.97	 
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
- 52.219.110.241	 
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
+ 52.219.93.41	 
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
- 52.219.96.50	 
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
- 52.219.80.83	 
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
+ 52.219.93.49	 
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
- 52.219.109.217	 
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
+ 52.219.110.209	 
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
+ 52.219.97.249	 
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
- 52.219.109.41	 
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
+ 52.219.100.186	 
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
- 16.12.66.17	 
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
+ 52.219.99.25	 
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
+ 52.219.102.241	 
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
- 52.219.178.65	 
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
+ 52.219.102.137	 
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
- 16.12.64.145	 
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
+ 52.219.108.81	 
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
- 52.219.97.145	 
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
+ 52.219.84.226	 
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
- 52.219.93.249	 
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
+ 52.219.108.145	 
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
- 16.12.64.81	 
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
+ 16.12.64.41	 
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
- 52.219.177.193	 
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
+ 52.219.178.9	 
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
- 52.219.84.234	 
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
+ 16.12.65.145	 
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
- 52.219.107.57	 
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
+ 52.219.109.121	 
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
+ 52.219.93.153	 
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
- 52.219.232.153	 
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
+ 52.219.109.193	 
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
- 52.219.92.65	 
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
+ 52.219.232.33	 
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
- 52.219.105.81	 
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
+ 52.219.96.50	 
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
- 52.219.106.201	 
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
+ 52.219.178.49	 
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
- 52.219.93.33	 
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
+ 52.219.92.201	 
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
- 52.219.111.105	 
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
+ 52.219.98.177	 
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
+ 52.219.106.89	 
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
- 52.219.103.33	 
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
+ 52.219.107.33	 
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
- 52.219.111.113	 
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
+ 52.219.179.105	 
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
- 52.219.109.241	 
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
+ 52.219.92.137	 
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
- 52.219.101.17	 
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
+ 52.219.80.114	 
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
- 52.219.98.169	 
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
+ 52.219.111.1	 
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
- 52.219.143.57	 
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
+ 52.219.97.233	 
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
- 52.219.94.233	 
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
+ 52.219.94.89	 
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
- 52.219.98.209	 
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
+ 52.219.101.1	 
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
+ 52.219.104.170	 
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
+ 52.219.100.34	 
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
- 52.219.106.41	 
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
+ 52.219.99.41	 
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
- 52.219.96.234	 
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
+ 52.219.178.177	 
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
- 52.219.101.161	 
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
+ 52.219.105.1	 
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
- 52.219.233.65	 
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
+ 52.219.80.130	 
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
- 16.12.66.33	 
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
+ 52.219.94.169	 
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
- 52.219.177.9	 
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
+ 52.219.96.2	 
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
- 52.219.104.34	 
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
+ 52.219.104.162	 
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
- 52.219.178.217	 
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
+ 16.12.65.73	 
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
- 52.219.84.194	 
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
+ 52.219.93.193	 
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
- 52.219.103.57	 
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
+ 52.219.84.194	 
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
- 52.219.142.81	 
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
+ 52.219.100.210	 
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
- 52.219.96.178	 
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
- 52.219.106.89	 
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
+ 52.219.106.73	 
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
- 52.219.101.121	 
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
+ 52.219.98.25	 
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
- 52.219.178.241	 
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
+ 52.219.111.113	 
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
- 52.219.99.65	 
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
+ 16.12.66.57	 
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
- 52.219.110.89	 
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
+ 52.219.92.25	 
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
- 52.219.102.177	 
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
+ 52.219.80.98	 
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
- 52.219.102.241	 
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
+ 52.219.109.249	 
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
- 52.219.111.73	 
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
- 52.219.109.185	 
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
- 52.219.176.73	 
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
+ 52.219.97.41	 
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
- 52.219.177.65	 
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
- 52.219.97.249	 
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
+ 52.219.106.185	 
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
- 52.219.108.249	 
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
+ 52.219.101.217	 
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
- 52.219.179.185	 
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
+ 52.219.111.25	 
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
- 52.219.98.225	 
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
+ 52.219.97.73	 
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
- 52.219.92.145	 
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
+ 52.219.176.241	 
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
- 52.219.94.193	 
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
+ 52.219.100.82	 
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
+ 52.219.102.177	 
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
- 52.219.108.193	 
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
+ 52.219.143.17	 
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
- 52.219.102.137	 
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
+ 52.219.105.161	 
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
- 52.219.111.65	 
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
+ 16.12.64.241	 
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
+ 52.219.98.145	 
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
+ 52.219.176.17	 
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
- 52.219.88.106	 
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
+ 52.219.104.82	 
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
- 52.219.104.98	 
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
+ 52.219.93.225	 
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
- 52.219.93.97	 
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
+ 52.219.110.49	 
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
- 52.219.97.185	 
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
+ 16.12.66.41	 
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
- 52.219.97.65	 
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
+ 52.219.88.138	 
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
- 52.219.106.105	 
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
+ 52.219.178.57	 
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
- 52.219.233.33	 
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
+ 52.219.80.162	 
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
- 52.219.93.185	 
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
+ 52.219.94.1	 
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
+ 52.219.109.153	 
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
- 52.219.111.129	 
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
+ 52.219.110.73	 
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
- 52.219.143.49	 
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
+ 52.219.80.154	 
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
- 52.219.92.193	 
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
+ 52.219.92.209	 
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
+ 52.219.232.25	 
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
- 52.219.93.233	 
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
+ 52.219.106.49	 
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
- 52.219.105.1	 
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
+ 52.219.232.41	 
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
+ 52.219.105.217	 
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
- 52.219.176.49	 
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
+ 52.219.105.73	 
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
- 52.219.179.209	 
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
+ 52.219.84.162	 
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
- 52.219.101.225	 
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
+ 52.219.109.185	 
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
- 52.219.176.193	 
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
+ 52.219.176.233	 
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
+ 52.219.106.105	 
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
- 52.219.94.137	 
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
+ 52.219.109.33	 
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
- 52.219.103.65	 
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
+ 52.219.94.193	 
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
- 52.219.97.201	 
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
+ 52.219.111.137	 
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
- 52.219.100.218	 
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
+ 52.219.104.210	 
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
+ 52.219.105.193	 
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
- 52.219.141.49	 
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
+ 52.219.141.33	 
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
- 52.219.98.129	 
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
- 52.219.95.25	 
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
- 52.219.88.130	 
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
+ 52.219.105.241	 
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
- 52.219.92.185	 
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
+ 52.219.108.113	 
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
- 52.219.142.33	 
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
- 52.219.101.177	 
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
+ 52.219.109.145	 
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
- 52.219.106.73	 
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
+ 52.219.88.210	 
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
- 52.219.179.121	 
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
+ 52.219.104.26	 
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
- 52.219.108.105	 
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
+ 52.219.106.201	 
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
- 52.219.98.57	 
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
+ 52.219.108.169	 
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
+ 52.219.84.202	 
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
- 52.219.98.241	 
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
+ 52.219.105.145	 
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
- 16.12.65.241	 
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
+ 52.219.102.57	 
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
+ 52.219.176.217	 
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
- 52.219.84.218	 
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
+ 52.219.110.201	 
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
- 52.219.108.217	 
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
+ 52.219.179.113	 
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
- 52.219.96.154	 
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
+ 52.219.102.145	 
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
- 52.219.179.65	 
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
+ 52.219.96.146	 
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
- 52.219.106.233	 
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
+ 16.12.65.17	 
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
- 52.219.105.25	 
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
+ 52.219.106.121	 
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
- 52.219.88.154	 
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
+ 52.219.102.1	 
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
- 16.12.65.89	 
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
+ 52.219.84.114	 
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
- 52.219.84.138	 
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
+ 52.219.94.217	 
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
+ 52.219.84.178	 
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
- 52.219.176.25	 
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
+ 52.219.179.201	 
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
- 52.219.177.201	 
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
+ 52.219.105.185	 
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
- 52.219.108.33	 
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
+ 52.219.106.25	 
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
- 16.12.65.217	 
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
+ 52.219.80.186	 
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
+ 52.219.92.249	 
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
- 52.219.96.10	 
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
+ 52.219.88.178	 
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
- 52.219.93.73	 
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
+ 52.219.232.161	 
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
- 52.219.104.18	 
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

```diff
+ 52.219.94.145	 
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
- 52.219.176.121	 
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
+ 52.219.92.241	 
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
+ 52.219.105.33	 
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
- 52.219.94.169	 
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
+ 52.219.108.41	 
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
+ 52.219.179.1	 
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
- 52.219.92.137	 
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
+ 52.219.109.97	 
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
- 52.219.101.233	 
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
+ 52.219.104.249	 
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
+ 52.219.101.41	 
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
- 52.219.94.209	 
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
- 52.219.88.51	 
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
+ 52.219.109.49	 
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
+ 16.12.64.129	 
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
- 52.219.233.81	 
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
- 52.219.141.57	 
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
+ 52.219.97.57	 
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
- 52.219.178.1	 
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
+ 52.219.100.194	 
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
- 16.12.64.185	 
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
+ 16.12.65.129	 
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
+ 52.219.97.161	 
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
- 52.219.102.225	 
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
+ 52.219.178.241	 
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
- 52.219.104.249	 
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
+ 52.219.97.209	 
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
- 52.219.100.18	 
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
- 52.219.97.177	 
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
+ 52.219.100.50	 
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
- 52.219.107.49	 
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
+ 52.219.109.217	 
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
+ 52.219.108.49	 
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
- 52.219.105.113	 
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
+ 52.219.107.57	 
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
- 16.12.65.33	 
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
+ 16.12.65.249	 
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
- 52.219.101.73	 
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
+ 52.219.96.194	 
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
- 52.219.93.161	 
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
+ 52.219.84.186	 
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
- 52.219.141.17	 
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
+ 52.219.177.25	 
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
- 16.12.64.201	 
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
+ 52.219.177.169	 
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
+ 52.219.143.73	 
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
+ 52.219.101.161	 
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
- 52.219.102.73	 
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
+ 52.219.101.225	 
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
+ 52.219.96.18	 
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
- 52.219.177.169	 
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
- 52.219.111.241	 
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
+ 52.219.88.51	 
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
+ 52.219.110.225	 
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
- 52.219.108.129	 
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
+ 52.219.103.73	 
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
- 52.219.92.121	 
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
+ 52.219.100.122	 
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
- 52.219.101.185	 
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
- 52.219.92.217	 
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
+ 52.219.100.10	 
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
- 52.219.110.17	 
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
+ 52.219.92.233	 
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
- 52.219.98.89	 
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
+ 52.219.109.1	 
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
- 52.219.88.98	 
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
- 16.12.65.17	 
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
+ 52.219.232.169	 
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
+ 52.219.105.129	 
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
- 52.219.80.226	 
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
+ 52.219.179.129	 
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
- 52.219.232.233	 
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
+ 52.219.178.121	 
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
- 52.219.105.145	 
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
+ 52.219.106.65	 
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
- 52.219.232.177	 
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
+ 52.219.98.129	 
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
- 52.219.102.9	 
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
+ 52.219.111.129	 
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
- 52.219.105.233	 
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
+ 52.219.96.178	 
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
- 52.219.101.169	 
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
+ 52.219.176.161	 
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
- 52.219.141.33	 
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
+ 16.12.65.161	 
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
- 52.219.102.185	 
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
+ 52.219.176.25	 
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
- 52.219.88.138	 
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
+ 52.219.142.1	 
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
- 52.219.100.194	 
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
- 52.219.84.162	 
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
+ 52.219.177.193	 
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
+ 52.219.98.105	 
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
- 52.219.80.130	 
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
+ 52.219.80.146	 
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
- 52.219.179.41	 
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
+ 52.219.110.89	 
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
+ 52.219.141.73	 
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
- 52.219.98.153	 
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
+ 52.219.142.89	 
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
- 52.219.108.153	 
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
+ 52.219.179.185	 
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
- 52.219.98.25	 
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
+ 16.12.65.65	 
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
+ 16.12.64.121	 
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
- 52.219.105.121	 
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
- 52.219.106.169	 
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
+ 52.219.104.106	 
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
- 16.12.65.41	 
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
- 52.219.110.81	 
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
+ 16.12.65.49	 
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
+ 52.219.107.49	 
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
- 52.219.141.41	 
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
+ 52.219.101.17	 
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
- 52.219.84.98	 
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
+ 16.12.64.201	 
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
- 16.12.65.121	 
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
+ 52.219.97.25	 
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
- 52.219.105.65	 
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
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 52.219.80.218	 
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
- 52.219.106.153	 
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
+ 16.12.65.193	 
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
+ 52.219.105.17	 
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
+ 52.219.106.249	 
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
- 52.219.177.153	 
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
+ 52.219.101.81	 
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
- 52.219.100.58	 
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
+ 52.219.98.57	 
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
+ 52.219.108.193	 
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
- 52.219.101.113	 
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
+ 52.219.96.210	 
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
+ 52.219.109.9	 
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
+ 52.219.179.209	 
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
<code>52.219.179.137</code>
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
<code>52.219.179.137</code>
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
+ 52.219.232.249	 
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
+ 52.219.179.225	 
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
+ 52.219.101.25	 
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
+ 52.219.101.177	 
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
+ 52.219.93.209	 
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
+ 52.219.100.18	 
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
+ 52.219.80.122	 
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
+ 52.219.88.234	 
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
+ 52.219.177.1	 
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
+ 52.219.106.1	 
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
+ 52.219.107.41	 
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
+ 52.219.102.129	 
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
+ 52.219.102.113	 
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
+ 52.219.92.105	 
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
+ 52.219.98.73	 
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
+ 52.219.176.249	 
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
+ 52.219.97.113	 
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
+ 52.219.88.162	 
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
+ 52.219.97.1	 
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
+ 52.219.102.33	 
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
+ 52.219.88.186	 
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
+ 52.219.110.241	 
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
+ 52.219.179.145	 
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
+ 52.219.142.73	 
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
+ 52.219.105.65	 
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
+ 52.219.111.73	 
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
+ 52.219.101.201	 
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
+ 52.219.88.202	 
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
+ 52.219.100.178	 
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
+ 52.219.88.67	 
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
+ 16.12.65.169	 
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
+ 52.219.97.169	 
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
+ 52.219.98.9	 
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
+ 52.219.94.73	 
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
+ 52.219.141.1	 
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
+ 52.219.101.49	 
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
+ 52.219.176.105	 
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
+ 52.219.232.65	 
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
+ 52.219.84.234	 
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
+ 52.219.80.138	 
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
+ 52.219.100.146	 
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
+ 52.219.96.249	 
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
+ 52.219.84.170	 
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
+ 52.219.97.65	 
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
+ 52.219.105.105	 
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
+ 52.219.97.185	 
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
+ 52.219.104.234	 
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
+ 52.219.105.113	 
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
+ 16.12.64.33	 
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
+ 52.219.101.57	 
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
+ 52.219.101.121	 
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
+ 52.219.80.106	 
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
+ 52.219.80.226	 
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
+ 52.219.100.241	 
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
+ 16.12.65.33	 
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
+ 52.219.104.122	 
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
+ 52.219.233.97	 
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
+ 52.219.96.202	 
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
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: cert-manager  
>**Type/Name**: deployment/cert-manager-webhook  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>6080</code>
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

```diff
+ 10.4.2.232	 
```
</td><td>
<code>6080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>6080</code>
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

```diff
+ 10.4.3.204	 
```
</td><td>
<code>6080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.33	 
```
</td><td>
<code>10250</code>
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

```diff
+ 10.4.3.101	 
```
</td><td>
<code>6080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.101</code>
</td><td>

```diff
+ 6080	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.204</code>
</td><td>

```diff
+ 6080	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.204</code>
</td><td>
<code>6080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.33	 
```
</td><td>
<code>10250</code>
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
<code>10.4.2.33</code>
</td><td>

```diff
+ 10250	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-user-mgmt  
>**Type/Name**: deployment/user-management-service  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.119	 
```
</td><td>
<code>15021</code>
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
+ 10.4.3.119	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.119</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.219</code>
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
<code>10.4.3.168</code>
</td><td>

```diff
+ 15006	 
```
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
+ 10.4.2.219	 
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
<code>10.4.2.219</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.43</code>
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-istio-ext-authz</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-policy-service  
>**Type/Name**: deployment/policymanagement  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.238	 
```
</td><td>
<code>15021</code>
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
- 10.4.2.216	 
```
</td><td>
<code>15001</code>
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
- 8080	 
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
<code>10.4.1.238</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 127.0.0.6	 
```
</td><td>
<code>8080</code>
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
+ 10.4.1.238	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.232</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.232</code>
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.79</code>
</td><td>

```diff
+ 15006	 
```
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
+ 10.4.2.79	 
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

```diff
+ 10.4.1.149	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.216</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.216	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-policy-service</code>
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
<code>10.4.2.216</code>
</td><td>

```diff
- 8080	 
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
- 10.4.12.68	 
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
<code>10.4.1.149</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-policy-service</code>
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
<code>10.4.2.216</code>
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.216</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
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
+ 10.4.1.238	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.238</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.21</code>
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

```diff
+ 10.4.3.223	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-knox-gateway</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.21</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.34	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-deo</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.83	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-knox-gateway</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.164	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-deo</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.27	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.91	 
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

```diff
+ 10.4.3.86	 
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

```diff
+ 10.4.2.231	 
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

```diff
+ 10.4.3.114	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-deo</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.107	 
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

```diff
+ 10.4.2.21	 
```
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: istio-system  
>**Type/Name**: deployment/istio-egressgateway  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.180</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.180</code>
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: statefulset/loki-write  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.50	 
```
</td><td>
<code>7946</code>
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
<code>10.4.1.50</code>
</td><td>

```diff
- 7946	 
```
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
<code>10.4.1.244</code>
</td><td>

```diff
+ 3100	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.1.244</code>
</td><td>
<code>3100</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.244	 
```
</td><td>
<code>3100</code>
</td><td>
<code>kubearmor</code>
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
<code>52.219.93.209</code>
</td><td>

```diff
- 443	 
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
<code>10.4.3.236</code>
</td><td>

```diff
+ 7946	 
```
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.50	 
```
</td><td>
<code>7946</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
- 5778	 
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
<code>52.219.110.65</code>
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
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.50</code>
</td><td>
<code>7946</code>
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
<code>10.4.1.50</code>
</td><td>
<code>7946</code>
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
<code>16.12.64.1</code>
</td><td>

```diff
- 443	 
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
- 52.219.98.177	 
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
- 52.219.105.193	 
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
+ 52.219.93.169	 
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
- 52.219.105.33	 
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
+ 52.219.100.42	 
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
- 52.219.104.194	 
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
- 52.219.233.73	 
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
+ 52.219.101.145	 
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
- 52.219.98.17	 
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
- 52.219.80.162	 
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
- 52.219.177.105	 
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
- 52.219.101.49	 
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
- 16.12.65.97	 
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
- 52.219.179.1	 
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
- 52.219.232.25	 
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
- 52.219.104.58	 
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
- 52.219.104.138	 
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
<code>52.219.88.106</code>
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
<code>52.219.88.106</code>
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
+ 52.219.96.226	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: kubecost  
>**Type/Name**: deployment/kubecost-prometheus-server  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.244	 
```
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.244</code>
</td><td>

```diff
+ 9090	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.1.244</code>
</td><td>
<code>9090</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy-minion  
>**Type/Name**: statefulset/divy-minion-9  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 172.20.3.44	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-saltstack</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_3f9a2af8bc_pull.ipc</code>
</td><td>
<code>N/A</code>
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
<code>172.20.3.44</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>accuknox-dev-saltstack</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_3f9a2af8bc_pull.ipc</code>
</td><td>
<code>N/A</code>
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
<code>172.20.3.44</code>
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-saltstack</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 172.20.3.44	 
```
</td><td>
<code>80</code>
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
<code>172.20.3.44</code>
</td><td>

```diff
- 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_3f9a2af8bc_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.3.44</code>
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_3f9a2af8bc_pull.ipc</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: default  
>**Type/Name**: deployment/trivy-operator-k8sgpt  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.238	 
```
</td><td>
<code>9090</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.238</code>
</td><td>

```diff
+ 9090	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.1.238</code>
</td><td>
<code>9090</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-saltstack  
>**Type/Name**: deployment/saltmaster  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>80</code>
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
+ 10.4.3.180	 
```
</td><td>
<code>80</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.164	 
```
</td><td>
<code>80</code>
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
- 10.4.3.180	 
```
</td><td>
<code>8000</code>
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
+ 10.4.2.126	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>80</code>
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
+ 10.4.3.206	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-divy-minion</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.139	 
```
</td><td>
<code>8000</code>
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
+ 10.4.1.13	 
```
</td><td>
<code>443</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.200	 
```
</td><td>
<code>8000</code>
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
+ 10.4.1.244	 
```
</td><td>
<code>80</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.162	 
```
</td><td>
<code>8000</code>
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
+ 10.4.2.202	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>8000</code>
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
+ 10.4.1.238	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.238	 
```
</td><td>
<code>80</code>
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
+ 10.4.3.201	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.126</code>
</td><td>

```diff
- 443	 
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
<code>10.4.2.146</code>
</td><td>

```diff
+ 8000	 
```
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.204	 
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
+ 10.4.2.47	 
```
</td><td>
<code>80</code>
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
- 10.4.1.244	 
```
</td><td>
<code>80</code>
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
+ 10.4.3.101	 
```
</td><td>
<code>80</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.119	 
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
+ 10.4.3.51	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-divy-minion</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.238	 
```
</td><td>
<code>8000</code>
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
+ 10.4.2.232	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.202	 
```
</td><td>
<code>8000</code>
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
- 10.4.1.238	 
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
- 10.4.3.101	 
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
+ 10.4.3.119	 
```
</td><td>
<code>80</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.13	 
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
+ 10.4.2.97	 
```
</td><td>
<code>80</code>
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
- 10.4.2.126	 
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
+ 10.4.2.146	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.175	 
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
+ 10.4.1.197	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-divy-minion</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.204</code>
</td><td>

```diff
- 8000	 
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
<code>10.4.3.204</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.126	 
```
</td><td>
<code>8000</code>
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
+ 10.4.3.4	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.13	 
```
</td><td>
<code>8000</code>
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
+ 10.4.2.175	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.232</code>
</td><td>

```diff
+ 443	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.180</code>
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.119	 
```
</td><td>
<code>443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.238	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.13	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.167	 
```
</td><td>
<code>443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.254	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.180</code>
</td><td>

```diff
+ 8000	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.157	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.244	 
```
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.12	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.204	 
```
</td><td>
<code>443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 80	 
```
</td><td>

```diff
+ 80	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.230	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.185	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.59	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.17	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.67	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.196	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.141	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>AF_UNIX</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>/var/run/salt/master/master_event_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>/var/run/salt/master/master_event_pull.ipc</code>
</td><td>
<code>N/A</code>
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
<code>/usr/bin/salt-run</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>

```diff
- /var/run/salt/master/master_event_pull.ipc	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/master/master_event_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>/var/run/salt/master/master_event_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>/usr/bin/python3.6</code>
</td><td>

```diff
+ /var/run/salt/master/master_event_pub.ipc	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/python3.6</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>/usr/bin/python3.6</code>
</td><td>
<code>/var/run/salt/master/master_event_pull.ipc</code>
</td><td>
<code>N/A</code>
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
<code>140.82.114.4</code>
</td><td>

```diff
+ 22	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
- 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>/usr/bin/salt-run</code>
</td><td>
<code>/var/run/salt/master/master_event_pull.ipc</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-observability-api  
>**Type/Name**: deployment/observability-api  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>15021</code>
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
<code>10.4.3.101</code>
</td><td>

```diff
- 15021	 
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
<code>10.4.3.168</code>
</td><td>

```diff
- 15006	 
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
<code>10.4.1.238</code>
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.249	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.144</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.144	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-observability-api</code>
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
+ 10.4.1.144	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.249</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-observability-api</code>
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
<code>10.4.3.249</code>
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.144</code>
</td><td>

```diff
- 8080	 
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
+ 10.4.3.249	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.144	 
```
</td><td>
<code>8080</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.144</code>
</td><td>
<code>8080</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-stackgres  
>**Type/Name**: deployment/stackgres-restapi  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.180</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.180</code>
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-grafana  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.13	 
```
</td><td>
<code>3000</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.13	 
```
</td><td>
<code>3000</code>
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

```diff
+ 10.4.3.167	 
```
</td><td>
<code>3000</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.123	 
```
</td><td>
<code>3000</code>
</td><td>
<code>ingress-nginx</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.13</code>
</td><td>

```diff
+ 3000	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.1.13</code>
</td><td>
<code>3000</code>
</td><td>
<code>kubearmor</code>
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
+ 3.136.241.236	 
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
<code>185.199.111.133</code>
</td><td>

```diff
- 443	 
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
<code>18.222.48.190</code>
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
<code>3.143.19.65</code>
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
<code>3.143.19.65</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.136.241.236</code>
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
<code>3.136.241.236</code>
</td><td>

```diff
- 587	 
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
+ 185.199.109.133	 
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
+ 34.120.177.193	 
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
- 3.128.56.183	 
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
+ 185.199.108.133	 
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
- 18.220.255.115	 
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
<code>18.222.48.190</code>
</td><td>

```diff
- 587	 
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
<code>172.20.126.24</code>
</td><td>

```diff
+ 3100	 
```
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 3.128.56.191	 
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
- 52.95.19.138	 
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
+ 3.128.56.136	 
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
+ 3.128.56.189	 
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
- 3.128.56.157	 
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
+ 3.128.56.191	 
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
- 3.128.56.188	 
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
+ 52.95.16.6	 
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
+ 3.128.56.144	 
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
- 3.128.56.144	 
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
- 3.128.56.167	 
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
+ 3.128.56.171	 
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
- 185.199.109.133	 
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
+ 3.128.56.174	 
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
+ 3.128.56.184	 
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
- 52.95.16.6	 
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
+ 52.95.21.107	 
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
- 3.128.56.139	 
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
- 3.128.56.171	 
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
+ 3.128.56.139	 
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
- 3.128.56.136	 
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
+ 99.78.178.101	 
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
+ 3.128.56.167	 
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
- 52.95.21.107	 
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
- 3.128.56.166	 
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
+ 99.78.176.76	 
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
- 99.78.178.181	 
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
+ 3.128.56.134	 
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
+ 99.78.180.84	 
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
+ 3.128.56.157	 
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
- 99.78.178.101	 
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
- 3.128.56.134	 
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
+ 3.128.56.166	 
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
- 3.128.56.184	 
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
+ 3.128.56.141	 
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
+ 3.128.56.129	 
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
- 3.128.56.174	 
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
- 99.78.180.84	 
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
+ 3.128.56.151	 
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
- 3.128.56.151	 
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
- 99.78.180.69	 
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
+ 52.95.19.138	 
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
- 52.95.17.167	 
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
+ 99.78.180.69	 
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
- 3.128.56.129	 
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
+ 99.78.178.181	 
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
- 3.128.56.189	 
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
+ 172.20.121.200	 
```
</td><td>
<code>15692</code>
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>3.128.56.189</code>
</td><td>

```diff
- 443	 
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
- 3.128.56.141	 
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
- 3.128.56.137	 
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
<code>10.4.1.85</code>
</td><td>

```diff
+ 9090	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 99.78.176.76	 
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
+ 10.4.1.88	 
```
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.85	 
```
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.128.56.188	 
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
<code>192.0.73.2</code>
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
<code>192.0.73.2</code>
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
+ 52.95.17.167	 
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
+ 3.128.56.137	 
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
+ 3.128.56.183	 
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
+ 3.130.194.143	 
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

```diff
+ 3.132.134.38	 
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

```diff
+ 18.220.96.227	 
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

```diff
+ 192.0.73.2	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-istio-ext-authz  
>**Type/Name**: deployment/istio-ext-authz  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.172	 
```
</td><td>
<code>8000</code>
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

```diff
+ 10.4.3.249	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.179	 
```
</td><td>
<code>9000</code>
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

```diff
+ 10.4.1.144	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.151</code>
</td><td>

```diff
+ 8000	 
```
</td><td>
<code>accuknox-dev-cluster-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.144	 
```
</td><td>
<code>8000</code>
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

```diff
- 10.4.1.36	 
```
</td><td>
<code>9000</code>
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

```diff
+ 10.4.1.151	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-cluster-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.149	 
```
</td><td>
<code>8000</code>
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

```diff
+ 10.4.2.216	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.149	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.162</code>
</td><td>

```diff
+ 8000	 
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
<code>10.4.1.162</code>
</td><td>
<code>8000</code>
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
+ 10.4.2.172	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.91	 
```
</td><td>
<code>8000</code>
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

```diff
+ 10.4.1.27	 
```
</td><td>
<code>8000</code>
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
+ 10.4.2.200	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.125	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.161	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.122	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.100	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.190	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.219	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.135	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.179	 
```
</td><td>
<code>9000</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.36	 
```
</td><td>
<code>9000</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.125	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.86	 
```
</td><td>
<code>8000</code>
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
+ 10.4.2.146	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.162	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-pulsar  
>**Type/Name**: deployment/pulsar-prometheus  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.21	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.143</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
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
<code>10.4.2.146</code>
</td><td>
<code>15020</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.111	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.144	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.143	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.146	 
```
</td><td>
<code>15020</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.146</code>
</td><td>

```diff
+ 15020	 
```
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-celery-exporter  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.119	 
```
</td><td>
<code>9808</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.119</code>
</td><td>

```diff
+ 9808	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.119</code>
</td><td>
<code>9808</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.121.200</code>
</td><td>
<code>5672</code>
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
+ 172.20.121.200	 
```
</td><td>
<code>5672</code>
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.121.200</code>
</td><td>

```diff
+ 5672	 
```
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.121.200</code>
</td><td>
<code>5672</code>
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Service</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-pulsar  
>**Type/Name**: statefulset/pulsar-zookeeper  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.21	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.143</code>
</td><td>

```diff
+ 2181	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
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
<code>10.4.2.143</code>
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.111	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.223	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.25	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.143	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 2181	 
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
<code>127.0.0.1</code>
</td><td>
<code>2181</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>2181</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>/usr/bin/nc.openbsd</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>2181</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-prometheus-cloudwatch-exporter  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.88	 
```
</td><td>
<code>9106</code>
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

```diff
+ 10.4.2.126	 
```
</td><td>
<code>9106</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.88	 
```
</td><td>
<code>9106</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.126</code>
</td><td>

```diff
+ 9106	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.126</code>
</td><td>
<code>9106</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: cattle-system  
>**Type/Name**: deployment/cattle-cluster-agent  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>

```diff
+ /usr/lib/git/git-remote-http	 
```
</td><td>
<code>/usr/lib/git/git</code>
</td><td>Allow</td></tr><tr><td>

```diff
+ /usr/lib/git/git	 
```
</td><td>

```diff
+ /usr/lib/git/git	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/lib/git/git</code>
</td><td>

```diff
+ /usr/lib/git/git-remote-https	 
```
</td><td>Allow</td></tr></table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>34.208.213.149</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>34.208.213.149</code>
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
+ 52.36.54.134	 
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
<code>52.36.54.134</code>
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
<code>52.36.54.134</code>
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
+ 34.208.213.149	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>
<code>/usr/lib/git/git-remote-http</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /usr/lib/git/git-remote-http	 
```
</td><td>
<code>52.36.54.134</code>
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
<code>/usr/lib/git/git-remote-http</code>
</td><td>

```diff
+ 34.208.213.149	 
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
<code>/usr/lib/git/git-remote-http</code>
</td><td>
<code>52.36.54.134</code>
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
<code>/usr/lib/git/git-remote-http</code>
</td><td>
<code>52.36.54.134</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/usr/lib/git/git-remote-http</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
+ 4.236.192.251	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: daemonset/loki-promtail  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.13	 
```
</td><td>
<code>3101</code>
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

```diff
+ 10.4.3.204	 
```
</td><td>
<code>3101</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.204	 
```
</td><td>
<code>3101</code>
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

```diff
+ 10.4.1.244	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>3101</code>
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

```diff
+ 10.4.2.126	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.167	 
```
</td><td>
<code>3101</code>
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

```diff
+ 10.4.1.238	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.238	 
```
</td><td>
<code>3101</code>
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

```diff
+ 10.4.3.167	 
```
</td><td>
<code>3101</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.244	 
```
</td><td>
<code>3101</code>
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

```diff
+ 10.4.1.13	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.101</code>
</td><td>

```diff
+ 3101	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.101</code>
</td><td>
<code>3101</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.119	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>3101</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>5778</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>5778</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
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
+ 10.4.2.157	 
```
</td><td>
<code>8200</code>
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

```diff
- 10.4.3.37	 
```
</td><td>
<code>8200</code>
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

```diff
- 10.4.3.248	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.1.12	 
```
</td><td>
<code>8200</code>
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

```diff
- 10.4.1.230	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.201	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.4	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.254	 
```
</td><td>
<code>8200</code>
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

```diff
- 10.4.1.200	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.2.26	 
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
+ 10.4.3.35	 
```
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.88	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.1.27	 
```
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
+ 10.4.2.146	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.2.91	 
```
</td><td>
<code>8200</code>
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

```diff
- 10.4.3.139	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.2.250	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.2.131	 
```
</td><td>
<code>8200</code>
</td><td>
<code>cms-test</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.229	 
```
</td><td>
<code>8200</code>
</td><td>
<code>cms-test</code>
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
<code>10.4.2.21</code>
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.230	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.1.185	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.196	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.2.59	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.67	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.1.228	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.2.141	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.1.17	 
```
</td><td>
<code>8200</code>
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

```diff
+ 10.4.3.120	 
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
+ 10.4.2.21	 
```
</td><td>
<code>8200</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>99.78.180.183</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>99.78.180.183</code>
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
<code>99.78.176.248</code>
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
<code>99.78.176.248</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: istio-system  
>**Type/Name**: deployment/istio-ingressgateway  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>31400</code>
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
- 0	 
```
</td><td>
<code>N/A</code>
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
<code>10.4.2.175</code>
</td><td>

```diff
+ 8443	 
```
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.13</code>
</td><td>

```diff
- 8443	 
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
<code>10.4.1.244</code>
</td><td>

```diff
+ 31400	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.238	 
```
</td><td>
<code>8443</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.13	 
```
</td><td>
<code>8443</code>
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
+ 10.4.1.244	 
```
</td><td>
<code>31400</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.167</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.175	 
```
</td><td>
<code>8443</code>
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
+ 10.4.1.13	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>8443</code>
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
- 10.4.1.244	 
```
</td><td>
<code>31400</code>
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
+ 10.4.3.119	 
```
</td><td>
<code>31400</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.180	 
```
</td><td>
<code>15021</code>
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
- 10.4.3.180	 
```
</td><td>
<code>8443</code>
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
+ 10.4.3.204	 
```
</td><td>
<code>31400</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>31400</code>
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
+ 10.4.3.101	 
```
</td><td>
<code>31400</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>8443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.13</code>
</td><td>

```diff
+ 15021	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.1.244</code>
</td><td>
<code>31400</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.126	 
```
</td><td>
<code>31400</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.101</code>
</td><td>

```diff
+ 8443	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>31400</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>31400</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 0	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>8443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.43</code>
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.216	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.107	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.43</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.43	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-divy</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.43</code>
</td><td>
<code>80</code>
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
<code>10.4.2.172</code>
</td><td>

```diff
- 8080	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.107</code>
</td><td>
<code>80</code>
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
- 10.4.2.172	 
```
</td><td>
<code>8080</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.172</code>
</td><td>
<code>8080</code>
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
- 10.4.2.216	 
```
</td><td>
<code>8080</code>
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
- 10.4.3.179	 
```
</td><td>
<code>8080</code>
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
+ 10.4.2.172	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.149	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.27	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.162</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-vulnerability-service</code>
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
<code>10.4.1.162</code>
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.36	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.179	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.91	 
```
</td><td>
<code>8080</code>
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
<code>10.4.2.219</code>
</td><td>

```diff
+ 8081	 
```
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
+ 10.4.3.86	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.146	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
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
+ 10.4.2.89	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.66	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.0.1</code>
</td><td>

```diff
- 443	 
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
<code>10.4.1.73</code>
</td><td>

```diff
+ 27017	 
```
</td><td>
<code>accuknox-dev-mongodb</code>
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
<code>10.4.3.66</code>
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.73</code>
</td><td>

```diff
- 27017	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.73</code>
</td><td>
<code>27017</code>
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
+ 10.4.1.73	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 3.140.105.0	 
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
<code>52.219.176.57</code>
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
<code>52.219.176.57</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-vault  
>**Type/Name**: daemonset/consul-consul-client  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.41	 
```
</td><td>
<code>8301</code>
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

```diff
+ 10.4.3.23	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.160	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
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
<code>10.4.3.160</code>
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>UDP</code>
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>10.4.2.68</code>
</td><td>

```diff
+ 8301	 
```
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>8501</code>
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
- 10.4.1.179	 
```
</td><td>
<code>8301</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
- 8501	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>8501</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- UDP	 
```
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>10.4.2.68</code>
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>8501</code>
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
<code>3.160.22.90</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 3.160.22.81	 
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
- 3.160.22.17	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: rabbitmq  
>**Type/Name**: statefulset/rabbitmq-server  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl_child_setup	 
```
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code>
</td><td>Allow</td></tr><tr><td>

```diff
- /bin/sh	 
```
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/epmd</code>
</td><td>Allow</td></tr><tr><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl	 
```
</td><td>
<code>/usr/bin/dirname</code>
</td><td>Allow</td></tr><tr><td>

```diff
- /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec	 
```
</td><td>
<code>/usr/bin/dirname</code>
</td><td>Allow</td></tr><tr><td>

```diff
+ /bin/dash	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>

```diff
- /bin/sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code>
</td><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/dyn_erl	 
```
</td><td>Allow</td></tr><tr><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec	 
```
</td><td>
<code>/usr/bin/basename</code>
</td><td>Allow</td></tr><tr><td>
<code>/bin/dash</code>
</td><td>

```diff
+ /bin/df	 
```
</td><td>Allow</td></tr><tr><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erlexec</code>
</td><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/dyn_erl	 
```
</td><td>Allow</td></tr></table>

</details>
<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.244	 
```
</td><td>
<code>5672</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.244</code>
</td><td>

```diff
+ 5672	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.88</code>
</td><td>
<code>15691</code>
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
<code>10.4.1.244</code>
</td><td>
<code>5672</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.208	 
```
</td><td>
<code>5672</code>
</td><td>
<code>accuknox-dev-monitoring</code>
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
<code>10.4.1.228</code>
</td><td>
<code>5671</code>
</td><td>
<code>accuknox-dev-divy</code>
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
<code>10.4.1.88</code>
</td><td>
<code>15691</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.250	 
```
</td><td>
<code>5671</code>
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
<code>10.4.1.228</code>
</td><td>

```diff
+ 5671	 
```
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

```diff
+ 10.4.3.35	 
```
</td><td>
<code>5671</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.4	 
```
</td><td>
<code>5671</code>
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

```diff
+ 10.4.2.141	 
```
</td><td>
<code>5671</code>
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

```diff
+ 10.4.1.228	 
```
</td><td>
<code>5671</code>
</td><td>
<code>accuknox-dev-divy</code>
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
- 10.4.3.80	 
```
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 4369	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- UDP	 
```
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.80</code>
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/beam.smp</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>4369</code>
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
<code>/opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>

```diff
+ /opt/bitnami/erlang/lib/erlang/erts-14.1.1/bin/erl	 
```
</td><td>
<code>N/A</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-agents  
>**Type/Name**: deployment/feeder-service  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 3.131.136.73	 
```
</td><td>
<code>3000</code>
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
<code>3.131.136.73</code>
</td><td>

```diff
- 3000	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.131.136.73</code>
</td><td>
<code>3000</code>
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
+ 18.224.35.36	 
```
</td><td>
<code>3000</code>
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
<code>18.224.35.36</code>
</td><td>

```diff
+ 3000	 
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
<code>18.224.35.36</code>
</td><td>
<code>3000</code>
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
+ 3.139.187.114	 
```
</td><td>
<code>3000</code>
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
<code>3.139.187.114</code>
</td><td>

```diff
+ 3000	 
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
<code>3.139.187.114</code>
</td><td>
<code>3000</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-agents  
>**Type/Name**: deployment/policy-enforcement-agent  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>18.189.154.90</code>
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
<code>18.189.154.90</code>
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
<code>18.223.230.159</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>18.223.230.159</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: statefulset/prometheus-prometheus-kube-prometheus-prometheus  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.75	 
```
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.220	 
```
</td><td>
<code>9090</code>
</td><td>
<code>accuknox-dev-monitoring</code>
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
+ 10.4.3.5	 
```
</td><td>
<code>10250</code>
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
+ 10.4.3.100	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.36	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.111	 
```
</td><td>
<code>10250</code>
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
- 10.4.3.84	 
```
</td><td>
<code>10250</code>
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
+ 10.4.1.50	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.50	 
```
</td><td>
<code>10250</code>
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
- 10.4.1.36	 
```
</td><td>
<code>10250</code>
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
- 10.4.3.100	 
```
</td><td>
<code>10250</code>
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
+ 10.4.3.44	 
```
</td><td>
<code>10250</code>
</td><td>
<code>cloud-watch</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.84	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.112	 
```
</td><td>
<code>10250</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.252	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.137</code>
</td><td>

```diff
- 15691	 
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
<code>10.4.3.180</code>
</td><td>

```diff
+ 10250	 
```
</td><td>
<code>kube-system</code>
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
<code>172.20.31.227</code>
</td><td>
<code>8443</code>
</td><td>
<code>testing</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.31.227</code>
</td><td>

```diff
+ 8443	 
```
</td><td>
<code>testing</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.209</code>
</td><td>

```diff
- 15691	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.209</code>
</td><td>
<code>15691</code>
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
- 10.4.2.148	 
```
</td><td>
<code>15691</code>
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
+ 10.4.3.101	 
```
</td><td>
<code>10250</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 172.20.127.67	 
```
</td><td>
<code>15692</code>
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
<code>10.4.1.209</code>
</td><td>

```diff
+ 15691	 
```
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>10250</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.252</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
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
<code>10.4.1.53</code>
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
+ 10.4.1.13	 
```
</td><td>
<code>10250</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>9100</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.232</code>
</td><td>

```diff
+ 9100	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.204	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.244	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.175</code>
</td><td>

```diff
+ 10249	 
```
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.80</code>
</td><td>

```diff
+ 15691	 
```
</td><td>
<code>rabbitmq</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>10249</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.53</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>9100</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.238	 
```
</td><td>
<code>10250</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.221	 
```
</td><td>
<code>9153</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.221</code>
</td><td>

```diff
+ 9153	 
```
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.167	 
```
</td><td>
<code>10250</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.53	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: cloud-watch  
>**Type/Name**: deployment/fluentd-fluentd-cloudwatch  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>N/A</code>
</td><td>
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>3.128.56.179</code>
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
<code>3.128.56.179</code>
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
- 3.128.56.142	 
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
<code>/opt/bitnami/ruby/bin/ruby</code>
</td><td>

```diff
+ 3.128.56.140	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.128.56.162</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<details>
<summary>Bind Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>Bind Port</th><th>Bind Address</th></tr><tr><td>
<code>AF_NETLINK</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
+ 0.0.0.0	 
```
</td><td>
<code>24224</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_NETLINK</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>0.0.0.0</code>
</td><td>
<code>24224</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_NETLINK	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy-minion  
>**Type/Name**: statefulset/divy-minion-10  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_33746e3e96_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_33746e3e96_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_33746e3e96_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_33746e3e96_pull.ipc</code>
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
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-pulsar  
>**Type/Name**: statefulset/pulsar-bookie  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.8098908	 
```
</td><td>
<code>8090</code>
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
+ 10.4.3.167	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.8098908</code>
</td><td>

```diff
- 8090	 
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
<code>10.4.3.167</code>
</td><td>

```diff
+ 8000	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.144	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.143</code>
</td><td>

```diff
+ 3181	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
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
<code>10.4.3.167</code>
</td><td>
<code>8000</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.111	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.21	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.143	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-reporter  
>**Type/Name**: deployment/reporter  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.172	 
```
</td><td>
<code>15001</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.146</code>
</td><td>
<code>15006</code>
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
<code>10.4.2.172</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>/usr/local/bin/pilot-agent</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>15020</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/google/chrome/chrome</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 45111	 
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
<code>10.4.2.146</code>
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /opt/google/chrome/chrome	 
```
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>45111</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 15000	 
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
+ 10.4.2.175	 
```
</td><td>
<code>15021</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>/usr/local/bin/pilot-agent</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 15020	 
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
<code>/usr/local/bin/pilot-agent</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>15020</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>

```diff
+ /usr/local/bin/pilot-agent	 
```
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>15020</code>
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
+ 10.4.2.146	 
```
</td><td>
<code>15001</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.146</code>
</td><td>

```diff
+ 15001	 
```
</td><td>
<code>accuknox-dev-reporter</code>
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
<code>10.4.2.172</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/google/chrome/chrome</code>
</td><td>

```diff
+ 172.217.5.10	 
```
</td><td>
<code>443</code>
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
<code>10.4.2.146</code>
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>N/A</code>
</td><td>
<code>/opt/google/chrome/chrome</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/opt/google/chrome/chrome</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /opt/google/chrome/chrome	 
```
</td><td>
<code>142.250.190.35</code>
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
+ 146.75.77.229	 
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
+ 104.17.24.14	 
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
+ 172.20.80.197	 
```
</td><td>
<code>80</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.146</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/pilot-agent</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>15000</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 45111	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/opt/google/chrome/chrome</code>
</td><td>

```diff
+ 142.250.190.35	 
```
</td><td>
<code>443</code>
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

```diff
+ ::1	 
```
</td><td>
<code>15000</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/bin/pilot-agent</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 15000	 
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
<code>::1</code>
</td><td>
<code>15000</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 15020	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /usr/local/bin/pilot-agent	 
```
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>15000</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<details>
<summary>Bind Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>Bind Port</th><th>Bind Address</th></tr><tr><td>
<code>AF_INET</code>
</td><td>
<code>/opt/google/chrome/chrome</code>
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
<code>AF_INET</code>
</td><td>

```diff
+ /opt/google/chrome/chrome	 
```
</td><td>
<code>127.0.0.1</code>
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
<code>/opt/google/chrome/chrome</code>
</td><td>

```diff
+ 127.0.0.1	 
```
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy  
>**Type/Name**: deployment/nginx  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.168	 
```
</td><td>
<code>80</code>
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
+ 10.4.3.146	 
```
</td><td>
<code>80</code>
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
- 10.4.3.146	 
```
</td><td>
<code>80</code>
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
+ 10.4.3.168	 
```
</td><td>
<code>80</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-agents  
>**Type/Name**: deployment/agents-operator  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>3.136.190.175</code>
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
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.136.190.175</code>
</td><td>
<code>8081</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>18.218.126.47</code>
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
+ 18.218.126.47	 
```
</td><td>
<code>8081</code>
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
<code>18.218.126.47</code>
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
+ 3.136.190.175	 
```
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
<code>18.188.253.145</code>
</td><td>

```diff
- 8090	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: ingress-nginx  
>**Type/Name**: deployment/ingress-nginx-controller  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>10246</code>
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

```diff
+ 10.4.3.101	 
```
</td><td>
<code>10254</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>45.79.181.104</code>
</td><td>

```diff
- 80	 
```
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
<code>10.4.2.126</code>
</td><td>

```diff
+ 10254	 
```
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>45.79.181.104</code>
</td><td>
<code>80</code>
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
<code>10.4.2.126</code>
</td><td>
<code>10254</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.204	 
```
</td><td>
<code>10254</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 10246	 
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
<code>198.235.24.2</code>
</td><td>

```diff
- 80	 
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
<code>159.89.53.40</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 222.217.86.135	 
```
</td><td>
<code>80</code>
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

```diff
+ 10.4.3.204	 
```
</td><td>
<code>10254</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.126	 
```
</td><td>
<code>10254</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 64.62.197.124	 
```
</td><td>
<code>80</code>
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
- 198.235.24.236	 
```
</td><td>
<code>80</code>
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
+ 64.23.136.190	 
```
</td><td>
<code>80</code>
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
- 141.98.11.152	 
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
- 172.105.128.11	 
```
</td><td>
<code>80</code>
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
+ 159.223.124.233	 
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
- 80.79.117.42	 
```
</td><td>
<code>80</code>
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
+ 3.84.129.243	 
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
- 205.210.31.88	 
```
</td><td>
<code>80</code>
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
+ 152.32.235.85	 
```
</td><td>
<code>80</code>
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
- 162.142.125.10	 
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
+ 34.65.104.163	 
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
- 41.216.188.119	 
```
</td><td>
<code>80</code>
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
+ 34.65.249.28	 
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
- 91.92.244.94	 
```
</td><td>
<code>80</code>
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
+ 35.240.121.17	 
```
</td><td>
<code>80</code>
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
- 141.98.11.152	 
```
</td><td>
<code>80</code>
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
+ 52.91.208.54	 
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
+ 106.75.162.237	 
```
</td><td>
<code>80</code>
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
- 205.210.31.59	 
```
</td><td>
<code>80</code>
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
+ 35.197.172.86	 
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
- 35.203.210.228	 
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
+ 66.160.133.234	 
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
- 3.255.209.25	 
```
</td><td>
<code>80</code>
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
- 162.216.150.90	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.137	 
```
</td><td>
<code>80</code>
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
- 87.236.176.100	 
```
</td><td>
<code>80</code>
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
+ 20.200.177.0	 
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
- 164.52.0.94	 
```
</td><td>
<code>80</code>
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
+ 159.203.192.37	 
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
- 18.170.61.65	 
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
+ 107.170.245.4	 
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
+ 52.90.196.158	 
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
- 205.210.31.157	 
```
</td><td>
<code>80</code>
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
+ 71.6.232.25	 
```
</td><td>
<code>80</code>
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
- 162.216.149.46	 
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
+ 104.237.145.170	 
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
- 162.142.125.216	 
```
</td><td>
<code>80</code>
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
+ 104.237.145.107	 
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
- 87.236.176.73	 
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
+ 54.237.245.103	 
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
- 87.236.176.201	 
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
+ 162.216.150.216	 
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
- 87.236.176.205	 
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
- 107.170.255.7	 
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
+ 35.228.0.242	 
```
</td><td>
<code>80</code>
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
- 172.104.11.51	 
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
+ 34.34.79.141	 
```
</td><td>
<code>80</code>
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
- 185.180.143.190	 
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
+ 192.155.90.220	 
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
+ 34.71.148.165	 
```
</td><td>
<code>80</code>
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
+ 183.136.225.9	 
```
</td><td>
<code>80</code>
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
- 87.236.176.212	 
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
+ 5.196.81.59	 
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
- 198.199.112.86	 
```
</td><td>
<code>80</code>
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
+ 5.188.210.227	 
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
- 87.236.176.209	 
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
+ 54.218.252.132	 
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
- 205.210.31.2	 
```
</td><td>
<code>80</code>
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
+ 35.92.63.218	 
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
+ 45.79.27.62	 
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
- 23.239.9.87	 
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
- 185.180.143.49	 
```
</td><td>
<code>80</code>
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
+ 165.154.225.239	 
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
+ 139.144.19.236	 
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
- 159.203.192.13	 
```
</td><td>
<code>80</code>
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
+ 178.128.64.217	 
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
+ 135.125.218.67	 
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
- 205.210.31.26	 
```
</td><td>
<code>80</code>
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
+ 167.71.136.228	 
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
- 198.235.24.156	 
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
+ 185.224.128.142	 
```
</td><td>
<code>80</code>
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
+ 18.229.12.159	 
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
- 80.79.117.42	 
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
+ 198.235.24.7	 
```
</td><td>
<code>80</code>
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
- 198.235.24.126	 
```
</td><td>
<code>80</code>
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
+ 102.129.232.53	 
```
</td><td>
<code>80</code>
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
- 103.195.101.209	 
```
</td><td>
<code>80</code>
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
+ 172.104.11.4	 
```
</td><td>
<code>80</code>
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
- 3.19.66.35	 
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
+ 154.61.75.158	 
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
- 161.35.190.246	 
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
- 184.168.99.253	 
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
+ 2.56.247.167	 
```
</td><td>
<code>80</code>
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
- 184.168.99.253	 
```
</td><td>
<code>80</code>
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
- 162.216.150.117	 
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
+ 181.214.166.113	 
```
</td><td>
<code>80</code>
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
- 114.96.103.33	 
```
</td><td>
<code>80</code>
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
+ 199.45.154.48	 
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
- 120.71.59.24	 
```
</td><td>
<code>80</code>
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
+ 35.203.210.222	 
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
- 185.180.143.188	 
```
</td><td>
<code>80</code>
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
+ 198.74.56.46	 
```
</td><td>
<code>80</code>
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
- 162.142.125.13	 
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
+ 45.134.26.97	 
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
- 65.49.20.66	 
```
</td><td>
<code>80</code>
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
+ 67.21.36.5	 
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
+ 45.79.163.53	 
```
</td><td>
<code>80</code>
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
- 192.99.166.176	 
```
</td><td>
<code>80</code>
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
- 45.95.146.86	 
```
</td><td>
<code>80</code>
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
+ 180.149.125.164	 
```
</td><td>
<code>80</code>
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
- 205.210.31.143	 
```
</td><td>
<code>80</code>
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
- 20.168.112.212	 
```
</td><td>
<code>80</code>
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
+ 62.233.50.179	 
```
</td><td>
<code>80</code>
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
- 44.200.0.62	 
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
+ 139.59.28.111	 
```
</td><td>
<code>80</code>
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
- 18.201.135.228	 
```
</td><td>
<code>80</code>
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
+ 159.223.60.143	 
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
- 18.201.135.228	 
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
+ 69.164.217.245	 
```
</td><td>
<code>80</code>
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
- 162.243.136.67	 
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
+ 66.240.236.116	 
```
</td><td>
<code>80</code>
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
- 3.252.131.89	 
```
</td><td>
<code>80</code>
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
+ 3.71.189.185	 
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
- 18.201.42.115	 
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
+ 192.155.88.231	 
```
</td><td>
<code>80</code>
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
- 107.170.229.63	 
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
+ 45.79.181.251	 
```
</td><td>
<code>80</code>
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
+ 167.94.138.49	 
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
+ 198.235.24.160	 
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
- 123.191.150.83	 
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
+ 193.118.53.194	 
```
</td><td>
<code>80</code>
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
- 87.236.176.160	 
```
</td><td>
<code>80</code>
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
- 111.224.234.55	 
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
+ 106.227.49.113	 
```
</td><td>
<code>80</code>
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
- 45.79.172.21	 
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
+ 36.41.75.167	 
```
</td><td>
<code>80</code>
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
- 192.241.197.4	 
```
</td><td>
<code>80</code>
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
+ 182.44.10.67	 
```
</td><td>
<code>80</code>
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
- 164.92.117.229	 
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
+ 180.149.125.170	 
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
- 45.33.80.243	 
```
</td><td>
<code>80</code>
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
+ 51.158.185.213	 
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
- 198.235.24.233	 
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
- 139.59.37.187	 
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
+ 137.184.98.209	 
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
- 34.67.136.168	 
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
+ 180.149.125.165	 
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
- 44.197.132.235	 
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
+ 159.223.199.149	 
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
+ 85.203.47.187	 
```
</td><td>
<code>80</code>
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
- 138.197.90.25	 
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
+ 85.203.47.199	 
```
</td><td>
<code>80</code>
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
+ 85.203.47.181	 
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
- 192.241.197.22	 
```
</td><td>
<code>80</code>
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
- 90.151.171.106	 
```
</td><td>
<code>80</code>
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
+ 184.72.66.213	 
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
- 45.56.77.151	 
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
- 192.241.215.51	 
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
+ 128.14.134.170	 
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
- 172.104.28.51	 
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
+ 185.254.196.173	 
```
</td><td>
<code>80</code>
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
- 43.229.88.115	 
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
- 65.49.1.106	 
```
</td><td>
<code>80</code>
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
+ 138.68.129.116	 
```
</td><td>
<code>80</code>
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
+ 34.76.185.29	 
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
- 162.243.142.47	 
```
</td><td>
<code>80</code>
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
- 68.69.186.30	 
```
</td><td>
<code>80</code>
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
+ 104.236.128.46	 
```
</td><td>
<code>80</code>
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
- 43.155.152.154	 
```
</td><td>
<code>80</code>
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
+ 167.248.133.125	 
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
- 107.170.232.57	 
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
+ 45.79.181.223	 
```
</td><td>
<code>80</code>
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
- 58.49.233.126	 
```
</td><td>
<code>80</code>
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
+ 185.180.140.5	 
```
</td><td>
<code>80</code>
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
+ 180.149.125.168	 
```
</td><td>
<code>80</code>
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
- 142.93.31.242	 
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
+ 104.131.183.158	 
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
- 193.37.69.106	 
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
+ 121.204.158.132	 
```
</td><td>
<code>80</code>
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
- 65.49.1.83	 
```
</td><td>
<code>80</code>
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
+ 198.199.94.11	 
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
- 65.49.1.88	 
```
</td><td>
<code>80</code>
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
+ 185.180.140.6	 
```
</td><td>
<code>80</code>
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
- 65.49.1.84	 
```
</td><td>
<code>80</code>
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
- 50.116.32.232	 
```
</td><td>
<code>80</code>
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
+ 180.214.239.225	 
```
</td><td>
<code>80</code>
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
- 134.209.124.87	 
```
</td><td>
<code>80</code>
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
+ 185.254.196.186	 
```
</td><td>
<code>80</code>
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
- 45.56.115.142	 
```
</td><td>
<code>80</code>
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
+ 134.209.185.91	 
```
</td><td>
<code>80</code>
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
- 173.230.152.194	 
```
</td><td>
<code>80</code>
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
+ 87.236.176.238	 
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
+ 87.236.176.172	 
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
- 172.104.11.34	 
```
</td><td>
<code>80</code>
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
+ 87.236.176.153	 
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
- 36.99.136.137	 
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
+ 87.236.176.180	 
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
- 185.166.84.142	 
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
+ 87.236.176.149	 
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
- 45.248.76.188	 
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
+ 87.236.176.168	 
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
- 111.7.96.171	 
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
+ 87.236.176.152	 
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
- 146.70.192.180	 
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
+ 87.236.176.174	 
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
- 43.248.137.37	 
```
</td><td>
<code>80</code>
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
+ 162.243.131.29	 
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
- 64.225.6.7	 
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
+ 87.236.176.158	 
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
+ 87.236.176.154	 
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
+ 167.94.146.53	 
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
- 111.7.100.29	 
```
</td><td>
<code>80</code>
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
+ 34.140.49.48	 
```
</td><td>
<code>80</code>
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
- 205.210.31.178	 
```
</td><td>
<code>80</code>
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
+ 34.79.217.122	 
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
+ 35.240.127.139	 
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
- 111.224.249.104	 
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
- 222.181.11.12	 
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
+ 20.163.29.208	 
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
- 185.255.114.23	 
```
</td><td>
<code>80</code>
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
+ 71.6.232.27	 
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
- 185.255.114.23	 
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
+ 87.236.176.156	 
```
</td><td>
<code>80</code>
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
- 52.167.144.54	 
```
</td><td>
<code>80</code>
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
+ 170.64.200.246	 
```
</td><td>
<code>80</code>
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
+ 146.190.48.172	 
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
+ 128.14.209.162	 
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
- 104.168.158.64	 
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
+ 167.94.138.33	 
```
</td><td>
<code>80</code>
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
+ 172.104.210.105	 
```
</td><td>
<code>80</code>
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
- 183.185.108.139	 
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
+ 34.140.254.214	 
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
- 43.131.62.4	 
```
</td><td>
<code>80</code>
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
+ 34.76.212.231	 
```
</td><td>
<code>80</code>
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
+ 34.76.11.101	 
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
+ 34.77.117.201	 
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
- 139.170.203.81	 
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
+ 104.155.118.222	 
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
- 45.156.128.2	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.30	 
```
</td><td>
<code>80</code>
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
- 205.210.31.154	 
```
</td><td>
<code>80</code>
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
+ 130.211.64.88	 
```
</td><td>
<code>80</code>
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
- 91.92.249.130	 
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
+ 44.206.231.124	 
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
- 192.155.90.118	 
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
+ 162.216.150.13	 
```
</td><td>
<code>80</code>
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
- 60.17.111.110	 
```
</td><td>
<code>80</code>
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
+ 45.79.168.172	 
```
</td><td>
<code>80</code>
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
- 123.158.48.186	 
```
</td><td>
<code>80</code>
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
+ 104.243.37.151	 
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
+ 143.110.182.33	 
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
- 159.65.120.34	 
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
+ 167.71.229.198	 
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
- 83.97.73.36	 
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
+ 106.75.90.129	 
```
</td><td>
<code>80</code>
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
- 18.234.245.22	 
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
+ 192.241.219.39	 
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
- 185.134.22.149	 
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
+ 106.75.98.174	 
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
- 2.56.247.173	 
```
</td><td>
<code>80</code>
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
+ 106.75.6.165	 
```
</td><td>
<code>80</code>
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
- 205.210.31.155	 
```
</td><td>
<code>80</code>
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
+ 106.75.70.178	 
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
- 162.216.150.143	 
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
+ 34.77.14.243	 
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
+ 34.79.100.254	 
```
</td><td>
<code>80</code>
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
- 170.64.200.191	 
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
+ 104.155.113.196	 
```
</td><td>
<code>80</code>
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
- 170.64.200.191	 
```
</td><td>
<code>80</code>
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
- 162.216.150.49	 
```
</td><td>
<code>80</code>
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
+ 139.59.26.87	 
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
+ 35.202.9.133	 
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
+ 205.210.31.129	 
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
- 20.168.112.212	 
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
+ 162.216.149.144	 
```
</td><td>
<code>80</code>
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
- 198.235.24.157	 
```
</td><td>
<code>80</code>
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
+ 34.140.130.61	 
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
+ 106.75.98.247	 
```
</td><td>
<code>80</code>
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
- 107.170.237.54	 
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
+ 106.75.64.13	 
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
- 198.235.24.2	 
```
</td><td>
<code>80</code>
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
+ 159.89.53.40	 
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
+ 128.14.209.162	 
```
</td><td>
<code>80</code>
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
<code>198.235.24.213</code>
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
+ 149.28.109.99	 
```
</td><td>
<code>80</code>
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
<code>198.235.24.213</code>
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
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 83.97.73.87	 
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
+ 2.57.169.213	 
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
+ 2.57.169.211	 
```
</td><td>
<code>80</code>
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
+ 2.57.169.212	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.4	 
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
+ 62.193.106.227	 
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
+ 199.45.154.16	 
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
+ 87.236.176.143	 
```
</td><td>
<code>80</code>
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
+ 125.242.99.202	 
```
</td><td>
<code>80</code>
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
+ 221.126.232.61	 
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
+ 198.235.24.226	 
```
</td><td>
<code>80</code>
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
+ 192.241.231.27	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.21	 
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
+ 3.15.9.152	 
```
</td><td>
<code>80</code>
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
+ 162.243.137.16	 
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
+ 173.255.227.162	 
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
+ 64.176.59.155	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.58	 
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
+ 198.235.24.220	 
```
</td><td>
<code>80</code>
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
+ 137.184.255.51	 
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
+ 198.235.24.184	 
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
+ 4.178.106.5	 
```
</td><td>
<code>80</code>
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
+ 107.170.254.28	 
```
</td><td>
<code>80</code>
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
+ 138.68.208.50	 
```
</td><td>
<code>80</code>
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
+ 34.78.6.216	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.50	 
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
+ 167.99.85.63	 
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
+ 205.210.31.148	 
```
</td><td>
<code>80</code>
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
+ 185.205.244.219	 
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
+ 162.216.149.226	 
```
</td><td>
<code>80</code>
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
+ 167.248.133.124	 
```
</td><td>
<code>80</code>
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
+ 170.106.82.193	 
```
</td><td>
<code>80</code>
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
+ 43.135.149.154	 
```
</td><td>
<code>80</code>
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
+ 60.188.57.0	 
```
</td><td>
<code>80</code>
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
+ 162.216.149.201	 
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
+ 107.170.248.46	 
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
+ 45.55.0.43	 
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
+ 45.8.19.104	 
```
</td><td>
<code>80</code>
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
+ 216.73.160.157	 
```
</td><td>
<code>80</code>
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
+ 191.101.41.192	 
```
</td><td>
<code>80</code>
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
+ 216.73.160.14	 
```
</td><td>
<code>80</code>
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
+ 216.73.160.160	 
```
</td><td>
<code>80</code>
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
+ 216.73.160.173	 
```
</td><td>
<code>80</code>
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
+ 45.8.19.110	 
```
</td><td>
<code>80</code>
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
+ 198.199.114.97	 
```
</td><td>
<code>80</code>
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
+ 35.203.211.213	 
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
+ 51.158.171.29	 
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
+ 35.203.211.138	 
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
+ 162.243.151.30	 
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
+ 167.99.85.137	 
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
+ 20.169.49.172	 
```
</td><td>
<code>80</code>
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
+ 45.33.87.154	 
```
</td><td>
<code>80</code>
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
+ 198.235.24.80	 
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
+ 193.242.153.212	 
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
+ 44.214.91.96	 
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
+ 35.203.210.92	 
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
+ 205.210.31.18	 
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
+ 69.164.217.74	 
```
</td><td>
<code>80</code>
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
+ 199.45.154.18	 
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
+ 18.118.201.113	 
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
+ 3.236.198.119	 
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
+ 118.194.251.112	 
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
+ 152.32.247.41	 
```
</td><td>
<code>80</code>
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
+ 107.173.134.190	 
```
</td><td>
<code>80</code>
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
+ 198.235.24.58	 
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
+ 85.235.66.94	 
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
+ 165.154.172.111	 
```
</td><td>
<code>80</code>
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
+ 66.240.236.116	 
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
+ 64.225.40.89	 
```
</td><td>
<code>80</code>
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
+ 45.79.54.153	 
```
</td><td>
<code>80</code>
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
+ 173.230.149.119	 
```
</td><td>
<code>80</code>
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
+ 66.228.59.53	 
```
</td><td>
<code>80</code>
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
+ 198.235.24.206	 
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
+ 104.237.144.210	 
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
+ 170.64.146.220	 
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
+ 104.156.155.32	 
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
+ 35.203.211.107	 
```
</td><td>
<code>80</code>
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
+ 45.79.191.98	 
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
+ 46.37.21.63	 
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
+ 205.210.31.161	 
```
</td><td>
<code>80</code>
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
+ 106.75.136.29	 
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
+ 185.224.128.191	 
```
</td><td>
<code>80</code>
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
+ 18.171.175.12	 
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
+ 49.37.163.10	 
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
+ 198.235.24.201	 
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
+ 45.79.159.224	 
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
+ 199.45.154.19	 
```
</td><td>
<code>80</code>
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
+ 107.170.233.42	 
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
+ 143.110.241.3	 
```
</td><td>
<code>80</code>
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
+ 172.104.30.39	 
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
+ 93.174.95.106	 
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
+ 148.153.45.238	 
```
</td><td>
<code>80</code>
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
+ 45.79.159.185	 
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
+ 167.248.133.38	 
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
+ 198.199.94.45	 
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
+ 35.203.210.198	 
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
+ 192.241.217.10	 
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
+ 185.180.140.5	 
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
+ 216.218.206.69	 
```
</td><td>
<code>80</code>
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
+ 165.227.149.175	 
```
</td><td>
<code>80</code>
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
+ 104.156.155.24	 
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
+ 35.203.211.39	 
```
</td><td>
<code>80</code>
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
+ 173.255.232.147	 
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
+ 43.131.248.209	 
```
</td><td>
<code>80</code>
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
+ 117.33.163.216	 
```
</td><td>
<code>80</code>
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
+ 4.233.192.143	 
```
</td><td>
<code>80</code>
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
+ 172.104.208.92	 
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
+ 167.94.138.49	 
```
</td><td>
<code>80</code>
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
+ 192.241.218.67	 
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
+ 18.170.64.203	 
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
+ 51.254.49.111	 
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
+ 143.198.143.69	 
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
+ 207.32.217.70	 
```
</td><td>
<code>80</code>
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
+ 157.230.60.182	 
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
+ 198.235.24.34	 
```
</td><td>
<code>80</code>
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
+ 35.85.224.17	 
```
</td><td>
<code>80</code>
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
+ 54.185.212.207	 
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
+ 194.187.176.212	 
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
+ 45.56.108.128	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.141	 
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
+ 194.33.191.100	 
```
</td><td>
<code>80</code>
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
+ 199.45.154.50	 
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
+ 198.20.87.98	 
```
</td><td>
<code>80</code>
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
+ 157.230.225.126	 
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
+ 162.243.128.49	 
```
</td><td>
<code>80</code>
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
+ 162.243.131.25	 
```
</td><td>
<code>80</code>
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
+ 152.59.65.155	 
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
+ 91.92.252.165	 
```
</td><td>
<code>80</code>
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
+ 152.58.67.251	 
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
+ 152.58.94.253	 
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
+ 89.23.101.167	 
```
</td><td>
<code>80</code>
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
+ 163.5.64.44	 
```
</td><td>
<code>80</code>
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
+ 205.210.31.48	 
```
</td><td>
<code>80</code>
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
+ 174.129.191.76	 
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
+ 8.142.12.12	 
```
</td><td>
<code>80</code>
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
+ 172.104.9.223	 
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
+ 45.79.181.179	 
```
</td><td>
<code>80</code>
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
+ 138.68.249.116	 
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
+ 45.79.182.233	 
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
+ 159.100.13.152	 
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
+ 3.93.50.254	 
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
+ 172.104.9.152	 
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
+ 212.83.8.79	 
```
</td><td>
<code>80</code>
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
<code>212.83.8.79</code>
</td><td>
<code>N/A</code>
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
+ 146.190.39.9	 
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
+ 135.125.246.110	 
```
</td><td>
<code>80</code>
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
+ 104.131.181.99	 
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
+ 118.193.39.91	 
```
</td><td>
<code>80</code>
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
+ 87.236.176.144	 
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
+ 87.236.176.195	 
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
+ 87.236.176.206	 
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
+ 205.210.31.73	 
```
</td><td>
<code>80</code>
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
+ 87.236.176.185	 
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
+ 87.236.176.188	 
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
+ 87.236.176.217	 
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
+ 205.210.31.41	 
```
</td><td>
<code>80</code>
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
+ 87.236.176.199	 
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
+ 87.236.176.198	 
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
+ 87.236.176.213	 
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
+ 52.90.43.97	 
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
+ 205.210.31.132	 
```
</td><td>
<code>80</code>
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
+ 51.89.5.185	 
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
+ 80.66.88.215	 
```
</td><td>
<code>80</code>
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
+ 172.104.208.170	 
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
+ 80.82.77.139	 
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
+ 172.104.11.4	 
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
+ 54.152.205.131	 
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
+ 23.239.9.7	 
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
+ 23.129.64.219	 
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
+ 69.164.213.41	 
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
+ 35.203.211.110	 
```
</td><td>
<code>80</code>
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
+ 172.104.211.9	 
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
+ 188.93.233.144	 
```
</td><td>
<code>80</code>
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
+ 190.2.143.136	 
```
</td><td>
<code>80</code>
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
+ 78.153.140.219	 
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
+ 45.79.142.92	 
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
+ 185.142.236.40	 
```
</td><td>
<code>80</code>
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
+ 185.180.143.142	 
```
</td><td>
<code>80</code>
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
+ 198.235.24.22	 
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
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>8181</code>
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
<code>10.4.3.217</code>
</td><td>

```diff
- 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/tmp/nginx/prometheus-nginx.socket</code>
</td><td>
<code>N/A</code>
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
<code>10.4.1.220</code>
</td><td>
<code>3000</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.75</code>
</td><td>

```diff
- 3000	 
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
<code>10.4.3.217</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.220	 
```
</td><td>
<code>3000</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.75</code>
</td><td>

```diff
+ 3000	 
```
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.220	 
```
</td><td>
<code>3000</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>
<code>/tmp/nginx/prometheus-nginx.socket</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.220</code>
</td><td>
<code>3000</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/tmp/nginx/prometheus-nginx.socket</code>
</td><td>
<code>N/A</code>
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
- 127.0.0.1	 
```
</td><td>
<code>8181</code>
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
+ 10.4.3.75	 
```
</td><td>
<code>3000</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy-minion  
>**Type/Name**: statefulset/divy-minion-7  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>AF_UNIX</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 0	 
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
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_596d0dd0f1_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_UNIX</code>
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
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_596d0dd0f1_pull.ipc</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: istio-system  
>**Type/Name**: deployment/istiod  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>8080</code>
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

```diff
+ 10.4.3.180	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.149</code>
</td><td>

```diff
- 15012	 
```
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
<code>10.4.2.232</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.36	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.3.179	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.79	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.3.119	 
```
</td><td>
<code>8080</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.36	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-datapipeline-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.172	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.3.135	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.79	 
```
</td><td>
<code>15012</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.161	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.146	 
```
</td><td>
<code>15012</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.216	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.1.151	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-cluster-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.168	 
```
</td><td>
<code>15012</code>
</td><td>
<code>istio-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.216	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.179	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.2.91	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-policy-provider-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.40	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.3.122	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.172	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.27	 
```
</td><td>
<code>15012</code>
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
- 10.4.1.151	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.3.100	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.144	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.3.249	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.146	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.2.125	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.183	 
```
</td><td>
<code>15012</code>
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

```diff
+ 10.4.2.219	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-user-mgmt</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.190	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-integration</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.144	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-observability-api</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.200	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.86</code>
</td><td>

```diff
+ 15012	 
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
<code>10.4.3.86</code>
</td><td>
<code>15012</code>
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
+ 10.4.1.149	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.125	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-policy-storage-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.216	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-policy-service</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.33	 
```
</td><td>
<code>15017</code>
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
<code>10.4.2.33</code>
</td><td>

```diff
+ 15017	 
```
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

```diff
+ 10.4.2.146	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.162	 
```
</td><td>
<code>15012</code>
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
+ 10.4.3.86	 
```
</td><td>
<code>15012</code>
</td><td>
<code>accuknox-dev-vulnerability-service</code>
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
<code>18.217.128.146</code>
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
<code>18.189.66.244</code>
</td><td>

```diff
- 443	 
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
- 18.217.128.146	 
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
+ 3.21.255.161	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: karpenter  
>**Type/Name**: deployment/karpenter-webhook  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.244	 
```
</td><td>
<code>8443</code>
</td><td>
<code>accuknox-dev-monitoring</code>
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
<code>10.4.1.244</code>
</td><td>
<code>8443</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy  
>**Type/Name**: deployment/celery  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>UDP</code>
</td><td>
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>52.217.140.57</code>
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
<code>52.217.140.57</code>
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
- 52.555.44.108	 
```
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- UDP	 
```
</td><td>
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>52.217.135.65</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>N/A</code>
</td><td>
<code>/usr/lib/git-core/git-remote-https</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
+ 172.20.3.44	 
```
</td><td>
<code>8000</code>
</td><td>
<code>accuknox-dev-saltstack</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>3.5.29.170</code>
</td><td>

```diff
- 443	 
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
<code>172.20.3.44</code>
</td><td>

```diff
+ 8000	 
```
</td><td>
<code>accuknox-dev-saltstack</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.216.76.84</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/usr/lib/git-core/git-remote-https</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
<code>54.231.135.9</code>
</td><td>

```diff
- 443	 
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
+ 172.20.135.200	 
```
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.216.240.220</code>
</td><td>

```diff
- 443	 
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
<code>3.5.29.51</code>
</td><td>

```diff
- 443	 
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
+ 52.217.12.236	 
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
- 172.20.3.44	 
```
</td><td>
<code>8000</code>
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
+ 52.216.76.84	 
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
<code>52.216.92.99</code>
</td><td>

```diff
- 443	 
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
+ 52.216.240.76	 
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
- 54.231.138.153	 
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
+ 52.217.44.108	 
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
- 52.216.36.233	 
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
+ 52.216.132.235	 
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
+ 52.217.135.65	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
- 140.82.112.3	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
- 140.82.113.3	 
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
+ 54.231.169.137	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
+ 140.82.112.4	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
+ 140.82.114.4	 
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
<code>140.82.112.3</code>
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
+ 140.82.112.3	 
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
+ 16.182.97.217	 
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
- 52.216.36.225	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
- 140.82.113.4	 
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
- 54.231.138.145	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
+ 140.82.113.4	 
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
+ 52.216.251.156	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
- 140.82.114.3	 
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
<code>/usr/lib/git-core/git-remote-http</code>
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
+ 140.82.113.3	 
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
<code>/usr/lib/git-core/git-remote-http</code>
</td><td>

```diff
- 140.82.114.4	 
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
+ 52.217.84.196	 
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
+ 52.217.84.204	 
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
<code>52.217.170.81</code>
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
<code>52.217.170.81</code>
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
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-pulsar  
>**Type/Name**: statefulset/pulsar-broker  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.144	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>

```diff
- WHAT-PEEPEE?	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.132</code>
</td><td>
<code>6650</code>
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
<code>10.4.3.144</code>
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.143</code>
</td><td>

```diff
+ 6650	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
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
<code>10.4.2.232</code>
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.43	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.172	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.232</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.143	 
```
</td><td>
<code>6650</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.85	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-pulsar</code>
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
+ 10.4.2.25	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.223</code>
</td><td>

```diff
+ 3181	 
```
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.98	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.70	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.223	 
```
</td><td>
<code>3181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.118	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
+ /usr/lib/jvm/java-17-openjdk-amd64/bin/java	 
```
</td><td>
<code>10.4.3.104</code>
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.61	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/lib/jvm/java-17-openjdk-amd64/bin/java</code>
</td><td>

```diff
+ 10.4.3.104	 
```
</td><td>
<code>2181</code>
</td><td>
<code>accuknox-dev-pulsar</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-mongodb  
>**Type/Name**: statefulset/accuknox-dev-mongodb-rs0  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>

```diff
+ /usr/sbin/runc	 
```
</td><td>
<code>/data/db/mongodb-healthcheck</code>
</td><td>Allow</td></tr></table>

</details>
<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>7777</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.175	 
```
</td><td>
<code>7777</code>
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
+ 10.4.2.124	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.179</code>
</td><td>

```diff
- 27017	 
```
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
<code>10.4.3.180</code>
</td><td>

```diff
+ 7777	 
```
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.146</code>
</td><td>

```diff
+ 27017	 
```
</td><td>
<code>accuknox-dev-reporter</code>
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
<code>10.4.2.146</code>
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-reporter</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>30102</code>
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
<code>127.0.0.1</code>
</td><td>

```diff
+ 30102	 
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
+ 10.4.3.164	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-deo</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.34	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-deo</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.231	 
```
</td><td>
<code>27017</code>
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
+ 10.4.3.86	 
```
</td><td>
<code>27017</code>
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
+ 10.4.1.107	 
```
</td><td>
<code>27017</code>
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
+ 10.4.3.114	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-deo</code>
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
<code>10.4.3.180</code>
</td><td>
<code>7777</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.146	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-reporter</code>
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
+ 127.0.0.1	 
```
</td><td>
<code>27017</code>
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
<code>52.219.109.65</code>
</td><td>

```diff
- 443	 
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
<code>10.4.3.66</code>
</td><td>

```diff
+ 27017	 
```
</td><td>
<code>accuknox-dev-mongodb</code>
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
<code>52.219.92.113</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.233.49</code>
</td><td>
<code>443</code>
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
<code>::1</code>
</td><td>
<code>27017</code>
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

```diff
+ ::1	 
```
</td><td>
<code>27017</code>
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
<code>::1</code>
</td><td>

```diff
- 27017	 
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
<code>52.219.92.113</code>
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
- TCP	 
```
</td><td>
<code>/data/db/mongodb-healthcheck</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>27017</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>/data/db/mongodb-healthcheck</code>
</td><td>

```diff
- ::1	 
```
</td><td>
<code>27017</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/data/db/mongodb-healthcheck</code>
</td><td>

```diff
+ 10.4.1.73	 
```
</td><td>
<code>27017</code>
</td><td>
<code>accuknox-dev-mongodb</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>52.219.110.73</code>
</td><td>

```diff
- 443	 
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
- 52.219.96.130	 
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
- 127.0.0.1	 
```
</td><td>
<code>27017</code>
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
<code>52.219.99.73</code>
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
<code>52.219.99.73</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: cert-manager  
>**Type/Name**: deployment/cert-manager  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 18.189.147.94	 
```
</td><td>
<code>80</code>
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
<code>3.130.39.168</code>
</td><td>

```diff
+ 80	 
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
<code>3.130.39.168</code>
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>18.189.147.94</code>
</td><td>
<code>80</code>
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
<code>18.189.147.94</code>
</td><td>

```diff
- 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy-minion  
>**Type/Name**: statefulset/divy-minion-3  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>3.19.40.182</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_002377739a_pull.ipc</code>
</td><td>
<code>N/A</code>
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
<code>3.19.40.182</code>
</td><td>
<code>80</code>
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
- 3.19.40.182	 
```
</td><td>
<code>80</code>
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
<code>3.19.40.182</code>
</td><td>

```diff
- 80	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.19.40.182</code>
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_002377739a_pull.ipc</code>
</td><td>
<code>N/A</code>
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
<code>3.19.40.182</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>3.19.40.182</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-prometheus-postgres-exporter  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.3.180	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.180	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.1.238	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.101	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.3.204	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.204	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.3.119	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.238	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.1.244	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.244	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.1.13	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.175	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.3.167	 
```
</td><td>
<code>9187</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.126	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.3.101	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.88	 
```
</td><td>
<code>9187</code>
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

```diff
+ 10.4.2.232	 
```
</td><td>
<code>9187</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.119</code>
</td><td>

```diff
+ 9187	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.119</code>
</td><td>
<code>9187</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.126	 
```
</td><td>
<code>9187</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.88	 
```
</td><td>
<code>9187</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: cloud-watch  
>**Type/Name**: deployment/cloudwatch-prometheus-cloudwatch-exporter  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>9106</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.175</code>
</td><td>

```diff
+ 9106	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.175</code>
</td><td>
<code>9106</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: karpenter  
>**Type/Name**: deployment/karpenter-controller  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>8081</code>
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.180</code>
</td><td>
<code>8081</code>
</td><td>
<code>kubearmor</code>
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
<code>99.78.178.225</code>
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
<code>99.78.178.225</code>
</td><td>
<code>443</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>99.78.180.195</code>
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
<code>99.78.180.195</code>
</td><td>

```diff
- 443	 
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
+ 99.78.180.195	 
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
+ 52.95.22.56	 
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
- 52.95.19.240	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: daemonset/loki-canary  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.180	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.167	 
```
</td><td>
<code>3500</code>
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

```diff
+ 10.4.1.244	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.175	 
```
</td><td>
<code>3500</code>
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

```diff
+ 10.4.1.238	 
```
</td><td>
<code>3500</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.119	 
```
</td><td>
<code>3500</code>
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

```diff
+ 10.4.1.13	 
```
</td><td>
<code>3500</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.119	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.175	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.232</code>
</td><td>

```diff
+ 3500	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.232</code>
</td><td>
<code>3500</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.167	 
```
</td><td>
<code>3500</code>
</td><td>
<code>kubearmor</code>
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
<code>172.20.48.40</code>
</td><td>

```diff
+ 80	 
```
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
+ TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.48.40</code>
</td><td>
<code>80</code>
</td><td>
<code>accuknox-loki</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.48.40</code>
</td><td>
<code>80</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy  
>**Type/Name**: deployment/celeryplaybook  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 172.20.135.200	 
```
</td><td>
<code>8200</code>
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
<code>172.20.3.44</code>
</td><td>

```diff
- 8000	 
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
<code>172.20.135.200</code>
</td><td>
<code>8200</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Service</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: kubecost  
>**Type/Name**: deployment/kubecost-kube-state-metrics  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.101	 
```
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.101</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.3.101</code>
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-fluentd-cloudtrial  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 15.206.137.220	 
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
<code>15.206.137.220</code>
</td><td>

```diff
- 443	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>15.206.137.220</code>
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
+ 15.206.137.220	 
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
<code>15.206.137.220</code>
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
<code>15.206.137.220</code>
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
- 15.206.137.193	 
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
+ 15.206.137.225	 
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
- 15.206.137.196	 
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
+ 15.206.137.195	 
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
- 15.206.137.254	 
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
+ 15.206.137.196	 
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
- 15.206.137.225	 
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
+ 15.206.137.193	 
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
- 15.206.137.195	 
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
+ 15.206.137.254	 
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-stackgres  
>**Type/Name**: deployment/stackgres-operator  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>

```diff
- /usr/bin/dash	 
```
</td><td>
<code>/usr/bin/whatnamelol</code>
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash/moredashlol</code>
</td><td>

```diff
- /usr/bin/grep	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/containerd-shim-runc-v2</code>
</td><td>

```diff
+ /app/stackgres-operator.sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/cut	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/containerd-shim-runc-v2</code>
</td><td>

```diff
+ /bin/sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/containerd-shim-runc-v2</code>
</td><td>

```diff
+ /usr/bin/java	 
```
</td><td>Allow</td></tr><tr><td>

```diff
- /usr/bin/dash	 
```
</td><td>
<code>/usr/bin/sed</code>
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /docker-entrypoint.d/20-envsubst-on-templates.sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/containerd-shim-runc-v2</code>
</td><td>

```diff
- /docker-entrypoint.sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/containerd-shim-runc-v2</code>
</td><td>

```diff
- /usr/sbin/nginx	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /docker-entrypoint.d/10-listen-on-ipv6-by-default.sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/awk	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/findwhatexactly	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/dpkg-query	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/touch	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/sort	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/md5sum	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /docker-entrypoint.d/30-tune-worker-processes.sh	 
```
</td><td>Allow</td></tr></table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-vault  
>**Type/Name**: statefulset/consul-consul-server  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.218	 
```
</td><td>
<code>8301</code>
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

```diff
+ 10.4.1.126	 
```
</td><td>
<code>8501</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.1.143</code>
</td><td>

```diff
+ 8501	 
```
</td><td>
<code>accuknox-dev-vault</code>
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
<code>10.4.1.143</code>
</td><td>
<code>8501</code>
</td><td>
<code>accuknox-dev-vault</code>
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
<code>/usr/bin/curl</code>
</td><td>

```diff
+ 127.0.0.1	 
```
</td><td>
<code>8501</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/curl</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
+ 8501	 
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
- 10.4.1.41	 
```
</td><td>
<code>8301</code>
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
+ 10.4.3.160	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.92</code>
</td><td>

```diff
+ 8301	 
```
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.92	 
```
</td><td>
<code>8301</code>
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
+ 10.4.3.191	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.160	 
```
</td><td>
<code>8301</code>
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
+ 10.4.3.218	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/bin/curl</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>8501</code>
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
+ 10.4.2.92	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.3.213	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.227	 
```
</td><td>
<code>8301</code>
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
+ 10.4.1.110	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.213	 
```
</td><td>
<code>8301</code>
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
<code>/usr/bin/curl</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>8501</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.3.213</code>
</td><td>
<code>8301</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>UDP</code>
</td><td>

```diff
+ /usr/bin/curl	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
- 10.4.3.218	 
```
</td><td>
<code>8301</code>
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
+ 10.4.2.68	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.68	 
```
</td><td>
<code>8301</code>
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
+ 10.4.2.36	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.191	 
```
</td><td>
<code>8301</code>
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
+ 10.4.1.41	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.227	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.110	 
```
</td><td>
<code>8301</code>
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
+ 10.4.3.23	 
```
</td><td>
<code>8301</code>
</td><td>
<code>accuknox-dev-vault</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-agents  
>**Type/Name**: deployment/discovery-engine  

<details>
<summary>Process/File Summary</summary>

<table><tr><th>Source Path</th><th>Destination Path</th><th>Status</th></tr><tr><td>
<code>/bin/sh</code>
</td><td>

```diff
+ /usr/local/lib/erlang/erts-13.2.2.2/bin/epmd	 
```
</td><td>Allow</td></tr><tr><td>

```diff
- /usr/bin/dash	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>

```diff
- /usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec	 
```
</td><td>
<code>/bin/sh</code>
</td><td>Allow</td></tr><tr><td>

```diff
+ /usr/local/lib/erlang/erts-13.2.2.2/bin/erl_child_setup	 
```
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erl</code>
</td><td>Allow</td></tr><tr><td>
<code>/usr/bin/dash</code>
</td><td>

```diff
- /usr/bin/basename	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erl_child_setup</code>
</td><td>

```diff
+ /usr/local/lib/erlang/erts-13.2.2.2/bin/inet_gethost	 
```
</td><td>Allow</td></tr><tr><td>

```diff
- /usr/local/lib/erlang/erts-13.2.2.2/bin/beam.smp	 
```
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/dyn_erl</code>
</td><td>Allow</td></tr><tr><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/beam.smp</code>
</td><td>

```diff
- /bin/sh	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>

```diff
+ /usr/bin/dirname	 
```
</td><td>Allow</td></tr><tr><td>

```diff
- /usr/local/lib/erlang/erts-13.2.2.2/bin/beam.smp	 
```
</td><td>
<code>/usr/bin/basename</code>
</td><td>Allow</td></tr><tr><td>

```diff
+ /usr/local/lib/erlang/erts-13.2.2.2/bin/erl	 
```
</td><td>
<code>/usr/bin/basename</code>
</td><td>Allow</td></tr><tr><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erl</code>
</td><td>

```diff
- /usr/bin/dirname	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>

```diff
+ /usr/bin/basename	 
```
</td><td>Allow</td></tr><tr><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erl</code>
</td><td>

```diff
+ /bin/sh	 
```
</td><td>Allow</td></tr></table>

</details>
<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>UDP</code>
</td><td>

```diff
+ /usr/local/lib/erlang/erts-13.2.2.2/bin/beam.smp	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>

```diff
- /usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec	 
```
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>4369</code>
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
+ 10.4.3.127	 
```
</td><td>
<code>4369</code>
</td><td>
<code>accuknox-agents</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- ::1	 
```
</td><td>
<code>5672</code>
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
+ 127.0.0.1	 
```
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCPv6	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>::1</code>
</td><td>
<code>5672</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>

```diff
- 127.0.0.1	 
```
</td><td>
<code>4369</code>
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

```diff
+ ::1	 
```
</td><td>
<code>5672</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>
<code>127.0.0.1</code>
</td><td>

```diff
- 4369	 
```
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
<code>::1</code>
</td><td>

```diff
+ 5672	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>4369</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
+ UDP	 
```
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/beam.smp</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
+ 172.20.131.163	 
```
</td><td>
<code>32767</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>
<code>172.20.131.163</code>
</td><td>

```diff
+ 32767	 
```
</td><td>
<code>kubearmor</code>
</td><td>
<code>Service</code>
</td></tr>
<tr><td>

```diff
- TCP	 
```
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>
<code>127.0.0.1</code>
</td><td>
<code>4369</code>
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
<code>::1</code>
</td><td>
<code>5672</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
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
- 0	 
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
<code>0.0.0.0</code>
</td><td>

```diff
+ 4369	 
```
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
<code>0.0.0.0</code>
</td><td>

```diff
- 4369	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>
<code>AF_INET</code>
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>

```diff
- 0	 
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
- AF_INET	 
```
</td><td>
<code>/usr/local/lib/erlang/erts-13.2.2.2/bin/erlexec</code>
</td><td>
<code>0.0.0.0</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-divy-minion  
>**Type/Name**: statefulset/divy-minion-1  

<details>
<summary>Egress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>

```diff
+ AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_8d993c9c10_pull.ipc</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td><td>
<code>N/A</code>
</td></tr>
<tr><td>

```diff
- AF_UNIX	 
```
</td><td>
<code>N/A</code>
</td><td>
<code>/var/run/salt/minion/minion_event_8d993c9c10_pull.ipc</code>
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

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-dev-monitoring  
>**Type/Name**: deployment/prometheus-kube-state-metrics  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.3.204	 
```
</td><td>
<code>8080</code>
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

```diff
+ 10.4.2.126	 
```
</td><td>
<code>8080</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.1.88	 
```
</td><td>
<code>8080</code>
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

```diff
+ 10.4.3.204	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>
<code>10.4.2.126</code>
</td><td>

```diff
+ 8080	 
```
</td><td>
<code>kubearmor</code>
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
<code>10.4.2.126</code>
</td><td>
<code>8080</code>
</td><td>
<code>kubearmor</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCPv6</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.1.88	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

## Workload Information 
>**Cluster**: default  
>**Namespace**: accuknox-loki  
>**Type/Name**: deployment/loki-gateway  

<details>
<summary>Ingress Connections</summary>

<table><tr><th>Protocol</th><th>Command</th><th>POD/SVC/IP</th><th>Port</th><th>Namespace</th><th>Type</th></tr><tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
+ 10.4.2.232	 
```
</td><td>
<code>8080</code>
</td><td>
<code>accuknox-dev-monitoring</code>
</td><td>
<code>Pod</code>
</td></tr>
<tr><td>
<code>TCP</code>
</td><td>
<code>N/A</code>
</td><td>

```diff
- 10.4.2.232	 
```
</td><td>
<code>8080</code>
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
+ 10.4.3.119	 
```
</td><td>
<code>8080</code>
</td><td>
<code>kube-system</code>
</td><td>
<code>Pod</code>
</td></tr>
</table>

</details>
<hr>

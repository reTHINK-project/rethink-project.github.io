---
layout: page
title: testing
permalink: /
---

# Welcome to Worldwide Real Time Decentralized Communications

reTHINK Framework provides the tools to build a global real-time decentralized communication infra-structure where services are inherently inter-operable.

Network effects can now be created by many millions businesses and not by a couple of big corporations and monopolies, creating the foundations for a more balanced economy, promoting a society with less inequalities.

# Adhoc Interoperability with Quasi Zero Standards

Thanks to radical new concepts like Protocol on-the-fly and Reporter-Observer peer-to-peer data synchronization pattern, Decentralized Applications developed by different teams and deployed in different domains, can easily interoperate, without having to agree in advance on common protocols or service APIs [...](Concepts).

# Power back to People: Decentralized Trust with new or existing Identity Providers

The reTHINK Framework empowers the users with the choice and the management of their private data and identities [...](concepts/decentralized-trust.md).

# Hyperties: the new reusable building block to develop complex decentralized Applications

The reTHINK Framework enables the usage of cutting edge software engineering in the Decentralized Ecosystem. By following microservices architectural patterns, Hyperties are independently deployable components each one providing a small set of business capabilities, using the smart endpoints and dumb pipes philosophy [...](specs/tutorials/development-of-apps.md).

```javascript
rethink.install(config).then((runtime) => {
  runtime.requireHyperty('hyperty-catalogue://catalogue.example.com/.well-known/hyperty/HelloWorldReporter').then((hyperty)=>{
    hyperty.instance.hello();

    });
  }).catch(function(reason) {
  console.error(reason);
  });
```


<table>
<tr valign="top" align="center">
<td width="20%">Concepts<br><a href="Concepts"><img width="23" src="images/lightbulb.png"></a></td>
<td width="20%">Specifications<br><a href="Specifications"><img width="32" src="images/txt.png"></a></td>
<td width="20%">Architecture<br><a href="Architecture"><img width="32" src="images/resources.png"></a></td>
<td width="20%">Framework Development<br><a href="Framework-Development"><img width="32" src="images/code.png"></a></td>
<td width="20%">Deployment<br><a href="Deployment"><img width="32" src="images/network-construction.png"></a></td>
</tr>
<tr valign="top" align="center">
<td width="20%">Standards<br><a href="https://github.com/reTHINK-project/w3c"><img width="32" src="images/home.png"></a></td>
<td width="20%">Tutorials<br><a href="Tutorials"><img width="26" src="images/glyphicon-book.png"></a></td>
<td width="20%">Toolkits<br><a href="Toolkits"><img width="32" src="images/configuration.png"></a></td>
<td width="20%">Use Cases<br><a href="Use-Cases"><img width="44" src="images/usecase_icon.png"></a></td>
<td width="20%">Demos<br><a href="Demos"><img width="42" src="images/demo_icon.png"></a></td></tr>
</table>
<br>

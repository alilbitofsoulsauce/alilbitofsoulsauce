<p align="center">
  <img src="./assets/header.svg" alt="alilbitofsoulsauce — systems, infrastructure, experiments" width="100%" />
</p>

<br />

<p align="center">
  <samp>
    computer science · infrastructure · resilient systems · strange experiments
  </samp>
</p>

<p align="center">
  I like building things that still make sense when the network disappears,<br />
  the hardware is cheap, the assumptions are wrong, or reality gets messy.
</p>

---

### /now

I’m an undergraduate Computer Science student in the Philippines, mostly working where **software meets unreliable real-world systems**.

Right now, that means:

- **edge + LoRaWAN systems** — telemetry, gateways, outage recovery, evidence integrity
- **low-cost infrastructure intelligence** — sensing, anomaly detection, and retrofit hardware
- **full-stack products** — turning prototypes into usable systems instead of leaving them as diagrams
- **experimental system design** — Merkle DAGs, distributed data, offline-first workflows, and failure testing

I care less about adding technology for its own sake and more about answering:

> **What survives contact with the real world?**

---

### /selected-work

<table>
<tr>
<td width="50%" valign="top">
<h4><a href="https://github.com/alilbitofsoulsauce/starfront">STARFRONT</a></h4>
<strong>An authoritative browser RTS on one continuous battlefield.</strong>
<br /><br />
A desktop-first sci-fi strategy game with an 8192×8192 world, server-owned combat and economy, construction, pathing, reconnect recovery, and deterministic playtests.
<br /><br />
<code>TypeScript</code> <code>Colyseus</code> <code>PixiJS</code> <code>multiplayer</code>
</td>
<td width="50%" valign="top">
<h4><a href="https://github.com/alilbitofsoulsauce/synapse">Synapse</a></h4>
<strong>A local-first knowledge layer for unrelated tools.</strong>
<br /><br />
A Rust system for durable machine knowledge with provenance, confidence, lifecycle state, append-only evolution, bounded retrieval, write authorization, and authenticated local IPC.
<br /><br />
<code>Rust</code> <code>local-first</code> <code>IPC</code> <code>knowledge systems</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h4><a href="https://github.com/alilbitofsoulsauce/ph-rice-disease-detector">RiceCare</a></h4>
<strong>Offline rice-disease detection for field use.</strong>
<br /><br />
A mobile-first PWA that runs local TensorFlow Lite inference in the browser, accepts camera or gallery input, and keeps scan history in IndexedDB for low-connectivity environments.
<br /><br />
<code>JavaScript</code> <code>TFLite</code> <code>PWA</code> <code>offline-first</code>
</td>
<td width="50%" valign="top">
<h4><a href="https://github.com/alilbitofsoulsauce/lorawan-setup">LoRaWAN Infrastructure</a></h4>
<strong>Making edge telemetry understandable and recoverable.</strong>
<br /><br />
Gateway and network-server work around real deployment constraints: setup, diagnostics, outage behavior, recovery, repeatable verification, and failure-focused experimentation.
<br /><br />
<code>Python</code> <code>LoRaWAN</code> <code>ChirpStack</code> <code>Linux</code>
</td>
</tr>
</table>

<details>
<summary><strong>research I’m pushing further</strong></summary>
<br />

- **Praevis by Nexura Labs** — low-cost transformer retrofit intelligence using external sensing, LoRaWAN telemetry, and evidence-driven analytics.
- **Forward-secure LoRaWAN evidence journaling** — authenticated gateway records, crash recovery, failure injection, and post-outage verification.
- **Grid-aligned Merkle DAGs for UAV rasters** — cross-epoch deduplication with verifiable spatial-window retrieval.

</details>

---

### /toolbox

```text
languages        Python · JavaScript / TypeScript · Rust · SQL
backend          Node.js · REST APIs · MySQL · Firebase · local IPC
infrastructure   Linux · Docker · Git · networking · LoRaWAN · ChirpStack
systems          offline-first design · journaling · integrity · failure injection
exploring        Hyperledger Fabric · IPFS · spatial data · edge analytics
```

I don’t treat this as a list of things I’ve “mastered.”  
It’s the set of tools I’m actively using, breaking, testing, and learning.

---

### /how-i-build

```text
01  start with the failure mode
02  remove the unnecessary cleverness
03  make the cheapest version that can answer the question
04  test ugly conditions, not just the happy path
05  document what the system cannot prove
06  ship the artifact
```

A lot of my work starts with constraints: weak connectivity, cheap sensors, limited compute, outages, deployment cost, or incomplete data. Those constraints usually make the architecture more interesting.

---

### /current-questions

- How much useful condition information can **cheap external sensors** extract from infrastructure?
- When does **AI actually outperform simpler detection**, and when is it just decoration?
- How should edge systems behave through **hours or days without WAN access**?
- Can verifiable storage structures remain efficient when the data is **spatial and repeatedly re-observed**?
- How do you turn an academic prototype into something people can **deploy, recover, and maintain**?

---

<p align="center">
  <samp>
    build → break → measure → revise
  </samp>
</p>

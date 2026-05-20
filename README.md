# `artio`: Component bundle for large-scale investigation of software variability in Nostr

<div>
  <img width="80%" src="./logo-artio.png" alt="artio logo" />
</div>
<br>
<div align="center">
  <strong>
    👋 <a href="#introduction">Introduction</a> &nbsp;&nbsp;| &nbsp;&nbsp; 
    📊 <a href="#dashboard">Dashboard</a> &nbsp;&nbsp;|&nbsp;&nbsp; 
    🎓 <a href="#thesis">Thesis</a> 
  </strong>
</div>
<div align="center">
  <a href="https://github.com/SEG-UNIBE/artio/releases"><img src="https://img.shields.io/github/v/release/SEG-UNIBE/artio?include_prereleases" alt="Changelog" /></a>
  <a href="https://doi.org/10.5281/zenodo.18849681"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.18849681.svg" alt="DOI" /></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT" /></a>
</div>



## Introduction

Artio named after the Celtic bear goddess, is a comprehensive component bundle designed for large-scale investigation of software variability in Nostr. 
It provides a suite of tools and resources to facilitate the analysis and understanding of software variability in the context of Nostr, enabling researchers and practitioners to explore and manage the complexities associated with software variability effectively.

All of these components have been developed as part of the Master Thesis of Michael Kaiser at the University of Bern, Switzerland, under the supervision of Prof. Time Kehrer and Roman Bögli. 

More general information about Nostr can be found in the following resources:

[![artio-relay](https://img.shields.io/badge/GitHub-nostr%2D%2Dprotocol-181717?style=for-the-badge&logo=github)](https://github.com/nostr-protocol)
[![artio-relay](https://img.shields.io/badge/GitHub-nostr%2D%2Dnips-181717?style=for-the-badge&logo=github)](https://github.com/nostr-protocol/nips)


## Dashboard
The public dashboards can be reached via the link below. 
[![Artio Dashboard](https://img.shields.io/badge/Artio%20Dashboard-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)](https://grafana.artio.inf.unibe.ch/public-dashboards/d68db6e7117d43338091f5e7c4f84c34)


## Thesis

The thesis titled "Large-Scale Investigation of Software Variability in Nostr" is available upon request. 

## Components
Following is a list of the components included in the Artio bundle, along with their respective GitHub repositories and relevant badges for license, release, and release date.
### artio-relay
The artio-relay is a custom Nostr relay implementation that serves as the core component of the Artio bundle. 
It actively participates in the Nostr network and collects information. 
<div align="center">
  <img width="80%" src="https://cdn.artio.inf.unibe.ch/logos/logo_relay_full.svg" alt="artio-relay logo" />
</div>

[![artio-relay](https://img.shields.io/badge/GitHub-artio%2D%2Drelay-181717?style=for-the-badge&logo=github)](https://github.com/SEG-UNIBE/artio-relay)


### artio-insight
The artio-insight is the data analysis component of artio and leverages the data collected by the artio-rely and artio-miner. 
<div align="center">
  <img width="80%" src="https://cdn.artio.inf.unibe.ch/logos/logo_insights_full.svg" alt="artio-insight logo" />
</div>

[![artio-insight](https://img.shields.io/badge/GitHub-artio%2D%2Dinsight-181717?style=for-the-badge&logo=github)](https://github.com/SEG-UNIBE/artio-insight)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/tag/SEG-UNIBE/artio-insight.svg?label=release)](https://github.com/SEG-UNIBE/artio-insight/releases)
[![GitHub release date](https://img.shields.io/github/release-date/SEG-UNIBE/artio-insight.svg)](https://github.com/SEG-UNIBE/artio-insight/releases)



### artio-miner
The artio-miner is responsible for mining the Nostr network and collecting data for analysis.
It uses the publicly available information from the NIP-11 and NIP-65 messages to gather insights about the software used by the relays in the Nostr network.
<div align="center">
  <img width="80%" src="https://cdn.artio.inf.unibe.ch/logos/logo_miner_full.svg" alt="artio-miner logo" />
</div>

[![artio-miner](https://img.shields.io/badge/GitHub-artio%2D%2Dminer-181717?style=for-the-badge&logo=github)](https://github.com/SEG-UNIBE/artio-miner)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/tag/SEG-UNIBE/artio-miner.svg?label=release)](https://github.com/SEG-UNIBE/artio-miner/releases)
[![GitHub release date](https://img.shields.io/github/release-date/SEG-UNIBE/artio-miner.svg)](https://github.com/SEG-UNIBE/artio-miner/releases)

### artio-orchestration
The orchestration repository contains the necessary scripts and ansible roles for setting up our environments. 
This repository is not public due to the fact, that it contains sensitive information. 
In order to get information about this, please get in touch with us. 
<div align="center">
  <img width="80%" src="https://cdn.artio.inf.unibe.ch/logos/logo_orchestration_full.svg" alt="artio-orchestration logo" />
</div>

[![artio-orchestration](https://img.shields.io/badge/GitHub-artio%2D%2Dorchestration-181717?style=for-the-badge&logo=github)](https://github.com/SEG-UNIBE/artio-orchestration)

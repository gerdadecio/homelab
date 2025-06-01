# 🏠 Homelab

I have been tinkering on networking stuff lately for the purpose of learning and to have my own private server at home since all of the big techs are taking away our privacy especially now with the rise of AI. While doing this, I thought of publishing my setup for future reference and to share it to the community as well.

This repo contains all of the configuration and documentation of my homelab which is inspired by https://github.com/mischavandenburg/homelab.

## 🔧 Hardware

### Synology NAS
For the past three years, I've been utilising my Synology NAS as a reliable home server. It efficiently manages and stores all my files and apps, allowing me remote access via the internet and file sharing with family and friends.

- DS420+ with 2.0 GHz CPU, 2GB RAM
- 10TB Seagate SATA Main drive
- 10TB Seagate SATA Backup drive

### Macbook
I have also setup some docker containers for some of the apps that I think would require more RAM than my NAS (ie. ollama LLMs)

- Apple M3 Pro
- 32GB RAM
- 500GB HD

## 🚀 Apps

End User Applications

<table>
  <tr>
    <th>Logo</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/499807/home-page.svg"></td>
    <td><a href="https://github.com/gethomepage/homepage">Homepage</a></td>
    <td>Dashboard interface as the entrypoint of all the apps and services</td>
  </td>
  <tr>
    <td><img width="32" src="https://openwebui.com/logo.png"></td>
    <td><a href="https://github.com/open-webui/open-webui">Openweb UI</a></td>
    <td>AI chat interface for Ollama LLMs</td>
  </td>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/504676/obsidian.svg"></td>
    <td><a href="https://obsidian.md/">Obsidian</a></td>
    <td>Note-taking app with self-hosted data</td>
  </td>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/349479/plex.svg"></td>
    <td><a href="https://www.plex.tv/">Plex</a></td>
    <td>Self-hosted media player similar to netflix</td>
  </tr>
</table>

### Infrastructure

Everything needed to run and deploy my applications

<table>
  <tr>
    <th>Logo</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/331593/synology.svg"></td>
    <td><a href="https://kb.synology.com/en-ca/DSM/help/ContainerManager/docker_desc?version=7">Synology Container Manager</a></td>
    <td>Synology's lightweight virtualization application for running docker containers</td>
  </td>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/519802/torguard.svg"></td>
    <td><a href="https://www.twingate.com/">Twingate</a></td>
    <td>Zero-trust remote access to a network resource</td>
  </tr>
</table>

### Monitoring

Monitor the health of the systems.

<table>
  <tr>
    <th>Logo</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img width="32" src="https://uptime.kuma.pet/img/icon.svg"></td>
    <td><a href="https://github.com/open-webui/open-webui">Uptime Kuma</a></td>
    <td>Uptime monitoring tool</td>
  </td>
  <tr>
    <td><img width="32" src="https://nicolargo.github.io/glances/public/images/glances.png"></td>
    <td><a href="https://github.com/nicolargo/glances">Glances</a></td>
    <td>System monitoring tool to monitor CPU, memory, disk, network, etc.</td>
  </td>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/448228/grafana.svg"></td>
    <td><a href="https://grafana.com/">Grafana</a></td>
    <td>The open observability platform.</td>
  </tr>
</table>

### Utilities

Other utility tools

<table>
  <tr>
    <th>Logo</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img width="32" src="https://www.svgrepo.com/download/306557/pi-hole.svg"></td>
    <td><a href="https://pi-hole.net/">Pihole</a></td>
    <td>Network-wide Ad blocking tool</td>
  </tr>
</table>

### Environment Variables

Create a `.env` file for your environment variables and update the docker-compose files accordingly

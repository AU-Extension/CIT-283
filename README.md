# CIT-283 Advanced Network Administration: course interactives

Interactive simulations for CIT-283 at Atlantis University, School of Information Technology. Each week has two self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The Moodle description blocks link to these pages through GitHub Pages.

Live site: https://au-extension.github.io/CIT-283/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| week1 | Network foundations and Cisco Packet Tracer | ipv4-binary-explorer.html | packet-journey.html |
| week2 | Subnetting and IPv4 addressing plans | subnet-visualizer.html | subnetting-drill.html |
| week3 | VLANs, trunking, and inter-VLAN routing | vlan-port-mapper.html | trunk-intervlan-sim.html |
| week4 | Designing small office networks | dhcp-nat-walkthrough.html | office-network-designer.html |
| week5 | Headquarters and branches with static routing | routing-table-explorer.html | static-route-builder.html |
| week6 | Dynamic routing with OSPF and troubleshooting | ospf-path-visualizer.html | troubleshooting-challenge.html |
| week7 | Virtual networks with Hyper-V | hyperv-vswitch-explorer.html | virtual-lab-builder.html |
| week8 | Azure networks and final project | azure-vnet-planner.html | nsg-rule-evaluator.html |

## Publishing

1. Create the public repository `AU-Extension/CIT-283` and upload the contents of this folder to the `main` branch (keep the `week1` to `week8` folders at the root).
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. After a minute or two, each page is live at `https://au-extension.github.io/CIT-283/weekN/<file>.html`.

Every page loads the AU logo from `AU-Extension/items` and GSAP and fonts from public CDNs, and still works if GSAP fails to load. No build step is needed.

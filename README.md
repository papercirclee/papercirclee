<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0D1117,40:134E4A,100:F97316&text=Li%20Tz%20Yuan&fontColor=FFFFFF&fontSize=62&fontAlignY=38&desc=Robotics%20systems%20%7C%20Marine%20autonomy%20%7C%20Field-ready%20engineering&descAlignY=58&descSize=18)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=700&color=36D399&center=true&vCenter=true&width=940&lines=I+build+systems+that+survive+the+real+world.;ROS+2+pipelines+%2B+USV+safety+%2B+simulation+contracts.;From+sensor+calibration+to+CI+gates+to+field+ops.)](https://git.io/typing-svg)

[![GitHub followers](https://img.shields.io/github/followers/papercirclee?style=for-the-badge&logo=github&label=Follow&color=22c55e)](https://github.com/papercirclee)
[![Profile views](https://komarev.com/ghpvc/?username=papercirclee&style=for-the-badge&color=f97316)](https://github.com/papercirclee)
[![NTU Archimedes](https://img.shields.io/badge/NTU-Archimedes-0ea5e9?style=for-the-badge&logo=sailfish&logoColor=white)](https://www.ntuarchimedes.org)

</div>

---

## Mission Control

I am a robotics and autonomy builder working across the stack: sensor rigs, ROS 2 interfaces, simulation realism, safety I/O, CI contracts, and the unglamorous glue that keeps a vehicle from falling apart outside the lab.

```txt
papercirclee@field-station:~$ ./launch_profile --mode autonomous-systems

STATUS        : building for real hardware, not just pretty demos
CURRENT       : RX26 USV + VRX simulation + safety indicators + perception pipelines
SPECIALTY     : turning messy integration work into repeatable, reviewable systems
OPERATING MODE: test in sim, verify in CI, document the contract, then touch hardware
```

| Console | Signal |
|---|---|
| **Autonomy stack** | ROS 2, MAVROS, BlueOS, RobotX interfaces, VRX simulation |
| **Sensors** | Basler cameras, OS0 LiDAR, hydrophones, perception datasets |
| **Safety systems** | Arduino mode lights, relay maps, POR readiness, hardware port contracts |
| **Infrastructure** | CI smoke tests, mocks, replay validation, reproducible setup docs |
| **Build taste** | Small interfaces, explicit assumptions, field-readable docs |

---

## Private Contribution Footprint

Most of my real work lives in private Archimedes repositories, so the public graph is only the surface. Recent private contribution patterns show a lot of systems ownership, especially across the RX26 USV platform and its simulator.

| Area | Repos | What I shipped |
|---|---|---|
| **USV platform integration** | `rx26_usv_pc` | Safety/mode-light wiring, Arduino I/O, POR validation, port maps, hardware network docs |
| **Simulation realism** | `rx26_vrx_sim` | RobotX course assets, BlueBoat/obstacle realism, VRX task controls, GPU-host camera capture fixes |
| **Perception + sensors** | `rx26_usv_pc` | Basler runtime, YOLO annotation contract, OS0 LiDAR notes, replay smoke tests |
| **Developer reliability** | `rx26_usv_pc`, `rx26_vrx_sim` | CI checks, mocks, doc consistency passes, launch/setup guardrails |

<details>
<summary><b>Selected private PR signal</b></summary>

| Repo | Private PR themes |
|---|---|
| `ArchimedesAutonomousVehicles/rx26_usv_pc` | Arduino safety I/O, acoustics pipeline, POR readiness, lidar readiness, hardware port maps, simulation contract, RoboCommand CI, UAV PX4 scope, validation mocks, Basler runtime, RobotX interfaces, BlueOS/MAVROS bridge |
| `ArchimedesAutonomousVehicles/rx26_vrx_sim` | Simulator metadata and CI, shell wrapper, RobotX course models, light controls, VRX task stability, BlueBoat realism, obstacle realism, UAV fixture defaults, dataset capture reliability, OS0 LiDAR docs |

</details>

---

## Build Stack

<div align="center">

![ROS2](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=111111)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-EF7B4D?style=for-the-badge&logo=ignition&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-111827?style=for-the-badge&logo=drone&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-DC2626?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![Fusion](https://img.shields.io/badge/Fusion-FF6D00?style=for-the-badge&logo=autodesk&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=111111)

</div>

---

## Live Systems Board

| Track | Current bias | Why it matters |
|---|---|---|
| **Autonomy** | ROS 2 interfaces before clever behavior | Contracts make integration survivable |
| **Simulation** | VRX parity with hardware assumptions | Sim bugs should fail before field bugs do |
| **Safety** | Visible mode state and clear relay behavior | Operators should know what the system thinks it is doing |
| **Perception** | Dataset and annotation discipline | Models are only as good as their capture process |
| **Documentation** | Wiring maps, launch notes, reviewable diffs | Future-me deserves fewer mysteries |

---

## GitHub Telemetry

<div align="center">

<img height="168" src="https://github-readme-stats.vercel.app/api?username=papercirclee&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img height="168" src="https://streak-stats.demolab.com?user=papercirclee&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="GitHub streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=papercirclee&theme=github-compact&hide_border=true&area=true&custom_title=Public%20activity%20graph%20%28private%20signal%20summarized%20above%29" alt="Activity graph" />

</div>

> Third-party cards mainly show public telemetry. The private contribution signal is summarized above from connector-visible private repo history.

---

## Contribution Snake

<div align="center">

![Contribution snake](https://raw.githubusercontent.com/papercirclee/papercirclee/output/github-contribution-grid-snake-dark.svg)

</div>

---

## Open A Channel

This profile borrows the best trick from the most memorable GitHub READMEs: make the profile interactive. Open an issue and give me a mission prompt.

| Button | Opens |
|---|---|
| [![Ask about RX26](https://img.shields.io/badge/Ask-RX26%20systems-22c55e?style=for-the-badge)](https://github.com/papercirclee/papercirclee/issues/new?title=RX26%20systems%20question&body=What%20part%20of%20the%20RX26%20stack%20should%20we%20talk%20about%3F%0A%0A-%20Safety%20I%2FO%0A-%20ROS%202%20interfaces%0A-%20Sensors%0A-%20Simulation%0A-%20Field%20testing) | A hardware or autonomy systems thread |
| [![Request validation notes](https://img.shields.io/badge/Request-validation%20notes-f97316?style=for-the-badge)](https://github.com/papercirclee/papercirclee/issues/new?title=Validation%20notes%20request&body=What%20do%20you%20want%20validated%3F%0A%0AExpected%20environment%3A%0AObserved%20behavior%3A%0AFailure%20mode%3A) | A test, CI, or field-debug conversation |
| [![Talk simulation](https://img.shields.io/badge/Talk-VRX%20simulation-0ea5e9?style=for-the-badge)](https://github.com/papercirclee/papercirclee/issues/new?title=VRX%20simulation%20discussion&body=Simulation%20topic%3A%0A%0A-%20Course%20models%0A-%20Vehicle%20fixtures%0A-%20Camera%20capture%0A-%20Task%20stability%0A-%20Reality%20gap) | A VRX/simulation realism thread |

---

<div align="center">

### Build for the test bench. Verify for the field. Document for the next operator.

![Footer](https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:134E4A,100:F97316)

</div>

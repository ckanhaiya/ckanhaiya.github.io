---
title: Cabin Pressure Control System (CPCS)

summary: Dynamic modeling of a cabin pressure control system for a multirole fighter aircraft

tags:
  - Fluid Mechanics

date: '2020-12-24T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart
  preview_only: true

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
## Abstract
Cabin pressure control system of an aircraft maintains cabin pressure in all flight modes as per the aircraft cabin pressurization characteristics by controlling the air flow from the cabin through the outflow valve of the cabin pressure control valve. The movement of outflow valve in turn depends on the air flow from the control chamber of cabin pressure control valve, which is controlled by the clapper and the poppet valves. These valves are actuated by absolute pressure and the differential pressure capsules, respectively depending upon the operating flight conditions. Mathematical models have been developed to simulate the air outflow rates from the cabin and the control chamber of cabin pressure control valve during steady-state and transient flight conditions. These mathematical models have then been translated into a MATLAB program to obtain plots of cabin pressures as a function of aircraft altitudes. The mathematical models are validated for standard cabin pressurization characteristics of a multirole light fighter/trainer aircraft. The model developed, thus can be used to produce a number of variants of cabin pressure control valve to suit different cabin pressurization characteristics.

{{< video src="CPCS.mp4"  controls="yes">}}

Cabin pressurization is a physiological requirement for pilots and passengers flying in an aircraft. At high altitudes, the partial pressure of oxygen is very low and the body is unable to supply an adequate amount of oxygen through normal breathing to cells and tissues. This lack of oxygen in the blood can cause effects ranging from simple headache and discomfort to total loss of consciousness, depending upon the duration of exposure to the high altitude condition. Other effects of low ambient pressure levels are the expansion of gases in cavities (sinus, abdomen) and getting dissolved in the blood (nitrogen) that may cause serious problems.

{{< figure src="pressurization_issues.png" caption="Issues related to unregulated pressurization" numbered="true" >}}

The cabin pressurization control law for a multirole light fighter/trainer aircraft is shown in Figure 2. Taking the structural limitations of the aircraft into consideration, it depicts the way in which cabin altitude (cabin pressure) must vary with aircraft altitude (external ambient pressure) in order to provide appropriate cabin environmental conditions for survival and comfort of pilot and co-pilot based on the physiological requirements.

{{< figure src="cpcs_law.jpg" caption="Cabin pressurization control law for a multirole light fighter/trainer aircraft." numbered="true" >}}

### Peer Reviewed Article
{{< cite page="/publication/chaurasiya-dynamic-2020" view="4" >}}

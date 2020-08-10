---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ATCO - Vertical Axis Wind Turbines"
summary: "Among the renewable and clean energy technologies, wind energy is one
of the most efficient, costing 1–2 cents per kilowatt-hour after the production
tax credit by governments. While natural wind speeds over various continents in
the world span from 0 to 20 m/s, the Vertical Axis Wind Turbines (VAWT) placed
on highway medians make it possible to utilize consistently higher wind speeds
due to vehicle motion. Additionally, the energy generated out of these wind
turbines is reported to increase multi-fold due to the shearing winds generated
on both sides of the medians by the on-going traffic [3]. Your task will be to
optimize the positioning of turbines to achieve optimal results using criteria
you deem to be important, such as output power, ease of installation/repair,
proximity to consumers, additive effects from positioning, etc, using real-life
traffic, geographical and weather data, and subsequently investigate economic
feasibility of implementation of this technology."
authors: []
tags: []
categories: []
date: 2020-07-23T17:00:22-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
math: true
---
# Feasibility study for Vertical Axis Wind Turbines on highways, 

### Industry mentors: Vakhtang Putkaradze and Nisha Mohan

Among the renewable and clean energy technologies, wind energy is one of the
most efficient, costing 1–2 cents per kilowatt-hour after the production tax
credit by governments [^1][^2][^3][^4][^17]. While natural wind speeds over
various continents in the world span from 0 to 20 m/s, the Vertical Axis Wind
Turbines (VAWT) placed on highway medians make it possible to utilize
consistently higher wind speeds due to vehicle motion [^5]. Additionally, the
energy generated out of these wind turbines is reported to increase multi-fold
due to the shearing winds generated on both sides of the medians by the on-going
traffic [^3]. Your task will be to optimize the positioning of turbines to
achieve optimal results using criteria you deem to be important, such as output
power, ease of installation/repair, proximity to consumers, additive effects
from positioning etc., using real-life traffic, geographical and weather data,
and subsequently investigate economic feasibility of implementation of this
technology. Specific focus to Alberta terrains and regulations would help as
well.

#### Problem Statement
The idea of VAWTs is to harvest the untapped turbulence energy generated from
vehicles in highways/roadways with ample traffic and speeds enough to generate
profitable energy. The VAWTs suffer from inconsistency in vehicle speeds etc.
and hence their outputs have a lot of factors that affect their performance.
Some of these factors include: the amount of traffic and the speed of the
traffic, the total time the wind energy is available (without traffic), seasons,
locations and changing climatic conditions. These questions need to be answered
to understand the long-term benefits of stationed vertical wind turbines.

We task the participants to quantify the effects of such factors and find an
optimized setup of wind turbine for maximum profitability along the roadways.
Here are a few areas of study:

1. Choose your favorite traffic highway system anywhere in the world. It is
   interesting to have some examples from both the developed and the developing
   world, and varying climate conditions. The traffic system should have enough
   data on cars’ movement to make quantitative predictions. Collect traffic data
   on various part of highways during various times and seasons;
1. Translate the traffic speeds into wind speeds using some hypotheses on the
   air motion around cars and available information in the literature;
1. Study typical wind patterns in that part of the world from available
   literature and compute the net effect of traffic motion on the wind;
1. Compute the optimal number and location of wind turbines along the highway to
   optimize either the power production, distance to the load point or utility
   grid etc, distance from neighboring city to minimize repair costs, or some
   combination of optimization goals;
1. See if viable options can be reached which pay off the original turbine setup
   costs sooner than those estimated in literature (3.5 yrs to 10 yrs) and start
   generating profitable energy after that [^17];
1. If return to profitability on its own is not possible, estimate the amount of
   government support needed to implement the system, either in terms of tax
   benefits, direct cash injection or setting tariff rates. We expect the team
   to come up with the relevant information during the literature search. As a
   starting point, the teams can look at Ref.
   [^10][^11][^12][^13][^14][^15][^17] for interesting questions about the
   technical/economic feasibility.

   There are some known issues that could be resolved with innovative ideas. For
   e.g., the cost issue of constructing long transmission lines from
   highways/remote roadways to the energy storage locations. This could be
   circumvented by constructing electric charging stations on the highways to
   charge electric vehicles, near to the wind turbine grids. A Tesla model 3 car
   takes 50-75KWh to get charged and each of these wind turbines are said to
   produce tens of thousands of KWh energy annually [^3][^5]. So, at least on
   paper, few hundred of VAWTs in a local grid seem to be enough for electric
   vehicle charging stations, but that calculation ignores the cost of setting
   up and maintaining the VAWT systems and their maintenance, grid connection
   and electricity storage. It would be interesting if any recommendation can be
   done for the conditions ATCO’s charging stations are currently operating in
   [^16]. If VAWT technology is not feasible for providing power for charging
   stations, lower levels of energy generated can be sold for street/highway
   lighting that forms a significant portion of the city’s budgets [^10]. The
   team is welcome to propose its own way to economic feasibility of the
   project, or, alternatively, prove that no system of VAWT can ever be
   economically viable.

   We advise to take caution and have conservative measures/weights for
   maintenance costs incurred due to replacements needed due to the turbine
   blade’s fatigue over the years of operation [^8]. Also, ice layers that build
   up in wind turbines in the North have disturbed the balance of turbine blades
   and created wobbling and vibration effects, eventually leading to breakage
   [^9]. So, areas with extreme temperatures/weather may be challenging from the
   possible spots for positioning. On the other hand, electricity costs may be
   substantially higher in these areas.

#### Data Collection and Optimization
Traffic data over the years, for most highways, are available online for various
countries/provinces. They can be collected from trusted government
reports/Google maps data. Natural wind speeds data is also available from
similar online resources. The formulation to translate both in terms of the
local wind speeds is up to the team.

The wind turbine blade design choice, the country/region of position
optimization are up to the team. The idea is not novel and has been implemented
in a few countries so far. Inspirations from similar studies on those
projects/patents can also be taken as reference. References to payback period
studies have also been done [^4]. They predict the original and operational costs
to be paid back within 6 months, 3.5 to 10 yrs depending on whichever turbine is
chosen [^3][^4][^7][^8]. The basis of all these reports must be critically
questioned from a scientific viewpoint, as some other authors say it is not
feasible and larger turbines are preferred [^6][^18]. The cost and effects of
large vs. these smaller turbines installable on highway medians should be
distinguished using technical and scientific proof.

#### Results
Quantitative results are needed to back up any of the claims. Please note that
this is a feasibility study and does not need to prove it viable or not.

#### Pre-requisites
Ability to quickly grasp on technical details and skills required. Desired
skills: knowledge of calculus of variations, optimization, programming/coding
experience.

#### References
[^1]: https://www.energy.gov/eere/wind/advantages-and-challenges-wind-energy
[^2]: https://www.irena.org/documentdownloads/publications/re_technologies_cost_analysis-wind_power.pdf
[^3]: http://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A652278&dswid=-862
[^4]: https://www.sciencedirect.com/science/article/pii/S2352484718301549
[^5]: https://www.altenergymag.com/article/2019/05/top-article-from-2019-traffic-powered-wind-turbines/31030
[^6]: https://www.sciencedirect.com/science/article/abs/pii/S1364032118301254
[^7]: https://wattsupwiththat.com/2014/06/16/wind-turbine-payback-period-claimed-to-be-within-8-months/
[^8]: https://www.nrel.gov/docs/fy18osti/71077.pdf
[^9]: https://energy.sandia.gov/wp-content//gallery/uploads/Sand80-0984.pdf
[^10]: https://blogs.worldbank.org/energy/led-street-lighting-unburdening-our-cities
[^11]: https://www.researchgate.net/publication/342121815_Energy_Recovery_of_Moving_Vehicles'_Wakes_in_Highways_by_Vertical_Axis_Wind_Turbines
[^12]: https://www.academia.edu/36611724/DESIGN_AND_SIMULATION_OF_A_VERTICAL_AXIS_WIND_TURBINE_FOR_HIGHWAY_WIND_POWER_GENERATION
[^13]: https://aiche.onlinelibrary.wiley.com/doi/abs/10.1002/ep.12917
[^14]: Wind Turbines along highways, TU Delft thesis
[^15]: https://www.sciencedirect.com/science/article/abs/pii/S136403211100596X
[^16]: https://www.atco.com/en-ca/projects/peaks-to-prairies-electric-vehicle-charging-station.html
[^17]: https://www.lazard.com/media/451086/lazards-levelized-cost-of-energy-version-130-vf.pdf
[^18]: https://www.drawdown.org/solutions/micro-wind-turbines
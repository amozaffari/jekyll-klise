---
layout: post
title:  "My notes from Climate Change AI summer school 2024"
date:   2024-08-28 09:29:20 +0700
categories: updates
usemathjax: true
---

 [Agenda](https://www.climatechange.ai/events/summer_school2024#schedule)
 Started on June 20th, ended on August 31st. 
#### Day 1 - Introduction to Climate Change and AI - June 20, 2024


**Lecture Recordings:**
- [Tackling Climate Change with Machine Learning](https://youtu.be/4HkJj3DFLgs)
- [Introduction to Machine Learning](https://youtu.be/4HkJj3DFLgs) (starting at 1:00:09)
	- not very useful session. (you can skip it)
	- [TerraDO](https://www.terra.do/) a community learning 
- [Expanded Introduction to Machine Learning Panel](https://youtu.be/4HkJj3DFLgs) (starting at 2:00:31)
- [Introduction to Climate Change](https://youtu.be/BIeyfltPVAw)

**Lecture Materials:**

- Tackling Climate Change with Machine Learning [pdf](https://www.dropbox.com/scl/fi/1nhqn5e7ox75y241g6onv/Tackling-Climate-Change-with-Machine-Learning.pdf?rlkey=kksmebez71yq4swzspetbtdh9&dl=0)
- [Introduction to Machine Learning](https://docs.google.com/presentation/d/1wzC4HdtL55KYXzowatk9WSccif7gxm_CosXDYwc7tsY/edit?usp=sharing)
- [Expanded Introduction to ML Materials](https://docs.google.com/document/d/1EdaAt2ZMS_59sfJL-2o4X3TeSI7oS4zgdvvMoxnQr0o/edit#heading=h.xaumv4cif8lz)

#### Day 2 - AI for Agriculture, Forestry, and Other Land Use - June 24, 2024

**Lecture Recording:**  
[https://youtu.be/99U0ePt9DzY](https://youtu.be/99U0ePt9DzY)

**Lecture Slide Decks:**

- **AI for Agriculture** [pdf](https://www.dropbox.com/scl/fi/5cxhck0kb3q6j41d0iho8/CCAI-Guest-Lecture-AI-for-Agriculture.pdf?rlkey=k5m9va1ff38u6yz8tjhxcrvtn&dl=0)
	- direct and feedback effect on agriculture and climate change (food production & water vs. land use change, biodiversity loss and emissions)
	- Who wants to to know what: Farmers: crop yield and perfomance, threats (potential and actual) , env. (soil moisture, rainfall, temp.,..) / Policy makers: same as farmers but in much bigger scale (spatio-temporal) 
		ML methods that is discussed : 
		ML is used to extract Essential Agricultural Variables (EAV) from satellite observations 
		crop type mapping -> Multi-class classification   other typical ML problems Binary classification,  example of the work can be used by CERISE project is [Vits for SITS](https://openaccess.thecvf.com/content/CVPR2023/html/Tarasiou_ViTs_for_SITS_Vision_Transformers_for_Satellite_Image_Time_Series_CVPR_2023_paper.html) with the [GitHub](https://github.com/michaeltrs/DeepSatModels) using vision transformer for satellite image recognition  (more in [[AI - Remote sensing]]) segmentation, regression, OOD detection (outlier detection) and some other methods 
		yield estimations, pest and disease detection, precision agriculture , robotic farming 
	- We need to increase yield to reduce the land use 
- **AI for Forestry** [pdf](https://www.dropbox.com/scl/fi/4j0y9m563ab9tnw1s1ft5/Forest-Slides-2024.pdf?rlkey=vgy133tgmhkllj4cklng55mhz&dl=0)
	- super intersting course! 
	- sounds of nature (https://xeno-canto.org/)  and other sources 
	- https://lila.science/datasets 
	- https://www.worldweatherattribution.org/about/
	- https://www.the-iea.org/
	- great slide about carbon storage 
	- large deforestation in global south while global north is rebounding 
	- deforestation is contributing to 18% of global anthropogenic emission / we should differentiate between the deforestation and  forest degradation 
	- Climate crisis results in biodiversity loss as well 
	- Monitoring, Reporting and Verification (MRV) for any incentives  and ML can be used
	- Bioacoustic :  identify the sounds of biodiversity with sound scape 
	- equitable ai: bias 

**Tutorial:**
-  Introduction slides to tutorial [pdf](https://www.dropbox.com/scl/fi/xidu8b15x9xjdo0bg8qeb/Tutorial-Slides-AFOLU.pptx?rlkey=izz01ztmdvb0o7h6h63yk70ok&dl=0)
- [Land Use and Land Cover Classification using Pytorch](https://www.climatechange.ai/tutorials?search=id:land-use-and-land-cover-lulc-classification-using-deep-learning-part-i&utm_source=summer-school2024&utm_medium=lulc-classification-tutorial)
- Walkthrough Video ([Part 1](https://youtu.be/6Cdwwlkkz80), [Part 2](https://youtu.be/gVEMfvnUwl4))

#### Day 3 - AI for Biodiversity and Ecosystems - June 26, 2024

**Lecture Recording:**

[https://youtu.be/I9TIRncO9HE](https://youtu.be/I9TIRncO9HE)

**Lecture Slide Decks :**

- AI for Wildlife Conservation ([pdf](https://www.dropbox.com/scl/fi/15tjvvboyme7wad03o3vx/CCAI_Biodiversity.pdf?rlkey=gipwdldwrzjqg9ffwl4pae5fq&dl=0))
	- habitat loss is concentrated in most vulnerable areas , many species are missing enough information 
	- sensors are used in different scales to monitor animals 
	- ML for animal detection and conversation and pose detection ; it helps to scale up 
	- Reconstruction of environment (3d models 7 LiDar)
	- uncertainty should be always provided 
- AI for Conservation Decisions ([pdf](https://www.dropbox.com/scl/fi/cbmco219v22qk9bkxe3pd/CCAI_AI_Conservation-Decisions.pdf?rlkey=b75mz81ayagecezd0sgub2b0l&dl=0))
	- 60%  of wildlife is lost since 1970 
	- 1M out of 8M species are in danger of extinction 
	- In causal inference, the key challenge is that we cannot observe what would have happened to the same unit (e.g., person, group) under a different treatment or condition (the counterfactual). This is often referred to as the "fundamental problem of causal inference."

**Tutorial:**

- [Agile Modeling for Bioacoustic Monitoring](https://www.climatechange.ai/tutorials?search=id:agile-modeling-bioacoustic-monitoring&utm_source=summer-school2024&utm_medium=bioacoustic-monitoring-tutorial)
- Live walkthrough on July 1, see [this calendar event](https://community.climatechange.ai/c/calendar/agile-modeling-for-bioacoustic-monitoring-live-tutorial-walkthrough-55e95934-ceb4-4a34-87d3-cdb50d036166) for details!    

#### Day 4 - AI for Social Sciences, Economics and Policy, Part I - June 28, 2024

**Lecture Recording:**

[https://youtu.be/q-rbAyZuZjo](https://youtu.be/q-rbAyZuZjo)

**Lecture Slide Decks:**

- **Climate Innovation Policy** [pdf](https://www.dropbox.com/scl/fi/5hb6e07fc58gvcv0wnq13/CCAI_Innovation-Policy.pdf?rlkey=nk8yyhxijjpgc30vemvkcye7n&dl=0)
	- innovation: for 2030 goals we already have the technology, but we need political power and will  / for 2050 goals we still dont have the necessary tech 
	- innovation like tech (as hardware) doesnt happened in vacuum , investment, policies, and regulation are software 
	- on average we need 4-5 Trillion $ a year until 2050
	- now carrots are much stronger than sticks in innovation policies 
	- political economy of climate change is difficult because benefits are in future and for all, while costs are visible and immediate and bares by specific groups    
- **Artificial Intelligence for Climate Action under the UNFCCC** [pdf](https://www.dropbox.com/scl/fi/wg87iamxyttay9cc13rjy/CCAI_UNFCCC_TEC.pdf?rlkey=ps8aib9kkqr949hjdp5eaq27i&dl=0)
	- UNFCC TEC (Technology Executive Committee) : policy 
	- UNFCC Climate Technology Centre and Network (CTCN) : implementation and assistance 
	-  ["#ai4climateaction"](https://unfccc.int/ttclear/artificial_intelligence) initiative by UNFCC  started on April 2024 : implementation, capacity building and raising awareness  
	- [AI Innovation Grand Challenge](https://enter.innovationgrandchallenge.ai/2024) : Deadline is August 12th 2024  

**Tutorial:**

- [Research Synthesis using NLP in the Field of Climate Change](https://www.climatechange.ai/tutorials?search=id:nlp-climate-policy-part1&utm_source=summer-school2024&utm_medium=policy-nlp-tutorial)
- Walkthrough Videos
    - [Part 1](https://youtu.be/KEScm0s7RCs)
    - [Part 2](https://youtu.be/pPDsLQIvWMM)

#### Day 5 - AI for Climate Science - July 2, 2024

**Lecture Pre-Readings:**

- [Climate science / Climate change basics](https://www.ipcc.ch/report/ar6/wg1/resources/spm-headline-statements/) 
- Section 8 of the [Tackling Climate Change with Machine Learning](https://dl.acm.org/doi/10.1145/3485128) paper
- Bonus: [https://www.nature.com/articles/s41586-019-0912-1](https://www.nature.com/articles/s41586-019-0912-1)
    

**Lecture Recordings:**

- [AI for Climate Science](https://youtu.be/P5_R_5kJDas)
- [AI for Weather](https://youtu.be/P5_R_5kJDas) (starting at 1:01:21)

**Lecture Slide Decks:**

- AI for Climate Science ([pdf](https://www.dropbox.com/scl/fi/y3in4zl9glsxm7r5bffjk/CCAI_AI_Climate.pdf?rlkey=q9c496dxd9gaisa6b22zchdtq&dl=0))
- AI for Weather ([pdf](https://www.dropbox.com/scl/fi/15n8j2h8xem67gknv226k/CCAI_AI4Weather.pdf?rlkey=smjfgfgzf0osyp241p3vfa691&dl=0))


**Tutorial:**

- [Forecasting the El Nino/ Southern Oscillation with Machine Learning](https://www.climatechange.ai/tutorials?search=id:forecasting-the-el-nino-southern-oscillation-with-machine-learning&utm_source=summer-school2024&utm_medium=forecasting-el-nino-tutorial)
- [Walkthrough Video](https://youtu.be/Ck2XWyj5CRo)
    

#### Day 6 - AI for Monitoring, Reporting, and Verification - July 5, 2024

Lecture Recording:

https://youtu.be/j3_jE0ZqsMM

Lecture Slide Deck [pdf](https://www.dropbox.com/scl/fi/px39po0sflo1mlx3pjznc/CCAI_Emissions-Accounting-and-Monitoring.pdf?rlkey=69zyexoed057sxzxd03fanzex&dl=0)
talk consist of multiple subject , most interesting for me was 
- carbon footprint estimation for three scopes of an entity (1: upstream , 2: processes, 3: downstream  )
- bottom up approach :  emission from units and entities and countries 
- ml for emission accounting and using of feature sensitivity for sanity check 
- top down: like using remote sensing climate trace is an example 
- monitoring of nature-based c-removal 
- [Remote sensing-based biomass estimation of dry deciduous tropical forest using machine learning and ensemble analysis](https://www.sciencedirect.com/science/article/abs/pii/S0301479722002122)
- ![Image 1](https://ars.els-cdn.com/content/image/1-s2.0-S0301479722002122-ga1.jpg)
- [High Resolution 1m Global Canopy Height Maps](https://gee-community-catalog.org/projects/meta_trees/#high-resolution-1m-global-canopy-height-maps "Permanent link") with pros and cons 
- assessing the potential impact and potential difficulties ( as easy and explainable as possible and as difficult as necessary  ) 

Tutorial:
- [Estimating Coal Power Plant Operation From Satellite Images with Computer Vision](https://github.com/climatechange-ai-tutorials/coal-power-mrv)
- [Walkthrough Video](https://www.youtube.com/watch?v=ec11zbTQCcM&ab_channel=ClimateChangeAI)

#### Day 7 - AI for Social Sciences, Economics and Policy, Part II - July 16, 2024

**Suggested Readings:**

- [Climate Econometrics](https://www.dropbox.com/scl/fi/v9zd35itnglsqfafih1dn/CCAI_Climate-Econometrics.pdf?rlkey=a0uu6le02b6bjp8963ygxssq7&dl=0)
    - This resource covers much of the topics of the lecture in greater detail and depth.
- [Nonlinear temperature effects indicate severe damages to U.S. crop yields under climate change](https://www.dropbox.com/scl/fi/jyoq0neamqo67d8ky4dxq/CCAI_schlenker-roberts-2009-nonlinear-temperature-effects-indicate-severe-damages-to-u-s-crop-yields-under-climate-change.pdf?rlkey=s52de4i39zbktp1hoh0t2z9l7&dl=0)
    - Example paper estimating a climate-outcome dose response curve and using it to
        project the effects of climate change
- A [Guide to Updating the US Government’s Social Cost of Carbon](https://www.dropbox.com/scl/fi/5krzmthtgm5dt117fiotg/CCAI_A-Guide-to-Updating-the-US-Government-s-Social-Cost-of-Carbon.pdf?rlkey=aqqmrpq9f6wa20cihcg89jvpg&dl=0)
    - Describes how climate-outcome dose-response functions are used to estimate the social cost of carbon, and the policy relevance of these calculations


**Lecture Recording:**

- [AI for Social Sciences, Economics and](https://youtu.be/jJsRRDy3WHQ)
- How GHG influence environment (previous talks)
- How changes in environment influence human wellbeing (focus of this talk)
	- climate variability impacts on social outcomes : linking the climate and the response function  as below:  
	- we can build this based on historical function , for example yield function based on temperature or cloud cover  ; then combining it with climate outcomes we can have a prediction of outcomes on different scenarios 
	- Social Cost of Carbon (SCC): the monetized value of all future net damage associated with a 1 metric ton increase in C02 emissions 
	- SCC as basis of the cost benefit analysis 
	- discounting damage in the future as it assume that money ( negative as damage) has less value in future compared to present 
	- How to estimate SCC? 
		- linear regression y = f(c) + controls + e
	- Panel Fixed effect Regression 
		- Panel : repeated observation of y and C for multiple locations over time 
		- Fixed effect:  a set of intercepts , often high dimensional and controlling for time and space  (like intercept for a county)
		- regression: ordinary least square linear regression 
	- implementing of the fixed effect to isolate the variations to be "as good as randomly assigned"
	- differentiate between the causal effect of the weather and longer term effect that is climate 
	- impact of temperature and soil moisture on crop yields : as climate variables effecting covarying variables compared with only temperature  
	- challenge
		- non linearity : observation are only aggregated, and local potential could be missed by canceling the variability or due to non-linear response function  derivation : non-linearity of the sum-up filed response to generate over the county level (by quadratic form  assumption ) Example in the slides 
		- Heterogeneity : response differs across space, time, and other attributes 
		- Model selections : remove and normalised for all the variables that you want to remove 

**Lecture Slide Deck:**
- [AI for Social Sciences, Economics and](https://www.dropbox.com/scl/fi/iltrs2bjsabk045cneros/CCAI_AI-for-Social-Sciences-Economics_II.pdf?rlkey=4quckyw2k93eml0e41og4em2s&dl=0)


#### Day 8 - Ethics, Impacts, and Regulation of AI - July 18, 2024

**Lecture Recordings:**

- [Ethics of AI](https://youtu.be/v3M4gdU83Z8) (very bad quality voice)
- [Regulation of AI](https://youtu.be/v3M4gdU83Z8) (starting at 1:03:53)
	- new regulation in horizon , China has some limited, US has Biden act, but EU AI act is the first broadly defined AI acts 
	- Artificial intelligence liability directive  
	-  AI definition in AI ACT : machine-based system with autonomy , that infers from input to an output that can influence world  
		- excluding : inference goes beyond basic data processing / rule based system by natural persons 
	- Four risk levels are defined 
		- prohibited ai  : social scoring , wide surveillance 
		- high risk : product safety , medical use case , education , credit system, migration, military, elections (not included in e-com, search engine, digital marketing)
		- Limited risk: Transparency 
		- Minimal risk: Ai literacy (all people who work with AI needs to have educations about AI) example of is chatbots: Disclosure of generated media by AI, a text production for public usage , Labeling of AI-generated and water mark 
		- ChatGPT / Claude doesnt fit any of them as they are in all of them
	- Environmental aspect  is not included 
	- Rules for pipeline 


- All foundation models (approximate GPT4 models) has specific obligations
- GHG effect pf ICT/AI : around 1.8 - 3.9 %  almost 2x more than air travel , inference also has big impact (one image generation = charging an iphone fully), their applications also has impact (like drilling oil for cheaper) 
- water consumption of ai is huge, and lot of it is evaporate (which is GHG)
- Gen AI will not have big impact on mitigation CC
- sustainable ai  : GHG emission and water usage  so far AI is not covered by Environmental regulations so far
- EU AI act is applied to anywhere as long as they are services and served client in EU / there are transparency requirement /  provider of high-risk ai system should disclose their computing consumption / assessment and mitigation of the systemic risks for very large foundation models (GPT4) might be required (not fully clear) / an emissions trading regime for ai is not including the large models  and most of them are build in places that have no tight regulation
- Open-source FMs are excluded (creates a loop hole)
-  Future : require standard , rule on training and define carbon and energy budgets 
-  [recsai.org](https://www.recsai.org/) 
	 The International Expert Consortium on the
	The International Expert Consortium on the Regulation, Economics, and Computer Science of AI (RECSAI) provides a platform to facilitate cross-disciplinary enquiries on key questions and challenges related to artificial intelligence. 

**Lecture Slide Decks:**

- [Ethics of AI](https://www.dropbox.com/scl/fi/3xjym2lrmbevv1rxd7bt6/CCAI_ethics.pdf?rlkey=nakyhcsl214z4e6c4nok2om5p&dl=0)
- [Regulation of AI](https://www.dropbox.com/scl/fi/w4akvt37zmnt1gavl71wh/CCAI_Regulation_AI.pdf?rlkey=3j910l9yf34766ixpd2pzpexs&dl=0)

#### Day 9 - AI for Buildings and Cities - July 19, 2024
**Lecture Recordings:**

- [Role of data and AI for climate change mitigation and adaptation in cities](https://youtu.be/RJ__2-qViCM)
- [AI for Buildings and Cities](https://youtu.be/RJ__2-qViCM) (starting at 1:01:01)

**Lecture Slide Decks:**

- [Role of data and AI for climate change mitigation and adaptation in cities](https://www.dropbox.com/scl/fi/63fzu1u9pzoz39hdgmnjx/CCAI_data_AI_cities.pptx.pdf?rlkey=kl79blnm9j6pgf98p5fs1r49a&dl=0)
- [AI for Buildings and Cities](https://www.dropbox.com/scl/fi/392iwquv8qgxuzkuw3sas/CCAI_AI_Buildings_Cities.pdf?rlkey=olz3xqdmcxtqr18dwkpftc4m7&dl=0)

**Tutorials:**

- [Building Load Forecasting with Machine Learning](https://www.climatechange.ai/tutorials?search=id:building-load-forecasting-with-machine-learning&utm_source=summer-school2024&utm_medium=building-load-forecasting-tutorial)
    - [Walkthrough Video](https://youtu.be/eTEBqljqM1U)
- [CityLearn Tutorial](https://www.climatechange.ai/tutorials?search=id:citylearn&utm_source=summer-school2024&utm_medium=citylearn-tutorial)
    - [Walkthrough Video](https://youtu.be/4SdRCDvyZUU
- [Building Control with RL using BOPTEST](https://www.climatechange.ai/tutorials?search=id:building-control-with-rl-using-boptest&utm_source=summer-school2024&utm_medium=boptest-tutorial)
    - [Walkthrough Video](https://youtu.be/RTz4OIFbm6M)

#### Day 10 - GHG Impact Assessment of AI - July 22, 2024

**Lecture Recordings:**

- [GHG Impact Assessment of AI](https://youtu.be/G5VuaWaYsLU)
- [Responsible AI and Sustainability](https://youtu.be/G5VuaWaYsLU) (starting at 1:02:10)


**Lecture Slide Decks Summary:**

1. **[GHG Impact Assessment of AI](https://www.dropbox.com/scl/fi/974hpjngmf313tquvy0hh/CCAI_GHG_impact_assessment_of_AI.pdf?rlkey=1jfdc997hf88qkdw47relepnd&dl=0)**

   - **Impact Assessment:** Measures greenhouse gas (GHG) emissions in terms of CO2 equivalent, focusing on the Global Warming Potential (GWP) of AI technologies.
   - **Life-Cycle Assessment (LCA):** Examines emissions from the entire lifecycle of AI systems—from production (cradle), operation (gate), to disposal (grave).
   - **Emissions Scope:** Covers three categories:
     1. **Scope 1:** Direct emissions from owned or controlled sources.
     2. **Scope 2:** Indirect emissions from the generation of purchased electricity.
     3. **Scope 3:** All other indirect emissions, including those from customer use.
   - **GHG Emissions in Machine Learning (ML):**
     - **Compute-Related Impact:** Includes emissions from ML training and inference, with tools like [CodeCarbon](https://codecarbon.io/) used to measure energy consumption. The energy demand for training foundation models (FMs) such as GPT-4 is rapidly growing, particularly for inference, which can account for 60-70% of energy use due to the high volume of inferences.
     - **Local vs. Global Energy Impact:** Future scenarios of energy consumption vary globally and locally, depending on the energy mix of local grids used by data centers.
     - **Google's ML Energy Use:** Reports that 10-15% of its total energy consumption is attributed to ML.
   - **Application-Related Impact:** ML can reduce costs and emissions in some sectors (e.g., improved cooling in data centers), but it may also encourage increased usage, known as the rebound effect.
   - **System-Level Impact:** ML can help reduce emissions across the supply chain by optimizing various processes.
   - **Shift to On-Device Inference:** There is a trend towards performing AI inference directly on devices, which could alter the emission landscape.
   - **Importance of Impact Assessment:** Understanding the cost and environmental impact of ML is crucial for developing sustainable AI practices.

2. **[Responsible AI and Sustainability](https://www.dropbox.com/scl/fi/c97i0hou1p4btelif02d2/CCAI_Responsible-AI-and-Sustainability.pdf?rlkey=ltwddi6ntnmjnyeuzuhwj0vmt&dl=0)**

   - **AI as a Socio-Technical System:** AI models use data extensively and have significant impacts on society.
   - **AI Ethics and Environmental Concerns:** AI ethics often overlook environmental impacts, while sustainability discussions might neglect issues of justice and equity. The Sustainable Development Goals (SDGs) cover both aspects.
   - **AI Guidelines:** Current guidelines for ethical and sustainable AI have limited convergence, are often vague, and open to interpretation.
   - **Efficiency and Usage Paradox:** As AI systems become more efficient, their use increases, leading to more significant overall impacts—a concept known as Jevons Paradox or the rebound effect.
   - **NeurIPS Code of Conduct (2023):** Encourages ethical and sustainable AI research practices.
   - **BLOOM Model Governance:** Focuses on governance and regulations for large language models like BLOOM with 176 billion parameters.
   - **Key Ethical and Sustainability Issues:**
     - **Representativeness:** Assumptions made by AI models can lead to mislabeling, as seen with ImageNet's biodiversity categories.
     - **Evaluation Metrics:** AI evaluation should not rely on a single metric; multiple aspects should be measured to understand trade-offs and impacts better.
     - **Transparency:** Due to the complexity of models like transformers, transparency is limited. Efforts like model cards and datasheets aim to improve understanding of models and datasets.
     - **Equity:** As language models grow larger, they risk increasing the digital divide and creating disparities in justice and power.
   - **Resource for AI Imagery:** [Better Images of AI](https://betterimagesofai.org/) provides high-quality visuals for AI.

**Additional Lecture Materials:**

- **Resources Shared by Dr. Luccioni:**
  - [Towards Measuring and Mitigating the Environmental Impacts of Large Language Models](https://cifar.ca/wp-content/uploads/2023/09/Towards-Measuring-and-Mitigating-the-Environmental-Impacts-of-Large-Language-Models.pdf)
  - [Estimating the Carbon Footprint of BLOOM, a 176B Parameter Language Model](https://jmlr.org/papers/volume24/23-0069/23-0069.pdf)
  - [Responsible AI Licenses Generator](https://www.licenses.ai/rail-license-generator)

**Tutorials:**

- **[Reducing Your Climate Impact When Training ML Models](https://www.climatechange.ai/tutorials?search=id:reduce-climate-impact-when-training-ml-models&utm_source=summer-school2024&utm_medium=tracking-ml-emissions-tutorial):** Provides strategies for minimizing the environmental footprint during the training of ML models.
- **[Walkthrough Video](https://www.youtube.com/watch?v=mQb27WtEh44):** A video tutorial on reducing the climate impact of ML model training.


#### Day 11 - AI for Energy Systems - July 29, 2024

**Lecture Pre-Readings:**

_Required readings_

- [Electricity 101](https://www.rff.org/publications/explainers/electricity-101/)
- [Review: Machine Learning for Sustainable Energy Systems](https://www.annualreviews.org/content/journals/10.1146/annurev-environ-020220-061831)
- TED Talk: [The energy Africa needs to develop — and fight climate change](https://www.ted.com/talks/rose_m_mutiso_the_energy_africa_needs_to_develop_and_fight_climate_change?language=en)
- [The Modern Energy Minimum: The case for a new global electricity consumption threshold](https://www.energyforgrowth.org/wp-content/uploads/2019/01/FULL-Modern-Energy-Minimum-final-Jan2021.pdf) (feel free to skim)

_Supplemental readings_
- [FERC Energy Primer](https://web.archive.org/web/20220126013442/https://www.ferc.gov/sites/default/files/2020-06/energy-primer-2020_0.pdf)

_Prerequisites_
- No special prerequisites, beyond engaging with the required readings above ahead of time.

**Lecture Recording:**

[AI for Power and Energy Systems](https://youtu.be/L8CYBqgAPAc)

**Lecture Slide Deck:**
- [AI for Power & Energy ](https://www.dropbox.com/scl/fi/y0o9mg3ah99uenubl2srs/CCAI-Power-Energy-Systems.pdf?rlkey=2gnwun6x1qrop40x12sb11ocb&dl=0)


**Tutorial:**
- [AI for Optimal Power Flow](https://www.climatechange.ai/tutorials?search=id:optimal-power-flow&utm_source=summer-school2024&utm_medium=opf-tutorial)

#### Day 12 - AI for Transportation - July 31, 2024

**Lecture Pre-Readings:**

- [IPCC AR6 WGIII](https://www.ipcc.ch/report/ar6/wg3/downloads/report/IPCC_AR6_WGIII_FullReport.pdf) Chapter 8 (Urban settlements) and Chapter 10 (Transport). We suggest **reading the executive summaries** of both chapters
- Kaack, Lynn, Transportation in Rolnick, David, et al. "[Tackling climate change with machine learning](https://dl.acm.org/doi/10.1145/3485128)." ACM Computing Surveys (CSUR) 55.2 (2022): 1-96.

**Lecture Recording:**

- [AI for Transportation](https://youtu.be/i23jr7pkjsM)

**Lecture Slide Deck:**
- [AI for Transportation](https://www.dropbox.com/s/38qz4ss4c6hmucp/CCAI_AI_%26_Transportation.pptx?dl=0)

**Tutorial:**

- [Predicting Mobility Demand from Urban Features](https://www.climatechange.ai/tutorials?search=id:predicting-mobility-demand&utm_source=summer-school2024&utm_medium=urban-mobility-tutorial)
- [Walkthrough Video](https://youtu.be/L8L7LFsDlxg)
#### Day 13 - Climate, Health, and AI - August 1, 2024

**Lecture Recording:**
- [Climate, Health, and AI](https://youtu.be/3mtbFx_8VVc)

**Planetary Health: Impact of Human-Induced Planetary Changes on Human Health**

- **Overview:**
  - A quarter of deaths worldwide are linked to environmental factors.

- **Health Impacts:**
  - **Direct:** Heatwaves.
  - **Indirect:** Various environmental changes leading to health issues.
  - **Long-term:** Climate-induced migration.

- **Vulnerable Populations:**
  - Increased heat affects certain groups more severely, including the elderly, pregnant individuals, outdoor workers, those with lower socioeconomic status, and people with specific lifestyles or genetic backgrounds.

- **Air Pollution and Health:**
  - The link between air pollution and mortality is well-documented, along with other health impacts.

- **The Role of Informatics:**
  - **Real-Time Data:** Provides immediate insights into environmental changes.
  - **Improved Knowledge:** Enhances understanding of environmental health impacts.
  - **Adaptation Strategies:** Includes early warning systems for heatwaves and floods, predicting disease outbreaks, tracking and monitoring air quality, and responding to pandemics.

- **Challenges and Opportunities:**
  - **Patient-Level Health Analytics:** Utilizing electronic health records to generate raw data for patient phenotyping.
  - **Climate-Informed Health Data:** Integrating climate information (such as temperature, air pollution, land use, and vegetation) with health data.
  - **Geospatial Linkage:** Combining patient-level data with geographic information to improve outcomes.
  - **Data Classification Issues:** The International Classification of Diseases (ICD) may not easily align with climate data, complicating the assessment of excess deaths.
  - **Healthcare Data Issues:** Challenges include biases, privacy concerns, safety, and the multi-modality of data.
  - **Biases in Data and Algorithms:** Data and algorithmic biases can lead to incorrect health assessments.
  - **Need for Awareness:** It's crucial to recognize inequalities and the lack of accurate representation of populations in data. 
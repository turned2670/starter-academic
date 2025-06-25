+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Undergraduate student"
  company = "Beijing University of Posts and Telecommunications"
  company_url = ""
  location = "Beijing"
  date_start = "2013-09-01"
  date_end = "2017-07-01"
  description = """

  * GPA: 3.9/4.0, Rank: 1/123
  * National scholarship
  * Meritorious Winner of MCM/ICM
  * Second Prize in Intel Cup National Collegiate Software Innovation Contest
  * First Prize in Student Innovation Contest
  """

[[experience]]
  title = "Research assistant"
  company = "Nanyang Technological University"
  company_url = "(Supervised by Yang Liu)"
  location = "Singapore"
  date_start = "2017-01-05"
  date_end = "2017-05-24"
  description = """
  
  * Leopard: Extract and assess program metrics of tested software programs to identify vulnerability-prone functions and CVEs, assisted with the fuzzing tools.
  """

[[experience]]
  title = "Ph.D. student"
  company = "Tsinghua University"
  company_url = "(Supervised by Yu Jiang and Jiaguang Sun)"
  location = "Beijing"
  date_start = "2017-09-01"
  date_end = "2022-07-01"
  description = """Representative works:    
  * RNN-Test: a general-purpose adversarial testing framework for seq2seq tasks in RNN systems. It produces adversarial examples by maximizing RNN state inconsistency against their inner dependencies. We also design two state-based coverage metrics for RNNs, enabling RNN-Test to generate adversarial examples and improve the coverage.
  * DLFuzz: the first DL testing framework combined with fuzz testing. DLFuzz mutates seed inputs to maximize neuron coverage and the prediction difference between original and mutated inputs, with multiple neuron selection strategies. Its paper published on ESEC/FSE 2018 is widely recognized with >300 citations."""

[[experience]]
  title = "Research intern"
  company = "Tencent"
  location = "Beijing"
  date_start = "2021-04-21"
  date_end = "2021-12-01"
  description = """
  * Train in-vehicle speech enhancement model, where audios with noise (particularly in-vehicle situation) will sound clear after speech enhancement.
  """

[[experience]]
  title = "Senior research engineer"
  company = "Huawei"
  location = "Beijing"
  date_start = "2022-08-21"
  date_end = ""
  description = """Core works:
  * Train a specialized LLM to assess response safety, evaluating whether outputs from tested LLMs meet predefined safety criteria when handling unsafe queries.
  * Detect deepfake and AIGC images & videos with classifiers of multiple features, as well as reconstruction-based methods utilizing diffusion models.
  * Construct unsafe multimodal data generation pipeline and design a semantics-aware moderation framework with MLLMs.
  * Defend black-box query attack on face recognition with probabilistic fingerprints.
  """

+++

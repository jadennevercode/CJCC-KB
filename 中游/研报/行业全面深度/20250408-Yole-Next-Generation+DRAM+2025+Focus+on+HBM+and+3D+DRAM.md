# 20250408-Yole-Next-Generation+DRAM+2025+Focus+on+HBM+and+3D+DRAM

- 来源文件：`中游/研报/行业全面深度/20250408-Yole-Next-Generation+DRAM+2025+Focus+on+HBM+and+3D+DRAM.pdf`
- 原格式：PDF
- 页数：225
- SHA-256：`8c6be10ba03254aa870811cb82aeb90a5d409877bf52703c089465ef12a4cfe3`


## 第 1 页

FROM TECHNOLOGY TO MARKET


Next-Generation
DRAM 2025

Focus on HBM and 3D DRAM


 YINTR25484| www.yolegroup.com | ©Yole Group 2025

## 第 2 页

TABLE OF CONTENTS
Next-Generation DRAM 2025 – Focus on HBM and 3D DRAM


 • Glossary and definitions 3 • DRAM technology trends 105
 • Report objectives 6 • DRAM scaling:challenges and solutions 110
 • Scope ofthe report 7 • Technology roadmaps and key trends 117
 • Methodology & definitions 9 • High Bandwidth Memory (HBM) 126
 • About the authors 10 • Leading-edge DRAM manufacturing 137
 • Companies cited in thisreport 11 • DRAM fabs and wafer production 139
 • What we got wrong, what we got right 12 • Equipment and materials for DRAM manufacturing 145
 • 2025 vs 2024 forecast comparison 13 • Advanced Packaging for DRAM 157
 • 3-page summary 14 • 3D stacking –focus on bonding technologies 162
 • Executive summary 18 • Memory-logic heterogenous integration 167
 • Market forecasts 41 • 3D DRAM 175
 • DRAM market overview 42 • R&D activitiesfor3D DRAM 181

 Revenue,bitshipments,ASP,wafers(incl.CBA),andmore
 • IPlandscape 195
 • HBM market forecast 51 • Long-term market evolution scenario 199
 • Introduction toDRAM technology & business 66
 • Brief historyof DRAM technology 67 • Processing in memory –overview 203
 • DRAM business – ahistorical overview 71 • Conclusions 208
 • Market drivers and trends 76 • Related products 212
 • Players and market shares 82 • How touse our data 216
 • M&As and noteworthy news 88 • Yole Group Corporate presentation 217

 • Memory business inChina – focus on DRAM 94


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 2
 2025-04-08 01:51

## 第 3 页

GLOSSARY AND DEFINITIONS


 1T-1C: DRAM cell with 1 transistor and 1 capacitor MCP: Multi-Chip Package
 2T-0C: Capacitorless DRAM cell with 2 transistors MRAM: Magnetic Random-Access Memory
 ASIC: Application-Specific Integrated Circuit MR-MUF: Mass Reflow-Molded Underfill
 ASSP: Application-Specific Standard Product NA Numerical Aperture (e.g., High NA EUV lithography)
 ASP: Average Selling Price NAND: Flash memory with logical NAND-type structure
 APU: Application Processor Unit NCF-TCB Non-Conductive Film-Thermocompression Bonding
 BEOL: Back End of Line NOR: Flash memory with logical NOR-type structure
 CAGR: Compound Annual Growth Rate NRAM: Nanotube RAM
 CBA: CMOS Bonded Array NV: Non-Volatile
 CMOS: Complementary-Metal-Oxide-Semiconductor PCIe: Peripheral Component Interconnect Express
 CoWoS Chip on Wafer on Substrate PCM: Phase-Change Memory
 CXL: Compute Express Link PCB: Printed Circuit Board
 DDR: Double Data Rate QLC: Quad-Level Cell
 DIMM: Dual In-Line Memory Module RCD: Register Clock Driver
 DRAM: Dynamic Random-Access Memory RRAM: Resistive Random-Access Memory
 ECC: Error Code Correction SAM: Serviceable Available Market
 EUV: Extreme Ultra-Violet SADP: Self-Aligned Double Patterning
 F2: Memory-cell size unit (F is the smallest feature size) SAQP: Self-Aligned Quadruple Patterning
 FC-BGA: Flip-Chip Ball Grid Array SiP: System in Package
 FEOL: Front End of Line SLC: Single-Level Cell
 FFET: Ferroelectric Field-Effect Transistor SoC: System on Chip
 FOWLP: Fan-Out Wafer-Level Packaging SRAM: Static Random-Access Memory
 FPGA: Field-Programmable Gate Array SSD: Solid-State Drive
 GDDR: Graphics DDR (used in GPU) TAM: Total Accessible Market
 HBM: High Bandwidth Memory TSV: Through Silicon Via
 IGZO: Indium-Gallium-Zinc-Oxide WLCSP: Wafer-Level Chip-Scale Packaging
 IOPS: Input/Output Operations Per Second WB-BGA: Wire Bond Ball Grid Array
 LLW: Low Latency Wide I/O x, y, z, a, b… These letters indicate the technology generation in each class, e.g.,
 LPCAMM Low Power Compression Attached Memory Module 1y denotes the 2nd gen. of the “10nm class”. Note: Micron uses Greek letters.
 LPDDR: Low-Power DDR (used in mobile applications)
 LPW: Low-Power Wide I/O

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 3
 2025-04-08 01:51

## 第 4 页

DEFINITIONS – MEMORY DENSITY
Mind the unit!


 Name of the unit Abbreviation Size

 bit b “0 or 1”

 byte B 8 bits
 Kilobit Kb 103 bits

 Kilobyte KB 103 bytes (8 Kb)

 Megabit Mb 106 bits

 Megabyte MB 106 bytes (8 Mb)

 Gigabit Gb 109 bits

 Gigabyte GB 109 bytes (8 Gb)

 Terabit Tb 1012bits

 Terabyte TB 1012bytes (8 Tb)

 Petabit (million of Gb) Pb 1015bits

 Petabyte (million of GB) PB 1015bytes (8 Pb)

 Exabit (billion of Gb) Eb 1018bits

 Exabyte (billion of GB) EB 1018bytes (8 Eb)

 Zettabit (trillionof Gb) Zb 1021bits

 Zettabyte (trillion of GB) ZB 1021bytes (8 Zb)


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 4
 2025-04-08 01:51

## 第 5 页

DEFINITIONS – MEMORY TECHNOLOGIES

 Volatile memory

 Memory • Requires power supply to retain information.

 • Examples: DRAM, SRAM.

 Non-volatile Volatile Non-volatile memory

 • Retains stored information even when unpowered.
 Mainstream NVM technologies are based on electrical
 Standard Emerging DRAM charge storage.

 • Examples: flash NAND and NOR.

 Flash MRAM & SRAM Random access memory
 NAND STT-MRAM
 • Data can be read and written in the same amount of time,
 irrespective of the physical location inside the memory.
 Flash PCM Emerging non-volatile memory
 NOR
 • Based on principles other than retention of charges.
 RRAM
 (e.g.,CBRAM, OxRAM) • Some products are already available on the market, and
 EEPROM mass production has started. Certain newly emerging

 FeRAM & memories are stillunder development.
 NVSRAM FeFET
 Note:some “emerging” memories have already emerged and are now inmass production, whereas
 others are stillin R&D or pre-production and could be more appropriately referred to as
 NRAM “prototypical”.Here, the term “emerging” is used to indicate allrecent technologies and to
 (carbon nanotubes) distinguishthem from theirmainstream counterparts.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 5
 2025-04-08 01:51

## 第 6 页

REPORT OBJECTIVES


 Yole ispleased to provide you with the 2025 update of the “Next-Generation DRAM” report, which provides a detailed analysis of the DRAM
 market and technology trends with a focus on DRAM scaling, high-bandwidth memory, and 3D DRAM. The main objectives of this report are as
 follows:

 (1) Provide a comprehensive analysis of the DRAM market (2) Present the latest DRAM technology trends

 • Description of the memory market, outlining the DRAM market • Technology roadmaps by DRAM supplier for next-generation
 cyclicality throughout history (from the early 1980s to the DRAM devices, such as DDR5 and HBM.
 present). • Technical solutions for DRAM scaling in terms of equipment
 • DRAM business overview, with market forecasts in terms of (including EUV lithography), novel cell structures, and materials.

 revenue, bit shipments, bit demand, and average selling prices. • Advanced packaging for memory: technical trends and
 roadmaps for high-performance DRAM devices.
 • DRAM supply analysis, with capex and wafer production forecast
 with details on the adoption of CBA* DRAM architectures. • Adoption of hybrid bonding for CBA* DRAM, HBM, as well as for
 emerging AI devices based on logic-DRAM stacks.
 • High-Bandwidth Memory (HBM) business: market drivers, player • Emerging technologies, such as 3D DRAM and processing-in-
 dynamics, bit shipments, wafer production, and more. memory (PiM).

 • Long-term 3D DRAM market evolution (2030-2035) and impact
 of the 2D-to-3D transition on the DRAM equipment business. (3) Describe the supply chain and the DRAM ecosystem

 • DRAM supply chain with a focus on wafer-fab equipment and
 material suppliers.

 *CMOS Bonded Array (CBA) – An XtackingTM-like approach used for stacking the DRAM • China’s DRAM business with analysis of the main technology
 array wafer and the “periphery-circuit” wafer via hybrid bonding (wafer-to-wafer).
 developments by Chinese players.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 6
 2025-04-08 01:51

## 第 7 页

SCOPE OF THE REPORT

 DRAM Market Dynamics Next-gen. DRAM via Advanced Packaging


 • DRAM market revenue and bit shipments HBM and logic-DRAM integration CBA* DRAM

 (with details on DDR5 and HBM) HBM
 Logic
 • DRAM wafer production by node INTERPOSER
 • Market adoption of CBA* DRAM
Your needs • Market scenario for 3D DRAM
are out of the (with details on theadoption of hybrid bonding)
report’s 3D DRAM
scope? Next-gen. 2D DRAM technology
Contact us for • 6F2 →4F2
a customized • Vertical Channel Transistors
inquiry 1c(𝛾) 3D
 • CMOS bonding

 Multiple possibilities under investigation
 1d(𝜕)

 1ε • 1T-1C DRAM with flipped capacitors
 2D 0a • 2T-0C DRAM
 0b 0c • 1T DRAM with 3D flash architecture


 2025 2027 2029 2031

 huguodong@cmbchina.com *CBA: CMOS Bonded Array Next-Generation DRAM 2025 | Report | www.yolegroup.com7
 2025-04-08 01:51

## 第 8 页

IDENTITY CARD
 Quick Summary
What will you find in this report? • The “Next-Generation DRAM 2025”
 report provides a detailed analysis of
 the leading-edge DRAM technology
 and market trends. It describes the
 technical challenges and the potential
 solutions for continuous DRAM device
 scaling; it offers details on DDR5, HBM,
 processing-in-memory (PiM), memory
 Main Markets Main Systems Technology Key metrics packaging, and other emerging
 tracked technologies, including 3D DRAM.
 Key Features
 Automotive & Mobility DRAM 2020-2025-2030 Units • Overview of the semiconductor
 Servers • DDR5 Timeframe memory market with a focus on DRAM.
 Personal Computers • HBM • Description of key technology trends
 Cell phones and tablets Value and R&D activities by suppliers, such as
 Defense & Aerospace • 3D DRAM CBA and 4F2 DRAM, 3D DRAM,
 Wearables processing-in-memory (PiM) and HBM.
 Smart home appliances Wafer • Market forecast for DRAM in terms of
 Industrial Vehicles wafer production, bit shipments, bit
 demand, capex, and more.
 and more. Market shares • Analysis of ongoing and future DRAM
 Medical Players technology transitions, such as DDR4-
 to-DDR5, 3D DRAM, HBM with hybrid
 bonding, etc.
 Supply chain • Technology roadmaps by DRAM
 Mobile & Consumer suppliers and detailed analysis of the
 competitive landscape.
 Depth Strategy • Description of the DRAM ecosystem
 Telecom & analysis and analysis of the WFE and material
 for DRAM manufacturing.
 Infrastructure Financial
 System analysis What’s new?
 Module • Analysis of DRAM bit shipments by
 Frequency Business NewsBusiness news technology – DDR, LPDDR, GDDR, HBM
 Sub-module Trends – and by generation (e.g., DDR3, DDR4,
 update Device DDR5, DDR6)
 Process • Breakown of the HBM market by
 Technology generation –including HBM4, HBM4E,
 Q Quarterly Wafer status HBM5, and beyond – and by stack
 Material height (4Hi, 8Hi, 12HI, 16Hi and 20Hi).
 Yearly Equipment Technology • Revised HBM ASP model with
 Y Roadmap breakdown by interface.
 • Detailed analysis of the HBM supply
 chain highlighting key equipment and
 materials vendors.
 • Update on the Chinese HBM business:
 China’s reactions to US export controls,
 technology roadmaps for CXMT, recent
 investments, and player dynamics.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 8
 2025-04-08 01:51

## 第 9 页

METHODOLOGIES & DEFINITIONS

 Yole’s market forecast model is based on the matching of several sources:


 Preexisting
 information


 Market
 Volume (in Munits)
 ASP (in $)
 Revenue (in $M)


 Information
 Aggregation


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com9
 2025-04-08 01:51

## 第 10 页

ABOUT THE AUTHORS – MEMORY ACTIVITY


 Simone Principal Analyst, John LORENZ Principal Analyst,
 BERTOLAZZI, PhD Memory Memory
 Experience Experience
 • 15+ years in emerging semiconductors and devices • 20+ years in advanced semiconductor devices
 At Yole Group At Yole Group
 • Memory • Memory and computing
 Education Education
 • PhD in nanoelectronics • Bachelor of Mechanical Engineering
 • MSc in micro & nanotechnology
 • MSc in engineering physics

 Thibault GROSSI Senior Technology & Market Analyst Josephine LAU Senior Technology & Market Analyst,
 Memory Memory
 Experience Experience
 • 15+ years in electronics industry • 10+ years in memory and storage industry
 At Yole Group At Yole Group
 • Memory • Memory
 Education Education
 • MSc in electronic and computing science • Bachelor of Business Marketing
 • Passed CFA level 1


 Belinda DUBE Senior Technology & Cost Analyst Daniel NIU Market Researcher
 Memory
 Experience Experience
 • 6+ years in semiconductor industry • 3+ years in memory and processor industry
 At Yole Group At Yole Group
 • Memories, ICs, advanced packaging • Memory, computing and AI
 Education Education
 • Master’s degree in instrumentation & nanotechnology • Master’s degree in chemical engineering
 engineering


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 10
 2025-04-08 01:51

## 第 11 页

COMPANIES CITED* IN THIS REPORT


 ACM Research, Adata, Advantest, Alibaba DAMO Academy, Alliance Memory, Alphabet, AMEC, AP Memory, Apacer,
 Apple, Applied Materials, ASE, ASML, Avalanche, BeSang, Buffalo, Canon, CXMT, Cisco, Dell, Dosilicon, Etron, ESMT,
 Everspin, Ferroelectric Memory Company, Fujitsu, GigaDevice, GlobalFoundries, HHGrace, Hikstor, Hitachi, HLMC,
 HP, Huawei, IBM, ICLeague, IMEC, IMECAS, Infineon, Innostar, Intel, ISSI, Jasminer, JHICC, Kingston, KLA, Lam
 Research, Lenovo, Longsys, Liteon, Macronix, Materion, Micron, MonolithIC 3D, Montage Technology, Nano Labs,
 Nantero, Nanya, Naura, Neo Semiconductor, Nikon, Nuvoton, NXP, onsemi, Powerchip, Powertech, ProMOS
 Technologies, Qualcomm, Rambus, Reliance, Realtek, Renesas, Rohm, Samsung, SanDisk, Seagate, Semtech, Silicon
 Motion, SK hynix, SK Materials, Smart Modular Technologies, SMEE, SMIC, Sony, SPIL, SST, Spin Memory,
 STMicroelectronics, STEC, SunLune, Sunrise, Texas Instruments, Tokyo Electron, Toshiba, TowerJazz, TPSCo,
 Transcend, Tsinghua Unigroup, TSMC, UMC, UniIC Semiconductors, Unimos Microelectronics, Unisantis Electronics,
 Viking, Violin Memory, Winbond, XFab, XMC, YMTC, and more.


 *non*non--exhaustive listexhaustive list


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com11
 2025-04-08 01:51

## 第 12 页

WHAT WE GOT WRONG, WHAT WE GOT RIGHT
The HBM market is growing faster than expected, driven by aggressive GPU and AI ASIC commercialization roadmaps

 What we got wrong What we got right


 • In the previous edition of this report, we anticipated a • In early 2024, Yole Group was the firstmarket research
 gradual decline in the average price of HBM starting in firm to project impressive HBM revenue growth from
 2025, driven by increasing volumes and intensifying $5.4B in 2023 to over $14B in 2024. While this bold
 competition among the three leading suppliers. While forecast was initially met with skepticism by several
 competitive pressure continues to push prices downward, industry insiders, actual data not only confirmed it but
 the blended average price of HBM across multiple even surpassed expectations.
 generations isnow projected to rise with a CAGR24-30 of
 2%. This shift is primarily due to the complexity of next- • The transition to 4F²+CBA isset to occur before 2029,
 generation HBM4, HBM4E, and HBM5 devices, which may though the exact timeline remains uncertain. We
 include premium, customized options. currently anticipate ramp-up beginning with the 0a node.
 • The ramp-up of 4F2+CBA DRAM has been delayed by To address the needs of different verticalmarkets, DRAM
 approximately 2 years. Top memory makers are likely to manufacturers will likelyoffer a mix of 6F² and 4F²+CBA
 implement their 0d node with “conventional” 6F2 products.
 technology. • As expected, China continues to move aggressively
 • Due to stringent pitch/alignment requirements, CBA toward self-sufficiency in advanced semiconductor
 DRAM is expected to be implemented with fusion technologies, including HBM. The U.S. curbs on AI chips
 bonding, not hybrid bonding. have triggered significant investments and numerous
 • The adoption of collectivedie-to-wafer hybrid bonding for initiatives for producing leading-edge memory within
 HBM manufacturing has also been postponed from China. Reportedly, the firstHBM2 products by Chinese
 HBM4 (2026) to HBM5 with 20 dies per stack (2029). companies are getting ready for commercialization.

 However, we currently expect a wafer-to-wafer hybrid to • Samsung, SK hynix, and Micron continue investing in the
 be used in HBM4E (late 2027) to stack the firstDRAM development of 3D DRAM for long-term DRAM scaling.
 layerand the logic IC. The firstprototypes have been presented / discussed at
 • CXMT has ramped up DDR4 DRAM production to higher technical conferences: 5, 8, and 16 layers for SK hynix,
 levelsthan expected and introduced DDR5 DRAM (16nm Micron, and Samsung, respectively.
 process) ahead ofschedule.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 12
 2025-04-08 01:51

## 第 13 页

2025 VS 2024 HBM FORECAST COMPARISON
The HBM market is growing faster than expected, driven by aggressive GPU and AI ASIC commercialization roadmaps


 HBM Revenue ($B) HBM Bit Shipments (EB) HBM Wafer Production (K WPM)

 $100 8 800

 The generative AI race is accelerating,
 HBM revenues are set to rise with GPU and AI-ASIC suppliers The three major DRAM
 significantly over the next five shipping high volumes of products manufacturers have significantly
 years, driven by stronger-than- featuring increasing HBM content. In
 expected bit shipments and 2024, HBM bit demand exceeded expanded their TSV capacity and
 robust ASP ($/GB) dynamics. 6 expectations, and the projected CAGR 600 scaled up DRAM-HBM wafer
 $75 Notably, our model no longer for 2024-2029 is expected to remain production beyond expectations to
 assumes ASP erosion in the well above the typical data center meet strong customer demand.

 2024-2029 timeframe. DRAM growth rate (34% vs. 21%).


 $50 4 400
 We refined our
 model based on
 industry feedback on
 average yields and
 GB output per wafer.
 $25 2 200


 $- - -


 “Next-Generation DRAM” Report – 2024 Edition (Analysis in November 2023)
 “Next-Generation DRAM” Report – 2025 Edition (Analysis in March 2025)

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 13
 2025-04-08 01:51

## 第 14 页

3-PAGE SUMMARY


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 14
 2025-04-08 01:51

## 第 15 页

NEXT-GENERATION DRAM – MARKET OVERVIEW
HBM shipments expand rapidly with over 190% YoY growth in 2024, and revenue is on track to hit $98 billion by 2030


 • The High-Bandwidth Memory (HBM) market isexperiencing exponential growth, primarily driven by the proliferation of artificialintelligence (AI)workloads and high-
 performance computing (HPC) applications. The generative AI boom, catalyzed by the introduction of ChatGPT in late 2022, resulted in an unprecedented 187% year-over-
 year (YoY) increase in HBM bitshipments in2023, followed by an additional 193% surge in 2024. This trajectory is expected to persist,with HBM bitshipments forecasted to
 grow at a 31% compound annual growth rate (CAGR) through 2030.

 • HBM is significantly outpacing the broader DRAM market. Global HBM revenue is projected to increase from $17B in 2024 to $98B by 2030, reflecting a 33% CAGR.
 Consequently, HBM’s revenue share within the DRAM market isexpected to increase from 18% in2024 to 50% by 2030.
 • The market willsee another significant inflection point in 2025, with HBM revenues projected to double to ~$34B. Current supply constraints underscore the strategic
 importance of HBM in AI data centers and advanced computing platforms, as evidenced by reports from SK hynix and Micron indicating that their HBM production
 capacity isfullyallocated through 2025. These supply-side limitations reinforce the need forinvestments in capacity expansion to meet the escalating demand.

 • By contrast, conventional DRAM –including DDR, LPDDR, and GDDR – was valued at $80B in 2024 but isexpected to grow at a modest 3% CAGR between 2024 and 2030,
 constrained by inherent price fluctuations and market cyclicality(as detailed in the DRAM Market Monitor by Yole Group). The combined growth of HBM and conventional
 DRAM translates to an overall DRAM market CAGR of 12%,with revenues increasing from $97B in 2024 to $194.5B in2030.
 • From a bit shipment perspective, HBM represented 5% of totalDRAM bitsin 2024, equivalent to 11.9Eb (1.49M GB) out of 254Eb (31.7M GB), and isprojected to reach 9% by
 2030. As a premium-tier product, HBM's average selling price (ASP) iscurrently estimated to be up to four times higher than the blended DRAM ASP in 2024. While
 competition among the three dominant HBM suppliers is expected to exert downward pricing pressure, blended HBM ASPs are projected to remain stable due to
 sustained demand.

 • The introduction of next-generation HBM architectures – including HBM4, HBM4E, and HBM5 – willdrive further improvements in bitdensity and stacking technology,
 enabling greater memory capacity per package. These technological advancements will not only enhance performance metrics but also sustain premium pricing
 structures. Current market projections indicate that HBM ASP per gigabyte (GB) willincrease at a 2% CAGR from 2024 to 2030.
 • To capitalize on the AI-driven demand surge and accelerate market recovery, leading suppliers – including Samsung, SK hynix, and Micron – have increased their wafer
 allocations for HBM production. In 2024, HBM wafer output expanded by more than 150% YoY, reaching approximately 216K wafer starts per month (KWPM). This upward
 trajectory is expected to continue in 2025, with average monthly production projected to reach ~350 KWPM. By 2030, HBM wafer capacity is expected to scale to 590
 KWPM, reflecting a 9% CAGR2024-2030.
 • In parallelwith the industry’s strong focus on HBM, the slowdown inplanar DRAM scaling is prompting memory manufacturers to investigate alternative approaches to
 maintain progress in bit density, performance, and cost efficiency.Among these, 3D DRAM is emerging as a leading candidate, currently in the pathfinding stage. Itis
 widely regarded as the most promising long-term solution for achieving high-density DRAM architectures in the coming decade. Initialcommercial deployment of 3D
 DRAM isanticipated around 2033–2034, with revenue growth expected to accelerate significantly inthe latterhalf ofthe 2030s.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 15
 2025-04-08 01:51

## 第 16 页

NEXT-GENERATION DRAM – PLAYER DYNAMICS
HBM leaders intensify the race, while China steadily progresses in AI and advanced memory technologies


• The global battle for HBM leadership has accelerated sharply, driven by the explosive demand for AI computing. This reflects the strategic importance ofmemory bandwidth
 and energy efficiency for AI.
 • SK hynix currently leads the market. The company began mass production of 12Hi HBM3E inSeptember 2024 and has already started sampling 12Hi HBM4 (36GB) to
 customers as of March 2025, with mass production expected in2H 2025. A notable collaboration with TSMC, announced inApril 2024, ishelping SK hynix strengthen
 itsposition in both advanced packaging and next-generation HBM technologies. This momentum culminated in a record quarterly operating profit of $5.6B in Q4-
 2024, overtaking Samsung forthe firsttime.
 • Samsung, traditionally a dominant memory player, has fallen behind in the HBM segment and isnow pushing hard to catch up. After facing yield and thermal
 challenges with itsdesign for HBM3E, the company is now refining itsDRAM design and working on 4nm logic dies forHBM4. Trialproduction has begun, with
 sample shipments expected in2025. Internally,Samsung restructured its HBM operations in July 2024, forming a dedicated team to enhance itscompetitiveness
 across HBM3, HBM3E, and HBM4.
 • Micron, having skipped HBM3, entered the race with HBM3E in 2024. Itbegan mass production of 8Hi and 12Hi HBM3E in 2024, with integration into Nvidia’s H200
 GPUs. However, Micron’s current production capacity islimited – less than 20% of that of SK hynix and Samsung combined – but is scaling up rapidly, targeting
 60,000 units/month by the end of 2025. Mass production ofHBM4 isplanned for2026, with HBM4E to follow.
• China, which consumed over 25% of global DRAM in 2024, isaccelerating effortsto localize memory production amid tightening U.S.sanctions.
 • Changxin Memory Technologies (CXMT), the country’s leading DRAM maker, skipped its G2 node and ramped up G3 (~18.5nm) production in 2024, significantly
 boosting DDR4 shipments and contributing to price decreases. In December 2024, KingBank and Gloway launched the firstdomestic DDR5 memory modules using
 CXMT G4 DRAM chips (16nm process), marking a supply chain milestone forChina.
 • In response to U.S.restrictions on AIchips and HBM, Chinese companies have launched large-scale investments to build domestic alternatives. Huawei isreportedly
 leading a consortium – including XMC, SJSemi, TFME, and JCET –to establish HBM capabilities.Meanwhile, CXMT is sampling HBM2 and actively developing HBM2E,
 supported by a $2.4B investment in advanced packaging. Despite the technological gap with industry leaders (~6 years), Chinese players can leverage strong
 domestic demand for locally developed AI accelerators, supported by significant government backing and a well-established industry network. These factors are
 expected to help them gain a foothold inthe HBM market in the coming years.
 • China is increasingly focusing itsR&D on (1)advanced packaging for DRAM-logic integration and (2)alternative scaling approaches beyond traditional lithography,
 including 4F² cells,CBA-DRAM, and 3D DRAM. These innovations allow Chinese players to develop high-performance AI chips without relying on restricted
 technologies likeEUV lithography.
• With 2D DRAM scaling expected to reach itslimit by 2033–2034, the industry is preparing for a shift to 3D DRAM architectures. This transition will ease dependence on
 advanced lithography and drive demand for deposition (ALD, CVD), HAR etching, and bonding tools – creating new opportunities, particularly forplayers without access to
 EUV, likeChina. Though stillinearly R&D, 3D DRAM has the potential to reshape industry dynamics and offera pathway for latecomers toclose the gap.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 16
 2025-04-08 01:51

## 第 17 页

NEXT-GENERATION DRAM – OVERVIEW BY TECHNOLOGY
As scaling challenges grow, new designs, CMOS bonding, and 3D architectures are redefining DRAM development


 • Despite increasing scaling challenges, planar DRAM isexpected to continue evolving through the 0c/0d nodes (2033–2034), leveraging a combination of architectural
 and process innovations. The industry is currently reliant on the 6F² DRAM cell structure, which dominates allcommercial products as of 2025. However, further
 miniaturization willeventually necessitate a transition to 4F² cellsbased on verticaltransistors (VT), integrated within a CMOS Bonded Array (CBA) architecture.
 • CBA enables higher bit density by separating the periphery circuit and memory array onto different wafers, which are subsequently bonded. This transition, expected
 around the 0a node (~2029), isanticipated to deliver up to a 30% increase inbit density. Despite the technical complexity and cost, CBA paves the way for the use of
 advanced logic(e.g.,FinFETs) for improved performance and reliabilityand is seen as acrucial step inthe DRAM roadmap and a precursor to full3D DRAM.

 • While 4F²+CBA offers significant advantages indensity and logic integration, cost and yield challenges may continue to pose major obstacles. Under these conditions,
 DRAM manufacturers are likely to extend 6F² scaling as faras economically viable, supported by broader adoption of EUV lithography – including High-NA EUV – to
 maintain density and performance scaling. According to our current model, starting in 2029, the top three DRAM suppliers are expected to implement a mixed-fab
 strategy, producing both 6F² and 4F²+CBA DRAM to address diverse performance and cost segments. Beyond 2030, CBA integration is anticipated to become a
 standard requirement – even for6F² architectures – to sustain the industry’s long-term scaling trajectory.

 • CMOS bonding is becoming a cornerstone technology for next-generation DRAM, particularly with CBA integration. Due to sub-200nm alignment and pitch
 constraints, fusion bonding is expected to be the preferred technique for wafer-to-wafer (W2W) stacking in DRAM starting from the 0a node. This bonding approach,
 although more costly than hybrid alternatives, enables precise alignment essential for high-density DRAM.
 • Hybrid bonding is being regarded as a key enabler for future HBM generations, particularly for high-stack configurations. However, due to yield and throughput
 challenges, HBM suppliers have extended microbump-based approaches – such as fluxless TCB and advanced MR-MUF – forHBM4 and HBM4E. Hybrid bonding is
 now projected to enter the market with HBM5 (around 2029), particularly forpremium 20Hi–24Hi stacks, where gapless bonding and die thinning (down to ~20µm) are
 required to adhere to the existing JEDEC standard on total stack thickness. Note: In March 2024, JEDEC relaxed the HBM4 thickness requirements from 720µm to
 775µm, enabling the use of TSV/microbumps formanufacturing 16Hi products.
 • After the 0c/0d nodes, the transition to a 3D DRAM architecture isexpected to be inevitable. As of 2025, allmajor DRAM manufacturers –including Samsung, SK hynix,
 Micron, and CXMT – are actively exploring multiple architectural pathways to enable 3D DRAM integration. Among the leading candidates are 1T-1C cell architectures
 with horizontally oriented capacitors, as well as capacitor-less alternatives such as gain cells (2T0C) and floating-body-based 1T-DRAM designs. In parallel, leading
 semiconductor equipment suppliers – such as Applied Materials, Lam Research, and Tokyo Electron – are investing in tooling solutions to address the unique
 challenges associated with 3D DRAM manufacturing.
 • The shift to 3D DRAM is likelyto mirror the transformational leap observed in NAND flash memory and willrequire a retooling of front-end process flows. While
 lithography constraints are expected to ease –allowing relaxed nodes around 20nm and minimizing reliance on EUV –the demand for advanced deposition and etch
 solutions willdrive capital intensity. These include high-aspect-ratio (HAR) etching, advanced gap-fill processes, and atomic-layer deposition (ALD) forconformal films.
 Additionally, the implementation of selective removal techniques and precise doping strategies will be essential to realize viable 3D DRAM structures at scale.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 17
 2025-04-08 01:51

## 第 18 页

EXECUTIVE SUMMARY


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 18
 2025-04-08 01:51

## 第 19 页

DRAM MARKET OVERVIEW Note: HBM is included

 DRAM Market Revenue
 2024 DRAM Market Shares $180 100%
 Revenue ($B) YoY (%) 87%
 $135 $129 60%

 0,5% 1,3% Other 41% $97 33%
 0,6% 0,8%
 $90 $94 $80 20%
 1,1% 7%
 $67 $52
 $45 -15% -20%
 21% -35%


 41% $0 -60%
 2020 2021 2022 2023 2024 2025F
 $97B
 +87% YoY DRAM Average Selling Price
 $0,8 80%
 ASP ($/Gb) YoY (%) 61%

 $0,6 40%
 $0,49
 $0,43 16% $0,41 18%
 34% $0,4 $0,38 $0,45 0%

 -14% -16%
 $0,24
 $0,2 -42% -40%
 Note: revenues include chips and wafers, as well as memory
 modules and HBM stacks sold by IDM memory companies.
 $0,0 -80%
 2020 2021 2022 2023 2024 2025F

 huguodong@cmbchina.com Source: DRAM Market Monitor Q1-2025 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 19
 2025-04-08 01:51

## 第 20 页

DRAM MARKET FORECAST – BIT SHIPMENTS

 DRAM Bit Shipments (in Exabits) DRAM Bit Shipments – Breakdown by Technology

 100% 4% 4% 4% 5%
 750 30% 5% 3% 8% 9% 9% 10% 9% 9%
 5% 6% 7% 7% 8% 7%
 Note: HBM is included YoY Growth (%) 80%
 33% 38% 34%
 36% 41%
 38% 37% 38% 37% 36% HBM
 37%
 20% 60% GDDR
 600 LPDDR
 40%

 62% 57% 61% 56% DDR
 51% 49% 48% 46% 46% 46% 48%
 10% 20% SDR


 450 0%


 0%


 651Eb DDR Bit Shipments – Breakdown by Generation
 300
 550Eb 100%
 -10% 16% 13% 10% 8% DDR
 459Eb 18%
 80% 30%
 387Eb 40% DDR2

 336Eb 67% DDR3
 150 286Eb 60%
 254Eb -20% 95% 96% 93% 81% DDR4
 194Eb 218Eb 81% 84% 87% 88%
 192Eb 40% DDR5
 157Eb ©Yole Group March 2025 69%
 58% DDR6
 20% 31%
 0 -30% 0%


 huguodong@cmbchina.com Source: DRAM Market Monitor Q4-2024 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 20
 2025-04-08 01:51

## 第 21 页

DRAM MARKET FORECAST – BIT DEMAND BY END MARKET


 DRAM Bit Demand in Exabits (Eb) DRAM Bit Demand Growth Rates

 900
 Note: HBM is included
 (data center segment)
 751Eb
 750


 642Eb PC
 Data Center
 600 CAGR24-30 ~ 18% CAGR24-30 ~ 18% CAGR24-30 ~ 21%
 541Eb


 460Eb
 450
 385Eb

 326Eb
 300 271Eb Mobile Consumer
 222Eb CAGR24-30 ~ 10% CAGR24-30 ~ 12%
 181Eb 200Eb

 145Eb ©Yole Group March 2025
 150

 Automotive Other
 0 CAGR24-30 ~ 20%
 CAGR24-30 ~ 37%


 Source: DRAM Market Monitor Q1-2025 by Yole Group
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 21
 2025-04-08 01:51

## 第 22 页

DRAM BIT DEMAND – FOCUS ON DATA CENTERS
Generative AI and HPC are fueling DRAM growth in data centers


 • The riseof generative AI –initiated by the release of ChatGPT in November 2022 – and the continuous expansion of data-intensive AI/HPC applications in
 data centers led to a significantsurge in DRAM shipments in 2023. These trends willinduce continuous market growth throughout the next fiveyears.

 Server DRAM Bit Demand Server DRAM Bit Demand
 Breakdown by type of server (%)

 400 100%


 300 CAGR24-30 ~ 21% 75%

 71% 69% 67% 66% 64%
 76% 73%


 200 50% ©Yole Group March 2025

 CAGR24-30~17%


 100 ©Yole Group March 2025 25%

 29% 31% 33% 34% 36%
 24% 27%
 CAGR24-30~28%
 0 0%
 2024 2025 2026 2027 2028 2029 2030 2024 2025 2026 2027 2028 2029 2030

 AI servers* All other servers AI servers All other servers


 huguodong@cmbchina.com *AI server systems dedicated to computing for AI Next-Generation DRAM 2025 | Report | www.yolegroup.com 22
 2025-04-08 01:51

## 第 23 页

HIGH-BANDWIDTH MEMORY (HBM)
Product Development Overview (1/2)


 HBM generation HBM HBM2 HBM2E HBM3 HBM3E HBM4


 Flarebolt Flashbolt Icebolt Shinebolt
 Players with market products Aquabolt
 Aquabolt-XL (PIM)


 Year of first product release 2014 2018 2020 2022 - 2023 2024 2026


 Typical number of dies per stack 4Hi 4-8Hi 4-8Hi 8-12Hi 8-12Hi (16Hi)NEW 12-16Hi
 (Main packaging approach) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps)


 Max capacity per stack 1GB 4-8GB 8-16GB 16-24GB 24-36GB (48GB)NEW 36-48GB


 Die density 2Gb 8-16Gb 16Gb 16Gb 24Gb 24Gb (32Gb)*
 (Typical process) (2x) (2y, 2z) (1y, 1z)(2) (1z) (1a, 1b/1β) (1b/1β, 1c/1γ)


 Max data rate 1Gbps 2-2.4Gbps 3.2-3.6Gbps 5.6-6.4Gbps 8.0-9.8Gbps ≥ 6.4Gbps


 Effective bus width 1,024 1,024 1,024 1,024 1,024 2,048


 Max bandwidth per stack 128GB/s 205-307GB/s 460GB/s 819GB/s 1.2TB/s ≥ 2TB/s


 huguodong@cmbchina.com *Note: we expect that 32Gb dies will be adopted in HBM4 with 12Hi configurations (48GB) Next-Generation DRAM 2025 | Report | www.yolegroup.com 23
 2025-04-08 01:51

## 第 24 页

HIGH-BANDWIDTH MEMORY (HBM)
Product Development Overview (2/2)


 HBM3E 8Hi / 12Hi / 16HiNEW HBM4 12Hi / 16Hi HBM4E 12Hi / 16Hi HBM5 16Hi / 20Hi
 (Expected in 2026) (Expected in 2027-2028) (Expected in 2029)


 1a / 1b DRAM(1) 1b / 1c DRAM(1) 1c DRAM 1d DRAM


 DRAM Die Process 1b DRAM 1b DRAM 1c DRAM 1d DRAM


 1b DRAM 1b DRAM 1c DRAM 1d DRAM


 1a / 1b DRAM 4nm 4nm / 2nm ≤ 2nm
 Samsung Foundry Samsung Foundry Samsung Foundry

 Base Die Process 1b DRAM 3nm / 5mn 3nm ≤ 3nm
 TSMC TSMC TSMC

 1b DRAM 1b DRAM 3nm ≤ 3nm
 TSMC TSMC


 TC-NCF TC-NCF TC-NCF TC-NCF / HB

 Bonding MR-MUF / Adv. MR-MUF Adv. MR-MUF Adv. MR-MUF Adv. MR-MUF / HB (D2W)
 Technology(2)

 TC-NCF TC-NCF TC-NCF TC-NCF / HB (D2W)

 MR-MUF: Mass Reflow Molded Underfill NCF-TCB: Non-Conductive Film Thermo-Compression Bonding HB: Hybrid Bonding (collective die to wafer)


 Notes: (1)Reportedly,Samsung faced yieldand thermal issueswith its1bDRAM forHBM3E, prompting a shiftback tothe more stable1anode while consideringskipping 1b entirelyforHBM4.
 However, due toNvidia'spreference,Samsung has been refiningits1bdesign.(2)Startingfrom HBM4E/HBM5 (≥16Hi),wafer-to-waferhybridbonding islikelytobe adopted to stackthe firstDRAM
 layeron top ofthe base/logiclayer.Die-to-Wafer(D2W) hybrid bonding willbe used from the HBM5 generation toenable more than 20 diesper stack.

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 24
 2025-04-08 01:51

## 第 25 页

HIGH-BANDWIDTH MEMORY (HBM) FOR GPUs AND AI ASICs
Examples of products and roadmaps by GPU and AI ASIC players Non-Exhaustive List!


 Company Model Type of (x)PU Technology Content (GB) Capacity/Stack Die Density (Gb) Stack Height Number of Launch Date
 (GB) (# Dies) Stacks
 Inferentia 2 AI ASIC HBM3 32 16 16 8 2 2022-Q4
 Trainium 2 AI ASIC HBM3E 96 24 24 8 4 2024-Q4
 Inferentia 2.5 AI ASIC HBM3 32 16 16 8 2 2024-Q2
 Trainium 2.5 AI ASIC HBM3E 144 36 24 12 4 2025-Q2
 Trainium 3 AI ASIC HBM3E 144 36 24 12 4 2025-Q4
 MI200 GPU HBM2E 128 16 16 8 8 2021-Q4
 MI300 GPU HBM3 192 24 16 12 8 2023-Q4
 MI325 GPU HBM3E 288 36 24 12 8 2024-Q4
 MI355 GPU HBM3E 288 36 24 12 8 2025-Q4
 MI400 GPU HBM4 384 48 24 16 8 2026-Q1
 TPU v5e AI ASIC HBM2 16 16 16 8 1 2023-Q2
 TPU v5p AI ASIC HBM2E 96 16 16 8 6 2023-Q4
 TPU v6e AI ASIC HBM3E 32 16 16 8 2 2024-Q3
 TPU v6p AI ASIC HBM3E 192 24 24 8 8 2025-Q2
 TPU v7p AI ASIC HBM4 288 36 24 12 8 2026-Q1
 TPU v7e AI ASIC HBM4 216 36 24 12 6 2026-Q3
 Gaudi2 GPU HBM2E 96 16 16 8 6 2022-Q2
 Gaudi3 GPU HBM2E 128 16 16 8 8 2024-Q4

 Maia AI ASIC HBM3 64 16 16 8 4 2025-Q3

 A100 GPU HBM2E 80 16 16 8 5 2020-Q3
 H100 GPU HBM3 80 16 16 8 5 2022-Q4
 H200 GPU HBM3 144 24 16 12 6 2024-Q2
 B200/GB200 GPU HBM3E 192 24 24 8 8 2025-Q1
 B300/GB300 GPU HBM3E 288 36 24 12 8 2025-Q3
 GB300A GPU HBM3 144 36 24 12 4 2025-Q3
 R100 GPU HBM4 288 36 24 12 8 2026-Q1
 Dojo AI ASIC HBM2E, HBM3 160 32 16 16 5 2023-Q3

 Note: For products with launch date in 2025 and 2026 we report the expected technical characteristics.
 huguodong@cmbchina.com They may be subject to change. Next-Generation DRAM 2025 | Report | www.yolegroup.com 25
 2025-04-08 01:51

## 第 26 页

HIGH-BANDWIDTH MEMORY (HBM) – ROADMAPS (TIME TO MARKET)


 HBM2
 HBM2E

 1y, 16Gb HBM3
 4-8Hi 1z, 16Gb
 (8-16GB) 8-12Hi HBM3E
 16-24GB 1a/1b, 24Gb HBM4
 8-12Hi
 (24-36GB) HBM4E
 HBM5


 HBM2
 HBM2E

 1y, 16Gb HBM3
 4-8Hi 12Hi
 (8-16GB) 1z, 16Gb (24GB)
 8Hi (16GB) HBM3E
 1b, 24Gb 12Hi
 8Hi (24B) (36GB) HBM4
 HBM4E
 HBM5


 HBM2E*

 1z, 16Gb HBM3E
 8Hi (16GB) 1b, 24Gb 12Hi
 8Hi (24B) (36GB) HBM4
 HBM4E

 HBM5


 Before 2020 2020 2021 2022 2023 2024 2025 2026 2027 2028 2029 2030


 Note:PriortoHBM, Micronwas involvedinHybrid Memory Cubes (HMC). Thecompany startedshippingHBM2E
 in2020 and skippedthe HBM3 generationtocatch up withKorean competitors.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 26
 2025-04-08 01:51

## 第 27 页

HBM MARKET FORECAST – OVERVIEW


 8 10%
 Bit shipments (B GB)


 HBM bit shipments (B GB) 4 ©Yole Group March 2025 5%

 CAGR24-30 ~31%

 HBM share of DRAM market (%) 0,5 1,5 2,8 3,7 4,6 5,5 6,5 7,6
 - 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F
 Revenue ($B) $100 50%


 HBM revenue ($B)
 CAGR ~33% $50 ©Yole Group March 2025 25%
 24-30


 HBM share of DRAM market (%) $5 $17 $34 $46 $59 $71 $83 $98
 $- 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 Wafer Production (K WPM)
 600 30%


 HBM wafer production (KWPM)
 CAGR ~18% 300 ©Yole Group March 2025 15%
 24-30

 HBM share of DRAM market (%)
 85 216 350 410 454 494 542 590
 - 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 27
 2025-04-08 01:51

## 第 28 页

2024 HBM MARKET SHARES

 2024 DRAM Revenue Shares DRAM players are investing heavily in HBM:


 Other (incl. China) Company Investment / Activity Details Location
 0,2%
 Expansion of advanced packaging facilityin Cheonan,
 Samsung aiming to boost HBM production. The company is South Korea
 reportedly exploring additional capacity at itsCheonan
 Samsung Display plan.
 7%
 The company isexpanding itsSamsung Electronics
 Samsung Suzhou Semiconductor (SESS) plant in China tobolster China
 HBM competitiveness

 39% Construction of new TSV packaging lines at Icheon, Icheon,
 SK hynix significantlyincreasingHBM packaging capacity South Korea
 $17.4B
 +219% YoY InApril2024, SK hynix announced plans to invest $3.87B
 to build an advanced packaging facility for next-
 SK hynix generation HBM in a move expected to create around West Lafayette,
 54% 1,000jobs. The company plans to break ground on the Indiana, USA
 firstfab in March 2025, with plans for completion in
 early2027.

 The company will invest $7B in the facilityadjacent to
 itsexisting plant “through the end of the decade and
 beyond”, creating around 1,400 jobs. Micron said the
 Micron new facilitywill package itslatest HBM3E products. Singapore
 Operations are slated to begin in 2026, while
 “meaningful expansion” of the company’s total
 advanced packaging capacity willbegin in2027 to meet
 demand from AI growth.

 Note: revenues include packaged HBM stacks sold by IDM Chinese companies developed initialsample HBM chips
 memory companies to (x)PU companies. CXMT / TFME with substantialR&D investments, filingseveral patents China
 relatedto HBM packaging technologies.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 28
 2025-04-08 01:51

## 第 29 页

HIGH-BANDWIDTH MEMORY – DETAILED SUPPLY CHAIN Wafers


 DRAM
 TSV Process

 Plating Solution

 Mold
 TCB Process


 Gases
 DRAM

 Hybrid Bonding (currently in R&D) Logic IC


 Logic IC CMP Slurries and Pads


 CMP, Grinding and Dicing
 Potential new entrants for customized HBM solutions


 HBM IP Tape (Dicing/Grinding)
 Molding Process


 And more…
 Non-Exhaustive Lists!
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 29
 2025-04-08 01:51

## 第 30 页

LEADING-EDGE MEMORY – A HIGHLY CAPITAL-INTENSIVE BUSINESS


 • The rapid growth of AIand high-performance computing (HPC) isdriving a surge in memory capital expenditures (CapEx) and wafer fab equipment (WFE),
 particularly inthe DRAM business.
 • DRAM bit growth is becoming more expensive as lithography shrinks become more difficult.Multi-patterning requirements are increasing with each node
 migration, resulting in additional processing steps and, therefore, more cleanroom space per wafer out. The adoption of EUV isreplacing multi-patterning but
 requires significantinvestments inexpensive leading-edge tools.
 • DRAM suppliers – Samsung, SK hynix, and Micron – are prioritizingHBM investments, focusing on advanced lithography (including EUV), TSV fabrication,and
 advanced packaging technologies such as wafer bonding. The transition to higher-stack HBM (e.g.,12Hi,16Hi) and finer process nodes (e.g.,1b,1c) further
 amplifies WFE spending, particularly infront-end wafer processing and back-end assembly.

 Memory industry CapEx (in $B) Wafer fab equipment for memory (in $B)

 $100 $50
 DRAM NAND DRAM NAND

 $80 $40


 $60 $30


 $40 $20


 $20 $10


 $- $-
 2019 2020 2021 2022 2023 2024 2025F 2019 2020 2021 2022 2023 2024 2025F


 Source: WFE, NAND and DRAM Market Monitors (Q4-2024) by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com
 huguodong@cmbchina.com 30
 2025-04-08 01:51

## 第 31 页

* *A new generation is said to start when its production
2020-2030 DRAM TECHNOLOGY ROADMAPS exceeds 10 M Gb per quarter.


 1znm
 1anm 1bnm

 1cnm
 1dnm
 0anm
 1znm
 1anm
 1bnm
 1cnm
 1dnm
 0anm
 1znm
 1αnm
 1βnm
 1γnm
 1δnm
 1ԑnm


 1xnm
 1ynm
 1z/1a nm

 2ynm eq.
 (Gen1) 1xnm eq.
 (Gen3) 1znm eq.
 (Gen4) 1anm eq.


 2znm
 1xnm


 2znm
 1xnm

 2020 2021 2022 2023 2024 2025 2026 2027 2028 2029 2030

 DRAM technology fully deployed w/ EUV DRAM technology based on CBA architecture (expected)

 huguodong@cmbchina.com Note: Samsung started manufacturing DRAM with EUV from the 1x node (test vehicle) Next-Generation DRAM 2025 | Report | www.yolegroup.com 31
 2025-04-08 01:51

## 第 32 页

DRAM MARKET FORECAST – WAFER PRODUCTION Note: HBM is included

 DRAM Wafer Production (in M WPY) Wafer Production Breakdown by Process Node


 40 20% 100% 4%
 YoY Growth (%) 6% 9%
 11% 12% ≤1dnm

 20% 22%
 27% 27%
 31% 1cnm
 34% 45%
 30 10% 75% 34%
 36% 36% 1bnm
 63%


 37% 36% 1anm

 35% 35%
 20 0% 50% 31% 1znm

 36% 26% 27%
 26%
 29 15% 1ynm
 25 27
 23 24 24% 15% 13% 11% 12%
 10 20 21 -10% 25% 11% 5% 1xnm
 18 19 6% 5% 2%
 16 16 12% 5% 4% 5% 6%
 7% 7%
 9% 11% 12% >1xnm
 24% 12% 13% 11%
 ©Yole Group March 2025 9%
 17% 15% 15% 5%
 11% 2% 2% 2%1% 2%1%
 7% 5% 4% 4% 3% 3%
 0 -20% 0%


 huguodong@cmbchina.com Source: DRAM Market Monitor Q4-2024 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 32
 2025-04-08 01:51

## 第 33 页

EXTREME ULTRAVIOLET (EUV) LITHOGRAPHY FOR DRAM MANUFACTURING
Overview of DRAM suppliers


 • Samsung, leveraging itsfoundry expertise, was the firstto adopt EUV lithography forDRAM, implementing a single EUV layerin its1z node in2020. Before
 that,Samsung had used its1x DRAM as a test vehicle forEUV integration. SK hynix followed in February 2021, completing itsfirstEUV-equipped fabrication
 lineand commencing mass production of 1aDRAM in the second half ofthe year.
 • Micron took a more cost-conscious approach, delaying EUV adoption to avoid the high depreciation costs of the equipment. Instead, the company relied on
 self-aligned multiple patterning techniques (e.g.,SAQP) through its 1βnode, achieving a bit-cellsizecomparable to itsKorean rivals.However, as process
 nodes shrink beyond 1β,maintaining process control and production stabilitywith multiple patterning becomes increasingly challenging. In February 2025,
 Micron announced the firstshipments ofDDR5 DRAM produced with its1γ node –itsfirsttoincorporate EUV lithography.
 • Looking ahead, Korean DRAM makers are exploring High-NA EUV forsub-10nm DRAM. As ofQ1 2025, SK hynix is collaborating with ASML at the High-NA
 Joint Lab at imec (Belgium) to validate process technology and stability.Meanwhile, Micron has yet to announce itsplans for High-NA EUV but islikelyto
 evaluate ASML’s pilot systems alongside itscompetitors.

 Estimated # of EUV layers EUV Lithography 0.33NA Exposure (weighted average)


 DRAM Node


 1z 1 0 0


 1a / 1α 3-5 1 0
 15-24% EUV spend CAGR
 1b / 1β 5-6 3-4 0


 1c / 1γ 6-7 5-6 1

 Source: ASML

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 33
 2025-04-08 01:51

## 第 34 页

LONG-TERM DRAM TECHNOLOGY ROADMAP

 2 2 < 4F2
 6F 4F
 2D 3D
 Vertical Transistors


 1c(𝛾) Multiple possibilities under investigation

 • 1T-1C DRAM with horizontal capacitors

 • 2T-0C DRAM (e.g.,IGZO)

 1d(𝜕) CMOS Bonding
 More EUV • 1T DRAM with 3D flash architecture
 1ε (PeriWafer + Array Wafer) (e.g., floating body, charge trap, ferroelectric layers)


 0a
 0b
 0c
 Bit area ~10×10-4 µm2 0d

 High-NA EUV Image credits: Applied Materials


 2025 2026 2027 2028 2029 2030 2031 2032 2033 2034 2035 2036


 Our modelprojectsthatstartingin2029,thetopthreememorymanufacturerswillproduce
 huguodong@cmbchina.com amixof6F²and4F²+CBADRAMproducts,eachtailoredforspecificendmarkets. Next-Generation DRAM 2025 | Report | www.yolegroup.com 34
 2025-04-08 01:51

## 第 35 页

DRAM MARKET FORECAST – WAFER PRODUCTION
Conventional vs. CMOS-Bonded Array (CBA) DRAM architecture


 • Compared tothe previous edition ofthis report,the ramp- DRAM wafer production (M WPY)
 up of CBA DRAM has been delayed by approximately 2
 years.During the most recent interview campaign, we 30,0
 became aware that the top memory makers will
 implement their 0d node with “conventional” 6F2
 technology.
 • Starting from the 0a node (>2028), some DRAM makers 25,0
 are now expected to shift to 4F2+CBA for premium
 memory products to enable higher density and better
 performance through advanced CMOS logiccircuitsinthe
 periwafers. 20,0
 • Due tostringent pitch and alignment requirements, CBA
 DRAM is expected to be implemented using fusion
 bonding, which involves three wafers – one of which is 15,0
 sacrificial.Thisapproach islikelyto have a greater cost
 impact compared to hybrid bonding.

 • Our current model assumes thatin 2029 and beyond, the
 top 3 memory makers willproduce a mix of both 6F2 and 10,0
 4F2+CBA DRAM products targeting differentend markets.

 Notes

 • In the CMOS-Bonded Array (CBA) DRAM architecture,the 5,0
 periphery circuitand the memory arrayare processed on
 different wafers and then bonded together through
 wafer-to-wafer CMOS bonding.
 • Another common way to refer to CBA DRAM is “cell-on- - 2020 2021 2022 2023 2024 2025 2026 2027 2028 2029 2030
 peri” (COP). The wafer containing the array ofDRAM cells Conventional DRAM 16,1 18,0 19,5 16,2 18,7 21,2 22,9 23,7 24,8 26,0 25,6
 is stacked on top of the wafer containing the periphery
 circuitviawafer-to-wafer hybridbonding. CBA DRAM - - - - - - - - 0,0 0,6 3,0
 • In our memory market model, we count only DRAM Total 16,1 18,0 19,5 16,2 18,7 21,2 22,9 23,7 24,8 26,6 28,6
 wafers (CMOS logicwafers are not included). % of CBA 0% 0% 0% 0% 0% 0% 0% 0% 0% 2% 10%


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 35
 2025-04-08 01:51

## 第 36 页

BONDING TECHNOLOGIES FOR NEXT-GENERATION DRAM – ROADMAPS


 High Bandwidth Memory

 • Hybrid bonding willbe needed to continue improving data-transfer speed, heat dissipation, and power efficiency,as well as tominimize the HBM stack thickness.

 • Reportedly, hybrid bonding willbe firstused tostack the firstDRAM layer and the base/logic layer. Inthis case, the HBM assembly process will require a wafer-to-wafer
 (W2W) hybrid bonding step.The firsttechnologies using this approach are likelytobe HBM4E/HBM5 (≥16Hi),particularlyin customized HBM solutions.

 • Die-to-Wafer (D2W) and Die-to-Die (D2D) bonding schemes willbe used in subsequent generations. We currently model die-bonding approaches to start from the
 HBM5 generation from 20Hi (~2029).
 Planar DRAM with CMOS Bonded Array (CBA) Architecture

 • DRAM makers are expected to use fusion W2W bonding from the 0a DRAM node (~2029) to stack the DRAM array wafer and the CMOS logic wafer. More detailsin the
 “DRAM scaling:challenges and solutions” chapter of thisreport. Collective D2W
 W2W
 W2W W2W (fusion) W2W

 HBM3E HBM3E HBM3E HBM4 HBM4 HBM4E HBM5 CBA DRAM HBM5
 (8Hi) (12Hi) (16Hi) (12Hi) (16Hi) (16Hi) (16Hi) (0a) (20Hi)


 2024 2025 2026 2027 2028 2029 2030

 Mass Production Time For Market Leaders


 Technologies based on MR-MUF* or NCF- Technologies that are likely to make use of
 TCB**with TSV and microbumps hybrid (or fusion) bonding


 Image credit: Applied Materials


 huguodong@cmbchina.com *MR-MUF: Mass Reflow Molded Underfill**NCF-TCB: Non-Conductive Film Thermo-Compression BondingNext-Generation DRAM 2025 | Report | www.yolegroup.com 36
 2025-04-08 01:51

## 第 37 页

A LONG JOURNEY TO 3D DRAM… but the “peak” is on the horizon!


 • Multiple solutions willenable continuous planar DRAM • Less litho
 scaling over the next 8–9 years. • More deposition …...
 • Starting with the 0a node (~2029), some DRAM 4F2 + CBA* 3D
 manufacturers areexpected to adopt a 4F² CMOS Bonded • More etching
 Array (CBA) architecture. This approach aims to achieve Vertical Transistors 1yyL
 increased density and enhanced performance, enabling
 scaling forat leasttwo subsequent nodes. Advanced logic
 technologies, such as FinFET transistors integrated onto
 dedicated CMOS wafers,willbe instrumental insustaining • More EUV
 ongoing performance improvements after2030.
 • However, if manufacturing costs and yield challenges • FinFET peri. 1xxL

 make high-volume 4F² DRAM production economically …
 prohibitive,memory makers may extend 6F² scalingas far 0c
 as possible. This extended scaling would leverage …
 additional EUV layers and potentiallyintroduce High-NA
 EUV lithography. In the long term (post-2030), CBA 2033-2034
 technology isanticipated to become essentialto maintain
 density and performance progression. 0c
 • Overall, planar DRAM scaling is likelytopersist untilthe 0b
 0c/0d nodes. Beyond this point, the transition to a 0a
 challenging but necessary 3D architecture willbegin.
 2029 6F2 + CBA*
 0a 0b • FinFET peri.
 2D ? 1e
 2025 1d 6F2 • More EUV
 1c • High-NA EUV


 huguodong@cmbchina.com *CBA: CMOS Bonded Array Next-Generation DRAM 2025 | Report | www.yolegroup.com 37
 2025-04-08 01:51

## 第 38 页

CHINA-UNITED STATES COMMERCIAL WAR – HIGHLIGHTS
Focus on AI chips and HBM


 • Due to U.S.trade restrictions, Chinese companies are barred from accessing high-end AI accelerators from Western suppliers. Even Nvidia’s AI chips tailored for China
 – such as the A800 (40GB HBM2) and H800 (80GB HBM3) – were banned from export inOctober 2023.

 • In response, Nvidia released the H20 GPUs, designed with adjusted performance specifications to comply with U.S. regulations. These modified models enable Nvidia
 to maintain itspresence in the Chinese market while adhering to export controls.

 • Example: H20 has 96GB HBM3 memory, and the bandwidth isup to 4.0 Tb/s, allhigher than the H100, but the computing power isonly 296 TFLOPs, and the
 performance density isfarinferior to the H100.
 • In December 2024, the U.S. government implemented new export controls restricting the sale of HBM chips to China without special authorization. These memory
 components are crucial for AI applications, and the restrictions aim to limit China's access to technologies that could enhance itsAI and military capabilities.
 Additionally, the U.S. Department of Commerce added ~140 Chinese entities toits trade blacklist,further tightening controls over China's semiconductor industry.
 • In early 2025, as the Chinese AI firm DeepSeek emerged as a major competitor in the AI landscape, Tencent, Alibaba, and ByteDance significantly increased their
 orders for Nvidia’s H20 GPUs. Meanwhile, the Trump administration has been discussing the possibility of expanding export controls to include the H20, given its
 capability to develop and power major AI applications. (Note: As ofMarch 2025, Nvidia isstillpermitted to ship the H20 to China.)
 • The Chinese government encourages local cloud service providers (CSPs) to procure at least20% of their AI hardware from domestic (x)PU or AIASIC manufacturers to
 support the development of China's semiconductor industry. However, due to domestic hardware and software limitations –including a lack of CUDA support and
 inferior performance in key computational tasks – Chinese CSPs continue to favor Nvidia’s GPUs, particularly the H20 model. Amid escalating U.S. restrictions on GPU
 exports, CSPs are actively stockpiling as many Nvidia GPUs as they can source to maintain competitiveness and efficiency.
 • Huawei’s AI ASICs (Ascend chips) are widely recognized as China's foremost alternative to Nvidia's hardware. While there are reports suggesting that DeepSeek R1
 utilizes Huawei's latest Ascend 910C chips for inference workloads, these accelerators are predominantly deployed by Chinese government agencies, state-owned
 enterprises, and entities engaged in national security sectors.
 • Initiallylaunched in 2019, the original Ascend 910 integrated HBM2E stacks sourced from global suppliers, a technology retained in subsequent iterations,
 including the Ascend 910B and 910C.

 • Researchers from DeepSeek indicate that the Ascend 910C chip achieves approximately 60% of the inference performance of Nvidia’s H100 GPU.
 • Market speculation suggests that Huawei may be indirectly accessing TSMC’s advanced foundry services through other Chinese semiconductor
 intermediaries to manufacture itscutting-edge Ascend chips. In response to these developments, the U.S. Department of Commerce reportedly issued a
 directive to TSMC, mandating the cessation of supplies ofAI chips manufactured atthe 7nm process node or below to customers inmainland China, effective
 November 11,2024. Notably, as of today, the Chinese foundry SMIC can provide 7nm-node manufacturing services.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 38
 2025-04-08 01:51

## 第 39 页

CHINA MEMORY BUSINESS – FOCUS ON DRAM
Summary and Outlook


 • Companies headquartered in China purchase over 25% of the DRAM products manufactured by global memory IDMs. The high level of memory consumption in
 China isfueling the country’s intense desire to produce more DRAM and NAND devices locally.However, China’s self-sufficiency in semiconductor memory is
 estimated to be below 15%.

 • U.S. trade restrictions pose a significant challenge toChina’s memory industry, which relies heavily on imported technologies. In turn,China isreacting to sanctions by
 increasing its semiconductor investments and establishing strong collaborative networks of local companies, including equipment suppliers, foundries, and OSATs
 with advanced packaging capabilities.

 • Changxin Memory Technologies (CXMT) isthe leading DRAM maker inChina. Itsfirst-generation DRAM (~27nm equivalent) isavailable domestically since 2019 (DDR4,
 LPPDDR4). After skipping itssecond-generation (G2) technology, CXMT ramped up production of G3 (~18.5nm equivalent) and significantly increased its DDR4
 shipments in 2024, triggering price declines in the DDR4 DRAM market. Looking ahead, CXMT aims to introduce an updated HKMG G4 technology (H2-2025) and
 develop 15nm DRAM technology in 2025 (G5),with commercialization targeted forthe second half of 2026. Note: In January 2025, the U.S. Department of Commerce
 tightened export restrictions on memory manufacturing equipment to China, subjecting equipment purchases for processes <25nm to additional controls. These
 restrictions could slow down CXMT’s G3 and G4 production growth, as well as itsG5 R&D.

 • Chinese companies have increasingly focused their R&D efforts on two key approaches: (1)advanced packaging techniques for DRAM-logic integration and (2)DRAM
 scaling methods beyond conventional lithography shrinks, such as 4F² cells,CBA-DRAM, and 3D DRAM. These innovations enable Chinese players to develop high-
 performance AI chips without relying on restricted leading-edge equipment likeEUV lithography. By leveraging More-than-Moore solutions that integrate logic and
 memory, China aims tostay competitive in the race for technological leadership, particularly in the criticalfieldof AI computing.

 • The U.S. curbs on AI chips and HBM have triggered significant investments and numerous initiativesfor producing such chips within China. Huawei is reportedly
 building a consortium of companies –including XMC, SJSemi, TFME, and JCET – tobuild HBM, an essential building block of AI computing systems.

 • CXMT is reportedly sampling HBM2 to customers and is currently working on HBM2E development. The company announced a CNY 17.1billion ($2.4B) investment in
 an advanced packaging plant inShanghai, aiming for a monthly capacity of 30,000 units by the second half of 2026.

 • At this stage, Chinese memory companies lag significantly behind memory leaders in technological development (~6 years).Despite their technological gap, Chinese
 players can leverage strong domestic demand forlocally developed AI accelerators, supported by significant government backing and a well-established industry
 network. These factors are expected to help them gain a foothold inthe market in the coming years.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 39
 2025-04-08 01:51

## 第 40 页

3D DRAM – BUSINESS OVERVIEW


 • 2D DRAM scaling islikely to persist until the 0c/0d nodes (2033-2034). Beyond this point, the transition to a challenging but necessary 3D
 architecture willbe necessary.

 • 3D DRAM isbeing considered by allDRAM manufacturers as a potential solution forlong-term DRAM scaling atsub-10nm nodes.
 • Top memory makers – such as Samsung, SK hynix, and Micron – willlikely invest more and more resources in the coming years, and
 we expect new solutions willbe found, no matter how complex the technical challenges are.
 • Equipment suppliers – such as Applied Materials, Tokyo Electron, and Lam Research – have also begun to develop solutions related to 3D
 DRAM. Significant R&D work has been carried out to develop suitable equipment and processes – deposition and etching – for implementing
 3D architectures, as well as new process solutions to deposit high-mobility materials through epitaxial growth, PVD, and ALD. 3D DRAM isalso
 expected torequire advanced gap-fill,selective removal, and advanced doping capabilities.
 • The transition from 2D to 3D DRAM willdrive significant changes within the industry, paralleling the evolution recently observed in NAND flash
 technology. Like the shifttoward 3D NAND, the adoption of 3D DRAM will demand substantial investments to establish and scale the new
 manufacturing processes.
 • Extensive retooling will be critical,particularly increasing expenditures for deposition systems such as Atomic Layer Deposition (ALD)
 and Plasma-Enhanced Chemical Vapor Deposition (PE-CVD), as well as high-aspect-ratio (HAR) etching equipment. Collectively,
 deposition and etching systems could account forover 70% of the total DRAM equipment investments.
 • Furthermore, 3D DRAM will leverage more “relaxed” lithography nodes around 20nm, eliminating the need for costly EUV
 lithography systems.
 • 3D DRAM could be favorable for Chinese memory companies that, at this stage, have no access to leading-edge equipment (e.g.,EUV
 lithography) due to U.S. trade restrictions.The availability of new 3D-DRAM manufacturing schemes could bring China back into the race and
 allow itto close the technology gap with global suppliers.
 • Ifthe U.S. restrictions hamper DRAM planar shrinking, then the only way for China to succeed isto build 3D structures. For this reason, multiple
 leading Chinese companies are intensely exploring the 3D pathway: both CXMT and the NAND company YMTC are active In this area (note:
 YMTC’s 3D NAND know-how and XtackingTM technology could become key enablers for Chinese 3D DRAM); Huawei is also developing 3D
 DRAM through itsdesign center in Yokohama, Japan.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 40
 2025-04-08 01:51

## 第 41 页

MARKET FORECASTS


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 41
 2025-04-08 01:51

## 第 42 页

DRAM Market Overview


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 42
 2025-04-08 01:51

## 第 43 页

MEMORY MARKET OVERVIEW


 2024 Memory Market – Breakdown by Technology Memory Market Evolution (2020 – 2024)


 (NV)SRAM / FRAM Emerging NVM $200B 100%
 0,4% 0,1% YoY (%)

 EEPROM and Other 78%
 NOR 0,6%
 1,6%

 $150B 50%


 32%

 NAND DRAM 15%
 40% $170B 57%
 $100B 0%
 +78% YoY $97B
 (incl. HBM) -14%


 -34%

 HBM $50B -50%
 10%

 ©Yole Group March 2025

 $17,4B
 $5,4B HBM
 DRAM NAND NOR $0B -100%
 (NV)SRAM / FRAM Emerging NVM EEPROM and Other 2020 2021 2022 2023 2024


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 43
 2025-04-08 01:51

## 第 44 页

DRAM MARKET OVERVIEW Note: HBM is included

 DRAM Market Revenue
 2024 DRAM Market Shares $180 100%
 Revenue ($B) YoY (%) 87%
 $135 $129 60%

 0,5% 1,3% Other 41% $97 33%
 0,6% 0,8%
 $90 $94 $80 20%
 1,1% 7%
 $67 $52
 $45 -15% -20%
 21% -35%


 41% $0 -60%
 2020 2021 2022 2023 2024 2025F
 $97B
 +87% YoY DRAM Average Selling Price
 $0,8 80%
 ASP ($/Gb) YoY (%) 61%

 $0,6 40%
 $0,49
 $0,43 16% $0,41 18%
 34% $0,4 $0,38 $0,45 0%

 -14% -16%
 $0,24
 $0,2 -42% -40%
 Note: revenues include chips and wafers, as well as memory
 modules and HBM stacks sold by IDM memory companies.
 $0,0 -80%
 2020 2021 2022 2023 2024 2025F

 huguodong@cmbchina.com Source: DRAM Market Monitor Q1-2025 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 44
 2025-04-08 01:51

## 第 45 页

DRAM MARKET SHARES BY APPLICATION

 2024 DRAM Market – Breakdown by Application 2024 DRAM Market Shares by Revenue


 100% 5%
 6% 8%
 2% 1% 14%
 22% 14%
 4% 21%
 80% 33% 4% 2% 20%
 21%
 PC 4% 11%
 52% 14% 3%

 Datacenter 60% 36% 7% 36%
 20% 20% 34%
 Mobile 35% 22%
 $97B 19% 8%

 Graphics +87% YoY 40%
 35% 13%

 Consumer

 20% 42% 42% 42% 37% 41% 41%
 Auto 34%
 27% 30%

 Other

 0%


 Note: revenues include chips and wafers, as well as memory
 modules and HBM stacks sold by IDM memory companies.

 Samsung SK hynix Micron Nanya Winbond Powerchip CXMT Other


 huguodong@cmbchina.com Source: DRAM Market Monitor Q1-2025by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 45
 2025-04-08 01:51

## 第 46 页

DRAM MARKET FORECAST – BIT DEMAND BY END MARKET


 DRAM Bit Demand in Exabits (Eb) DRAM Bit Demand Growth Rates

 900


 751Eb
 750


 642Eb PC
 Data Center
 600 CAGR24-30 ~ 18% CAGR24-30 ~ 18% CAGR24-30~ 21%
 541Eb


 460Eb
 450
 385Eb

 326Eb
 300 271Eb Mobile Consumer
 222Eb CAGR24-30 ~ 10% CAGR24-30 ~ 12%
 181Eb 200Eb

 145Eb ©Yole Group March 2025
 150

 Automotive Other
 0 CAGR24-30 ~ 20%
 CAGR24-30 ~ 37%


 Source: DRAM Market Monitor Q1-2025 by Yole Group
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 46
 2025-04-08 01:51

## 第 47 页

DRAM MARKET FORECAST – REVENUE AND AVERAGE SELLING PRICE

 DRAM Market Revenue (in $B) DRAM ASP in $/Gb


 $240 100% $0,6 100%
 Note: HBM is included YoY Growth (%) Note: HBM is included YoY Growth (%)


 $200
 60%
 $0,5 50%

 $160

 20%


 $120 $0,3 0%


 $194 -20% $0,49
 $173 $0,43 $0,45
 $80 $0,41 $0,38 $0,40
 $133 $144
 $129 $130 $0,34 $0,31 $0,31
 $0,2 $0,30 -50%
 $94 $97 -60% $0,24
 $40 $80
 $67
 $52 ©Yole Group March 2025
 ©Yole Group March 2025


 $- -100% $- -100%


 huguodong@cmbchina.com Source: DRAM Market Monitor Q4-2024 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 47
 2025-04-08 01:51

## 第 48 页

DRAM MARKET FORECAST – BIT SHIPMENTS

 DRAM Bit Shipments (in Exabits) DRAM Bit Shipments – Breakdown by Technology

 100% 4% 4% 4% 5%
 750 30% 5% 3% 8% 9% 9% 10% 9% 9%
 5% 6% 7% 7% 8% 7%
 Note: HBM is included YoY Growth (%) 80%
 33% 38% 34%
 36% 41%
 38% 37% 38% 37% 36% HBM
 37%
 20% 60% GDDR
 600 LPDDR
 40%

 62% 57% 61% 56% DDR
 51% 49% 48% 46% 46% 46% 48%
 10% 20% SDR


 450 0%


 0%


 651Eb DDR Bit Shipments – Breakdown by Generation
 300
 550Eb 100%
 -10% 16% 13% 10% 8% DDR
 459Eb 18%
 80% 30%
 387Eb 40% DDR2

 336Eb 67% DDR3
 150 286Eb 60%
 254Eb -20% 95% 96% 93% 81% DDR4
 194Eb 218Eb 81% 84% 87% 88%
 192Eb 40% DDR5
 157Eb ©Yole Group March 2025 69%
 58% DDR6
 20% 31%
 0 -30% 0%


 huguodong@cmbchina.com Source: DRAM Market Monitor Q4-2024 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 48
 2025-04-08 01:51

## 第 49 页

DRAM MARKET FORECAST – WAFER PRODUCTION Note: HBM is included

 DRAM Wafer Production (in M WPY) Wafer Production Breakdown by Process Node


 40 20% 100% 4%
 YoY Growth (%) 6% 9%
 11% 12% ≤1dnm

 20% 22%
 27% 27%
 31% 1cnm
 34% 45%
 30 10% 75% 34%
 36% 36% 1bnm
 63%


 37% 36% 1anm

 35% 35%
 20 0% 50% 31% 1znm

 36% 26% 27%
 26%
 29 15% 1ynm
 25 27
 23 24 24% 15% 13% 11% 12%
 10 20 21 -10% 25% 11% 5% 1xnm
 18 19 6% 5% 2%
 16 16 12% 5% 4% 5% 6%
 7% 7%
 9% 11% 12% >1xnm
 24% 12% 13% 11%
 ©Yole Group March 2025 9%
 17% 15% 15% 5%
 11% 2% 2% 2%1% 2%1%
 7% 5% 4% 4% 3% 3%
 0 -20% 0%


 huguodong@cmbchina.com Source: DRAM Market Monitor Q4-2024 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 49
 2025-04-08 01:51

## 第 50 页

DRAM MARKET FORECAST – WAFER PRODUCTION
Conventional vs. CMOS-Bonded Array (CBA) DRAM architecture


 • Compared tothe previous edition ofthis report,the ramp- DRAM wafer production (M WPY)
 up of CBA DRAM has been delayed by approximately 2
 years.During the most recent interview campaign, we 30,0
 became aware that the top memory makers will
 implement their 0d node with “conventional” 6F2
 technology.
 • Starting from the 0a node (>2028), some DRAM makers 25,0
 are now expected to shift to 4F2+CBA for premium
 memory products to enable higher density and better
 performance through advanced CMOS logiccircuitsinthe
 periwafers. 20,0
 • Due tostringent pitch and alignment requirements, CBA
 DRAM is expected to be implemented using fusion
 bonding, which involves three wafers – one of which is 15,0
 sacrificial.Thisapproach islikelyto have a greater cost
 impact compared to hybrid bonding.

 • Our current model assumes thatin 2029 and beyond, the
 top 3 memory makers willproduce a mix of both 6F2 and 10,0
 4F2+CBA DRAM products targeting differentend markets.

 Notes

 • In the CMOS-Bonded Array (CBA) DRAM architecture,the 5,0
 periphery circuitand the memory arrayare processed on
 different wafers and then bonded together through
 wafer-to-wafer CMOS bonding.
 • Another common way to refer to CBA DRAM is “cell-on- - 2020 2021 2022 2023 2024 2025 2026 2027 2028 2029 2030
 peri” (COP). The wafer containing the array ofDRAM cells Conventional DRAM 16,1 18,0 19,5 16,2 18,7 21,2 22,9 23,7 24,8 26,0 25,6
 is stacked on top of the wafer containing the periphery
 circuitviawafer-to-wafer hybridbonding. CBA DRAM - - - - - - - - 0,0 0,6 3,0
 • In our memory market model, we count only DRAM Total 16,1 18,0 19,5 16,2 18,7 21,2 22,9 23,7 24,8 26,6 28,6
 wafers (CMOS logicwafers are not included). % of CBA 0% 0% 0% 0% 0% 0% 0% 0% 0% 2% 10%


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 50
 2025-04-08 01:51

## 第 51 页

HBM Market Forecast


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 51
 2025-04-08 01:51

## 第 52 页

HBM MARKET FORECAST – OVERVIEW


 8 10%
 Bit shipments (B GB)


 HBM bit shipments (B GB) 4 ©Yole Group March 2025 5%

 CAGR24-30 ~31%

 HBM share of DRAM market (%) 0,5 1,5 2,8 3,7 4,6 5,5 6,5 7,6
 - 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F
 Revenue ($B) $100 50%


 HBM revenue ($B)
 CAGR ~33% $50 ©Yole Group March 2025 25%
 24-30


 HBM share of DRAM market (%) $5 $17 $34 $46 $59 $71 $83 $98
 $- 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 Wafer Production (K WPM)
 600 30%


 HBM wafer production (KWPM)
 CAGR ~18% 300 ©Yole Group March 2025 15%
 24-30

 HBM share of DRAM market (%)
 85 216 350 410 454 494 542 590
 - 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 52
 2025-04-08 01:51

## 第 53 页

HBM MARKET FORECAST – OVERVIEW
HBM share of the total DRAM market

 Bit-shipments share (%)

 100%

 HBM

 Other DRAM 50%


 1% 1% 2% 5% 8% 9% 9% 10% 9% 9%
 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 Revenue share (%)

 100%

 HBM

 Other DRAM 50%


 1% 2% 10% 18% 26% 35% 45% 49% 48% 50%
 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 Wafer share (%)

 100%

 HBM
 50%
 Other DRAM

 2% 2% 6% 14% 20% 22% 23% 24% 24% 25%
 0%
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 53
 2025-04-08 01:51

## 第 54 页

MEMORY PLAYERS 2024 HBM MARKET SHARES


 Bit Shipments Shares (%) Revenue Shares (%) Wafer Production Shares (%)


 0,2% 0,2% 0,3%
 7% 7% 6%


 40% 39% 41%
 1.49 B GB $17.4B 216 KWPM
 +193% YoY +219% YoY +155% YoY


 54% 54% 53%


 Samsung SK hynix Micron Other (incl. China)


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com54
 2025-04-08 01:51

## 第 55 页

HBM BIT SHIPMENTS FORECAST

 HBM bit shipments by generation (M GB*)

 8 000


 7 000


 6 000

 The generative AI 5000
 market wave –
 initiated by the
release of ChatGPT 4 000
in November 2022 –
 led to an 3000
 impressive YoY ©Yole Group March 2025
 surge in HBM bit
shipments in 2023 2000
 (+187%) and 2024
 (+193%). The HBM 1000
 bit growth is
 expected to
 continue in the 0 CAGR
 next 5 years, with 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30
 CAGR24-30~31%. HBM5 (and beyond) - - - - - - - - 288 1033 3552
 HBM4E - - - - - - - 894 2565 3 701 3287
 HBM4 - - - - - 167 1889 2860 2254 1421 605
 HBM3E - - - - 283 1782 1259 477 219 194 76 -20%
 HBM3 - - 8 243 922 533 254 152 48 45 38 -41%
 HBM2E 4 50 94 186 197 228 244 161 73 65 -
 HBM2 97 80 75 79 87 74 57 51 51 - -
 Total 101 130 177 508 1489 2784 3703 4 596 5497 6458 7556 31%
 YoY (%) 26% 29% 36% 187% 193% 87% 33% 24% 20% 18% 17%


 huguodong@cmbchina.com *Note: 1GB = 8Gb Next-Generation DRAM 2025 | Report | www.yolegroup.com 55
 2025-04-08 01:51

## 第 56 页

HBM REVENUE FORECAST

 HBM revenue by generation ($B)

 $100


 $80


 $60
 HBM will outgrow
 the overall DRAM
 market. Revenues
are expected to grow $40 ©Yole Group March 2025
from ~$17B in 2024 to
 ~$98B in 2030,
corresponding to 18%
 and 50% – $20
 respectively – of the
 overall DRAM
 revenue.
 $0 CAGR
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30

 HBM5 (and beyond) $- $- $- $- $- $- $- $- $4,0 $14,1 $47,6
 HBM4E $- $- $- $- $- $- $- $12,0 $33,9 $48,5 $42,0
 HBM4 $- $- $- $- $- $2,2 $24,7 $36,8 $28,3 $17,4 $7,2
 HBM3E $- $- $- $- $3,6 $22,5 $15,7 $5,8 $2,6 $2,2 $0,9 -21%
 HBM3 $- $- $0,1 $2,7 $10,9 $6,2 $2,9 $1,7 $0,5 $0,5 $0,4 -42%
 HBM2E $0,0 $0,5 $1,0 $1,9 $2,1 $2,4 $2,6 $1,7 $0,8 $0,7 $-
 HBM2 $1,0 $0,8 $0,7 $0,8 $0,8 $0,7 $0,6 $0,5 $0,5 $- $-
 Total $1,0 $1,3 $1,8 $5,4 $17,4 $34,1 $46,4 $58,5 $70,6 $83,4 $98,1 33%
 YoY (%) 26% 30% 37% 201% 219% 96% 36% 26% 21% 18% 18%


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 56
 2025-04-08 01:51

## 第 57 页

HBM WAFER PRODUCTION FORECAST
 12'' DRAM wafer-start volume by generation (K WPM)

 600


 500


 During the 2022- 400
 2023 DRAM
 downturn, HBM
 suppliers
 increased their 300 ©Yole Group March 2025
 HBM production
 by shifting their
capacity from low- 200
 profitability
products to HBM.
 The HBM 100
production ramp-
up is expected to
 continue in the
 coming years to 0 CAGR
 meet the rising 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30
 demand from AI HBM5 (and beyond) - - - - - - - - 22 77 261
 chip suppliers. HBM4E - - - - - - - 75 211 299 261
 HBM4 - - - - - 16 182 271 209 129 54
 HBM3E - - - - 34 207 142 52 23 20 8 -21%
 HBM3 - - 1 35 130 73 34 20 6 6 5 -42%
 HBM2E 1 9 17 32 33 37 40 26 12 10 -
 HBM2 22 18 16 17 19 16 12 11 11 - -
 Total 23 27 34 85 216 350 410 454 494 542 590 18%
 YoY (%) 20% 17% 27% 146% 155% 62% 17% 11% 9% 10% 9%

 *Note: our model does not take into account R&D and test wafers.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 57
 2025-04-08 01:51

## 第 58 页

HBM PACKAGE VOLUME FORECAST (1/2)

 HBM package* volume by generation (Munits)

 150


 120


The total volume
of HBM packages 90 ©Yole Group March 2025
 will reach more
 than 110 million
 units in 2026. 60
 Thereafter, the
 total package
 volume is
 expected to 30

 remain stable
 because of the
 fast-growing 0 CAGR
average capacity 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30
 per package HBM5 (and beyond) - - - - - - - - 4,2 14,7 48,3
 (GB/pkg). HBM4E - - - - - - - 16,6 44,2 60,6 52,4
 HBM4 - - - - - 4,1 43,4 62,4 47,9 29,8 12,6
 HBM3E - - - - 9,4 54,4 36,4 13,5 6,1 5,4 2,1 -22%
 HBM3 - - 0,4 11,6 40,9 22,8 10,7 6,3 2,0 1,9 1,6 -42%
 HBM2E 0,3 3,5 6,1 11,8 12,4 14,3 15,2 10,1 4,6 4,0 -
 HBM2 12,7 10,2 9,5 9,9 10,9 9,3 7,1 6,4 6,4 - -
 Total 13,0 13,7 16,0 33,3 73,6 104,8 113,0 115,3 115,4 116,4 116,9 8%
 YoY (%) 15% 5% 17% 108% 121% 42% 8% 2% 0% 1% 0%


 huguodong@cmbchina.com * 1 pkg = 1 stack of logic and DRAM dies Next-Generation DRAM 2025 | Report | www.yolegroup.com 58
 2025-04-08 01:51

## 第 59 页

HBM PACKAGE VOLUME FORECAST (2/2)

 HBM package* volume by stack height (Munits) Breakdown by stack height (%)

 120 100%
 5%
 6
 6 20% 22%
 25%
 29 32%
 37 37%
 90 75% 52%

 61% 62%

 72
 - 64 70%
 75%
 79 87 48%
 60 50% 99%

 38
 79 80% 52% 68%
 60


 62% 33%
 ©Yole Group March 2025
 30 7 25% 30% 27%
 31 31
 24
 16 21 31% 18%
 - 19 10% 17%
 3 6 11
 5 ©Yole Group March 2025 15% 4%
 13 11 10 10 11 9 9 9% 6% 7%
 7 6 6 4%
 0 - 0%


 4Hi 8Hi 12Hi 16Hi 20Hi

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 59
 2025-04-08 01:51

## 第 60 页

HBM MARKET BREAKDOWN BY GENERATION (1/2)


 Revenue breakdown (%) Bit shipments breakdown (%)

 100% 4% 100% 4% 4%
 5% 6% 6% 6% 5%

 17% 19% 19% 16%
 21% 20%


 39% 38%
 49% 75% 48% 51% 47%
 75% 50% 53%
 48% 47%
 54% 53%


 64%
 66%
 ©Yole Group March 2025 ©Yole Group March 2025 57%
 58%
 50% 50% 96% 62% 62%
 96% 63% 63%


 37% 34%
 36% 62% 44%
 61% 34% 43% 41%
 25% 40% 25%
 43% 19%
 41%
 18% 22%
 21% 13% 7% 10%
 12% 6% 10% 16%
 8% 7% 3% 4% 8%
 14% 7% 3% 7% 6% 4%
 5% 6% 3% 4% 0%
 0%


 HBM2 HBM2E HBM3 HBM3E HBM4 HBM4E HBM5 and beyond


 huguodong@cmbchina.com * 1 pkg = 1 stack of logic and DRAM dies Next-Generation DRAM 2025 | Report | www.yolegroup.com 60
 2025-04-08 01:51

## 第 61 页

HBM MARKET BREAKDOWN BY GENERATION (2/2)


 Package Volume Breakdown (%) Wafer Production Breakdown (%)

 100% 100% 3% 3% 5% 4%
 4% 4%

 13% 14% 13% 16% 16% 14%

 26%
 35% 35%
 38% 41% 42%
 38% 38% 45% 44%
 75% 75% 43%
 49%
 52%
 ©Yole Group March 2025 59%

 56% 52%
 54% ©Yole Group March 2025 55%
 60% 60%
 50% 97% 50% 97%
 35% 32%


 74% 41% 38% 35%
 45%
 22% 65% 42% 44%
 59%
 25% 9% 12% 25% 21%
 17% 26% 47%

 6% 8% 11% 24%
 30% 14% 5% 15%
 13%
 9% 11% 20% 11% 4%
 15% 5% 10% 5% 9%
 9% 6% 9% 6% 4%
 0% 0% 5%


 HBM2 HBM2E HBM3 HBM3E HBM4 HBM4E HBM5 and beyond


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 61
 2025-04-08 01:51

## 第 62 页

HBM AVERAGE SELLING PRICE (ASP) EVOLUTION

 HBM ASP per GB ($/GB)

 $15


 $14


 $13

 Although competition
among the three leading
HBM suppliers is exerting $12
 downward pressure on
 pricing, average
(blended) HBM prices are $11
projected to increase over
 the next five years.
Notably, next-generation $10
 HBM4/4E/5 devices –
 potentially featuring
 premium, customized $9
options – are expected to
be highly challenging to
 manufacture and will
 likely be positioned at $8 CAGR
 higher price points in 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30
 terms of $/GB. HBM2 $10,0 $10,0 $9,9 $9,8 $9,8 $9,8 $9,8 $9,8 $9,8

 HBM2E $10,3 $10,4 $10,4 $10,4 $10,5 $10,5 $10,5 $10,5 $10,5 $10,5
 HBM3 $11,1 $11,2 $11,8 $11,7 $11,4 $11,3 $11,1 $11,0 $10,8 -1%
 HBM3E $12,6 $12,6 $12,5 $12,2 $11,9 $11,6 $11,3 -2%
 HBM4 $13,2 $13,1 $12,9 $12,6 $12,3 $11,9
 HBM4E $13,4 $13,2 $13,1 $12,8
 HBM5 (and beyond) $13,7 $13,6 $13,4
 Blended $10,0 $10,1 $10,2 $10,7 $11,7 $12,2 $12,5 $12,7 $12,8 $12,9 $13,0 2%
 YoY (%) 0% 1% 1% 5% 9% 5% 2% 2% 1% 1% 0%


 huguodong@cmbchina.com *Blended: Weighted average across all generations Next-Generation DRAM 2025 | Report | www.yolegroup.com 62
 2025-04-08 01:51

## 第 63 页

HBM AVERAGE SELLING PRICE (ASP) EVOLUTION * 1 pkg = 1 stack of logic and DRAM dies

 HBM ASP per package* ($/pkg)

 $1200


 $1000


 The ASP per $800
 package is
projected to grow
at a 24% CAGR24-30, $600
primarily driven by
capacity-per-stack
 growth (see next $400
 slide). Note: For
 comparison, the
 ASP per GB is $200
 expected to grow
 at CAG24-30 of 2%
(see previous slide). $- CAGR
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30

 HBM2 $77 $79 $79 $78 $78 $78 $78 $78 $78
 HBM2E $124 $147 $160 $165 $167 $167 $167 $168 $168 $168
 HBM3 $212 $236 $266 $274 $272 $271 $267 $264 $260 0%
 HBM3E $378 $414 $431 $433 $425 $416 $405 1%
 HBM4 $534 $567 $589 $592 $584 $569
 HBM4E $724 $767 $801 $802
 HBM5 (and beyond) $930 $960 $987
 Average $78 $96 $113 $164 $236 $325 $411 $507 $612 $717 $839 24%


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 63
 2025-04-08 01:51

## 第 64 页

HBM PACKAGE CAPACITY EVOLUTION * 1 pkg = 1 stack of logic and DRAM dies

 HBM average capacity per package* (GB/pkg)

 80


 70


 60

 Each new HBM 50
generation expands
 capacity by 40
increasing bit density
 (Gb/die) and stack
 height 30

(dies/package). Note:
 Capacity growth 20

 within each
generation is driven 10

 by the evolving mix
 of products with 0 CAGR
 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F 24-30
 varying capacities. HBM2 7,7 7,9 8,0 8,0 8,0 8,0 8,0 8,0 8,0

 HBM2E 12,0 14,1 15,3 15,8 15,9 16,0 16,0 16,0 16,0 16,0
 HBM3 19,0 21,0 22,5 23,4 23,8 23,9 24,0 24,0 24,0 1%
 HBM3E 30,0 32,8 34,6 35,4 35,8 35,9 36,0 3%
 HBM4 40,5 43,5 45,8 47,1 47,6 47,9
 HBM4E 54,0 58,0 61,1 62,8
 HBM5 (and beyond) 67,7 70,4 73,6
 Blended 7,8 9,5 11,1 15,3 20,2 26,6 32,8 39,9 47,6 55,5 64,6 21%
 YoY (%) 10% 22% 16% 38% 32% 31% 23% 22% 19% 17% 16%


 *Blended: Weighted average across all generations
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 64
 2025-04-08 01:51

## 第 65 页

BIT OUTPUT PER WAFER START

 Bit output per DRAM wafer start (GB/wafer)

 1400


 1200


 1000


 For each HBM 800
generation, our
model considers 600
 a combination
 of DRAM
 process nodes 400
utilized by HBM
 suppliers and 200
the evolution of
 process yields -
 during mass 2020 2021 2022 2023 2024 2025F 2026F 2027F 2028F 2029F 2030F CAGR
 24-30
 production. HBM2 360 376 385 388 390 390 390 390 390
 HBM2E 432 443 460 480 497 508 514 517 519 519
 HBM3 562 573 590 610 627 638 644 647 649 2%
 HBM3E 700 717 740 763 780 790 795 2%
 HBM4 852 863 880 900 917 928
 HBM4E 997 1011 1030 1049
 HBM5 (and beyond) 1110 1119 1132
 Average 362 399 428 500 576 664 753 843 927 993 1068 11%
 YoY (%) 5% 10% 7% 17% 15% 15% 13% 12% 10% 7% 8%


 *Note: our model does not consider R&D and test wafers.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 65
 2025-04-08 01:51

## 第 66 页

INTRODUCTION TO DRAM TECHNOLOGY & BUSINESS


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com66
 2025-04-08 01:51

## 第 67 页

Brief history of DRAM technology


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 67
 2025-04-08 01:51

## 第 68 页

DRAM TECHNOLOGY – HISTORICAL OVERVIEW


 DRAM is the workhorse working
 memory technology with almost
 60 years of history!


 Source: Samsung
 2003 R&D on 20253D DRAM


 Source: Samsung 3D Cell Structure
 1998

 First 64Mb DDR Product
 1993
 First SDRAM at JEDEC
 1990
 1Mb/4Mb DRAM 800nm Technology
 1980
 Source: Intel Evolution to stack capacitor

 Image credit:
 1970 Applied Materials

 First commercial products (1Kb) by Intel

 1966 Sources: SK hynix (IEDM 2024), Samsung and Neumonda
 DRAM patent by Robert H. Dennard


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 68
 2025-04-08 01:51

## 第 69 页

HISTORY OF DRAM TECHNOLOGY – TIMELINE (1/2)


 1960 • Invention of the DRAM cell– In the late 1960s, researchers at IBM, including Robert

 Dennard, invented the concept of the DRAM cell,which consists of a capacitor to
 store charge and a transistor to read and write data. In 1968, Dennard received the
 firstDRAM patent (US3387286A): “Field-effect transistor memory”.


 • First commercial DRAM – In 1970, Intel introduced the firstcommercial DRAM, the Intel 1103
 1970 Intel 1103 device with a capacity of 1Kb and an operating speed of 60ns. This is the First DRAM IC
 chip that replaced magnetic core memory, making Intela world leader in memory 1Kb, 60ns
 for a decade.


 • Dramatic increase in density –Over time (1970s-1980s), DRAM technology advanced DRAM Density (Mb)
 rapidly, leading to an increase in memory density. The introduction of improved
 lithography techniques and circuit designs allowed for higher-capacity chips. In 10000
 1980 1976, Dr. Koyanagi (Tohoku University) devised the stacked capacitor cell 1000
 (US4151607A), the dominant DRAM cellsince the 1-Mb generation came into being. 100 1Gb
 As density increased to 64Kb in the early 1980s, U.S. manufacturers were overtaken
 by Japanese DRAM manufacturers, which dominated during the 1980s and 1990s. 10
 1 1Mb

 • Introduction of Mb-class DRAM – In 1984, multiple Japanese companies introduced 0,1
 1Mb DRAM chips to the market, marking a significant milestone in memory 0,01
 capacity. These devices were manufactured with a 1µm/800nm process and were 1Kb
 widely used in PCs and other computing devices. In 1986, NEC and Toshiba started 0,001
 manufacturing 4Mb DRAM with an 800nm manufacturing process. 1970 1980 1990 2000 2010


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 69
 2025-04-08 01:51

## 第 70 页

HISTORY OF DRAM TECHNOLOGY – TIMELINE (2/2)


 1990 • Evolution to Synchronous DRAM (SDRAM) –In the early 1990s, SDRAM technology entered the market and progressively
 became the dominant form of memory in PCs and other systems. SDRAM synchronizes the memory’s operations with the
 computer's bus speed, resulting inimproved performance.

 • Introduction of Double Data Rate (DDR) SDRAM – in the late 1990s, DRAM companies introduced DDR SDRAM, which
 offered higher data transfer rates than traditional SDRAM. DDR SDRAM allowed for data to be transferred twice per clock
 2000 cycle, increasing overallmemory performance. The following generations – DDR2 and DDR3 –were introduced in2003 and
 2007, respectively, and provided higher speeds and reduced power consumption.

 • Introduction ofthe 6F2 cellstructure – In2007, Micron was the firstcompany to switch from an 8F2 to 6F2 cell layout at 9x
 nm node, followed by Samsung at 80 nm node and, finally,SK hynix, which adopted the 6F2 celllayout at3x nm node.

 • The rise of DDR4 SDRAM – DDR4 SDRAM was firstreleased in Q2-2014. The primary advantages of DDR4 over its
 2010 predecessors include higher module density and lower voltage requirements coupled with higher bandwidth.

 • Introduction ofHBM and 3DS DRAM – In2013, SK hynix was the firstplayer tosucceed in developing and mass-producing
 High Bandwidth Memory (HBM) with a TSV structure. In the same year, the first3DS DRAM products were developed
 targeting high-capacity memory modules.

 • Launch of 1xnm DRAM production – At the end of 2016, Samsung started mass producing 1xnm DRAM (18nm equivalent).
 2020 They were followed inQ4-2017 by SK hynix and inQ1-2018 by Micron.

 • Ramp up of 1b/1𝜷DRAM -In 2024, the three major memory players (Samsung, SK hynix,and Micron) were allshipping 1b/1𝜷
 (5th10nm-class generation) DRAM in high volume. While SK hynix and Samsung had already adopted EUV lithography for
 DRAM manufacturing, Micron would finallystartusing itfrom the 1γnode in2025.

 • R&D on 3D DRAM – 3D DRAM isbeing investigated by allmajor DRAM manufacturers as a potential solution forlong-term
 DRAM scaling and has been included in the roadmaps of major equipment suppliers. We are confident that 3D DRAM is
 set to happen, but itwillnot be within the next fiveyears.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 70
 2025-04-08 01:51

## 第 71 页

DRAM business – A historical overview


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 71
 2025-04-08 01:51

## 第 72 页

DRAM MARKET OVERVIEW
Historical evolution of DRAM revenue on a quarterly basis


 • The DRAM industry iswell-known for itspronounced cyclical nature, characterized by sharp upturns and downturns, leading to significant fluctuations in
 revenue and profitabilityforcompanies. Such cycles are an inherent feature of capital-intensive industries producing commodity products.

 Memory Cycles throughout the DRAM market history
 Memory Revenue (in $B) by Quarter


 $45 9 10

 18-20 22-23
 6Q 8Q
 Rev: -41% Rev: -57%
 $30 ASP: -60% ASP: -58%
 1 2 3 4 5 6 7 8
 80-81 85 89-90 96-98 00-03 07-09 10-12 14-15
 5Q 3Q 5Q 10Q 11Q 9Q 9Q 6Q
 Rev: -48% Rev: -72% Rev: -36% Rev: -71% Rev: -79% Rev: -67% Rev: -41% Rev: -31%
 ASP: -64% ASP: -73% ASP: -63% ASP: -94% ASP: -89% ASP: -87% ASP: -45% ASP: -60%
 $15


 ©Yole Group March 2025

 $-


 huguodong@cmbchina.com Downturn period Next-Generation DRAM 2025 | Report | www.yolegroup.com 72
 2025-04-08 01:51

## 第 73 页

DRAM BUSINESS – HISTORICAL OVERVIEW (1/2) 4Kb DRAM Market Shares in 1975


 National Semi. Other
 US Era (1970s) 3% 8%

 • In the 1970s, Intel developed the 1Kb DRAM product with the mainframe NEC
 market growing. Intel's1K DRAM became the industry standard due to itscost- 4%
 effectiveness, small size, and performance . Following Intel’ssuccess, many Intel
 other U.S. companies, such as Advanced Micro Devices (AMD), Motorola, and Mostek 46%
 Texas Instruments (TI),joined the DRAM industry. U.S. companies dominated 14%
 with almost 90% ofthe market share of4K DRAM.

 TI
 25%
 Japanese Era (Late 1970s – 1980s)

 • Japanese companies such as Hitachi, Matsushita, NEC, Toshiba, Mitsubishi, and DRAM Market Ranking in 1987
 Fujitsu challenged the DRAM dominance by U.S. companies. Japanese players
 could manufacture high-quality DRAM devices and sell them globally at very
 competitive prices. Inearly 1985, Gordon Moore decided to withdraw Intelfrom
 producing DRAM, and by the end of the 1980s, only two U.S. companies –
 Micron and Texas Instruments –remained in the DRAM market.
 • There are multiple factors behind the success of Japanese companies in the
 DRAM market, among which are strong government support, easy capital
 accessibility, solid local demand, and rapid progress in manufacturing yield.
 Note: at that time, Japanese DRAM providers were vertically integrated into
 large electronics companies, and this structure allowed Japanese DRAM
 providers to easily get funds from banks and pursue a long-run strategy. As a
 result of this, in 1987 seven of the companies among the top ten DRAM
 providers were Japanese.

 Other 7.6%


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 73
 2025-04-08 01:51

## 第 74 页

DRAM BUSINESS – HISTORICAL OVERVIEW (2/2)

 The Korean Era (1990s-present)

 • Since the mid-1980s, three Korean companies (Samsung, Hyundai, and GoldStar)*, which enjoyed a unique corporate structure
 (Chaebol), invested heavily with the help of government subsidies to enter the DRAM business. *Note: after AT&T sold its share in
 GoldStar, the latter changed its name to LG Electronics in 1995; later, in October 1999, LG Semicon merged with Hyundai
 Electronics to form hynix Semiconductor.
 • When Japan was hit by a recession in the early 1990s, these three companies gained leadership in the DRAM business. Samsung
 became the leading DRAM supplier in 1991 with a 13% share. In 1995, Samsung reached a 16% share, and the three Korean
 companies accounted for 32% of the market. Many Taiwanese companies, such as Nanya, ProMos, Powerchip, and Winbond,
 entered the market following the success of the Korean companies.
 • Since then, Samsung has retained itsnumber-one position in the DRAM market, and Korean DRAM providers together held more
 than 50% of the market in 2009. In the same year, only one Japanese company –Elpida –entered the top-10 DRAM ranking.

 1995 DRAM Market Shares 2009 DRAM Market Shares With the financial crisis in
 2008, the memory industry
 Powerchip Winbond entered a challenging
 Others Samsung ProMOS 1% 1% downturn cycle. In 2009,
 12% 16% 1% Etron Others Qimonda (Germany) was the
 Fujitsu Qimonda 1% 1% first company to go bankrupt,
 5% 5% and in 2012, Elpida was
 Mitsubishi Nanya acquired by Micron after filing
 5% NEC 5% Samsung for bankruptcy.
 12% 34% After decades of turmoil, the
 Micron Elpida current DRAM market is
 6% 14% dominated by Samsung,

 TI hynix, and Micron, which
 8% Hitachi account together for more
 11% Hynix than 95% of revenues.
 Micron 22%
 LG Semicon Toshiba Hyundai 15%
 7% 9% 9%
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 74
 2025-04-08 01:51

## 第 75 页

DRAM MARKET TRENDS – SUPPLIER CONSOLIDATION
The DRAM market has experienced major consolidation since the late 1990s

 DRAM Consolidation from 1998 to 2001
 History of Active DRAM Vendors (Excluding pure foundry players)
 (1985-2004) 1998 2001

 25 1800
 Samsung (Korea)
 1600 Micron (US)
 20 1400 Hyundai (Korea)

 1200 NEC (Japan)
 15 LG Semicon (Korea)
 1000 Infineon (Germany) Samsung (Korea)

 800 Mitsubishi (Japan) Micron (US)
 10 Hitachi (Japan) hynix (Korea)
 600 Toshiba (Japan) Infineon (Germany)

 5 400 Fujitsu (Japan) Elpida (Japan)
 200 IBM (US) Toshiba (Japan)
 Mosel -Vitelic (US) Nanya (Taiwan)
 0 0 Vanguard (Taiwan) Winbond (Taiwan)
 1985 1986 1987 1988 1989 1990 1991 1992 1993 1994 1995 1996 1997 1998 1999 2000 OKI (Japan) ProMOS (Taiwan)

 Number of active DRAM vendors Herfindahl-Hirschman Index (HHI) Nanya (Taiwan) Powerchip (Taiwan)

 Data source: Ralph Siebert, “The Impact of Horizontal Mergers on Market Structure: Evidence Matsushita (Japan) Mitsubishi (Japan)
 from the Semiconductor Industry”, 2016 Powerchip (Taiwan)
 Sanyo (Japan)
 • The HHI iscalculated by squaring the market share of each firm competing in a market and Nippon Steel (Japan)
 then summing the resulting numbers. Itcan range from close to 0 to 10,000, with lower values Winbond (Taiwan)
 indicating a less concentrated market. ProMOS (Taiwan)
 • The DRAM-market HHI increased strongly after 1998, when several M&As occurred.

 Suggested reading:“The Great Escape (PartIand PartII):How These Companies Exited the DRAM Business” –Source: Cadence Blog.

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 75
 2025-04-08 01:51

## 第 76 页

MARKET DRIVERS AND TRENDS


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com76
 2025-04-08 01:51

## 第 77 页

SEMICONDUCTOR MEMORY – DRIVERS AND MEGATRENDS
Following the 2022-2023 downturn, generative AI and HPC are driving the recovery of the memory industry


 • The memory market is criticalinmodern data-centric societies and isdriven by crucialmegatrends, among which are cloud computing, artificialintelligence(AI),
 and the Internet of Things (IoT).Driven by these megatrends, the long-term demand will result inmemory continuing to increase itsshare of the overall
 semiconductor market.
 • Increasingly demanding workloads ina host of data center applications (e.g.,cloud computing, artificialintelligence,real-timeanalytics)drive the need forfaster
 data processing and higher memory capacity and bandwidth.
 • The rise ofgenerative AI – initiatedby the release of ChatGPT inNovember 2022 – and the continuous expansion ofdata-intensive AI/HPC applications indata
 centers led toa significantsurge in bitshipments in 2023. These trends willpropel continuous market growth throughout the next fiveyears.

 Data-intensive applications Data generation trend


 Generative AI


 Courtesy of Marvell Technology Group (adapted by Yole) Source: IDC, May 2024

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 77
 2025-04-08 01:51

## 第 78 页

DRAM BIT DEMAND – FOCUS ON DATA CENTERS
AI applications are fueling DRAM growth in data centers


 • The riseof generative AI – initiatedby the release ofChatGPT inNovember 2022 – and the continuous expansion of data-intensive AI/HPC applications in
 data centers led to a significant surge in DRAM shipments in 2023. These trends willinduce continuous market growth throughout the next fiveyears.

 Server DRAM Bit Demand Server DRAM Bit Demand
 Breakdown by type of server (%)

 400 100%


 300 CAGR24-30 ~ 21% 75%

 71% 69% 67% 66% 64%
 76% 73%


 200 50% ©Yole Group March 2025

 CAGR24-30~17%


 100 ©Yole Group March 2025 25%

 29% 31% 33% 34% 36%
 24% 27%
 CAGR24-30~28%
 0 0%
 2024 2025 2026 2027 2028 2029 2030 2024 2025 2026 2027 2028 2029 2030

 AI servers* All other servers AI servers* All other servers


 huguodong@cmbchina.com *AI server systems dedicated to computing for AI Next-Generation DRAM 2025 | Report | www.yolegroup.com 78
 2025-04-08 01:51

## 第 79 页

MEMORY AND COMPUTING TECHNOLOGY LANDSCAPE
Memory is struggling to keep pace with fast-growing data generation and computing demand


 • Generative AI and high-performance computing applications require ever-increasing memory bandwidth. Inrecent years,the explosion incore count per (x)PU socket
 has further exacerbated thisneed. Despite progress in DDR speeds, the available bandwidth per core has not seen a corresponding scaling.New system-level solutions
 areneeded to overcome the so-called “memory bottleneck,” namely the performance limitationassociated with data transfer between processors and memory.
 • Continuous DRAM scaling is essential to increase the density of memory chips and reduce the cost-per-bit, enabling memory-content growth for a varietyof end
 systems spanning servers to smartphones. Although the memory content per system keeps growing, the scaling of DRAM technology has significantlyslowed down
 due to increasing manufacturing complexity.

 Compute demand is accelerating Bandwidth per core is decreasing Memory content is growing but DRAM
 scaling has slowed down
 800 120 10
 Phase 3 32Gb
 Bandwidth (GB/s) Density increase 16Gb
 # of cores ×2 every 4 years
 8Gb
 8 4Gb
 600 90
 2Gb
 1Gb
 6 512Mb
 256Mb Phase 2
 400 60 128Mb Density increase
 ×2 every 2 years
 4 64Mb

 200 30 16Mb

 2 Phase 1
 4Mb Density increase
 ×4 every 3 years
 0 0 1Mb
 0
 2007 2010 2013 2016 2019 2022 2025 1980 1985 1990 1995 2000 2005 2010 2015 2020 2025


 huguodong@cmbchina.com Sources: Intel, Micron, Yole Next-Generation DRAM 2025 | Report | www.yolegroup.com 79
 2025-04-08 01:51

## 第 80 页

APPROACHES TO OVERCOME THE MEMORY WALL – OVERVIEW


 HBM, Chiplets, Near- or In-Memory Computing

 Low latency is the
 most important
 feature.
 Mainly for
 applications
 requiring high
 bandwidth.
 Memory Computing

 Memory moves towards computing

 Computing moves towards memory or storage


 DRAM-based Computational storage
 processing in memory Data is more
 important for the
 application.
 Mainly for data-
 intensive
 applications.

 Samsung AXDIMM solution Samsung computational
 storage drive solution


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com80
 2025-04-08 01:51

## 第 81 页

WHAT IS DRIVING SEMICONDUCTOR TECHNOLOGY PROGRESS TODAY?
 A continuous improvement in performance, power, area, and cost (PPAC), as well as time-to-market


 • For decades, technology progress in the semiconductor industry was driven by simultaneous improvements in chip performance, power, area, and cost (PPAC). These
 improvements were allmade possible by 2D scaling –as outlined by Moore’s Law – as well as monolithic semiconductor integration.

 • In recent years, Moore’s Law for2D scaling has slowed down, and scaling costs have increased. Thus, chipmakers are increasingly shifting towards heterogeneous
 integration techniques based on advanced packaging to accelerate PPAC (i.e.,Power, Performance, Area-Cost) improvements and reduce the time-to-market for new
 technology generations.

 • Incomputing devices, cost-per-transistor scaling has reached a plateau. However, each new generation ofcomputing chips offershigher performance, lower power
 consumption, and a reduced footprintvia heterogeneous integration solutions.

 • DRAM manufacturers need to provide their
 customers with continuous bandwidth and
 capacity improvements to cope with demanding
 workloads, particularly from data center
 applications and generative artificialintelligence.
 There are currently various options for high-
 speed memory serving such applications, such
 asDDR5 DRAM and HBM. The latterprovides the
 highest possible bandwidth enabled by
 advanced packaging (e.g.,3D stacking) and
 heterogeneous integration.

 • Future DRAM technology will have to provide
 ever-growing speed and bitdensity. In the long
 term, conventional planar scaling of DRAM
 technology will be unable to meet such
 requirements. New approaches, materials, and
 device architectures are being explored to this
 end, among which is3D DRAM. Source: Samsung Electronics


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 81
 2025-04-08 01:51

## 第 82 页

PLAYERS AND MARKET SHARES


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com82
 2025-04-08 01:51

## 第 83 页

MEMORY BUSINESS – MAIN PLAYERS

 NAND DRAM NOR 3D XPoint

 In March 2021,
 Micron
 announced its
 intention to cease
 all 3D XPoint
 On February 24, 2025, activities. The Lehi
 Western Digital fab dedicated to
 completed the 3D XPoint
 planned separation manufacturing
 of its flash memory was sold to Texas
 business, resulting in Instruments in
 the formation of June 2021.
 SanDisk Corporation
 as an independent
 public company.

 In January 2022, SK hynix Alliance: Kioxia-WD In July 2022, Intel
 launched Solidigm announced the
 Technology to manage winding down of the
 the newly acquired Intel Optane memory
 NAND business. business.
 In March 2025, SK hynix
 finalized its acquisition of
 Intel's NAND business,
 completing a transaction
 valued at $8.844B.


 In 2018, SK hynix and Cypress In 2019,
 formed a JV company –
 SkyHigh Memory – which Cypress was
 focuses on SLC NAND. acquired by
 Infineon.


 huguodong@cmbchina.com 83
 2025-04-08 01:51 Next-Generation DRAM 2025 | Report | www.yolegroup.com

## 第 84 页

TOP MEMORY PLAYERS, BY TECHNOLOGY – SALES RANKINGS IN 2023*


 DRAM NAND NOR HDD SRAM / FRAM

 1 1


 2 4


 3 5 5


 3 2


 1


 2 (Kioxia) 3 (Toshiba)


 6 (tie)


 6 (tie)


 4


 6 7(tie) 1 (pseudo-SRAM)

 7(tie) 2


 3


 7


 4


 5


 huguodong@cmbchina.com *Note: The 2024 rankings will be released in the “Status of the Memory Industry 2025” report by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com84
 2025-04-08 01:51

## 第 85 页

MEMORY PLAYERS – INTEGRATED DEVICE MANUFACTURERS (IDMs)


 The leading
 memory
manufacturers
 are based in
Korea, the U.S.,
and Japan. The
 Chinese
 memory
 business is
growing, with
 two key
players: YMTC
 (NAND) and
CXMT (DRAM).


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com85
 2025-04-08 01:51

## 第 86 页

MEMORY PLAYERS – 2023 DRAM MARKET SHARES

 2024 DRAM Market Shares by Application
 2024 DRAM Market Shares
 100%
 6%

 0,5% 1,3% Other 22% 14%
 0,6% 0,8% 4%
 80% 33% 2% 20%
 1,1% 21% 4%


 14% 3%
 21% 52%

 60% 36% 7% 36%
 41% 20%

 35% 22%
 $97B 19% 8%
 +87% YoY 40%
 13%


 20% 42% 42% 42% 37% 41%
 34% 30%
 34%


 0%
 PC Datacenter Mobile Graphics Consumer Auto Other
 Note: revenues include chips and wafers, as well as memory
 modules and HBM devices sold by IDM memory companies. Samsung SK hynix Micron Nanya Winbond Powerchip CXMT Other


 huguodong@cmbchina.com Source: DRAM Market Monitor Q1-2025 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 86
 2025-04-08 01:51

## 第 87 页

MEMORY PLAYERS – 2024 HBM MARKET SHARES

 2024 DRAM Market Shares DRAM players are investing heavily in HBM:


 Other (incl. China) Company Investment / Activity Details Location
 0,2%
 Expansion of advanced packaging facilityinCheonan,
 Samsung aiming to boost HBM production. The company is South Korea
 reportedly exploring additional capacity at itsCheonan
 Samsung Display plant.
 7%
 The company isexpanding its Samsung Electronics
 Samsung Suzhou Semiconductor (SESS) plant in China to bolster China
 HBM competitiveness

 39% Construction of new TSV packaging linesat Icheon, Icheon,
 SK hynix significantlyincreasingHBM packaging capacity South Korea
 $17.4B
 +219% YoY InApril 2024,SK hynixannounced plans to invest$3.87B
 to build an advanced packaging facilityfor next-
 SK hynix generation HBM ina move expected tocreate around West Lafayette,
 54% 1,000 jobs.The company plans tobreak ground on the Indiana, USA
 firstfab in March 2025, with plans forcompletion in
 early2027.

 The company willinvest$7B in the facilityadjacent to
 itsexisting plant “through the end ofthe decade and
 beyond”, creating around 1,400 jobs.Micron said the
 Micron new facilitywill package itslatest HBM3E products. Singapore
 Operations are slated to begin in 2026, while
 “meaningful expansion” of the company’s total
 advanced packaging capacity willbegin in 2027 tomeet
 demand from AI growth.

 Note: revenues include packaged HBM stacks sold by IDM Chinese companies developed initialsample HBM chips
 memory companies to (x)PU companies. CXMT / TFME with substantial R&D investments, filingseveralpatents China
 related toHBM packaging technologies.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 87
 2025-04-08 01:51

## 第 88 页

M&As and noteworthy news


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 88
 2025-04-08 01:51

## 第 89 页

NOTEWORTHY NEWS 2024


 January 2024
 Micron Technology begins volume shipments of 8Hi HBM3E (24GB) to major customers. Note: Nvidia adopted Micron’s 24GB HBM3E forthe H200 Hopper GPU in 2024.
 Samsunggears up forthe development ofnext-generation DRAM by establishing a new research lab in the U.S.focusing on 3D structures for sub-10nm DRAM.
 SK hynix starts mass production of HBM3E with 36 GB 12Hi stacks, shipping to customers likeNVIDIA forH100/H200 accelerators.
 Montage Technologylaunches 4th-generation DDR5 RCD chips supporting speeds up to7200 MT/s.
 February 2024
 SK hynix signs an MOU with TSMC to co-develop HBM4 technology, targeting 2025–26. Moreover, they announced the intention to build a state-of-the-art fabrication plant inthe
 state ofIndiana as a part ofthe Biden administration's plans to be self-sufficient inmanufacturing AI chips.
 Micron Technology ships 1γ DDR5 samples designed for next-generation CPUs to ecosystem partners and select customers.
 Samsung announces that ithas developed HBM3E 12Hiwith bandwidth up 1,280 GB/s and an industry-leading capacity of 36 GB (12× 24Gb dies).
 Winbond starts mass production of specialty DRAM memory using 20nm process technology, with plans to transition to a newer 16nm process within two years.
 March 2024
 SK hynix begins volume production of HBM3E (8Hi, 24GB) and reaches fullbooking ofits2024 production of HBM3/3E, signaling strong demand.
 Samsung announces plans toship HBM3E to major clients by early 2025. Italso forms a dedicated HBM team to fast-trackHBM3E and HBM4 development.
 April 2024
 Samsung develops 10.7Gbps LPDDR5X DRAM optimized forAI applications leveraging 12nm-class (1b) process technology.
 Powertech Technology Inc. (PTI)raises 2024 capex by 50% to boost HBM packaging capacity.
 Nanya Technology begins small-scale production ofDDR5 DRAM, aiming for6400 MT/s speed with itsupcoming second DDR5 design.
 SK hynix announces plans to construct the M15X fab in Cheongju, South Korea, with an investment of approximately ₩5.3 trillion(around $4.7B). The facilityaims to bolster HBM
 production capacity, with construction expected to be completed by November 2025 and mass production commencing in the third quarter of 2026.
 CXMTraises CNY10.8 billion($1.5B)from severalinvestors, including GigaDevice, in a financing round.
 Korean media reports that Samsung has signed a 4.134 trillionWon ($3 billion)agreement with AMD to supply 12Hi HBM3E stacks.
 May 2024
 Nanya Technology begins small-scale production ofDDR5 DRAM, aiming for6400 MT/s speed with itsupcoming second DDR5 design.
 Renesas introduces Gen3 DDR5 RCD for server DIMMs and client DIMM clock drivers (CKD).
 Micron Technology launches the firstCrucial® LPCAMM2 modules based on LPDDR5X DRAM. Lenovo's ThinkPad P1 Gen 7 laptops are the firsttouse the new technology.
 Powertech Technology (PTI)raises its2024 capital expenditure by 50% (toNT$15 billion),with 60% earmarked for HBM packaging capacity. PTI invested in TSV bonding equipment,
 mold/underfill, and high-speed testers to boost itsthroughput of HBM2E/HBM3 assembly, which major memory makers outsource.
 June 2024
 Micron Technologystarts trialproduction on 1γDRAM node using EUV lithography at itsHiroshima fab.
 At Computex, Kingston unveils new Fury Impact DDR5 CAMM2 modules. MSI and Asus showcase the firstmotherboards that support the new modules.
 SK hynix sharesits latest breakthroughon 5-layer 3D DRAM at VLSI. Reportedly, Samsung is working on a16-layer technology (VS-CAT) and Micron on an 8-layer model.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 89
 2025-04-08 01:51

## 第 90 页

NOTEWORTHY NEWS 2024-2025


 July2024
 Innotron, the controlling firm of CXMT, announced that itwillinvest CNY17.1 billion($2.4B) in an advanced packaging plant in Shanghai that could be used to make HBM.
 SK hynix revealsit isreadying 32Gb DDR5 1b DRAM and plans to launch Multiplexer Combined Ranks (MCR) DIMMs for high-performance computing.
 Micron Technology begins sampling 12Hi HBM3E (36GB). To expand capacity, Micron setup a pilotHBM line inthe U.S.and considered adding HBM assembly inMalaysia.
 SK hynix commits to investing $75B in AI-related technologies, allocating 80% ofthis investment to HBM development and production.
 Samsung reveals that the ongoing development of 48GB HBM4 that isexpected to use a 4nm advanced process to produce the HBM4 logic die.
 SK hynix commits to 103 trillionwon ($74.5B) investment over fiveyears, with 80% (82 trillionwon or $60B) directed towards AI-related business areas such as HBM.
 August 2024
 PSMC unveils multi-layer “Logic+DRAM” wafer stacking technology for AI,partnering with AMD and a Japanese GPU firm.
 The U.S. Commerce Department plans to grant SK hynix up to $450M to support the establishment of an advanced packaging and R&D facilityinIndiana (US). SK hynix pledges to
 invest $3.87B inthis project, which includes a production line fornext-generation HBM chips. Mass production isexpected to begin in2028.
 Samsung begins mass production ofits12nm-class LPDDR5X in ultra-thin packages (asslim as 0.65mm) to enable on-device AI in smartphones (12/16GB).
 SK hynix completesdevelopmentof 16Gb DDR5 DRAM builtusing its1c node, the sixthgeneration ofthe 10nm process.
 September 2024
 SK hynix begins volume production of HBM3E (36 GB) with twelve verticallystacked 24Gb DRAM chips.
 October 2024
 Samsungannounces 24 Gb GDDR7 graphics DRAM, running at 40 Gbps, with mass production set for the firsthalfof 2025.
 Montage Technology starts sampling a 5th-gen RCD (RCD05), aiming forDDR5-8000+ modules.
 November 2024
 SK hynix reveals16Hi HBM3E (48GB) with ~18% higher AIperformance than the 12Hi version manufactured using advanced thermocompression bonding.
 Winbond increases wafer capacity to14k wafers/month at itsKaohsiung fab, running near fullcapacity by Q3.
 Samsung’s officialshave stated that itwillenhance itssemiconductor packaging facilitiesinSouth Chungcheong Province to increase the production ofHBM.
 December 2024
 KingBank and Gloway (China) launch firstdomestic DDR5 memory modules using CXMT DDR5 chips (16nm process), marking a supply chain milestone forChina.
 SK hynix announces“1c” DDR5 development, introducing a16 Gb chip on its1c node and planning volume production ahead of peers.
 Micron Technology secured up to $6.1B in U.S.CHIPS Act incentives to build new leading-edge DRAM fabs in New York and expand itsBoise, Idaho facility.Thisfunding jump-starts
 Micron’s plan to invest $100B over 20 years inU.S. memory manufacturing.
 Samsung’s 8Hi HBM3E memory passes Nvidia’s tests and is approved foruse in Nvidia’s AI GPUs targeting the Chinese market.
 January- March 2025
 At CES, SK hynixshowcasesHBM3E 16Hi (48GB), LPCAMM2 modules forlaptops, and Multiplexer Combined Ranks (MCR) DIMMs forservers.
 Micron Technology announces shipments of DDR5 DRAM manufactured with 1γnode – Micron’s firstnode leveraging EUV lithography combined with high-K metal gate CMOS
 technology –to ecosystem partners and select customers.
 InMarch, SK hynix begins shipping the world’s first12-layer36GB HBM4 samples to customers.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 90
 2025-04-08 01:51

## 第 91 页

SIGNIFICANT MERGERS & ACQUISITIONS


 March 2024

 • Chinese OSAT firm JCET acquired an 80% stake in SanDisk Semiconductor (Shanghai) forRMB 4.5billion ($620M)​. This gave JCET control of a localfab
 and expanded its packaging capacity formemory chips. Shortly thereafter, JCET itselfunderwent a change of control – state-owned China Resources
 Group (CRC) purchased a majority stake forRMB 11.7billion ($1.6B)​.

 June 2024

 • Japan’s state-backed fund JIC completed a takeover of JSR Corporation, a top photoresist maker for chip manufacturing, in a deal worth about $6.4B.
 The move aimed to secure domestic control and drive consolidation in critical chip materials and is expected to strengthen Japan’s semiconductor
 supply chain for lithography materials used in memory production​.
 July 2023

 • California-based Aehr Test Systems, a supplier of semiconductor test & burn-in equipment, acquired Incal Technology for $23.1M​. The deal broadens
 Aehr’s portfolio to include Incal’s ultra-high-power burn-in solutions, which are criticalfor testing AIaccelerators and HBM-equipped processors.

 November 2024

 • GigaDevice (China) acquired a 70% stake in analog chipmaker Xysemi for RMB 580 million (~$79M)​. Xysemi specializes in power management and
 analog ICs. This move allows GigaDevice tobroaden itsproduct lineup beyond memory into power/control chips, achieving synergies in itssupply chain.

 December 2024

 • Taiwan’s GlobalWafers – a major silicon wafer supplier – acquired a 10.34% minority stake in Germany’s Siltronic AG. By buying this stake, GlobalWafers
 gains partialaccess to Siltronic’s advanced wafer technology and strengthens its influence inthe 300mm wafer supply criticalfor DRAM production.
 Other M&A activity in China

 • China saw a broader semiconductorM&A boom inlate 2024, with 31 deals disclosed by year-end​. Notably, several Chinese semiconductor materials firms
 and suppliers pursued acquisitions to localize the semiconductor supply chain. For example, upstream silicon wafer manufacturers like Li-On
 Microelectronics, TCL Zhonghuan, and Grinm Semiconductor Materials each undertook M&A deals to expand wafer production or criticalraw materials
 capacity. These moves, though smaller inscale, were strategically aimed atself-sufficiency insemiconductors (wafers, chemicals) – including memory –
 amid global supply tensions.

 Ongoing Trends into 2025

 • Surging demand for AI and HBM isdriving both strategic partnerships and M&A as firms secure technology and capacity. For instance, memory makers
 are investing heavily in new fabs and packaging facilities(often with government incentives) while EDA/IP vendors continue to snap up niche players
 (e.g.,Cadence’s planned 2025 acquisition of Secure-IC in embedded security tobolster chip design IP).Overall, the DRAM/HBM supply chain is expected
 to see consolidation in materials and tooling, ensuring that manufacturers can deliver the ever-increasing performance and volume of memory that
 next-gen computing requires.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 91
 2025-04-08 01:51

## 第 92 页

DRAM TECHNOLOGY DEVELOPMENTS WORTH WATCHING (1/2)
List of relevant R&D effort presented at technical conferences in 2024


 IEEE International Memory Workshop – Seoul, May 2024

 o Applied Material and Besi provided a comprehensive overview of the challenges and progress toward a die-to-wafer hybrid bonding process for HBM.

 o Macronix presented a stacked 4F2 DRAM with circuit under array (CuA) architecture. To avoid new channel material complexities, an annealed poly-Si channel
 access transistor isimplemented with an additional auxiliary gate (AG) to minimize the GIDL leakage current. The company also introduced an enhanced 3D
 DRAM based on gate-controlled thyristors (GCTs) with vertical BitLines and horizontal Word Lines.

 o Micron Technology showed new detailsof itsferroelectric NVDRAM (32Gb) based on zirconium-doped hafnium oxide with viamaterials engineering.

 o Samsung discussed advancements in IGZO-based DRAM cell architectures, including VCT (verticalchannel transistor), VS-CAT (verticallystacked cellarray
 transistor),and 2T0C (2transistors, 0 capacitors), and recent advances in key technologies, including IGZO deposition and gate stack engineering.

 o Neo Semiconductor showed TCAD simulations on 3D X-DRAM, a novel capacitorless 3D DRAM floating body cell using a 3D NAND-like cellstructure. The new
 DRAM celluses a dual-gate, thin-body structure and a new operation mechanism that uses a back gate voltage to modulate the channel current.


 IEEE Symposium on VLSI Technology and Circuits – Honolulu,June2024

 o Micron Technology described the methodology used to enable a stackable 4F2 polysilicon thin film transistor (TFT) forits ultra-dense 32 Gb NVDRAM. Moreover,
 incollaboration with imec and ASM, Micron reported on a Replacement Metal Gate (RMG) FinFET platform forDRAM-periphery beyond the 10nm node.

 o Samsung presented several R&D works, including: (1)a-IGZO channel FET for VCT / 3D DRAM applications; (2) DRAM celltransistors with a metal dual work
 function gate (MDWG) based on an oxide/La (Lanthanum) /TiN structure; (3)2T0C IGZO gain cellsbased on one gate-around (GA) FET and one channel-around
 (CA) FET for bit-cost scalable 3D DRAM; (4) Cell to Core-Periphery Overlap (C20) architecture based on Buried Channel Array Transistors (BCATs) with a wafer
 bonding technique; (5) High-k Hafnium Zirconium Oxide (HZO) capacitors with record-low equivalent oxide thickness (EOT) of 2.4Å obtained through a low-
 damage deposition process; (6)BCAT process technology forhigh purity and low resistance cellWord Line (WL) with minimized Row Hammer bitfail.

 o SK hynix introduced 3D DRAM with verticalbit line (BL) architecture and demonstrated fullchip integration for5-layer 1T1C 3D DRAM through a novel process
 integration scheme based on Si/SiGe sacrificialmultilayers and a hybrid wafer bonding technique.


 huguodong@cmbchina.com The full list of relevant R&D papers is available in the Excel file associated with this report (“Technical Papers” tab).Next-Generation DRAM 2025 | Report | www.yolegroup.com92
 2025-04-08 01:51

## 第 93 页

DRAM TECHNOLOGY DEVELOPMENTS WORTH WATCHING (2/2)
List of relevant R&D effort presented at technical conferences in 2024-2025


 IEEE International Electron Device Meeting – San Francisco, December 2024

 o IMECAS (China) proposed and experimentally demonstrated a 4F2 vertical-channel IGZO multi-bit dual-gate (DG) 2T0C DRAM where the write and read
 transistors are integrated simultaneously by adopting a self-aligned single-step (SASS) process. In a separate paper incollaboration with Beijing Superstring,
 IMECAS demonstrated a4-layer stacked Planar Channel-All-Around (P-CAA) IGZO FET for high-density 1T1C 3D DRAM.

 o Kioxia and Nanya demonstrated a 4F2 gate-all-around (GAA) Oxide-semiconductor Channel Transistor DRAM (OCTRAM) with IGZO Vertical Channel Transistors
 (VCT). A 275Mbit OCTRAM array was fabricated with WL 54nm / BL 63nm pitches and operated successfully.

 o SK hynix presented an Accelerator-in-Memory (AiM) device and an AiM-based Large Language Model (LLM) inference acceleration system. The company also
 provided acomprehensive review of the key innovations in DRAM technology & design for sub-10nm and beyond.

 o Tsinghua University presented a complementary oxide semiconductor (OS)-based 2T0C DRAM macro with CFET peripherals. This was accomplished using top-
 gate TeOx-PFET (read transistor) and back-gate IGZO-NFET (write transistor)via an ultra-low-temperature (≤150°C) backend-of-the-line (BEOL) process.

 o TSMC and Stanford University demonstrated a Complementary Gain Cell (CGC) memory utilizingan n-type oxide semiconductor transistor (OSFET) as the write
 and a p-type OSFET as the read transistor.The CGC achieves a retention of 10,000 seconds and can mitigate WL capacitive coupling, while the n-type and p-
 type OSFETs enable multilayer monolithic 3D integrated memory.


 IEEE International Solid-State Circuits Conference

 San Francisco, February 2024

 o SK hynix showcased an extended version of HBM3 – namely HBM3E –achieving 1280GB/s bandwidth with astack density of 48GB (16Hi,24Gb/die).

 o Samsung presented its new 24Gb GDDR7 DRAM (42.5Gb/s) with low-power Write Clock (WC) distribution, Read Clock (RC) optimizations, and voltage/time
 margin-enhanced power reduction. The company also showcased a 16Gb LPDDR5-Ultra-Pro DRAM (12.7Gb/s/pin) 5th-Generation 10nm DRAM process.

 San Francisco, February 2025

 o Samsung presented a monolithic 32Gb DDR5 DRAM die achieving 8Gb/s/pin. A 10% power reduction isachieved, and a maximum of 1TB (8-stack) DIMM can be
 supported using the 3D Stacking (3DS) option. Moreover, Samsung unveiled a16Gb GDDR7 DRAM @37Gps with PAM3-optimized TRX equalization.


 huguodong@cmbchina.com The full list of relevant R&D papers is available in the Excel file associated with this report (“Technical Papers” tab).Next-Generation DRAM 2025 | Report | www.yolegroup.com93
 2025-04-08 01:51

## 第 94 页

MEMORY BUSINESS IN CHINA
– FOCUS ON DRAM


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com94
 2025-04-08 01:51

## 第 95 页

MEMORY BUSINESS IN MAINLAND CHINA – OVERVIEW
China is a key market for all leading memory suppliers


 • China is a key market for memory devices and continues to grow rapidly thanks to high demand in the mobile/wireless, automotive, and data center markets.
 • Currently, China must import most of its memory chips from foreign suppliers, leading to an enormous trade gap. This is why the Chinese government – in
 partnership with private players – has been investing billions of dollars in developing local memory manufacturing.
 • DRAM sales to China were worth around ~$25B in 2024, corresponding to around 26% of overall DRAM sales worldwide.
 • ChangXin Memory Technologies (CXMT) isthe workhorse DRAM player in China and accounted foraround ~4.5% (~8%) of the totalDRAM bit (wafer) production in
 2024. CXMT iscurrently targeting the local Chinese market in clientPC and consumer applications and aims to expand tomobile (e.g.,smartphones).

 2024 DRAM Market - Geographic Breakdown 2024 DRAM Sales - Geographic Breakdown

 $40 100%


 14% $30 75%
 Americas

 China 5%
 3% $20 50%

 Europe $97B
 in 2024 52% $10 25%
 Japan

 ROW 26% $0 0%

 Samsung SK hynix Micron Nanya Winbond PSMC CXMT


 Sales in Mainland China Sales in Other Countries
 % Sales in Mainland China


 *This geographic breakdown of memory sales is obtained considering the HQ country of the companies purchasing DRAM products.

 huguodong@cmbchina.com Source: DRAM Market Monitor Q1-2025 by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 95
 2025-04-08 01:51

## 第 96 页

MEMORY BUSINESS IN MAINLAND CHINA – KEY PLAYERS
 China has long been investing in its domestic IC industry. Ithas also lured various multinational chipmakers into building memory and foundry fabs.


 Beijing and Qingdao Beijing (RRAM) Beijing (Foundry) Beijing (NOR, NAND)
 (MRAM / SOT-MRAM) Beijing (HQ) and Jiangsu
 Xi’an (Assembly & test) Xi’an (3D NAND) Xi’an (DRAM) PCM project halted


 Dalian (3D NAND)


 Non-exhaustive! Wuxi (SLC/MLC NAND)
 Wuxi (DRAM, SLC NAND) Wuxi (FRAM)

 Wuxi (DRAM)


 Shanghai (NOR, EEPROM) Shanghai (NOR, NAND, DRAM) Shanghai (RRAM)

 Wuhan (3D NAND)


 Shanghai (MRAM) Shanghai (NOR, EEPROM) Shanghai (NOR, EEPROM)

 Wuhan (Foundry)
 Wuhan (DRAM, NAND)

 Hangzhou (MRAM) Suzhou (VC-MRAM) Suzhou Nanjing
 (AI chip, RRAM) (AI chip, RRAM)
 Fujian (DRAM)


 JV Powerchip & Hefei City Hefei (DRAM)
 (Foundry) Changxin Xinqiao
 Hefei (DRAM) Shenzhen (NOR,NAND) Shenzhen (MRAM) Hangzhou MRAM) Shanghai and Wuxi (Foundry / NOR)


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 96
 2025-04-08 01:51

## 第 97 页

CHINA MEMORY’S LANDSCAPE – FOREIGN AND LOCAL PLAYERS

 Foreign memory players - SK hynix, Samsung, and Solidigm are the major foreign chip manufacturers


 • SK hynix maintains a significant presence in China, operating three production facilities:theWuxi DRAM plant, the Dalian NAND plant (Solidigm), and a
 packaging plant in Chongqing. SK hynix’s DRAM fabs in Wuxi produced more than 170,000 wafers per month (WPM) on average in2024, accounting for
 ~38% ofitstotal DRAM production (mostly 1zand 1y).In2024, SK hynix upgraded some of the DRAM production equipment at itsWuxi plant to manufacture
 1aDRAM.

 • U.S.restrictions prevent SK hynix from upgrading its Wuxi fab with EUV scanners forsub-1z nodes. In October 2023, SK hynix received an indefinite waiver to
 ship U.S.chip equipment to itsfactories in China. More recently, inFebruary 2025, SK hynix conducted a comprehensive review of itsinternallyused Chinese
 EDA software, anticipating future U.S. restrictionson Korean companies' use of Chinese software.
 • In 2023, SK hynix initiated the liquidation of itsShanghai sales office as part ofa strategic restructuring aimed at enhancing operational efficiency. In2024,
 SK hynix further adjusted its operations by selling a 49.9% stake in itsWuxi subsidiary to a local investment firm,indicating a strategic reevaluation of its
 manufacturing footprint inChina.
 • Samsung’s NAND fabs in Xi’an (X1and X2) together produced ~206 kWPM. In 2025, Samsung isupgrading its Xi’an,China plant to a 286-layer (V9) NAND
 flashprocess to navigate the market downturn. In January, the company opted to cut NAND flashproduction, primarily at the Xi’an facility,anticipating
 further price declines. The company is also expanding its Samsung Electronics Suzhou Semiconductor (SESS) plant in China to bolster HBM’s
 competitiveness.

 • ​In2024, Micron announced a 4.3-billion-yuan (approximately $602M) investment to expand its packaging and testing plant inXi'an, China. The expansion
 includes the construction of a new production lineto enhance the facility'scapabilities,with completion anticipated in2025 and production expected to
 commence in the latter halfof that year.
 Local memory players – YMTC and CXMT – are the workhorse players for NAND and DRAM, respectively
 DRAM NAND NOR


 HQed in US


 Non-exhaustive list!
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 97
 2025-04-08 01:51

## 第 98 页

CHANGXIN MEMORY TECHNOLOGIES (CXMT)
China’s leading DRAM manufacturer


 • CXMT is the leading DRAM maker inChina. Itsfirst-generation DRAM (~27nm equivalent) has been available domestically since 2019 (DDR4, LPPDDR4). After skipping second-generation (G2)
 technology, CXMT ramped up production of G3 (~18.5nm equivalent) and significantly increased itsDDR4 shipments in 2024, triggering price declines in the DDR4 DRAM market.
 • Since late 2023, CXMT has been shipping LPDDR5 products, including 12Gb LPDDR5 dies, 6GB LPDDR5 mobile DRAM, and 12GB LPDDR5 mobile DRAM. The 12GB LPDDR5 package-on-
 package (PoP) chip marked CXMT’s firstforay into PoP assembly and has been validated by customers such as Xiaomi and Transsion. In December 2024, KingBank and Gloway (China)
 launched the firstdomestic DDR5 memory modules using CXMT DDR5 chips (16nm process), marking a supply chain milestone for China.
 • Looking ahead, CXMT aims to introduce an updated HKMG G4 technology (H2-2025) and develop 15nm DRAM technology in 2025 (G5), with commercialization targeted for the second half of
 2026. Note: In January 2025, the U.S. Department of Commerce tightened export restrictions on memory manufacturing equipment to China, subjecting purchases of equipment for
 processes <25nm to additional controls. These restrictions could slow down CXMT’s G3 and G4 production growth, as well as itsG5 R&D.
 • Changxin Xinqiao, a company founded in 2021 by the Hefei citygovernment, together with Naura, and other venture capital companies, is currently expanding DRAM manufacturing capacity
 with a second fab in Hefei. The firstphase of Fab 2 began production in early 2024 and reached fullcapacity (~50K WPM) by early 2025.
 • Xinpu Tianying, a wholly-owned subsidiary of CXMT and founded in February 2024, is constructing a new production line inTangzhen, Pudong District,Shanghai, with an investment of RMB
 13.78billion.The facility,covering 280,000 m² (with ~180,000 m² allocated for Phase I),benefits from proximity to major Chinese semiconductor equipment suppliers, including AMEC, ACM
 Research (Shanghai), Naura, Piotech, and Kingsemi. The strong local supply chain was a key factor in CXMT’s decision to establish itsnew facilityinShanghai. This site willalso focus on
 advanced packaging technologies, such as through-silicon vias(TSVs), to support HBM manufacturing.


 Production Lines Target Capacity Beginning of Mass Comments
 [KSPM] Production

 Hefei Fab 1 120 Q3-2019 Node: G 1 and G3

 Hefei Fab 2 (Changxin Xinqiao) 100 H1-2024
 Phase I 50 H1-2024 Nodes: G3 and G4

 Phase II 50 H2-2025
 Beijing Fab 100 H1-2023 DDR4,LPDDR4/5

 Phase I ~30 H1-2023
 Phase II 40 H1-2024
 Phase III 30 N.A.
 Shanghai Fab (Xinpu Tianying) N.A. H2-2026 Adv. Pkg capacity: 30 Ku/month Source: “CXMT G4 DDR5 DRAM” report by Yole Group (to be released soon)


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 98
 2025-04-08 01:51

## 第 99 页

FUJIAN JINHUA INTEGRATED CIRCUIT CO. (JHICC)


 • JHICC is a state-owned high-tech enterprise founded on February 26, 2016. The company is jointly funded by Fujian Electronics Information Group, Quanzhou
 Financial Holding Group, and Fujian Jinjiang Industrial Development Investment Group. JHICC focuses on developing 12-inch memory wafer fabrication in Jinjiang,
 Fujian, specializing in DRAM technology, manufacturing processes, and product sales.As of2024, the company employs more than 1,600 people.

 • JHICC’s small-scale trialproduction of DDR4 memory chips firstsurfaced in2021, with limited appearances of DDR4 8GB memory products in the market. Currently,
 JHICC operates at a monthly production capacity of 60,000 wafers, primarily using a 25nm process, with a small portion produced at 19nm.
 Legal Dispute with Micron Technology and Global Settlement

 • Litigation Origins (2017-2018): In2017, Micron Technology accused JHICC of stealing DRAM technology through itsTaiwanese partner UMC, initiating legal action
 in the U.S., Taiwan, and other jurisdictions. In January 2018, JHICC counterclaimed that Micron's products sold in China infringed its patents, seeking RMB 196
 million in damages. Later that year, the U.S.Department of Commerce placed JHICC on the Entity List,citing national security concerns and restricting itsaccess
 to U.S.technology.
 • Settlement Agreement (2023): On December 24, 2023, JHICC and Micron reached a global settlement, withdrawing alllawsuits and concluding their six-year legal
 battle.This resolution marked a significant milestone for Chinese semiconductor firms in international intellectual property (IP) disputes.
 JHICC's production strategy was structured into four phases
 • Phase I:A $5.3B investment, with production from Q3 2018, targeting a monthly capacity of 60,000 wafers, producing 25nm 4Gb DDR4/DDR3.
 • Phases II,III,IV:Planned expansion to a total capacity of 240,000 wafers per month, with an overall investment exceeding $20B. However, due to U.S. sanctions,
 subsequent phases were stalled, significantly limiting JHICC’s ability to expand itsproduction capabilities.


 Notes:
 • Following U.S. sanctions, the company has shifted to using mainly domestic equipment,
 except for photolithography tools.
 • Huawei is rumored to be a key customer, and inthe second half of 2024, JHICC, alongside
 CXMT, expanded DDR4 production to initiate a price war, aiming to push foreign
 competitors out ofthe Chinese DDR4 market.
 • Looking ahead, JHICC is ramping up production in 2025. It’sfab, built in 2018, has the
 capacity to expand by another 60,000 wafers per month. Tracking its recent equipment
 purchases could provide further insights into itsexpansion strategy.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 99
 2025-04-08 01:51

## 第 100 页

CHINA-UNITED STATES COMMERCIAL WAR – HIGHLIGHTS
Focus on AI chips and HBM


 • Due to U.S.trade restrictions,Chinese companies are barred from accessing high-end AI accelerators from Western suppliers. Even Nvidia’s AI chips tailored for China
 – such as the A800 (40GB HBM2) and H800 (80GB HBM3) – were banned from export inOctober 2023.

 • In response, Nvidia released the H20 GPUs, designed with adjusted performance specifications to comply with U.S. regulations. These modified models enable Nvidia
 to maintain itspresence in the Chinese market while adhering to export controls.

 • Example: H20 has 96GB HBM3 memory, and the bandwidth isup to 4.0 Tb/s, allhigher than the H100, but the computing power isonly 296 TFLOPs, and the
 performance density isfarinferior to the H100.
 • In December 2024, the U.S. government implemented new export controls restricting the sale of HBM chips to China without special authorization. These memory
 components are crucial for AI applications, and the restrictions aim to limit China's access to technologies that could enhance itsAI and military capabilities.
 Additionally, the U.S. Department of Commerce added ~140 Chinese entities toits trade blacklist,further tightening controls over China's semiconductor industry.
 • In early 2025, as the Chinese AI firm DeepSeek emerged as a major competitor in the AI landscape, Tencent, Alibaba, and ByteDance significantly increased their
 orders for Nvidia’s H20 GPUs. Meanwhile, the Trump administration has been discussing the possibility of expanding export controls to include the H20, given its
 capability to develop and power major AI applications. (Note: As ofMarch 2025, Nvidia isstillpermitted to ship the H20 to China.)
 • The Chinese government encourages local cloud service providers (CSPs) to procure at least20% of their AI hardware from domestic (x)PU or AIASIC manufacturers to
 support the development of China's semiconductor industry. However, due to domestic hardware and software limitations –including a lack of CUDA support and
 inferior performance in key computational tasks – Chinese CSPs continue to favor Nvidia’s GPUs, particularly the H20 model. Amid escalating U.S. restrictions on GPU
 exports, CSPs are actively stockpiling as many Nvidia GPUs as they can source to maintain competitiveness and efficiency.
 • Huawei’s AI ASICs (Ascend chips) are widely recognized as China's foremost alternative to Nvidia's hardware. While there are reports suggesting that DeepSeek R1
 utilizes Huawei's latest Ascend 910C chips for inference workloads, these accelerators are predominantly deployed by Chinese government agencies, state-owned
 enterprises, and entities engaged in national security sectors.
 • Initiallylaunched in 2019, the original Ascend 910 integrated HBM2E stacks sourced from global suppliers, a technology retained in subsequent iterations,
 including the Ascend 910B and 910C.

 • Researchers from DeepSeek indicate that the Ascend 910C chip achieves approximately 60% of the inference performance of Nvidia’s H100 GPU.
 • Market speculation suggests that Huawei may be indirectly accessing TSMC’s advanced foundry services through other Chinese semiconductor
 intermediaries to manufacture itscutting-edge Ascend chips. In response to these developments, the U.S. Department of Commerce reportedly issued a
 directive to TSMC, mandating the cessation of supplies ofAI chips manufactured atthe 7nm process node or below to customers inmainland China, effective
 November 11,2024. Notably, as of today, the Chinese foundry SMIC can provide 7nm-node manufacturing services.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 100
 2025-04-08 01:51

## 第 101 页

HBM DEVELOPMENTS IN MAINLAND CHINA


 • The U.S. curbs on AI chips and HBM have triggered significant investments and numerous initiativeswithin China aimed at producing such chips. Huawei isreportedly
 forming a consortium of companies to develop HBM, aiming to circumvent U.S.sanctions. Itis rumored that they are partnering with SJSemi and XMC. In addition,
 major Chinese OSAT companies –such as JCET and TFME –are alsoplanning to provide advanced packaging services for HBM integration. Examples:

 • JCET and TFME already possess HBM packaging technology; however, theirmanufacturing capabilities for thistechnology lack maturity and remain in the
 early stages of development.
 • XMC is equipping fabs with back-end tools to offer HBM stacking/packaging services (target capacity: 3KWPM).

 • Longforce, a subsidiary of Longsys, isreportedly exploring entry into the HBM market, potentially utilizing itsSuzhou R&D center for trialproduction.
 However, itcurrently lacks mass production capabilities.
 • CXMT is reportedly developing HBM2 and has announced a CNY 17.1billion ($2.4B) investment in an advanced packaging plant in Shanghai, aiming for a monthly
 capacity of 30,000 units by the second halfof 2026. TFME isrumored to be itsOSAT partner. CXMT's HBM2 samples are currently being tested by key customers, and
 the company isnow developing HBM2E.
 • China's firstHBM2 products are reportedly reaching maturity, with samples undergoing evaluation by select customers or being used internallyfor the development of
 server-grade processing units. Meanwhile, leading IDMs are already mass-producing 5th-generation HBM (HBM3E) and advancing tothe development and sampling of
 6th-generation HBM (HBM4). Given that HBM2 entered the market in 2018, Chinese companies are currently more than six years behind.
 • Manufacturing HBM remains highly complex, requiring cutting-edge DRAM designs and advanced packaging technologies forDRAM/logic stacking and
 heterogeneous integration. While leading global players have moved to ≤12nm DRAM nodes (1b or 1c),China's most advanced DRAM technology isstillat
 16nm (1z equivalent), a process node that has been inmass production since 2019.

 • Despite their technological gap, Chinese companies can leverage strong domestic demand forlocally developed AI accelerators, supported by significant government
 backing and a well-established industry network. These factors are expected to help them gain afoothold in the market inthe coming years.

 Key Chinese players active in HBM development


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 101
 2025-04-08 01:51

## 第 102 页

MEMORY PACKAGING BUSINESS IN MAINLAND CHINA
 Non-exhaustive!
IDMs and OSATs involved in memory packaging


 Dalian (3D NAND)
 Xi’an Xi’an (3D NAND) Xi’an (OSAT)
 (Assembly & test) DRAM packaging


 Wuxi (DRAM) Jiangyin (OSAT) Wuxi (OSAT)


 Gansu, (OSAT)
 Shanghai (OSAT) Shanghai (OSAT) Shanghai (OSAT)


 Wuhan (Foundry with adv. Suzhou (OSAT) Suzhou (OSAT)
 packaging capabilities)


 Note: YMTC and CXMT outsource the
 packaging of their NAND and DRAM devices. Jiangsu, (OSAT) Jiangsu, (OSAT)


 Top Chinese Memory OSATs
 Shenzen (OSAT) Shenzen (OSAT)

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 102
 2025-04-08 01:51

## 第 103 页

EUV EXPORT RESTRICTIONS – IMPACT ON THE DRAM BUSINESS


 • The U.S.government restrictstheshipment of EUV lithography equipment to China, preventing SK hynix from upgrading itsWuxi fab with EUV scanners forsub-1z nodes. Wuxi
 accounts for ~38% ofSK hynix’sDRAM wafer production and ~10% ofthe total DRAM output.

 • SK hynix currently ships wafers to South Korea forEUV processing before returning them to Wuxi. However, thisworkaround willbecome increasingly challenging as more EUV
 layersare required in advanced nodes—1a requires a single EUV layer,while 1bisexpected toneed 3-4 layers.

 • Without changes to EUV export policies,SK hynix will need to scale down DRAM production in China and expand further in Korea. The company isdeveloping a new
 manufacturing base in Yongin, South Korea, which willhost four fabs,with the firstexpected to be completed in 2027. Additionally,in May 2024, SK hynix sold a 49.9% stake in
 itsWuxi foundry to Wuxi Industrial Development Group Corp. for$349.3M.

 • Chinese DRAM manufacturer CXMT has made notable advancements in itstechnology and product offerings. The company has transitioned from itsGen 3 technology,
 comparable tothe 1x nodes of other DRAM producers, toa more advanced Gen 4 process. This Gen 4 technology utilizesa 16nm process node (1z),enabling the production of
 DDR5 memory chips. In response to export restrictionson advanced lithography equipment, CXMT is exploring alternative approaches for future DRAM development. One
 such approach involves the potential adoption of 3D device architectures, which could provide apathway to continue scaling memory technologies without relying on extreme
 ultraviolet(EUV) lithography.

 2024 Wafer Production by DRAM Manufacturer 2024 SK hynix Wafer Production
 Breakdown by Location (%) Breakdown by Location (%)


 Samsung

 8% SK hynix - Icheon
 SK hynix - Korea
 3% SK hynix - Wuxi
 SK hynix - China 38%

 38% Micron 430


 20% 1,560 Nanya KWPM
 KWPM Winbond 62%


 Powerchip

 10% CXMT
 17%
 Other


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 103
 2025-04-08 01:51

## 第 104 页

CHINA MEMORY BUSINESS – FOCUS ON DRAM
Summary and Outlook


 • Companies headquartered in China purchase over 25% of the DRAM products manufactured by global memory IDMs. The high level of memory consumption in
 China isfueling the country’s intense desire to produce more DRAM and NAND devices locally.However, China’s self-sufficiency in semiconductor memory is
 estimated to be below 15%.

 • U.S. trade restrictions pose a significant challenge to China’s memory industry, which relies heavily on imported technologies. Inturn, China isreacting to sanctions by
 increasing its semiconductor investments and establishing strong collaborative networks of local companies, including equipment suppliers, foundries, and OSATs
 with advanced packaging capabilities.

 • Changxin Memory Technologies (CXMT) isthe leading DRAM maker inChina. Itsfirst-generation DRAM (~27nm equivalent) isavailable domestically since 2019 (DDR4,
 LPPDDR4). After skipping its second-generation (G2) technology, CXMT ramped up production of G3 (~18.5nm equivalent) and significantly increased itsDDR4
 shipments in 2024, triggering price declines in the DDR4 DRAM market. In December 2024, KingBank and Gloway launched the first domestic DDR5 memory
 modules using CXMT G4 DRAM chips (16nm process), marking a supply chain milestone for China. Looking ahead, CXMT aims to introduce an updated HKMG G4
 technology (H2-2025) and develop 15nm DRAM technology in2025 (G5), with commercialization targeted for the second half of 2026. Note: In January 2025, the U.S.
 Department of Commerce tightened export restrictions on memory manufacturing equipment to China, subjecting equipment purchases for processes <25nm to
 additional controls. These restrictions could slow down CXMT’s G3 and G4 production growth, as well as itsG5 R&D.

 • Chinese companies have increasingly focused theirR&D efforts on two key approaches: (1)advanced packaging techniques for DRAM-logic integration and (2) DRAM
 scaling methods beyond conventional lithography shrinks, such as 4F² cells,CBA-DRAM, and 3D DRAM. These innovations enable Chinese players to develop high-
 performance AI chips without relying on restricted leading-edge equipment likeEUV lithography. By leveraging More-than-Moore solutions that integrate logic and
 memory, China aims to stay competitive in the race for technological leadership, particularly in the criticalfieldof AI computing.

 • The U.S. curbs on AI chips and HBM have triggered significant investments and numerous initiativesfor producing such chips within China. Huawei isreportedly
 building a consortium of companies –including XMC, SJSemi, TFME, and JCET –to build HBM, an essential building block of AIcomputing systems.

 • CXMT is reportedly sampling HBM2 to customers and is currently working on HBM2E development. The company announced a CNY 17.1billion($2.4B) investment in
 an advanced packaging plant in Shanghai, aiming for amonthly capacity of 30,000 units by the second half of2026.

 • At this stage, Chinese memory companies lag significantlybehind memory leaders intechnological development (~6 years). Despite their technological gap, Chinese
 players can leverage strong domestic demand for locally developed AI accelerators, supported by significant government backing and a well-established industry
 network. These factors are expected to help them gain afoothold in the market in the coming years.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 104
 2025-04-08 01:51

## 第 105 页

DRAM TECHNOLOGY TRENDS


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com105
 2025-04-08 01:51

## 第 106 页

INTRODUCTION TO DRAM TECHNOLOGY – BASIC BUILDING BLOCKS


 • A conventional DRAM structure consists offour basic elements:
 o Bitline: A conductive path that provides the carriers (current) to be injected into a transistor
 o Transistor: The gate that can be opened (turned on) orclosed (turned off)to keep or stop the current traveling within the capacitor
 o Capacitor: The device that stores the “bit”information in the form ofelectrical charge
 o Wordline: A conductive path that isused to apply a voltage bias to modulate the transistor state
 • During a read/write operation, the wordline isset to a high-voltage state; the transistor connects the capacitor to the bitlineenabling the current to flow. The
 value on the bitline(“1”or “0”)gets stored or retrieved from the capacitor.
 • Maintaining sufficient storage capacitance and adequate celltransistor performance are required to maintain the retention time inthe future.In addition, ifthe
 efficiency ofnode-over-node cost scaling becomes poor, new device architectures (e.g.,3D DRAM) willbecome necessary.

 Schematics of the basic DRAM structure Notes

 • During retention, electrical charges tend to leak out from
 the capacitor, so DRAM cells must be refreshed every 64
 ms at normal temperature (<85 °C).

 • The act of reading from the bitline forces the charge to
 flow out of the capacitor. Thus, in DRAM, reads are
 destructive.

 • The capacitor has a high aspect ratio (HAR) structure. In
 early DRAM generations, the capacitor was embedded into
 the silicon substrate, while today, itis processed on top of
 the transistor.

 • The charge stored in each capacitor istypically too small
 and a circuit called a sense amplifier is needed for a correct
 measurement.

 Image Source: K.H. Ahn, Vacuum Magazine 2016
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 106
 2025-04-08 01:51

## 第 107 页

INTRODUCTION TO DRAM TECHNOLOGY – BIT DENSITY SCALING


 • Since the early 1970s, each new DRAM generation has enabled continuous scaling of the bit density, which refers to the number of bits that can be
 stored per unit of silicon surface (i.e.,bits/mm2).Another common metric isthe average area per bit,which has reached ~13×10-4 µm2 (or 1,300 nm2) in
 today’s 1b(β) DRAM technology.
 • Continuous reduction of the area per bithas been pursued by reducing the footprint ofthe capacitors –i.e.,by making them tallerand narrower – but
 this willnot be possible in the long term because etch and deposition processes for capacitor fabrication cannot handle extremely high aspect ratios.
 • The DRAM industry isexpected to be able to maintain 2D DRAM until reaching an area of ~10×10-4 µm2 per bit,which islikelyto occur by the end of the
 decade. By then, DRAM shrinking willinevitably hit unsurmountable barriers, such as sub-10 nm patterning issues, ultra-high aspect ratio (HAR)
 capacitors, narrow sensing margins, etc.

 DRAM Cell Size Evolution DRAM Node Scaling Trend (nm)

 100 35
 Samsung SK hynix Micron
 80 30


 25

 60 20


 40 15

 10
 20
 5


 0 0
 3x 2x 2y 1x 1y 1z 1a(α) 1b(β) 1c(γ) 3x 2x 2y 1x 1y 1z 1a(α) 1b(β) 1c(γ)


 huguodong@cmbchina.com Note: the first products based on 1c(γ)DRAM will hit the market in 2025. Next-Generation DRAM 2025 | Report | www.yolegroup.com
 107
 2025-04-08 01:51

## 第 108 页

DRAM TEARDOWN REPORTS BY YOLE GROUP
 Examples of technology, process, and cost reports released in the last three years


 LPDDR5
 Memory
 Comparison
 • CXMT G4 DDR5 DRAMNEW (report to be released in Q2-2025)2024


 LPDDR5 Memory Comparison 2024
 • LPDDR5 Memory Comparison 2024
 • Samsung’s 8GB LPDDR5X (1a EUV, 16Gb/die, 0.43 Gb/mm2)
 • Micron’s 8GB LPDDR5 (1β, 16Gb/die, 0.5 Gb/mm2)
 • SK hynix’s 16GB LPDDR5X (1a EUV, 16Gb/die, 0.39 Gb/mm2)


 16Gb DDR5 DRAM Memory from Micron
 • 16Gb DDR5 DRAM Memory from Micron (1z, 16Gb/die, 0.24 Gb/mm2)
Are you Samsung 16Gb DDR5 DRAM Memory 2
interested in • Samsung 16Gb DDR5 DRAM Memory (1y, 16Gb/die, 0.22 Gb/mm )


 LPDDR5 Memory Comparison 2022
technology, • LPDDR5 Memory Comparison 2022
process, and • Samsung’s 8GB LPDDR5 (1z EUV, 16Gb/die, 0.26 Gb/mm2)
cost analyses • Micron’s 12GB LPDDR5 (1y, 12Gb/die, 0.18 Gb/mm2)
of leading- • SK hynix’s 8GB LPDDR5 (1y, 8Gb/die, 0.22 Gb/mm2)


 Samsung 16Gb LPDDR5 1z DRAM Memory
edge memory • Samsung 16Gb LPDDR5 1z DRAM Memory (1z EUV, 16Gb/die, 0.26 Gb/mm2)
devices?
Contact us for
details.
 ©Yole Group
 Example:
 Micron’s 1β 16Gb die

 source: “LPDDR5 Memory Comparison
 2024” report by Yole Group


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 108
 2025-04-08 01:51

## 第 109 页

LONG-TERM DRAM TECHNOLOGY ROADMAP

 2 2 < 4F2
 6F 4F
 2D 3D
 Vertical Transistors


 1c(𝛾) Multiple possibilities under investigation

 • 1T-1C DRAM with horizontal capacitors

 • 2T-0C DRAM (e.g.,IGZO)

 1d(𝜕) CMOS Bonding
 More EUV • 1T DRAM with 3D flash architecture
 1ε (PeriWafer + Array Wafer) (e.g., floating body, charge trap, ferroelectric layers)


 0a
 0b
 0c
 Bit area ~10×10-4 µm2 0d

 High-NA EUV Image credits: Applied Materials


 2025 2026 2027 2028 2029 2030 2031 2032 2033 2034 2035 2036


 Our modelprojectsthatstartingin2029,thetopthreememorymanufacturerswillproduce
 huguodong@cmbchina.com amixof6F²and4F²+CBADRAMproducts,eachtailoredforspecificendmarkets. Next-Generation DRAM 2025 | Report | www.yolegroup.com 109
 2025-04-08 01:51

## 第 110 页

DRAM scaling: challenges and solutions


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 110
 2025-04-08 01:51

## 第 111 页

DRAM TECHNOLOGY SCALING – OVERVIEW
New solutions are needed for long-term DRAM scaling


 • DRAM bit densities per unit surface (Gb/mm2) increased on average by about 25-35% node-over-node until~2014. However, due to the challenges with
 scaling the cell size,the node-over-node increase inbit density isnow down to less than 15%.
 • Overall, DRAM scaling is very challenging and isslowing down compared to the past – both in terms of bit density (Gb/mm2) and cost-per-bit ($/Gb) –
 but itcontinues to move forward!
 • Multiple technical solutions (see next slide)enabled continuous planar scaling until the recent 6th 10nm-class generation, namely 1c (or 1𝛾),which isnow
 entering early-stage production.
 • The increasing costs of patterning and fundamental physics limitations make scaling in two dimensions increasingly challenging for DRAM
 manufacturers. New materials, new device architectures, and new process technologies willbe necessary to extend DRAM scaling in the long term. A
 potential transition to 3D DRAM –as happened in 2014-2015 for NAND –could enable long-term scaling inthe 2030s.

 DRAM bit density scaling Key parameters that should be maintained/improved upon scaling


 Features Key Factors Performance
 DRAM bit density scaling
 has slowed since ~2014

 Leakage Current Refresh
 Data Retention Time Cell Capacitance Interval / Power


 Cell Capacitance
 Sensing Margin Bit-Line Capacitance Mat Size
 (or Net die)
 Sense Amplifier Offset


 Cell Transistor Current
 Data Write Time Margin Time Margin
 Source: IC Knowledge Contact Resistance


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 111
 2025-04-08 01:51

## 第 112 页

DRAM TECHNOLOGY SCALING – HISTORICAL TRENDS

 DRAM scaling and key technology innovations


 150nm


 130nm

 110nm 80nm (RCAT)

 60nm (Sphere RCAT)
 9x
 8x 40nm (Saddle Fin)
 6x 30nm (Buried Gate)

 5x 4x 20nm (DWG Buried Gate)
 3x 2x
 150nm (Planar Cell) 2y 2z 1x 1y 1z 1a(α) 1b(β) 1c(γ)

 90nm (STAR)
 25
 2000 2002 2004 2006 2008 2010 2012 2014 2016 2018 2020 2022 2024

 DRAM capacitor technical trends Die density scaling throughout DRAM history

 1E+13
 1E+12 2× / 40 months
 1E+11
 1E+10 16Gb 32Gb
 1E+09 4Gb 8Gb
 100000000 2× / 18 months 1Gb
 256Mb
 10000000 64Mb
 1000000 4Mb16Mb

 100000 1Mb
 256Kb
 10000 64Kb
 1000 16Kb
 4Kb
 100 1Kb
 1965 1975 1985 1995 2005 2015 2025

 huguodong@cmbchina.com Source: SK hynix (IEDM 2024) Next-Generation DRAM 2025 | Report | www.yolegroup.com 112
 2025-04-08 01:51

## 第 113 页

DRAM-CELL SCALING – TECHNICAL CHALLENGES


 • The DRAM capacitance value must be maintained How to increase the capacitance of a
 approximately constant node-over-node, even ifthe cylindrical capacitor?

 area of the DRAM cell capacitor is reduced. This is
 one of the most significant challenges forcontinuous Source: SK hynix, 2024
 DRAM scaling as it requires implementing capacitors
 with a high aspect ratio(HAR), bringing considerable Cell capacitor material selection
 manufacturing challenges.

 • To meet the requirements for future DRAM-cell
 capacitors, memory manufacturers are also
 developing ultra-thin dielectric layers with a high
 dielectric constant (𝜅) and low leakage currents. For
 instance, SK hynix’s Revolutionary Technology Center
 (RTC) has been working on fused ultra-thin
 (anti)ferroelectric materials. More details available at


 link
 this link.

 • Note: Shrinking the Si active area of a DRAM cell Example of DRAM cell roadmap (TEL)
 leads to lower drive current and increased variability.
 To prevent cell-to-cell variations, itis necessary to
 adopt advanced manufacturing solutions (e.g.,EUV)
 with HAR etching and minimize damage from the
 implant and Silicon loss due to oxidation.

 *The aspect ratio of the DRAM capacitor is
 poised to grow dramatically in the coming years
 without new solutions in terms of materials and
 cell architecture.

 Source: Tokyo Electron 2025
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 113
 2025-04-08 01:51

## 第 114 页

DRAM TECHNOLOGY TRENDS – 4F2 AND CMOS BONDING
The implementation of 4F2 cells and CMOS bonding are the next major steps in the technology scaling trajectory


 • Micron was the firstcompany to switch from an 8F2 to a 6F2 cell layout at 9x nm,
 followed by Samsung at 80 nm and SK hynix at 3x nm.
 BCAT VT • The 6F2 cell was developed by fillingthe empty spaces of 8F2 by positioning the
 transistors –e.g.,Buried Channel Array Transistors (BCAT) – diagonally to reduce the
 2 interruption by the BL. 4F2 cellsare based on verticaltransistors (VT).Connecting the
 6F2 4F WL and BL willresultin theirdimensions being 2F and 4F, respectively.
 • In 2025, allcommercial products willbe manufactured using the 6F2 DRAM cell
 design. However, due to process and layout limitations,all major DRAM makers
 established dedicated R&D teams to develop 4F2 structures for DRAM to be
 manufactured atsub-10nm nodes.
 • Reportedly, the introduction of 4F2 cellswith verticaltransistors willrequire adopting
 a CMOS-Bonded Array (CBA) architecture, where the periphery circuitand the
 memory arrayare processed on differentwafers and then bonded together. CBA will
 enable further density growth thanks to the area savings resulting from the
 repositioning of the CMOS circuit on a different wafer. Note: DRAM manufacturers
 expect a~30% increase inbit density from the combination of CBA and 4F2.

 • Due to stringent pitch/alignment requirements (<200nm), CBA DRAM isexpected to
 be implemented with fusion bonding, which islikelyto have a higher impact on cost
 than hybrid bonding.
 • Starting from the 0a node (>2028), some DRAM makers are expected to shiftto
 4F2+CBA for premium memory products to enable higher density and better
 performance through the implementation ofadvanced logic circuitsin a dedicated
 CMOS wafer, such as HKMG and FinFET(>2030).
 • Based on industry feedback, our current model projects that from 2029 onward, the
 top three memory makers willmanufacture a mix of6F² DRAM and 4F²+CBA DRAM,
 catering to differentend markets.
 CMOS at the Periphery CMOS Bonding • Warning: Moving to 4F² DRAM will require advanced deposition, etching, and
 (Monolithic Solution) (CMOS + DRAM Array Wafer) integration techniques (e.g.,CMOS bonding), increasing both cost and process
 complexity. Ifmanufacturing costs become prohibitive and yields remain low for
 high-volume production, DRAM makers willlikely extend 6F² scaling as much as
 possible –leveraging additional EUV layers and potentiallyHigh-NA EUV. Inthe long
 term (>2030), CBA willlikely become essential, even with 6F² architectures, to
 Source: Applied Materials, SEMICON West Technology Breakfast 2024 sustain performance and density advancements.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 114
 2025-04-08 01:51

## 第 115 页

DRAM SCALING ROADMAPS BEYOND 10nm
Examples of DRAM roadmaps shared by SK hynix and Samsung


 Prospects for DRAM cells beyond 10nm


 Source: Samsung, presented at IMW 2024


 Source: SK hynix, presented at IEDM 2024 (adapted from Yole’s “Next-Generation DRAM 2024” report)
 Proposed Candidates for Next-Generation DRAM


 Structure of the 4F2 cell
 with Vertical Gate (VG)
 transistors highlighting the
 use of CMOS Wafer Bonding


 Source: SK hynix, presented at IEDM 2024


 At VLSI 2024, Samsung also presented a work entitled Cell-to-CoreOverlap
 based on BCAT fornext generation DRAM that demonstrates the possibilityto
 scale densityvia CMOS wafer bonding changing thetype of arraytransistors.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 115
 2025-04-08 01:51

## 第 116 页

DRAM SCALING – FOCUS ON THE PERIPHERAL CIRCUIT


 • With DRAM scaling, itismore challenging to maintain the required off-current and
 wordline resistance. Peripheral circuits based on polysilicon gate technology with
 SiON oxide have been a cost-effective solution for decades. However, itnow faces
 several challenges in scaling the equivalent oxide thickness (EOT) to meet the
 growing power and performance requirements.

 • In this context, High-K Metal Gate (HKMG) is one of the innovations that enable
 further DRAM scaling. Besides being compatible with existing DRAM processes, it
 enables low power consumption, low leakage current, and more speed.

 • HKMG has been developed for logic devices since the early 2000s. Today, it isused in
 multiple products by leading DRAM manufacturers.

 • Samsung started using HKMG in2018 with itsGDDR6 (1x)products and,
 later,in2021, the company also used itfor DDR5 (1y).

 • SK hynix and Micron also introduced HKMG-based DRAM products, such
 as GDDR6 (1z)and LPDDR5X (1a and 1b nodes for SK hynix and Micron,
 respectively).

 • In the coming years, we believe that most new leading-edge DRAM
 products willfeature HKMG peripheral circuits.

 • In the long term, it is likelythat more advanced forms of transistors – such as
 FinFETs – will be used in the peripheral circuits.FinFETs enable improved control
 over leakage currents, higher performance, reduced short-channel effects, and
 faster switching speed.

 • The implementation of CMOS-Bonded Array (CBA) DRAM architectures will open
 new opportunities for scaling and optimizing the peripheral circuit. In fact,in CBA
 DRAM, two distinct processes/wafers are used for manufacturing the DRAM array
 and the peripheral circuit.Hence, the latter can be more conveniently manufactured
 with a dedicated advanced logic process (e.g.,FinFET). Source: IBM, presented at Flash Memory Summit 2023


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 116
 2025-04-08 01:51

## 第 117 页

Technology roadmaps and key trends


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com117
 2025-04-08 01:51

## 第 118 页

DRAM TECHNOLOGY – OVERVIEW BY PLAYER
Technology processes and main products of leading suppliers


 100 100 100


 80 80 80


 60 60 60


 40 40 40


 20 20 20


 0 0 0
 3x 2x 2y 1x 1y 1z 1a 1b 3x 2x 2y 2z 1x 1y 1z 1a 1b 3x 2x 2y 1x 1y 1z 1α 1β


 huguodong@cmbchina.com Non-exhaustive lists! Next-Generation DRAM 2025 | Report | www.yolegroup.com118
 2025-04-08 01:51

## 第 119 页

* *A new generation is said to start when its production
2020-2030 DRAM TECHNOLOGY ROADMAPS exceeds 10 M Gb per quarter.


 1znm
 1anm 1bnm

 1cnm
 1dnm
 0anm
 1znm
 1anm
 1bnm
 1cnm
 1dnm
 0anm
 1znm
 1αnm
 1βnm
 1γnm
 1δnm
 1ԑnm


 1xnm
 1ynm
 1z/1a nm

 2ynm eq.
 (Gen1) 1xnm eq.
 (Gen3) 1znm eq.
 (Gen4) 1anm eq.


 2znm
 1xnm


 2znm
 1xnm

 2020 2021 2022 2023 2024 2025 2026 2027 2028 2029 2030

 DRAM technology fully deployed w/ EUV DRAM technology based on CBA architecture (expected)

 huguodong@cmbchina.com Note: Samsung started manufacturing DRAM with EUV from the 1x node (test vehicle) Next-Generation DRAM 2025 | Report | www.yolegroup.com 119
 2025-04-08 01:51

## 第 120 页

DDR5 DRAM – HISTORICAL TIMELINES OF LEADING PLAYERS


 1y, 16Gb
 4,800-5,600 Mbps
 1a, 24Gb (EUV)
 4,800 Mbps
 1a, 16Gb (EUV)
 5,600-6,400 Mbps
 1a, 24Gb (EUV)
 5,600-6,400 Mbps
 1b, 16Gb (EUV)
 1a, 24Gb (EUV)
 5,600-7,200 Mbps

 1b, 32Gb (EUV)
 5,600-6,400 Mbps


 1y, 16Gb
 4,800 Mbps
 1a, 16Gb and 24 (EUV)
 4,800-5,600 Mbps
 1a, 16Gb / 24Gb (EUV)
 1b, 16Gb (EUV)
 5,600-6,400 Mbps
 1b, 32Gb (EUV)
 5,600-6,400 Mbps

 1z*, 16Gb
 4,800-5,600 Mbps
 1α, 24Gb
 4,800-6,400 Mbps

 1β, 16Gb 1β, 24Gb
 4,800-6,400 Mbps 6,400 Mbps
 1β, 32Gb
 5,600-6,400 Mbps


 2Q-22 3Q-22 4Q-22 1Q-23 2Q-23 3Q-23 4Q-23 1Q-24 2Q-24 3Q-24 4Q-24 1Q-25 2Q-25 3Q-25 4Q-25


 Note: Samsung and SK hynix manufactured the firstDDR5 products using the 1ynode, while Micron startedfrom the 1znode.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 120
 2025-04-08 01:51

## 第 121 页

HIGH-BANDWIDTH MEMORY (HBM) – ROADMAPS (TIME TO MARKET)


 HBM2
 HBM2E

 1y, 16Gb HBM3
 4-8Hi 1z, 16Gb
 (8-16GB) 8-12Hi HBM3E
 16-24GB 1a/1b, 24Gb HBM4
 8-12Hi
 (24-36GB) HBM4E
 HBM5


 HBM2
 HBM2E

 1y, 16Gb HBM3
 4-8Hi 12Hi
 (8-16GB) 1z, 16Gb (24GB)
 8Hi (16GB) HBM3E
 1b, 24Gb 12Hi
 8Hi (24B) (36GB) HBM4
 HBM4E
 HBM5


 HBM2E*

 1z, 16Gb HBM3E
 8Hi (16GB) 1b, 24Gb 12Hi
 8Hi (24B) (36GB) HBM4
 HBM4E

 HBM5


 Before 2020 2020 2021 2022 2023 2024 2025 2026 2027 2028 2029 2030


 Note:PriortoHBM, Micronwas involvedin HybridMemory Cubes (HMC). Thecompany startedshippingHBM2E
 in2020 and skippedthe HBM3 generationtocatch up withKorean competitors.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 121
 2025-04-08 01:51

## 第 122 页

IMPACT OF AI ON MOBILE AND CONSUMER DEVICES

 Smartphones and PCs with on-device generative AI are now hitting the market. Due to the substantial size of large-language-models (LLM), these devices
 require large memory/storage and will drive further bit-demand growth from the mobile & consumer market segment.

 2024 2025 and beyond

 Conventional PCs New devices with embedded Gen AI integrated in OS,
 software and games.
 Typical configurations: Typical configurations:
 DRAM NAND AI
 >8GB DRAM NAND
 256GB 512GB 1TB 2TB ≥16GB
 256GB 512GB 1TB 2TB
 Main DRAM technologies: DDR5 SO-DIMMs and LP DRAM (soldered) Main DRAM technologies: LP DRAM (soldered) and LPCAMM2 (≥LPDDR5X)
 Main NAND technologies: PCIe 3.0/4.0 SSDs Main NAND technologies: PCIe 4.0, PCIE5.0 to come

 Smartphones with basic AI functionalities New devices that use LLM multimodal AI inference to
 Use of a specific AI inference for targeted applications. assist the user in all tasks.

 Models with less than 150M parameters
 AI Typical content:
 Typical content: DRAM NAND
 DRAM NAND ≥12GB ≥256GB
 ≥6GB ≥64GB Hybrid
 Main DRAM technologies: LPDDR5/5X/5T DRAM (Pop Top), LLW/LPW DRAM.
 Main DRAM technologies: LPDDR5/5X/5T DRAM (Pop Top) Main NAND technologies: UFS 4.0,ZUFS 4.0 and beyond.
 Main NAND technologies: UFS3 and UFS 4.0


 Note: LLW: Low latency wide IO –LPW: Low power wide IO.
 huguodong@cmbchina.com LPW DRAM could be based on stacked LPDDR, e.g., Vertical Cu Post Stack (VCS) by Samsung. Next-Generation DRAM 2025 | Report | www.yolegroup.com 122
 2025-04-08 01:51

## 第 123 页

TECHNOLOGY TRENDS – DRAM FOR ON-DEVICE AI APPLICATIONS


 • ​The development of Low-Power Wide I/O (LPW) and Low-Latency Wide I/O (LLW) DRAM
 technologies reflects the semiconductor industry's commitment to enhancing memory
 bandwidth for mobile and consumer applications, particularly in artificialintelligence (AI)
 and augmented reality(AR).

 • LPW DRAM: Designed to offer high bandwidth while maintaining low power consumption,
 LPW DRAM integrates wide I/O interfaces to facilitaterapid data transfer, making itideal for
 mobile and on-device AI applications.

 • Samsung is reportedly collaborating with Apple to develop next-generation LPW
 DRAM, targeting mass production by 2028. This partnership aims to bring high-
 performance, low-power memory to future mobile and wearable devices,
 improving on-device AI capabilities.

 • A key technological advancement in LPW DRAM is fan-out packaging, which
 enables thinner, more power-efficient memory solutions, supporting compact
 and energy-sensitive devices such as AI-enabled smartphones. Samsung’s
 devices are expected to be based on the Vertical Cu-Post Stack (VCS) Source: Samsung, 2024 – Heterogeneous Integration Roadmap (HIR)
 architecture.

 • SK hynix has also been actively advancing LPW DRAM technologies, focusing on
 enhancing performance while maintaining energy efficiency for mobile and AI
 applications. A notable development in this area istheir work on Vertical Fan-Out
 (VFO) technology. VFO aims to improve memory performance by vertically
 stacking DRAM chips, thereby increasing data bandwidth and reducing latency,
 which iscrucial foron-device AI processing.

 • LLW DRAM: Designed to minimize access latency, which iscriticalfor real-time computing
 applications such as AI inference and edge computing. One notable implementation of
 LLW DRAM is Apple's Vision Pro AR headset, which integrates SK hynix’s LLW DRAM
 (H5EA1A56MWA, 1 Gb) alongside the R1 APL1W08 sensor processing unit. This combination
 enhances the device’s ability to process real-time sensor data with minimal latency,
 delivering a more immersive AR experience.
 Source: Yole Group, 2024 – SK hynix LLW DRAM dedicated to XR computing

 More details in the report “Apple –APU Co-Processor R1 from Apple Vision Pro” 2024 by Yole Group
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 123
 2025-04-08 01:51

## 第 124 页

TECHNOLOGY TRENDS – DRAM MODULES FOR AI PCs
LPCAMM2 hit the market in early 2024 and is poised to replace SODIMMs in AI PCs


 • Compression Attached Memory Modules (CAMM) debuted in2022 as a proprietary technology in Dell’s Precision 7670 notebooks. Later, in 2023, Dell donated itsCAMM intellectual
 property to JEDEC, which in turn developed and introduced the new CAMM2 standard that defines the technical specifications for both DDR- and LPDDR-based CAMM modules.
 Reference: JESD318: Compression Attached Memory Module (CAMM2) Common Standard.

 • Since Q3-2023, the three leading DRAM manufacturers have been gearing up tolaunch low-power (LP)CAMM products to replace SODIMMs in laptops:
 • In September 2023, Samsung announced the development of the firstLPCAMM2 technology and validated itsoperation at 7.5 Gbps on Intelplatforms. The company is
 currently conducting validations formajor customers.

 • SK hynix unveiled LPCAMM2 in November 2023 at the SK Technology Summit. More recently,they showcased LPCAMM2 atseveral industry events, including CES 2025 and
 GTC 2025, highlighting theircommitment to advancing AI memory solutions.

 • Micron presented LPCAMM2 samples atCES in January 2024. A few months later,Lenovo was the firstcompany to use Micron’s LPCAMM2 in itsThinkPad P1Gen 7 laptops.
 Note: Crucialiscurrently selling64GB and 32GB LPCAMM2 modules at $330 and $175, respectively.

 • LPDDR issignificantlymore power-efficient than mainstream DDR DRAM used in SODIMMs. However, LPDDR chips must be soldered directlyto the mainboard – as closeas possible to
 the processor – to avoid signal integrity (SI)losses,and, therefore, memory cannot be upgraded or repaired. The introduction of LPDDR DRAM modules –such as LPCAMM2 – isnow
 opening sound alternatives to both SODIMMs and soldered LPDDR DRAM.

 • LPCAMM2 is user-upgradeable –like SODIMM –and itscircuitboard isdesigned with very short traces to maximize signalintegrity.Itoffers multiple advantages:

 • LPCAMM2 occupies 64% lessspace than SODIMM

 • LPCAMM2 based on LPDDR5X uses up to60% less activepower

 • LPCAMM2 offersa 128-bit wide memory bus (vs.64-bit forSODIMM), maximizing bandwidth for AI PCs.

 • LPCAMM2 based on LPDDR5X enables speeds of7.5 Gbps, which is1.3times fasterthan DDR5 SODIMMs

 • Overall,the adoption ofLPCAMM2 ispoised to accelerate the penetration of LPDDR technology in personal computers at
 the expense of mainstream DDR DRAM (more detailsin the chapter: “Mobile and consumer – Focus on computing”).
 Source: Micron
 • Notes:
 • To assess the replacement rateof SODIMMs, we are currently investigating the impact ofLPCAMM2 on the total billofmaterials of notebooks, which includes the cost of
 replaceable compression connectors.
 • Besides the DRAM chips,LPCAMM modules also contain SerialPresence Detect (SPD) and a power management IC (PMIC).
 • We expect that solutions based on soldered LPDDR DRAM will remain popular. Although upgrades and repairs are not possible,such solutions are very competitive in
 terms of cost and speed.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 124
 2025-04-08 01:51

## 第 125 页

TECHNOLOGY TRENDS – DRAM MODULES FOR AI SERVERS
Small Outline Compression Attached Memory Module


 • In March 2025, Micron announced the availabilityof SOCAMM (Small Outline Compression Attached Memory Module), a new memory standard aimed at enhancing
 performance and efficiency in computing systems, particularly those handling artificialintelligence (AI)workloads. At GTC 2025, SK hynix also unveiled SOCAMM with
 speeds ofup to7.5 Gbps. Note: Micron announced that its128GB SOCAMM modules are designed for the Nvidia GB300 Grace Blackwell Ultra Superchip.

 • Micron, SK hynix, and Samsung have been collaborating with Nvidia to create the SOCAMM standard. This initiativeseeks to deliver a compact, high-performance
 memory solution tailored for AIapplications. ​The SOCAMM module is expected to be used forNvidia's next-generation successor to itsProject Digits AI computers, which
 was announced at CES 2025.

 • SOCAMM is designed to offer a significant increase in I/O ports compared to existing memory modules. Specifically,itprovides up to 694 I/O ports,exceeding the 644
 ports ofLPCAMM and the 260 ports found intraditional DRAM modules. This enhancement supports higher data transferrates essential for AIworkloads.

 • Compact and Modular Design: The SOCAMM form factor isnotably compact. Itsdetachable design facilitatesstraightforward upgrades and maintenance, aligning with
 the industry'smove towards modular and serviceable components.

 • These developments underscore the commitment to advancing memory technologies that meet the evolving demands of AI computing, offering enhanced
 performance, scalability,and energy efficiency.

 Key features of SOCAMM Micron’s SOCAMM product


 • Itprovides over 2.5times higherbandwidth at thesame capacity asRDIMMs

 • Itoccupies one-third ofthe sizeofthe industry-standard RDIMM

 • Leveraging LPDDR5X memory, SOCAMM consumes one-thirdthe power ofstandard DDR5
 RDIMMs

 • SOCAMM uses four placements of 16-die stacks of LPDDR5X memory to enable a 128GB
 memory module

 • SOCAMM’s modular design and innovativestacking technology improve serviceabilityandaid
 the design ofliquid-cooled servers

 Source: Micron, March 2025


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 125
 2025-04-08 01:51

## 第 126 页

HIGH-BANDWIDTH MEMORY (HBM)


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com126
 2025-04-08 01:51

## 第 127 页

HIGH-BANDWIDTH MEMORY – OVERVIEW


 • High-Bandwidth Memory (HBM) is a high-value, high-performance memory product with multiple DRAM dies
 interconnected vertically,providing faster data processing than traditional DRAM products.

 • HBM isthe ideal memory technology to meet the demanding performance requirements of generative AI
 applications. Advanced packaging approaches are needed for stacking multiple dies and integrating the
 resulting HBM stack ina computing system based on a GPU, CPU, or an AI ASIC accelerator.

 • HBM enables fast data transfer thanks to itswide I/O interface with 1,024 data bits(for comparison, DDR5 has an
 interface of “only” 64 data bits).HBM systems typically have a base/logic die that includes an HBM controller, a
 basic/fixed test engine provided by the DRAM vendor, and Direct Access (DA) ports.

 • HBM3E isthe fifth-generation product (succeeding HBM, HBM2, HBM2E and HBM3), and hit the market in 2024.
 The same year, in July, JEDEC announced it is nearing completion of the HBM4 standard, which is set to
 introduce a doubled channel count (i.e.,2,048)compared to HBM3, with a larger physical footprint. To support
 device compatibility, the standard ensures that a single controller can work with both HBM3 and HBM4 if
 needed. HBM4 willspecify both 24Gb and 32Gb DRAM dies, with options for supporting up to 16-high TSV stacks Source: SK hynix
 and speed up to 6.4 Gbps, with discussions ongoing for higher frequencies.
 DRAM Capacity vs. Bandwidth Example of bandwidth and capacity calculations


 Key advantage of HBM I/F Width Max. capacity Speed per Capacity Bandwidth
 # I/F* (DQ bits) per I/F (GB) data pin (GB) (GB/s) Comments
 (Mbps)
 Bandwidth = (# I/F) × (I/F width) × (Speed-per-data-pin)
 DDR5 8 64 512 5,600 4,096 350 Dual 256GB LRDIMMs


 LPDDR5 12 32 16 7,500 192 352 16Gb dies
 8 dies/package
 Source: Synopsis
 GDDR6 12 32 2 18,000 24 844 16Gb dies


 HBM3 6 1,024 16 4,800 96 3,600 16Gb dies, 8 dies/stack


 *I/F = memory Interface channel


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 127
 2025-04-08 01:51

## 第 128 页

HIGH-BANDWIDTH MEMORY (HBM)
Product Development Overview (1/2)


 HBM generation HBM HBM2 HBM2E HBM3 HBM3E HBM4


 Flarebolt Flashbolt Icebolt Shinebolt
 Players with market products Aquabolt
 Aquabolt-XL (PIM)


 Year of first product release 2014 2018 2020 2022 - 2023 2024 2026


 Typical number of dies per stack 4Hi 4-8Hi 4-8Hi 8-12Hi 8-12Hi (16Hi)NEW 12-16Hi
 (Main packaging approach) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps) (TSV & microbumps)


 Max capacity per stack 1GB 4-8GB 8-16GB 16-24GB 24-36GB (48GB)NEW 36-48GB


 Die density 2Gb 8-16Gb 16Gb 16Gb 24Gb 24Gb (32Gb)*
 (Typical process) (2x) (2y, 2z) (1y, 1z)(2) (1z) (1a, 1b/1β) (1b/1β, 1c/1γ)


 Max data rate 1Gbps 2-2.4Gbps 3.2-3.6Gbps 5.6-6.4Gbps 8.0-9.8Gbps ≥ 6.4Gbps


 Effective bus width 1,024 1,024 1,024 1,024 1,024 2,048


 Max bandwidth per stack 128GB/s 205-307GB/s 460GB/s 819GB/s 1.2TB/s ≥ 2TB/s


 huguodong@cmbchina.com *Note: we expect that 32Gb dies will be adopted in HBM4 with 12Hi configurations (48GB) Next-Generation DRAM 2025 | Report | www.yolegroup.com 128
 2025-04-08 01:51

## 第 129 页

HIGH-BANDWIDTH MEMORY (HBM)
Product Development Overview (2/2)


 HBM3E 8Hi / 12Hi / 16HiNEW HBM4 12Hi / 16Hi HBM4E 12Hi / 16Hi HBM5 16Hi / 20Hi
 (Expected in 2026) (Expected in 2027-2028) (Expected in 2029)


 1a / 1b DRAM(1) 1b / 1c DRAM(1) 1c DRAM 1d DRAM


 DRAM Die Process 1b DRAM 1b DRAM 1c DRAM 1d DRAM


 1b DRAM 1b DRAM 1c DRAM 1d DRAM


 1a / 1b DRAM 4nm 4nm / 2nm ≤ 2nm
 Samsung Foundry Samsung Foundry Samsung Foundry

 Base Die Process 1b DRAM 3nm / 5mn 3nm ≤ 3nm
 TSMC TSMC TSMC

 1b DRAM 1b DRAM 3nm ≤ 3nm
 TSMC TSMC


 TC-NCF TC-NCF TC-NCF TC-NCF / HB

 Bonding MR-MUF / Adv. MR-MUF Adv. MR-MUF Adv. MR-MUF Adv. MR-MUF / HB (D2W)
 Technology(2)

 TC-NCF TC-NCF TC-NCF TC-NCF / HB (D2W)

 MR-MUF: Mass Reflow Molded Underfill NCF-TCB: Non-Conductive Film Thermo-Compression Bonding HB: Hybrid Bonding (collective die to wafer)


 Notes: (1)Reportedly,Samsung faced yieldand thermal issueswith its1bDRAM forHBM3E, prompting ashiftback to the more stable 1anode whileconsidering skipping 1bentirelyforHBM4.
 However, due toNvidia'spreference,Samsung has been refiningits1bdesign. (2)StartingfromHBM4E/HBM5 (≥16Hi),wafer-to-waferhybridbonding islikelytobeadopted tostack thefirstDRAM
 layeron top ofthe base/logiclayer.Die-to-Wafer(D2W) hybrid bonding willbe used from theHBM5 generationto enable more than 20 diesper stack.

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 129
 2025-04-08 01:51

## 第 130 页

HIGH-BANDWIDTH MEMORY (HBM) FOR GPUs AND AI ASICs
Examples of products and roadmaps by GPU and AI ASIC players Non-Exhaustive List!


 Company Model Type of (x)PU Technology Content (GB) Capacity/Stack Die Density (Gb) Stack Height Number of Launch Date
 (GB) (# Dies) Stacks
 Inferentia 2 AI ASIC HBM3 32 16 16 8 2 2022-Q4
 Trainium 2 AI ASIC HBM3E 96 24 24 8 4 2024-Q4
 Inferentia 2.5 AI ASIC HBM3 32 16 16 8 2 2024-Q2
 Trainium 2.5 AI ASIC HBM3E 144 36 24 12 4 2025-Q2
 Trainium 3 AI ASIC HBM3E 144 36 24 12 4 2025-Q4
 MI200 GPU HBM2E 128 16 16 8 8 2021-Q4
 MI300 GPU HBM3 192 24 16 12 8 2023-Q4
 MI325 GPU HBM3E 288 36 24 12 8 2024-Q4
 MI355 GPU HBM3E 288 36 24 12 8 2025-Q4
 MI400 GPU HBM4 384 48 24 16 8 2026-Q1
 TPU v5e AI ASIC HBM2 16 16 16 8 1 2023-Q2
 TPU v5p AI ASIC HBM2E 96 16 16 8 6 2023-Q4
 TPU v6e AI ASIC HBM3E 32 16 16 8 2 2024-Q3
 TPU v6p AI ASIC HBM3E 192 24 24 8 8 2025-Q2
 TPU v7p AI ASIC HBM4 288 36 24 12 8 2026-Q1
 TPU v7e AI ASIC HBM4 216 36 24 12 6 2026-Q3
 Gaudi2 GPU HBM2E 96 16 16 8 6 2022-Q2
 Gaudi3 GPU HBM2E 128 16 16 8 8 2024-Q4

 Maia AI ASIC HBM3 64 16 16 8 4 2025-Q3

 A100 GPU HBM2E 80 16 16 8 5 2020-Q3
 H100 GPU HBM3 80 16 16 8 5 2022-Q4
 H200 GPU HBM3 144 24 16 12 6 2024-Q2
 B200/GB200 GPU HBM3E 192 24 24 8 8 2025-Q1
 B300/GB300 GPU HBM3E 288 36 24 12 8 2025-Q3
 GB300A GPU HBM3 144 36 24 12 4 2025-Q3
 R100 GPU HBM4 288 36 24 12 8 2026-Q1
 Dojo AI ASIC HBM2E, HBM3 160 32 16 16 5 2023-Q3

 Note: For products with launch date in 2025 and 2026 we report the expected technical characteristics.
 huguodong@cmbchina.com They may be subject to change. Next-Generation DRAM 2025 | Report | www.yolegroup.com 130
 2025-04-08 01:51

## 第 131 页

HBM ACTIVITIES BY PLAYERS – HIGHLIGHTS


 In 2014, SK hynix was the firstcompany to introduce HBM products, and since then, ithas had to defend itsleadership in HBM. In 2023, they announced the
 development of a novel HBM3 product with the highest capacity (24GB, 12Hi) and provided samples of HBM3E for AI applications to Nvidia for performance
 evaluation. Itcontinues to advance rapidly to maintain itsleadership in HBM technology. In April 2024, SK hynix and TSMC signed a memorandum of
 understanding (MoU) to collaborate on HBM4 development and next-generation packaging technologies, aiming to strengthen their positions in the high-
 performance memory market. In September 2024, SK hynix began mass production of 12Hi HBM3E. ​The surge in demand for HBM products, particularly forAI
 applications, propelled SK hynix to achieve a record quarterly operating profitof 8.1 trillionwon ($5.6B) in the fourth quarter of 2024, surpassing Samsung for
 the firsttime. ​Responding to industry demands, notably from Nvidia, SK hynix accelerated its HBM4 development timeline, achieving a 70% yield in 12Hi
 HBM4 testing ahead of mass production. ​InMarch 2025, the company started shipping samples of 12HiHBM4 (36GB) to selected customers.


 Samsung fellbehind SK hynix in the HBM race and is now working aggressively to regain momentum and secure its share of the market. In 2023, the
 company acquired a plant and equipment from Samsung Display in Tanjeong, South Korea, for approximately KRW 10.5 billion,and announced plans to
 invest an additional KRW 700 billionto KRW 1 trillionto increase HBM production capacity to 150,000–170,000 units per month. In February 2024, Samsung
 announced the development of 12Hi HBM3E, offering a capacity of 36GB and bandwidth of up to 1,280 GB/s. In July 2024, Samsung established a dedicated
 HBM development team within itsDevice Solutions Division to enhance itscompetitiveness in HBM technologies, including HBM3, HBM3E, and the
 forthcoming HBM4. In December 2024, Samsung’s 8Hi HBM3E memory passed Nvidia’s tests and was approved for use in Nvidia’s AI GPUs targeting the
 Chinese market. Reportedly, Samsung faced yield and thermal issues with its1b DRAM for HBM3E, prompting a shiftback to the more stable 1a node and
 consideration ofskipping 1b entirely forHBM4. However, due to Nvidia's preference, Samsung has been refining its1b design. As of early 2025, Samsung has
 reportedly initiated trialproduction of logic dies for HBM4 using 4nm process technology (Samsung Foundry). The company plans to provide HBM4 samples
 to customers fortesting aftercompleting performance verifications,with mass production anticipated in the latterhalf of 2025.


 Micron, having previously focused on the Hybrid Memory Cube (HMC) until discontinuing the project in 2018, entered the HBM market in late 2020 with 4-
 and 8-layer HBM2E designs (8GB and 16GB, respectively). To expedite itspresence in the HBM sector, Micron opted to bypass the HBM3 generation and
 instead directed its effortstoward developing HBM3E. In February 2024, Micron commenced mass production ofits 24GB 8Hi HBM3E memory stacks, which
 were integrated into NVIDIA's H200 Tensor Core GPUs starting in the second quarter of 2024. By September 2024, Micron introduced its12Hi HBM3E memory
 stacks, offering a 36GB capacity. As of late 2024, the company's HBM capacity was less than 20% of that of itsleading competitors, such as SK hynix and
 Samsung. Plans are underway to increase this capacity to 60,000 units per month by the end of 2025. Micron has collaborated with TSMC as part of TSMC's
 3DFabric Alliance, aiming to enhance semiconductor and system innovations. The company plans to commence mass production of HBM4 in 2026, with
 HBM4E expected tofollow in2027 or 2028. The forthcoming HBM4E willintroduce the option to customize the logic base die for specific customers.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 131
 2025-04-08 01:51

## 第 132 页

HIGH-BANDWIDTH MEMORY FOR ADVANCED (X)PUs
Device structure and supply chain


 Final Assembly: OSAT | Foundry | IDM
 The final assembly (HBM, GPU, interposer, interposer on PCB, passives assembly and BGA balls) is performed by the OSAT and
 foundry (possibly IDM).

 HBM Packaging: IDM | Memory Supplier

 The HBM stack (memory dies,logicdie) ismade by
 xPU Supplier: Foundry | IDM memory manufacturers. In the coming years,
 The CPU or GPU die is manufactured by the customized HBM willrequire DRAM suppliers to
 wafer foundry. HBM outsource the design and manufacturing of the
 xPU logicdie(more detailslaterinthischapter).


 2.5D Interposer:
 Foundry | IDM
 The Interposer die is manufactured 2.5D INTERPOSER
 by the wafer foundry.
 IC Substrate:
 Substrate Supplier
 IC Substrate The PCB package substrate is
 made by a substrate maker.


 PCB Board


 Source: “High-End Performance Packaging 2024” Report

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 132
 2025-04-08 01:51

## 第 133 页

HIGH-BANDWIDTH MEMORY – DETAILED SUPPLY CHAIN Wafers


 DRAM
 TSV Process

 Plating Solution

 Mold
 TCB Process


 Gases
 DRAM

 Hybrid Bonding (currently in R&D) Logic IC


 Logic IC CMP Slurries and Pads


 CMP, Grinding and Dicing
 Potential new entrants for customized HBM solutions


 HBM IP Tape (Dicing/Grinding)
 Molding Process


 And more…
 Non-Exhaustive Lists!
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 133
 2025-04-08 01:51

## 第 134 页

HBM MANUFACTURING – PROCESS FLOW
The HBM process comprises fab process, bumping/stacking processes, and testing


 Source:Applied Materials,SEMICON West Technology Breakfast2024

 For more detailsonstacking approaches bydifferentplayersseethechapter “Advanced Packaging forDRAM”


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com134
 2025-04-08 01:51

## 第 135 页

CUSTOMIZED HIGH-BANDWIDTH MEMORY – TECHNICAL TRENDS


 • Traditional HBM architectures, standardized by JEDEC, consist of memory stacks provided entirely
 by DRAM vendors (Samsung, SK hynix, Micron), including a base die that manages the interface
 between the memory and processor. While effective, this standardized approach can limit design
 flexibilityand optimization opportunities for system-on-chip (SoC) designers.

 • The advent of customized HBM (cHBM) addresses these limitations by providing SoC designers with
 enhanced flexibilityto develop solutions that are more closely aligned with their specific workload
 requirements, leading to higher performance, efficiency, and scalability in next-generation
 computing environments. In cHBM, the logic die can be designed and manufactured separately –
 often by the SoC vendor – while the DRAM vendor focuses on the stacked memory. Such
 customization necessitates close collaboration with DRAM manufacturers.

 • The logic die in customized HBM plays a crucial role in memory management, interface
 optimization, and overall system efficiency.One of the key technical trends in this space isthe shift
 to advanced logic nodes to enhance performance while reducing power consumption. Traditionally,
 standard HBM solutions use logic dies fabricated on older nodes, such as 28nm or 14nm, to strike a
 balance between cost and reliability.However, with customized HBM, there isa growing demand for
 logic dies manufactured using sub-10nm technologies (e.g.,7nm, 5nm, and even lower).
 • TSMC and Samsung Foundry are becoming key players inmanufacturing logic dies for customized
 HBM, leveraging their advanced process nodes. Moreover, technologies like TSMC’s CoWoS and
 Samsung’s I-Cube are gaining traction forassembling customized HBM solutions.

 • Companies like Nvidia, AMD, Marvell, and Broadcom are actively working on co-designing logic dies
 with foundries instead of relying solely on DRAM vendors. This shift enables chipmakers to integrate
 custom accelerators, power management features, and proprietary interconnects into their logicdie.
 • Hyperscale companies (e.g.,Google, Amazon, Microsoft) are increasingly designing their own custom
 HBM logic dies to optimize AI workloads. This trend isleading to more direct partnerships between
 hyperscalers and foundries, bypassing traditional DRAM vendors in certain aspects of the supply
 chain.

 • For instance, in December 2024, Marvell introduced a custom HBM compute architecture that
 demonstrated up to a 25% increase inthe area available for compute resources, a 33% enhancement
 in memory capacity, and a 70% reduction in memory interface power.

 Source: Marvell, December 2024


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 135
 2025-04-08 01:51

## 第 136 页

HIGH-BANDWIDTH MEMORY – FUTURE TRENDS AND INSIGHTS
Larger I/O buses, hybrid bonding and optical interconnects are being investigated for future HBM generations


 • DRAM manufacturers are activelydeveloping HBM4, aiming forinitialshipments to processor companies (CPU/GPU/APU) by late2025. HBM4 is expected to double the interface width up
 to 2,048 bits while simultaneously doubling interconnection density without significantly increasing the HBM module footprint. Looking further ahead to HBM5 and subsequent
 generations, manufacturers are exploring options to expand the interface width further, enabling continued bandwidth growth.

 • In the next generation of products, which could feature up to 20 layers (e.g.,HBM5), the adoption of hybrid copper bonding (HCB) is expected to be necessary to enable stacking
 architectures of 20Hi or even 24Hi while maintaining a package thickness of approximately 775 µm. HCB isa bonding technology that uses copper conductor and oxide film insulator
 instead of conventional solder to minimize the distance between DRAM devices as well as enable smaller bumps required fora 2,048-bit (or larger)interface.

 • As HBM continues to evolve, silicon photonics isbeing regarded as a potential solution to addressing performance scaling and heat-dissipation challenges in the long term. Major
 companies, including Intel,Samsung, AMD, TSMC, Nvidia, and Broadcom, have allactively engaged inphotonics research in recent years (more details are available inthe “SiliconPhotonics
 2024” report by Yole Group).
 • Samsung and Broadcom have entered into a partnership to develop siliconphotonics technology. The collaboration began in early 2024, positioning Samsung to compete with TSMC in
 next-generation foundry capabilities.At IEDM 2024, Nvidia provided insights into its vision for future AI chip designs, which may incorporate siliconphotonics I/O interconnects. These
 interconnects are crucialfor optimizing data flow between multiple GPU tiles,significantlyenhancing scalabilityand performance. In March 2025, the American startup Celestial AI –which is
 developing photonics solutions to create linksbetween AI computing chips and memory chips – raised an additional $250M in venture capital,bringing itstotal raised todate to $515M.

 • However, integrating silicon photonics at scale presents notable challenges:

 o Scaling up the capacity to produce siliconphotonics interconnects – over
 1 million connections per month may be needed for the commercial
 deployment ofAI accelerators indata centers.

 o Implementing effective thermal management solutions, considering that
 multi-tierGPU architectures have very complex cooling requirements.

 • The commercialization ofsuch designs is not expected tooccur before 2028. Once
 introduced, they could pave the way for optically-connected HBMs.

 • The industry isexploring two different approaches for integrating photonics and
 HBM. The firstisbased on a photonic interposer serving as the communication
 layer, which requires both logic and HBM to be configured with expensive
 photonics I/O.The second consists ofdecoupling the HBM stacks from the logic
 chip package and connecting them via an optical connector. This could simplify
 chip manufacturing and packaging costs for both HBM and logic, reducing the
 Source: Samsung’s Advanced Packaging Team need for localconversion from digital to optical.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 136
 2025-04-08 01:51

## 第 137 页

LEADING-EDGE DRAM MANUFACTURING


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com137
 2025-04-08 01:51

## 第 138 页

LEADING-EDGE MEMORY – A HIGHLY CAPITAL-INTENSIVE BUSINESS


 • The rapid growth of AIand high-performance computing (HPC) isdriving a surge in memory capital expenditures (CapEx) and wafer fab equipment (WFE),
 particularly inthe DRAM business.
 • DRAM bit growth isbecoming more expensive as lithography shrinks become more difficult.Multi-patterning requirements are increasing with each node
 migration, resulting in additional processing steps and, therefore, more cleanroom space per wafer out.The adoption of EUV isreplacing multi-patterning but
 requires significantinvestments inexpensive leading-edge tools.
 • DRAM suppliers – Samsung, SK hynix, and Micron – are prioritizingHBM investments, focusing on advanced lithography (including EUV), TSV fabrication, and
 advanced packaging technologies such as wafer bonding. The transition to higher-stack HBM (e.g.,12Hi,16Hi) and finerprocess nodes (e.g.,1b,1c)further
 amplifies WFE spending, particularlyin front-end wafer processing and back-end assembly.

 Memory industry CapEx (in $B) Wafer fab equipment for memory (in $B)

 $80 $80 100%
 DRAM NAND DRAM NAND % of CapEx


 $60 $60 75%


 $40 $40 50%


 $20 $20 25%


 $- $- 0%
 2020 2021 2022 2023 2024 2025F 2020 2021 2022 2023 2024 2025F


 Source: WFE, NAND and DRAM Market Monitors (Q4-2024) by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com
 huguodong@cmbchina.com 138
 2025-04-08 01:51

## 第 139 页

DRAM Fabs and Wafer Production


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 139
 2025-04-08 01:51

## 第 140 页

DRAM WAFER PRODUCTION – WORLDWIDE FAB LOCATIONS


 New Hwaesong
 Pyeongtaek Icheon
 Boise(~2025) New Cheongju
 Yongin
 Clay, New York
 Manassas (~2028) Wuxi Hiroshima
 (legacy fab)
 Hefei
 Beijing
 Shanghai


 Taoyuan Taishan

 Taichung Taichung


 Hsinchu


 Kaohsiung


 See next slide for fab production data Next-Generation DRAM 2025 | Report | www.yolegroup.com
 huguodong@cmbchina.com 140
 2025-04-08 01:51

## 第 141 页

DRAM WAFER PRODUCTION – BREAKDOWN BY FABS

 2024 DRAM Production – Wafers Out per Month

 200 189


 180

 162
 160 154


 140


 120 112

 101
 100 94 92 93

 81
 80 71 73

 60 59 57

 45

 40 30 31 31

 18 19 20
 20

 - - - - - 1 3 - -
 -


 *Notes: TNTP = New fab in Taishan Nanlin Technology Park
 CTSP = Central Taiwan Science Park (Taichung)
 huguodong@cmbchina.com STSP = Southern Taiwan Science Park (Kaohsiung) Next-Generation DRAM 2025 | Report | www.yolegroup.com 141
 2025-04-08 01:51

## 第 142 页

DRAM PRODUCTION WORLDWIDE – FOCUS ON SAMSUNG

 Pyeongtaek site, South Korea Hwaesong site, South Korea


 P1 Line 15
 Line 17
 EUV Fab P2

 P3 Line 17 EUV
 Line 16 Expansion
 P4 & P5


 Notes:
 • Pyeongtaek isthe super-site that could eventually accommodate >1M wpm. The P1 fab isused fora mix of NAND and DRAM and produced an average ~80k DRAM wafers per
 month throughout 2024. P2 was completed in 2020 and produced ~94k wpm in 2024. P3 started production in 2023 (currentlyproducing ~30k wpm), while P4 and P5 are
 expected to kickoff mass production in2025 and 2027,respectively.Construction ofP5 was initiallyhaltedinearly2024 but resumed in mid-2024 due to soaring demand forHBM
 drivenby AI accelerators.The foundational construction isunderway, with timelines adjusted toalignwith market conditions.
 • Inthe Hwaesong site,thefab expansion south of Line17 willaccommodate EUV toolsto enable advanced process nodes.
 • Notes:Samsung plans toexpand itssemiconductor packaging facilityinCheonan, South Chungcheong Province, withcompletion slated forend 2027.
 • Samsung's IC packaging capacitiesare located at itsCheonan and Onyang industrialparks. The Onyang campus has reached saturationdue tocontinuous facilityinvestments,
 prompting Samsung to consider establishing a new packaging line forHBM mass production inCheonan. The new linein Cheonan isexpected to produce the latestHBM,
 including5thgeneration (HBM3E) and 6thgeneration (HBM4).


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 142
 2025-04-08 01:51

## 第 143 页

DRAM PRODUCTION WORLDWIDE – FOCUS ON SK HYNIX

 Icheon, South Korea Wuxi, China


 M10 M16
 EUV-capable
 Wuxi C2F
 Wuxi C2
 M14


 Package
 and Test


 Notes:
 • InIcheon, the M10 facility,originallydedicated toDRAM production, iscurrently dedicated to CMOS image sensors (~100k wpm). The other fabs produce NAND and DRAM.
 • SK hynix isinvesting over 20 trillionwon to construct the M15X fab inCheongju, aiming to bolster HBM production capabilities.Construction began in April2024, with completion
 expected by November 2025.
 • The future siteforSK hynix’sDRAM expansion willbe Yongin. Announced in 2019,this clusterisset to become a major manufacturing base fornext-generation DRAM technologies,
 encompassing four fabs constructed in stages. ​The construction of the firstfab commenced in lateFebruary 2025, ahead of the initiallyplanned March start,with completion
 targeted formid 2027. This facilitywillfocuson producing next-generation DRAMs, including HBM.
 • To enhance HBM capacity, SK hynix plans to establish new TSV packaging lines atitsIcheon site.The company isalso constructing a packaging and research facilityinIndiana, USA,
 with an investment of approximately $3.87B. This facilityisexpected to commence operations inthe second half of2028, focusing on next-generation HBM products.
 • Due to export controls, SK hynix cannot currently installEUV tools initsWuxi, China fab. As aworkaround, the company has been processing wafers inSouth Korea before returning
 them toWuxi. However, thisapproach may become increasingly challenging asmore EUV layers are incorporated inadvanced process nodes.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 143
 2025-04-08 01:51

## 第 144 页

DRAM PRODUCTION WORLDWIDE – FOCUS ON MICRON

 Taoyuan, Taiwan Taichung, Taiwan Hiroshima, Japan

 Fab 11 (Inotera) Fab 16 Expansion Fab 15


 New fab space (A3/A5)
 EUV capable


 Expansion Rexchip, A1/A2
 Non-EUV capable


 January 2018 July 2021 August 2017


 Notes:
 • InOctober 2022, Micron announced plans to invest up to $100B over the next 20-plus years to construct a megafab inClay, New York. The facilityisdesigned to house four fabs,each
 with 600,000 square feet ofcleanroom space. The firstphase involves a$20 billioninvestment by the end ofthisdecade.
 • InMay 2023, Micron announced plans toinvest up to $3.6B over the next few years to bring 1γDRAM process technology based on EUV lithography to itswafer fabin Hiroshima, Japan,
 with mass production expected to begin in 2025. Micron also has an EUV manufacturing plant in Taichung (Taiwan).
 • InSeptember 2023, Micron disclosed plans for itsTaichung facilityto become the hub of advanced packaging for HBM. Additionally, Micron isconstructing a new HBM packaging
 facilityinSingapore, adjacent to itsexisting 3D NAND and DRAM fabs.This facilityrepresents an investment of approximately $7B and isscheduled tocommence operations in 2026.
 • InOctober 2023, Micron initiatedconstruction on itsleading-edge memory manufacturing fab inBoise. As of June 2024, significant progress has been made, with the project employing
 thousands of workers and involving substantial infrastructuredevelopment. The fab isprojected to begin meaningful DRAM production in 2027
 • Micron does not produce memory chips in China but has vast packaging operations in the country. InJune 2023, Micron announced plans to investmore than $600M initspackaging
 and test facilityinXi’an,China. InMarch 2024, Micron commenced construction of anew semiconductor assembly and testingplant in Xi'an.This facility,partofthe company's ongoing
 investment strategy,was expected to create 500 jobs and furtherstrengthen Micron’s presence inthe Chinese market.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 144
 2025-04-08 01:51

## 第 145 页

Equipment and materials for DRAM
manufacturing – overview


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com145
 2025-04-08 01:51

## 第 146 页

WAFER FAB EQUIPMENT (WFE) – MARKET OVERVIEW

 Wafer Fab Equipment Market ($B) WFE Investment for 100k WSPM (greenfield)
 Source:Tokyo Electron
 $120 60%


 $90 More details are available in the “Wafer Fab 45%

 Equipment Market Monitor” by Yole Group


 $60 30%

 DRAM WFE Mix by Node


 $30 15%


 $0 0%
 2019 2020 2021 2022 2023 2024 2025F

 DRAM ($B) NAND ($B)
 Other Memory ($B) Non-Memory ($B)
 Memory WFE / Total WFE (%)


 Source: Wafer Fab Equipment Market Monitor (Q4-2024) by Yole Group
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 146
 2025-04-08 01:51

## 第 147 页

MEMORY WAFER FAB EQUIPMENT (WFE) MARKET

 Memory* WFE Revenue – Estimated Breakdown by Process Type (%)
 *All memory technologies are included in the analysis
 Notes
 100%

 4% 5% 5% • DRAM is a lithography-intensive
 technology that requires advanced
 12% 12% 10% and costly patterning systems,
 80% such as EUV lithography tools.


 25% • In 2024, DRAM manufacturers
 23% made significant investments in
 32%
 60% capacity expansion to meet the
 growing demand for high-
 performance memory, particularly
 HBM.
 29% 26%
 40% 22% • Unlike DRAM, 3D NAND does not
 rely on advanced lithography but
 is instead heavily dependent on
 etching and deposition processes.
 20% Future 3D DRAM devices could
 27% 27% 30% shift the business landscape
 toward a WFE mix more like that
 of NAND.
 0%
 2022 2023 2024 (E) • In 2024, NAND manufacturers
 limited their investments to
 Deposition Equipment Patterning Etch and Clean Metrology & Inspection mitigate the risk of oversupply.


 Thinning and CMP Equipment Ion Implant Wafer Bonders Other Equipment


 More details are available in the “Wafer Fab Equipment Market Monitor” by Yole Group
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 147
 2025-04-08 01:51

## 第 148 页

More details are available in the “Wafer Fab
 WAFER FAB EQUIPMENT (WFE) FOR MEMORY Equipment Market Monitor” by Yole Group

 Memory* WFE Market Shares (%)
 (*incl. all memory technologies) Top-5 Equipment Suppliers

 100% ASML

 Applied Materials

 80% Lam Research

 Tokyo Electron

 60% KLA

 Kokusai
 Top 5 Semes
 40%
 memory ASM
 WFE 20% Wonik IPS

 SCREEN
 suppliers
 0% Other
have more 2022 2023 2024 (E)
than 80% of
the market. Deposition Etch & Clean Lithography Metrology & Inspection


 3 main competitors: 3 main competitors: 1 leading player in this area: 1 leading player in this area:


 Others: Nikon, Canon… Others: AMAT, Onto…


 huguodong@cmbchina.com Source: Wafer Fab Equipment Market Monitor (Q4-2024) by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 148
 2025-04-08 01:51

## 第 149 页

WAFER FAB EQUIPMENT SUPPLIERS
 Key players, by process type Non-exhaustive lists!


 Patterning


 Deposition


 Etch and Clean


 Thinning and CMP


 Bonding
 (incl. diffusion furnaces)


 Metrology & Inspection


 Memory Testing


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 149
 2025-04-08 01:51

## 第 150 页

EQUIPMENT FOR DRAM MANUFACTURING – FOCUS ON LITHOGRAPHY


 • Increasing DRAM density by reducing celldimensions isdriving changes in lithography. Since the 1xnode, bit-contact layers have been implemented
 with ahoneycomb pattern toincrease density within a given line spacing, as well as with self-aligned multiple patterning.

 • SADP combines one photolithography step and one spacer deposition, aiming to halve the pitch during the patterning step (see figure
 below). SADP with 193nm immersion lithography works well forDRAM fabrication at the 1x,1y,and 1znodes.

 • As DRAM shrinks and defect probability rises,itbecomes convenient – in terms of cost and yield – to switch from self-aligned multiple patterning to
 single patterning with EUV lithography systems, which are currently supplied by only one company, the Dutch ASML.

 • EUV lithography uses light with a wavelength of 13.5nm and a numerical aperture (NA) of 0.33.This represents a wavelength reduction of almost 15times
 compared to the next most advanced lithography solution – deep ultraviolet(DUV) ArF lithography –which utilizes 193nm light.ASML has also started to
 build the next generation of EUV lithography systems with a higher NA of 0.55.

 Cost positioning – EUV vs. other patterning methods Lithography Layer Count


 MOR: Metal Oxide Resist
 CAR: Chemically Augmented Resist


 huguodong@cmbchina.com Source:Micron Next-Generation DRAM 2025 | Report | www.yolegroup.com
 150
 2025-04-08 01:51

## 第 151 页

EXTREME ULTRAVIOLET (EUV) LITHOGRAPHY FOR DRAM MANUFACTURING
Overview of DRAM suppliers


 • Samsung, leveraging itsfoundry expertise, was the firstto adopt EUV lithography forDRAM, implementing a single EUV layerin its1z node in2020. Before
 that,Samsung had used its1x DRAM as a test vehicle forEUV integration. SK hynix followed in February 2021, completing itsfirstEUV-equipped fabrication
 lineand commencing mass production of 1aDRAM in the second half ofthe year.
 • Micron took a more cost-conscious approach, delaying EUV adoption to avoid the high depreciation costs of the equipment. Instead, the company relied on
 self-aligned multiple patterning techniques (e.g.,SAQP) through its 1βnode, achieving a bit-cellsizecomparable to itsKorean rivals.However, as process
 nodes shrink beyond 1β,maintaining process control and production stabilitywith multiple patterning becomes increasingly challenging. In February 2025,
 Micron announced the firstshipments ofDDR5 DRAM produced with its1γ node –itsfirsttoincorporate EUV lithography.
 • Looking ahead, Korean DRAM makers are exploring High-NA EUV forsub-10nm DRAM. As ofQ1 2025, SK hynix is collaborating with ASML at the High-NA
 Joint Lab at imec (Belgium) to validate process technology and stability.Meanwhile, Micron has yet to announce itsplans for High-NA EUV but islikelyto
 evaluate ASML’s pilot systems alongside itscompetitors.

 Estimated # of EUV layers EUV Lithography 0.33NA Exposure (weighted average)


 DRAM Node


 1z 1 0 0


 1a / 1α 3-5 1 0
 15-24% EUV spend CAGR
 1b / 1β 5-6 3-4 0


 1c / 1γ 6-7 5-6 1

 Source: ASML

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 151
 2025-04-08 01:51

## 第 152 页

EQUIPMENT AND MATERIALS FOR DRAM MANUFACTURING
Novel opportunities are emerging beyond advanced lithography systems

 Examples of new materials, processes and systems that will enable continuous technology progress


 Source: Lam Research, Investor Day, 2025


 • Molybdenum (Mo) isexpected to replace tungsten in DRAM bitlinecontacts to reduce resistance and
 enhance speed. AsDRAM moves toward stackedtransistorarchitectures(3DDRAM), Mo could alsoplaya role Source: Tokyo Electron, Investor Day, 2025
 in gateand wordline materialstoenhance performance.
 • ALD isthe besttechnique fordepositing Mo inDRAM manufacturing, as itprovidesconformal, uniform films,
 even inhigh-aspect-ratiostructures.Italsoenablesprecisecontroloffilmthickness and composition,offering
 better etchselectivityandpatterningcompatibilitythan tungsten.

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 152
 2025-04-08 01:51

## 第 153 页

IMPACT OF THE 2D-TO-3D DRAM TRANSITION ON THE DRAM WFE BUSINESS
3D DRAM will reshuffle the DRAM WFE mix in favor of etching and depositions


 • Currently, multiple key aspects of the monolithic 3D-DRAM development are stillunknown. Different options – in terms of
 device architecture and process flow – are currently being worked on in the labs of major memory manufacturers (see the
 chapter dedicated to “3D DRAM”), but the “way-to-go” strategy has not yet been defined.

 • Samsung and SK hynix expect that a clearer development direction on 3D DRAM willemerge in the next few years.Given the
 lack ofdetails,itis premature atthis stage to develop a market model to quantify the impact ofthe 2D-to-3D DRAM transition
 on the WFE business.
 • However, we can make a few preliminary considerations based on the following plausible scenario:

 • 3D DRAM willbe based on stacked layersof interconnected capacitors lying horizontally.

 • A relativelyhigh number oflayers (>>20) would be necessary from the very first3D-DRAM generation to achieve a
 competitive bit-density level.

 • CMOS bonding approaches willbe used to connect periphery circuitsand memory arrays.

 • Under these conditions, 3D-DRAM manufacturing willbring complex process challenges and very aggressive specifications in
 terms of etching and deposition requirements. However, it willenable the use of “relaxed” lithography nodes (20-25nm),
 opening new competitive pathways forthose players thathave no access to advanced EUV lithography (e.g.,China).

 • 3D DRAM willlead toincreased deposition, etch, and gas chemical etch processes, and a significant retooling ofDRAM fabs
 willbe necessary. Equipment spending for deposition systems (ALD, PE-CVD) and high-aspect-ratio (HAR) etching systems
 willgrow significantly.More than 70% of the equipment spending forDRAM manufacturing could be focused on deposition
 and etching systems; the share of lithography spending could shrink below 20%.

 • The use of CMOS bonding (hybrid/fusion) for 3D DRAM will be the next major growth wave forthe wafer-to-wafer bonding
 equipment market.

 • As in the case of 3D NAND, significant investments will be needed to implement the new 3D-DRAM process flows in high-
 volume manufacturing. We expect asubstantial capex increase by DRAM manufacturers to ramp up 3D DRAM generations, a
 more than 50% increase in the firstyearof 3D-DRAM production.


 Image Source: Applied Materials ‘Engineering Capabilities for3D DRAM
 presented atthe SEMICON West Technology Breakfast 2024
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 153
 2025-04-08 01:51

## 第 154 页

DEVICE AND MATERIAL CHALLENGES FOR NEXT-GENERATION DRAM

 Summary of major device and material challenges

 • Besides patterning/lithography challenges, there are three other major hurdles:
 • Storage capacitor scaling – numerous detrimental phenomena, such as the so-called Row Hammer effect, arise when decreasing capacitor
 dimensions. Moreover, the sense margin decreases with the cell capacitance, driving manufacturers to increase the aspect ratio and introduce
 new geometries and materials (see next slide).
 • Interconnects – improvements are needed in bitline and wordline resistance/capacitance for increased speed. Logic copper interconnects –
 instead ofaluminum – can minimize RC delays associated with peripheral circuit minimization.
 • Peripheral transistor scaling – with decreasing cellsize,itis more difficultto maintain the required off-current and wordline resistance. Polysilicon
 gate technology with SiON oxide has been a cost-effective solution for decades. However, itnow faces several challenges in scaling the equivalent
 oxide thickness (EOT) to meet the growing power and performance requirements. In this context, the high-K metal gate (HKMG) process -which
 replaces the SiON gate oxide material inthe transistor gate with a thin high-k film – has emerged as a potential solution.
 • The HKMG process was initiallyadopted by Samsung in 2018 for GDDR6 memory, and later,in 2022, the company also used HKMG for DDR5
 DRAM.
 • SK hynix and Micron have also begun using HKMG. In November 2022, SK hynix announced 1αnm LPDDR5X DRAM with HKMG, while
 Micron began shipping its 1βDRAM with HKMG transistors.

 Summary of major material challenges

 • At each new technology generation, DRAM makers narrow the diameter ofthe capacitor and elongate it to maximize itssurface area, thereby pushing the
 aspect ratioto its extreme. The higher the aspect ratio,the greater the riskthat the ‘hard mask’ – which isused as a stencil for patterning – iseroded before
 the capacitor hole is fullyformed. However, a thick hard mask and narrow capacitor make itdifficultto complete the etch by removing allbyproducts, which
 can cause twisting, bending, under-etching, and other defects. Hence, there is currently a quest fornew hard mask materials to pattern high-aspect-ratio
 (HAR) capacitors.
 • Each metal line needs to be surrounded by an insulating dielectric material to prevent interference between electrical signals. However, thinning the
 dielectrics brings the metal linesso close together that capacitive coupling increases the degradation of the device performance metrics. Besides looking for
 novel low-k dielectric materials to replace siliconoxide, one solution can be taken from the logic IC world, namely copper low-k interconnects. In DRAM, the
 time is now fora new metal-line material!


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 154
 2025-04-08 01:51

## 第 155 页

MATERIALS FOR DRAM MANUFACTURING – DEVELOPMENT OPPORTUNITIES
Focus on the Metal-Insulator-Metal Capacitor (MIMCAP)


• Objective: reduce the equivalent oxide thickness and minimize the leakage of the DRAM capacitor.
• Options: (1)use high band gap dielectricstoreduce leakage;(2)avoid tunneling currentby choice of dielectricthickness;(3)optimize dopants and anneals
 and template bottom electrode to crystallizedielectrictohigh Kphases; (4) use high work function electrodes tominimize leakage.


 huguodong@cmbchina.com Source: Merck, Intermolecular Next-Generation DRAM 2025 | Report | www.yolegroup.com 155
 2025-04-08 01:51

## 第 156 页

SUPPLIERS OF MATERIALS FOR MEMORY MANUFACTURING
By manufacturing process Non-exhaustive!


 Lithography & CVD/ALD PVD Etching Electroplating CMP
 patterning


 Photoresist Precursors Targets/sources Etching chemicals Plating chemistries CMP slurries


 Wafer Suppliers: Shin-Etsu, GlobalWafer, Siltronic, SK Siltron
 huguodong@cmbchina.com IC Substrates: Unimicron, Ibiden, Semco, Simmtech, AT&S, and more Next-Generation DRAM 2025 | Report | www.yolegroup.com 156
 2025-04-08 01:51

## 第 157 页

ADVANCED PACKAGING FOR DRAM


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com157
 2025-04-08 01:51

## 第 158 页

MEMORY PACKAGING TECHNOLOGY – SUMMARY
Advanced packaging is a key enabler of performance improvement and bit density growth


 • Wirebond is the most common memory packaging approach, accounting forover half ofthe totalmemory packaging revenue. Itiswidely used for
 mobile memory and storage applications. Flip-chip packaging is the second largest segment in terms of revenue as itcontinues itsexpansion inthe
 DRAM business.
 • The adoption of flip-chip packaging with short interconnects isessential to enable high bandwidth per pin, which iswhy all leading-edge GDDR
 devices use flip-chippackages. Since the mid-2010s, PC and server DRAM packaging has been progressively migrating from wirebond to flip-chip.

 • Fan-out packaging is emerging as a key enabler forLow-Latency Wide I/O and Low-Power Wide I/O (LPW) DRAM technologies to be used innext-
 generation portable devices with on-device AI functionalities.It offers compact integration, reduced interconnect lengths, and improved electrical
 efficiency.
 • Samsung and SK hynix are working on Vertical Cu-Post Stack (VCS) and Vertical Fan-Out (VFO), respectively, to improve memory
 performance by stacking DRAM chips, thereby increasing data bandwidth and reducing latency, which iscrucial foron-device AIprocessing.
 • Among the various advanced packaging approaches, CMOS bonding has emerged as the most promising solution formanufacturing denser and
 more performant memory devices.
 • Reportedly, Wafer-to-Wafer (W2W) hybrid bonding will be used to stack the firstDRAM layer and the base/logic layer. The firsttechnologies
 utilizingthis approach are likelyto be HBM4E/HBM5 (≥16Hi),particularly in customized HBM solutions.
 • SK hynix, Samsung, and Micron – in partnership with equipment suppliers – are conducting intense R&D activities to enable the next
 generations of HBM with ≥20 dies/stack through Die-to-Wafer (D2W) and Die-to-Die (D2D) hybrid bonding processes. We currently model
 die-bonding approaches to start with the HBM5 generation from 20Hi (~2028).

 • Wafer-to-Wafer CMOS bonding is alsoexpected to be part of the DRAM scaling path forthe implementation of CMOS Bonded Array (CBA)
 DRAM devices. Leading IDMs are expected to ramp up CBA-DRAM production using wafer-to-wafer stacking approaches from the 0a
 technology process (>2028). Due to stringent pitch/alignment requirements (<200nm), CBA DRAM is expected to be implemented using
 fusion bonding, which islikelyto have a higher impact on cost than hybrid bonding.

 • Chiplet architectures enabled by novel stacking/bonding solutions –such as AMD’s 3D-Vcache with hybrid bonded SRAM and Intel’sRAMBO (random-
 access memory bandwidth optimized) chiplets –have become essential for increasing the performance of computing units such as CPUs and GPUs
 viaa tight integration of logic and memory.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 158
 2025-04-08 01:51

## 第 159 页

MAIN MEMORY PACKAGING PLATFORMS
Memory devices use a wide variety of packages


 Standard packaging Advanced packaging


 Wirebond TSV & micro Hybrid Bonding
 Leadframe (Organic substrate) Flip-chip bumps (3D NAND / HBM) FAN-IN FAN-OUT WLP
 (3DS/HBM)

 Die 3D NAND based on FOWLP
 3DS hybrid bonding WLCSP Die

 Die
 IC Substrate PCB

 PCB
 Stacked FOWLP
 PCB
 Source: YMTC Die Die
 HBM Die Die
 Die HBM based on
 hybrid bonding PCB

 IC Substrate


 PCB


 can be multi-chip


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 159
 2025-04-08 01:51

## 第 160 页

MEMORY PACKAGING EVOLUTION AND ROADMAP


 Conventional Packaging Technologies Advanced Packaging Technologies

 Chiplet / SoIC
 Evolution driven by higher TSV HBM
 bandwidth requirements, higher Image
 density, smaller form factors credit:
 Intel
 Memory SiP
 Hybrid Bonding
 packaging TSV DRAM (3DS) NAND HBM
technology has
 evolved from BOC
 leadframe
 packaging to
 advanced TSOP MC Image credit: YMTC
 packaging WB BGA P Stacked FOWLP

 Die Die
 based on TSV Die Die
 and hybrid
 bonding. DIP SOJ PCB

 WLCSP Flip-Chip Fan-Out SiP


 1970s 1980s 1990s 2000s 2010s 2020s 2030s


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 160
 2025-04-08 01:51

## 第 161 页

MEMORY PACKAGING, ASSEMBLY, AND TESTING
Key players
 Non-exhaustive!


 OSATs


 (1)


 IDMs involved in
 memory packaging
 (2)


 (1) Unimos Microelectronicsisa JV between ChipMos (Shanghai),originallyawholly-owned subsidiaryofTaiwan's ChipMos Technologies,and Tsinghua Unigroup.
 Tsinghua isthe largestshareholderof theJV,with a 48% stake.
 (2) Most IDM memory suppliershave theirown in-house assembly capability.

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 161
 2025-04-08 01:51

## 第 162 页

3D Stacking – Focus on bonding technologies


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com162
 2025-04-08 01:51

## 第 163 页

BONDING TECHNOLOGIES FOR NEXT-GENERATION DRAM – ROADMAPS


 High Bandwidth Memory

 • Hybrid bonding willbe needed to continue improving data-transfer speed, heat dissipation, and power efficiency,as well as tominimize the HBM stack thickness.

 • Reportedly, hybrid bonding willbe firstused tostack the firstDRAM layer and the base/logic layer. Inthis case, the HBM assembly process will require a wafer-to-wafer
 (W2W) hybrid bonding step.The firsttechnologies using this approach are likelytobe HBM4E/HBM5 (≥16Hi),particularlyin customized HBM solutions.

 • Die-to-Wafer (D2W) and Die-to-Die (D2D) bonding schemes willbe used in subsequent generations. We currently model die-bonding approaches to start from the
 HBM5 generation from 20Hi (~2029).
 Planar DRAM with CMOS Bonded Array (CBA) Architecture

 • DRAM makers are expected to use fusion W2W bonding from the 0a DRAM node (~2029) to stack the DRAM array wafer and the CMOS logic wafer. More detailsin the
 “DRAM scaling:challenges and solutions” chapter of thisreport. Collective D2W
 W2W
 W2W W2W (fusion) W2W

 HBM3E HBM3E HBM3E HBM4 HBM4 HBM4E HBM5 CBA DRAM HBM5
 (8Hi) (12Hi) (16Hi) (12Hi) (16Hi) (16Hi) (16Hi) (0a) (20Hi)


 2024 2025 2026 2027 2028 2029 2030

 Mass Production Time For Market Leaders


 Technologies based on MR-MUF* or NCF- Technologies that are likely to make use of
 TCB**with TSV and microbumps hybrid (or fusion) bonding


 Image credit: Applied Materials


 huguodong@cmbchina.com *MR-MUF: Mass Reflow Molded Underfill**NCF-TCB: Non-Conductive Film Thermo-Compression BondingNext-Generation DRAM 2025 | Report | www.yolegroup.com 163
 2025-04-08 01:51

## 第 164 页

BONDING TECHNOLOGIES FOR NEXT-GENERATION DRAM


 Hybrid Bonding for High-Bandwidth Memory

 • Hybrid bonding enables higher bandwidth thanks to the bumpless die-to-die interconnects, smaller inter-die spacing and lower HBM
 stack thickness, improved power efficiency, and better thermal dissipation across the stack.
 • However, hybrid bonding ischallenging to implement – yields and throughputs are reportedly low – and expensive, so memory makers
 are trying to extend their existing bonding solutions – such as flux-lessTC-NCF or Advanced MR-MUF –to HBM4 and HBM4E with up to 16
 layers.
 • To adhere to the existing JEDEC standards*, the thickness of individual DRAM dies and the microbump gaps must be minimized. 8Hi
 stacks typically have a die thickness of 50-55µm and a microbump height of 14.5µm, while products featuring a 12Hi stack have a reduced
 die thickness inthe 30-40µm range.
 • Looking ahead, further reductions to approximately 20µm die thickness and the implementation of gapless stacking viahybrid bonding
 are necessary to enable architectures of 20Hi or even 24Hi while maintaining the package thickness at approximately 775 µm.
 • In the previous edition of this report,we indicated that hybrid bonding could have started with the HBM4 generation. As of today (March
 2025), allHBM suppliers have implemented advanced versions of their microbump-based packaging approaches (e.g.,flux-less TCB or
 advanced MR-MUF), and we expect they will delay the introduction of hybrid bonding to HBM5 (≥ 20Hi stacks).
 • Note: HBM manufacturers are currently considering using Wafer-to-Wafer (W2W) hybrid bonding to stack the firstDRAM layer and the
 base/logic layer.The firsttechnologies using this approach are likelyto be HBM4E/HBM5 (≥16Hi),particularly in customized HBM solutions.

 Source: Tokyo Electron, 2025
 CMOS Bonding for Next-Generation DRAM Technologies
 • DRAM manufacturers are also expected to introduce CMOS Bonded Array (CBA) architectures following an approach likethe one developed by YMTC for itsXtackingTM 3D NAND
 technology. Peripheral circuits and DRAM arrays are manufactured on different wafers, which are then stacked atop each other using wafer-to-wafer bonding.
 • Due to stringent pitch/alignment requirements (<200nm), CBA DRAM isexpected to be implemented with fusion bonding, which is likelyto have a higher impact on cost than
 hybrid bonding.
 • Leading IDMs are expected to ramp up CBA-DRAM production with wafer-to-wafer stacking approaches from the 0a technology process (~2029). The use of CBA DRAM is
 expected to improve the DRAM-array efficiency,triggering further density growth in terms of bits per wafer. Multiple players consider CBA the next step in the DRAM scaling
 roadmap and a necessary development towards 3D DRAM (more details in the “3D DRAM” chapter).


 *Note: In March 2024, JEDEC relaxed the HBM4 thickness requirements from 720µm to
 775µm, enabling the use of TSV/microbumps for manufacturing 16Hi products
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 164
 2025-04-08 01:51

## 第 165 页

BONDING TECHNOLOGIES FOR HBM – OVERVIEW


 • Microbumping technology is widely used in HBM devices. The three primary HBM manufacturers currently utilize stacking architectures, such as
 Thermocompression with Non-Conductive Film (TC-NCF), Mass Reflow-Molded Underfill (MR-MUF), or Advanced MR-MUF for their HBM3 and HBM3E
 products which feature 8Hi or 12Hi stacks.
 • SK hynix started using MR-MUF from the HBM2E generation, while Samsung and Micron continued using TC-NCF. MR-MUF involves placing multiple dies on
 the lower substrate and bonding them through reflow, and then simultaneously fillingthe gap between the chips/substrate with a mold material. Compared
 to TC-NCF – where film-type material is applied after each chip is stacked – MR-MUF is claimed to be a more efficient process, offering effective heat
 dissipation.
 • While 16Hi configurations may stillutilizeMR-MUF or TC-NCF methods with thin DRAM dies (30-50µm), itis expected that stacks of 20Hi or greater will
 require the adoption of hybrid bonding technology to overcome limitations related to stack height, I/O density, and thermal management.


 Advanced MR-MUF

 To address challenges in stacking more
 layers,such asincreased chip warpage and
 heat generation, SK hynix introduced chip
 control technology, applying a momentary
 burst of high heat to each chip during
 stacking to fuse bumps and prevent
 warpage. Additionally, a new generation of
 epoxy molding compound with 1.6 times
 greater thermal conductivity was utilized,
 further enhancing heat dissipation. These
 advancements enabled the production of
 12-layerHBM3/HBM3E products.

 Less sensitive to dies warpage High productivity, low thermal resistivity Source: SK hynix

 Low productivity, high thermal resistivity More sensitive to chip warpage, narrow gap fill


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 165
 2025-04-08 01:51

## 第 166 页

BONDING TECHNOLOGIES FOR HBM – KEY PLAYERS
Why is equipment vendor collaboration useful?


 Die handling Wafer / frame Die handling Wafer / frame Die handling Wafer / frame
 and bonding handling and and bonding handling and and bonding handling and
 processing processing processing


 W2W bonding Cluster W2W bonding Cluster W2W bonding Cluster
 automation automation automation


 D2W and W2W bonding systems are available as standalone
 Die-to-Wafer (D2W) and Wafer-to-Wafer (W2W) units or integrated clusters. SET brings die handling
 Die-to-Wafer (D2W) cluster: Besi brings die cluster machines can be standalone: ASM PT brings capabilities, SUSS MicroTec brings wafer handling capabilities,
 handling capabilities and Applied Materials brings die handling capabilities and EV Group brings wafer and wafer bonder. Companies offer all-rounder solutions
 wafer handling capabilities handling capabilities and wafer bonder. (W2W, D2W, c-D2W).


 Die handling Wafer /frame Die handling Wafer /frame Die handling Wafer /frame
 and bonding handling and and bonding handling and and bonding handling and
 processing processing processing


 W2W Cluster W2W ? Cluster W2W ? Cluster
 bonding automation bonding automation bonding automation


 D2W and W2W bonding systems are available as
 standalone units or integrated clusters. Other possible collaborations can be between Korean vendors for Other possible collaborations in Mainland China might be
 Shibaura brings die handling capabilities, local chipmakers. SEMES, a provider of wafer and die processing between new entrants in the W2W bonder space – Piotech or
 wafer/frame handling and processing as well as equipment, might cooperate with local die bonder providers, established W2W bonder supplier U-precision and local
 automation. TEL brings wafer handling capabilities Hanmi or Hanwha. Another possibility is that SEMES will develop its supplier ACCURACY
 own D2W HBI bonder. Finally, W2W bonding might be done in-
 and wafer bonding. house by local chipmakers.

 huguodong@cmbchina.com More details in the forthcoming “High-End Performance Packaging 2025” report by Yole Group Next-Generation DRAM 2025 | Report | www.yolegroup.com 166
 2025-04-08 01:51

## 第 167 页

Memory-logic heterogenous integration


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com167
 2025-04-08 01:51

## 第 168 页

HBM-LOGIC INTEGRATION – ADVANCED PACKAGING APPROACHES

 Example: Chip-on-Wafer-on-Substrate (CoWoS) by TSMC

 Advanced Packaging for HBM-(x)PU Integration


 Embedded Si Bridge Si Interposer


 Embedded in Interposer die
 mold Embedded in +
 compound IC substrate TSVs + Microbumps + FC Bumps
 +
 IC substrate Example: I-Cube by Samsung


 Si Bridge EMIB Active Passive


 Co-EMIB
 TSMC: InFO-LSI, TSMC:
 CoWoS-L Intel: • CoWoS-S
 Samsung: I-CubeE e.g., Sapphire Samsung:
 ASE: FoCoS-Bridge Rapids • H-Cube
 SPIL: FOEB • I-CubeS
 JCET: XDFOI-EB
 Amkor: S-Connect Intel: UMC
 e.g., Ponte Vecchio

 Non-Exhaustive List!


 huguodong@cmbchina.com Source: “High-End Performance Packaging 2024” Report by Yole Next-Generation DRAM 2025 | Report | www.yolegroup.com 168
 2025-04-08 01:51

## 第 169 页

HBM-LOGIC INTEGRATION – SAMSUNG’S I-CUBE AND H-CUBE
2.5D Interposer-Based Packaging Technology


 I-CUBE4/ I-CUBE S I-Cube4 Package Structure - Source: Samsung

 • Mold-free structure to improve
 efficiency of heat removal
 • Enhanced yield using a pre-
 screening test to filter out
 defective products during the
 fabrication process
 • Reduced costs & shorter
 turnaround time
 • Interposer material & thickness H-Cube Package Structure Concept - Source: Samsung
 configuration to reduce
 warpage & thermal expansion
 • Improved reliability 2.5D Package
 Logic Chip
 H-CUBE
 • Improved reliability 6 HBMs

 • Minimized single loss or Si Interposer
 distortion Fine-Pitch
 • Lower cost Substrate

 HDI Substrate


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 169
 2025-04-08 01:51

## 第 170 页

HBM-LOGIC INTEGRATION – NVIDIA & TSMC
From TSMC’s CoWoS-S to CoWoS-L for greater reticle size (HPC & AI)


 • The Blackwell B100 GPU was released in late2024 and is the firstNVIDIA product touse a chiplet design. Itcombines two GPU chips and eight HBM3e memory stacks and
 uses TSMC’s 4NP process node. This design ispaired with TSMC’s CoWoS-L packaging technology. Therefore, itis the firstGPU from Nvidia to use a chiplet approach and
 CoWoS-L packaging technology.

 • In contrast, the Hopper H200, released earlier the same year and built on TSMC’s N4 node, continues NVIDIA’s use of a monolithic design combined with CoWoS-S
 packaging. Itfeatures six HBM3e memory stacks, delivering 2.4 times the speed of the A100 and fasterinference performance than itspredecessor, the H100.

 • The successor to the B100 isexpected to be the B200 and B300 in 2025, representing an improved Blackwell version that utilizes the same packaging technology (CoWoS-
 L).

 • The next step in NVIDIA’s future AI GPU roadmap includes Rubin R100, which isexpected to be launched in late2025 or early 2026, incorporating HBM4 and using CoWoS-
 L packaging technology from TSMC.
 CoWoS-S package architecture


 TSMC’s CoWoS-S
 Die HBM packaging used for
 Hopper GPU where a
 SILICON INTERPOSER passive Si Interposer is
 used to connect the
 IC Substrate GPU and HBM dies.


 Nvidia H100 Source: TSMC
 CoWoS-L package architecture TSMC’s CoWoS-L

 packaging is used for
 the Blackwell GPU
 where silicon bridge
 (LSI) is added to mold-
 interposer to connect B200 is set up to deliver 3 times more AI
 the GPU chiplets and training performance than the H100.
 the HBM dies. Source: Nvidia

 Nvidia B100
 Source: TSMC

 huguodong@cmbchina.com More details in the forthcoming “High-End Performance Packaging 2025” report by Yole GroupNext-Generation DRAM 2025 | Report | www.yolegroup.com 170
 2025-04-08 01:51

## 第 171 页

DRAM-LOGIC INTEGRATION – DEVICE TRENDS
Bufferless / Interposer-less HBM and Cache DRAM


 • The shiftto heterogeneous integration and advanced packaging has triggered new developments in computing devices to leverage the benefits of processing closer
 to the source of data. For instance, Samsung publicly discussed bufferless HBM and SK hynix Interposer-less HBM.
 • In 2024, Samsung and TSMC announced a collaboration to develop bufferless HBM4 memory chips, marking their firstpartnership in the AI chip segment. ​Traditional
 HBM designs incorporate buffers to manage electrical issues and voltage distribution. The bufferless HBM4 architecture aims toeliminate these buffers, resulting in
 higher integration and reduced power consumption.
 • Intel and SK Hynix have been investigating glass substrates as a promising alternative to silicon interposers. Additionally, SK hynix has been recruiting logic
 semiconductor design engineers since late 2023, with the aim of integrating HBM directlyonto processors. This strategy could further streamline memory integration
 and enhance performance by removing the interposer layer.
 • Samsung and Intelhave been jointlydeveloping “cache DRAM” to go beyond HBM solutions in terms oflatency and power efficiency.Unlike HBM, cache DRAM is
 stacked directlyon top of the processor. Intel isexpected to adopt cache DRAM for itsprocessors – likelyan answer to AMD 3D V-Cache – and could offer itto third
 parties as afoundry service.Compared tobufferless HBM – forwhich Samsung has already obtained customer engagement – cache DRAM islikelyto be a long-term
 project forthe Korean company.


 Source: “Heterogeneous Integration Platform forNext Generation Computing (Beyond Source: SK hynix, New Opportunities with HBM4/4E

 huguodong@cmbchina.com Moore)”,SamsungElectronics,February2023 Next-Generation DRAM 2025 | Report | www.yolegroup.com 171
 2025-04-08 01:51

## 第 172 页

DRAM-LOGIC INTEGRATION – DEVICE TRENDS
Winbond’s Customized Ultra-Bandwidth Element (CUBE) Technology

 CUBE Device Architecture
 • In September 2023, Winbond officiallyintroduced itsCUBE architecture for
 edge AI computing, targeting specific markets such as wearable devices,
 edge servers,surveillance equipment, and advanced driver assistance systems
 (ADAS).
 • The technical requirements for AI computing depend strongly on the
 targeted application (edge or cloud). The edge-computing space served by
 Winbond does not require high-density leading-edge DRAM but needs CUBE by Winbond
 bandwidth levelsin the range of 32-256 GB/s, as illustratedin the chart below.
 • CUBE devices are currently manufactured with 1-8Gb DRAM dies based on
 Winbond’s D20 process (D16 from 2025).

 Memory Density (Gb/package) and Bandwidth (GB/s) Requirements


 • CUBE is a cost-effective, power-efficient, and compact solution for
 edge applications. According to Winbond, CUBE architecture can
 enhance the performance offront-end 3D structures such as chip-
 on-wafer (CoW) and wafer-on-wafer (WoW), as well as back-end
 2.5D/3D chip on Si-interposer on the substrate and fan-out solutions.
 • The device includes TSVs that further enhance performance,
 improving signal integrity,power integrity, and heat dissipation if
 SoC ison the top ofthe die and CUBE on the bottom die.
 • Winbond has also been engaging with partner companies to
 establish a 3DCaaS (3D CUBE-as-a-service) platform, which will
 leverage CUBE capabilitiesin product designs.


 huguodong@cmbchina.com Source: Winbond DRAM Promotion Flyer 2023 Next-Generation DRAM 2025 | Report | www.yolegroup.com172
 2025-04-08 01:51

## 第 173 页

DRAM-LOGIC INTEGRATION – EMERGING RESEARCH DEVICES
Bumpless Build Cube 3D (BBCube 3D)


 • Researchers atthe Tokyo Instituteof Technology developed a form of stacked DRAM called BBCube 3D – Device Architecture

 Bumpless Build Cube 3D (BBCube 3D),which relieson TSVs to connect theDRAM dies and
 does not use microbumps toconnect the differentlayers.

 • This bumpless wafer-on-wafer (WoW) process consists ofbonding, wafer thinning, and
 then the formation ofTSV interconnects. A permanent adhesive layer with athickness of1
 to5 μm was used forwafer stacking.

 • Fulldetails available here: “Review of Bumpless Build Cube (BBCube) Using Wafer-on-
 Wafer (WOW) and Chip-on-Wafer (COW) for Tera-Scale Three-Dimensional Integration
 (3DI)”,Electronics2022,11(2),236.Link tothe article.

 • The BBCube 3D approach isclaimed to enable better cooling, as the TSVs can channel
 heat from the DRAM dies down into the substrate. Moreover, bumpless interconnect
 technology can improve the transmission speed – thanks to short TSV connections – and
 increase the density ofTSVs per chip due to the finerTSV pitch and the lower impedance
 ofbumpless TSV interconnects. Comparison with other technologies

 • Note: atthisstage, we are not aware ofany plans forthe commercialization of BBCube 3D.

 Chip-on-Chip vs. Bumpless Wafer-on-Wafer processes


 huguodong@cmbchina.com Source: Tokyo Institute of Technology Next-Generation DRAM 2025 | Report | www.yolegroup.com 173
 2025-04-08 01:51

## 第 174 页

DRAM-LOGIC INTEGRATION – TEARDOWN OF A COMMERCIAL PRODUCTS
Jasminer X4-Q Mining ASIC with Direct bond interconnect (DBI) Process


 • SunLune introduced an innovative ASIC chip based on a 3D IC technology platform. This incorporates a logicdie and DRAM die bonded
 together through copper-to-copper hybrid bonding to increase chip bandwidth. More detailsare in the chapter “China Memory Business”.
 • With itsleading 3D integrated high-throughput ASIC, SunLune designed this chip specificallyfor the crypto world. This chip enables high
 throughput, high computing power, and low power consumption incrypto mining applications thanks toitsnew 3D IC architecture.


 DRAM Die:
 • Process:
 • 2y (~25nm)


 Logic die & Logic die &
 DRAM die DRAM die


 LogicDie:
 • Process:
 • CMOS 40 nm
 • Placement: bumped topackage substrate


 Source: “Jasminer X4-Q Mining ASIC with DBI” report by Yole Group
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 174
 2025-04-08 01:51

## 第 175 页

3D DRAM


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 175
 2025-04-08 01:51

## 第 176 页

PREMISE – A LONG JOURNEY TO 3D DRAM… but the “peak” is on the horizon!


 • Multiple solutions willenable continuous planar DRAM • Less litho
 scaling over thenext 8–9 years. • More deposition …...
 • Starting with the 0a node (~2029), some DRAM 4F2 + CBA* 3D
 manufacturers are expected toadopt a 4F² CMOS Bonded • More etching
 Array (CBA) architecture. Thisapproach aims to achieve Vertical Transistors 1yyL
 increased density and enhanced performance, enabling
 scaling forat leasttwo subsequent nodes. Advanced logic
 technologies, such as FinFET transistorsintegrated onto
 dedicated CMOS wafers,willbe instrumental in sustaining • More EUV
 ongoing performance improvements after2030.
 • However, ifmanufacturing costs and yield challenges • FinFET peri. 1xxL

 make high-volume 4F² DRAM production economically …
 prohibitive,memory makers may extend 6F² scaling as far 0c
 as possible. This extended scaling would leverage …
 additional EUV layers and potentiallyintroduce High-NA
 EUV lithography. In the long term (post-2030), CBA 2033-2034
 technology isanticipated to become essential tomaintain
 density and performance progression. 0c
 • Overall,planar DRAM scaling islikelyto persistuntil the 0b
 0c/0d nodes. Beyond this point, the transition to a 0a
 challenging but necessary 3D architecture willbegin.
 2029 6F2 + CBA*
 0a 0b • FinFET peri.
 2D ? 1e
 2025 1d 6F2 • More EVU
 1c • High-NA EUV


 huguodong@cmbchina.com *CBA: CMOS Bonded Array Next-Generation DRAM 2025 | Report | www.yolegroup.com 176
 2025-04-08 01:51

## 第 177 页

3D DRAM – INTRODUCTION


 • Since the 1970s, DRAM scaling has been successfully achieved through the continuous miniaturization of
 the DRAM-cell building blocks, namely transistors and capacitors. However, planar DRAM scaling has
 significantly slowed down in the lastdecade and is expected to hit insurmountable barriers at technology
 nodes <10nm, such as process and reliabilitychallenges (e.g.,narrow sensing margins) and the need for
 ultra-high aspect ratio (HAR) capacitors.

 • Following the example of NAND flash technology – which made a pivotal and successful transition from
 2D to 3D NAND – DRAM technology is also expected to go 3D to enable further scaling of the bitdensity
 on a die by increasing the number ofDRAM-cell layers.

 • Note: 3D DRAM isa different concept from HBM, which is produced by stacking multiple dies atop each
 other. Here, the term 3D refers to a multi-layer configuration that can count on a single lithographic and
 etching step to pattern many layers as opposed to the sequential integration where each layer is
 processed separately before bonding.

 • Unlike NAND flash, DRAM is a high-speed memory technology that requires the use of high-mobility
 channel materials. DRAM has less flexibilitybecause the memory cellsare constantly being used, and new
 material and process innovations are required to enable high-mobility, ultra-low defect channels in 3D
 architectures.

 • At this stage, all leading DRAM companies – including CXMT – are exploring multiple pathways to
 implement 3D-DRAM, among which are 1T-1C cells with horizontal capacitors and other capacitor-less
 options, such as gain cells (2T0C) or 1T-DRAM (e.g.,based on the floating-body effect).

 • As oftoday, R&D efforts are primarily centered on 1T-1C cells with horizontal capacitors, despite significant
 technical challenges (detailed insubsequent slides).Major DRAM manufacturers are actively pursuing this
 approach. At VLSI 2024, SK hynix presented itslatest advancements in 5-layer 3D DRAM technology.
 Samsung is reportedly developing a 16-layer architecture (VS-CAT), while Micron focuses on an 8-layer
 model. Prototypes featuring even higher layer counts are rumored to exist already.
 Source: Neo Semiconductor
 • Capacitor-less DRAM cellsand other cell architectures are also under intense investigation, but the type of
 cell to be used has not yet been decided. Samsung Electronics and SK hynix stated their expectations that
 a “more clear development direction” on 3D DRAM will emerge in the next 2 years. Source: Applied Materials


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 177
 2025-04-08 01:51

## 第 178 页

3D DRAM OVERVIEW – CHALLENGES AND PLAYERS
The 2D-to-3D transition is expected to be more challenging than in the case of NAND


 Many challenges need to be addressed forthe successful implementation of 3D DRAM:
 • DRAM capacitors are too long and are not convenient to be oriented in-plane,and capacitor-less bitcells have been tough to build.
 Several new bit cellsarein the works but are not yet mature – e.g.,cell-flipping,floatingbodies,and gain cells.

 • Building acapacitor suitable forstacking while minimizing interference with adjacent bit cells.

 • The back-end-of-line (BEOL) requires low-temperature processing (note:stacked layers are processed inthe BEOL).

 • Different from NAND, DRAM requires low latency and virtuallyinfiniteendurance. These characteristics cannot be compromised.

 Schematics of the cell-flipping approach List of key players tackling 3D DRAM challenges

 Source: Monolithic 3D


 Non-exhaustive list!


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 178
 2025-04-08 01:51

## 第 179 页

CHALLENGES FOR 3D DRAM WITH HORIZONTAL CAPACITORS


 • While inconventional DRAM, vertically-standing capacitors occupy minimal chip footprint,in 3D DRAM, the horizontal capacitor consumes a
 significant portion of the chip area. Horizontal capacitors must be shortened to increase the quantity ofbits per unit area.
 • 3D DRAM architectures with more than 100 layers of horizontal capacitor cells are expected to be needed tomeet the density levelof 2D DRAM
 at the 0b/0c nodes (>2032). Despite the industry having already gained significant know-how with 3D NAND, itis extremely challenging to
 implement the first1xxL 3D DRAM generation (i.e.,>100layers)with yields sufficientfor mass production.
 • The natural move to advance DRAM scaling by putting the 2D DRAM components on their side and stacking them also presents significant
 manufacturing challenges.
 • The horizontal orientation necessitates lateral etching, which is challenging because recess sizes vary greatly (lateralcavities must
 Given the be etched and filledto varying depths inthe SiActive Area).
 complex • Different materials are needed in the stack etching and fillingprocess, making fabrication difficult.Moreover, integration challenges
 challenges emerge when trying to connect the various 3D components (e.g.,long cylindrical capacitors and access transistors).
associated with • Considering allthe complex challenges listed above –which need to be optimally solved for implementing high-performance DRAM devices –
1T-1C 3D DRAM, several companies are exploring alternative solutions to implementing 3D DRAM. Currently, most efforts are focused on the development of
 capacitorless capacitorless DRAM cells.

architectures are Overview of technical proposals for capacitor-less DRAM cells
 also being
 explored to
 enable the
vertical stacking
 of DRAM cells.


 Source: Macronix, IEDM 2022
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 179
 2025-04-08 01:51

## 第 180 页

3D DRAM – BUSINESS OVERVIEW


 • 2D DRAM scaling islikely to persist until the 0c/0d nodes (2033-2034). Beyond this point, the transition to a challenging but necessary 3D
 architecture willbe necessary.

 • 3D DRAM isbeing considered by allDRAM manufacturers as a potential solution forlong-term DRAM scaling atsub-10nm nodes.
 • Top memory makers – such as Samsung, SK hynix, and Micron – willlikely invest more and more resources in the coming years, and
 we expect new solutions willbe found, no matter how complex the technical challenges are.
 • Equipment suppliers – such as Applied Materials, Tokyo Electron, and Lam Research – have also begun to develop solutions related to 3D
 DRAM. Significant R&D work has been carried out to develop suitable equipment and processes – deposition and etching – for implementing
 3D architectures, as well as new process solutions to deposit high-mobility materials through epitaxial growth, PVD, and ALD. 3D DRAM isalso
 expected torequire advanced gap-fill,selective removal, and advanced doping capabilities.
 • The transition from 2D to 3D DRAM willdrive significant changes within the industry, paralleling the evolution recently observed in NAND flash
 technology. Like the shift toward 3D NAND, the adoption of 3D DRAM will demand substantial investments to establish and scale the new
 manufacturing processes.
 • Extensive retooling will be critical,particularly increasing expenditures for deposition systems such as Atomic Layer Deposition (ALD)
 and Plasma-Enhanced Chemical Vapor Deposition (PE-CVD), as well as high-aspect-ratio (HAR) etching equipment. Collectively,
 deposition and etching systems could account forover 70% of the total DRAM equipment investments.
 • Furthermore, 3D DRAM will leverage more “relaxed” lithography nodes around 20nm, eliminating the need for costly EUV
 lithography systems.
 • 3D DRAM could be favorable for Chinese memory companies that, at this stage, have no access to leading-edge equipment (e.g.,EUV
 lithography) due to U.S. trade restrictions.The availability of new 3D-DRAM manufacturing schemes could bring China back into the race and
 allow itto close the technology gap with global suppliers.
 • Ifthe U.S. restrictions hamper DRAM planar shrinking, then the only way for China to succeed isto build 3D structures. For this reason, multiple
 leading Chinese companies are intensely exploring the 3D pathway: both CXMT and the NAND company YMTC are active In this area (note:
 YMTC’s 3D NAND know-how and XtackingTM technology could become key enablers for Chinese 3D DRAM); Huawei is also developing 3D
 DRAM through itsdesign center in Yokohama, Japan.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 180
 2025-04-08 01:51

## 第 181 页

R&D activities for 3D DRAM


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 181
 2025-04-08 01:51

## 第 182 页

SAMSUNG’S VERTICALLY STACKED DRAM (VS-DRAM)


• At the 2023 IEEE Symposium on VLSI Technology and Circuits, Samsung presented a work entitled “Ongoing Evolution ofDRAM Scaling via Third Dimension –
 Vertically Stacked DRAM” .Here, 1T1C DRAM cellsare flipped by 90 degrees and then multiple celllayers are stacked on the same wafer.
• Unlike NAND, DRAM needs high-mobility transistor channels based on single-crystal silicon, so the layer-to-layer materials used to implement the 3D
 architecture are different.For itsVS-DRAM technology, Samsung employs an epitaxially-grown Si/SiGe super-lattice structure (SiGe isthe sacrificiallayer).
• Moreover, DRAM requires a seed layer forthe growth of the epitaxial silicon channel. For thisreason, combined with the need for optimizing the cell-area
 efficiency, Samsung decided to adopt a wafer-to-wafer hybrid bonding approach like YMTC’s XtackingTM: the DRAM-cell array and the periphery circuit are
 fabricated on two different wafers and then combined using wafer-to-wafer hybrid bonding technology.


 Two different orientations are possible Stacking cell-array and periphery circuit via hybrid bonding

 Horizontal WL, Vertical BL
 Horizontal BL, Vertical WL


 Source: IEEE Symposium on VLSI Technology and Circuits, Samsung R&D Center
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 182
 2025-04-08 01:51

## 第 183 页

SK HYNIX’ 3D DRAM TECHNOLOGY FOR THE NEXT DECADE


 • At IMW 2024, SK hynix introduced 3D DRAM with verticalbit line(BL) architecture and demonstrated fullchip integration for5-layer 1T1C 3D DRAM through a
 novel process integration scheme based on Si/SiGe sacrificialmultilayersand a hybrid wafer bonding technique.


 Source: SK hynix, slide presented at IEDM 2024

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 183
 2025-04-08 01:51

## 第 184 页

CXMT’S 3D STACKABLE DRAM TECHNOLOGY
 3D DRAM technology based on flipping and stacking 1T-1C cells


 • At the 2023 IEEE International Memory Workshop, CXMT presented a research work entitled “A 3D Stackable 1T-1C DRAM: Architecture, Process
 Integration and Circuit Simulation”. CXMT’s 3D DRAM technology isbased on flipping and stacking 1T-1C cells with vertical-channel access transistors for
 acompact unit cellarea (4F2).

 • The authors described a possible integration scheme and process flow that make use ofepitaxially-grown Si/SiGe layers(likeSamsung's’ VS-DRAM).
 • They estimate that 61 layers of horizontal DRAM cells are needed to match the bitdensity of future 0α DRAM technology based on conventional 6F2 cells.
 • Circuit simulation studies showed that the wordline structure of 3D DRAM has a clear advantage in terms of RC delay and coupling noise with the
 potential forDRAM core timing optimization.
 • Note: Wafer-to-wafer hybrid bonding isused to stack the periphery circuit and the DRAM-array wafers using an approach similarto YMTC’s XtackingTM.


 3D DRAM array architecture Bird’s eye view of Xtacking-like 3D DRAM Equivalent Node by Layer Number


 0α 2D DRAM
 ~
 61-layer 3D DRAM


 Source: 2023 IEEE International Memory Workshop, ChangXin Memory
 huguodong@cmbchina.com Technologies & Beijing Superstring Academy of Memory Next-Generation DRAM 2025 | Report | www.yolegroup.com 184
 2025-04-08 01:51

## 第 185 页

CXMT’S 3D STACKABLE DRAM TECHNOLOGY
Example of a simplified process flow for manufacturing 3D DRAM with flipped 1T-1C cells


 Epitaxial deposition of Si/SiGe Patterning and etching Formation of SiN and low-k Removal of SiGe
 multilayers on Si substrate (RIE) of active regions materials frames sacrificial layers
 Source: 2023 IEEE
 International Memory
 Workshop

 ChangXin Memory
 Technologies &
 Beijing Superstring
 Academy of Memory
 Sacrificial layer Capacitor area opening BL and transistor formation
 (low-k) removal and TiN deposition (GAA or dual gate) Oxide and SiN deposition
 (bottom electrode)

 Notes

 • 3D DRAM technology will relieve the
 challenge of lithography, limiting the
 use of advanced lithography systems
 based on EUV light.

 Bottom electrode Filling the removed Capacitor opening High-k and top • However, it willsignificantly increase the
 sidewall removal sacrificial-layer area with SiN electrodes deposition number of low-throughput deposition
 steps (e.g.,PECVD epitaxy and ALD), as
 well as high-aspect-ratio (HAR) etching.

 • The number of criticallithography and
 etch processes can be shared for
 multiple layers, which is favorable for
 reducing the cost per bit.

 Source: CXMT & Beijing Superstring Academy of Memory
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 185
 2025-04-08 01:51

## 第 186 页

LAM RESEARCH’S SIMULATION STUDIES
A possible way to build 3D DRAM with 1T-1C cells and horizontal capacitors


 • In a recent blog articleentitled “3D DRAM IsComing. Here’s a Possible Way to Build It”(July 14th,2023), Lam Research presented the results ofa study conducted with
 their SEMulator3D computer software, which allows itto fabricate devices virtuallyby mimicking actual wafer fabrication processes.

 • In its blog article,Lam investigates a 3D DRAM architecture based on a 1T-1C cellwith horizontal capacitors and proposes a set of design changes to solve scaling and
 layer-stacking challenges and enable further capacitor and transistor shrinking. The company also lays down the process requirements that enable the fabrication of
 their proposed design.
 • The firstimplementation consists of28 layers and would be two nodes (~13×10 µm2 per bit) ahead of 1zDRAM technology. Various aspects are analyzed below:

 1. Architecture –A listofdesign changes isdescribed in the schematics below:


 2. Connections – Lam suggests a set ofnovel approaches, among which isa stack ofgate-all-around (GAA) nanosheet silicon transistors, astack of bitlinelayers in between
 two rows of transistors,vertical wordlines, multibridge connections, as well as an array ofhorizontal MIM (metal-isolation-metal) capacitors.

 3. Via arrays – To avoid the limitations of a staircase construction as used in 3D NAND, Lam inserts the contact inside the memory cell by introducing an array of vias that
 goes through the silicon stack and can stop ateach level (one via per level).

 4. Process requirements – Lam’s experiments result in very aggressive specifications to the point that “etch and deposition experts may be shocked atwhat our simulations
 propose” (source: Lam’s blog). For example, trenches with 30nm criticaldimensions and 2µm depth need to be etched and filledin such a 3D structure.

 • Overall, 3D DRAM is acutting-edge design that demands unprecedented processes. It’sthe only way to move from concept to prototype.

 huguodong@cmbchina.com Source: Lam Research Next-Generation DRAM 2025 | Report | www.yolegroup.com 186
 2025-04-08 01:51

## 第 187 页

CAPACITOR-LESS DRAM – REVIEW OF A HISTORICAL ATTEMPT
Zero Capacitor RAM (Z-RAM) technology by Innovative Silicon (2003-2010)


 • Z-RAM is a“Zero Capacitor” high-density memory technology that leverages the floating body effect and makes use of siliconon insulator(SOI) substrates.
 • Z-RAM was developed by Innovative Silicon (ISi),aventure-funded start-up company founded by chief scientist Serguei Okhonin and chairman and CTO
 Pierre Fazan.
 • Since 2003, the company has closed three funding rounds totaling $47M, received dozens ofpatents on the technology, developed testchips in multiple
 technologies from 90nm to 32nm, and established global R&D, engineering, and support centers in Europe, Asia, and North America.
 • Z-RAM memory technology has been licensed by hynix Semiconductor for use in itsDRAM chips and by AMD foruse in microprocessors.
 • The use of SOI substrates was expected to significantly increase the cost of Z-RAM over conventional DRAM, which limited the adoption ofthe technology
 (note:an SOI substrate can be ~5 times more expensive than bulk silicon substrates,leading to more than 15% cost increase fora complete DRAM wafer).
 • InMarch 2010, Innovative Silicon announced that itwould develop a second generation of Z-RAM memory based on CMOS technology that would be much
 cheaper to produce, but soon after the announcement, the company went bankrupt. Itspatents were transferred toMicron Technology.


 Z-RAM working principle

 • The functionality of the first-generation ZRAM is based on
 the ability to store the majority of the carriers in the
 floating body of the SOI transistor.

 • The carriers are generated by impact ionization caused by
 the minority carriers close to the drain.

 • The threshold voltage ismodified because of the charge
 accumulated in the body, thus guaranteeing the two
 Suggested reading: “Overview and Future Challenges of Capacitor-less DRAM states of a MOSFET channel, open and closed, fora gate
 Technologies for High Density Memory Applications” by Pierre Fazan, 2009 voltage chosen between the two thresholds.
 InternationalConference on SolidState Devices and Materials


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 187
 2025-04-08 01:51

## 第 188 页

CAPACITOR-LESS DRAM BASED ON 2T-0C GAIN CELLS
 2T-0C cell structure
 • A 2T-0C gain cell isa capacitor-less DRAM cellbased on two transistors: a write transistor that is used to write the bitline (BL)
 signal into the storage node (SN). Italso acts as the gate of a read transistor, whose states can then be determined by sensing
 the current ofthe BL.

 • This is a relatively simple concept that was proposed in the early 2010s for eDRAM applications. However, due to the non-
 negligible leakage from the Si-based write transistor, the SN node voltage can only be retained for110 μs, failing to meet the
 64 ms refresh time criterion.

 • For this reason, such a design has not received widespread attention until recently, with the introduction of novel low- 20F2
 leakage transistors.

 • imec has been working on 2T-OC gain cells based on indium-gallium-zinc-oxide (IGZO) thin-film transistors (TFT)
 with extremely low off-current (Ioff)and high electron mobility (retention > 1000s and endurance >1011).According to
 imec, IGZO DRAM cellscan be fabricated at a relatively low temperature; they are compatible with BEOL processing
 and could, therefore, enable the stacking ofmultiple DRAM cells inthe back-end of the line. CAA IGZO DRAM

 • Despite being more convenient than the 1T-1C DRAM cell with a horizontal capacitor, the 2T-0C bit-cellsize has a
 relatively large footprint of about 20F2 in a planar FET structure. The Institute of Microelectronics of the Chinese
 Academy of Sciences (IMECAS), in collaboration with a Huawei-Heisi team, proposed research work on “Novel
 Vertical Channel-All-Around(CAA) IGZO FETs for2T0C DRAM with High Density beyond 4F2 by Monolithic Stacking”.
 More recently, at VLSI 2024, Samsung demonstrated 2T0C IGZO gain cellsbased on one gate-around (GA) FET and
 one channel-around (CA) FET fora bit-cost scalable 3D array process. More details here.

 • At VLSI 2023, SK hynix demonstrated a crystalline IGZO transistor with high thermal stability for memory
 applications. Due to itswell-controlled crystalline structure, the device can be processed at temperatures above 550
 °C and remains immune to the hydrogen atmosphere, showing a higher current (Ion) than amorphous IGZO.

 • Remarks – Although the 2T-0C gain cell isattractive due to itsrelative simplicity, significant challenges need to be addressed
 for the implementation ofhigh-density DRAM. Among them: (1)the integration of IGZO materials inhigh-volume production
 lines, and (2)device reliabilityconcerns due to strong signal coupling of SN node and read disturbances. (3)Moreover, the 3D- Source: IMECAS
 stacking capability of thisarchitecture islimited; notice that multiple layers of 2T-0C gain cellsare embedded in the BEOL and
 require multiple metal lines and multiple process steps for each layer.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 188
 2025-04-08 01:51

## 第 189 页

INDIUM-GALLIUM-ZINC-OXIDE (IGZO) TRANSISTORS FOR HIGH-DENSITY DRAM


 • In 2024, many R&D works focused on the implementation of high-density DRAM devices leveraging the unique features of Indium-Gallium-Zinc-Oxide (IGZO), among
 which are high ON current and ultra-low leakage. The successful implementation of IGZO-based transistors would pave the way to high-density DRAM, including 3D
 DRAM architectures.
 • In 2024, Samsung presented various relevant research work focusing on the use ofIGZO:
 • IGZO gain cells based on one gate-around FET and one channel-around FET for bit-cost scalable 3D DRAM (VLSI 2024, link);
 • IGZO-based DRAM cellarchitectures, including VCT, vertically stacked cellarray transistor (VS-CAT), and 2T0C, as well as recent advances in key technologies,
 including IGZO deposition and gate stack engineering (IMW 2024, link).
 • At IEDM 2024, IMECAS (China) proposed and experimentally demonstrated a 4F2 vertical-channel IGZO multi-bit dual-gate (DG) 2T0C DRAM, where the write and read
 transistors are integrated simultaneously by adopting a self-aligned single-step (SASS) process. In a separate paper in collaboration with Beijing Superstring, IMECAS
 demonstrated a 4-layer stacked Planar Channel-All-Around (P-CAA) IGZO FET forhigh-density 1T1C 3D DRAM. At the same conference, Kioxia and Nanya demonstrated
 a promising 4F2 gate-all-around (GAA) Oxide-semiconductor Channel Transistor DRAM (OCTRAM) with IGZO Vertical Channel Transistors (VCT). A 275Mbit OCTRAM
 array was fabricated with WL 54nm / BL 63nm pitches and operated successfully.
 • Overall, IGZO isemerging as a promising transistor material for high-density DRAM, including 3D DRAM architectures. However, itpresents significant integration
 challenges as uniformity on the wafer scale remains difficultto achieve with CVD approaches. Optimizing IGZO for display technologies required roughly a decade, and
 similar complexities are anticipated when adapting IGZO forhigh-volume DRAM manufacturing.


 Source: Kioxia and Nanya, presented at IEDM 2024


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 189
 2025-04-08 01:51

## 第 190 页

UNISANTIS ELECTRONICS
Dynamic Flash Memory (DFM)


 • Unisantis Electronics isa Singapore- and Japan-based company founded by NAND inventor Dr. Fujio Masuoka in 2004. Between 2004 and 2007, Professor
 Masuoka and his team investigated allaspects ofthree-dimensional semiconductors through sophisticated simulation techniques and laidthe foundation to
 produce prototypes in a semiconductor facility.
 • Unisantis’ team focuses on capacitor-less DRAM, which has been studied extensively for more than three decades(1-2).However, various reliability issues
 hampered its adoption and productization. To address such challenges, Dr. Koji Sakui and Dr. Nozomu Harada from Unisantis introduced a new type of
 memory device, namely Dynamic Flash Memory (DFM).3

 • DFM was unveiled for the firsttime at the 2021 IEEE International Memory Workshop (IMW). The device had a dual-gate Surrounding Gate Transistor (SGT)
 and capacitor-less 4F2 celldesign. However, itsuffered from limited retention and electrical disturbances.

 • Unisantis implemented DFM ina variety of base processes, such as SOI, FinFET, and SGTs. More recently, the company has shown a structure named 3G-DFM,
 which consists of a single SGT with three gates: SG1, PL, and SG2. 3G-DFM has a long hole retention time and robust disturbance shield;it isalso suitable for2-
 bit/celloperation4 and for 3D stacking. The stacked 3G-DFM has a substantial potential torealize a much smaller equivalent cell than 6F2 with 3~4 tiers.

 DFM with dual gate SGT 3G DFM Stacked DFM (Horizontal Gates)


 Source: Unisantis
 References:
 1. K. Sakui et al. (Toshiba), A New Static Memory Cell Based on Reverse Base Current (RBC) Effect of Bipolar Transistor”, IEDM 1988.
 2. K. Sakui (Toshiba), “Semiconductor Storage Device”, Japanese Patent, Filed on Nov. 30, 1989.
 3. K. Sakui and N. Harada., “Dynamic Flash Memory with Dual Gate Surrounding Gate Transistor (SGT)”, IMW 2021.
 huguodong@cmbchina.com 4.K. Sakui et al., “2 bit/cell Dynamic Flash Memory with Three Gates”, SSDM 2023. Next-Generation DRAM 2025 | Report | www.yolegroup.com 190
 2025-04-08 01:51

## 第 191 页

NEO SEMICONDUCTOR
3D X-DRAM based on capacitor-less floating body cell technology


 • Founded in 2012 in San Jose, California, the fabless IP company Neo Semiconductor focuses on advancing 3D NAND and DRAM technologies and holds more than 23 U.S.patents. In 2020,
 the company introduced a 3D NAND architecture named X-NAND that can achieve SLC performance from TLC and QLC memory.
 • In May 2023. Neo Semiconductor launched 3D X-DRAM based on capacitor-less floating body cell(FBC) technology using (poly-)silicon materials. Relevant patent applications were
 published with the U.S.Patent Application Publication in April 2023. Compared to the 2D FBC technology, which has limited possibilitiesfor increasing the capacitor size,the 3D FBC’s size
 (diameter >100 nm) issignificantly largerand provides sufficient capacitance for charge storage.
 • Neo Semiconductor’s 3D X-DRAM can be manufactured using today’s 3D NAND-like processes. In itsbasic form, only one lithography mask isneeded to define the bit-lineholes and form
 the cellstructure inside the holes. This cellstructure simplifies the process steps and is expected to provide a high-speed, high-density, low-cost, and high-yield solution leveraging 3D-
 NAND industry know-how.
 • At IMW 2024, Neo Semiconductor presented compelling TCAD simulations of itsinnovative 3D X-DRAM technology. This DRAM cellemploys a dual-gate, thin-body architecture, combined
 with a novel operation mechanism that utilizesback-gate voltage modulation toprecisely control channel current. In the same year, Neo Semiconductor received the "Best ofShow" award
 at the Future of Memory and Storage event forits3D X-AI technology, which was recognized as the "Most Innovative AI Application." The groundbreaking 3D X-AI simulates artificialneural
 networks (ANNs) by integrating synapses for weight data storage and neurons for data processing, positioning it as an ideal solution to enhance performance and accelerate the
 development ofnext-generation AI chips and applications.
 • The company is currently collaborating with a leading research foundry in Taiwan to develop a Proof of Concept (POC) device, with results anticipated in the second half of the year.
 Additionally, new simulations are underway todemonstrate that their technology meets criticalDRAM specifications regarding endurance, retention, and power efficiency.The company is
 also actively engaging with equipment vendors to facilitatethe implementation oftheir advanced 3D architecture that features more than 100 layers.
 3D X-DRAM: cell structure, array architecture, and process flow


 Data are written into the cell through impact ionization. Reads are non- Source: Neo Semiconductor
 destructive. A dual-gate structure is used for increased retention.
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 191
 2025-04-08 01:51

## 第 192 页

MACRONIX’ 3D STACKABLE DRAM TECHNOLOGY
 Capacitor-less 3D DRAM technology based on Gate-Controlled Thyristors (GCT)


 • Macronix’s 3D DRAM proposal relieson a capacitor-less cellstructure, which isvery attractive forDRAM scaling as itavoids the large area overhead of capacitors.
 • The company uses athree-wordline (3-WL) gate-controlled thyristor (GCT) RAM structure, which consists of a vertical-channel gate-all-around (GAA) device with three wordline
 transistors(G1,G2, and G3). The architecture shares similaritieswith stacked nanosheet CMOS and 3D-stackable NAND flash.
 • According toMacronix, multilayer stacking in the Z direction and aggressive X/Y scaling can pave the way forhigh-density 3D DRAM.
 • Relevant research papers by Macronix (2022-2023):
 • “A 3D Stackable DRAM: Capacitor-less Three-Wordline Gate-Controlled Thyristor (GCT) RAM with >40 μA Current Sensing Window, >1010 Endurance, and 3-second
 Retention at Room Temperature” (IEDM, 2022)
 • “A Simulation Study of Scaling Capability toward 10nm for the 3D Stackable Gate-Controlled Thyristor (GCT) DRAM Device” (IMW 2023)
 • Note: More recently, at IMW 2024, Macronix also presented a stacked 4F2 DRAM with circuit under array (CuA) architecture. To avoid new channel material complexities, an
 annealed poly-Si channel access transistor isimplemented with an additional auxiliary gate (AG) to minimize the GIDL leakage current. The company also introduced an
 enhanced version 3D DRAM based on GTC with verticalBit Lines and horizontal Word Lines (link).

 Schematics of the 3-WL GCT device Major manufacturing steps Si channel grown by selective epitaxy
 (Cross-sectional TEM)


 Thegate-controlledthyristoroperatesbyapplyingsuitablegate
 voltagesofG1,G2 and G3,which caninduce differentvirtual
 junctions(NorPtype)dependingonthegatebiaspolarity.
 Source: Macronix, IEDM 2022
 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 192
 2025-04-08 01:51

## 第 193 页

OTHER COMPANIES WORTH WATCHING (NON-EXHAUSTIVE LIST!)


 SunRise Memory (San Jose, Calif.)was founded in 2016 by EliHarari, founder of SanDisk and a highly regarded expert innon-volatile memory technology
 and business. The company has recently emerged from stealth mode. Itcurrently has ~60 engineers in the US, Japan, and Israel.Several memory IC
 design engineers joined the company in 2019, including some who came from a design group belonging to YMTC in California. SunRise raised $74.8
 million in a Series C round of financing in October 2019 to develop high-speed 3D memory using transistors based on ferroelectric channel materials,
 likely doped HfO2 or similar high-K oxides.
 SunRise’s memory technology is based on a 3D-NOR architecture. Eli Harari had filed multiple patents on this subject, and one of the most relevant is
 “Three-dimensional vertical NOR flash thin film transistor strings” (US20170148517A1, filed on November 25, 2015). SunRise’s engineers designed
 ferroelectric RAM to be manufacturable on existing high-volume memory fabs that have previously mastered 3D process flows, such as 3D NAND fabs.
 Kioxia isrumored to be the primary manufacturing partner of SunRise.
 Note: there is currently a concern with the limited endurance of ferroelectric materials (105 cycles, while the endurance of DRAM should be virtually
 infinite).We expect it willtake a long time to optimize the material for high-volume manufacturing (>> 2 years).


 MonolithIC 3D (San Jose, Calif.)isan IP company with operations in Silicon Valley, Romania, and Israel.Itinvented and developed a practical path to
 monolithic 3D Integrated circuits, which includes multiple derivatives for logic, memory, and electro-optic devices. The company was founded and
 incorporated in 2009 by semiconductor industry veteran Zvi Or-Bach under the name NuPGA. The mission of NuPGA was to develop programmable
 logic technology with density, speed, and power approaching that of ASICs. While developing improved FPGA technology, the NuPGA team discovered a
 path for practical monolithic 3D-ICs, and the company was renamed MonolithIC 3D Inc.
 MonolithIC plans to use 3D-NOR architecture, possibly in combination with W2W stacking approaches that enable a different configuration of the bit
 lines to improve latency and density. While SunRise plans to use ferroelectric materials – which are more complex to deal with in high-volume
 manufacturing environments – MonolithIC 3D plans to use charge trap materials that have already been adopted for 3D NAND. The tunneling oxide
 could be reduced from 3nm to ~0.5nm, enabling low latencies inthe range of 5ns with a retention time of the order of 1s.Note: charge-trap materials are
 well established in the industry, and they willbe the preferred choice over more exotic materials such as IGZO or ferroelectrics.


 BeSang (Hillsboro, Oregon) – which inKorean means “flying high” – isa fabless semiconductor company founded in 2003 by Dr. Sang-Yun Lee, a former
 executive at Samsung, IDT, and Motorola. The current board of directors consists of Dr. Sang-Yun Lee (Founder and CEO) and Dr. Choonsik Oh (former
 CTO and EVP of hynix Semiconductor).
 Using a combination of vertical Gate-All-Around (GAA) transistors and monolithic 3D ICs, BeSang is developing its so-called “3D Super Memories” that
 aim to achieve high density at ultra-low costs. In the case of DRAM, BeSang presented a solution to increase DRAM density through the implementation
 of a periphery-under-cells (PUC) scheme together with vertical surrounded gate transistors (SGTs) for 4F2 design and vertically-standing capacitors. Note:
 BeSang has not disclosed detailson multilayer 3D DRAM technology.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 193
 2025-04-08 01:51

## 第 194 页

R&D ACTIVITIES ON 3D DRAM – SUMMARY AND PERSPECTIVES


 • Based on technical papers and patent filings– which are reported in the next chapter – itappears that allmajor DRAM companies are exploring multiple pathways
 to implement 3D DRAM. At the same time, leading equipment suppliers (Applied Materials, Lam Research, Tokyo Electron) are developing solutions to address the
 complex challenges of manufacturing next-generation 3D-DRAM devices.

 • Currently, R&D efforts are primarily centered on 1T-1C cellswith horizontal capacitors and major DRAM manufacturers are actively pursuing this approach: at VLSI
 2024, SK hynix presented its latest advancements in 5-layer 3D DRAM technology. Samsung is reportedly developing a 16-layer architecture (VS-CAT), while Micron
 focuses on an 8-layer model. Prototypes featuring even higher layer counts are rumored to existalready.

 • In the 1T-1C flipped architecture, horizontal capacitors consume a significant portion of the chip area, so a relatively high number oflayers would be necessary from
 the very first3D-DRAM generation to achieve a bit-density gain over leading-edge 2D DRAM. Examples:

 • CXMT estimated that ~61 layers of horizontal-capacitor cellswould be needed to match the density levelof 2D DRAM atthe 0a node.

 • More than 100 layers are expected to be necessary if3D DRAM isintroduced after the 0c technology node.

 • Manufacturing 3D DRAM with flipped 1T-1C cells brings complex process challenges and sets very aggressive specifications in terms of etching and deposition
 requirements. Hence, alternative solutions are highly desired.

 • Multiple options are currently in development. Most efforts are centered around the development ofcapacitor-less DRAM cells,among which are gain cells (2T0C) or
 1T-DRAM (e.g.,based on the floating-body effect).

 • Options based on IGZO gain cells are less likely since it will be hard to integrate the new materials in high-volume manufacturing. Moreover, the 3D-stacking
 capability ofthis architecture is limited as the gain-cell layers are embedded in the BEOL and require several metal lines and process steps for each layer.

 • Overall, IGZO isemerging as a promising transistor material for high-density DRAM, including 3D DRAM architectures. However, itpresents significant integration
 challenges as uniformity on the wafer scale remains difficultto achieve with CVD approaches. Optimizing IGZO for display technologies required roughly a decade,
 and similar complexities are anticipated when adapting IGZO forhigh-volume DRAM manufacturing.

 • Capacitor-less 1T-DRAM has been investigated fordecades, but its commercialization has been hampered by reliabilityissues (e.g.,parasitic capacitive couplings and
 read disturbances) and economic barriers. Different solutions have been proposed by various IP companies, as well as by memory manufacturers; however, at this
 stage, itis stilltooearly to identify the winning approach.

 • The industry willbe eager to adopt a capacitor-less solution that is compatible with 3D NAND manufacturing schemes and does not require new exotic materials.
 However, working prototypes satisfying the DRAM performance requirements are stillmissing, and we expect >5 years of R&D willbe necessary for high-density
 fully-functional capacitor-less 3D DRAM prototypes.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 194
 2025-04-08 01:51

## 第 195 页

IP landscape – list of relevant patents


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 195
 2025-04-08 01:51

## 第 196 页

3D DRAM – RELEVANT PATENTS (1/3)
Non-exhaustive lists of patents and players


 Current Assignee Patent ID Title Publication date
 (mm/dd/yyyy)

 Applied Materials US-20250063716-A1 Storage node contact (SNC) junction formation for 3D DRAM 2/20/2025

 Applied Materials WO-2023055771-A1 Three-color 3D DRAM stack and methods of making 4/6/2023

 Applied Materials US-20230055158-A1 Semiconductor isolation bridge for 3D DRAM 2/23/2023

 Applied Materials US-20220344339-A1 3D DRAM gate all-around (GAA) design using stacked Si/Sige 10/27/2022

 Applied Materials US-20220285362-A1 Methods and structures for 3D DRAM 9/8/2022

 Applied Materials US-20220285364-A1 Methods and apparatus for hierarchical bitline for 3D DRAM 9/8/2022

 Applied Materials US-20230029344-A1 Methods of formation of a SiGe/Si superlattice 7/21/2022

 Applied Materials US-20220199627-A1 Replacement channel process for 3D DRAM 6/23/2022

 Applied Materials KR-20210102094-A 3D DRAM structures and methods of manufacture 8/19/2021

 Applied Materials TW-202046491-A 3D DRAM structure with high mobility channel 12/16/2020

 Beijing Superstring Ac. of Mem. Tech. CN-118250997-B Semiconductor device, method of manufacturing the same, and electronic apparatus 09/06/2024

 BeSang US-20220189515-A1 3D Memory with 3D sense amplifier 6/16/2022

 BeSang US-20220139918-A1 Novel 3D DRAM structures 5/5/2022

 ChangXin Memory Technologies CN119486169-A Semiconductor structure and method for manufacturing the same 2/18/2025

 ChangXin Xinrui Storage Tech. Beijing CN-119403436-A Semiconductor structure and method for manufacturing semiconductor structure 2/7/2025

 ChangXin Memory Technologies CN-118647209-A Semiconductor device, dynamic random-access memory and selection control circuit 09/12/2024

 ChangXin Memory Technologies US-20230011180-A1 Method for manufacturing semicon. structure, semicon. structure and semicon. memory 1/12/2023

 ChangXin Memory Technologies CN-115188666-A Three-dimensional semiconductor structure and preparation method thereof 10/14/2022

 ChangXin Memory Technologies CN-115020351-A Method for forming semiconductor device 9/6/2022

 ChangXin Memory Technologies CN-207302640-U A kind of 3D dynamic random-access memory 5/1/2018

 Huazhong University CN-11948613-2A A three-dimensional dynamic memory and its preparation method 02/18/2025

 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 196
 2025-04-08 01:51

## 第 197 页

3D DRAM – RELEVANT PATENTS (2/3)
Non-exhaustive lists of patents and players


 Current Assignee Patent ID Title Publication date
 (mm/dd/yyyy)

 Intel US-20220068931-A1 Three-dimensional nanoribbon-based dynamic random-access memory 3/3/2022

 Lam Research WO-2023164717-A1 Surface inhibition atomic layer deposition 8/31/2023

 Macronix US-20230240062-A1 Memory structure 7/27/2023

 Micron Technology US-11690210-B2 3D dynamic random-access memory array 6/27/2023

 Micron Technology US-2021143055-A1 Methods of forming high aspect ratio (HAR) openings and methods of forming HAR features 5/13/2021

 Micron Technology US-10672456-B2 Three-dimensional memory devices 6/2/2020

 MonolithIC 3D US-2025070091-A1 3d semiconductor device and structure with metal layers 02/27/2025

 MonolithIC 3D US-20230253296-A1 3D semiconductor device and structure with metal layers and a connective path 8/10/2023

 MonolithIC 3D US-20230223469-A1 3D semiconductor device and structure with oxide bonding 7/13/2023

 MonolithIC 3D US-11094576-B1 Methods for producing a 3D semiconductor memory device and structure 8/17/2021

 MonolithIC 3D US-10991675-B2 3D semiconductor device and structure 4/27/2021

 MonolithIC 3D US-8754533-B2 Monolithic three-dimensional semiconductor device and structure 6/17/2014

 MonolithIC 3D US-8642416-B2 Method of forming three-dimensional integrated circuit devices using layer transfer technique 2/4/2014

 MonolithIC 3D US-8581349-B1 3D memory semiconductor device and structure 11/12/2013

 NEO Semiconductor US-2023269926-A1 3D memory cells and array architectures 8/24/2023

 NEO Semiconductor US-2023269927-A1 3D memory cells and array architectures and processes 8/24/2023

 NEO Semiconductor US-2023106561-A1 3D memory cells and array architectures 4/6/2023

 NEO Semiconductor WO-2023056476-A1 3D memory cells and array architectures 4/6/2023

 NEO Semiconductor US-2022351790-A1 Methods and apparatus for a novel memory array 11/3/2022


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 197
 2025-04-08 01:51

## 第 198 页

3D DRAM – RELEVANT PATENTS (3/3)
Non-exhaustive lists of patents and players


 Current Assignee Patent ID Title Publication date
 (mm/dd/yyyy)

 NEO Semiconductor WO-2020097098-A2 Methods and apparatus for a 3D array having aligned deep-trench contacts 5/14/2020

 NEO Semiconductor US-10008265-B2 Method and apparatus for providing 3D integrated (NVM) and DRAM memory device 6/26/2018

 Samsung Electronics US-20180190619-A1 3D semiconductor device and structure 2/25/2018 (MonolithIC 3D)*

 Samsung Electronics KR-102237739-B1 Dynamic random-access memory having three-dimensional vertical cell structure 4/8/2021

 SK hynix US-20220399340-A1 Semiconductor memory device 12/15/2022

 SK hynix US-2021242210-A1 Memory device 8/5/2021

 SK hynix KR-20210007737-A Vertical memory device 1/20/2021

 Tokyo Electron US-20230261113-A1 3D UFET device for advanced 3D integration 8/17/2023

 Tokyo Electron US-20230262956-A1 3D horizontal DRAM with in-situ bridge 8/17/2023

 Tokyo Electron US-2021249430-A1 Architecture design and process for 3D logic and 3D memory 8/12/2021

 TSMC US-20230240066-A1 Vertical DRAM structure and method of formation 7/27/2023

 TSMC KR-20210098834-A High-density 3D-DRAM cell with scaled capacitors 8/11/2021

 Unisantis Electronics US-20230284433-A1 Semiconductor-element-including memory device 9/7/2023

 Unisantis Electronics US-20230269925-A1 Method for manufacturing memory device including pillar-shaped semiconductor element 8/24/2023

 Unisantis Electronics TW-20224058-1A Memory device including semiconductor element related applications 10/16/2022

 Unisantis Electronics JP-7057034-B1 Semiconductor memory cells and semiconductor memory devices 8/11/2022


 *Samsung is the current assignee of several patents originally filed by MonolithIC 3D focusing on three -dimensional memory structures


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 198
 2025-04-08 01:51

## 第 199 页

Long-term market evolution scenario


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com199
 2025-04-08 01:51

## 第 200 页

3D DRAM LONG-TERM MARKET EVOLUTION SCENARIO
Modeling the market evolution with a Fischer-Pry model calibrated using NAND historical data


 • At this stage, there are stillmajor unknown aspects regarding 3D DRAM, its device
 structure, and manufacturing process, as well as itspotential adoption for continuous Modeled 3D DRAM penetration rate (%)
 bit-density scaling.
 • Leading companies mentioned that development trajectorieswill start becoming 100%
 clearer in the next few years, and the riseof 3D DRAM could occur at the end of this
 decade. Model (% of DRAM bits)
 • In thischapter, we present abasic market evolution scenario that assumes thatfrom 80%
 2033-2034 – at a firstlevelof approximation – the 2D-to-3D DRAM transition will Model (% of DRAM wafers)
 mimic itsNAND counterpart, which started back in2015. For thisto happen, 3D DRAM
 needs to provide both density and performance improvement (which at this stage
 remains to be demonstrated) before becoming a replacement forplanar DRAM in 60%
 mainstream applications.
 • We used the Fischer-Pry market penetration model topredict the 3D DRAM bitsand
 wafer production volume using data available inthe “DRAM Market Monitor” by Yole 40%
 Group. The model parameters (Aand Rs,see table below) were obtained by fittingthe
 3D NAND historicaldata availablein the “NAND Market Monitor” by Yole Group. Our model assumes
 that sampling to
 20% selected customer
 will begin in 2033.
 Fisher-Pry Model Parameters
 3D DRAM penetration rate (%) 0%

 Unit Bits Wafers 2015 2020 2025 2030 2035 2040

 Adoption rate (A) 125% 105%

 Penetration rate at saturation (RS) 98% 85% 𝑅𝑠
 Fisher-Pry equation: 𝑅(%) = 1 + exp(−𝐴 ∙ 𝑡𝑖𝑚𝑒 − 𝑡 )
 Time (year) to reach 50% of saturation (t0) ~2037 ~2037 0


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 200
 2025-04-08 01:51

## 第 201 页

3D DRAM LONG-TERM MARKET EVOLUTION SCENARIO


 2031-2037 DRAM bit production (Eb) 2031-2037 DRAM wafer production (M WPY)
 2000 50
 CAGR31-37 ~ 16% CAGR31-37 ~ 4%
 1600 40


 1200 30


 800 20


 400 704 10

 10
 243 4
 0 68 0 2
 2031 2032 2033 2034 2035 2036 2037 2031 2032 2033 2034 2035 2036 2037


 2031-2037 DRAM bit production mix (%) 2031-2037 DRAM wafer production mix (%)
 100% 100%

 80% 80%

 60% 60%

 40% 40%

 20% 39% 20%

 16% 27%
 0% 5% 5% 12%
 2031 2032 2033 2034 2035 2036 2037 0%
 2031 2032 2033 2034 2035 2036 2037
 Planar (2D) DRAM
 huguodong@cmbchina.com 3D DRAM Next-Generation DRAM 2025 | Report | www.yolegroup.com 201
 2025-04-08 01:51

## 第 202 页

3D DRAM LONG-TERM MARKET EVOLUTION SCENARIO
 Estimated evolution of DRAM revenues generated by 3D-DRAM


 Note: Given the strong uncertainty on the long-term DRAM pricing environment, toestimate the revenues thatwillbe generated by
 3D DRAM we used a simple ASP model that assumes a constant price-per-Gb decay of ~-6% in thetime range 2031-2035.

 2031-2037 3D DRAM revenue ($B)

 $150 30%
 3D DRAM revenue ($B) 28%
After hitting the % of DRAM revenue generated by 3D DRAM
market in 2033- $120 24%
2034, 3D DRAM
 will grow
 rapidly. Our $90 18%
model predicts
 that it will
account for up 13%
 to 28% of the $60 12%
 total DRAM
 revenues in
 2037. $30 6%
 5%

 1%
 $- 0%
 2031 2032 2033 2034 2035 2036 2037


 Our model assumes thatDRAM manufacturers willramp up 3D DRAM production from ~2034


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 202
 2025-04-08 01:51

## 第 203 页

PROCESSING IN MEMORY – OVERVIEW


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com203
 2025-04-08 01:51

## 第 204 页

APPROACHES TO OVERCOME THE MEMORY WALL – OVERVIEW


 HBM & 3D packaging
 Low latency is the
 most important
 feature.
 Mainly for
 applications
 requiring high
 Memory-Logic bandwidth.
 Heterogenous Integration
 Memory Computing

 Memory moves towards computing

 Computing moves towards memory or storage


 1. DRAM-based 2. Computational storage
 processing in memory Data is more
 Focus of this chapter important for the
 application.
 Mainly for data-
 intensive
 applications.
 Samsung Samsung computational
 AXDIMM solution storage drive solution


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com204
 2025-04-08 01:51

## 第 205 页

DRAM-BASED PROCESSING IN MEMORY (PIM)


 • The firstHBM-PIM solution (Aquabolt-XL) was announced by Samsung in February 2021. Itincorporates the AI processing function into Samsung’s
 HBM2 Aquabolt to enhance high-speed data processing insupercomputers and AI applications. SK hynix went in a slightlydifferent direction and, in
 2022, showcased AiM (accelerator in memory), a GDDR6-based PIM implemented to accelerate AI/ML, high-performance computing, big data
 computation, and storage applications.

 • At Hot Chips 2023, Samsung presented new resultson HBM-PIM as part of itsefforts to focus on the AI sector. HBM-PIM was integrated on the
 commercial MI-100 GPU by AMD to enable more than double the performance and power efficiencythan existing HBMs. Samsung alsointroduced the
 LPDDR-PIM, which combines mobile DRAM with PIM to enable direct processing and computing within edge devices.

 • At the same event, SK hynix unveiled a prototype of AiMX – a generative AI accelerator card based on GDDR6-AiM – and demonstrated Meta’s
 generative AI Open Pretrained Transformer (OPT) 13B model on a server system equipped with the AiMX prototype. The latterwas shown to reduce
 data processing time by more than 10times compared to systems with GPUs while consuming 20% ofthe power.


 HBM-PIM concept by Samsung HBM-PIM die by Samsung AiM GDDR6 die and AiMX card by SK hynix


 huguodong@cmbchina.com Source: Hot Chips 2023 Next-Generation DRAM 2025 | Report | www.yolegroup.com
 205
 2025-04-08 01:51

## 第 206 页

DRAM-BASED PROCESSING IN MEMORY (PIM)
The computing function is integrated in the module controller – Examples


 DDR5-based acceleration DIMMs (AXDIMMs)

 • In August 2021, at the Hot Chips 33 conference, Samsung unveiled AXDIMM (acceleration DIMM) – a brand-new DDR5
 memory module featuring processing-in-memory (PIM) functionality. The aim is to boost the energy efficiency of AI
 accelerator systems through better management ofdata movement between the CPU and DRAM.
 • The AI engine that drives the process isbuilt into the AXDIMM buffer IC. This enables the AXDIMM to perform parallel
 processing ofmultiple memory ranks orsets of DRAM chips rather than being limited toaccessing them one at a time. Samsung’s AXDIMM
 • As AXDIMM retains its traditional DIMM form factor, it facilitates drop-in replacement without requiring system
 modifications. Moreover, according to Samsung, AXDIMM can offer approximately twice the performance in AI-based
 recommendation applications and a 40% decrease in system-wide energy usage. The technology has been tested in
 combination with XilinxZynq Ultrascale+ FPGA chips and in partnership with SAP. It isexpected to provide significant
 performance improvements forin-memory database management system tasks.


 CXL-based processing-near-memory (PNM) solutions
 • In October 2022, at itsMemory Tech Day (October 5th),Samsung introduced the firstCXL-based processing-near-memory
 (PNM) technology for use in database-based applications and recommendation systems, as well as high-capacity AI model
 processing.
 • CXL (more details inthe chapter “Compute Express Link –Overview”) can be utilized inconjunction with other technologies,
 such as processing near memory (PNM), tofacilitatememory capacity expansion and improve performance.
 • PNM reduces the memory bottleneck phenomenon between the processor and memory and improves the system
 performance by having the memory feature within the memory module.
 • According to Samsung, the implementation of PNM technology enhances performance by at least a factor of three in
 database-based applications and almost a factorof two in recommendation systems.
 • In the initialprototypes, the CLX-PNM compute functions are implemented within the CXL controller. However, Samsung
 also mentioned plans to introduce AI-acceleration modules where the compute functions are integrated within the DRAM Samsung’s CXL-PNM Module
 chips, for instance, by making use ofLPDDR-PIM devices.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 206
 2025-04-08 01:51

## 第 207 页

DRAM-BASED PROCESSING IN MEMORY – HISTORICAL TIMELINE


 At Hot Chips, Samsung unveils At Hot Chips, Samsung At CES, SK hynix presents a
 The French startup the first successful integration At ISSCC 2022, SK hynix presents new research Computational Memory
 company UPMEM releases of its HBM-PIM into a showcases AiM (accelerator results on HBM-PIM and Solution (CMS) test product
 the first silicon-based PIM commercialized accelerator in memory), a GDDR6- low power DDR (LPDDR)- leveraging the CXL
 benchmarks. system (MD instinct Mi100). based PIM implemented to PIM as part of its efforts to interface. Note: CMS was
 UPMEM’s DIMMs are DDR4- They also showcase AXDIMM –a accelerate AI/ML, high- focus on the AI sector. first introduced at the OCP
 compatible and embed brand-new DDR5 memory performance computing, Summit in 2022.
 UPMEM’s PIM DRAM chips module with PIM functionality. big data computation, and
 storage applications.


 2020 2021 2022 2023 2024


 In February 2021, Samsung announces the At the AI Hardware & Edge
 world’s first HBM-PIM solution, Aquabolt-XL, At its Memory Tech Day (October 5th), AI Summit, SK hynix
 which incorporates AI processing in Samsung unveils the industry first demonstrates a prototype
 Samsung’s HBM2 Aquabolt to enhance CXL-based processing near memory of AiMX, a generative AI
 high-speed data processing in (PNM) technology for use with high- accelerator card based on
 supercomputers and AI applications. capacity AI model processing. GDDR6-AiM.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 207
 2025-04-08 01:51

## 第 208 页

CONCLUSIONS


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 208
 2025-04-08 01:51

## 第 209 页

NEXT-GENERATION DRAM – MARKET OVERVIEW
HBM shipments expand rapidly with over 190% YoY growth in 2024, and revenue is on track to hit $98 billion by 2030


 • The High-Bandwidth Memory (HBM) market isexperiencing exponential growth, primarily driven by the proliferation of artificialintelligence (AI) workloads and high-
 performance computing (HPC) applications. The generative AI boom, catalyzed by the introduction of ChatGPT in late2022, resulted in an unprecedented 187% year-over-
 year (YoY) increase in HBM bitshipments in2023, followed by an additional 193% surge in 2024. This trajectory isexpected to persist,with HBM bitshipments forecasted to
 grow at a 31% compound annual growth rate (CAGR) through 2030.

 • HBM is significantly outpacing the broader DRAM market. Global HBM revenue is projected to increase from $17B in 2024 to $98B by 2030, reflecting a 33% CAGR.
 Consequently, HBM’s revenue share within the DRAM market isexpected toincrease from 18% in2024 to 50% by 2030.
 • The market willsee another significant inflection point in 2025, with HBM revenues projected to double to ~$34B. Current supply constraints underscore the strategic
 importance of HBM in AI data centers and advanced computing platforms, as evidenced by reports from SK hynix and Micron indicating that their HBM production
 capacity isfullyallocated through 2025. These supply-side limitations reinforce the need for investments in capacity expansion to meet the escalating demand.

 • By contrast, conventional DRAM—including DDR, LPDDR, and GDDR—was valued at $80B in2024 but isexpected togrow ata modest 3% CAGR between 2024 and 2030,
 constrained by inherent price fluctuations and market cyclicality(as detailed in the DRAM Market Monitor by Yole Group). The combined growth of HBM and conventional
 DRAM translates to an overall DRAM market CAGR of12%, with revenues increasing from $97B in 2024 to $194.5B in2030.
 • From a bit shipment perspective, HBM represented 5% oftotal DRAM bitsin 2024, equivalent to 11.9Eb (1.49M GB) out of 254Eb (31.7M GB), and is projected to reach 9% by
 2030. As a premium-tier product, HBM's average selling price (ASP) iscurrently estimated to be up to four times higher than the blended DRAM ASP in 2024. While
 competition among the three dominant HBM suppliers is expected to exert downward pricing pressure, blended HBM ASPs are projected to remain stable due to
 sustained demand.

 • The introduction of next-generation HBM architectures—including HBM4, HBM4E, and HBM5—will drive further improvements inbit density and stacking technology,
 enabling greater memory capacity per package. These technological advancements will not only enhance performance metrics but also sustain premium pricing
 structures. Current market projections indicate that HBM ASP per gigabyte (GB) willincrease at a2% CAGR from 2024 to 2030.
 • To capitalize on the AI-driven demand surge and accelerate market recovery, leading suppliers – including Samsung, SK hynix, and Micron – have increased their wafer
 allocations for HBM production. In 2024, HBM wafer output expanded by more than 150% YoY, reaching approximately 216K wafer starts per month (KWPM). This upward
 trajectory is expected to continue in 2025, with average monthly production projected to reach ~350 KWPM. By 2030, HBM wafer capacity isexpected to scale to 590
 KWPM, reflecting a 9% CAGR2024-2030.
 • In parallelwith the industry’s strong focus on HBM, the slowdown in planar DRAM scaling isprompting memory manufacturers to investigate alternative approaches to
 maintain progress in bit density, performance, and cost efficiency.Among these, 3D DRAM is emerging as a leading candidate, currently inthe pathfinding stage. Itis
 widely regarded as the most promising long-term solution for achieving high-density DRAM architectures in the coming decade. Initialcommercial deployment of 3D
 DRAM isanticipated around 2033–2034, with revenue growth expected to accelerate significantly inthe latter half ofthe 2030s.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 209
 2025-04-08 01:51

## 第 210 页

NEXT-GENERATION DRAM – PLAYER DYNAMICS
HBM leaders intensify the race, while China steadily progresses in AI and advanced memory technologies


• The global battle for HBM leadership has accelerated sharply, driven by the explosive demand for AI computing. This reflects the strategic importance ofmemory bandwidth
 and energy efficiency for AI.
 • SK hynix currently leads the market. The company began mass production of 12Hi HBM3E inSeptember 2024 and has already started sampling 12Hi HBM4 (36GB) to
 customers as of March 2025, with mass production expected in2H 2025. A notable collaboration with TSMC, announced inApril 2024, ishelping SK hynix strengthen
 itsposition in both advanced packaging and next-generation HBM technologies. This momentum culminated in a record quarterly operating profit of $5.6B in Q4-
 2024, overtaking Samsung forthe firsttime.
 • Samsung, traditionally a dominant memory player, has fallen behind in the HBM segment and isnow pushing hard to catch up. After facing yield and thermal
 challenges with itsdesign for HBM3E, the company is now refining itsDRAM design and working on 4nm logic dies forHBM4. Trialproduction has begun, with
 sample shipments expected in2025. Internally,Samsung restructured its HBM operations in July 2024, forming a dedicated team to enhance itscompetitiveness
 across HBM3, HBM3E, and HBM4.
 • Micron, having skipped HBM3, entered the race with HBM3E in 2024. Itbegan mass production of 8Hi and 12Hi HBM3E in 2024, with integration into Nvidia’s H200
 GPUs. However, Micron’s current production capacity islimited – less than 20% of that of SK hynix and Samsung combined – but is scaling up rapidly, targeting
 60,000 units/month by the end of 2025. Mass production ofHBM4 isplanned for2026, with HBM4E to follow.
• China, which consumed over 25% of global DRAM in 2024, isaccelerating effortsto localize memory production amid tightening U.S.sanctions.
 • Changxin Memory Technologies (CXMT), the country’s leading DRAM maker, skipped its G2 node and ramped up G3 (~18.5nm) production in 2024, significantly
 boosting DDR4 shipments and contributing to price decreases. In December 2024, KingBank and Gloway launched the firstdomestic DDR5 memory modules using
 CXMT G4 DRAM chips (16nm process), marking a supply chain milestone forChina.
 • In response to U.S.restrictions on AIchips and HBM, Chinese companies have launched large-scale investments to build domestic alternatives. Huawei isreportedly
 leading a consortium – including XMC, SJSemi, TFME, and JCET –to establish HBM capabilities.Meanwhile, CXMT is sampling HBM2 and actively developing HBM2E,
 supported by a $2.4B investment in advanced packaging. Despite the technological gap with industry leaders (~6 years), Chinese players can leverage strong
 domestic demand for locally developed AI accelerators, supported by significant government backing and a well-established industry network. These factors are
 expected to help them gain a foothold inthe HBM market in the coming years.
 • China is increasingly focusing itsR&D on (1)advanced packaging for DRAM-logic integration and (2)alternative scaling approaches beyond traditional lithography,
 including 4F² cells,CBA-DRAM, and 3D DRAM. These innovations allow Chinese players to develop high-performance AI chips without relying on restricted
 technologies likeEUV lithography.
• With 2D DRAM scaling expected to reach itslimit by 2033–2034, the industry is preparing for a shift to 3D DRAM architectures. This transition will ease dependence on
 advanced lithography and drive demand for deposition (ALD, CVD), HAR etching, and bonding tools – creating new opportunities, particularly forplayers without access to
 EUV, likeChina. Though stillinearly R&D, 3D DRAM has the potential to reshape industry dynamics and offera pathway for latecomers toclose the gap.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 210
 2025-04-08 01:51

## 第 211 页

NEXT-GENERATION DRAM – OVERVIEW BY TECHNOLOGY
As scaling challenges grow, new designs, CMOS bonding, and 3D architectures are redefining DRAM development


 • Despite increasing scaling challenges, planar DRAM isexpected to continue evolving through the 0c/0d nodes (2033–2034), leveraging a combination of architectural
 and process innovations. The industry is currently reliant on the 6F² DRAM cell structure, which dominates allcommercial products as of 2025. However, further
 miniaturization willeventually necessitate a transition to 4F² cellsbased on verticaltransistors (VT),integrated within a CMOS Bonded Array (CBA) architecture.
 • CBA enables higher bit density by separating the periphery circuit and memory array onto different wafers, which are subsequently bonded. This transition, expected
 around the 0a node (~2029), isanticipated to deliver up to a 30% increase inbit density. Despite the technical complexity and cost, CBA paves the way for the use of
 advanced logic(e.g.,FinFETs) for improved performance and reliabilityand is seen as acrucial step inthe DRAM roadmap and a precursor to full3D DRAM.

 • While 4F²+CBA offers significant advantages indensity and logic integration, cost and yield challenges may continue to pose major obstacles. Under these conditions,
 DRAM manufacturers are likelyto extend 6F² scaling as faras economically viable, supported by broader adoption of EUV lithography – including High-NA EUV – to
 maintain density and performance scaling. According to our current model, starting in 2029, the top three DRAM suppliers are expected to implement a mixed-fab
 strategy, producing both 6F² and 4F²+CBA DRAM to address diverse performance and cost segments. Beyond 2030, CBA integration is anticipated to become a
 standard requirement – even for6F² architectures – to sustain the industry’s long-term scaling trajectory.

 • CMOS bonding is becoming a cornerstone technology for next-generation DRAM, particularly with CBA integration. Due to sub-200nm alignment and pitch
 constraints, fusion bonding is expected to be the preferred technique for wafer-to-wafer (W2W) stacking in DRAM starting from the 0a node. This bonding approach,
 although more costly than hybrid alternatives, enables precise alignment essential for high-density DRAM.
 • Hybrid bonding is being regarded as a key enabler for future HBM generations, particularly for high-stack configurations. However, due to yield and throughput
 challenges, HBM suppliers have extended microbump-based approaches – such as fluxless TCB and advanced MR-MUF – forHBM4 and HBM4E. Hybrid bonding is
 now projected to enter the market with HBM5 (around 2029), particularly forpremium 20Hi–24Hi stacks, where gapless bonding and die thinning (down to ~20µm) are
 required to adhere to the existing JEDEC standard on total stack thickness. Note: In March 2024, JEDEC relaxed the HBM4 thickness requirements from 720µm to
 775µm, enabling the use of TSV/microbumps formanufacturing 16Hi products.
 • After the 0c/0d nodes, the transition to a 3D DRAM architecture isexpected to be inevitable. As of 2025, allmajor DRAM manufacturers –including Samsung, SK hynix,
 Micron, and CXMT – are actively exploring multiple architectural pathways to enable 3D DRAM integration. Among the leading candidates are 1T-1C cell architectures
 with horizontally oriented capacitors, as well as capacitor-less alternatives such as gain cells (2T0C) and floating-body-based 1T-DRAM designs. In parallel, leading
 semiconductor equipment suppliers – such as Applied Materials, Lam Research, and Tokyo Electron – are investing in tooling solutions to address the unique
 challenges associated with 3D DRAM manufacturing.
 • The shift to 3D DRAM is likelyto mirror the transformational leap observed in NAND flash memory and willrequire a retooling of front-end process flows. While
 lithography constraints are expected to ease –allowing relaxed nodes around 20nm and minimizing reliance on EUV –the demand for advanced deposition and etch
 solutions willdrive capital intensity.These include high-aspect-ratio (HAR) etching, advanced gap-fillprocesses, and atomic-layer deposition (ALD) forconformal films.
 Additionally, the implementation of selective removal techniques and precise doping strategies will be essential to realize viable 3D DRAM structures at scale.


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 211
 2025-04-08 01:51

## 第 212 页

RELATED PRODUCTS


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 212
 2025-04-08 01:51

## 第 213 页

YOLE GROUP OF COMPANIES RELATED PRODUCTS
Reports


 A long hallway with rows of blue lights A close-up of a computer chip

 Description automatically generated Description automatically generated
 Status of the Memory Generative AI 2024
 Industry 2024
 2025 edition coming soon 2025 edition coming soon


 A close-up of a microchip

 Description automatically generated
 Emerging Non-Volatile Status of the Microcontroller
 Memory 2024 Industry 2024

Contact our Sales Team
for more information
Contact our


Contact our Sales Team
for more information 2025 edition coming soon 2025 edition coming soon
Sales Team


Contact our Sales Team
for more information
for more


Contact our Sales Team
for more information


 A computer chip with orange lights A computer chip in a city

 Description automatically generated Description automatically generated
information
 High-End Performance Status of the Processor
 Packaging 2024 Industry 2024
 2025 edition coming soon 2025 edition coming soon


 A computer server with blue lights

 Description automatically generated with medium confidence
 Memory-Processor Interface Neuromorphic Computing,
 2023 - Focus on Compute Memory and Sensing 2024
 Express Link (CXL)


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 213
 2025-04-08 01:51

## 第 214 页

YOLE GROUP OF COMPANIES RELATED PRODUCTS
Reports


 Une image contenant texte, Police, Graphique, logo

 Le contenu généré par l’IA peut être incorrect.


 HBM Comparison 2025 GH200 HBM3e


 Une image contenant texte, Police, Graphique, logo Une image contenant texte, Police, Graphique, logo

 Le contenu généré par l’IA peut être incorrect. Le contenu généré par l’IA peut être incorrect.


Contact our Sales Team NVIDIA GPU GH200 Hopper CXMT G4 DDR5 DRAM

for more information
Contact our


Contact our Sales Team
for more information
Sales Team


Contact our Sales Team
for more information
for more


Contact our Sales Team
for more information


 Une image contenant texte, capture d’écran, piano A close-up of a black and white photo of several plastic cups

 Description générée automatiquement Description automatically generated
information

 YMTC 232-Layer 3D NAND 16Gb DDR5 DRAM Memory
 Memory from Micron


 A graph showing a graph of progress Close-up of a chip

 Description automatically generated with medium confidence Description automatically generated

 Samsung 176-layer 3D NAND Everspin Technologies
 Memory Latest STT-MRAM in 28nm


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 214
 2025-04-08 01:51

## 第 215 页

YOLE GROUP RELATED PRODUCTS
Monitors


 Une image contenant Caractère coloré, Bleu électrique, violet, bleu Une image contenant Appareils électroniques, piano, Caractère coloré, musique

 Description générée automatiquement Description générée automatiquement


 DRAM Market Monitor NAND Market Monitor


 A microchip being held by tweezers Une image contenant texte, intérieur, orgue électrique

 Description automatically generated Description générée automatiquement

 Microcontroller (MCU) Market Processor Market Monitor


Contact our Sales TeamContact our Sales Team
for more informationfor more information
Contact our Contact our Monitor


Contact our Sales TeamContact our Sales Team
for more informationfor more information
Sales TeamSales Team


Contact our Sales TeamContact our Sales Team
for more informationfor more information
for more for more


Contact our Sales TeamContact our Sales Team
for more informationfor more information


 Une image contenant intérieur, ingénierie, machine, industrie A close-up of a machine

 Description générée automatiquement Description automatically generated
informationinformation

 Wafer Fab Equipment Market Semiconductor Equipment
 Monitor Subsystems Market Monitor


 Une image contenant Néon, nuit, ligne, léger

 Description générée automatiquement

 Advanced Packaging Market Wafer Data Monitor
 Monitor


 huguodong@cmbchina.com Next-Generation DRAM 2025 | Report | www.yolegroup.com 215
 2025-04-08 01:51

## 第 216 页

HOW TO USE OUR DATA?


 Yole Group ispleased to provide you a glimpse of our accumulated knowledge.
 Please note that the entire document and itsdata is copyrighted © Yole Group 2025.
 To share our data with your own network, within your presentations, press releases,
 dedicated articles and more, please contact our Public Relations department to make
 sure you get up-to-date, licensed materials.
 We will be more than happy to provide you our latest results and appropriate formats
 of our approved content.


 Public Relations & External Communications
 publicrelations@yolegroup.com


 Visit our website: www.yolegroup.com


 huguodong@cmbchina.com
 2025-04-08 01:51 Next-Generation DRAM 2025 | Report | www.yolegroup.com216

## 第 217 页

Corporate Presentation


©Yole Group 2025huguodong@cmbchina.com 2025 yolegroup.com
 2025-04-08 01:51

## 第 218 页

YOLE GROUP

 We provide industrial companies, financial investors, and R&D organizations, with market research, technology,
supply chain, and cost analysis, along with performance evaluation. Our services support informed decision-making
 on business and manufacturing strategies in the semiconductor, photonic, and electronic sectors.


 • Market, technology and • Technology, process and • Strategy consulting
 supply chain analysis cost analysis
 • M&A, due diligence and
 • Markets trends and v • Teardown and reverse v evaluation of companiesv
 forecasts engineering

 • Performance analysis


 Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com218
 huguodong@cmbchina.com 218
 2025-04-08 01:51

## 第 219 页

OUR PRODUCTS & SERVICES

 REPORTS QUARTERLY TEARDOWN TRACKS CUSTOM SERVICES
 MONITORS
INSIGHT INSIGHT INSIGHT INSIGHT
• Yearly published reports • Quarterly analysis with market • Teardowns of phones, smart • Specific and dedicated projects
• Market, technology and strategy data and technology trends in home, wearables and automotive • Strategic, financial, technical,
 analysis units, value at wafer level modules and systems supply chain, market and other
• Reverse costing and reverse • Direct access to the analyst • Bill-of-Materials semiconductor-related fields
 engineering (except for Wafer Data Monitor) • Block diagrams • Reverse costing & reverse
• Performance analysis • Interactive zooming engineering
 FORMAT
FORMAT • Excel files with data FORMAT FORMAT
• PDF files with analyses • PDF files with analyses graphs • Web access • Direct work with the analyst
• Excel files with graphics and data and key facts • PDF and Excel files team
• Web access • Web access • High-resolution photos PDF files with analyses
 • Excel files with graphics and data
TOPICS TOPICS TOPICS
• All thematic • Advanced Packaging​ • Consumer
 • Compound semiconductor: SiC, • Automotive
 GaN and RF GaN • Telecom
 • Computing: Processor and
 µcontroller​
 • Memory: DRAM​, NAND
 • Semiconductor Manufacturing
 and Test Equipment
 • Wafer Data


 115+ reports per year 15 different monitors 315+ Single Teardowns Tracks per 190 custom projects per year
 quarterly updated year - Daily updates


 Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com 219
 huguodong@cmbchina.com 219
 2025-04-08 01:51

## 第 220 页

RESEARCH PRODUCTS


 REPORTS MONITORS TEARDOWN TRACKS
 Annually with data and 5-yr forecast Quarterly data and analysis Full BOM costing

Market and technology trends analysis
 Dismantling
 photos
 from A to Z


Reverse engineering & reverse costing Detailed PCB


 Block diagram
 interactive


 Bill of materials


 huguodong@cmbchina.com Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com220
 2025-04-08 01:51

## 第 221 页

OUR EXPERTISE


 • Battery • Memory


 • Compound Semiconductor • Photonics and Lighting

 • Computing and Software • Power Electronics


 • Display • Radio Frequency


 • Electronic Systems • Semiconductor Equipment


 • Global Semiconductor Trends • Semiconductor Packaging


 • Imaging • Sensing and Actuating


 Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com221
huguodong@cmbchina.com 221
2025-04-08 01:51

## 第 222 页

ACROSS THE SEMICONDUCTOR SUPPLY CHAIN & MARKETS


 MOBILE AUTOMOTIVE TELECOM & MEDICAL DEFENSE INDUSTRIAL
& CONSUMER & MOBILITY INFRASTRUCTURE & AEROSPACE


Academic/ Design & Material & Front-end Back-end OEMs & Consulting &
 research engineering equipment manufacturing manufacturing system finance
 integrator


 Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com222
 huguodong@cmbchina.com 222
 2025-04-08 01:51

## 第 223 页

YOLE GROUP – KEY FIGURES


 26+ 180+
 Years in the semiconductor Worldwide collaborators
 industry

 900+ 160+
 Products Worldwide trade shows &
 conferences

 10+ 125,000+
 Fields of expertise Contacts in our database

 5,000+ 16,000+
Interactions with the industry Mentions in Media
 (EETIMES, Forbes, Thomson Reuters…)


 Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com223
 huguodong@cmbchina.com 223
 2025-04-08 01:51

## 第 224 页

YOLE GROUP – A WORLDWIDE PRESENCE


 United
 Kingdom
 United States Germany
 of America
 China South
 Nantes Korea

 Lyon Japan


 Taiwan


 Copyright © Yole Group 2025. All rights reserved. | www.yolegroup.com224
huguodong@cmbchina.com 224
2025-04-08 01:51

## 第 225 页

CONTACTS


 REPORTS, MONITORS & TRACKS GLOBAL OPERATIONS FOLLOW U.S. ON

NORTH AMERICA CUSTOM SERVICES
sales.us@yolegroup.com custom@yolegroup.com
+1 833 338 4999
 MARKETING
EMEA marketing@yolegroup.com
sales.emea@yolegroup.com PUBLIC RELATIONS & EXTERNAL
+49 69 9621 7675 COMMUNICATIONS
JAPAN, KOREA, REST OF ASIA publicrelations@yolegroup.com General terms
sales.japan@yolegroup.com communication@yolegroup.com and conditions
sales.korea@yolegroup.com GENERAL INQUIRIES of sales
sales.restofasia@yolegroup.com contact@yolegroup.com | +33 4 72 83 01 80
+81 3 4405 9204

GREATER CHINA
sales.gc@yolegroup.com
+886 922 408 282


 Copyright © Yole Group 2025.22522
 huguodong@cmbchina.com All rights reserved | www.yolegroup.com5
 2025-04-08 01:51

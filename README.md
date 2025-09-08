This repository contains laipn's resume in markdown form.  Copy and paste the markdown below into <https://markdownresume.app>.

# Lai Nguyen

**Computer Engineer**
California, United States | <Lai.Phu.Nguyen@gmail.com> | +1 (512) 256-3232 | (<https://www.linkedin.com/in/laipn)\[LinkedIn>]

***

See [github.com/laipn/resume](http://github.com/laipn/resume) for markdown version of this resume.  It has click-able links.

***

## Experience

**Sys admin at [Paws 2 Read](https://www.paws2read.org/) (Charity)**
*Mesa, Arizona | March 2025 – September | 6 months*

**Site Reliability Engineer at Google ([Borg](https://research.google/pubs/large-scale-cluster-management-at-google-with-borg/))**
*Sunnyvale, California | Jan 2016 – Feb 2025 | 9 years*

* Worked primarily with Google Borg (internal Kubernetes equivalent) Control Plane and [Node](https://kubernetes.io/docs/concepts/overview/components/#node-components) teams.
* Created "First-Class Metrics". FCM formalizes "[Service Level Objectives](https://sre.google/sre-book/service-level-objectives/)" into working code used to monitor and gate all host-level software (e.g. kernel, system [software-packages](https://en.wikipedia.org/wiki/Package_manager)) at Google.
* Introduced concept of "experimental" **machine** [error-budget](https://cloud.google.com/blog/products/management-tools/sre-error-budgets-and-maintenance-windows): The amount of machine footprint lent to developers in order to pursue long-running risky host-level experiments (e.g. [IPv6](https://en.wikipedia.org/wiki/IPv6)). Established oversight committee to ensure the budget was used effectively.
* Established the SRE methodology to introduce new server platforms (["AMD Zen 2"](https://en.wikipedia.org/wiki/Zen_2), ["Intel Skylake"](https://en.wikipedia.org/wiki/Skylake_(microarchitecture)) and onward) into Google production.
* Established the SRE Methodology to introduce [compiler](https://github.com/google/tcmalloc) and [ISA](https://en.wikipedia.org/wiki/Instruction_set_architecture) (e.g. [ARM](https://cloud.google.com/compute/docs/instances/arm-on-compute)) changes to all Google production code.
* SRE lead for "Tiered main memory" initiatives. Memory technologies includes: DRAM->Flash memory-swapping, Intel [3D Xpoint](https://en.wikipedia.org/wiki/3D_XPoint) replacement [DIMMs](https://en.wikipedia.org/wiki/DIMM), [CXL.mem](https://en.wikipedia.org/wiki/Compute_Express_Link) PCIe devices sharing memory bus, kernel-based [compressed memory](https://wiki.archlinux.org/title/Zswap) swapping.
* Developed Machine Learning SLOs for Google [Tensor Processing Units](https://en.wikipedia.org/wiki/Tensor_Processing_Unit), ["virtual" CPU](https://cloud.google.com/compute/docs/cpu-platforms) performance SLOs, etc.
* Production 24/7 production (paging) on-call with 15min SLO.  Mitigated or stopped >5 major incidents seen in the [news](https://status.cloud.google.com/incidents/dS9ps52MUnxQfyDGPfkY).
* Contributions: Google Python [Style Guide](https://google.github.io/styleguide/pyguide.html#doc-function-args), Google Engineering Code of Ethics, SRE document confidentiality policy.

**[J9 Java VM](https://en.wikipedia.org/wiki/OpenJ9) Software Developer at IBM**
*Ottawa, Ontario | June 2010 – Dec 2015 | 6 years*

* Worked primarily in Garbage Collection team. Developed: [NUMA-aware](https://ieeexplore.ieee.org/document/8498195) garbage collection algorithms,  PowerPC "[read barrier"](https://content.ikr.uni-stuttgart.de/en/Content/Publications/Archive/Me_ismm22_36512.pdf) instructions and [region-based](https://github.com/BlendedFeelings/software/blob/main/memory-management/garbage-collection/region-based-garbage-collection.md) garbage collection.
* Worked on [Reliability, Availability, Serviceability](https://en.wikipedia.org/wiki/Reliability,_availability_and_serviceability) team, as developer support for customer issues. Work includes: [Core-File](https://en.wikipedia.org/wiki/Core_dump) inspection, [Linux performance](https://www.brendangregg.com/linuxperf.html) analysis.

**Intern at [Object Technology International](https://en.wikipedia.org/wiki/Object_Technology_International)**
*Ottawa, Ontario | June 2021 – May 2022 | 1 year*

* Developed [Smalltalk](https://en.wikipedia.org/wiki/Smalltalk) ([Eclipse](https://en.wikipedia.org/wiki/Eclipse_(software))) IDE tooling.
* Developed inline assembly code generation infrastructure for building [JNI](https://en.wikipedia.org/wiki/Java_Native_Interface) [call stacks](https://en.wikipedia.org/wiki/Call_stack).

## Projects

**Company Fit Interview**
*Question and rubrics to use when deciding if a company is a good fit for you.*

* See [laipn.github.io/company-fit](http://laipn.github.io/company-fit)
* A ["structured"](https://pmc.ncbi.nlm.nih.gov/articles/PMC9553626/) company-fit interview process designed to remove bias when choosing prospective companies.
* Also provides prospective companies a way to see if I am a good fit for them.

**Docker Media Server**
*A home media-server providing a netflix-like experience with media served from torrent/usenet clients*

* See [github.com/laipn/docker-media-server](http://github.com/laipn/docker-media-server).
* Integrates ~12 different services running inside a docker-ized network.  Security implement with Oauth2 and Traefik as reverse-proxy.
* Demonstrates working knowledge of modern deployment and production practices.

***

## Skills

* **Programming Languages**
  * **Fluent**: Python, C
  * **Intermediate** *(has written code in)*: C++, Java, Bash
  * **Basic** *(can read some)*: Go
* *Wish I knew more of*: Rust, Haskell, Machine Learning

***

## Education

**Bachelor of Engineering (with distinction) in Computer Engineering**
*University of Alberta | 2005 – 2010*

***

## Languages

* **English**: Fluent
* **French**: Intermediate
* **Vietnamese**: Basic

***

## Interests

* **Hobbies**: Home Automation (<https://laipn.duckdns.org:8123>, user/pass: borg-sre/borg-sre), amateur electrical engineering (fixing appliances, soldering, rigging speakers, LEDs, micro-controllers, etc)

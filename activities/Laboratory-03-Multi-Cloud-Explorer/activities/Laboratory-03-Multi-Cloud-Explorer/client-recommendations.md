# Client Recommendations

## Client A – Startup Company

**Scenario:** Startup na naglulunsad ng mobile application, limitado ang budget, pero umaasang mabilis lumaki sa susunod na mga taon.

**Recommended Platform: Amazon Web Services (AWS)**

Angkop ang AWS para sa startup na tulad ni Client A dahil sa flexible pay-as-you-go pricing model nito, kung saan babayaran lang nila ang aktwal na ginagamit na resources — perpekto para sa limitadong budget. Bukod dito, madali itong i-scale habang lumalaki ang application, kaya hindi na nila kailangang mag-migrate sa ibang platform kapag dumami na ang users. Malaki rin ang tulong ng AWS Free Tier at mga startup credit programs (tulad ng AWS Activate) na nagbibigay ng discounted o libreng access sa mga bagong negosyo. Dahil sa laki ng community at documentation ng AWS, mas madali ring makahanap ng mga developer na may kaalaman dito.

**Services na maaaring gamitin:**
1. **AWS Lambda** – para sa serverless backend, walang bayad kung walang traffic
2. **Amazon S3** – para sa storage ng app assets at user data
3. **Amazon EC2 (with Auto Scaling)** – para awtomatikong dumagdag ng servers habang lumalaki ang users

---

## Client B – University

**Scenario:** Gumagamit na ng Windows Server, Microsoft 365, at Active Directory. Gustong i-migrate ang ilang services sa cloud.

**Recommended Platform: Microsoft Azure**

Pinaka-angkop ang Azure para sa Client B dahil direktang naka-integrate ito sa mga umiiral na na Microsoft technologies ng unibersidad — Windows Server, Microsoft 365, at Active Directory. Ang migration papunta sa Azure ay magiging mas madali at mabilis dahil hindi na kailangang mag-alala sa compatibility issues. Bukod dito, may mga espesyal na academic pricing at Azure for Education programs ang Microsoft na maaaring makatipid nang malaki sa mga unibersidad. Ang hybrid cloud capability ng Azure ay nagbibigay-daan din sa unibersidad na unti-unting mag-migrate nang hindi kaagad iniiwan ang kanilang on-premises infrastructure.

**Services na maaaring gamitin:**
1. **Azure Active Directory** – para sa seamless na pag-manage ng user identities, kaugnay ng existing AD nila
2. **Azure Virtual Machines** – para i-migrate ang mga umiiral na Windows Server workloads
3. **Microsoft 365 + Azure integration** – para sa collaboration tools ng mga estudyante at faculty

---

## Client C – AI Research Company

**Scenario:** Nagde-develop ng Artificial Intelligence at Machine Learning applications na nangangailangan ng high-performance computing.

**Recommended Platform: Google Cloud Platform (GCP)**

Ang GCP ang pinakamainam na pagpipilian para kay Client C dahil ito ang kilala bilang pinakamalakas na platform pagdating sa AI at Machine Learning. Ang mga tools tulad ng Vertex AI at TensorFlow (na parehong ginawa ng Google) ay partikular na dinisenyo para sa mabilis na pagde-develop at pag-deploy ng ML models. Bukod dito, may access ang GCP sa mga advanced na hardware tulad ng TPUs (Tensor Processing Units) na optimized talaga para sa machine learning workloads, na hindi katulad na inaalok ng ibang providers. Ang malakas na data analytics capability nito (BigQuery) ay makakatulong din sa pagproseso ng malalaking datasets na kailangan sa AI research.

**Services na maaaring gamitin:**
1. **Vertex AI** – para sa pag-train at pag-deploy ng machine learning models
2. **BigQuery** – para sa mabilis na pag-analyze ng malalaking research datasets
3. **Compute Engine (with GPU/TPU support)** – para sa high-performance computing power na kailangan sa AI training

---

## Client D – Global E-Commerce Company

**Scenario:** Multinational online shopping company, kailangan ng highly available infrastructure na may automatic scaling.

**Recommended Platform: Amazon Web Services (AWS)**

Angkop ang AWS para kay Client D dahil sa pinakamalawak na global infrastructure footprint nito — pinakamaraming Regions at Availability Zones sa buong mundo — na nagbibigay-daan sa mataas na availability at mababang latency saanman ang mga customer. May mature at proven na track record din ang AWS sa pag-handle ng malalaking e-commerce platforms (kabilang na ang Amazon.com mismo), kaya may mga battle-tested na tools para sa auto-scaling at fault tolerance. Ang CloudFront CDN nito ay nagpapabilis ng pag-deliver ng content sa mga customer sa iba't ibang bansa.

**Services na maaaring gamitin:**
1. **Amazon EC2 with Auto Scaling** – para awtomatikong mag-adjust ng resources base sa traffic
2. **Amazon CloudFront** – CDN para sa mabilis na content delivery sa mga global customers
3. **Amazon RDS (Multi-AZ)** – para sa highly available at fault-tolerant na database

---

## Multi-Cloud Decision Matrix (Checkpoint 6)

| Business Need | Recommended Platform | Why |
|---|---|---|
| Limited budget, rapid growth (startup) | **AWS** | Flexible pricing, scalability, startup credits |
| Existing Microsoft ecosystem | **Azure** | Seamless integration with Windows Server, AD, M365 |
| AI/ML & high-performance computing | **GCP** | Best-in-class AI tools (Vertex AI), TPU access |
| Global scale & high availability | **AWS** | Widest global infrastructure, proven e-commerce track record |
| Hybrid cloud (on-premises + cloud) | **Azure** | Strong hybrid cloud tools (Azure Arc, Region Pairs) |
| Big data analytics | **GCP** | BigQuery, strong data processing tools |
| General-purpose / widest service range | **AWS** | Largest service catalog, market leader |

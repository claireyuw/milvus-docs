---
id: milvus_distributions-cpu.md
label: CPU-only Milvus
order: 0
group: distribution
---

# Milvus Distributions

{{tab}} 

## Overview


{{fragments/distributions.md}}



## Indexes for CPU-only Milvus

<div class="filter">
<a href="#floating">Floating point embeddings</a> <a href="#binary">Binary embeddings</a>
</div>

<div class="table-wrapper filter-floating" markdown="block">

| Index type       | Indexing with CPU | Search with CPU |
| -------- | ----------------- | -------------- |
| FLAT     | N/A                 | ✔️           |
| IVF_FLAT | ✔️                | ✔️            |
| IVF_SQ8  | ✔️                | ✔️            |
| IVF_PQ   | ✔️                | ✔️            |
| RNSG     | ✔️                | ✔️            |
| HNSW     | ✔️                | ✔️            |
| ANNOY    | ✔️                | ✔️            |

</div>

<div class="table-wrapper filter-binary" markdown="block">

| Index type      | Index building with CPU | Search with CPU |
| -------- | ----------------- | -------------- |
| FLAT     | N/A                | ✔️           |
| IVF_FLAT | ✔️                | ✔️            |

</div>

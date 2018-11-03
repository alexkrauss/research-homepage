+++
title = "Scalable LCF-style proof translation"
date = 2013-01-01

authors = ["Alexander Krauss", "Cezary Kaliszyk"]
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Sandrine Blazy, Christine Paulin-Mohring, and David Pichardie, editors, Interactive Theorem Proving (ITP 2013), volume 7998 of Lecture Notes in Computer Science, pages 51-66. Springer Verlag, 2013"
publication_short = "Interactive Theorem Proving (ITP 2013)"

# Abstract and optional shortened version.
abstract = "All existing translations between proof assistants have been notoriously sluggy, resource-demanding, and do not scale to large developments, which has lead to the general perception that the whole approach is probably not practical. We aim to show that the observed inefficiencies are not inherent, but merely a deficiency of the existing implementations. We do so by providing a new implementation of a theory import from HOL Light to Isabelle/HOL, which achieves decent performance and scalability mostly by avoiding the mistakes of the past. After some preprocessing, our tool can import large HOL Light developments faster than HOL Light processes them. Our main target and motivation is the Flyspeck development, which can be imported in a few hours on commodity hardware. We also provide mappings for most basic types present in the developments including lists, integers and real numbers. This papers outlines some design considerations and presents a few of our extensive measurements, which reveal interesting insights in the low-level structure of larger proof developments."
abstract_short = ""

# Links (optional).
url_pdf = "papers/proof-translation-itp13.pdf"
url_source = "http://dx.doi.org/10.1007/978-3-642-39634-2_7"

+++

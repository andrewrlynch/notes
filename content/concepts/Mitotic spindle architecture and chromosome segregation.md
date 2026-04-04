---
cluster: true
created: '2026-03-31'
createdBy: fossick
elevated_at: []
hub: false
hub_score: 0
members:
- '[[concepts/anaphase|anaphase]]'
- '[[concepts/bipolar cell division|bipolar cell division]]'
- '[[concepts/bipolar spindle assembly|bipolar spindle assembly]]'
- '[[concepts/centrosome clustering|centrosome clustering]]'
- '[[concepts/centrosomes|centrosomes]]'
- '[[concepts/chromosome missegregation|chromosome missegregation]]'
- '[[concepts/diploid|diploid]]'
- '[[concepts/kinetochore|kinetochore]]'
- '[[concepts/lagging chromosomes|lagging chromosomes]]'
- '[[concepts/merotely|merotely]]'
- '[[concepts/microtubule|microtubule]]'
- '[[concepts/microtubule chromosome attachment|microtubule chromosome attachment]]'
- '[[concepts/multipolar cell division|multipolar cell division]]'
- '[[concepts/multipolar spindle intermediate|multipolar spindle intermediate]]'
- '[[concepts/multipolar spindles|multipolar spindles]]'
- '[[concepts/phenotypic changes|phenotypic changes]]'
- '[[concepts/spindle assembly checkpoint|spindle assembly checkpoint]]'
modified: '2026-03-31'
order: 2
sources: []
synthesis_status: none
tags: []
title: Mitotic spindle architecture and chromosome segregation
type: concept
---

The mitotic spindle is a bipolar structure assembled from microtubules nucleated at [[concepts/centrosomes|centrosomes]] that mediates accurate chromosome segregation during cell division. In normal [[concepts/mitosis|mitosis]], centrosomes organize two opposing spindle poles, microtubules attach to kinetochores at chromosome centromeres, and the [[concepts/spindle assembly checkpoint|spindle assembly checkpoint]] ensures proper attachments before permitting [[concepts/anaphase|anaphase]], when sister chromatids separate and move to opposite poles. This orchestrated process maintains diploidy by delivering one complete chromosome set to each daughter cell.

Cells with extra centrosomes face the challenge of organizing a functional bipolar spindle from multiple potential poles. Through [[concepts/centrosome clustering|centrosome clustering]], supernumerary centrosomes aggregate into two functional poles, enabling bipolar rather than [[concepts/multipolar cell division|multipolar cell division]] and preventing the lethal outcome of massively [[concepts/aneuploid|aneuploid]] progeny. However, the [[concepts/multipolar spindle intermediate|multipolar spindle intermediate]] that transiently forms during this clustering process creates conditions for erroneous [[concepts/microtubule|microtubule]]-chromosome attachments. [[concepts/merotely|Merotely]], in which a single [[concepts/kinetochore|kinetochore]] captures microtubules from both spindle poles, is a particularly consequential error that can evade checkpoint detection because the kinetochore remains attached. Merotelic attachments generate [[concepts/lagging chromosomes|lagging chromosomes]] during anaphase that fail to segregate properly, resulting in [[concepts/chromosome missegregation|chromosome missegregation]] even after successful bipolar spindle formation.

The relationship between classic mitotic defects and [[concepts/chromosomal instability|chromosomal instability]] remains contested. While extra centrosomes promote chromosome missegregation through the mechanism described above, chromosomal instability can exist independently of these classic mitotic defects in most cells, suggesting additional mechanisms beyond spindle architecture errors. Furthermore, chromosome missegregation alone appears insufficient for aneuploid cell propagation, indicating that [[concepts/phenotypic changes|phenotypic changes]] and selection pressures determine which missegregation events contribute to stable aneuploidy. The extent to which merotely causes chromosome missegregation specifically in unstable versus stable near-[[concepts/diploid|diploid]] cells, and whether elevated merotely is the primary driver of chromosomal instability in near-diploid contexts, remain areas of active investigation.

## Member Concepts
- [[concepts/anaphase|anaphase]]
- [[concepts/bipolar cell division|bipolar cell division]]
- [[concepts/bipolar spindle assembly|bipolar spindle assembly]]
- [[concepts/centrosome clustering|centrosome clustering]]
- [[concepts/centrosomes|centrosomes]]
- [[concepts/chromosome missegregation|chromosome missegregation]]
- [[concepts/diploid|diploid]]
- [[concepts/kinetochore|kinetochore]]
- [[concepts/lagging chromosomes|lagging chromosomes]]
- [[concepts/merotely|merotely]]
- [[concepts/microtubule|microtubule]]
- [[concepts/microtubule chromosome attachment|microtubule chromosome attachment]]
- [[concepts/multipolar cell division|multipolar cell division]]
- [[concepts/multipolar spindle intermediate|multipolar spindle intermediate]]
- [[concepts/multipolar spindles|multipolar spindles]]
- [[concepts/phenotypic changes|phenotypic changes]]
- [[concepts/spindle assembly checkpoint|spindle assembly checkpoint]]

## Tensions
- **centrosome clustering vs chromosome missegregation:** Centrosome clustering is a corrective mechanism that prevents lethal multipolar cell division by reducing extra centrosomes to a bipolar arrangement. However, the multipolar spindle intermediate that forms during clustering promotes merotelic attachments that cause chromosome missegregation. Resolving this tension requires understanding whether clustering is primarily protective or error-promoting, and whether its net effect varies by cellular context.
- **spindle assembly checkpoint vs merotely:** The spindle assembly checkpoint delays anaphase until all chromosomes achieve proper microtubule attachment, serving as a fidelity mechanism. Merotelic attachments evade this checkpoint because the affected kinetochore remains attached to microtubules from both poles, satisfying checkpoint requirements despite being erroneous. Understanding this tension requires determining what attachment features the checkpoint actually monitors and why merotely escapes detection.
- **extra centrosomes promote chromosome missegregation vs CIN exists independently of classic mitotic defects:** Extra centrosomes are documented to promote chromosome missegregation through multipolar intermediates and merotelic attachments, suggesting mitotic defects drive chromosomal instability. However, chromosomal instability exists independently of these classic mitotic defects in most cells. Reconciling this requires identifying alternative missegregation mechanisms and determining what fraction of CIN derives from centrosome-dependent versus centrosome-independent pathways.

## Open Questions
- What molecular mechanisms distinguish merotelic attachments that resolve correctly from those that persist through anaphase and cause missegregation?
- Does the duration or geometry of the multipolar spindle intermediate quantitatively predict the frequency of subsequent chromosome missegregation?
- Why does chromosome missegregation alone appear insufficient for aneuploid cell propagation, and what additional phenotypic changes enable missegregated cells to survive and proliferate?
- Through what mechanisms does chromosomal instability arise independently of extra centrosomes and classic mitotic defects in stable near-diploid cells?
- Do cells with elevated merotely but normal centrosome numbers experience chromosomal instability at rates comparable to cells with extra centrosomes?
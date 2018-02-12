# prioritizr: Systematic conservation prioritization in R

Jeffrey O. Hanson$^1$, Richard Schuster$^{2,3}$, Nina Morrell$^4$, Matthew Strimas-Mackey$^5$, Matthew E. Watts$^1$, Peter Arcese$^4$, Joeseph R. Bennett$^2$, Hugh P. Possingham$^{1,6}$.

$^1$School of Biological Sciences, The University of Queensland, Brisbane, QLD 4072, Australia
$^2$Department of Biology, 1125 Colonel By Drive, Carleton University, Ottawa ON, K1S 5B6 Canada
$^3$Ecosystem Science and Management Program, 3333 University Way, University of Northern British Columbia, Prince George BC, V2N 4Z9 Canada
$^4$Department of Forest and Conservation Sciences, 2424 Main Mall, University of British Columbia, Vancouver BC, V6T 1Z4 Canada
$^5$ Department of Zoology, University of British Columbia, Vancouver, British Columbia, Canada
$^6$The Nature Conservancy, South Brisbane, QLD, Australia

**Keywords**: conservation, space/time, reproducibility, performance

Biodiversity is in crisis. To prevent further declines, protected areas and other cost-effective management areas need to be established in places that will achieve conservation objectives for minimal cost. However, existing decision support tools tend to offer limited customizability and can take a long time to deliver solutions. To overcome these limitations and help prioritize conservation efforts in a transparent and reproducible manner, here we present the prioritizr R package. Inspired by the tidyverse principles, this R package provides a flexible interface for articulating and building conservation planning problems---meaning that users can find the solutions to their problems. In contrast to conventional decision support tools, the prioritizr R package uses integer linear programming (ILP) techniques to mathematically formulate and solve conservation planning problems. As a consequence, the prioritizr R package can find solutions that are guaranteed to be optimal and in record time. By finding solutions to problems that are relevant to the species, ecosystems, and economic factors in areas of interest, conservation scientists, planners, and decision makers stand a far greater chance at enhancing biodiversity. For more information on the prioritizr R package, visit https://github.com/prioritizr/prioritizr.

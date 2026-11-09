# Relay Lab

Three short browser activities for the combined session on axonal conduction and
synapses (Sessions 10–12) of *Introduction to Neuroscience* (Krea University).
Students use it beside the slides.

1. **The race.** How axon diameter and myelin set conduction speed, and what damaged
   myelin (as in multiple sclerosis) does. Two electrodes 10 cm apart, as in a clinical
   nerve conduction test.
2. **Adding up.** The six steps of a chemical synapse (put in order), then spatial and
   temporal summation and inhibition in a model neuron.
3. **Keys and locks.** Ion-channel versus G-protein receptors, and how agonists,
   antagonists and clearance (reuptake/enzyme) blockers change a synaptic response.

**Privacy:** nothing is saved or sent. Everything runs in the student's browser tab.

## The models (stated honestly in the lab as well)

- **Part 1** is not a simulation. Speeds follow rules of thumb fitted to real nerves:
  about 6 m/s per µm of diameter for myelinated mammalian axons (Hursh, 1939), and about
  √(diameter in µm) m/s for bare axons (giving ~1 m/s for a 1 µm pain fibre and ~22 m/s
  for a 500 µm squid giant axon). The damaged-myelin patch covers 3 of the 10 cm and
  conducts like a bare axon of the same diameter.
- **Part 2** is a conductance-based leaky integrate-and-fire neuron (membrane time
  constant 15 ms, rest −65 mV, threshold −50 mV). Each excitatory input gives about 7 mV,
  so three are needed together; one input repeated three times fires the neuron if the
  inputs are at most 7 ms apart. Real CNS EPSPs are usually much smaller.
- **Part 3** is a simplified kinetic model in arbitrary units: transmitter clearance,
  receptor binding, and either a direct (ion channel) or a slow, cascade-driven (G-protein)
  response. Antagonist blocks 85% of receptors; clearance blocker slows clearance 8×;
  agonist produces a tonic response of 70% of the normal peak.



## Credits

Built with jsPsych 7.3.4 (de Leeuw, 2015, *Behavior Research Methods* 47, 1–12; MIT
licence, in `lib/`). Content follows Bear, Connors & Paradiso, *Neuroscience: Exploring
the Brain* (4th ed.), Chapters 4–6.

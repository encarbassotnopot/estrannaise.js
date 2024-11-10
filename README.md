### estrannaise.js
estrannaise.js is a small playground for estradiol pharmacokinetics. It can simulate estradiol blood levels under arbitrary dosing regimes and schedules. In the near future it will allow users to infer model parameters from outside sources, including their own personal blood levels.

Under the hood, estrannaise.js uses pharmacokinetic compartments models and MCMC inference using a simple Gaussian model with mixed effects or for more complicated pooled dataset our very own homebrewed hierarchical Bayesian model called Emix.

### Changelog
- 2024-11-10: New warning, css tweaks
- [lost to history]

### TODO
- Backfill changelog
- Add visual markers for dose times
- Save/load from localStorage
- Automatically remove double empty tailing input lines
- Offer different ways to visualize the uncertainty (parallel sigma lines and cloud ensemble of curves)
- Deal with customdose visibilities and table differently.
- Allow possibility of changing patch wear time
- Oral/sublingual/iv/gel models
- Re-organize the mess of pk/math notes

### Disclaimer
estrannaise.js is designed as a playground to explore estradiol pharmacokinetics and provides a simulation for informational and entertainment purposes only. The developer(s) cannot guarantee the accuracy of the predictions generated by the simulator. Users acknowledge that the software is offered "as is," without any warranties. The developer(s) assume no liability for direct or indirect damages, either physical, psychological, or otherwise, resulting from the use of the simulator. Users are strongly advised to exercise caution and seek professional medical advice for health-related queries.

**estrannaise.js is entirely client-side. Your data, whether entered, imported, or stashed, remains exclusively within your browser and will never be transmitted to the developer(s) or any third-party.**


### Contact
If this kind of thing interests you, you can contact me on signal a1ix2.91 or by email \_a1ix2\_at\_proton\_dot\_me\_.
For feedback, bugs, and feature requests submit an issue on github.
### estrannaise.js
estrannaise.js is a small playground for estradiol pharmacokinetics. It can simulate estradiol blood levels under arbitrary dosing regimes and schedules. In the near future it will allow users to infer model parameters from outside sources, including their own personal blood levels.

Under the hood, estrannaise.js uses pharmacokinetic compartments models and MCMC inference using a simple Gaussian model with mixed effects or for more complicated pooled dataset our very own homebrewed hierarchical Bayesian model called Emix.

### Usage

```
git clone https://github.com/WHSAH/estrannaise.js
cd estrannaise.js
python -m http.server 8000
```
and then direct your browser to <http://127.0.0.1:8000>.

### Changelog
- 2025-02-18: Reorganized text, clarified differences with TFS sim.
- 2024-12-20: New EUn im model, added reference section, shorter bottom text
- 2024-12-09: v0.4.0 improved EV/EEn/EC/EB models, added fudge factor
- 2024-12-08: Save state/data/theme to localStorage
- 2024-11-15: Switched deps to ESM, minor formatting
- 2024-11-10: New warning, css tweaks, contact info
- [lost to history]

### TODO
- Add visual markers for dose times
- Add tutorial
- Screen-reader accessible
- Access to traditional PK quantities
- Automatically remove double empty tailing input lines
- Offer different ways to visualize the uncertainty or switch to ±sigma band
- Deal with customdose visibilities and table differently.
- Allow possibility of changing patch wear time
- Oral/sublingual/iv/gel models
- Re-organize the mess of pk/math notes
- Template all the things (logo/title, bottom text, banner, plotting labels/axes)
- Use version as hide-banner flag
- *bug:* button styles don't reset after mouseleave before mouseup

### Disclaimer
estrannaise.js is designed as a playground to explore estradiol pharmacokinetics and provides a simulation for informational and entertainment purposes only. The developer(s) cannot guarantee the accuracy of the predictions generated by the simulator. Users acknowledge that the software is offered "as is," without any warranties. The developer(s) assume no liability for direct or indirect damages, either physical, psychological, or otherwise, resulting from the use of the simulator. Users are strongly advised to exercise caution and seek professional medical advice for health-related queries.

**estrannaise.js is entirely client-side. Your data, whether entered, imported, stashed, or loaded from a shared url, remains exclusively within your browser and will never be transmitted to the developer(s) or any third-party by our application.**

### Contact
If this kind of thing interests you, you can contact me on signal a1ix2.91 or by email \_a1ix2\_at\_proton\_dot\_me\_.
For feedback, bugs, and feature requests submit an issue on github.
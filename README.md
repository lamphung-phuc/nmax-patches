# NMAX Patches

Morphe patches that let [NmaxConnect](https://github.com/lamphung-phuc/nmax_connect) show Google Maps or Waze
navigation on the Yamaha NMAX dash. You patch the app on your own phone with Morphe Manager; no patched APK is
shared here.

### How to use these patches

1. Install [NmaxConnect](https://github.com/lamphung-phuc/nmax_connect/releases/latest) and
   [Morphe Manager](https://morphe.software).
2. Add this patch source in Morphe Manager: tap the button below on your phone, or add
   `https://github.com/lamphung-phuc/nmax-patches` by hand.

   <a href="https://morphe.software/add-source?github=lamphung-phuc/nmax-patches">
     <img src=".github/assets/add-to-morphe.svg" alt="Add to Morphe" height="48">
   </a>
3. Patch the app you want. Morphe Manager shows which version to download.
   - **Waze NMAX**: Waze 5.27.0.1. Installs next to Waze, with its own login.
   - **Google Maps NMAX**: also install [MicroG-RE 7.3.0](https://github.com/MorpheApp/MicroG-RE/releases) and keep
     Google Play Services. In MicroG-RE, allow location and turn on BeaconDB, or Maps cannot find you.
4. Open NmaxConnect and pick Waze NMAX or Google Maps NMAX as the dash map.

## 🩹 Patches list

<!-- PATCHES_START EXPANDED -->
#### The patch list appears here after the first release.
<!-- PATCHES_END -->

## Credits

The Google Maps patches are based on [fangkampanat/gmaps-patches](https://github.com/fangkampanat/gmaps-patches), built
with [Morphe](https://github.com/MorpheApp). GNU General Public License v3.0, with the additional GPL section 7
requirements in [NOTICE](NOTICE). Not affiliated with Google, Waze, Yamaha or the Morphe project.

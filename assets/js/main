(function () {
  function initSite() {
    if (window.PrestigeTabs && typeof window.PrestigeTabs.initTabs === "function") {
      window.PrestigeTabs.initTabs();
    }

    if (window.PrestigeCalculator && typeof window.PrestigeCalculator.initCalculator === "function") {
      window.PrestigeCalculator.initCalculator();
    }

    if (window.PrestigeBooking && typeof window.PrestigeBooking.initBooking === "function") {
      window.PrestigeBooking.initBooking();
    }
  }

  if (document.readyState === "loading") {
    document.addEventListener("DOMContentLoaded", initSite);
  } else {
    initSite();
  }
})();

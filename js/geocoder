document.addEventListener("DOMContentLoaded", function () {
    let geocoderControl = document.querySelector(".leaflet-control-geocoder");

    geocoderControl.addEventListener("click", function () {
        this.classList.toggle("expanded");
    });

    // Close if user clicks outside
    document.addEventListener("click", function (event) {
        if (!geocoderControl.contains(event.target)) {
            geocoderControl.classList.remove("expanded");
        }
    });
});

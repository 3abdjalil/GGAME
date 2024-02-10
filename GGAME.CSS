document.addEventListener("DOMContentLoaded", function() {
    // Check if geolocation is supported by the browser
    if (navigator.geolocation) {
        // Request the user's location
        navigator.geolocation.getCurrentPosition(successCallback, errorCallback);
    } else {
        console.log("Geolocation is not supported by this browser.");
    }
});

function successCallback(position) {
    // Get latitude and longitude
    const latitude = position.coords.latitude;
    const longitude = position.coords.longitude;
    
    // Do something with the user's location (e.g., display on map, fetch nearby stores)
    console.log("Latitude:", latitude);
    console.log("Longitude:", longitude);
}

function errorCallback(error) {
    switch(error.code) {
        case error.PERMISSION_DENIED:
            console.log("User denied the request for Geolocation.");
            break;
        case error.POSITION_UNAVAILABLE:
            console.log("Location information is unavailable.");
            break;
        case error.TIMEOUT:
            console.log("The request to get user location timed out.");
            break;
        case error.UNKNOWN_ERROR:
            console.log("An unknown error occurred.");
            break;
    }
}

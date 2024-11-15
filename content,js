(function() {
    'use strict';

    function scanAndClick() {
        const inputs = document.querySelectorAll('input');
        const acceptInputs = Array.from(inputs).filter(input => input.value.includes("Accept and Connect"));

        if (acceptInputs.length > 0) {
            acceptInputs[0].click();
            console.log("Clicked the first 'Accept and Connect' input.");
        }
    }

    setInterval(scanAndClick, 1000);
})();

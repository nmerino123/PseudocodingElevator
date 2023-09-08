# BEGIN
    pax inputs floor
        WHILE(current floor != input floor) {
            IF input floor is more than current floor
                travel up to input floor
            ELSE
                travel down to input floor
            open door
    pax gets on/off
            close door
        }
# END

function getVal() {
  const val = document.querySelector('input').value;
  console.log(val);
}

var going = 9;
var on = 3;
if(going < on){
    while (going < on){
        console.log(on);
        on = on -1
    };
} else {
    while (going > on){
        console.log(on);
        on = on +1
    };
};
console.log("Here!")
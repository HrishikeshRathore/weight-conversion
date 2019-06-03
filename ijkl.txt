
//function for the conversion of Pounds to other units.
	
function weightConverter1(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*1; 
  document.getElementById("outputOunce").innerHTML=valNum*16;
  document.getElementById("outputKilograms").innerHTML=valNum/2.2046;
  document.getElementById("outputStone").innerHTML=valNum/14;
  document.getElementById("outputMetrictonnes").innerHTML=valNum/2204.62262;
  document.getElementById("outputTroyPounds").innerHTML=valNum*1.2152778;
  document.getElementById("outputGrams").innerHTML=valNum*453.59237;
  document.getElementById("outputMilligrams").innerHTML=valNum*453592.37;
  document.getElementById("outputMicrograms").innerHTML=valNum*453592370;
}

//function for the conversion of Ounces to other units.

function weightConverter2(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*.0625;
  document.getElementById("outputOunce").innerHTML=valNum*1;
  document.getElementById("outputKilograms").innerHTML=valNum*.0283495;
  document.getElementById("outputStone").innerHTML=valNum*.00446429;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*2.835e-5;
  document.getElementById("outputTroyPounds").innerHTML=valNum*.0759549;
  document.getElementById("outputGrams").innerHTML=valNum*28.3495;
  document.getElementById("outputMilligrams").innerHTML=valNum*28349.5;
  document.getElementById("outputMicrograms").innerHTML=valNum*28349523.1;
}

//function for the conversion of Kilograms to other units.

function weightConverter3(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*2.20462; 
  document.getElementById("outputOunce").innerHTML=valNum*35.274;
  document.getElementById("outputKilograms").innerHTML=valNum*1;
  document.getElementById("outputStone").innerHTML=valNum*.157473;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*.001;
  document.getElementById("outputTroyPounds").innerHTML=valNum*2.6792;
  document.getElementById("outputGrams").innerHTML=valNum*1000;
  document.getElementById("outputMilligrams").innerHTML=valNum*1000000;
  document.getElementById("outputMicrograms").innerHTML=valNum*1000000000;
}

//function for the conversion Stones to other units.

function weightConverter4(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*14; 
  document.getElementById("outputOunce").innerHTML=valNum*224;
  document.getElementById("outputKilograms").innerHTML=valNum*6.35029;
  document.getElementById("outputStone").innerHTML=valNum*1;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*.00635029;
  document.getElementById("outputTroyPounds").innerHTML=valNum*17.0139;
  document.getElementById("outputGrams").innerHTML=valNum*6350.29;
  document.getElementById("outputMilligrams").innerHTML=valNum*6350293.18;
  document.getElementById("outputMicrograms").innerHTML=valNum*6350293180;
}

//function for the conversion of Metrictons to other units.

function weightConverter5(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*2204.62; 
  document.getElementById("outputOunce").innerHTML=valNum*35274;
  document.getElementById("outputKilograms").innerHTML=valNum*1000;
  document.getElementById("outputStone").innerHTML=valNum*157.473;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*1;
  document.getElementById("outputTroyPounds").innerHTML=valNum*2679.23;
  document.getElementById("outputGrams").innerHTML=valNum*1000000;
  document.getElementById("outputMilligrams").innerHTML=valNum*1000000000;
  document.getElementById("outputMicrograms").innerHTML=valNum*1000000000000;
}

//function for the conversion of Troypounds to other units.

function weightConverter6(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*.822857; 
  document.getElementById("outputOunce").innerHTML=valNum*13.1657;
  document.getElementById("outputKilograms").innerHTML=valNum*.373242;
  document.getElementById("outputStone").innerHTML=valNum*.058775;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*.00037324;
  document.getElementById("outputTroyPounds").innerHTML=valNum*1;
  document.getElementById("outputGrams").innerHTML=valNum*373.24;
  document.getElementById("outputMilligrams").innerHTML=valNum*373241.721;
  document.getElementById("outputMicrograms").innerHTML=valNum*373241721;
}

//function for the conversion of Grams to other units.

function weightConverter7(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*.0022; 
  document.getElementById("outputOunce").innerHTML=valNum*.0353;
  document.getElementById("outputKilograms").innerHTML=valNum*.001;
  document.getElementById("outputStone").innerHTML=valNum*.000157;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*1e-6;
  document.getElementById("outputTroyPounds").innerHTML=valNum*.00267923;
  document.getElementById("outputGrams").innerHTML=valNum*1;
  document.getElementById("outputMilligrams").innerHTML=valNum*1000;
  document.getElementById("outputMicrograms").innerHTML=valNum*1000000;
}

//function for the conversion of Milligrams to other units.

function weightConverter8(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*2.205e-6; 
  document.getElementById("outputOunce").innerHTML=valNum*3.527e-5;
  document.getElementById("outputKilograms").innerHTML=valNum*1e-6;
  document.getElementById("outputStone").innerHTML=valNum*1.575e-7;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*1e-9;
  document.getElementById("outputTroyPounds").innerHTML=valNum*.0000026792;
  document.getElementById("outputGrams").innerHTML=valNum*.001;
  document.getElementById("outputMilligrams").innerHTML=valNum*1;
  document.getElementById("outputMicrograms").innerHTML=valNum*1000;
}

//function for the conversion of Micrograms to other units.

function weightConverter9(valNum) {
  document.getElementById("outputPounds").innerHTML=valNum*2.205e-9; 
  document.getElementById("outputOunce").innerHTML=valNum*3.527e-8;
  document.getElementById("outputKilograms").innerHTML=valNum*1e-9;
  document.getElementById("outputStone").innerHTML=valNum*1.575e-10;
  document.getElementById("outputMetrictonnes").innerHTML=valNum*1e-12;
  document.getElementById("outputTroyPounds").innerHTML=valNum*2.6792e-9;
  document.getElementById("outputGrams").innerHTML=valNum*1e-6;
  document.getElementById("outputMilligrams").innerHTML=valNum*.001;
  document.getElementById("outputMicrograms").innerHTML=valNum*1;
}

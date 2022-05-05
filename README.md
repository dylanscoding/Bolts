Programmer: Dylan Sabuda
Date: 5.4.2022
Program Name: Figure 8

async function startProgram() {
	
	setMainLed({ r: 0, g: 0, b: 255 });

	await speak("Figure 8", true);

	await setHeading(0)
	
	await delay(0.5)
	
	await setSpeed(100)
	
	for (let i=0; i<1 i++) {
		await spin(360,2.5)
		await spin(-360,2.5)
	}
	await stopRoll()
}

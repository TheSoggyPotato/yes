	]),
		new ModMenu.MenuTree('Factory', [
			new ModMenu.MenuButton('Get Cash', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/factory/getCash.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Get Mega Bot', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/factory/getMegaBot.js").then((res) => res.text().then((t) => eval(t)))),
		]),
		new ModMenu.MenuTree('Fishing Frenzy', [
			new ModMenu.MenuButton('Set Weight', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/fishing-frenzy/setWeight.js").then((res) => res.text().then((t) => eval(t)))),
		]),
		new ModMenu.MenuTree('Global', [
			new ModMenu.MenuButton('Add Tokens', (999999) => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/addTokens.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Get Every Answer Correct', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/getEveryCorrectAnswer.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Bypass Random Name', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/bypassRandomName.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Flood Games', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/floodGames.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Get All Blooks in Game', (999999) => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/getAllBlooksInGame.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Get Every Answer Correct', (999999) => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/getEveryCorrectAnswer.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Spam Open Boxes', (0) => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/global/spamOpenBoxes.js").then((res) => res.text().then((t) => eval(t)))),
		]),
		new ModMenu.MenuTree('Gold', [
			new ModMenu.MenuButton('Get Gold', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/gold/getGold.js").then((res) => res.text().then((t) => eval(t)))),
@@ -27,8 +34,14 @@
			new ModMenu.MenuButton('Instant Win', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/racing/instantWin.js").then((res) => res.text().then((t) => eval(t)))),
		]),
		new ModMenu.MenuTree('Tower Defense', [
			new ModMenu.MenuButton('All Free', (blooks) => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/allFree.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Change Game Round', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/changeGameRound.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Get Cash', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/getCash.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Get Damage', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/getDamage.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Remove Ducks', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/removeDucks.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Remove Enemies', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/removeEnemies.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Remove Obsticles', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/removeObsticles.js").then((res) => res.text().then((t) => eval(t)))),
			new ModMenu.MenuButton('Sell for True Value', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-defense/sellForTrueValue.js").then((res) => res.text().then((t) => eval(t)))),
		]),
		new ModMenu.MenuTree('Tower of Doom', [
			new ModMenu.MenuButton('Add Coins', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-of-doom/addCoins.js").then((res) => res.text().then((t) => eval(t)))),
@@ -37,4 +50,4 @@
			new ModMenu.MenuButton('Lower Enemy Wisdom', () => fetch("https://raw.githubusercontent.com/glixzzy/blooket-cheat/main/tower-of-doom/lowerEnemyWisdom.js").then((res) => res.text().then((t) => eval(t)))),
		]),
	]));
})();  
})(); 

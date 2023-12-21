---
description: 🌍Explore, create and live an immersive experience in our mobile metaverse!
---

# 📱Homiverse

🏞️ **Discover a captivating virtual world** 🌠

Homiverse is a mobile metaverse designed to provide a unique interactive experience for users. Immerse yourself in a rich and vivid virtual environment, where you can explore stunning landscapes, interact with other users and participate in a multitude of entertaining activities.



{% code lineNumbers="true" fullWidth="false" %}
```cpp
Unreal Engine 5.1 Build.
// Fill out your copyright notice in the Description page of Project Settings.


#include "testing.h"

// Sets default values
Atesting::Atesting()
{
 	// Set this character to call Tick() every frame.  You can turn this off to improve performance if you don't need it.
	PrimaryActorTick.bCanEverTick = true;

}

// Called when the game starts or when spawned
void Atesting::BeginPlay()
{
	Super::BeginPlay();
	
}

// Called every frame
void Atesting::Tick(float DeltaTime)
{
	Super::Tick(DeltaTime);

}

// Called to bind functionality to input
void Atesting::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent)
{
	Super::SetupPlayerInputComponent(PlayerInputComponent);

}
```
{% endcode %}



🚀 **Create your own adventure** 🎮

In Homiverse, you have the freedom to create and customize your own avatar, choosing from a variety of unique physical traits, outfits and accessories. Express your individuality and style by creating an avatar that looks like you.



🌟 **Participate in exciting activities** 🎉

Homiverse is full of interactive activities that will entertain you and stimulate your imagination. Participate in thrilling mini-games such as Reward Roulette, take part in challenges and quests to win valuable rewards, or engage in exciting role-playing games with other users.



💰 **Dynamic economy and NFT** 💎

Homiverse offers a dynamic economy powered by our HOMI token and our Era-Homi marketplace. Buy, sell and trade unique hominid NFTs, which are true digital works of art. Own rare and exclusive collectibles that can increase in value over time.



🌿 **Environmental commitment** 🌱

At Hominids, we are committed to environmental sustainability. Homiverse uses servers powered by renewable energy sources, reducing our carbon footprint. In addition, we support carbon offset initiatives to help preserve our planet.



🔒 **Security and Privacy** 🛡️

The security of our users is a top priority. We use robust security protocols to protect data and transactions. Your privacy is also respected, and you have full control over your personal information.

{% code title="Unreal Engine 5.1 Build." overflow="wrap" lineNumbers="true" %}
```unrealscript
{
	"FileVersion": 3,
	"EngineAssociation": "5.1",
	"Category": "",
	"Description": "",
	"Modules": [
		{
			"Name": "Homiverse",
			"Type": "Runtime",
			"LoadingPhase": "Default",
			"AdditionalDependencies": [
				"Engine"
			]
		}
	],
	"Plugins": [
		{
			"Name": "ModelingToolsEditorMode",
			"Enabled": true,
			"TargetAllowList": [
				"Editor"
			]
		},
		{
			"Name": "VaRest",
			"Enabled": true,
			"MarketplaceURL": "com.epicgames.launcher://ue/marketplace/content/e47be161e7a24e928560290abd5dcc4f"
		},
		{
			"Name": "SuiUnrealSDKCore",
			"Enabled": false
		},
		{
			"Name": "Bip39UE",
			"Enabled": false
		},
		{
			"Name": "LibsodiumUE",
			"Enabled": false
		}
	]
}
```
{% endcode %}

### **Fortnite Offsets**

**Version:** `++Fortnite-Release-36.30-CL-44367537`
**From:** Sternl's dump.
**Source:** [offsets.host](https://offsets.host) and [dumpspace.spuckwaffel.com](https://dumpspace.spuckwaffel.com)

```cpp
namespace offsets
{
    uintptr_t UWorld                       = 0x173AF320; // Globals -> UWorld
    uintptr_t GEngine                      = 0x14F97328; // Globals -> GEngine
    uintptr_t GNames                       = 0x151EA300; // Globals -> GNames

    uintptr_t OwningGameInstance           = 0x250;      // World -> OwningGameInstance
    uintptr_t GameState                    = 0x1D8;      // World -> GameState
    uintptr_t Levels                       = 0x1C0;      // World -> Levels

    uintptr_t LocalPlayers                 = 0x38;       // GameInstance -> LocalPlayers
    uintptr_t PlayerController             = 0x30;       // Player -> PlayerController

    uintptr_t AcknowledgedPawn             = 0x350;      // PlayerController -> AcknowledgedPawn
    uintptr_t TargetedFortPawn             = 0x18D0;     // FortPlayerController -> TargetedFortPawn

    uintptr_t PlayerState                  = 0x2C8;      // Pawn -> PlayerState
    uintptr_t RootComponent                = 0x1B0;      // Actor -> RootComponent
    uintptr_t Mesh                         = 0x328;      // Character -> Mesh
    uintptr_t CurrentWeapon                = 0xAF0;      // FortPawn -> CurrentWeapon
    uintptr_t bIsDying                     = 0x728;      // FortPawn -> bIsDying
    uintptr_t bIsABot                      = 0x2B2;      // FortPawn -> bIsABot (guessed)

    uintptr_t PawnPrivate                  = 0x320;      // PlayerState -> PawnPrivate
    uintptr_t PlayerNamePrivate            = 0x340;      // PlayerState -> PlayerNamePrivate
    uintptr_t Platform                     = 0x430;      // FortPlayerState -> Platform
    uintptr_t HabaneroComponent            = 0xA80;      // FortPlayerState -> HabaneroComponent
  
    uintptr_t TeamIndex                    = 0x1291;     // FortPlayerStateAthena -> TeamIndex
    uintptr_t KillScore                    = 0x12A8;     // FortPlayerStateAthena -> KillScore
    uintptr_t SeasonLevelUIDisplay         = 0x1274;     // FortPlayerStateAthena -> SeasonLevelUIDisplay
    uintptr_t bIsAnAthenaGameParticipant   = 0x199F;     // FortPlayerStateAthena -> bIsAnAthenaGameParticipant

    uintptr_t RankedProgress               = 0xD0;       // FortPlayerStateComponent_Habanero -> RankedProgress
  
    uintptr_t PlayerArray                  = 0x2C0;      // GameStateBase -> PlayerArray
    uintptr_t ServerWorldTimeSecondsDelta  = 0x2E0;      // GameStateBase -> ServerWorldTimeSecondsDelta

    uintptr_t RelativeLocation             = 0x138;      // SceneComponent -> RelativeLocation
    uintptr_t ComponentVelocity            = 0x180;      // SceneComponent -> ComponentVelocity
    uintptr_t ComponentToWorld             = 0x1E0;      // SceneComponent -> ComponentToWorld
  
    uintptr_t WeaponData                   = 0x560;      // FortWeapon -> WeaponData
    uintptr_t ItemName                     = 0x40;       // ItemDefinitionBase -> ItemName
    uintptr_t ItemDefinition               = 0x10;       // FItemEntry -> ItemDefinition
    uintptr_t ItemData                     = 0x610;      // FItemEntry -> ItemData (uncertain)
    uintptr_t Rarity                       = 0xA2;       // FortItemDefinition -> Rarity
    uintptr_t PrimaryPickupItemEntry       = 0x370;      // FortPickup -> PrimaryPickupItemEntry

    uintptr_t bAlreadySearched             = 0xDFA;      // BuildingContainer -> bAlreadySearched
    uintptr_t NamePrivate                  = 0x18;       // Probably stable, rarely updates
    uintptr_t LastRenderTime               = 0x32C;      // SkeletalMeshComponent -> LastRenderTime

    uintptr_t ProjectileSpeed              = 0x20C4;     // Projectile -> ProjectileSpeed
    uintptr_t ProjectileGravity            = 0x20C8;     // Projectile -> ProjectileGravity

    uintptr_t Wireframe                    = 0x1D8;      // Material -> Wireframe
    uintptr_t bDisableDepthTest            = 0x1C8;      // Material -> bDisableDepthTest
    uintptr_t Parent                       = 0x128;      // MaterialInstance -> Parent
    uintptr_t PawnMaterials_ALL            = 0x4F40;     // PlayerPawn_Athena_Generic_Parent_C -> PawnMaterials_ALL

    uintptr_t Actors                       = 0x1F0;      // Level -> Actors
    uintptr_t CustomTimeDilation           = 0x68;       // Actor -> CustomTimeDilation (unsure)
}
```

# splitgate
Splitgate stuff, dumped by CODEX.

```yaml
class AACTOR : UOBJECT
------------------------------------------------------------------------------------------------
PrimaryActorTick	FActorTickFunction	0x28	
bNetTemporary : 1	char	0x58	
bNetStartup : 1	char	0x58	
bOnlyRelevantToOwner : 1	char	0x58	
bAlwaysRelevant : 1	char	0x58	
bReplicateMovement : 1	char	0x58	
bHidden : 1	char	0x58	
bTearOff : 1	char	0x58	
bForceNetAddressable : 1	char	0x58	
bExchangedRoles : 1	char	0x59	
bNetLoadOnClient : 1	char	0x59	
bNetUseOwnerRelevancy : 1	char	0x59	
bRelevantForNetworkReplays : 1	char	0x59	
bRelevantForLevelBounds : 1	char	0x59	
bReplayRewindable : 1	char	0x59	
bAllowTickBeforeBeginPlay : 1	char	0x59	
bAutoDestroyWhenFinished : 1	char	0x59	
bCanBeDamaged : 1	char	0x5a	
bBlockInput : 1	char	0x5a	
bCollideWhenPlacing : 1	char	0x5a	
bFindCameraComponentWhenViewTarget : 1	char	0x5a	
bGenerateOverlapEventsDuringLevelStreaming : 1	char	0x5a	
bIgnoresOriginShifting : 1	char	0x5a	
bEnableAutoLODGeneration : 1	char	0x5a	
bIsEditorOnlyActor : 1	char	0x5a	
bActorSeamlessTraveled : 1	char	0x5b	
bReplicates : 1	char	0x5b	
bCanBeInCluster : 1	char	0x5b	
bAllowReceiveTickEventOnDedicatedServer : 1	char	0x5b	
bActorEnableCollision : 1	char	0x5c	
bActorIsBeingDestroyed : 1	char	0x5c	
UpdateOverlapsMethodDuringLevelStreaming	EActorUpdateOverlapsMethod	0x5d	
DefaultUpdateOverlapsMethodDuringLevelStreaming	EActorUpdateOverlapsMethod	0x5e	
RemoteRole	ENetRole	0x5f	
ReplicatedMovement	FRepMovement	0x60	
InitialLifeSpan	float	0x94	
CustomTimeDilation	float	0x98	
AttachmentReplication	FRepAttachment	0xa0	
Owner	AActor*	0xe0	
NetDriverName	FName	0xe8	
Role	ENetRole	0xf0	
NetDormancy	ENetDormancy	0xf1	
SpawnCollisionHandlingMethod	ESpawnActorCollisionHandlingMethod	0xf2	
AutoReceiveInput	EAutoReceiveInput	0xf3	
InputPriority	int32_t	0xf4	
InputComponent	UInputComponent*	0xf8	
NetCullDistanceSquared	float	0x100	
NetTag	int32_t	0x104	
NetUpdateFrequency	float	0x108	
MinNetUpdateFrequency	float	0x10c	
NetPriority	float	0x110	
Instigator	APawn*	0x118	
Children	TArray<AActor*>	0x120	
RootComponent	USceneComponent*	0x130	
ControllingMatineeActors	TArray<AMatineeActor*>	0x138	
Layers	TArray<FName>	0x150	
ParentComponent	TWeakObjectPtr<UChildActorComponent>	0x160	
Tags	TArray<FName>	0x170	
OnTakeAnyDamage	FMulticastSparseDelegate	0x180	
OnTakePointDamage	FMulticastSparseDelegate	0x181	
OnTakeRadialDamage	FMulticastSparseDelegate	0x182	
OnActorBeginOverlap	FMulticastSparseDelegate	0x183	
OnActorEndOverlap	FMulticastSparseDelegate	0x184	
OnBeginCursorOver	FMulticastSparseDelegate	0x185	
OnEndCursorOver	FMulticastSparseDelegate	0x186	
OnClicked	FMulticastSparseDelegate	0x187	
OnReleased	FMulticastSparseDelegate	0x188	
OnInputTouchBegin	FMulticastSparseDelegate	0x189	
OnInputTouchEnd	FMulticastSparseDelegate	0x18a	
OnInputTouchEnter	FMulticastSparseDelegate	0x18b	
OnInputTouchLeave	FMulticastSparseDelegate	0x18c	
OnActorHit	FMulticastSparseDelegate	0x18d	
OnDestroyed	FMulticastSparseDelegate	0x18e	
OnEndPlay	FMulticastSparseDelegate	0x18f	
InstanceComponents	TArray<UActorComponent*>	0x1f0	
BlueprintCreatedComponents	TArray<UActorComponent*>	0x200
------------------------------------------------------------------------------------------------
Basic Offsets : Offsets
GNames	0x4efa980	
GObjects	0x4f36eb0	
GWorld	0x507bd50
------------------------------------------------------------------------------------------------
class AAIController : AController
ActionsComp	UPawnActionsComponent*	0x2f0	
Blackboard	UBlackboardComponent*	0x2f8	
BrainComponent	UBrainComponent*	0x2e0	
CachedGameplayTasksComponent	UGameplayTasksComponent*	0x300	
DefaultNavigationFilterClass	UNavigationQueryFilter*	0x308	
PathFollowingComponent	UPathFollowingComponent*	0x2d8	
PerceptionComponent	UAIPerceptionComponent*	0x2e8	
ReceiveMoveCompleted	FMulticastInlineDelegate	0x310	
bAllowStrafe : 1	char	0x2d0	
bLOSflag : 1	char	0x2d0	
bSetControlRotationFromPawnOrientation : 1	char	0x2d0	
bSkipExtraLOSChecks : 1	char	0x2d0	
bStartAILogicOnPossess : 1	char	0x2d0	
bStopAILogicOnUnposses : 1	char	0x2d0	
bWantsPlayerState : 1	char	0x2d0
------------------------------------------------------------------------------------------------
class AAkAcousticPortal : AVolume
ObstructionRefreshInterval	float	0x25c	
ObstructionCollisionChannel	ECollisionChannel	0x260	
InitialState	AkAcousticPortalState	0x258
------------------------------------------------------------------------------------------------
class ABaseGun : ACullableActor
MuzzleAttachPoint	FName	0x22c	
MuzzleFX	UParticleSystem*	0x238	
Muzzle1pScale	FVector	0x240	
Muzzle3pScale	FVector	0x24c	
MuzzlePSC_1P	UParticleSystemComponent*	0x258	
MuzzlePSC_3P	UParticleSystemComponent*	0x260	
bLoopedMuzzleFX : 1	char	0x268	
MyPawn	APortalWarsCharacter*	0x270	
Mesh1P	USkeletalMeshComponent*	0x278	
Mesh3P	UStaticMeshComponent*	0x280	
SkinType	ECustomizationType	0x288	
ColorIntensity3P	float	0x28c	
ColorIntensity1P	float	0x290	
LoudnessForBots	float	0x2b0
------------------------------------------------------------------------------------------------
class AHUD : AActor
Canvas	UCanvas*	0x270	
CurrentTargetIndex	int32_t	0x22c	
DebugCanvas	UCanvas*	0x278	
DebugDisplay	TArray<FName>	0x250	
DebugTextList	TArray<FDebugTextInfo>	0x280	
PlayerOwner	APlayerController*	0x220	
PostRenderedActors	TArray<AActor*>	0x238	
ShowDebugTargetActor	AActor*	0x298	
ShowDebugTargetDesiredClass	AActor*	0x290	
ToggledDebugCategories	TArray<FName>	0x260	
bEnableDebugTextShadow : 1	char	0x230	
bLostFocusPaused : 1	char	0x228	
bShowDebugInfo : 1	char	0x228	
bShowHUD : 1	char	0x228	
bShowHitBoxDebugInfo : 1	char	0x230	
bShowOverlays : 1	char	0x230
------------------------------------------------------------------------------------------------

```

You can make your own base with that.



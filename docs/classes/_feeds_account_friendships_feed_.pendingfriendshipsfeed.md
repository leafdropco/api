> **[instagram-private-api](../README.md)**

[Globals](../README.md) / ["feeds/account-friendships.feed"](../modules/_feeds_account_friendships_feed_.md) / [PendingFriendshipsFeed](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md) /

# Class: PendingFriendshipsFeed

## Hierarchy

  * [Feed](_core_feed_.feed.md)‹*[PendingFriendshipsFeedResponse](../interfaces/_responses_account_friendships_feed_response_.pendingfriendshipsfeedresponse.md)*, *[PendingFriendshipsFeedResponseUsersItem](_responses_account_friendships_feed_response_.pendingfriendshipsfeedresponseusersitem.md)*›

  * **PendingFriendshipsFeed**

## Index

### Constructors

* [constructor](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#constructor)

### Accessors

* [items$](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#items$)
* [state](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#state)

### Methods

* [deserialize](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#deserialize)
* [isMoreAvailable](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#ismoreavailable)
* [items](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#items)
* [observable](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#observable)
* [request](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#request)
* [serialize](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#serialize)
* [toPlain](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#toplain)

### Object literals

* [attemptOptions](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md#attemptoptions)

## Constructors

###  constructor

\+ **new PendingFriendshipsFeed**(`client`: [IgApiClient](_core_client_.igapiclient.md)): *[PendingFriendshipsFeed](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md)*

*Inherited from [Repository](_core_repository_.repository.md).[constructor](_core_repository_.repository.md#constructor)*

*Defined in [core/repository.ts:6](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/repository.ts#L6)*

**Parameters:**

Name | Type |
------ | ------ |
`client` | [IgApiClient](_core_client_.igapiclient.md) |

**Returns:** *[PendingFriendshipsFeed](_feeds_account_friendships_feed_.pendingfriendshipsfeed.md)*

## Accessors

###  items$

• **get items$**(): *`Observable<Item[]>`*

*Inherited from [Feed](_core_feed_.feed.md).[items$](_core_feed_.feed.md#items$)*

*Defined in [core/feed.ts:18](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L18)*

**Returns:** *`Observable<Item[]>`*

___

###  state

• **set state**(`body`: [PendingFriendshipsFeedResponse](../interfaces/_responses_account_friendships_feed_response_.pendingfriendshipsfeedresponse.md)): *void*

*Defined in [feeds/account-friendships.feed.ts:12](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/feeds/account-friendships.feed.ts#L12)*

**Parameters:**

Name | Type |
------ | ------ |
`body` | [PendingFriendshipsFeedResponse](../interfaces/_responses_account_friendships_feed_response_.pendingfriendshipsfeedresponse.md) |

**Returns:** *void*

## Methods

###  deserialize

▸ **deserialize**(`data`: string): *void*

*Inherited from [Feed](_core_feed_.feed.md).[deserialize](_core_feed_.feed.md#deserialize)*

*Defined in [core/feed.ts:79](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L79)*

**Parameters:**

Name | Type |
------ | ------ |
`data` | string |

**Returns:** *void*

___

###  isMoreAvailable

▸ **isMoreAvailable**(): *boolean*

*Inherited from [Feed](_core_feed_.feed.md).[isMoreAvailable](_core_feed_.feed.md#ismoreavailable)*

*Defined in [core/feed.ts:87](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L87)*

**Returns:** *boolean*

___

###  items

▸ **items**(): *`Promise<PendingFriendshipsFeedResponseUsersItem[]>`*

*Overrides [Feed](_core_feed_.feed.md).[items](_core_feed_.feed.md#abstract-items)*

*Defined in [feeds/account-friendships.feed.ts:29](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/feeds/account-friendships.feed.ts#L29)*

**Returns:** *`Promise<PendingFriendshipsFeedResponseUsersItem[]>`*

___

###  observable

▸ **observable**(`semaphore?`: function, `attemptOptions?`: `Partial<AttemptOptions<any>>`): *`Observable<Item[]>`*

*Inherited from [Feed](_core_feed_.feed.md).[observable](_core_feed_.feed.md#observable)*

*Defined in [core/feed.ts:21](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L21)*

**Parameters:**

▪`Optional`  **semaphore**: *function*

▸ (): *`Promise<any>`*

▪`Optional`  **attemptOptions**: *`Partial<AttemptOptions<any>>`*

**Returns:** *`Observable<Item[]>`*

___

###  request

▸ **request**(): *`Promise<PendingFriendshipsFeedResponse>`*

*Overrides [Feed](_core_feed_.feed.md).[request](_core_feed_.feed.md#abstract-request)*

*Defined in [feeds/account-friendships.feed.ts:17](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/feeds/account-friendships.feed.ts#L17)*

**Returns:** *`Promise<PendingFriendshipsFeedResponse>`*

___

###  serialize

▸ **serialize**(): *string*

*Inherited from [Feed](_core_feed_.feed.md).[serialize](_core_feed_.feed.md#serialize)*

*Defined in [core/feed.ts:75](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L75)*

**Returns:** *string*

___

###  toPlain

▸ **toPlain**(): *`Object`*

*Inherited from [Feed](_core_feed_.feed.md).[toPlain](_core_feed_.feed.md#toplain)*

*Defined in [core/feed.ts:83](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L83)*

**Returns:** *`Object`*

## Object literals

###  attemptOptions

### ▪ **attemptOptions**: *object*

*Inherited from [Feed](_core_feed_.feed.md).[attemptOptions](_core_feed_.feed.md#attemptoptions)*

*Defined in [core/feed.ts:10](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L10)*

###  delay

• **delay**: *number* = 60000

*Defined in [core/feed.ts:11](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L11)*

###  factor

• **factor**: *number* = 1.5

*Defined in [core/feed.ts:12](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L12)*

###  jitter

• **jitter**: *true* = true

*Defined in [core/feed.ts:16](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L16)*

###  maxAttempts

• **maxAttempts**: *number* = 10

*Defined in [core/feed.ts:13](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L13)*

###  maxDelay

• **maxDelay**: *number* = 300000

*Defined in [core/feed.ts:15](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L15)*

###  minDelay

• **minDelay**: *number* = 60000

*Defined in [core/feed.ts:14](https://github.com/dilame/instagram-private-api/blob/e9c516c/src/core/feed.ts#L14)*
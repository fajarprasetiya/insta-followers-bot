> **[instagram-private-api](../README.md)**

[Globals](../README.md) / ["responses/account-followers.feed.response"](../modules/_responses_account_followers_feed_response_.md) / [AccountFollowersFeedResponseUsersItem](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md) /

# Class: AccountFollowersFeedResponseUsersItem

## Hierarchy

  * [ProfileEntity](_entities_profile_entity_.profileentity.md)

  * **AccountFollowersFeedResponseUsersItem**

## Index

### Constructors

* [constructor](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#constructor)

### Properties

* [full_name](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#full_name)
* [has_anonymous_profile_picture](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#has_anonymous_profile_picture)
* [is_private](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#is_private)
* [is_verified](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#is_verified)
* [latest_reel_media](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#optional-latest_reel_media)
* [pk](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#pk)
* [profile_pic_id](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#optional-profile_pic_id)
* [profile_pic_url](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#profile_pic_url)
* [username](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#username)

### Methods

* [checkFollow](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#checkfollow)
* [checkUnfollow](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md#checkunfollow)

## Constructors

###  constructor

\+ **new AccountFollowersFeedResponseUsersItem**(`client`: [IgApiClient](_core_client_.igapiclient.md)): *[AccountFollowersFeedResponseUsersItem](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md)*

*Inherited from [Repository](_core_repository_.repository.md).[constructor](_core_repository_.repository.md#constructor)*

*Defined in [core/repository.ts:6](https://github.com/dilame/instagram-private-api/blob/3e16058/src/core/repository.ts#L6)*

**Parameters:**

Name | Type |
------ | ------ |
`client` | [IgApiClient](_core_client_.igapiclient.md) |

**Returns:** *[AccountFollowersFeedResponseUsersItem](_responses_account_followers_feed_response_.accountfollowersfeedresponseusersitem.md)*

## Properties

###  full_name

??? **full_name**: *string*

*Defined in [responses/account-followers.feed.response.ts:14](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L14)*

___

###  has_anonymous_profile_picture

??? **has_anonymous_profile_picture**: *boolean*

*Defined in [responses/account-followers.feed.response.ts:19](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L19)*

___

###  is_private

??? **is_private**: *boolean*

*Defined in [responses/account-followers.feed.response.ts:15](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L15)*

___

###  is_verified

??? **is_verified**: *boolean*

*Defined in [responses/account-followers.feed.response.ts:18](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L18)*

___

### `Optional` latest_reel_media

??? **latest_reel_media**? : *number*

*Defined in [responses/account-followers.feed.response.ts:20](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L20)*

___

###  pk

??? **pk**: *number*

*Overrides [ProfileEntity](_entities_profile_entity_.profileentity.md).[pk](_entities_profile_entity_.profileentity.md#pk)*

*Defined in [responses/account-followers.feed.response.ts:12](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L12)*

___

### `Optional` profile_pic_id

??? **profile_pic_id**? : *string*

*Defined in [responses/account-followers.feed.response.ts:17](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L17)*

___

###  profile_pic_url

??? **profile_pic_url**: *string*

*Defined in [responses/account-followers.feed.response.ts:16](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L16)*

___

###  username

??? **username**: *string*

*Defined in [responses/account-followers.feed.response.ts:13](https://github.com/dilame/instagram-private-api/blob/3e16058/src/responses/account-followers.feed.response.ts#L13)*

## Methods

###  checkFollow

??? **checkFollow**(): *`Promise<FriendshipRepositoryChangeResponseFriendship_status>`*

*Inherited from [ProfileEntity](_entities_profile_entity_.profileentity.md).[checkFollow](_entities_profile_entity_.profileentity.md#checkfollow)*

*Defined in [entities/profile.entity.ts:5](https://github.com/dilame/instagram-private-api/blob/3e16058/src/entities/profile.entity.ts#L5)*

**Returns:** *`Promise<FriendshipRepositoryChangeResponseFriendship_status>`*

___

###  checkUnfollow

??? **checkUnfollow**(): *`Promise<FriendshipRepositoryChangeResponseFriendship_status>`*

*Inherited from [ProfileEntity](_entities_profile_entity_.profileentity.md).[checkUnfollow](_entities_profile_entity_.profileentity.md#checkunfollow)*

*Defined in [entities/profile.entity.ts:10](https://github.com/dilame/instagram-private-api/blob/3e16058/src/entities/profile.entity.ts#L10)*

**Returns:** *`Promise<FriendshipRepositoryChangeResponseFriendship_status>`*
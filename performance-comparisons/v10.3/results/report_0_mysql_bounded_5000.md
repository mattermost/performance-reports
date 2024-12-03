### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 82ms | 223ms | 141ms | 171.28
| ThreadStore.MarkAllAsReadByTeam | avg | 1ms | 3ms | 2ms | 169.53
| StatusStore.UpdateExpiredDNDStatuses | avg | 2ms | 4ms | 2ms | 100.63
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 7ms | 9ms | 2ms | 26.72
| StatusStore.SaveOrUpdate | avg | 12ms | 14ms | 2ms | 17.15
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 14ms | 16ms | 2ms | 14.09
| PostStore.SearchPostsForUser | avg | 52ms | 54ms | 2ms | 3.82
| TeamStore.SaveMember | avg | 65ms | 67ms | 2ms | 3.06
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 400ms | 2.278s | 1.878s | 469.27
| StatusStore.UpdateExpiredDNDStatuses | p99 | 5ms | 22ms | 17ms | 343.43
| UserStore.Update | p99 | 8ms | 22ms | 14ms | 172.36
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 25ms | 15ms | 150.75
| PostStore.Delete | p99 | 10ms | 23ms | 13ms | 130.65
| UserAccessTokenStore.GetByToken | p99 | 5ms | 10ms | 5ms | 100.98
| WebhookStore.GetOutgoingByTeam | p99 | 10ms | 20ms | 10ms | 95.60
| BotStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetMany | p99 | 5ms | 9ms | 4ms | 80.81
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateStatusOptimistically | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.SetPostReminder | p99 | 5ms | 9ms | 4ms | 80.81
| ClusterDiscoveryStore.SetLastPingAt | p99 | 5ms | 8ms | 3ms | 60.61
| PluginStore.SetWithOptions | p99 | 10ms | 16ms | 6ms | 60.25
| ChannelStore.SearchGroupChannels | p99 | 5ms | 8ms | 3ms | 60.23
| ChannelStore.GetMember | p99 | 5ms | 8ms | 3ms | 60.08
| FileInfoStore.AttachToPost | p99 | 9ms | 13ms | 4ms | 43.60
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 90ms | 128ms | 38ms | 42.15
| TeamStore.GetMember | p99 | 5ms | 7ms | 2ms | 40.36
| JobStore.GetAllByStatus | p99 | 5ms | 7ms | 2ms | 40.12
| DraftStore.GetDraftsForUser | p99 | 5ms | 7ms | 2ms | 40.10
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 5ms | 7ms | 2ms | 40.08
| ChannelStore.CreateDirectChannel | p99 | 25ms | 35ms | 10ms | 39.96
| PostStore.SearchPostsForUser | p99 | 800ms | 1.098s | 298ms | 37.25
| PluginStore.Delete | p99 | 6ms | 8ms | 2ms | 31.12
| UserStore.UpdateFailedPasswordAttempts | p99 | 14ms | 18ms | 4ms | 28.21
| FileInfoStore.Save | p99 | 7ms | 9ms | 2ms | 26.82
| PostAcknowledgementStore.GetForPost | p99 | 8ms | 10ms | 2ms | 25.86
| ChannelStore.GetByName | p99 | 21ms | 24ms | 3ms | 14.11
| SessionStore.Save | p99 | 21ms | 23ms | 2ms | 9.65
| StatusStore.SaveOrUpdate | p99 | 202ms | 221ms | 19ms | 9.40
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 9ms | 0s | -9ms | -105.28
| ChannelStore.CreateSidebarCategory | avg | 8ms | 0s | -8ms | -97.74
| BotStore.Save | avg | 3ms | 0s | -3ms | -91.64
| ChannelStore.GetAllChannelMembersForUser | avg | 7ms | 3ms | -4ms | -56.27
| ChannelStore.GetMemberCount | avg | 81ms | 64ms | -17ms | -20.98
| UserStore.GetAllProfilesInChannel | avg | 248ms | 198ms | -50ms | -20.13
| ChannelStore.GetTeamChannels | avg | 28ms | 24ms | -4ms | -14.35
| ChannelStore.Autocomplete | avg | 997ms | 927ms | -70ms | -7.02
| UserStore.Search | avg | 58ms | 56ms | -2ms | -3.47
| PostStore.AnalyticsPostCount | avg | 582ms | 576ms | -6ms | -1.03
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 25ms | 0s | -25ms | -100.51
| ChannelStore.CreateSidebarCategory | p99 | 10ms | 0s | -10ms | -100.50
| ChannelStore.GetAllChannelMembersForUser | p99 | 34ms | 11ms | -23ms | -67.81
| ChannelBookmarkStore.Save | p99 | 24ms | 10ms | -14ms | -58.09
| FileInfoStore.SetContent | p99 | 23ms | 10ms | -13ms | -55.68
| ReactionStore.GetForPost | p99 | 19ms | 9ms | -10ms | -52.30
| PostPriorityStore.GetForPost | p99 | 15ms | 8ms | -7ms | -47.30
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -43.96
| ThreadStore.GetTotalUnreadMentions | p99 | 15ms | 10ms | -5ms | -34.43
| PostStore.Update | p99 | 38ms | 25ms | -13ms | -33.77
| ChannelStore.GetPublicChannelsForTeam | p99 | 29ms | 22ms | -7ms | -24.29
| ThreadStore.GetThreadFollowers | p99 | 9ms | 7ms | -2ms | -22.72
| SessionStore.GetLRUSessions | p99 | 13ms | 10ms | -3ms | -22.23
| UserStore.GetForLogin | p99 | 14ms | 11ms | -3ms | -21.26
| UserStore.GetAllProfilesInChannel | p99 | 597ms | 495ms | -102ms | -17.10
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 12ms | 10ms | -2ms | -17.09
| TeamStore.GetAllPage | p99 | 13ms | 11ms | -2ms | -15.18
| SessionStore.Get | p99 | 21ms | 18ms | -3ms | -14.58
| ThreadStore.GetTeamsUnreadForUser | p99 | 15ms | 13ms | -2ms | -13.43
| TeamStore.GetTeamsByUserId | p99 | 15ms | 13ms | -2ms | -13.30
| ChannelStore.GetGuestCount | p99 | 16ms | 14ms | -2ms | -12.79
| ChannelStore.SaveMember | p99 | 65ms | 57ms | -8ms | -12.34
| PreferenceStore.GetAll | p99 | 19ms | 17ms | -2ms | -10.70
| UserStore.AutocompleteUsersInChannel | p99 | 384ms | 349ms | -35ms | -9.12
| ChannelStore.CreateInitialSidebarCategories | p99 | 38ms | 35ms | -3ms | -7.96
| ProductNoticesStore.View | p99 | 78ms | 75ms | -3ms | -3.84
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 82ms | 223ms | 141ms | 171.10
| updateReadStateAllThreadsByUser | avg | 1ms | 3ms | 2ms | 156.34
| removeUserCustomStatus | avg | 75ms | 105ms | 30ms | 39.90
| viewChannel | avg | 9ms | 11ms | 2ms | 22.68
| createDirectChannel | avg | 127ms | 155ms | 28ms | 22.07
| createGroupChannel | avg | 198ms | 240ms | 42ms | 21.22
| logout | avg | 17ms | 20ms | 3ms | 17.24
| createChannel | avg | 176ms | 188ms | 12ms | 6.84
| searchPostsInTeam | avg | 58ms | 60ms | 2ms | 3.47
| addChannelMember | avg | 145ms | 150ms | 5ms | 3.44
| createUser | avg | 105ms | 107ms | 2ms | 1.91
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 400ms | 2.278s | 1.878s | 469.27
| unfollowThreadByUser | p99 | 10ms | 23ms | 13ms | 130.65
| logout | p99 | 25ms | 47ms | 22ms | 88.53
| deletePost | p99 | 25ms | 47ms | 22ms | 88.53
| searchGroupChannels | p99 | 5ms | 8ms | 3ms | 60.17
| createGroupChannel | p99 | 486ms | 765ms | 279ms | 57.36
| createDirectChannel | p99 | 248ms | 373ms | 125ms | 50.39
| searchPostsInTeam | p99 | 800ms | 1.098s | 298ms | 37.25
| getUser | p99 | 14ms | 17ms | 3ms | 21.23
| getUsers | p99 | 14ms | 16ms | 2ms | 13.88
| removeUserCustomStatus | p99 | 244ms | 247ms | 3ms | 1.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 11ms | 0s | -11ms | -101.91
| patchPost | avg | 1.092s | 27ms | -1.065s | -97.56
| createPost | avg | 289ms | 160ms | -129ms | -44.56
| getProfileImage | avg | 100ms | 74ms | -26ms | -25.99
| getChannelStats | avg | 9ms | 7ms | -2ms | -22.56
| addTeamMember | avg | 753ms | 662ms | -91ms | -12.08
| searchAllChannels | avg | 997ms | 927ms | -70ms | -7.02
| uploadFileStream | avg | 409ms | 389ms | -20ms | -4.89
| searchUsers | avg | 59ms | 57ms | -2ms | -3.41
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| patchPost | p99 | 10s | 55ms | -9.945s | -99.45
| addChannelMember | p99 | 379ms | 250ms | -129ms | -34.06
| getTeamsForUser | p99 | 15ms | 13ms | -2ms | -13.07
| getProfileImage | p99 | 394ms | 344ms | -50ms | -12.69
| autocompleteUsers | p99 | 347ms | 311ms | -36ms | -10.37
| getPostsForChannel | p99 | 175ms | 157ms | -18ms | -10.29
| createPost | p99 | 960ms | 867ms | -93ms | -9.69
| addTeamMember | p99 | 2.386s | 2.168s | -218ms | -9.14
| saveReaction | p99 | 24ms | 22ms | -2ms | -8.42
| getChannelStats | p99 | 222ms | 212ms | -10ms | -4.49
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| BotStore.Save |  Avg| 3ms| 0s | -3ms | -91.638
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 10ms | -14ms | -58.091
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.032
| ChannelStore.Autocomplete |  Avg| 997ms| 927ms | -70ms | -7.022
| |  P99| 2.463s| 2.458s | -5ms | -0.203
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 82ms| 223ms | 141ms | 171.279
| |  P99| 400ms| 2.278s | 1.878s | 469.272
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 25ms| 35ms | 10ms | 39.956
| ChannelStore.CreateInitialSidebarCategories |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 38ms| 35ms | -3ms | -7.960
| ChannelStore.CreateSidebarCategory |  Avg| 8ms| 0s | -8ms | -97.738
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.431
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 9ms| 0s | -9ms | -105.279
| |  P99| 25ms| 0s | -25ms | -100.511
| ChannelStore.GetAllChannelMembersForUser |  Avg| 7ms| 3ms | -4ms | -56.274
| |  P99| 34ms| 11ms | -23ms | -67.805
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 16ms | 2ms | 14.091
| |  P99| 90ms| 128ms | 38ms | 42.153
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.112
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 4ms | 1ms | 29.006
| |  P99| 10ms| 9ms | -1ms | -10.504
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.793
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.081
| ChannelStore.GetMemberCount |  Avg| 81ms| 64ms | -17ms | -20.983
| |  P99| 248ms| 246ms | -2ms | -0.807
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.648
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 29ms| 22ms | -7ms | -24.294
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 9ms| 8ms | -1ms | -11.661
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.173
| ChannelStore.GetTeamChannels |  Avg| 28ms| 24ms | -4ms | -14.351
| |  P99| 50ms| 49ms | -1ms | -2.020
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.142
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 65ms| 57ms | -8ms | -12.343
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.228
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.811
| ChannelStore.UpdateSidebarCategories |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 1ms | 1ms | 209.771
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 3ms | 1ms | 42.755
| |  P99| 5ms| 8ms | 3ms | 60.606
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 7ms| 9ms | 2ms | 26.723
| |  P99| 10ms| 25ms | 15ms | 150.754
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.099
| DraftStore.Upsert |  Avg| 2ms| 3ms | 1ms | 42.296
| |  P99| 6ms| 7ms | 1ms | 18.034
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 4ms | 1ms | 31.027
| |  P99| 9ms| 13ms | 4ms | 43.597
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.858
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 26.820
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 10ms | -13ms | -55.675
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.093
| GroupStore.GetByName |  Avg| 3ms| 2ms | -1ms | -39.483
| |  P99| 10ms| 10ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.485
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.123
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 2ms| 3ms | 1ms | 41.427
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 2ms| 3ms | 1ms | 42.995
| |  P99| 8ms| 8ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 2ms| 3ms | 1ms | 41.750
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 1ms| 2ms | 1ms | 140.710
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 31.120
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.247
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 43.245
| |  P99| 8ms| 10ms | 2ms | 25.862
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 0s| 1ms | 1ms | 207.809
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -39.589
| |  P99| 15ms| 8ms | -7ms | -47.297
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 582ms| 576ms | -6ms | -1.031
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 130.653
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 9.336
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 4ms| 3ms | -1ms | -26.657
| |  P99| 10ms| 9ms | -1ms | -10.444
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 8ms| 9ms | 1ms | 12.592
| |  P99| 24ms| 25ms | 1ms | 4.095
| PostStore.SearchPostsForUser |  Avg| 52ms| 54ms | 2ms | 3.823
| |  P99| 800ms| 1.098s | 298ms | 37.251
| PostStore.SetPostReminder |  Avg| 3ms| 4ms | 1ms | 30.928
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.Update |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 38ms| 25ms | -13ms | -33.766
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.781
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.704
| PreferenceStore.Save |  Avg| 5ms| 6ms | 1ms | 19.248
| |  P99| 23ms| 24ms | 1ms | 4.376
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 78ms| 75ms | -3ms | -3.842
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 9ms | -10ms | -52.301
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -70.396
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -90.185
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.583
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.232
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.085
| SessionStore.Remove |  Avg| 2ms| 3ms | 1ms | 40.298
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.654
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 3ms | 1ms | 41.669
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 12ms| 14ms | 2ms | 17.154
| |  P99| 202ms| 221ms | 19ms | 9.403
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 4ms | 2ms | 100.634
| |  P99| 5ms| 22ms | 17ms | 343.434
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 102ms| 101ms | -1ms | -0.982
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.179
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 9.808
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.358
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.296
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 74ms| 74ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 65ms| 67ms | 2ms | 3.056
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.428
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.720
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 3ms| 2ms | -1ms | -39.694
| |  P99| 9ms| 8ms | -1ms | -10.694
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -34.432
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 2ms | -1ms | -39.999
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.445
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 1ms | -1ms | -52.379
| |  P99| 9ms| 5ms | -4ms | -43.956
| ThreadStore.MarkAllAsReadByTeam |  Avg| 1ms| 3ms | 2ms | 169.531
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 3ms | 1ms | 43.020
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 3ms | 1ms | 49.525
| |  P99| 5ms| 10ms | 5ms | 100.980
| UserStore.AutocompleteUsersInChannel |  Avg| 128ms| 127ms | -1ms | -0.780
| |  P99| 384ms| 349ms | -35ms | -9.120
| UserStore.Count |  Avg| 66ms| 67ms | 1ms | 1.516
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 1ms | -1ms | -54.544
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.172
| UserStore.GetAllProfilesInChannel |  Avg| 248ms| 198ms | -50ms | -20.132
| |  P99| 597ms| 495ms | -102ms | -17.097
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.259
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 41.391
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 3ms | 1ms | 41.471
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 5ms | 1ms | 22.554
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 5ms | 1ms | 24.017
| |  P99| 20ms| 21ms | 1ms | 5.083
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.639
| UserStore.Save |  Avg| 70ms| 71ms | 1ms | 1.424
| |  P99| 129ms| 129ms | 0s | 0.000
| UserStore.Search |  Avg| 58ms| 56ms | -2ms | -3.469
| |  P99| 241ms| 239ms | -2ms | -0.831
| UserStore.Update |  Avg| 3ms| 4ms | 1ms | 29.734
| |  P99| 8ms| 22ms | 14ms | 172.362
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 18ms | 4ms | 28.211
| UserStore.UpdateLastLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.456
| UserStore.UpdateUpdateAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.109
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 95.596
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 145ms| 150ms | 5ms | 3.441
| | P99| 379ms| 250ms | -129ms | -34.059
| addTeamMember | Avg| 753ms| 662ms | -91ms | -12.079
| | P99| 2.386s| 2.168s | -218ms | -9.137
| autocompleteChannelsForTeamForSearch | Avg| 82ms| 223ms | 141ms | 171.096
| | P99| 400ms| 2.278s | 1.878s | 469.272
| autocompleteUsers | Avg| 111ms| 112ms | 1ms | 0.904
| | P99| 347ms| 311ms | -36ms | -10.371
| createCategoryForTeamForUser | Avg| 11ms| 0s | -11ms | -101.909
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 176ms| 188ms | 12ms | 6.838
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 127ms| 155ms | 28ms | 22.066
| | P99| 248ms| 373ms | 125ms | 50.387
| createGroupChannel | Avg| 198ms| 240ms | 42ms | 21.217
| | P99| 486ms| 765ms | 279ms | 57.361
| createPost | Avg| 289ms| 160ms | -129ms | -44.561
| | P99| 960ms| 867ms | -93ms | -9.685
| createUser | Avg| 105ms| 107ms | 2ms | 1.913
| | P99| 248ms| 249ms | 1ms | 0.403
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 13.639
| deletePost | Avg| 14ms| 15ms | 1ms | 7.300
| | P99| 25ms| 47ms | 22ms | 88.531
| followThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 15ms | -1ms | -6.233
| getCategoriesForTeamForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 9ms| 7ms | -2ms | -22.562
| | P99| 222ms| 212ms | -10ms | -4.495
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.567
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.758
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 92ms| 93ms | 1ms | 1.085
| getFileThumbnail | Avg| 31ms| 32ms | 1ms | 3.212
| | P99| 83ms| 83ms | 0s | 0.000
| getPostThread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 21ms| 20ms | -1ms | -4.810
| | P99| 175ms| 157ms | -18ms | -10.289
| getPostsForChannelAroundLastUnread | Avg| 19ms| 20ms | 1ms | 5.153
| | P99| 69ms| 70ms | 1ms | 1.440
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 18ms | -1ms | -5.164
| getProfileImage | Avg| 100ms| 74ms | -26ms | -25.987
| | P99| 394ms| 344ms | -50ms | -12.690
| getPublicChannelsForTeam | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 29ms| 28ms | -1ms | -3.471
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getTeamStats | Avg| 102ms| 101ms | -1ms | -0.981
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 13ms | -2ms | -13.074
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 17ms | 3ms | 21.230
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 4ms | 1ms | 29.287
| | P99| 14ms| 16ms | 2ms | 13.878
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 55ms| 56ms | 1ms | 1.833
| | P99| 241ms| 242ms | 1ms | 0.414
| logout | Avg| 17ms| 20ms | 3ms | 17.242
| | P99| 25ms| 47ms | 22ms | 88.531
| patchPost | Avg| 1.092s| 27ms | -1.065s | -97.558
| | P99| 10s| 55ms | -9.945s | -99.450
| removeUserCustomStatus | Avg| 75ms| 105ms | 30ms | 39.900
| | P99| 244ms| 247ms | 3ms | 1.231
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.419
| searchAllChannels | Avg| 997ms| 927ms | -70ms | -7.020
| | P99| 2.463s| 2.458s | -5ms | -0.203
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.165
| searchPostsInTeam | Avg| 58ms| 60ms | 2ms | 3.471
| | P99| 800ms| 1.098s | 298ms | 37.251
| searchUsers | Avg| 59ms| 57ms | -2ms | -3.411
| | P99| 241ms| 240ms | -1ms | -0.414
| setPostReminder | Avg| 13ms| 14ms | 1ms | 7.436
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 8ms| 9ms | 1ms | 12.235
| | P99| 10ms| 23ms | 13ms | 130.653
| updateCategoriesForTeamForUser | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 1ms| 3ms | 2ms | 156.337
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 24ms| 25ms | 1ms | 4.147
| | P99| 49ms| 49ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 409ms| 389ms | -20ms | -4.892
| | P99| 993ms| 988ms | -5ms | -0.504
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 9ms| 11ms | 2ms | 22.685
| | P99| 25ms| 25ms | 0s | 0.000

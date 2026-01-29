### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 137ms | 135ms | 8320.00
| UserStore.GetProfilesInChannel | avg | 10ms | 30ms | 20ms | 208.83
| ChannelBookmarkStore.Save | avg | 4ms | 6ms | 2ms | 47.52
| ChannelStore.Autocomplete | avg | 31ms | 38ms | 7ms | 22.78
| ChannelStore.GetTeamChannels | avg | 13ms | 15ms | 2ms | 15.24
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9898.74
| UserStore.GetProfilesInChannel | p99 | 10ms | 242ms | 232ms | 2327.19
| JobStore.UpdateStatus | p99 | 9ms | 36ms | 27ms | 310.35
| JobStore.GetCountByStatusAndType | p99 | 9ms | 36ms | 27ms | 305.08
| ChannelStore.Autocomplete | p99 | 98ms | 323ms | 225ms | 229.23
| PostStore.Delete | p99 | 10ms | 24ms | 14ms | 140.68
| JobStore.GetAllByStatus | p99 | 9ms | 21ms | 12ms | 131.05
| FileInfoStore.GetByIds | p99 | 6ms | 14ms | 8ms | 126.46
| PropertyValueStore.SearchPropertyValues | p99 | 7ms | 15ms | 8ms | 118.61
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 10ms | 5ms | 100.97
| ChannelStore.UpdateSidebarCategories | p99 | 25ms | 47ms | 22ms | 88.53
| UserStore.GetMany | p99 | 5ms | 9ms | 4ms | 80.81
| FileInfoStore.Save | p99 | 10ms | 16ms | 6ms | 62.88
| JobStore.Save | p99 | 5ms | 7ms | 2ms | 40.40
| DraftStore.Delete | p99 | 5ms | 7ms | 2ms | 40.01
| FileInfoStore.SetContent | p99 | 33ms | 46ms | 13ms | 39.39
| JobStore.UpdateStatusOptimistically | p99 | 7ms | 9ms | 2ms | 27.03
| ChannelStore.CreateInitialSidebarCategories | p99 | 49ms | 58ms | 9ms | 18.41
| ChannelStore.GetPublicChannelsForTeam | p99 | 37ms | 39ms | 2ms | 5.34
| PostStore.SearchPostsForUser | p99 | 891ms | 910ms | 19ms | 2.13
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -108.68
| SystemStore.PermanentDeleteByName | avg | 2ms | 0s | -2ms | -105.30
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 4ms | 0s | -4ms | -101.35
| ChannelStore.CreateSidebarCategory | avg | 8ms | 0s | -8ms | -95.50
| SystemStore.SaveOrUpdate | avg | 2ms | 0s | -2ms | -90.05
| TokenStore.Cleanup | avg | 4ms | 1ms | -3ms | -72.87
| EmojiStore.GetMultipleByName | avg | 4ms | 2ms | -2ms | -49.19
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 14ms | 12ms | -2ms | -14.61
| PostStore.SearchPostsForUser | avg | 79ms | 76ms | -3ms | -3.81
| UserStore.GetAllProfilesInChannel | avg | 155ms | 153ms | -2ms | -1.29
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.93
| ChannelStore.CreateSidebarCategory | p99 | 24ms | 0s | -24ms | -98.36
| EmojiStore.GetMultipleByName | p99 | 24ms | 5ms | -19ms | -77.87
| UserAccessTokenStore.GetByToken | p99 | 22ms | 5ms | -17ms | -76.75
| LinkMetadataStore.Save | p99 | 20ms | 5ms | -15ms | -75.38
| UserStore.Update | p99 | 37ms | 10ms | -27ms | -73.46
| UserStore.GetByUsername | p99 | 16ms | 5ms | -11ms | -67.48
| ChannelStore.CreateDirectChannel | p99 | 67ms | 25ms | -42ms | -62.92
| PostStore.GetPostReminders | p99 | 22ms | 9ms | -13ms | -57.91
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 22ms | 9ms | -13ms | -57.91
| TokenStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.50
| JobStore.UpdateOptimistically | p99 | 9ms | 5ms | -4ms | -45.98
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -45.20
| StatusStore.SaveOrUpdate | p99 | 21ms | 12ms | -9ms | -43.37
| PostAcknowledgementStore.GetForPost | p99 | 16ms | 10ms | -6ms | -36.80
| ChannelStore.Save | p99 | 36ms | 23ms | -13ms | -35.86
| StatusStore.SaveOrUpdateMany | p99 | 25ms | 18ms | -7ms | -28.07
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 95ms | 71ms | -24ms | -25.29
| PostPriorityStore.GetForPost | p99 | 13ms | 10ms | -3ms | -22.69
| ClusterDiscoveryStore.SetLastPingAt | p99 | 16ms | 13ms | -3ms | -18.63
| TeamStore.SaveMember | p99 | 61ms | 50ms | -11ms | -17.95
| ChannelStore.GetFileCount | p99 | 11ms | 9ms | -2ms | -17.73
| SessionStore.Save | p99 | 38ms | 32ms | -6ms | -15.68
| PostStore.GetPostIdAfterTime | p99 | 14ms | 12ms | -2ms | -14.71
| UserStore.UpdateFailedPasswordAttempts | p99 | 30ms | 27ms | -3ms | -9.94
| PostStore.Update | p99 | 26ms | 24ms | -2ms | -7.69
| ProductNoticesStore.View | p99 | 117ms | 111ms | -6ms | -5.14
| SessionStore.Get | p99 | 43ms | 41ms | -2ms | -4.66
| UserStore.AutocompleteUsersInChannel | p99 | 176ms | 169ms | -7ms | -3.98
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchAllChannels | avg | 31ms | 38ms | 7ms | 22.61
| handleCheckCWSConnection | avg | 55ms | 63ms | 8ms | 14.56
| createChannel | avg | 148ms | 163ms | 15ms | 10.15
| patchPost | avg | 20ms | 22ms | 2ms | 9.82
| removeUserCustomStatus | avg | 101ms | 110ms | 9ms | 8.95
| updateCategoriesForTeamForUser | avg | 34ms | 36ms | 2ms | 5.91
| createPost | avg | 141ms | 143ms | 2ms | 1.42
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchAllChannels | p99 | 98ms | 323ms | 225ms | 229.17
| listCPAValues | p99 | 8ms | 15ms | 7ms | 89.73
| deletePost | p99 | 25ms | 47ms | 22ms | 88.51
| updateCategoriesForTeamForUser | p99 | 50ms | 89ms | 39ms | 78.39
| root | p99 | 5ms | 7ms | 2ms | 40.40
| unfollowThreadByUser | p99 | 20ms | 24ms | 4ms | 20.10
| getPublicChannelsForTeam | p99 | 37ms | 42ms | 5ms | 13.35
| saveReaction | p99 | 24ms | 27ms | 3ms | 12.27
| logout | p99 | 44ms | 47ms | 3ms | 6.78
| updateReadStateThreadByUser | p99 | 65ms | 67ms | 2ms | 3.09
| searchPostsInTeam | p99 | 895ms | 919ms | 24ms | 2.68
| addTeamMember | p99 | 2.143s | 2.169s | 26ms | 1.21
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 12ms | 0s | -12ms | -102.65
| createChannelBookmark | avg | 11ms | 9ms | -2ms | -18.85
| getProfileImage | avg | 96ms | 87ms | -9ms | -9.42
| addChannelMember | avg | 158ms | 148ms | -10ms | -6.31
| createGroupChannel | avg | 245ms | 230ms | -15ms | -6.11
| createUser | avg | 204ms | 199ms | -5ms | -2.45
| searchPostsInTeam | avg | 86ms | 84ms | -2ms | -2.32
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.81
| createSchedulePost | p99 | 9ms | 5ms | -4ms | -43.55
| getChannel | p99 | 34ms | 20ms | -14ms | -40.88
| createDirectChannel | p99 | 421ms | 250ms | -171ms | -40.59
| addChannelMember | p99 | 364ms | 248ms | -116ms | -31.89
| getTeamScheduledPosts | p99 | 42ms | 37ms | -5ms | -11.92
| getPostsForChannel | p99 | 158ms | 143ms | -15ms | -9.52
| getProfileImage | p99 | 446ms | 413ms | -33ms | -7.41
| getUsers | p99 | 31ms | 29ms | -2ms | -6.46
| getUser | p99 | 38ms | 36ms | -2ms | -5.30
| autocompleteUsers | p99 | 152ms | 145ms | -7ms | -4.60
| getPostsForChannelAroundLastUnread | p99 | 93ms | 91ms | -2ms | -2.16
| createPost | p99 | 714ms | 699ms | -15ms | -2.10
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 4ms| 6ms | 2ms | 47.520
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 31ms| 38ms | 7ms | 22.780
| |  P99| 98ms| 323ms | 225ms | 229.232
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 41ms| 42ms | 1ms | 2.435
| |  P99| 99ms| 99ms | 0s | 0.000
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 67ms| 25ms | -42ms | -62.922
| ChannelStore.CreateInitialSidebarCategories |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 49ms| 58ms | 9ms | 18.413
| ChannelStore.CreateSidebarCategory |  Avg| 8ms| 0s | -8ms | -95.502
| |  P99| 24ms| 0s | -24ms | -98.361
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.478
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 12ms | -2ms | -14.606
| |  P99| 95ms| 71ms | -24ms | -25.292
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.171
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.732
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 28ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.570
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 0s | -4ms | -101.352
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 37ms| 39ms | 2ms | 5.342
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 6ms| 5ms | -1ms | -18.161
| |  P99| 39ms| 38ms | -1ms | -2.586
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 13ms| 15ms | 2ms | 15.238
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ChannelStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 36ms| 23ms | -13ms | -35.859
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 98ms| 99ms | 1ms | 1.021
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.404
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 18ms| 19ms | 1ms | 5.425
| |  P99| 25ms| 47ms | 22ms | 88.531
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 0s | -1ms | -196.230
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.632
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.005
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.971
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -39.428
| |  P99| 12ms| 11ms | -1ms | -8.439
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 4ms| 2ms | -2ms | -49.193
| |  P99| 24ms| 5ms | -19ms | -77.869
| FileInfoStore.AttachToPost |  Avg| 4ms| 3ms | -1ms | -28.314
| |  P99| 10ms| 9ms | -1ms | -10.261
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 14ms | 8ms | 126.458
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.031
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 62.881
| FileInfoStore.SetContent |  Avg| 5ms| 6ms | 1ms | 21.180
| |  P99| 33ms| 46ms | 13ms | 39.394
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.155
| GroupStore.GetByName |  Avg| 3ms| 2ms | -1ms | -39.981
| |  P99| 23ms| 23ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 21ms | 12ms | 131.048
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 36ms | 27ms | 305.085
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.978
| JobStore.UpdateStatus |  Avg| 2ms| 3ms | 1ms | 46.837
| |  P99| 9ms| 36ms | 27ms | 310.350
| JobStore.UpdateStatusOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.028
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.195
| LinkMetadataStore.Save |  Avg| 3ms| 2ms | -1ms | -38.802
| |  P99| 20ms| 5ms | -15ms | -75.381
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -36.801
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.045
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 0s | -1ms | -159.913
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.283
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.685
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 2ms| 137ms | 135ms | 8320.001
| |  P99| 5ms| 495ms | 490ms | 9898.739
| PostStore.AnalyticsPostCountByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 7ms| 8ms | 1ms | 13.463
| |  P99| 10ms| 24ms | 14ms | 140.676
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.314
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.259
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.709
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 3ms| 2ms | -1ms | -34.911
| |  P99| 22ms| 9ms | -13ms | -57.906
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 32ms| 32ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 79ms| 76ms | -3ms | -3.805
| |  P99| 891ms| 910ms | 19ms | 2.133
| PostStore.SetPostReminder |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.Update |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 26ms| 24ms | -2ms | -7.691
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 117ms| 111ms | -6ms | -5.144
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 15ms | 8ms | 118.612
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.115
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -70.917
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 3ms| 2ms | -1ms | -34.155
| |  P99| 22ms| 9ms | -13ms | -57.906
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.660
| SessionStore.GetLRUSessions |  Avg| 2ms| 3ms | 1ms | 40.163
| |  P99| 23ms| 23ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.495
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.199
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 32ms | -6ms | -15.679
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 3ms| 2ms | -1ms | -39.842
| |  P99| 21ms| 12ms | -9ms | -43.373
| StatusStore.SaveOrUpdateMany |  Avg| 5ms| 4ms | -1ms | -18.933
| |  P99| 25ms| 18ms | -7ms | -28.071
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.716
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.460
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 0s | -2ms | -105.301
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 2ms| 0s | -2ms | -90.049
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 2ms | -1ms | -39.474
| |  P99| 24ms| 23ms | -1ms | -4.177
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.091
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.166
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.208
| TeamStore.GetTotalMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 61ms| 50ms | -11ms | -17.952
| TemporaryPostStore.GetExpiredPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.221
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.264
| ThreadStore.GetTotalThreads |  Avg| 2ms| 3ms | 1ms | 40.035
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.200
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 1ms | -1ms | -59.024
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 4ms| 1ms | -3ms | -72.865
| |  P99| 10ms| 5ms | -5ms | -50.505
| UserAccessTokenStore.GetByToken |  Avg| 3ms| 2ms | -1ms | -36.258
| |  P99| 22ms| 5ms | -17ms | -76.748
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 176ms| 169ms | -7ms | -3.980
| UserStore.Count |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.091
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 155ms| 153ms | -2ms | -1.288
| |  P99| 479ms| 479ms | 0s | 0.000
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 5ms | -11ms | -67.479
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -108.677
| |  P99| 5ms| 0s | -5ms | -100.931
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.725
| UserStore.GetProfilesInChannel |  Avg| 10ms| 30ms | 20ms | 208.832
| |  P99| 10ms| 242ms | 232ms | 2327.191
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.300
| UserStore.Save |  Avg| 134ms| 135ms | 1ms | 0.748
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 10ms | -27ms | -73.463
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 27ms | -3ms | -9.941
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.377
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.479
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.167
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 158ms| 148ms | -10ms | -6.309
| | P99| 364ms| 248ms | -116ms | -31.889
| addTeamMember | Avg| 588ms| 586ms | -2ms | -0.340
| | P99| 2.143s| 2.169s | 26ms | 1.213
| autocompleteChannelsForTeamForSearch | Avg| 41ms| 42ms | 1ms | 2.432
| | P99| 99ms| 99ms | 0s | 0.000
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 152ms| 145ms | -7ms | -4.599
| createCategoryForTeamForUser | Avg| 12ms| 0s | -12ms | -102.653
| | P99| 25ms| 0s | -25ms | -100.806
| createChannel | Avg| 148ms| 163ms | 15ms | 10.146
| | P99| 248ms| 249ms | 1ms | 0.402
| createChannelBookmark | Avg| 11ms| 9ms | -2ms | -18.854
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 158ms| 158ms | 0s | 0.000
| | P99| 421ms| 250ms | -171ms | -40.593
| createGroupChannel | Avg| 245ms| 230ms | -15ms | -6.113
| | P99| 495ms| 495ms | 0s | 0.000
| createPost | Avg| 141ms| 143ms | 2ms | 1.418
| | P99| 714ms| 699ms | -15ms | -2.102
| createSchedulePost | Avg| 3ms| 2ms | -1ms | -36.213
| | P99| 9ms| 5ms | -4ms | -43.553
| createUser | Avg| 204ms| 199ms | -5ms | -2.454
| | P99| 487ms| 486ms | -1ms | -0.205
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 19.006
| deletePost | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 47ms | 22ms | 88.511
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.367
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAnalytics | Avg| 25ms| 26ms | 1ms | 4.077
| | P99| 49ms| 49ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 42ms| 42ms | 0s | 0.000
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 34ms| 20ms | -14ms | -40.876
| getChannelMember | Avg| 6ms| 5ms | -1ms | -18.042
| | P99| 46ms| 45ms | -1ms | -2.197
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.632
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 30ms| 31ms | 1ms | 3.298
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 17ms | 1ms | 6.094
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getClientConfig | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 44ms| 43ms | -1ms | -2.266
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 11ms | -1ms | -8.421
| getFilePreview | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 94ms| 94ms | 0s | 0.000
| getFileThumbnail | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 92ms| 92ms | 0s | 0.000
| getFilteredUsersStats | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 158ms| 143ms | -15ms | -9.524
| getPostsForChannelAroundLastUnread | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 93ms| 91ms | -2ms | -2.157
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 96ms| 87ms | -9ms | -9.424
| | P99| 446ms| 413ms | -33ms | -7.407
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 37ms| 42ms | 5ms | 13.355
| getRolesByNames | Avg| 5ms| 4ms | -1ms | -21.749
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.112
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.045
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 42ms| 37ms | -5ms | -11.918
| getTeamStats | Avg| 34ms| 35ms | 1ms | 2.912
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.138
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 40ms| 39ms | -1ms | -2.512
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 38ms| 36ms | -2ms | -5.301
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 31ms| 29ms | -2ms | -6.456
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 55ms| 63ms | 8ms | 14.562
| | P99| 100ms| 100ms | 0s | 0.000
| listCPAFields | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| listCPAValues | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 15ms | 7ms | 89.734
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| login | Avg| 106ms| 106ms | 0s | 0.000
| | P99| 498ms| 497ms | -1ms | -0.201
| logout | Avg| 18ms| 19ms | 1ms | 5.497
| | P99| 44ms| 47ms | 3ms | 6.780
| patchPost | Avg| 20ms| 22ms | 2ms | 9.817
| | P99| 52ms| 53ms | 1ms | 1.923
| removeUserCustomStatus | Avg| 101ms| 110ms | 9ms | 8.953
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 0s| 1ms | 1ms | 774.592
| | P99| 5ms| 7ms | 2ms | 40.404
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 27ms | 3ms | 12.270
| searchAllChannels | Avg| 31ms| 38ms | 7ms | 22.610
| | P99| 98ms| 323ms | 225ms | 229.167
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.040
| searchPostsInTeam | Avg| 86ms| 84ms | -2ms | -2.315
| | P99| 895ms| 919ms | 24ms | 2.681
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 17ms | 1ms | 6.332
| | P99| 48ms| 48ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 20ms| 24ms | 4ms | 20.099
| updateCategoriesForTeamForUser | Avg| 34ms| 36ms | 2ms | 5.911
| | P99| 50ms| 89ms | 39ms | 78.392
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 65ms| 67ms | 2ms | 3.092
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 403ms| 401ms | -2ms | -0.496
| | P99| 988ms| 988ms | 0s | 0.000
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 12ms | 1ms | 8.768
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 29ms| 29ms | 0s | 0.000

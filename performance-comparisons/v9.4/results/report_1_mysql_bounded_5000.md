### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 2ms | 31ms | 29ms | 1181.40
| CommandWebhookStore.Cleanup | avg | 2ms | 7ms | 5ms | 263.78
| UserStore.GetAllProfiles | avg | 7ms | 16ms | 9ms | 138.26
| PostStore.AnalyticsPostCount | avg | 1.215s | 2.306s | 1.091s | 89.82
| UserStore.AnalyticsActiveCount | avg | 137ms | 141ms | 4ms | 2.92
| UserStore.GetAllProfilesInChannel | avg | 265ms | 272ms | 7ms | 2.64
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 9ms | 243ms | 234ms | 2571.56
| CommandWebhookStore.Cleanup | p99 | 5ms | 25ms | 20ms | 403.85
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 23ms | 18ms | 363.59
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 50ms | 221ms | 171ms | 343.72
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.UpdateOptimistically | p99 | 10ms | 37ms | 27ms | 277.14
| ChannelStore.GetAllChannelMembersForUser | p99 | 5ms | 17ms | 12ms | 241.30
| ChannelStore.GetMember | p99 | 5ms | 14ms | 9ms | 181.28
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 24ms | 14ms | 140.70
| DraftStore.Upsert | p99 | 5ms | 10ms | 5ms | 100.87
| ChannelStore.CreateDirectChannel | p99 | 25ms | 50ms | 25ms | 100.60
| PostPersistentNotificationStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.GetCountByStatusAndType | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.Autocomplete | p99 | 184ms | 277ms | 93ms | 50.44
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 16ms | 4ms | 34.33
| FileInfoStore.AttachToPost | p99 | 15ms | 19ms | 4ms | 25.98
| UserStore.GetAllProfiles | p99 | 196ms | 238ms | 42ms | 21.45
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Delete | avg | 5ms | 0s | -5ms | -104.90
| FileInfoStore.Search | avg | 24ms | 0s | -24ms | -100.30
| ChannelStore.GetMembers | avg | 82ms | 0s | -82ms | -99.88
| UserStore.GetUnreadCount | avg | 12ms | 2ms | -10ms | -85.34
| ChannelStore.AutocompleteInTeamForSearch | avg | 273ms | 80ms | -193ms | -70.73
| LinkMetadataStore.Save | avg | 4ms | 2ms | -2ms | -47.65
| PostStore.SearchPostsForUser | avg | 160ms | 101ms | -59ms | -36.98
| ChannelStore.UpdateSidebarCategories | avg | 72ms | 56ms | -16ms | -22.21
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 41ms | 32ms | -9ms | -22.07
| ChannelStore.AnalyticsTypeCount | avg | 57ms | 48ms | -9ms | -15.75
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 20ms | 18ms | -2ms | -10.23
| UserStore.Count | avg | 48ms | 45ms | -3ms | -6.23
| ChannelStore.CreateSidebarCategory | avg | 51ms | 48ms | -3ms | -5.93
| ProductNoticesStore.View | avg | 40ms | 38ms | -2ms | -4.99
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | p99 | 50ms | 0s | -50ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.GetMultipleByName | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Delete | p99 | 5ms | 0s | -5ms | -100.86
| ChannelStore.GetMembers | p99 | 249ms | 0s | -249ms | -100.12
| UserStore.GetUnreadCount | p99 | 513ms | 10ms | -503ms | -98.07
| PostStore.SearchPostsForUser | p99 | 4.463s | 495ms | -3.968s | -88.92
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.371s | 306ms | -2.065s | -87.11
| GroupStore.GetByName | p99 | 14ms | 6ms | -8ms | -58.18
| StatusStore.GetByIds | p99 | 11ms | 5ms | -6ms | -54.31
| WebhookStore.GetOutgoingByTeam | p99 | 19ms | 9ms | -10ms | -52.51
| LinkMetadataStore.Save | p99 | 10ms | 5ms | -5ms | -52.08
| SystemStore.PermanentDeleteByName | p99 | 10ms | 5ms | -5ms | -50.25
| ChannelStore.CreateSidebarCategory | p99 | 100ms | 50ms | -50ms | -50.25
| ChannelStore.GetSidebarCategory | p99 | 20ms | 10ms | -10ms | -49.50
| PostStore.SetPostReminder | p99 | 48ms | 25ms | -23ms | -48.17
| UserTermsOfServiceStore.GetByUser | p99 | 9ms | 5ms | -4ms | -46.10
| TeamStore.GetTeamsForUser | p99 | 9ms | 5ms | -4ms | -43.07
| ChannelStore.GetGuestCount | p99 | 16ms | 10ms | -6ms | -38.13
| UserAccessTokenStore.GetByToken | p99 | 8ms | 5ms | -3ms | -37.62
| PostAcknowledgementStore.GetForPost | p99 | 8ms | 5ms | -3ms | -36.37
| StatusStore.Get | p99 | 8ms | 5ms | -3ms | -35.72
| StatusStore.SaveOrUpdate | p99 | 15ms | 10ms | -5ms | -33.88
| UserStore.Save | p99 | 146ms | 100ms | -46ms | -31.55
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 7ms | 5ms | -2ms | -30.66
| UserStore.GetForLogin | p99 | 10ms | 7ms | -3ms | -30.18
| ChannelStore.SearchGroupChannels | p99 | 7ms | 5ms | -2ms | -30.14
| JobStore.GetNewestJobByStatusesAndType | p99 | 7ms | 5ms | -2ms | -29.30
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 7ms | 5ms | -2ms | -27.70
| ChannelStore.GetChannels | p99 | 7ms | 5ms | -2ms | -27.60
| ChannelStore.GetFileCount | p99 | 8ms | 6ms | -2ms | -26.52
| PostStore.GetPostIdAfterTime | p99 | 12ms | 9ms | -3ms | -25.89
| ProductNoticesStore.View | p99 | 132ms | 98ms | -34ms | -25.67
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 8ms | 6ms | -2ms | -25.38
| ChannelStore.GetByName | p99 | 24ms | 18ms | -6ms | -25.31
| UserStore.GetProfileByIds | p99 | 8ms | 6ms | -2ms | -25.22
| TeamStore.GetAllPage | p99 | 8ms | 6ms | -2ms | -23.61
| PluginStore.Delete | p99 | 13ms | 10ms | -3ms | -22.65
| TeamStore.GetTeamsByUserId | p99 | 9ms | 7ms | -2ms | -22.62
| SystemStore.GetByName | p99 | 13ms | 10ms | -3ms | -22.25
| ThreadStore.GetTeamsUnreadForUser | p99 | 14ms | 11ms | -3ms | -22.15
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 88ms | 71ms | -17ms | -19.39
| ChannelStore.SaveMember | p99 | 77ms | 65ms | -12ms | -15.55
| PreferenceStore.GetAll | p99 | 17ms | 15ms | -2ms | -12.00
| PreferenceStore.Save | p99 | 44ms | 39ms | -5ms | -11.48
| ChannelStore.UpdateLastViewedAt | p99 | 18ms | 16ms | -2ms | -10.88
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 19ms | 17ms | -2ms | -10.37
| UserStore.UpdateFailedPasswordAttempts | p99 | 22ms | 20ms | -2ms | -9.01
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 23ms | 21ms | -2ms | -8.72
| SessionStore.Get | p99 | 24ms | 22ms | -2ms | -8.19
| ChannelStore.CreateInitialSidebarCategories | p99 | 53ms | 49ms | -4ms | -7.60
| PostStore.Update | p99 | 47ms | 45ms | -2ms | -4.27
| UserStore.AutocompleteUsersInChannel | p99 | 316ms | 303ms | -13ms | -4.11
| ChannelStore.UpdateSidebarCategories | p99 | 476ms | 462ms | -14ms | -2.94
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsers | avg | 8ms | 18ms | 10ms | 123.92
| patchPost | avg | 28ms | 43ms | 15ms | 53.27
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 50ms | 768ms | 718ms | 1444.43
| searchAllChannels | p99 | 184ms | 277ms | 93ms | 50.44
| getUsers | p99 | 205ms | 238ms | 33ms | 16.07
| logout | p99 | 93ms | 97ms | 4ms | 4.28
| getChannelsForUser | p99 | 750ms | 765ms | 15ms | 2.00
| getChannelStats | p99 | 173ms | 175ms | 2ms | 1.16
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 2ms | 0s | -2ms | -101.91
| getFilteredUsersStats | avg | 64ms | 0s | -64ms | -100.35
| updateUserCustomStatus | avg | 146ms | 0s | -146ms | -100.15
| getLicenseSelfServeStatus | avg | 155ms | 0s | -155ms | -100.07
| getChannelMembers | avg | 3ms | 0s | -3ms | -99.98
| searchFiles | avg | 25ms | 0s | -25ms | -98.78
| autocompleteChannelsForTeamForSearch | avg | 273ms | 80ms | -193ms | -70.72
| searchPostsInTeam | avg | 169ms | 104ms | -65ms | -38.54
| getAnalytics | avg | 69ms | 53ms | -16ms | -23.22
| updateCategoriesForTeamForUser | avg | 85ms | 67ms | -18ms | -21.16
| addChannelMember | avg | 200ms | 174ms | -26ms | -12.99
| setPostReminder | avg | 16ms | 14ms | -2ms | -12.40
| createDirectChannel | avg | 211ms | 186ms | -25ms | -11.84
| getProfileImage | avg | 101ms | 91ms | -10ms | -9.93
| createGroupChannel | avg | 277ms | 258ms | -19ms | -6.85
| uploadFileStream | avg | 419ms | 397ms | -22ms | -5.26
| getFilePreview | avg | 40ms | 38ms | -2ms | -4.97
| searchAllChannels | avg | 45ms | 43ms | -2ms | -4.47
| createCategoryForTeamForUser | avg | 68ms | 66ms | -2ms | -2.94
| createPost | avg | 302ms | 295ms | -7ms | -2.32
| createUser | avg | 97ms | 95ms | -2ms | -2.06
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | p99 | 50ms | 0s | -50ms | -101.01
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| getEmojisByNames | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 246ms | 0s | -246ms | -100.20
| getLicenseSelfServeStatus | p99 | 249ms | 0s | -249ms | -100.20
| updateUserCustomStatus | p99 | 248ms | 5ms | -243ms | -97.81
| searchPostsInTeam | p99 | 4.463s | 496ms | -3.967s | -88.90
| autocompleteChannelsForTeamForSearch | p99 | 2.371s | 306ms | -2.065s | -87.11
| setPostReminder | p99 | 48ms | 25ms | -23ms | -48.17
| getTeamMember | p99 | 9ms | 5ms | -4ms | -43.72
| getPublicChannelsForTeam | p99 | 38ms | 25ms | -13ms | -34.26
| getTeamMembersForUser | p99 | 18ms | 12ms | -6ms | -34.17
| searchGroupChannels | p99 | 7ms | 5ms | -2ms | -30.14
| getUser | p99 | 17ms | 12ms | -5ms | -29.53
| getThreadsForUser | p99 | 7ms | 5ms | -2ms | -28.24
| getChannelMembersForTeamForUser | p99 | 8ms | 6ms | -2ms | -25.34
| getAllTeams | p99 | 12ms | 9ms | -3ms | -24.59
| getTeamsForUser | p99 | 9ms | 7ms | -2ms | -22.16
| getPostThread | p99 | 12ms | 10ms | -2ms | -16.73
| getTeamsUnreadForUser | p99 | 18ms | 15ms | -3ms | -16.27
| addChannelMember | p99 | 478ms | 431ms | -47ms | -9.84
| getCategoriesForTeamForUser | p99 | 23ms | 21ms | -2ms | -8.58
| updateReadStateThreadByUser | p99 | 45ms | 42ms | -3ms | -6.71
| saveReaction | p99 | 46ms | 43ms | -3ms | -6.54
| getFilePreview | p99 | 206ms | 194ms | -12ms | -5.83
| getProfileImage | p99 | 474ms | 456ms | -18ms | -3.80
| updateCategoriesForTeamForUser | p99 | 476ms | 462ms | -14ms | -2.94
| getPostsForChannelAroundLastUnread | p99 | 81ms | 79ms | -2ms | -2.46
| getFileThumbnail | p99 | 96ms | 94ms | -2ms | -2.09
| createPost | p99 | 993ms | 982ms | -11ms | -1.11
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.649
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 41ms| 32ms | -9ms | -22.068
| |  P99| 50ms| 221ms | 171ms | 343.719
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.365
| ChannelStore.AnalyticsTypeCount |  Avg| 57ms| 48ms | -9ms | -15.748
| |  P99| 99ms| 99ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 44ms| 43ms | -1ms | -2.248
| |  P99| 184ms| 277ms | 93ms | 50.443
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 273ms| 80ms | -193ms | -70.734
| |  P99| 2.371s| 306ms | -2.065s | -87.109
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 20ms | 1ms | 5.240
| |  P99| 25ms| 50ms | 25ms | 100.604
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 53ms| 49ms | -4ms | -7.604
| ChannelStore.CreateSidebarCategory |  Avg| 51ms| 48ms | -3ms | -5.931
| |  P99| 100ms| 50ms | -50ms | -50.251
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 0s| 1ms | 1ms | 350.372
| |  P99| 5ms| 17ms | 12ms | 241.296
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 18ms | -2ms | -10.228
| |  P99| 88ms| 71ms | -17ms | -19.390
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 18ms | -6ms | -25.308
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 0s | -1ms | -106.693
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.597
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.270
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 1ms | -1ms | -62.471
| |  P99| 8ms| 6ms | -2ms | -26.516
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -38.126
| ChannelStore.GetMember |  Avg| 1ms| 2ms | 1ms | 105.293
| |  P99| 5ms| 14ms | 9ms | 181.281
| ChannelStore.GetMemberCount |  Avg| 63ms| 63ms | 0s | 0.000
| |  P99| 241ms| 243ms | 2ms | 0.829
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 82ms| 0s | -82ms | -99.883
| |  P99| 249ms| 0s | -249ms | -100.116
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.863
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.723
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 10ms | -10ms | -49.504
| ChannelStore.GetTeamChannels |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.322
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 24ms| 23ms | -1ms | -4.160
| |  P99| 77ms| 65ms | -12ms | -15.546
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.139
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 18ms| 16ms | -2ms | -10.885
| ChannelStore.UpdateSidebarCategories |  Avg| 72ms| 56ms | -16ms | -22.210
| |  P99| 476ms| 462ms | -14ms | -2.940
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 12ms| 16ms | 4ms | 34.335
| CommandWebhookStore.Cleanup |  Avg| 2ms| 7ms | 5ms | 263.777
| |  P99| 5ms| 25ms | 20ms | 403.852
| ComplianceStore.MessageExport |  Avg| 2ms| 31ms | 29ms | 1181.402
| |  P99| 9ms| 243ms | 234ms | 2571.557
| DraftStore.Delete |  Avg| 5ms| 0s | -5ms | -104.898
| |  P99| 5ms| 0s | -5ms | -100.863
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 5ms| 6ms | 1ms | 21.955
| |  P99| 5ms| 10ms | 5ms | 100.872
| EmojiStore.GetMultipleByName |  Avg| 1ms| 0s | -1ms | -122.591
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 15ms| 19ms | 4ms | 25.975
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.408
| FileInfoStore.Search |  Avg| 24ms| 0s | -24ms | -100.296
| |  P99| 50ms| 0s | -50ms | -101.010
| FileInfoStore.SetContent |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.698
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 6ms | -8ms | -58.182
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 0s | -1ms | -80.035
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.304
| JobStore.Save |  Avg| 5ms| 4ms | -1ms | -22.143
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 37ms | 27ms | 277.138
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 2ms | -2ms | -47.646
| |  P99| 10ms| 5ms | -5ms | -52.083
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.648
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.336
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.369
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 1.215s| 2.306s | 1.091s | 89.824
| |  P99| 4.925s| 4.95s | 25ms | 0.508
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.569
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.122
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -25.892
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.062
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.333
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.569
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.247
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 160ms| 101ms | -59ms | -36.976
| |  P99| 4.463s| 495ms | -3.968s | -88.917
| PostStore.SetPostReminder |  Avg| 11ms| 10ms | -1ms | -9.183
| |  P99| 48ms| 25ms | -23ms | -48.168
| PostStore.Update |  Avg| 20ms| 19ms | -1ms | -5.030
| |  P99| 47ms| 45ms | -2ms | -4.274
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 4ms | 1ms | 39.568
| |  P99| 5ms| 23ms | 18ms | 363.589
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -12.001
| PreferenceStore.Save |  Avg| 12ms| 11ms | -1ms | -8.595
| |  P99| 44ms| 39ms | -5ms | -11.483
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 40ms| 38ms | -2ms | -4.995
| |  P99| 132ms| 98ms | -34ms | -25.666
| ReactionStore.ExistsOnPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.674
| ReactionStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetUniqueCountForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -88.874
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.195
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.721
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -54.309
| StatusStore.SaveOrUpdate |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -33.880
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 140.704
| StatusStore.UpdateLastActivityAt |  Avg| 5ms| 4ms | -1ms | -21.982
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.250
| SystemStore.PermanentDeleteByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.251
| SystemStore.SaveOrUpdate |  Avg| 5ms| 4ms | -1ms | -20.567
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -23.611
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.377
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.620
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.074
| TeamStore.SaveMember |  Avg| 68ms| 67ms | -1ms | -1.467
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -22.151
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.444
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.850
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -11.973
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.663
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.622
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -29.469
| |  P99| 10ms| 9ms | -1ms | -10.235
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 5ms | 1ms | 25.457
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 52.279
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.617
| UserStore.AnalyticsActiveCount |  Avg| 137ms| 141ms | 4ms | 2.919
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 126ms| 126ms | 0s | 0.000
| |  P99| 316ms| 303ms | -13ms | -4.110
| UserStore.Count |  Avg| 48ms| 45ms | -3ms | -6.235
| |  P99| 225ms| 225ms | 0s | 0.000
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 7ms| 16ms | 9ms | 138.262
| |  P99| 196ms| 238ms | 42ms | 21.448
| UserStore.GetAllProfilesInChannel |  Avg| 265ms| 272ms | 7ms | 2.639
| |  P99| 883ms| 883ms | 0s | 0.000
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 7ms | -3ms | -30.180
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 1ms | -1ms | -64.989
| |  P99| 8ms| 6ms | -2ms | -25.223
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -11.870
| UserStore.GetUnreadCount |  Avg| 12ms| 2ms | -10ms | -85.337
| |  P99| 513ms| 10ms | -503ms | -98.069
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 68ms | -1ms | -1.454
| |  P99| 146ms| 100ms | -46ms | -31.552
| UserStore.Search |  Avg| 48ms| 47ms | -1ms | -2.078
| |  P99| 241ms| 240ms | -1ms | -0.416
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.938
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.008
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.096
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 9ms | -10ms | -52.507
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 200ms| 174ms | -26ms | -12.989
| | P99| 478ms| 431ms | -47ms | -9.843
| addTeamMember | Avg| 824ms| 826ms | 2ms | 0.243
| | P99| 2.418s| 2.398s | -20ms | -0.827
| autocompleteChannelsForTeamForSearch | Avg| 273ms| 80ms | -193ms | -70.720
| | P99| 2.371s| 306ms | -2.065s | -87.109
| autocompleteUsers | Avg| 100ms| 99ms | -1ms | -1.002
| | P99| 250ms| 250ms | 0s | 0.000
| createCategoryForTeamForUser | Avg| 68ms| 66ms | -2ms | -2.937
| | P99| 100ms| 100ms | 0s | 0.000
| createChannel | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 211ms| 186ms | -25ms | -11.837
| | P99| 489ms| 486ms | -3ms | -0.613
| createGroupChannel | Avg| 277ms| 258ms | -19ms | -6.848
| | P99| 496ms| 496ms | 0s | 0.000
| createPost | Avg| 302ms| 295ms | -7ms | -2.319
| | P99| 993ms| 982ms | -11ms | -1.108
| createUser | Avg| 97ms| 95ms | -2ms | -2.061
| | P99| 243ms| 241ms | -2ms | -0.823
| deleteDraft | Avg| 3ms| 4ms | 1ms | 36.102
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 18ms| 17ms | -1ms | -5.423
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 12ms| 9ms | -3ms | -24.594
| getAnalytics | Avg| 69ms| 53ms | -16ms | -23.223
| | P99| 246ms| 245ms | -1ms | -0.407
| getCategoriesForTeamForUser | Avg| 5ms| 4ms | -1ms | -21.352
| | P99| 23ms| 21ms | -2ms | -8.581
| getChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.202
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelMembers | Avg| 3ms| 0s | -3ms | -99.983
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 1ms | -1ms | -66.611
| | P99| 8ms| 6ms | -2ms | -25.344
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 173ms| 175ms | 2ms | 1.156
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.035
| getChannelsForUser | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 750ms| 765ms | 15ms | 2.000
| getClientConfig | Avg| 7ms| 6ms | -1ms | -15.313
| | P99| 25ms| 24ms | -1ms | -4.035
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 0s | -1ms | -97.409
| | P99| 5ms| 0s | -5ms | -101.010
| getEmojisByNames | Avg| 1ms| 0s | -1ms | -114.118
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 40ms| 38ms | -2ms | -4.966
| | P99| 206ms| 194ms | -12ms | -5.829
| getFileThumbnail | Avg| 29ms| 28ms | -1ms | -3.413
| | P99| 96ms| 94ms | -2ms | -2.093
| getFilteredUsersStats | Avg| 64ms| 0s | -64ms | -100.348
| | P99| 246ms| 0s | -246ms | -100.204
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 155ms| 0s | -155ms | -100.074
| | P99| 249ms| 0s | -249ms | -100.201
| getPostThread | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 12ms| 10ms | -2ms | -16.729
| getPostsForChannel | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 97ms| 97ms | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 81ms| 79ms | -2ms | -2.456
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 16ms | -1ms | -5.855
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 101ms| 91ms | -10ms | -9.933
| | P99| 474ms| 456ms | -18ms | -3.800
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 38ms| 25ms | -13ms | -34.263
| getRolesByNames | Avg| 2ms| 0s | -2ms | -101.913
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 5ms | -4ms | -43.715
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 12ms | -6ms | -34.174
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 7ms | -2ms | -22.160
| getTeamsUnreadForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 15ms | -3ms | -16.269
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -28.236
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 12ms | -5ms | -29.526
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 8ms| 18ms | 10ms | 123.923
| | P99| 205ms| 238ms | 33ms | 16.069
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 62ms| 62ms | 0s | 0.000
| | P99| 246ms| 246ms | 0s | 0.000
| logout | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 93ms| 97ms | 4ms | 4.278
| patchPost | Avg| 28ms| 43ms | 15ms | 53.273
| | P99| 50ms| 768ms | 718ms | 1444.425
| removeUserCustomStatus | Avg| 120ms| 119ms | -1ms | -0.835
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 46ms| 43ms | -3ms | -6.544
| searchAllChannels | Avg| 45ms| 43ms | -2ms | -4.474
| | P99| 184ms| 277ms | 93ms | 50.443
| searchFiles | Avg| 25ms| 0s | -25ms | -98.779
| | P99| 50ms| 0s | -50ms | -101.010
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -30.139
| searchPostsInTeam | Avg| 169ms| 104ms | -65ms | -38.538
| | P99| 4.463s| 496ms | -3.967s | -88.895
| searchUsers | Avg| 48ms| 48ms | 0s | 0.000
| | P99| 241ms| 240ms | -1ms | -0.415
| setPostReminder | Avg| 16ms| 14ms | -2ms | -12.395
| | P99| 48ms| 25ms | -23ms | -48.168
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 85ms| 67ms | -18ms | -21.158
| | P99| 476ms| 462ms | -14ms | -2.940
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 4ms| 5ms | 1ms | 24.902
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 45ms| 42ms | -3ms | -6.712
| updateUserCustomStatus | Avg| 146ms| 0s | -146ms | -100.150
| | P99| 248ms| 5ms | -243ms | -97.811
| uploadFileStream | Avg| 419ms| 397ms | -22ms | -5.256
| | P99| 994ms| 988ms | -6ms | -0.603
| upsertDraft | Avg| 6ms| 7ms | 1ms | 17.214
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000

### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.Delete | avg | 12ms | 14ms | 2ms | 16.68
| ChannelStore.AutocompleteInTeamForSearch | avg | 27ms | 29ms | 2ms | 7.42
| PostStore.AnalyticsPostCount | avg | 173ms | 178ms | 5ms | 2.88
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.UpdateExpiredDNDStatuses | p99 | 9ms | 19ms | 10ms | 113.31
| PostStore.GetPostReminders | p99 | 10ms | 21ms | 11ms | 111.42
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 18ms | 9ms | 97.47
| PostStore.Delete | p99 | 25ms | 47ms | 22ms | 88.58
| ScheduledPostStore.CreateScheduledPost | p99 | 5ms | 9ms | 4ms | 80.81
| ThreadStore.Get | p99 | 5ms | 9ms | 4ms | 80.20
| PostStore.Get | p99 | 15ms | 23ms | 8ms | 54.14
| ChannelStore.CreateDirectChannel | p99 | 44ms | 63ms | 19ms | 43.31
| ChannelStore.GetPinnedPostCount | p99 | 5ms | 7ms | 2ms | 40.06
| ChannelStore.Save | p99 | 35ms | 45ms | 10ms | 28.78
| UserStore.UpdateLastLogin | p99 | 10ms | 12ms | 2ms | 20.60
| UserStore.Update | p99 | 11ms | 13ms | 2ms | 18.60
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 36ms | 39ms | 3ms | 8.25
| ChannelStore.GetPublicChannelsForTeam | p99 | 27ms | 29ms | 2ms | 7.36
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -105.32
| ChannelStore.GetByNameIncludeDeleted | avg | 4ms | 0s | -4ms | -103.90
| ChannelStore.GetMemberCountsByGroup | avg | 7ms | 0s | -7ms | -99.83
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -89.86
| StatusStore.SaveOrUpdate | avg | 20ms | 6ms | -14ms | -70.63
| TeamStore.GetTotalMemberCount | avg | 70ms | 27ms | -43ms | -61.42
| TeamStore.GetActiveMemberCount | avg | 70ms | 35ms | -35ms | -50.01
| UserStore.GetProfilesInChannel | avg | 78ms | 54ms | -24ms | -30.88
| ChannelStore.UpdateSidebarCategories | avg | 38ms | 30ms | -8ms | -21.26
| PostStore.SearchPostsForUser | avg | 95ms | 84ms | -11ms | -11.55
| UserStore.GetAllProfilesInChannel | avg | 148ms | 146ms | -2ms | -1.36
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 48ms | 0s | -48ms | -100.00
| TeamStore.GetActiveMemberCount | p99 | 246ms | 50ms | -196ms | -79.84
| TeamStore.GetTotalMemberCount | p99 | 246ms | 50ms | -196ms | -79.84
| BotStore.Get | p99 | 21ms | 5ms | -16ms | -76.92
| PostStore.GetPostReminderMetadata | p99 | 19ms | 5ms | -14ms | -72.54
| StatusStore.SaveOrUpdate | p99 | 418ms | 141ms | -277ms | -66.20
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 5ms | -5ms | -50.76
| JobStore.GetAllByTypePage | p99 | 10ms | 5ms | -5ms | -50.16
| UserAccessTokenStore.GetByToken | p99 | 9ms | 5ms | -4ms | -47.02
| PostPriorityStore.GetForPost | p99 | 9ms | 5ms | -4ms | -45.87
| ChannelStore.UpdateSidebarCategories | p99 | 92ms | 50ms | -42ms | -45.53
| JobStore.GetCountByStatusAndType | p99 | 11ms | 6ms | -5ms | -44.64
| PreferenceStore.DeleteCategoryAndName | p99 | 9ms | 5ms | -4ms | -42.55
| FileInfoStore.AttachToPost | p99 | 17ms | 10ms | -7ms | -40.99
| UserStore.GetMany | p99 | 8ms | 5ms | -3ms | -39.73
| JobStore.GetAllByStatus | p99 | 16ms | 10ms | -6ms | -37.45
| DraftStore.GetDraftsForUser | p99 | 12ms | 8ms | -4ms | -32.06
| PluginStore.Delete | p99 | 7ms | 5ms | -2ms | -30.40
| UserStore.GetByUsername | p99 | 7ms | 5ms | -2ms | -28.71
| PostStore.GetPostsByThread | p99 | 18ms | 13ms | -5ms | -27.13
| FileInfoStore.GetByIds | p99 | 8ms | 6ms | -2ms | -23.55
| PreferenceStore.GetAll | p99 | 13ms | 10ms | -3ms | -23.22
| ChannelStore.GetMemberForPost | p99 | 13ms | 10ms | -3ms | -23.18
| PostStore.GetPostsAfter | p99 | 9ms | 7ms | -2ms | -22.40
| DraftStore.Upsert | p99 | 10ms | 8ms | -2ms | -20.85
| UserStore.Save | p99 | 147ms | 123ms | -24ms | -16.37
| ChannelStore.SaveMember | p99 | 70ms | 60ms | -10ms | -14.22
| UserStore.UpdateFailedPasswordAttempts | p99 | 14ms | 12ms | -2ms | -13.86
| PluginStore.SetWithOptions | p99 | 15ms | 13ms | -2ms | -13.30
| ChannelStore.GetByName | p99 | 28ms | 25ms | -3ms | -10.87
| ChannelStore.GetAllChannelMembersForUser | p99 | 21ms | 19ms | -2ms | -9.40
| ChannelStore.SearchGroupChannels | p99 | 22ms | 20ms | -2ms | -8.95
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 94ms | 86ms | -8ms | -8.55
| WebhookStore.GetOutgoingByTeam | p99 | 32ms | 30ms | -2ms | -6.18
| UserStore.AutocompleteUsersInChannel | p99 | 160ms | 154ms | -6ms | -3.75
| PostStore.SearchPostsForUser | p99 | 972ms | 944ms | -28ms | -2.88
| ProductNoticesStore.View | p99 | 94ms | 92ms | -2ms | -2.13
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | avg | 15ms | 18ms | 3ms | 19.88
| deletePost | avg | 18ms | 21ms | 3ms | 16.88
| logout | avg | 23ms | 26ms | 3ms | 12.85
| autocompleteChannelsForTeamForSearch | avg | 27ms | 29ms | 2ms | 7.40
| createGroupChannel | avg | 263ms | 277ms | 14ms | 5.31
| getProfileImage | avg | 65ms | 67ms | 2ms | 3.06
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | p99 | 25ms | 48ms | 23ms | 92.56
| logout | p99 | 49ms | 93ms | 44ms | 89.57
| deletePost | p99 | 25ms | 47ms | 22ms | 88.53
| createGroupChannel | p99 | 495ms | 718ms | 223ms | 45.02
| getChannel | p99 | 15ms | 19ms | 4ms | 25.85
| getPostThread | p99 | 26ms | 29ms | 3ms | 11.47
| getCategoriesForTeamForUser | p99 | 39ms | 41ms | 2ms | 5.17
| getPostsForChannel | p99 | 182ms | 184ms | 2ms | 1.10
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | avg | 6ms | 0s | -6ms | -105.70
| channelMemberCountsByGroup | avg | 8ms | 0s | -8ms | -95.77
| getRolesByNames | avg | 3ms | 1ms | -2ms | -58.98
| getTeamStats | avg | 70ms | 35ms | -35ms | -49.83
| updateChannelBookmark | avg | 20ms | 11ms | -9ms | -45.83
| createChannel | avg | 280ms | 203ms | -77ms | -27.52
| updateCategoriesForTeamForUser | avg | 56ms | 46ms | -10ms | -18.02
| followThreadByUser | avg | 13ms | 11ms | -2ms | -15.80
| removeUserCustomStatus | avg | 129ms | 113ms | -16ms | -12.39
| searchPostsInTeam | avg | 102ms | 92ms | -10ms | -9.77
| createDirectChannel | avg | 185ms | 176ms | -9ms | -4.86
| createUser | avg | 130ms | 124ms | -6ms | -4.62
| getAnalytics | avg | 48ms | 46ms | -2ms | -4.20
| addChannelMember | avg | 174ms | 167ms | -7ms | -4.02
| uploadFileStream | avg | 379ms | 366ms | -13ms | -3.43
| createPost | avg | 179ms | 175ms | -4ms | -2.24
| addTeamMember | avg | 523ms | 512ms | -11ms | -2.10
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | p99 | 10ms | 0s | -10ms | -100.73
| channelMemberCountsByGroup | p99 | 48ms | 0s | -48ms | -98.97
| getTeamStats | p99 | 246ms | 50ms | -196ms | -79.84
| getRolesByNames | p99 | 10ms | 5ms | -5ms | -50.76
| getJobsByType | p99 | 10ms | 5ms | -5ms | -50.16
| unfollowThreadByUser | p99 | 49ms | 25ms | -24ms | -48.90
| followThreadByUser | p99 | 45ms | 25ms | -20ms | -44.42
| getDrafts | p99 | 12ms | 9ms | -3ms | -24.03
| upsertDraft | p99 | 13ms | 10ms | -3ms | -23.39
| getPreferences | p99 | 13ms | 10ms | -3ms | -22.96
| getPublicChannelsForTeam | p99 | 35ms | 29ms | -6ms | -17.25
| updateReadStateThreadByUser | p99 | 88ms | 76ms | -12ms | -13.64
| viewChannel | p99 | 28ms | 25ms | -3ms | -10.84
| createPost | p99 | 556ms | 499ms | -57ms | -10.25
| getClientConfig | p99 | 21ms | 19ms | -2ms | -9.66
| updatePreferences | p99 | 21ms | 19ms | -2ms | -9.35
| searchGroupChannels | p99 | 22ms | 20ms | -2ms | -8.95
| createUser | p99 | 440ms | 402ms | -38ms | -8.64
| createChannel | p99 | 496ms | 475ms | -21ms | -4.23
| autocompleteUsers | p99 | 127ms | 123ms | -4ms | -3.14
| searchPostsInTeam | p99 | 974ms | 948ms | -26ms | -2.67
| addChannelMember | p99 | 468ms | 456ms | -12ms | -2.57
| createDirectChannel | p99 | 486ms | 479ms | -7ms | -1.44
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.966
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.923
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -105.323
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 5ms| 4ms | -1ms | -21.467
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.020
| ChannelBookmarkStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.090
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.093
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 27ms| 29ms | 2ms | 7.422
| |  P99| 96ms| 97ms | 1ms | 1.041
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 19ms | 1ms | 5.424
| |  P99| 44ms| 63ms | 19ms | 43.306
| ChannelStore.CreateInitialSidebarCategories |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.123
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.397
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 12ms | -1ms | -7.693
| |  P99| 94ms| 86ms | -8ms | -8.553
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.869
| ChannelStore.GetByNameIncludeDeleted |  Avg| 4ms| 0s | -4ms | -103.904
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 3ms | 1ms | 41.020
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 8.730
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.047
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 40ms| 39ms | -1ms | -2.497
| ChannelStore.GetMemberCountsByGroup |  Avg| 7ms| 0s | -7ms | -99.829
| |  P99| 48ms| 0s | -48ms | -100.002
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -23.183
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.065
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 27ms| 29ms | 2ms | 7.358
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 12ms| 13ms | 1ms | 8.191
| |  P99| 36ms| 39ms | 3ms | 8.253
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 7ms | -1ms | -12.051
| |  P99| 25ms| 24ms | -1ms | -4.054
| ChannelStore.GetTeamChannels |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.466
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.763
| ChannelStore.Save |  Avg| 9ms| 10ms | 1ms | 11.319
| |  P99| 35ms| 45ms | 10ms | 28.775
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 70ms| 60ms | -10ms | -14.220
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.952
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.318
| ChannelStore.UpdateSidebarCategories |  Avg| 38ms| 30ms | -8ms | -21.261
| |  P99| 92ms| 50ms | -42ms | -45.528
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 97.471
| CommandWebhookStore.Cleanup |  Avg| 2ms| 1ms | -1ms | -61.934
| |  P99| 5ms| 5ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.274
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 8ms | -4ms | -32.065
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.851
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.802
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -40.987
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.035
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -23.547
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.449
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.926
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.446
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.162
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 6ms | -5ms | -44.643
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.397
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.305
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.872
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 173ms| 178ms | 5ms | 2.884
| |  P99| 496ms| 496ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 2ms | 1ms | 68.258
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 12ms| 14ms | 2ms | 16.676
| |  P99| 25ms| 47ms | 22ms | 88.580
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 23ms | 8ms | 54.135
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.052
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -18.162
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -72.539
| PostStore.GetPostReminders |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 111.418
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.404
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.401
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 4ms | -1ms | -21.895
| |  P99| 18ms| 13ms | -5ms | -27.130
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.309
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.096
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 95ms| 84ms | -11ms | -11.547
| |  P99| 972ms| 944ms | -28ms | -2.880
| PostStore.SetPostReminder |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -39.823
| |  P99| 9ms| 5ms | -4ms | -42.550
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.414
| PreferenceStore.GetAll |  Avg| 3ms| 2ms | -1ms | -39.461
| |  P99| 13ms| 10ms | -3ms | -23.217
| PreferenceStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.068
| ProductNoticesStore.ClearOldNotices |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 94ms| 92ms | -2ms | -2.125
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.312
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -89.862
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -110.138
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.514
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.347
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 1ms | -1ms | -66.077
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.803
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 3ms | 1ms | 40.881
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 5ms | -1ms | -18.149
| |  P99| 19ms| 18ms | -1ms | -5.160
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.132
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.159
| StatusStore.SaveOrUpdate |  Avg| 20ms| 6ms | -14ms | -70.628
| |  P99| 418ms| 141ms | -277ms | -66.203
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 19ms | 10ms | 113.314
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 2ms | -1ms | -38.519
| |  P99| 9ms| 8ms | -1ms | -11.559
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.531
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.598
| TeamStore.GetActiveMemberCount |  Avg| 70ms| 35ms | -35ms | -50.014
| |  P99| 246ms| 50ms | -196ms | -79.836
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 70ms| 27ms | -43ms | -61.423
| |  P99| 246ms| 50ms | -196ms | -79.836
| TeamStore.SaveMember |  Avg| 22ms| 21ms | -1ms | -4.569
| |  P99| 48ms| 47ms | -1ms | -2.075
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.201
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.665
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.655
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.205
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.053
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.300
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.020
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 2ms | -1ms | -31.907
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.387
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.617
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -47.015
| UserStore.AnalyticsActiveCount |  Avg| 15ms| 14ms | -1ms | -6.703
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 36ms| 35ms | -1ms | -2.773
| |  P99| 160ms| 154ms | -6ms | -3.751
| UserStore.Count |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.815
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 148ms| 146ms | -2ms | -1.355
| |  P99| 462ms| 459ms | -3ms | -0.650
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.708
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.734
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 5ms| 4ms | -1ms | -20.674
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.400
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.928
| UserStore.GetProfilesInChannel |  Avg| 78ms| 54ms | -24ms | -30.879
| |  P99| 248ms| 246ms | -2ms | -0.808
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 4ms | -1ms | -21.800
| |  P99| 10ms| 5ms | -5ms | -50.761
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.138
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 70ms| 69ms | -1ms | -1.433
| |  P99| 147ms| 123ms | -24ms | -16.371
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 18.602
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -13.857
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.604
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.948
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.123
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 4ms | -1ms | -21.974
| |  P99| 32ms| 30ms | -2ms | -6.184
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 174ms| 167ms | -7ms | -4.025
| | P99| 468ms| 456ms | -12ms | -2.565
| addTeamMember | Avg| 523ms| 512ms | -11ms | -2.104
| | P99| 992ms| 991ms | -1ms | -0.101
| autocompleteChannelsForTeamForSearch | Avg| 27ms| 29ms | 2ms | 7.404
| | P99| 96ms| 97ms | 1ms | 1.041
| autocompleteEmojis | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 127ms| 123ms | -4ms | -3.140
| channelMemberCountsByGroup | Avg| 8ms| 0s | -8ms | -95.766
| | P99| 48ms| 0s | -48ms | -98.971
| createChannel | Avg| 280ms| 203ms | -77ms | -27.515
| | P99| 496ms| 475ms | -21ms | -4.232
| createChannelBookmark | Avg| 15ms| 18ms | 3ms | 19.881
| | P99| 25ms| 48ms | 23ms | 92.555
| createDirectChannel | Avg| 185ms| 176ms | -9ms | -4.856
| | P99| 486ms| 479ms | -7ms | -1.439
| createEmoji | Avg| 6ms| 0s | -6ms | -105.703
| | P99| 10ms| 0s | -10ms | -100.733
| createGroupChannel | Avg| 263ms| 277ms | 14ms | 5.314
| | P99| 495ms| 718ms | 223ms | 45.018
| createPost | Avg| 179ms| 175ms | -4ms | -2.239
| | P99| 556ms| 499ms | -57ms | -10.248
| createSchedulePost | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.118
| createUser | Avg| 130ms| 124ms | -6ms | -4.615
| | P99| 440ms| 402ms | -38ms | -8.643
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.272
| deletePost | Avg| 18ms| 21ms | 3ms | 16.876
| | P99| 25ms| 47ms | 22ms | 88.531
| followThreadByUser | Avg| 13ms| 11ms | -2ms | -15.800
| | P99| 45ms| 25ms | -20ms | -44.424
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAnalytics | Avg| 48ms| 46ms | -2ms | -4.204
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 39ms| 41ms | 2ms | 5.169
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 15ms| 19ms | 4ms | 25.850
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getChannelMembers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 13ms| 12ms | -1ms | -7.835
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 3ms | 1ms | 40.038
| | P99| 9ms| 9ms | 0s | 0.000
| getClientConfig | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.664
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 9ms | -3ms | -24.028
| getFilePreview | Avg| 38ms| 37ms | -1ms | -2.659
| | P99| 94ms| 93ms | -1ms | -1.061
| getFileThumbnail | Avg| 32ms| 31ms | -1ms | -3.171
| | P99| 88ms| 87ms | -1ms | -1.133
| getFilteredUsersStats | Avg| 11ms| 10ms | -1ms | -9.244
| | P99| 25ms| 25ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -50.162
| getPostThread | Avg| 11ms| 12ms | 1ms | 9.106
| | P99| 26ms| 29ms | 3ms | 11.471
| getPostsForChannel | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 182ms| 184ms | 2ms | 1.101
| getPostsForChannelAroundLastUnread | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 10ms | -3ms | -22.957
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 65ms| 67ms | 2ms | 3.064
| | P99| 249ms| 248ms | -1ms | -0.402
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 35ms| 29ms | -6ms | -17.247
| getRolesByNames | Avg| 3ms| 1ms | -2ms | -58.985
| | P99| 10ms| 5ms | -5ms | -50.761
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 13.898
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 5ms| 4ms | -1ms | -22.203
| | P99| 19ms| 18ms | -1ms | -5.283
| getTeamStats | Avg| 70ms| 35ms | -35ms | -49.827
| | P99| 246ms| 50ms | -196ms | -79.836
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 13ms| 12ms | -1ms | -7.616
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 12ms | -1ms | -7.742
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 13ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -13.269
| login | Avg| 65ms| 64ms | -1ms | -1.536
| | P99| 241ms| 240ms | -1ms | -0.414
| logout | Avg| 23ms| 26ms | 3ms | 12.853
| | P99| 49ms| 93ms | 44ms | 89.567
| patchPost | Avg| 24ms| 25ms | 1ms | 4.226
| | P99| 49ms| 50ms | 1ms | 2.053
| removeUserCustomStatus | Avg| 129ms| 113ms | -16ms | -12.392
| | P99| 248ms| 247ms | -1ms | -0.403
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.061
| searchAllChannels | Avg| 32ms| 33ms | 1ms | 3.095
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 3ms | -1ms | -28.014
| | P99| 22ms| 20ms | -2ms | -8.952
| searchPostsInTeam | Avg| 102ms| 92ms | -10ms | -9.765
| | P99| 974ms| 948ms | -26ms | -2.670
| searchUsers | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 12ms | -1ms | -7.970
| | P99| 49ms| 25ms | -24ms | -48.895
| updateCategoriesForTeamForUser | Avg| 56ms| 46ms | -10ms | -18.017
| | P99| 99ms| 99ms | 0s | 0.000
| updateChannelBookmark | Avg| 20ms| 11ms | -9ms | -45.831
| | P99| 25ms| 25ms | 0s | 0.000
| updatePreferences | Avg| 7ms| 6ms | -1ms | -15.030
| | P99| 21ms| 19ms | -2ms | -9.349
| updateReadStateAllThreadsByUser | Avg| 3ms| 2ms | -1ms | -30.724
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 88ms| 76ms | -12ms | -13.643
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 379ms| 366ms | -13ms | -3.430
| | P99| 984ms| 979ms | -5ms | -0.508
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 10ms | -3ms | -23.390
| viewChannel | Avg| 11ms| 10ms | -1ms | -9.350
| | P99| 28ms| 25ms | -3ms | -10.837

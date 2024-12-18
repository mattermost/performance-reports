### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 4ms | 14ms | 10ms | 254.68
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 6ms | 4ms | 169.47
| ChannelStore.GetByNameIncludeDeleted | avg | 1ms | 3ms | 2ms | 167.04
| ComplianceStore.MessageExport | avg | 2ms | 4ms | 2ms | 112.80
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 4ms | 8ms | 4ms | 92.24
| TeamStore.GetTotalMemberCount | avg | 19ms | 34ms | 15ms | 80.36
| UserStore.GetProfilesInChannel | avg | 23ms | 30ms | 7ms | 30.53
| ChannelStore.AutocompleteInTeamForSearch | avg | 20ms | 25ms | 5ms | 25.10
| ChannelStore.GetTeamChannels | avg | 10ms | 12ms | 2ms | 19.35
| ChannelBookmarkStore.Save | avg | 10ms | 12ms | 2ms | 19.13
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 11ms | 13ms | 2ms | 17.67
| PostStore.Delete | avg | 15ms | 17ms | 2ms | 13.55
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 5ms | 133ms | 128ms | 2585.86
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 89ms | 84ms | 1696.97
| StatusStore.SaveOrUpdate | p99 | 16ms | 214ms | 198ms | 1212.46
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 89ms | 79ms | 802.03
| BotStore.Get | p99 | 5ms | 22ms | 17ms | 343.43
| PostStore.GetPostsAfter | p99 | 5ms | 19ms | 14ms | 282.83
| FileInfoStore.GetByIds | p99 | 5ms | 11ms | 6ms | 120.68
| TeamStore.GetTotalMemberCount | p99 | 25ms | 50ms | 25ms | 100.57
| JobStore.UpdateStatus | p99 | 9ms | 18ms | 9ms | 97.66
| PostStore.Delete | p99 | 25ms | 47ms | 22ms | 88.53
| ThreadStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.80
| ChannelStore.Save | p99 | 24ms | 41ms | 17ms | 69.45
| ChannelStore.GetSidebarCategory | p99 | 25ms | 41ms | 16ms | 64.74
| ChannelStore.AutocompleteInTeamForSearch | p99 | 94ms | 114ms | 20ms | 21.22
| UserStore.Count | p99 | 20ms | 24ms | 4ms | 19.51
| ChannelStore.CreateDirectChannel | p99 | 38ms | 44ms | 6ms | 15.79
| UserStore.Update | p99 | 20ms | 23ms | 3ms | 15.31
| ChannelStore.GetByName | p99 | 28ms | 31ms | 3ms | 10.57
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 87ms | 94ms | 7ms | 8.09
| ChannelStore.UpdateSidebarCategories | p99 | 95ms | 98ms | 3ms | 3.17
| UserStore.GetProfilesInChannel | p99 | 238ms | 243ms | 5ms | 2.10
| UserStore.AutocompleteUsersInChannel | p99 | 170ms | 172ms | 2ms | 1.18
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Delete | avg | 6ms | 0s | -6ms | -107.75
| FileInfoStore.Search | avg | 4ms | 0s | -4ms | -90.32
| PostStore.AnalyticsPostCount | avg | 243ms | 177ms | -66ms | -27.13
| PostStore.SearchPostsForUser | avg | 25ms | 20ms | -5ms | -20.38
| ChannelStore.CreateSidebarCategory | avg | 32ms | 28ms | -4ms | -12.49
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 55ms | 53ms | -2ms | -3.66
| UserStore.GetAllProfilesInChannel | avg | 153ms | 151ms | -2ms | -1.31
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| FileInfoStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -100.94
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -100.50
| JobStore.GetAllByTypePage | p99 | 18ms | 5ms | -13ms | -72.41
| JobStore.Get | p99 | 17ms | 5ms | -12ms | -72.36
| JobStore.GetCountByStatusAndType | p99 | 16ms | 5ms | -11ms | -70.06
| PluginStore.List | p99 | 20ms | 8ms | -12ms | -61.22
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 8ms | -10ms | -56.20
| JobStore.Save | p99 | 18ms | 9ms | -9ms | -50.99
| FileInfoStore.SetContent | p99 | 38ms | 21ms | -17ms | -45.24
| ClusterDiscoveryStore.SetLastPingAt | p99 | 21ms | 12ms | -9ms | -43.80
| LinkMetadataStore.Save | p99 | 9ms | 5ms | -4ms | -43.64
| UserStore.GetByUsername | p99 | 8ms | 5ms | -3ms | -39.48
| PostAcknowledgementStore.GetForPost | p99 | 8ms | 5ms | -3ms | -37.26
| PostPriorityStore.GetForPost | p99 | 8ms | 5ms | -3ms | -37.26
| PostStore.SearchPostsForUser | p99 | 621ms | 406ms | -215ms | -34.60
| GroupStore.GetByName | p99 | 12ms | 8ms | -4ms | -32.59
| PostStore.Get | p99 | 16ms | 11ms | -5ms | -31.89
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 39ms | 27ms | -12ms | -31.08
| ChannelStore.GetFileCount | p99 | 7ms | 5ms | -2ms | -28.33
| TeamStore.GetTeamsForUser | p99 | 15ms | 11ms | -4ms | -26.31
| ChannelStore.GetGuestCount | p99 | 19ms | 14ms | -5ms | -25.66
| TeamStore.GetMember | p99 | 16ms | 12ms | -4ms | -24.98
| ChannelStore.GetMemberLastViewedAt | p99 | 8ms | 6ms | -2ms | -23.78
| ChannelStore.Get | p99 | 9ms | 7ms | -2ms | -22.49
| DraftStore.GetDraftsForUser | p99 | 10ms | 8ms | -2ms | -21.03
| PostStore.GetEtag | p99 | 10ms | 8ms | -2ms | -20.81
| JobStore.GetAllByStatus | p99 | 20ms | 16ms | -4ms | -20.32
| TeamStore.GetAllPage | p99 | 10ms | 8ms | -2ms | -20.32
| ThreadStore.GetThreadsForUser | p99 | 11ms | 9ms | -2ms | -18.70
| UserStore.GetForLogin | p99 | 11ms | 9ms | -2ms | -17.64
| ProductNoticesStore.View | p99 | 121ms | 100ms | -21ms | -17.40
| ThreadStore.GetTeamsUnreadForUser | p99 | 12ms | 10ms | -2ms | -16.77
| ChannelStore.UpdateLastViewedAt | p99 | 12ms | 10ms | -2ms | -16.56
| SystemStore.GetByName | p99 | 18ms | 15ms | -3ms | -16.44
| UserStore.Get | p99 | 13ms | 11ms | -2ms | -15.86
| ChannelStore.GetAllChannelMembersForUser | p99 | 14ms | 12ms | -2ms | -14.07
| PostStore.GetPostIdAfterTime | p99 | 16ms | 14ms | -2ms | -12.46
| ChannelStore.IncrementMentionCount | p99 | 17ms | 15ms | -2ms | -11.76
| SessionStore.Get | p99 | 28ms | 25ms | -3ms | -10.85
| ChannelStore.CreateInitialSidebarCategories | p99 | 75ms | 67ms | -8ms | -10.74
| ChannelStore.SaveMember | p99 | 87ms | 80ms | -7ms | -8.04
| ChannelStore.GetMemberCount | p99 | 46ms | 44ms | -2ms | -4.35
| PreferenceStore.Save | p99 | 48ms | 46ms | -2ms | -4.17
| UserStore.Save | p99 | 210ms | 204ms | -6ms | -2.86
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | avg | 18ms | 23ms | 5ms | 27.10
| followThreadByUser | avg | 11ms | 14ms | 3ms | 27.05
| autocompleteChannelsForTeamForSearch | avg | 20ms | 25ms | 5ms | 25.03
| addChannelMember | avg | 159ms | 178ms | 19ms | 11.98
| createDirectChannel | avg | 172ms | 184ms | 12ms | 6.97
| createChannel | avg | 202ms | 205ms | 3ms | 1.48
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deletePost | p99 | 25ms | 89ms | 64ms | 257.55
| getTeamMember | p99 | 12ms | 15ms | 3ms | 24.44
| getChannel | p99 | 8ms | 10ms | 2ms | 24.24
| updateReadStateThreadByUser | p99 | 57ms | 70ms | 13ms | 22.92
| autocompleteChannelsForTeamForSearch | p99 | 94ms | 114ms | 20ms | 21.22
| addChannelMember | p99 | 419ms | 474ms | 55ms | 13.11
| patchPost | p99 | 51ms | 57ms | 6ms | 11.65
| autocompleteUsers | p99 | 139ms | 151ms | 12ms | 8.66
| createDirectChannel | p99 | 477ms | 486ms | 9ms | 1.89
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getAnalytics | avg | 15ms | 0s | -15ms | -100.44
| createJob | avg | 4ms | 0s | -4ms | -99.53
| getFilteredUsersStats | avg | 9ms | 0s | -9ms | -99.49
| updateChannelBookmark | avg | 22ms | 0s | -22ms | -98.67
| searchFiles | avg | 5ms | 0s | -5ms | -96.37
| createCategoryForTeamForUser | avg | 34ms | 29ms | -5ms | -14.54
| searchPostsInTeam | avg | 28ms | 24ms | -4ms | -14.26
| removeUserCustomStatus | avg | 136ms | 125ms | -11ms | -8.10
| createGroupChannel | avg | 274ms | 253ms | -21ms | -7.66
| createPost | avg | 175ms | 171ms | -4ms | -2.29
| addTeamMember | avg | 583ms | 572ms | -11ms | -1.89
| createUser | avg | 119ms | 117ms | -2ms | -1.67
| uploadFileStream | avg | 407ms | 402ms | -5ms | -1.23
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getAnalytics | p99 | 25ms | 0s | -25ms | -101.12
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| createJob | p99 | 5ms | 0s | -5ms | -101.01
| getUserByUsername | p99 | 5ms | 0s | -5ms | -101.01
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| updateChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| searchFiles | p99 | 10ms | 0s | -10ms | -100.50
| getFilteredUsersStats | p99 | 10ms | 0s | -10ms | -100.48
| getJobsByType | p99 | 18ms | 5ms | -13ms | -72.41
| createChannel | p99 | 483ms | 249ms | -234ms | -48.50
| searchPostsInTeam | p99 | 669ms | 406ms | -263ms | -39.33
| getAllTeams | p99 | 15ms | 10ms | -5ms | -33.63
| unfollowThreadByUser | p99 | 37ms | 25ms | -12ms | -32.22
| getCategoriesForTeamForUser | p99 | 40ms | 28ms | -12ms | -30.37
| getChannelsForUser | p99 | 22ms | 16ms | -6ms | -27.55
| getThreadsForUser | p99 | 14ms | 11ms | -3ms | -22.06
| getPostThread | p99 | 18ms | 14ms | -4ms | -21.67
| createUser | p99 | 357ms | 282ms | -75ms | -21.03
| getDrafts | p99 | 10ms | 8ms | -2ms | -21.01
| getPostsForChannelAroundLastUnread | p99 | 58ms | 46ms | -12ms | -20.74
| getChannelMember | p99 | 46ms | 38ms | -8ms | -17.55
| addTeamMember | p99 | 2.077s | 1.713s | -364ms | -17.53
| getClientConfig | p99 | 41ms | 34ms | -7ms | -17.21
| getChannelMembersForTeamForUser | p99 | 13ms | 11ms | -2ms | -15.58
| getTeamsUnreadForUser | p99 | 19ms | 16ms | -3ms | -15.57
| getUser | p99 | 20ms | 18ms | -2ms | -9.83
| createPost | p99 | 789ms | 712ms | -77ms | -9.76
| getTeamMembersForUser | p99 | 21ms | 19ms | -2ms | -9.43
| getUsers | p99 | 22ms | 20ms | -2ms | -9.16
| viewChannel | p99 | 27ms | 25ms | -2ms | -7.38
| searchUsers | p99 | 54ms | 52ms | -2ms | -3.67
| getFileThumbnail | p99 | 85ms | 83ms | -2ms | -2.36
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 134.539
| |  P99| 5ms| 22ms | 17ms | 343.434
| BotStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Delete |  Avg| 6ms| 0s | -6ms | -107.755
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelBookmarkStore.Get |  Avg| 1ms| 0s | -1ms | -128.805
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 10ms| 12ms | 2ms | 19.135
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 55ms| 53ms | -2ms | -3.657
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 20ms| 25ms | 5ms | 25.100
| |  P99| 94ms| 114ms | 20ms | 21.220
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 38ms| 44ms | 6ms | 15.790
| ChannelStore.CreateInitialSidebarCategories |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 75ms| 67ms | -8ms | -10.737
| ChannelStore.CreateSidebarCategory |  Avg| 32ms| 28ms | -4ms | -12.487
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.495
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.066
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 13ms | 2ms | 17.671
| |  P99| 87ms| 94ms | 7ms | 8.086
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 31ms | 3ms | 10.572
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 3ms | 2ms | 167.042
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.730
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.329
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 14ms | -5ms | -25.657
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.580
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 46ms| 44ms | -2ms | -4.351
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.508
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -23.780
| ChannelStore.GetMembers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.395
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 10ms| 9ms | -1ms | -10.071
| |  P99| 39ms| 27ms | -12ms | -31.085
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 9ms | 1ms | 12.105
| |  P99| 25ms| 41ms | 16ms | 64.738
| ChannelStore.GetTeamChannels |  Avg| 10ms| 12ms | 2ms | 19.345
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.760
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 24ms| 41ms | 17ms | 69.451
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 87ms| 80ms | -7ms | -8.039
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.557
| ChannelStore.UpdateSidebarCategories |  Avg| 48ms| 47ms | -1ms | -2.092
| |  P99| 95ms| 98ms | 3ms | 3.174
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.035
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 12ms | -9ms | -43.796
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 2ms| 4ms | 2ms | 112.799
| |  P99| 5ms| 133ms | 128ms | 2585.859
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.187
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 8ms | 4ms | 92.239
| |  P99| 10ms| 89ms | 79ms | 802.031
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -21.030
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.833
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 11ms | 6ms | 120.685
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.212
| FileInfoStore.Search |  Avg| 4ms| 0s | -4ms | -90.316
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 38ms| 21ms | -17ms | -45.236
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 8ms | -4ms | -32.590
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.025
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -72.362
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -20.321
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -72.410
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 5ms | -11ms | -70.064
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -50.992
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.743
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 97.659
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -56.204
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.637
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.153
| PluginStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 8ms | -12ms | -61.224
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.181
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.264
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 0s | -1ms | -173.970
| |  P99| 8ms| 5ms | -3ms | -37.262
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.142
| PostStore.AnalyticsPostCount |  Avg| 243ms| 177ms | -66ms | -27.132
| |  P99| 495ms| 495ms | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 17ms | 2ms | 13.548
| |  P99| 25ms| 47ms | 22ms | 88.531
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 11ms | -5ms | -31.891
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.808
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.464
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 2ms | 1ms | 92.277
| |  P99| 5ms| 9ms | 4ms | 80.798
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.587
| PostStore.GetPostsAfter |  Avg| 1ms| 2ms | 1ms | 68.609
| |  P99| 5ms| 19ms | 14ms | 282.828
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.231
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 25ms| 20ms | -5ms | -20.377
| |  P99| 621ms| 406ms | -215ms | -34.597
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 6ms | 4ms | 169.472
| |  P99| 5ms| 89ms | 84ms | 1696.970
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.627
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.832
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.170
| ProductNoticesStore.ClearOldNotices |  Avg| 13ms| 14ms | 1ms | 7.409
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 37ms| 36ms | -1ms | -2.722
| |  P99| 121ms| 100ms | -21ms | -17.401
| ReactionStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.004
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -101.472
| |  P99| 5ms| 0s | -5ms | -100.938
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.853
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.781
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 0s | -1ms | -195.412
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.697
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 14ms | 10ms | 254.683
| |  P99| 16ms| 214ms | 198ms | 1212.465
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 2ms | -1ms | -39.781
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 2ms | -1ms | -39.506
| |  P99| 18ms| 15ms | -3ms | -16.437
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 0s | -1ms | -185.611
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.318
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.605
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -24.979
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 11ms | -4ms | -26.312
| TeamStore.GetTotalMemberCount |  Avg| 19ms| 34ms | 15ms | 80.362
| |  P99| 25ms| 50ms | 25ms | 100.565
| TeamStore.SaveMember |  Avg| 23ms| 24ms | 1ms | 4.329
| |  P99| 63ms| 63ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.427
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 1ms | -1ms | -64.961
| |  P99| 12ms| 10ms | -2ms | -16.775
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.285
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.705
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.954
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.426
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.251
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.299
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 170ms| 172ms | 2ms | 1.178
| UserStore.Count |  Avg| 9ms| 10ms | 1ms | 10.965
| |  P99| 20ms| 24ms | 4ms | 19.512
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.855
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.541
| UserStore.GetAllProfilesInChannel |  Avg| 153ms| 151ms | -2ms | -1.310
| |  P99| 475ms| 473ms | -2ms | -0.421
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.476
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.639
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.022
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.740
| UserStore.GetProfilesInChannel |  Avg| 23ms| 30ms | 7ms | 30.533
| |  P99| 238ms| 243ms | 5ms | 2.101
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.137
| UserStore.IsEmpty |  Avg| 1ms| 0s | -1ms | -193.419
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 74ms| 74ms | 0s | 0.000
| |  P99| 210ms| 204ms | -6ms | -2.856
| UserStore.Search |  Avg| 25ms| 26ms | 1ms | 3.950
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 8ms | 1ms | 13.694
| |  P99| 20ms| 23ms | 3ms | 15.306
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.273
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.620
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 28ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 159ms| 178ms | 19ms | 11.982
| | P99| 419ms| 474ms | 55ms | 13.115
| addTeamMember | Avg| 583ms| 572ms | -11ms | -1.888
| | P99| 2.077s| 1.713s | -364ms | -17.529
| autocompleteChannelsForTeamForSearch | Avg| 20ms| 25ms | 5ms | 25.026
| | P99| 94ms| 114ms | 20ms | 21.220
| autocompleteUsers | Avg| 31ms| 32ms | 1ms | 3.253
| | P99| 139ms| 151ms | 12ms | 8.663
| createCategoryForTeamForUser | Avg| 34ms| 29ms | -5ms | -14.541
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 202ms| 205ms | 3ms | 1.482
| | P99| 483ms| 249ms | -234ms | -48.497
| createChannelBookmark | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 172ms| 184ms | 12ms | 6.974
| | P99| 477ms| 486ms | 9ms | 1.885
| createGroupChannel | Avg| 274ms| 253ms | -21ms | -7.658
| | P99| 497ms| 496ms | -1ms | -0.201
| createJob | Avg| 4ms| 0s | -4ms | -99.533
| | P99| 5ms| 0s | -5ms | -101.010
| createPost | Avg| 175ms| 171ms | -4ms | -2.290
| | P99| 789ms| 712ms | -77ms | -9.763
| createUser | Avg| 119ms| 117ms | -2ms | -1.675
| | P99| 357ms| 282ms | -75ms | -21.032
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| deletePost | Avg| 18ms| 23ms | 5ms | 27.103
| | P99| 25ms| 89ms | 64ms | 257.545
| followThreadByUser | Avg| 11ms| 14ms | 3ms | 27.052
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 15ms| 10ms | -5ms | -33.629
| getAnalytics | Avg| 15ms| 0s | -15ms | -100.442
| | P99| 25ms| 0s | -25ms | -101.123
| getCategoriesForTeamForUser | Avg| 10ms| 9ms | -1ms | -9.918
| | P99| 40ms| 28ms | -12ms | -30.366
| getChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 10ms | 2ms | 24.241
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 46ms| 38ms | -8ms | -17.553
| getChannelMembers | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 11ms | -2ms | -15.584
| getChannelMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 22ms| 16ms | -6ms | -27.553
| getClientConfig | Avg| 8ms| 7ms | -1ms | -13.324
| | P99| 41ms| 34ms | -7ms | -17.208
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 10ms| 8ms | -2ms | -21.007
| getFilePreview | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 94ms| 94ms | 0s | 0.000
| getFileThumbnail | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 85ms| 83ms | -2ms | -2.360
| getFilteredUsersStats | Avg| 9ms| 0s | -9ms | -99.485
| | P99| 10ms| 0s | -10ms | -100.480
| getGroups | Avg| 1ms| 0s | -1ms | -114.468
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 18ms| 5ms | -13ms | -72.410
| getPostThread | Avg| 4ms| 3ms | -1ms | -27.191
| | P99| 18ms| 14ms | -4ms | -21.669
| getPostsForChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 89ms| 88ms | -1ms | -1.119
| getPostsForChannelAroundLastUnread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 58ms| 46ms | -12ms | -20.740
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.449
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 0s | -1ms | -128.878
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 80ms| 79ms | -1ms | -1.243
| | P99| 379ms| 378ms | -1ms | -0.264
| getPublicChannelsForTeam | Avg| 12ms| 13ms | 1ms | 8.008
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 0s | -1ms | -144.630
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 15ms | 3ms | 24.436
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.431
| getTeamStats | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.440
| getTeamsUnreadForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 16ms | -3ms | -15.570
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 11ms | -3ms | -22.061
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 18ms | -2ms | -9.832
| getUserByUsername | Avg| 1ms| 0s | -1ms | -115.662
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.155
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -16.448
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 61ms| 60ms | -1ms | -1.642
| | P99| 246ms| 246ms | 0s | 0.000
| logout | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| patchPost | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 51ms| 57ms | 6ms | 11.652
| removeUserCustomStatus | Avg| 136ms| 125ms | -11ms | -8.096
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.524
| searchAllChannels | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchFiles | Avg| 5ms| 0s | -5ms | -96.370
| | P99| 10ms| 0s | -10ms | -100.503
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| searchPostsInTeam | Avg| 28ms| 24ms | -4ms | -14.258
| | P99| 669ms| 406ms | -263ms | -39.326
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 54ms| 52ms | -2ms | -3.671
| setPostReminder | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 37ms| 25ms | -12ms | -32.220
| updateCategoriesForTeamForUser | Avg| 64ms| 64ms | 0s | 0.000
| | P99| 219ms| 220ms | 1ms | 0.458
| updateChannelBookmark | Avg| 22ms| 0s | -22ms | -98.672
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 26ms| 27ms | 1ms | 3.801
| | P99| 57ms| 70ms | 13ms | 22.925
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 407ms| 402ms | -5ms | -1.227
| | P99| 990ms| 988ms | -2ms | -0.202
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.529
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 27ms| 25ms | -2ms | -7.379

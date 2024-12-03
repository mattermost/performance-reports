### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 2ms | 10ms | 8ms | 338.80
| CommandWebhookStore.Cleanup | avg | 1ms | 3ms | 2ms | 300.53
| SessionStore.GetSessionsExpired | avg | 2ms | 5ms | 3ms | 151.57
| ProductNoticesStore.ClearOldNotices | avg | 10ms | 13ms | 3ms | 28.82
| UserStore.Count | avg | 10ms | 12ms | 2ms | 19.85
| ChannelStore.GetTeamChannels | avg | 12ms | 14ms | 2ms | 17.35
| UserStore.GetAllProfilesInChannel | avg | 147ms | 159ms | 12ms | 8.17
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 8ms | 213ms | 205ms | 2647.42
| SessionStore.GetSessionsExpired | p99 | 5ms | 47ms | 42ms | 848.48
| JobStore.Get | p99 | 5ms | 31ms | 26ms | 490.57
| RoleStore.GetByNames | p99 | 7ms | 36ms | 29ms | 420.29
| CommandWebhookStore.Cleanup | p99 | 5ms | 24ms | 19ms | 383.67
| PostStore.GetPostReminders | p99 | 5ms | 21ms | 16ms | 323.23
| UserAccessTokenStore.GetByToken | p99 | 5ms | 21ms | 16ms | 323.19
| UserStore.GetMany | p99 | 5ms | 17ms | 12ms | 242.42
| ClusterDiscoveryStore.SetLastPingAt | p99 | 6ms | 19ms | 13ms | 212.25
| JobStore.UpdateStatus | p99 | 5ms | 13ms | 8ms | 161.62
| UserStore.GetProfilesNotInChannel | p99 | 9ms | 23ms | 14ms | 152.18
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 9ms | 23ms | 14ms | 148.94
| UserStore.GetUnreadCount | p99 | 10ms | 23ms | 13ms | 133.01
| ChannelBookmarkStore.Save | p99 | 10ms | 23ms | 13ms | 131.31
| JobStore.Save | p99 | 8ms | 19ms | 11ms | 130.43
| BotStore.Get | p99 | 9ms | 21ms | 12ms | 127.43
| LinkMetadataStore.Save | p99 | 9ms | 19ms | 10ms | 112.08
| PostStore.GetPostsByThread | p99 | 10ms | 20ms | 10ms | 100.27
| FileInfoStore.GetByIds | p99 | 5ms | 10ms | 5ms | 100.21
| UserStore.Count | p99 | 25ms | 46ms | 21ms | 84.92
| ChannelStore.GetTeamChannels | p99 | 25ms | 46ms | 21ms | 84.81
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateOptimistically | p99 | 5ms | 9ms | 4ms | 75.47
| ThreadStore.GetTotalUnreadMentions | p99 | 9ms | 16ms | 7ms | 74.13
| UserStore.UpdateFailedPasswordAttempts | p99 | 9ms | 16ms | 7ms | 73.91
| PreferenceStore.GetAll | p99 | 10ms | 17ms | 7ms | 71.94
| ChannelStore.GetMember | p99 | 8ms | 14ms | 6ms | 71.61
| FileInfoStore.Save | p99 | 10ms | 17ms | 7ms | 71.61
| ChannelStore.GetGuestCount | p99 | 10ms | 17ms | 7ms | 69.26
| ThreadStore.Get | p99 | 5ms | 8ms | 3ms | 60.61
| TeamStore.GetMember | p99 | 5ms | 8ms | 3ms | 60.38
| ThreadStore.GetThreadsForUser | p99 | 10ms | 16ms | 6ms | 60.15
| ChannelStore.GetPinnedPostCount | p99 | 5ms | 8ms | 3ms | 60.08
| ChannelStore.GetChannelUnread | p99 | 5ms | 8ms | 3ms | 58.36
| ChannelStore.IncrementMentionCount | p99 | 5ms | 8ms | 3ms | 56.96
| ChannelStore.GetByName | p99 | 24ms | 37ms | 13ms | 54.03
| JobStore.GetAllByStatus | p99 | 10ms | 15ms | 5ms | 51.37
| PostStore.GetEtag | p99 | 10ms | 15ms | 5ms | 50.89
| PostStore.GetPostsBefore | p99 | 10ms | 15ms | 5ms | 50.04
| PluginStore.List | p99 | 6ms | 9ms | 3ms | 46.15
| WebhookStore.GetOutgoingByTeam | p99 | 25ms | 36ms | 11ms | 44.42
| UserStore.Save | p99 | 121ms | 171ms | 50ms | 41.24
| TeamStore.GetTeamsForUser | p99 | 7ms | 10ms | 3ms | 40.39
| DraftStore.GetDraftsForUser | p99 | 9ms | 12ms | 3ms | 34.44
| PostAcknowledgementStore.GetForPost | p99 | 9ms | 12ms | 3ms | 33.34
| ChannelStore.GetMemberForPost | p99 | 15ms | 20ms | 5ms | 33.26
| AuditStore.Save | p99 | 12ms | 16ms | 4ms | 32.71
| EmojiStore.GetByName | p99 | 6ms | 8ms | 2ms | 32.30
| ReactionStore.GetForPost | p99 | 10ms | 13ms | 3ms | 31.24
| ChannelStore.GetMemberLastViewedAt | p99 | 7ms | 9ms | 2ms | 30.43
| ChannelStore.GetChannelsByUser | p99 | 7ms | 9ms | 2ms | 28.75
| SessionStore.GetLRUSessions | p99 | 7ms | 9ms | 2ms | 27.15
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 7ms | 9ms | 2ms | 27.00
| ChannelStore.GetFileCount | p99 | 8ms | 10ms | 2ms | 25.92
| StatusStore.Get | p99 | 8ms | 10ms | 2ms | 25.88
| PostStore.GetPosts | p99 | 12ms | 15ms | 3ms | 24.84
| TeamStore.GetAllPage | p99 | 8ms | 10ms | 2ms | 24.64
| ThreadStore.GetTotalThreads | p99 | 8ms | 10ms | 2ms | 24.63
| ThreadStore.GetTotalUnreadThreads | p99 | 8ms | 10ms | 2ms | 23.90
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 8ms | 10ms | 2ms | 23.62
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 8ms | 10ms | 2ms | 23.61
| DraftStore.Upsert | p99 | 9ms | 11ms | 2ms | 22.51
| ChannelStore.GetMembersForUser | p99 | 9ms | 11ms | 2ms | 21.65
| ThreadStore.GetTeamsUnreadForUser | p99 | 9ms | 11ms | 2ms | 21.18
| FileInfoStore.AttachToPost | p99 | 10ms | 12ms | 2ms | 20.88
| ChannelStore.SaveMember | p99 | 50ms | 60ms | 10ms | 20.04
| SessionStore.Save | p99 | 16ms | 19ms | 3ms | 18.62
| SessionStore.Get | p99 | 17ms | 20ms | 3ms | 17.37
| PreferenceStore.Save | p99 | 19ms | 22ms | 3ms | 15.43
| PostAcknowledgementStore.GetForPosts | p99 | 16ms | 18ms | 2ms | 12.85
| UserStore.Search | p99 | 50ms | 56ms | 6ms | 12.03
| PostPriorityStore.GetForPosts | p99 | 17ms | 19ms | 2ms | 11.90
| PostStore.Get | p99 | 17ms | 19ms | 2ms | 11.88
| FileInfoStore.SetContent | p99 | 19ms | 21ms | 2ms | 10.38
| ChannelStore.CreateInitialSidebarCategories | p99 | 50ms | 55ms | 5ms | 10.06
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 90ms | 98ms | 8ms | 8.85
| TeamStore.SaveMember | p99 | 45ms | 48ms | 3ms | 6.61
| PostStore.GetPostsSince | p99 | 45ms | 47ms | 2ms | 4.47
| UserStore.GetAllProfilesInChannel | p99 | 459ms | 477ms | 18ms | 3.92
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.UpdateSortOrder | avg | 5ms | 0s | -5ms | -101.88
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 12ms | 0s | -12ms | -100.85
| ChannelStore.CreateSidebarCategory | avg | 18ms | 0s | -18ms | -99.24
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -88.32
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 1ms | -2ms | -75.14
| PostStore.SetPostReminder | avg | 7ms | 3ms | -4ms | -57.67
| ChannelStore.GetAllChannelMembersForUser | avg | 5ms | 3ms | -2ms | -40.53
| UserStore.GetProfilesInChannel | avg | 51ms | 35ms | -16ms | -31.29
| ChannelStore.AutocompleteInTeamForSearch | avg | 82ms | 64ms | -18ms | -21.94
| PostStore.SearchPostsForUser | avg | 173ms | 152ms | -21ms | -12.11
| ChannelStore.UpdateSidebarCategories | avg | 36ms | 34ms | -2ms | -5.49
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.UpdateSortOrder | p99 | 10ms | 0s | -10ms | -101.52
| RetentionPolicyStore.GetCount | p99 | 22ms | 0s | -22ms | -101.03
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.58
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 25ms | 0s | -25ms | -100.51
| RetentionPolicyStore.GetAll | p99 | 39ms | 0s | -39ms | -99.36
| PostStore.SetPostReminder | p99 | 48ms | 5ms | -43ms | -89.35
| PostStore.GetPostReminderMetadata | p99 | 43ms | 8ms | -35ms | -81.40
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 5ms | -4ms | -45.33
| ChannelStore.GetAllChannelMembersForUser | p99 | 24ms | 15ms | -9ms | -38.03
| JobStore.GetCountByStatusAndType | p99 | 21ms | 13ms | -8ms | -37.38
| StatusStore.UpdateExpiredDNDStatuses | p99 | 8ms | 5ms | -3ms | -36.36
| RoleStore.ChannelHigherScopedPermissions | p99 | 14ms | 9ms | -5ms | -34.84
| JobStore.GetNewestJobByStatusesAndType | p99 | 26ms | 17ms | -9ms | -34.62
| ChannelStore.Save | p99 | 33ms | 25ms | -8ms | -24.24
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.313s | 2.52s | -793ms | -23.94
| ChannelStore.GetSidebarCategory | p99 | 38ms | 30ms | -8ms | -21.05
| UserStore.Update | p99 | 10ms | 8ms | -2ms | -20.11
| ChannelStore.UpdateSidebarCategories | p99 | 88ms | 80ms | -8ms | -9.09
| PostStore.Delete | p99 | 23ms | 21ms | -2ms | -8.62
| ChannelStore.CreateDirectChannel | p99 | 43ms | 40ms | -3ms | -7.01
| PostStore.SearchPostsForUser | p99 | 2.3s | 2.243s | -57ms | -2.48
| UserStore.GetProfilesInChannel | p99 | 245ms | 242ms | -3ms | -1.22
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | avg | 10ms | 17ms | 7ms | 70.34
| viewChannel | avg | 8ms | 10ms | 2ms | 25.56
| logout | avg | 25ms | 29ms | 4ms | 15.86
| createChannel | avg | 164ms | 187ms | 23ms | 14.06
| addTeamMember | avg | 497ms | 537ms | 40ms | 8.06
| updateReadStateThreadByUser | avg | 32ms | 34ms | 2ms | 6.30
| removeUserCustomStatus | avg | 115ms | 120ms | 5ms | 4.36
| createGroupChannel | avg | 262ms | 272ms | 10ms | 3.82
| addChannelMember | avg | 165ms | 171ms | 6ms | 3.64
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | p99 | 25ms | 94ms | 69ms | 279.01
| logout | p99 | 95ms | 211ms | 116ms | 122.11
| getPreferences | p99 | 10ms | 18ms | 8ms | 81.10
| getUser | p99 | 9ms | 16ms | 7ms | 75.67
| getPostThread | p99 | 25ms | 41ms | 16ms | 63.25
| upsertDraft | p99 | 10ms | 16ms | 6ms | 60.42
| getUsers | p99 | 10ms | 16ms | 6ms | 60.38
| getTeamMember | p99 | 5ms | 8ms | 3ms | 60.07
| getDrafts | p99 | 9ms | 14ms | 5ms | 53.92
| getTeamMembersForUser | p99 | 9ms | 14ms | 5ms | 52.81
| getChannelMember | p99 | 15ms | 23ms | 8ms | 52.68
| getThreadsForUser | p99 | 11ms | 16ms | 5ms | 47.14
| viewChannel | p99 | 24ms | 34ms | 10ms | 41.22
| updatePreferences | p99 | 10ms | 14ms | 4ms | 38.84
| getChannelsForTeamForUser | p99 | 10ms | 13ms | 3ms | 31.48
| getClientConfig | p99 | 10ms | 13ms | 3ms | 31.24
| getAllTeams | p99 | 10ms | 13ms | 3ms | 30.70
| getChannelMembersForTeamForUser | p99 | 10ms | 13ms | 3ms | 30.43
| getChannelsForUser | p99 | 7ms | 9ms | 2ms | 28.59
| getUsersByNames | p99 | 8ms | 10ms | 2ms | 23.69
| searchUsers | p99 | 50ms | 61ms | 11ms | 22.01
| getChannel | p99 | 16ms | 19ms | 3ms | 18.46
| getTeamsUnreadForUser | p99 | 16ms | 19ms | 3ms | 18.44
| updateReadStateThreadByUser | p99 | 79ms | 92ms | 13ms | 16.53
| getChannelStats | p99 | 25ms | 28ms | 3ms | 12.07
| saveReaction | p99 | 25ms | 27ms | 2ms | 8.07
| updateCategoriesForTeamForUser | p99 | 178ms | 190ms | 12ms | 6.74
| addChannelMember | p99 | 455ms | 477ms | 22ms | 4.84
| getPostsForChannel | p99 | 186ms | 194ms | 8ms | 4.29
| getFileThumbnail | p99 | 85ms | 87ms | 2ms | 2.35
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmarkSortOrder | avg | 14ms | 0s | -14ms | -101.98
| createCategoryForTeamForUser | avg | 20ms | 0s | -20ms | -98.13
| updateReadStateAllThreadsByUser | avg | 3ms | 1ms | -2ms | -72.93
| setPostReminder | avg | 26ms | 15ms | -11ms | -42.97
| createPost | avg | 246ms | 186ms | -60ms | -24.37
| autocompleteChannelsForTeamForSearch | avg | 82ms | 64ms | -18ms | -21.92
| patchPost | avg | 26ms | 22ms | -4ms | -15.50
| getProfileImage | avg | 80ms | 69ms | -11ms | -13.69
| searchPostsInTeam | avg | 181ms | 159ms | -22ms | -12.19
| updateCategoriesForTeamForUser | avg | 58ms | 56ms | -2ms | -3.42
| createDirectChannel | avg | 178ms | 172ms | -6ms | -3.37
| uploadFileStream | avg | 392ms | 386ms | -6ms | -1.53
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -101.01
| updateChannelBookmarkSortOrder | p99 | 25ms | 0s | -25ms | -100.60
| setPostReminder | p99 | 227ms | 46ms | -181ms | -79.56
| patchPost | p99 | 175ms | 48ms | -127ms | -72.57
| getProfileImage | p99 | 352ms | 262ms | -90ms | -25.59
| autocompleteChannelsForTeamForSearch | p99 | 3.313s | 2.52s | -793ms | -23.94
| removeUserCustomStatus | p99 | 464ms | 365ms | -99ms | -21.32
| createPost | p99 | 872ms | 743ms | -129ms | -14.79
| searchPostsInTeam | p99 | 2.303s | 2.257s | -46ms | -2.00
| createDirectChannel | p99 | 486ms | 479ms | -7ms | -1.44
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 16ms | 4ms | 32.709
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 21ms | 12ms | 127.434
| ChannelBookmarkStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.702
| ChannelBookmarkStore.Save |  Avg| 5ms| 6ms | 1ms | 18.460
| |  P99| 10ms| 23ms | 13ms | 131.313
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 5ms| 0s | -5ms | -101.878
| |  P99| 10ms| 0s | -10ms | -101.523
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.002
| ChannelStore.Autocomplete |  Avg| 32ms| 33ms | 1ms | 3.082
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 82ms| 64ms | -18ms | -21.936
| |  P99| 3.313s| 2.52s | -793ms | -23.939
| ChannelStore.CreateDirectChannel |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 43ms| 40ms | -3ms | -7.013
| ChannelStore.CreateInitialSidebarCategories |  Avg| 24ms| 25ms | 1ms | 4.137
| |  P99| 50ms| 55ms | 5ms | 10.059
| ChannelStore.CreateSidebarCategory |  Avg| 18ms| 0s | -18ms | -99.238
| |  P99| 25ms| 0s | -25ms | -100.584
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.142
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 12ms| 0s | -12ms | -100.846
| |  P99| 25ms| 0s | -25ms | -100.508
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 3ms | -2ms | -40.526
| |  P99| 24ms| 15ms | -9ms | -38.032
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 14ms | 1ms | 7.614
| |  P99| 90ms| 98ms | 8ms | 8.852
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 37ms | 13ms | 54.033
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 58.358
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.718
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 28.746
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.348
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.915
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 69.263
| ChannelStore.GetMember |  Avg| 1ms| 2ms | 1ms | 76.171
| |  P99| 8ms| 14ms | 6ms | 71.615
| ChannelStore.GetMemberCount |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.210
| ChannelStore.GetMemberForPost |  Avg| 4ms| 5ms | 1ms | 22.425
| |  P99| 15ms| 20ms | 5ms | 33.261
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 30.435
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.646
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.075
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.089
| ChannelStore.GetSidebarCategory |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 38ms| 30ms | -8ms | -21.053
| ChannelStore.GetTeamChannels |  Avg| 12ms| 14ms | 2ms | 17.355
| |  P99| 25ms| 46ms | 21ms | 84.814
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 56.965
| ChannelStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 33ms| 25ms | -8ms | -24.243
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 50ms| 60ms | 10ms | 20.045
| ChannelStore.SearchGroupChannels |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 36ms| 34ms | -2ms | -5.491
| |  P99| 88ms| 80ms | -8ms | -9.091
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 3ms | 1ms | 45.340
| |  P99| 6ms| 19ms | 13ms | 212.249
| CommandWebhookStore.Cleanup |  Avg| 1ms| 3ms | 2ms | 300.525
| |  P99| 5ms| 24ms | 19ms | 383.673
| DesktopTokensStore.DeleteOlderThan |  Avg| 0s| 1ms | 1ms | 240.155
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.200
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 4ms | 1ms | 34.467
| |  P99| 9ms| 23ms | 14ms | 148.936
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.554
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 34.440
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 22.509
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 32.302
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.883
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.116
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.210
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.829
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 71.611
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.379
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.245
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.667
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.291
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 31ms | 26ms | 490.566
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 51.370
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -37.327
| |  P99| 21ms| 13ms | -8ms | -37.383
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -37.542
| |  P99| 26ms| 17ms | -9ms | -34.615
| JobStore.Save |  Avg| 2ms| 3ms | 1ms | 40.769
| |  P99| 8ms| 19ms | 11ms | 130.435
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 75.472
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 13ms | 8ms | 161.616
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.326
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 3ms | 1ms | 45.774
| |  P99| 9ms| 19ms | 10ms | 112.076
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 9ms | 3ms | 46.154
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.869
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 33.345
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.852
| PostPersistentNotificationStore.DeleteExpired |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.929
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.897
| PostStore.AnalyticsPostCount |  Avg| 346ms| 348ms | 2ms | 0.578
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.621
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.884
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 50.889
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 3ms | -1ms | -26.130
| |  P99| 43ms| 8ms | -35ms | -81.396
| PostStore.GetPostReminders |  Avg| 2ms| 3ms | 1ms | 52.758
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.838
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 50.037
| PostStore.GetPostsByThread |  Avg| 4ms| 5ms | 1ms | 24.019
| |  P99| 10ms| 20ms | 10ms | 100.272
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.475
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.171
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.112
| PostStore.SearchPostsForUser |  Avg| 173ms| 152ms | -21ms | -12.109
| |  P99| 2.3s| 2.243s | -57ms | -2.478
| PostStore.SetPostReminder |  Avg| 7ms| 3ms | -4ms | -57.666
| |  P99| 48ms| 5ms | -43ms | -89.351
| PostStore.Update |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.045
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 3ms | 1ms | 40.853
| |  P99| 10ms| 17ms | 7ms | 71.942
| PreferenceStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.432
| ProductNoticesStore.ClearOldNotices |  Avg| 10ms| 13ms | 3ms | 28.817
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 14ms| 15ms | 1ms | 7.194
| |  P99| 93ms| 92ms | -1ms | -1.080
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 31.236
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -88.325
| |  P99| 39ms| 0s | -39ms | -99.363
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -72.022
| |  P99| 22ms| 0s | -22ms | -101.033
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -34.843
| RoleStore.GetByNames |  Avg| 2ms| 3ms | 1ms | 52.128
| |  P99| 7ms| 36ms | 29ms | 420.290
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.371
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.155
| SessionStore.GetSessionsExpired |  Avg| 2ms| 5ms | 3ms | 151.567
| |  P99| 5ms| 47ms | 42ms | 848.485
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.618
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.624
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.580
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.880
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.766
| StatusStore.SaveOrUpdate |  Avg| 2ms| 10ms | 8ms | 338.804
| |  P99| 8ms| 213ms | 205ms | 2647.418
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.364
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 0s| 1ms | 1ms | 215.682
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.981
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 37ms | 1ms | 2.805
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.643
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.655
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.385
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.452
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 40.392
| TeamStore.GetTotalMemberCount |  Avg| 31ms| 32ms | 1ms | 3.178
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 19ms| 20ms | 1ms | 5.172
| |  P99| 45ms| 48ms | 3ms | 6.606
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.061
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.184
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.809
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.361
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.287
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.150
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.633
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 3ms | 1ms | 43.291
| |  P99| 9ms| 16ms | 7ms | 74.131
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.898
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.608
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 1ms | -2ms | -75.144
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.664
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.187
| UserStore.AutocompleteUsersInChannel |  Avg| 35ms| 36ms | 1ms | 2.843
| |  P99| 170ms| 170ms | 0s | 0.000
| UserStore.Count |  Avg| 10ms| 12ms | 2ms | 19.845
| |  P99| 25ms| 46ms | 21ms | 84.917
| UserStore.Get |  Avg| 2ms| 1ms | -1ms | -60.502
| |  P99| 6ms| 7ms | 1ms | 17.554
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.694
| UserStore.GetAllProfilesInChannel |  Avg| 147ms| 159ms | 12ms | 8.172
| |  P99| 459ms| 477ms | 18ms | 3.924
| UserStore.GetByUsername |  Avg| 2ms| 3ms | 1ms | 40.838
| |  P99| 10ms| 9ms | -1ms | -10.135
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.488
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 17ms | 12ms | 242.424
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.256
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.327
| UserStore.GetProfilesInChannel |  Avg| 51ms| 35ms | -16ms | -31.291
| |  P99| 245ms| 242ms | -3ms | -1.223
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 5ms | 1ms | 23.962
| |  P99| 9ms| 23ms | 14ms | 152.175
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 133.014
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 72ms| 73ms | 1ms | 1.399
| |  P99| 121ms| 171ms | 50ms | 41.236
| UserStore.Search |  Avg| 27ms| 28ms | 1ms | 3.716
| |  P99| 50ms| 56ms | 6ms | 12.031
| UserStore.Update |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.105
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 73.911
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.783
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.051
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.208
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 5ms | 1ms | 23.708
| |  P99| 25ms| 36ms | 11ms | 44.419
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 165ms| 171ms | 6ms | 3.643
| | P99| 455ms| 477ms | 22ms | 4.839
| addTeamMember | Avg| 497ms| 537ms | 40ms | 8.056
| | P99| 993ms| 995ms | 2ms | 0.201
| autocompleteChannelsForTeamForSearch | Avg| 82ms| 64ms | -18ms | -21.921
| | P99| 3.313s| 2.52s | -793ms | -23.939
| autocompleteUsers | Avg| 32ms| 33ms | 1ms | 3.103
| | P99| 146ms| 147ms | 1ms | 0.683
| createCategoryForTeamForUser | Avg| 20ms| 0s | -20ms | -98.135
| | P99| 50ms| 0s | -50ms | -101.010
| createChannel | Avg| 164ms| 187ms | 23ms | 14.058
| | P99| 480ms| 480ms | 0s | 0.000
| createChannelBookmark | Avg| 10ms| 17ms | 7ms | 70.345
| | P99| 25ms| 94ms | 69ms | 279.013
| createDirectChannel | Avg| 178ms| 172ms | -6ms | -3.369
| | P99| 486ms| 479ms | -7ms | -1.440
| createGroupChannel | Avg| 262ms| 272ms | 10ms | 3.815
| | P99| 499ms| 496ms | -3ms | -0.601
| createPost | Avg| 246ms| 186ms | -60ms | -24.366
| | P99| 872ms| 743ms | -129ms | -14.789
| createUser | Avg| 133ms| 134ms | 1ms | 0.751
| | P99| 444ms| 445ms | 1ms | 0.225
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.930
| deletePost | Avg| 14ms| 13ms | -1ms | -7.304
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 3ms | 1ms | 40.347
| | P99| 10ms| 13ms | 3ms | 30.695
| getCategoriesForTeamForUser | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.076
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 16ms| 19ms | 3ms | 18.461
| getChannelMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 23ms | 8ms | 52.677
| getChannelMembers | Avg| 4ms| 3ms | -1ms | -28.108
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 13ms | 3ms | 30.427
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 28ms | 3ms | 12.071
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 13ms | 3ms | 31.479
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 9ms | 2ms | 28.594
| getClientConfig | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 13ms | 3ms | 31.241
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 14ms | 5ms | 53.925
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 94ms| 94ms | 0s | 0.000
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 85ms| 87ms | 2ms | 2.350
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 41ms | 16ms | 63.245
| getPostsForChannel | Avg| 20ms| 21ms | 1ms | 4.947
| | P99| 186ms| 194ms | 8ms | 4.292
| getPostsForChannelAroundLastUnread | Avg| 16ms| 15ms | -1ms | -6.436
| | P99| 48ms| 48ms | 0s | 0.000
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 18ms | 8ms | 81.104
| getProfileImage | Avg| 80ms| 69ms | -11ms | -13.695
| | P99| 352ms| 262ms | -90ms | -25.594
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.073
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 14ms | 5ms | 52.813
| getTeamStats | Avg| 36ms| 37ms | 1ms | 2.787
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.325
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 16ms| 19ms | 3ms | 18.437
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 16ms | 5ms | 47.136
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 16ms | 7ms | 75.672
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 16ms | 6ms | 60.384
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 10ms | 2ms | 23.686
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.305
| login | Avg| 70ms| 69ms | -1ms | -1.420
| | P99| 239ms| 241ms | 2ms | 0.835
| logout | Avg| 25ms| 29ms | 4ms | 15.865
| | P99| 95ms| 211ms | 116ms | 122.106
| patchPost | Avg| 26ms| 22ms | -4ms | -15.502
| | P99| 175ms| 48ms | -127ms | -72.573
| removeUserCustomStatus | Avg| 115ms| 120ms | 5ms | 4.360
| | P99| 464ms| 365ms | -99ms | -21.319
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 27ms | 2ms | 8.069
| searchAllChannels | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| searchPostsInTeam | Avg| 181ms| 159ms | -22ms | -12.187
| | P99| 2.303s| 2.257s | -46ms | -1.998
| searchUsers | Avg| 28ms| 29ms | 1ms | 3.567
| | P99| 50ms| 61ms | 11ms | 22.011
| setPostReminder | Avg| 26ms| 15ms | -11ms | -42.970
| | P99| 227ms| 46ms | -181ms | -79.561
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 10ms | 1ms | 10.694
| | P99| 24ms| 25ms | 1ms | 4.178
| updateCategoriesForTeamForUser | Avg| 58ms| 56ms | -2ms | -3.425
| | P99| 178ms| 190ms | 12ms | 6.742
| updateChannelBookmark | Avg| 11ms| 12ms | 1ms | 9.001
| | P99| 25ms| 25ms | 0s | 0.000
| updateChannelBookmarkSortOrder | Avg| 14ms| 0s | -14ms | -101.981
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 14ms | 4ms | 38.835
| updateReadStateAllThreadsByUser | Avg| 3ms| 1ms | -2ms | -72.933
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 32ms| 34ms | 2ms | 6.298
| | P99| 79ms| 92ms | 13ms | 16.532
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 392ms| 386ms | -6ms | -1.531
| | P99| 985ms| 986ms | 1ms | 0.101
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 16ms | 6ms | 60.416
| viewChannel | Avg| 8ms| 10ms | 2ms | 25.562
| | P99| 24ms| 34ms | 10ms | 41.216

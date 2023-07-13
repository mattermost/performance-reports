### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 4ms | 25ms | 21ms | 576.46
| LinkMetadataStore.Save | avg | 1ms | 3ms | 2ms | 179.06
| PostStore.AnalyticsPostCount | avg | 2.053s | 4.801s | 2.748s | 133.87
| ChannelStore.GetMembers | avg | 10ms | 17ms | 7ms | 71.11
| PostStore.SearchPostsForUser | avg | 90ms | 110ms | 20ms | 22.22
| UserStore.Count | avg | 30ms | 34ms | 4ms | 13.12
| UserStore.Search | avg | 31ms | 33ms | 2ms | 6.46
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 16ms | 423ms | 407ms | 2489.46
| PostStore.GetPostReminderMetadata | p99 | 5ms | 43ms | 38ms | 767.68
| JobStore.UpdateOptimistically | p99 | 5ms | 18ms | 13ms | 262.63
| ChannelStore.GetMembersForUserWithPagination | p99 | 25ms | 86ms | 61ms | 245.47
| PostStore.GetPostReminders | p99 | 10ms | 22ms | 12ms | 121.56
| LinkMetadataStore.Save | p99 | 5ms | 10ms | 5ms | 100.04
| FileInfoStore.AttachToPost | p99 | 11ms | 21ms | 10ms | 91.12
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 19ms | 9ms | 90.76
| JobStore.UpdateStatusOptimistically | p99 | 10ms | 18ms | 8ms | 82.69
| UserAccessTokenStore.GetByToken | p99 | 10ms | 17ms | 7ms | 68.97
| JobStore.UpdateStatus | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.GetTeamChannels | p99 | 50ms | 78ms | 28ms | 56.19
| PostStore.SearchPostsForUser | p99 | 894ms | 1.376s | 482ms | 53.94
| UserStore.AutocompleteUsersInChannel | p99 | 249ms | 378ms | 129ms | 51.87
| ChannelStore.SearchGroupChannels | p99 | 10ms | 15ms | 5ms | 49.72
| ThreadStore.GetThreadFollowers | p99 | 6ms | 8ms | 2ms | 31.25
| PostStore.HasAutoResponsePostByUserSince | p99 | 25ms | 32ms | 7ms | 28.05
| FileInfoStore.Save | p99 | 15ms | 19ms | 4ms | 25.95
| ThreadStore.GetThreadForUser | p99 | 11ms | 13ms | 2ms | 18.38
| PostStore.Delete | p99 | 32ms | 36ms | 4ms | 12.40
| ChannelStore.GetMembers | p99 | 208ms | 233ms | 25ms | 12.04
| SessionStore.Save | p99 | 29ms | 32ms | 3ms | 10.50
| PostStore.Update | p99 | 35ms | 38ms | 3ms | 8.59
| PostStore.GetPostsSince | p99 | 50ms | 54ms | 4ms | 8.05
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| WebhookStore.GetIncomingByTeamByUser | avg | 4ms | 0s | -4ms | -111.13
| ChannelStore.GetTopChannelsForUserSince | avg | 6ms | 0s | -6ms | -101.20
| FileInfoStore.Search | avg | 7ms | 0s | -7ms | -101.18
| ChannelStore.PostCountsByDuration | avg | 37ms | 0s | -37ms | -100.76
| ChannelStore.AutocompleteInTeam | avg | 18ms | 0s | -18ms | -100.65
| ChannelStore.AnalyticsTypeCount | avg | 67ms | 0s | -67ms | -100.30
| ThreadStore.GetTopThreadsForTeamSince | avg | 171ms | 0s | -171ms | -100.08
| ReactionStore.GetTopForUserSince | avg | 1.22s | 0s | -1.22s | -100.04
| ChannelStore.GetTopChannelsForTeamSince | avg | 2.29s | 0s | -2.29s | -100.01
| ReactionStore.GetTopForTeamSince | avg | 19.068s | 0s | -19.068s | -100.00
| ChannelStore.GetTopInactiveChannelsForUserSince | avg | 1.298s | 0s | -1.298s | -99.99
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 86ms | 0s | -86ms | -99.90
| ComplianceStore.MessageExport | avg | 5ms | 0s | -5ms | -99.72
| UserStore.AnalyticsActiveCount | avg | 44ms | 0s | -44ms | -99.53
| PostStore.GetTopDMsForUserSince | avg | 13ms | 0s | -13ms | -98.43
| ThreadStore.GetTopThreadsForUserSince | avg | 4ms | 0s | -4ms | -93.58
| DraftStore.Save | avg | 4ms | 0s | -4ms | -92.22
| ChannelStore.GetFileCount | avg | 15ms | 2ms | -13ms | -86.46
| DraftStore.Update | avg | 2ms | 0s | -2ms | -81.66
| SessionStore.AnalyticsSessionCount | avg | 2ms | 0s | -2ms | -80.11
| ThreadStore.GetTotalUnreadMentions | avg | 3ms | 1ms | -2ms | -76.88
| PluginStore.List | avg | 3ms | 1ms | -2ms | -59.23
| ChannelStore.UpdateSidebarCategories | avg | 30ms | 17ms | -13ms | -44.03
| ChannelStore.Autocomplete | avg | 56ms | 48ms | -8ms | -14.39
| ChannelStore.AutocompleteInTeamForSearch | avg | 247ms | 220ms | -27ms | -10.95
| UserStore.GetAllProfilesInChannel | avg | 187ms | 177ms | -10ms | -5.35
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.GetTopThreadsForUserSince | p99 | 20ms | 0s | -20ms | -102.04
| DraftStore.Get | p99 | 9ms | 0s | -9ms | -101.12
| ComplianceStore.MessageExport | p99 | 10ms | 0s | -10ms | -101.01
| ChannelStore.AutocompleteInTeam | p99 | 50ms | 0s | -50ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| WebhookStore.GetIncomingByTeamByUser | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Save | p99 | 10ms | 0s | -10ms | -101.01
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.GetDraftsForUser | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Update | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| WebhookStore.AnalyticsOutgoingCount | p99 | 5ms | 0s | -5ms | -101.01
| SessionStore.AnalyticsSessionCount | p99 | 5ms | 0s | -5ms | -101.01
| CommandStore.AnalyticsCommandCount | p99 | 5ms | 0s | -5ms | -100.78
| WebhookStore.AnalyticsIncomingCount | p99 | 5ms | 0s | -5ms | -100.78
| FileInfoStore.Search | p99 | 10ms | 0s | -10ms | -100.41
| ChannelStore.PostCountsByDuration | p99 | 241ms | 0s | -241ms | -100.15
| ThreadStore.GetTopThreadsForTeamSince | p99 | 2.091s | 0s | -2.091s | -100.01
| ChannelStore.GetTopChannelsForTeamSince | p99 | 10s | 0s | -10s | -100.00
| ReactionStore.GetTopForUserSince | p99 | 2.485s | 0s | -2.485s | -100.00
| ReactionStore.GetTopForTeamSince | p99 | 10s | 0s | -10s | -100.00
| ChannelStore.GetTopChannelsForUserSince | p99 | 32ms | 0s | -32ms | -100.00
| ChannelStore.GetTopInactiveChannelsForUserSince | p99 | 8.879s | 0s | -8.879s | -99.99
| UserStore.AnalyticsActiveCount | p99 | 97ms | 0s | -97ms | -99.99
| PostStore.GetTopDMsForUserSince | p99 | 46ms | 0s | -46ms | -99.96
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 245ms | 0s | -245ms | -99.85
| ChannelStore.AnalyticsTypeCount | p99 | 99ms | 0s | -99ms | -99.54
| ChannelStore.GetFileCount | p99 | 42ms | 9ms | -33ms | -79.32
| ChannelStore.UpdateSidebarCategories | p99 | 234ms | 49ms | -185ms | -79.18
| JobStore.GetCountByStatusAndType | p99 | 22ms | 5ms | -17ms | -76.92
| ChannelStore.GetSidebarCategory | p99 | 17ms | 5ms | -12ms | -69.17
| JobStore.GetNewestJobByStatusesAndType | p99 | 14ms | 5ms | -9ms | -64.75
| PostStore.GetEtag | p99 | 26ms | 10ms | -16ms | -61.55
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 5ms | -5ms | -51.55
| ChannelStore.GetChannelsWithCursor | p99 | 18ms | 9ms | -9ms | -50.62
| ChannelStore.GetMembersForUserWithCursor | p99 | 22ms | 11ms | -11ms | -49.36
| ChannelStore.GetMembersInfoByChannelIds | p99 | 18ms | 10ms | -8ms | -44.46
| PreferenceStore.DeleteCategoryAndName | p99 | 40ms | 24ms | -16ms | -40.50
| StatusStore.UpdateLastActivityAt | p99 | 15ms | 10ms | -5ms | -34.22
| UserStore.GetUnreadCount | p99 | 363ms | 245ms | -118ms | -32.47
| SessionStore.Remove | p99 | 16ms | 11ms | -5ms | -31.03
| TeamStore.Get | p99 | 7ms | 5ms | -2ms | -30.69
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 34ms | 25ms | -9ms | -26.22
| ChannelStore.GetMember | p99 | 8ms | 6ms | -2ms | -25.94
| ThreadStore.GetTotalUnreadMentions | p99 | 20ms | 15ms | -5ms | -25.01
| ChannelStore.CreateInitialSidebarCategories | p99 | 79ms | 60ms | -19ms | -24.15
| PostAcknowledgementStore.GetForPosts | p99 | 17ms | 13ms | -4ms | -24.03
| ChannelStore.GetChannels | p99 | 14ms | 11ms | -3ms | -21.95
| JobStore.Save | p99 | 23ms | 18ms | -5ms | -21.83
| ChannelStore.CreateDirectChannel | p99 | 44ms | 35ms | -9ms | -20.57
| JobStore.GetAllByStatus | p99 | 10ms | 8ms | -2ms | -20.41
| SystemStore.GetByName | p99 | 15ms | 12ms | -3ms | -20.24
| PluginStore.List | p99 | 10ms | 8ms | -2ms | -20.22
| PostPriorityStore.GetForPosts | p99 | 15ms | 12ms | -3ms | -19.83
| ThreadStore.GetTeamsUnreadForUser | p99 | 21ms | 17ms | -4ms | -19.18
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 16ms | 13ms | -3ms | -18.90
| UserStore.Update | p99 | 24ms | 20ms | -4ms | -17.01
| ChannelStore.GetMembersForUser | p99 | 12ms | 10ms | -2ms | -16.90
| TeamStore.GetTeamsByUserId | p99 | 19ms | 16ms | -3ms | -16.09
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.921s | 2.454s | -467ms | -15.99
| ChannelStore.IncrementMentionCount | p99 | 13ms | 11ms | -2ms | -15.74
| ClusterDiscoveryStore.SetLastPingAt | p99 | 19ms | 16ms | -3ms | -15.73
| ThreadStore.GetThreadsForUser | p99 | 13ms | 11ms | -2ms | -15.39
| UserStore.GetForLogin | p99 | 21ms | 18ms | -3ms | -14.43
| PostStore.GetPosts | p99 | 81ms | 73ms | -8ms | -9.85
| PostAcknowledgementStore.Save | p99 | 21ms | 19ms | -2ms | -9.69
| PreferenceStore.GetAll | p99 | 22ms | 20ms | -2ms | -9.22
| ProductNoticesStore.View | p99 | 97ms | 91ms | -6ms | -6.16
| PostStore.Save | p99 | 35ms | 33ms | -2ms | -5.76
| TeamStore.SaveMember | p99 | 106ms | 100ms | -6ms | -5.67
| SessionStore.Get | p99 | 37ms | 35ms | -2ms | -5.42
| ChannelStore.GetMemberCount | p99 | 188ms | 180ms | -8ms | -4.25
| ChannelStore.CreateSidebarCategory | p99 | 47ms | 45ms | -2ms | -4.23
| UserStore.Save | p99 | 179ms | 173ms | -6ms | -3.35
| ChannelStore.Autocomplete | p99 | 240ms | 233ms | -7ms | -2.91
| UserStore.GetAllProfilesInChannel | p99 | 954ms | 932ms | -22ms | -2.31
| UserStore.Count | p99 | 99ms | 97ms | -2ms | -2.03
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 98ms | 115ms | 17ms | 17.43
| getPostsForChannel | avg | 34ms | 37ms | 3ms | 8.74
| createPost | avg | 309ms | 335ms | 26ms | 8.40
| searchUsers | avg | 32ms | 34ms | 2ms | 6.22
| updateUserCustomStatus | avg | 137ms | 142ms | 5ms | 3.66
| autocompleteUsers | avg | 76ms | 78ms | 2ms | 2.64
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 10ms | 19ms | 9ms | 90.65
| unfollowThreadByUser | p99 | 12ms | 21ms | 9ms | 76.76
| createChannel | p99 | 50ms | 78ms | 28ms | 56.18
| searchGroupChannels | p99 | 10ms | 15ms | 5ms | 49.72
| searchPostsInTeam | p99 | 1.191s | 1.376s | 185ms | 15.53
| updateReadStateThreadByUser | p99 | 43ms | 47ms | 4ms | 9.28
| autocompleteUsers | p99 | 248ms | 258ms | 10ms | 4.04
| createCategoryForTeamForUser | p99 | 50ms | 52ms | 2ms | 4.03
| getPostsForChannel | p99 | 411ms | 427ms | 16ms | 3.89
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 2ms | 0s | -2ms | -126.98
| getIncomingHooks | avg | 4ms | 0s | -4ms | -106.33
| getTopChannelsForUserSince | avg | 9ms | 0s | -9ms | -103.00
| getTotalUsersStats | avg | 19ms | 0s | -19ms | -102.66
| handleCheckCWSConnection | avg | 49ms | 0s | -49ms | -100.80
| getAnalytics | avg | 64ms | 0s | -64ms | -100.54
| upsertDraft | avg | 6ms | 0s | -6ms | -100.26
| patchUser | avg | 73ms | 0s | -73ms | -100.08
| updateConfig | avg | 201ms | 0s | -201ms | -100.04
| getTopChannelsForTeamSince | avg | 2.385s | 0s | -2.385s | -100.00
| getTopReactionsForTeamSince | avg | 19.069s | 0s | -19.069s | -100.00
| getTopInactiveChannelsForUserSince | avg | 1.299s | 0s | -1.299s | -99.99
| getTopReactionsForUserSince | avg | 1.221s | 0s | -1.221s | -99.97
| autocompleteChannelsForTeam | avg | 18ms | 0s | -18ms | -99.78
| updateCategoryForTeamForUser | avg | 74ms | 0s | -74ms | -99.59
| searchFilesInTeam | avg | 8ms | 0s | -8ms | -99.28
| getTopThreadsForTeamSince | avg | 182ms | 2ms | -180ms | -98.64
| getTopDMsForUserSince | avg | 13ms | 0s | -13ms | -97.98
| getClientConfig | avg | 36ms | 4ms | -32ms | -88.77
| getTopThreadsForUserSince | avg | 7ms | 1ms | -6ms | -83.98
| getPostsForChannelAroundLastUnread | avg | 36ms | 21ms | -15ms | -41.29
| createUser | avg | 125ms | 89ms | -36ms | -28.85
| updateCategoriesForTeamForUser | avg | 35ms | 25ms | -10ms | -28.62
| searchAllChannels | avg | 66ms | 48ms | -18ms | -27.32
| patchPost | avg | 32ms | 26ms | -6ms | -18.98
| getProfileImage | avg | 128ms | 106ms | -22ms | -17.24
| getFilteredUsersStats | avg | 29ms | 25ms | -4ms | -13.74
| gqlWebCurrentUserInfo | avg | 41ms | 36ms | -5ms | -12.22
| autocompleteChannelsForTeamForSearch | avg | 247ms | 220ms | -27ms | -10.94
| removeUserCustomStatus | avg | 136ms | 131ms | -5ms | -3.69
| addTeamMember | avg | 897ms | 865ms | -32ms | -3.57
| createGroupChannel | avg | 332ms | 321ms | -11ms | -3.31
| uploadFileStream | avg | 450ms | 437ms | -13ms | -2.89
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeam | p99 | 50ms | 0s | -50ms | -101.01
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| getIncomingHooks | p99 | 5ms | 0s | -5ms | -101.01
| getRolesByNames | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| getJobsByType | p99 | 5ms | 0s | -5ms | -101.01
| getTotalUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| patchUser | p99 | 100ms | 0s | -100ms | -100.50
| searchFilesInTeam | p99 | 10ms | 0s | -10ms | -100.41
| updateCategoryForTeamForUser | p99 | 246ms | 0s | -246ms | -100.20
| getTopReactionsForUserSince | p99 | 2.485s | 0s | -2.485s | -100.00
| getTopChannelsForTeamSince | p99 | 10s | 0s | -10s | -100.00
| getTopReactionsForTeamSince | p99 | 10s | 0s | -10s | -100.00
| getTopChannelsForUserSince | p99 | 41ms | 0s | -41ms | -100.00
| getTopInactiveChannelsForUserSince | p99 | 8.879s | 0s | -8.879s | -99.99
| handleCheckCWSConnection | p99 | 98ms | 0s | -98ms | -99.97
| getTopDMsForUserSince | p99 | 46ms | 0s | -46ms | -99.96
| updateConfig | p99 | 249ms | 0s | -249ms | -99.92
| getAnalytics | p99 | 243ms | 0s | -243ms | -99.81
| upsertDraft | p99 | 24ms | 0s | -24ms | -98.97
| getTopThreadsForTeamSince | p99 | 2.091s | 40ms | -2.051s | -98.10
| getPrevTrialLicense | p99 | 9ms | 0s | -9ms | -97.84
| deleteDraft | p99 | 9ms | 0s | -9ms | -97.83
| getPostsForChannelAroundLastUnread | p99 | 848ms | 183ms | -665ms | -78.41
| getTopThreadsForUserSince | p99 | 24ms | 5ms | -19ms | -78.11
| getClientConfig | p99 | 140ms | 34ms | -106ms | -75.75
| updateCategoriesForTeamForUser | p99 | 222ms | 70ms | -152ms | -68.39
| getChannelMembers | p99 | 22ms | 10ms | -12ms | -54.75
| updateUserCustomStatus | p99 | 417ms | 267ms | -150ms | -36.01
| gqlWebChannelsAndChannelMembers | p99 | 78ms | 50ms | -28ms | -35.73
| getChannel | p99 | 17ms | 11ms | -6ms | -35.60
| getCategoriesForTeamForUser | p99 | 35ms | 25ms | -10ms | -28.18
| getUser | p99 | 31ms | 23ms | -8ms | -25.78
| getUsersByNames | p99 | 8ms | 6ms | -2ms | -25.76
| acknowledgePost | p99 | 44ms | 33ms | -11ms | -24.73
| gqlWebCurrentUserInfo | p99 | 97ms | 73ms | -24ms | -24.64
| deletePost | p99 | 47ms | 36ms | -11ms | -23.66
| getChannelUnread | p99 | 9ms | 7ms | -2ms | -23.17
| autocompleteChannelsForTeamForSearch | p99 | 2.921s | 2.454s | -467ms | -15.99
| getThreadsForUser | p99 | 14ms | 12ms | -2ms | -14.22
| createUser | p99 | 277ms | 242ms | -35ms | -12.63
| getFilePreview | p99 | 146ms | 128ms | -18ms | -12.29
| viewChannel | p99 | 41ms | 36ms | -5ms | -12.25
| getChannelsForTeamForUser | p99 | 19ms | 17ms | -2ms | -10.80
| getTeamsForUser | p99 | 19ms | 17ms | -2ms | -10.53
| getUsers | p99 | 23ms | 21ms | -2ms | -8.74
| followThreadByUser | p99 | 26ms | 24ms | -2ms | -7.65
| uploadFileStream | p99 | 1.062s | 986ms | -76ms | -7.15
| removeUserCustomStatus | p99 | 419ms | 393ms | -26ms | -6.20
| saveReaction | p99 | 42ms | 40ms | -2ms | -4.79
| searchAllChannels | p99 | 243ms | 234ms | -9ms | -3.71
| logout | p99 | 98ms | 95ms | -3ms | -3.07
| getChannelStats | p99 | 202ms | 197ms | -5ms | -2.47
| getProfileImage | p99 | 464ms | 455ms | -9ms | -1.94
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.582
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 86ms| 0s | -86ms | -99.897
| |  P99| 245ms| 0s | -245ms | -99.854
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.555
| ChannelStore.AnalyticsTypeCount |  Avg| 67ms| 0s | -67ms | -100.297
| |  P99| 99ms| 0s | -99ms | -99.538
| ChannelStore.Autocomplete |  Avg| 56ms| 48ms | -8ms | -14.389
| |  P99| 240ms| 233ms | -7ms | -2.912
| ChannelStore.AutocompleteInTeam |  Avg| 18ms| 0s | -18ms | -100.654
| |  P99| 50ms| 0s | -50ms | -101.010
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 247ms| 220ms | -27ms | -10.947
| |  P99| 2.921s| 2.454s | -467ms | -15.986
| ChannelStore.CreateDirectChannel |  Avg| 12ms| 11ms | -1ms | -8.453
| |  P99| 44ms| 35ms | -9ms | -20.575
| ChannelStore.CreateInitialSidebarCategories |  Avg| 13ms| 12ms | -1ms | -7.648
| |  P99| 79ms| 60ms | -19ms | -24.150
| ChannelStore.CreateSidebarCategory |  Avg| 13ms| 12ms | -1ms | -7.749
| |  P99| 47ms| 45ms | -2ms | -4.231
| ChannelStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 71ms| 72ms | 1ms | 1.408
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 0s | -1ms | -104.692
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.945
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithCursor |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -50.621
| ChannelStore.GetFileCount |  Avg| 15ms| 2ms | -13ms | -86.460
| |  P99| 42ms| 9ms | -33ms | -79.321
| ChannelStore.GetGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.935
| ChannelStore.GetMemberCount |  Avg| 10ms| 9ms | -1ms | -10.378
| |  P99| 188ms| 180ms | -8ms | -4.248
| ChannelStore.GetMemberCountsByGroup |  Avg| 1ms| 0s | -1ms | -88.727
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 10ms| 17ms | 7ms | 71.109
| |  P99| 208ms| 233ms | 25ms | 12.041
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.901
| ChannelStore.GetMembersForUserWithCursor |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 11ms | -11ms | -49.356
| ChannelStore.GetMembersForUserWithPagination |  Avg| 11ms| 12ms | 1ms | 8.814
| |  P99| 25ms| 86ms | 61ms | 245.473
| ChannelStore.GetMembersInfoByChannelIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -44.459
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 6ms| 5ms | -1ms | -17.504
| |  P99| 34ms| 25ms | -9ms | -26.224
| ChannelStore.GetSidebarCategory |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -69.165
| ChannelStore.GetTeamChannels |  Avg| 26ms| 25ms | -1ms | -3.790
| |  P99| 50ms| 78ms | 28ms | 56.192
| ChannelStore.GetTopChannelsForTeamSince |  Avg| 2.29s| 0s | -2.29s | -100.006
| |  P99| 10s| 0s | -10s | -100.000
| ChannelStore.GetTopChannelsForUserSince |  Avg| 6ms| 0s | -6ms | -101.202
| |  P99| 32ms| 0s | -32ms | -100.000
| ChannelStore.GetTopInactiveChannelsForUserSince |  Avg| 1.298s| 0s | -1.298s | -99.993
| |  P99| 8.879s| 0s | -8.879s | -99.995
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.736
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannel |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateMemberCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidatePinnedPostCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.PostCountsByDuration |  Avg| 37ms| 0s | -37ms | -100.763
| |  P99| 241ms| 0s | -241ms | -100.151
| ChannelStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.313
| ChannelStore.SaveMember |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 70ms| 69ms | -1ms | -1.429
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 49.720
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.714
| ChannelStore.UpdateSidebarCategories |  Avg| 30ms| 17ms | -13ms | -44.028
| |  P99| 234ms| 49ms | -185ms | -79.183
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 3ms | -1ms | -28.030
| |  P99| 19ms| 16ms | -3ms | -15.726
| CommandStore.AnalyticsCommandCount |  Avg| 1ms| 0s | -1ms | -99.666
| |  P99| 5ms| 0s | -5ms | -100.777
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 5ms| 0s | -5ms | -99.715
| |  P99| 10ms| 0s | -10ms | -101.010
| DraftStore.Get |  Avg| 1ms| 0s | -1ms | -86.548
| |  P99| 9ms| 0s | -9ms | -101.124
| DraftStore.GetDraftsForUser |  Avg| 1ms| 0s | -1ms | -71.237
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Save |  Avg| 4ms| 0s | -4ms | -92.222
| |  P99| 10ms| 0s | -10ms | -101.010
| DraftStore.Update |  Avg| 2ms| 0s | -2ms | -81.662
| |  P99| 5ms| 0s | -5ms | -101.010
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 1ms| 0s | -1ms | -145.686
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 4ms| 5ms | 1ms | 22.282
| |  P99| 11ms| 21ms | 10ms | 91.116
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 19ms | 4ms | 25.946
| FileInfoStore.Search |  Avg| 7ms| 0s | -7ms | -101.181
| |  P99| 10ms| 0s | -10ms | -100.409
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.264
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.057
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.937
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.408
| JobStore.GetAllByTypePage |  Avg| 1ms| 0s | -1ms | -110.595
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 1ms | -1ms | -41.013
| |  P99| 22ms| 5ms | -17ms | -76.923
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 1ms | -1ms | -53.375
| |  P99| 14ms| 5ms | -9ms | -64.748
| JobStore.Save |  Avg| 4ms| 3ms | -1ms | -26.393
| |  P99| 23ms| 18ms | -5ms | -21.834
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 82.687
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -142.215
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 1ms| 3ms | 2ms | 179.064
| |  P99| 5ms| 10ms | 5ms | 100.044
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.811
| PluginStore.List |  Avg| 3ms| 1ms | -2ms | -59.230
| |  P99| 10ms| 8ms | -2ms | -20.224
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 13ms | -4ms | -24.026
| PostAcknowledgementStore.Save |  Avg| 6ms| 5ms | -1ms | -18.178
| |  P99| 21ms| 19ms | -2ms | -9.688
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 1ms | -1ms | -65.261
| |  P99| 15ms| 12ms | -3ms | -19.834
| PostStore.AnalyticsPostCount |  Avg| 2.053s| 4.801s | 2.748s | 133.872
| |  P99| 4.95s| 4.975s | 25ms | 0.505
| PostStore.Delete |  Avg| 8ms| 9ms | 1ms | 12.283
| |  P99| 32ms| 36ms | 4ms | 12.403
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 26ms| 10ms | -16ms | -61.551
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.801
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 2ms | 1ms | 93.768
| |  P99| 5ms| 43ms | 38ms | 767.677
| PostStore.GetPostReminders |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 121.563
| PostStore.GetPosts |  Avg| 7ms| 6ms | -1ms | -13.489
| |  P99| 81ms| 73ms | -8ms | -9.853
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.439
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.022
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 10ms| 9ms | -1ms | -9.696
| |  P99| 50ms| 54ms | 4ms | 8.051
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetTopDMsForUserSince |  Avg| 13ms| 0s | -13ms | -98.428
| |  P99| 46ms| 0s | -46ms | -99.964
| PostStore.HasAutoResponsePostByUserSince |  Avg| 7ms| 6ms | -1ms | -14.829
| |  P99| 25ms| 32ms | 7ms | 28.051
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 35ms| 33ms | -2ms | -5.762
| PostStore.SearchPostsForUser |  Avg| 90ms| 110ms | 20ms | 22.218
| |  P99| 894ms| 1.376s | 482ms | 53.941
| PostStore.SetPostReminder |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 35ms| 38ms | 3ms | 8.587
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 3ms | -1ms | -28.467
| |  P99| 40ms| 24ms | -16ms | -40.505
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.187
| PreferenceStore.GetAll |  Avg| 3ms| 2ms | -1ms | -39.385
| |  P99| 22ms| 20ms | -2ms | -9.221
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.081
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 18ms| 17ms | -1ms | -5.706
| |  P99| 97ms| 91ms | -6ms | -6.158
| ReactionStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetTopForTeamSince |  Avg| 19.068s| 0s | -19.068s | -99.998
| |  P99| 10s| 0s | -10s | -100.000
| ReactionStore.GetTopForUserSince |  Avg| 1.22s| 0s | -1.22s | -100.040
| |  P99| 2.485s| 0s | -2.485s | -100.000
| ReactionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.331
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -89.518
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.AnalyticsSessionCount |  Avg| 2ms| 0s | -2ms | -80.106
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 35ms | -2ms | -5.422
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 11ms | -5ms | -31.032
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 29ms| 32ms | 3ms | 10.501
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -6.026
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 25ms | 21ms | 576.458
| |  P99| 16ms| 423ms | 407ms | 2489.461
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.546
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -34.217
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -20.237
| TeamStore.AnalyticsTeamCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.687
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.527
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 1ms | -1ms | -62.776
| |  P99| 16ms| 13ms | -3ms | -18.904
| TeamStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.065
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 1ms | -1ms | -63.127
| |  P99| 19ms| 16ms | -3ms | -16.091
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.145
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 63ms| 63ms | 0s | 0.000
| |  P99| 106ms| 100ms | -6ms | -5.675
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 2ms | -1ms | -38.493
| |  P99| 21ms| 17ms | -4ms | -19.178
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 31.250
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 18.385
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.394
| ThreadStore.GetTopThreadsForTeamSince |  Avg| 171ms| 0s | -171ms | -100.083
| |  P99| 2.091s| 0s | -2.091s | -100.014
| ThreadStore.GetTopThreadsForUserSince |  Avg| 4ms| 0s | -4ms | -93.582
| |  P99| 20ms| 0s | -20ms | -102.040
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.660
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 1ms | -2ms | -76.881
| |  P99| 20ms| 15ms | -5ms | -25.005
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.407
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.034
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.744
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 19ms | 9ms | 90.757
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.245
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 68.966
| UserStore.AnalyticsActiveCount |  Avg| 44ms| 0s | -44ms | -99.530
| |  P99| 97ms| 0s | -97ms | -99.994
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 0s | -1ms | -167.566
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 124ms| 124ms | 0s | 0.000
| |  P99| 249ms| 378ms | 129ms | 51.870
| UserStore.Count |  Avg| 30ms| 34ms | 4ms | 13.121
| |  P99| 99ms| 97ms | -2ms | -2.029
| UserStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.523
| UserStore.GetAllProfilesInChannel |  Avg| 187ms| 177ms | -10ms | -5.350
| |  P99| 954ms| 932ms | -22ms | -2.305
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.431
| UserStore.GetMany |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.696
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 10ms| 9ms | -1ms | -9.627
| |  P99| 363ms| 245ms | -118ms | -32.470
| UserStore.GetUnreadCountForChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.026
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 94ms| 94ms | 0s | 0.000
| |  P99| 248ms| 249ms | 1ms | 0.403
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.Save |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 179ms| 173ms | -6ms | -3.346
| UserStore.Search |  Avg| 31ms| 33ms | 2ms | 6.456
| |  P99| 243ms| 243ms | 0s | 0.000
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 20ms | -4ms | -17.015
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.541
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.775
| WebhookStore.AnalyticsIncomingCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -100.777
| WebhookStore.AnalyticsOutgoingCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| WebhookStore.GetIncomingByTeamByUser |  Avg| 4ms| 0s | -4ms | -111.131
| |  P99| 5ms| 0s | -5ms | -101.010
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.654
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| acknowledgePost | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 44ms| 33ms | -11ms | -24.727
| addChannelMember | Avg| 177ms| 176ms | -1ms | -0.566
| | P99| 475ms| 472ms | -3ms | -0.631
| addTeamMember | Avg| 897ms| 865ms | -32ms | -3.566
| | P99| 2.45s| 2.442s | -8ms | -0.327
| autocompleteChannelsForTeam | Avg| 18ms| 0s | -18ms | -99.779
| | P99| 50ms| 0s | -50ms | -101.010
| autocompleteChannelsForTeamForSearch | Avg| 247ms| 220ms | -27ms | -10.944
| | P99| 2.921s| 2.454s | -467ms | -15.986
| autocompleteEmojis | Avg| 1ms| 0s | -1ms | -136.262
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 76ms| 78ms | 2ms | 2.642
| | P99| 248ms| 258ms | 10ms | 4.039
| channelMemberCountsByGroup | Avg| 2ms| 0s | -2ms | -126.980
| | P99| 5ms| 0s | -5ms | -101.010
| createCategoryForTeamForUser | Avg| 15ms| 14ms | -1ms | -6.652
| | P99| 50ms| 52ms | 2ms | 4.035
| createChannel | Avg| 27ms| 26ms | -1ms | -3.771
| | P99| 50ms| 78ms | 28ms | 56.176
| createDirectChannel | Avg| 218ms| 218ms | 0s | 0.000
| | P99| 494ms| 493ms | -1ms | -0.202
| createGroupChannel | Avg| 332ms| 321ms | -11ms | -3.311
| | P99| 880ms| 881ms | 1ms | 0.114
| createPost | Avg| 309ms| 335ms | 26ms | 8.402
| | P99| 991ms| 993ms | 2ms | 0.202
| createUser | Avg| 125ms| 89ms | -36ms | -28.851
| | P99| 277ms| 242ms | -35ms | -12.631
| deleteDraft | Avg| 1ms| 0s | -1ms | -80.831
| | P99| 9ms| 0s | -9ms | -97.826
| deletePost | Avg| 12ms| 13ms | 1ms | 8.232
| | P99| 47ms| 36ms | -11ms | -23.656
| followThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 26ms| 24ms | -2ms | -7.655
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.457
| getAnalytics | Avg| 64ms| 0s | -64ms | -100.538
| | P99| 243ms| 0s | -243ms | -99.808
| getCategoriesForTeamForUser | Avg| 6ms| 5ms | -1ms | -17.123
| | P99| 35ms| 25ms | -10ms | -28.178
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 11ms | -6ms | -35.599
| getChannelMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 12ms| 11ms | -1ms | -8.199
| getChannelMembers | Avg| 4ms| 3ms | -1ms | -28.186
| | P99| 22ms| 10ms | -12ms | -54.753
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 15ms | -1ms | -6.241
| getChannelStats | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 202ms| 197ms | -5ms | -2.473
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 7ms | -2ms | -23.173
| getChannelsForTeamForUser | Avg| 3ms| 2ms | -1ms | -39.572
| | P99| 19ms| 17ms | -2ms | -10.804
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.793
| getClientConfig | Avg| 36ms| 4ms | -32ms | -88.772
| | P99| 140ms| 34ms | -106ms | -75.747
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 1ms| 0s | -1ms | -68.041
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 146ms| 128ms | -18ms | -12.293
| getFileThumbnail | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
| getFilteredUsersStats | Avg| 29ms| 25ms | -4ms | -13.738
| | P99| 98ms| 99ms | 1ms | 1.015
| getGroups | Avg| 2ms| 1ms | -1ms | -56.412
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getIncomingHooks | Avg| 4ms| 0s | -4ms | -106.330
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 1ms| 0s | -1ms | -98.546
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 34ms| 37ms | 3ms | 8.737
| | P99| 411ms| 427ms | 16ms | 3.893
| getPostsForChannelAroundLastUnread | Avg| 36ms| 21ms | -15ms | -41.294
| | P99| 848ms| 183ms | -665ms | -78.407
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.177
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -88.590
| | P99| 9ms| 0s | -9ms | -97.841
| getProductNotices | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 128ms| 106ms | -22ms | -17.241
| | P99| 464ms| 455ms | -9ms | -1.939
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 0s | -1ms | -67.629
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.550
| getTeamsForUser | Avg| 2ms| 1ms | -1ms | -60.805
| | P99| 19ms| 17ms | -2ms | -10.530
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.294
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 12ms | -2ms | -14.221
| getTopChannelsForTeamSince | Avg| 2.385s| 0s | -2.385s | -100.002
| | P99| 10s| 0s | -10s | -100.000
| getTopChannelsForUserSince | Avg| 9ms| 0s | -9ms | -102.998
| | P99| 41ms| 0s | -41ms | -100.000
| getTopDMsForUserSince | Avg| 13ms| 0s | -13ms | -97.980
| | P99| 46ms| 0s | -46ms | -99.964
| getTopInactiveChannelsForUserSince | Avg| 1.299s| 0s | -1.299s | -99.991
| | P99| 8.879s| 0s | -8.879s | -99.995
| getTopReactionsForTeamSince | Avg| 19.069s| 0s | -19.069s | -99.999
| | P99| 10s| 0s | -10s | -100.000
| getTopReactionsForUserSince | Avg| 1.221s| 0s | -1.221s | -99.970
| | P99| 2.485s| 0s | -2.485s | -100.000
| getTopThreadsForTeamSince | Avg| 182ms| 2ms | -180ms | -98.636
| | P99| 2.091s| 40ms | -2.051s | -98.101
| getTopThreadsForUserSince | Avg| 7ms| 1ms | -6ms | -83.977
| | P99| 24ms| 5ms | -19ms | -78.109
| getTotalUsersStats | Avg| 19ms| 0s | -19ms | -102.664
| | P99| 25ms| 0s | -25ms | -100.604
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 31ms| 23ms | -8ms | -25.780
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 23ms| 21ms | -2ms | -8.740
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 6ms | -2ms | -25.757
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| gqlWebChannelsAndChannelMembers | Avg| 23ms| 22ms | -1ms | -4.362
| | P99| 78ms| 50ms | -28ms | -35.727
| gqlWebCurrentUserInfo | Avg| 41ms| 36ms | -5ms | -12.221
| | P99| 97ms| 73ms | -24ms | -24.640
| handleCheckCWSConnection | Avg| 49ms| 0s | -49ms | -100.802
| | P99| 98ms| 0s | -98ms | -99.973
| login | Avg| 97ms| 97ms | 0s | 0.000
| | P99| 458ms| 456ms | -2ms | -0.437
| logout | Avg| 36ms| 35ms | -1ms | -2.764
| | P99| 98ms| 95ms | -3ms | -3.068
| patchPost | Avg| 32ms| 26ms | -6ms | -18.975
| | P99| 50ms| 50ms | 0s | 0.000
| patchUser | Avg| 73ms| 0s | -73ms | -100.080
| | P99| 100ms| 0s | -100ms | -100.503
| removeUserCustomStatus | Avg| 136ms| 131ms | -5ms | -3.688
| | P99| 419ms| 393ms | -26ms | -6.202
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 11ms | 1ms | 9.530
| | P99| 42ms| 40ms | -2ms | -4.785
| searchAllChannels | Avg| 66ms| 48ms | -18ms | -27.321
| | P99| 243ms| 234ms | -9ms | -3.707
| searchFilesInTeam | Avg| 8ms| 0s | -8ms | -99.283
| | P99| 10ms| 0s | -10ms | -100.409
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 15ms | 5ms | 49.720
| searchPostsInTeam | Avg| 98ms| 115ms | 17ms | 17.435
| | P99| 1.191s| 1.376s | 185ms | 15.530
| searchUsers | Avg| 32ms| 34ms | 2ms | 6.219
| | P99| 243ms| 244ms | 1ms | 0.411
| setPostReminder | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 6ms| 7ms | 1ms | 16.711
| | P99| 12ms| 21ms | 9ms | 76.758
| updateCategoriesForTeamForUser | Avg| 35ms| 25ms | -10ms | -28.621
| | P99| 222ms| 70ms | -152ms | -68.391
| updateCategoryForTeamForUser | Avg| 74ms| 0s | -74ms | -99.594
| | P99| 246ms| 0s | -246ms | -100.195
| updateConfig | Avg| 201ms| 0s | -201ms | -100.035
| | P99| 249ms| 0s | -249ms | -99.918
| updatePreferences | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 19ms | 9ms | 90.648
| updateReadStateThreadByUser | Avg| 15ms| 16ms | 1ms | 6.453
| | P99| 43ms| 47ms | 4ms | 9.283
| updateUserCustomStatus | Avg| 137ms| 142ms | 5ms | 3.657
| | P99| 417ms| 267ms | -150ms | -36.011
| uploadFileStream | Avg| 450ms| 437ms | -13ms | -2.888
| | P99| 1.062s| 986ms | -76ms | -7.153
| upsertDraft | Avg| 6ms| 0s | -6ms | -100.263
| | P99| 24ms| 0s | -24ms | -98.969
| viewChannel | Avg| 11ms| 10ms | -1ms | -9.347
| | P99| 41ms| 36ms | -5ms | -12.245

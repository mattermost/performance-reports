### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 3ms | 3ms | 1053787.73
| UserStore.GetProfilesInChannel | avg | 11ms | 122ms | 111ms | 1055.26
| ChannelStore.AutocompleteInTeamForSearch | avg | 15ms | 28ms | 13ms | 88.23
| PostStore.SearchPostsForUser | avg | 23ms | 26ms | 3ms | 13.02
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfilesInChannel | p99 | 25ms | 249ms | 224ms | 901.26
| RoleStore.GetByNames | p99 | 5ms | 23ms | 18ms | 363.64
| LinkMetadataStore.Save | p99 | 5ms | 21ms | 16ms | 323.23
| PostStore.GetPostsAfter | p99 | 5ms | 20ms | 15ms | 303.03
| ChannelStore.AutocompleteInTeamForSearch | p99 | 49ms | 131ms | 82ms | 166.38
| TeamStore.GetMember | p99 | 5ms | 12ms | 7ms | 140.38
| UserStore.GetMany | p99 | 24ms | 46ms | 22ms | 93.02
| ChannelStore.GetSidebarCategory | p99 | 24ms | 46ms | 22ms | 90.91
| JobStore.UpdateStatus | p99 | 5ms | 8ms | 3ms | 60.61
| UserStore.GetUnreadCount | p99 | 11ms | 17ms | 6ms | 53.09
| ChannelStore.Save | p99 | 27ms | 40ms | 13ms | 47.71
| PostAcknowledgementStore.GetForPost | p99 | 9ms | 13ms | 4ms | 44.25
| FileInfoStore.GetByIds | p99 | 7ms | 9ms | 2ms | 27.78
| FileInfoStore.Save | p99 | 16ms | 20ms | 4ms | 24.64
| WebhookStore.GetOutgoingByTeam | p99 | 30ms | 34ms | 4ms | 13.24
| ChannelStore.GetByName | p99 | 36ms | 39ms | 3ms | 8.39
| UserStore.Search | p99 | 65ms | 68ms | 3ms | 4.63
| PostStore.SearchPostsForUser | p99 | 595ms | 611ms | 16ms | 2.69
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 10ms | 0s | -10ms | -104.18
| ChannelStore.CreateSidebarCategory | avg | 15ms | 0s | -15ms | -102.12
| TeamStore.GetActiveMemberCount | avg | 37ms | 0s | -37ms | -101.08
| TeamStore.GetTotalMemberCount | avg | 36ms | 0s | -36ms | -99.52
| ChannelStore.GetTeamChannels | avg | 10ms | 0s | -10ms | -97.41
| UserStore.GetProfilesNotInChannel | avg | 4ms | 0s | -4ms | -95.43
| JobStore.Get | avg | 2ms | 0s | -2ms | -89.85
| StatusStore.SaveOrUpdate | avg | 24ms | 3ms | -21ms | -86.25
| ChannelStore.GetAllChannelMembersForUser | avg | 5ms | 3ms | -2ms | -44.07
| BotStore.Get | avg | 5ms | 3ms | -2ms | -41.89
| ChannelStore.UpdateSidebarCategories | avg | 28ms | 24ms | -4ms | -14.41
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 16ms | 14ms | -2ms | -12.55
| UserStore.GetAllProfilesInChannel | avg | 170ms | 156ms | -14ms | -8.24
| PostStore.AnalyticsPostCount | avg | 484ms | 448ms | -36ms | -7.44
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Get | p99 | 8ms | 0s | -8ms | -104.58
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 32ms | 0s | -32ms | -101.59
| ChannelStore.GetTeamChannels | p99 | 25ms | 0s | -25ms | -101.21
| UserStore.GetProfilesNotInChannel | p99 | 5ms | 0s | -5ms | -100.97
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| TeamStore.GetActiveMemberCount | p99 | 50ms | 0s | -50ms | -100.50
| TeamStore.GetTotalMemberCount | p99 | 50ms | 0s | -50ms | -100.50
| StatusStore.SaveOrUpdate | p99 | 428ms | 10ms | -418ms | -97.73
| UserStore.Update | p99 | 67ms | 10ms | -57ms | -84.45
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 24ms | 5ms | -19ms | -80.85
| ChannelStore.GetChannelUnread | p99 | 41ms | 8ms | -33ms | -80.49
| JobStore.GetNewestJobByStatusesAndType | p99 | 51ms | 10ms | -41ms | -80.39
| BotStore.Get | p99 | 45ms | 10ms | -35ms | -76.92
| JobStore.GetCountByStatusAndType | p99 | 18ms | 5ms | -13ms | -73.65
| UserStore.GetByUsername | p99 | 24ms | 10ms | -14ms | -59.38
| StatusStore.UpdateExpiredDNDStatuses | p99 | 22ms | 9ms | -13ms | -58.30
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| PreferenceStore.DeleteCategoryAndName | p99 | 10ms | 5ms | -5ms | -52.63
| SessionStore.Remove | p99 | 10ms | 5ms | -5ms | -51.95
| SessionStore.GetSessionsExpired | p99 | 10ms | 5ms | -5ms | -51.81
| ClusterDiscoveryStore.SetLastPingAt | p99 | 16ms | 8ms | -8ms | -49.69
| DraftStore.GetDraftsForUser | p99 | 17ms | 9ms | -8ms | -45.75
| PostStore.Update | p99 | 42ms | 24ms | -18ms | -43.11
| FileInfoStore.SetContent | p99 | 30ms | 17ms | -13ms | -42.98
| JobStore.Save | p99 | 8ms | 5ms | -3ms | -39.22
| ThreadStore.GetThreadFollowers | p99 | 14ms | 9ms | -5ms | -36.87
| PreferenceStore.Get | p99 | 14ms | 10ms | -4ms | -28.57
| JobStore.GetAllByStatus | p99 | 25ms | 18ms | -7ms | -28.26
| PostStore.GetPostIdAfterTime | p99 | 14ms | 10ms | -4ms | -27.64
| ProductNoticesStore.View | p99 | 128ms | 93ms | -35ms | -27.34
| ChannelStore.Get | p99 | 18ms | 13ms | -5ms | -27.26
| StatusStore.Get | p99 | 18ms | 13ms | -5ms | -27.04
| SystemStore.GetByName | p99 | 15ms | 11ms | -4ms | -26.14
| ThreadStore.UpdateMembership | p99 | 8ms | 6ms | -2ms | -25.90
| ChannelStore.CreateInitialSidebarCategories | p99 | 70ms | 52ms | -18ms | -25.85
| ChannelStore.IncrementMentionCount | p99 | 16ms | 12ms | -4ms | -25.46
| ChannelStore.GetFileCount | p99 | 12ms | 9ms | -3ms | -24.63
| FileInfoStore.AttachToPost | p99 | 16ms | 12ms | -4ms | -24.45
| PostStore.GetPostIdBeforeTime | p99 | 8ms | 6ms | -2ms | -24.33
| DraftStore.Upsert | p99 | 14ms | 11ms | -3ms | -21.81
| SessionStore.GetLRUSessions | p99 | 19ms | 15ms | -4ms | -20.83
| EmojiStore.GetByName | p99 | 10ms | 8ms | -2ms | -20.59
| PostStore.Save | p99 | 34ms | 27ms | -7ms | -20.46
| ThreadStore.GetTotalUnreadMentions | p99 | 20ms | 16ms | -4ms | -20.19
| SessionStore.Get | p99 | 37ms | 30ms | -7ms | -18.74
| UserStore.GetProfilesByUsernames | p99 | 11ms | 9ms | -2ms | -18.71
| PostStore.Get | p99 | 22ms | 18ms | -4ms | -18.57
| UserStore.GetProfileByIds | p99 | 16ms | 13ms | -3ms | -18.57
| ChannelStore.GetChannels | p99 | 16ms | 13ms | -3ms | -18.34
| GroupStore.GetGroups | p99 | 16ms | 13ms | -3ms | -18.20
| ChannelStore.UpdateLastViewedAt | p99 | 11ms | 9ms | -2ms | -17.59
| PostStore.GetPostsBefore | p99 | 17ms | 14ms | -3ms | -17.40
| ChannelStore.GetMemberForPost | p99 | 17ms | 14ms | -3ms | -17.31
| ChannelStore.CreateDirectChannel | p99 | 94ms | 79ms | -15ms | -15.87
| ThreadStore.GetTotalUnreadThreads | p99 | 19ms | 16ms | -3ms | -15.48
| ThreadStore.GetTotalThreads | p99 | 19ms | 16ms | -3ms | -15.41
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 20ms | 17ms | -3ms | -15.33
| TeamStore.SaveMember | p99 | 73ms | 62ms | -11ms | -15.16
| TeamStore.GetAllPage | p99 | 21ms | 18ms | -3ms | -14.46
| ThreadStore.MaintainMembership | p99 | 14ms | 12ms | -2ms | -14.00
| JobStore.UpdateStatusOptimistically | p99 | 21ms | 18ms | -3ms | -13.97
| PreferenceStore.Save | p99 | 46ms | 40ms | -6ms | -13.18
| ChannelStore.SearchGroupChannels | p99 | 23ms | 20ms | -3ms | -13.05
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 16ms | 14ms | -2ms | -12.18
| ThreadStore.GetThreadsForUser | p99 | 18ms | 16ms | -2ms | -11.36
| ChannelStore.GetMemberLastViewedAt | p99 | 19ms | 17ms | -2ms | -10.60
| PostStore.GetEtag | p99 | 19ms | 17ms | -2ms | -10.26
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 20ms | 18ms | -2ms | -10.04
| UserStore.GetAllProfiles | p99 | 20ms | 18ms | -2ms | -10.03
| TeamStore.GetTeamsForUser | p99 | 21ms | 19ms | -2ms | -9.74
| TeamStore.GetTeamsByUserId | p99 | 21ms | 19ms | -2ms | -9.42
| UserStore.GetForLogin | p99 | 21ms | 19ms | -2ms | -9.38
| GroupStore.GetByName | p99 | 21ms | 19ms | -2ms | -9.32
| ChannelStore.GetMembersForUserWithPagination | p99 | 22ms | 20ms | -2ms | -9.12
| PreferenceStore.GetAll | p99 | 23ms | 21ms | -2ms | -8.79
| ChannelStore.SaveMember | p99 | 95ms | 87ms | -8ms | -8.42
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 50ms | 47ms | -3ms | -6.02
| UserStore.GetAllProfilesInChannel | p99 | 486ms | 477ms | -9ms | -1.85
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 15ms | 28ms | 13ms | 87.89
| viewChannel | avg | 8ms | 10ms | 2ms | 24.55
| setPostReminder | avg | 14ms | 16ms | 2ms | 13.91
| searchPostsInTeam | avg | 31ms | 33ms | 2ms | 6.52
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 49ms | 131ms | 82ms | 166.31
| updateCategoriesForTeamForUser | p99 | 96ms | 224ms | 128ms | 133.32
| getPublicChannelsForTeam | p99 | 25ms | 48ms | 23ms | 92.56
| unfollowThreadByUser | p99 | 25ms | 43ms | 18ms | 73.10
| viewChannel | p99 | 36ms | 39ms | 3ms | 8.36
| searchUsers | p99 | 68ms | 72ms | 4ms | 5.89
| searchPostsInTeam | p99 | 595ms | 611ms | 16ms | 2.69
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannel | avg | 186ms | 0s | -186ms | -100.20
| createCategoryForTeamForUser | avg | 17ms | 0s | -17ms | -100.10
| getTeamStats | avg | 39ms | 0s | -39ms | -99.18
| updateReadStateAllThreadsByUser | avg | 3ms | 1ms | -2ms | -77.62
| patchPost | avg | 66ms | 22ms | -44ms | -66.97
| getChannelUnread | avg | 4ms | 2ms | -2ms | -48.61
| getChannel | avg | 9ms | 5ms | -4ms | -44.42
| logout | avg | 40ms | 23ms | -17ms | -42.48
| login | avg | 80ms | 57ms | -23ms | -28.72
| createPost | avg | 244ms | 175ms | -69ms | -28.25
| removeUserCustomStatus | avg | 155ms | 112ms | -43ms | -27.79
| createGroupChannel | avg | 353ms | 270ms | -83ms | -23.52
| addChannelMember | avg | 216ms | 169ms | -47ms | -21.75
| createDirectChannel | avg | 231ms | 183ms | -48ms | -20.81
| createUser | avg | 136ms | 121ms | -15ms | -11.04
| addTeamMember | avg | 631ms | 588ms | -43ms | -6.81
| getProfileImage | avg | 92ms | 86ms | -6ms | -6.51
| updateCategoriesForTeamForUser | avg | 44ms | 42ms | -2ms | -4.54
| uploadFileStream | avg | 476ms | 456ms | -20ms | -4.20
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| getTeamStats | p99 | 50ms | 0s | -50ms | -100.50
| createChannel | p99 | 249ms | 0s | -249ms | -100.20
| patchPost | p99 | 1.772s | 48ms | -1.724s | -97.26
| getChannelUnread | p99 | 82ms | 8ms | -74ms | -90.24
| getChannel | p99 | 99ms | 22ms | -77ms | -78.17
| getChannelMembers | p99 | 10ms | 5ms | -5ms | -50.51
| getDrafts | p99 | 18ms | 9ms | -9ms | -49.69
| deletePost | p99 | 48ms | 25ms | -23ms | -48.42
| logout | p99 | 93ms | 49ms | -44ms | -47.57
| login | p99 | 459ms | 242ms | -217ms | -47.30
| createGroupChannel | p99 | 894ms | 496ms | -398ms | -44.53
| removeUserCustomStatus | p99 | 419ms | 248ms | -171ms | -40.84
| saveReaction | p99 | 40ms | 30ms | -10ms | -24.83
| getChannelsForTeamForUser | p99 | 17ms | 13ms | -4ms | -23.48
| updatePreferences | p99 | 23ms | 18ms | -5ms | -21.94
| getPostsForChannelAroundLastUnread | p99 | 84ms | 66ms | -18ms | -21.44
| createUser | p99 | 456ms | 359ms | -97ms | -21.28
| getClientConfig | p99 | 38ms | 30ms | -8ms | -21.21
| getTeamsUnreadForUser | p99 | 30ms | 24ms | -6ms | -20.01
| listChannelBookmarksForChannel | p99 | 11ms | 9ms | -2ms | -18.11
| getUsersByNames | p99 | 11ms | 9ms | -2ms | -17.45
| getCategoriesForTeamForUser | p99 | 58ms | 48ms | -10ms | -17.37
| getChannelMember | p99 | 41ms | 34ms | -7ms | -17.28
| createPost | p99 | 945ms | 798ms | -147ms | -15.56
| getChannelStats | p99 | 32ms | 27ms | -5ms | -15.50
| getTeamsForUser | p99 | 22ms | 19ms | -3ms | -13.92
| searchGroupChannels | p99 | 23ms | 20ms | -3ms | -13.02
| getUsers | p99 | 25ms | 22ms | -3ms | -12.24
| addTeamMember | p99 | 2.289s | 2.011s | -278ms | -12.15
| uploadFileStream | p99 | 1.124s | 993ms | -131ms | -11.65
| upsertDraft | p99 | 17ms | 15ms | -2ms | -11.50
| getChannelsForUser | p99 | 21ms | 19ms | -2ms | -9.63
| getChannelMembersForUser | p99 | 22ms | 20ms | -2ms | -9.01
| getTeamMembersForUser | p99 | 22ms | 20ms | -2ms | -9.00
| getThreadsForUser | p99 | 22ms | 20ms | -2ms | -8.95
| getAllTeams | p99 | 23ms | 21ms | -2ms | -8.83
| getPreferences | p99 | 23ms | 21ms | -2ms | -8.58
| getPostThread | p99 | 31ms | 29ms | -2ms | -6.40
| addChannelMember | p99 | 487ms | 459ms | -28ms | -5.74
| getProfileImage | p99 | 484ms | 468ms | -16ms | -3.31
| updateReadStateThreadByUser | p99 | 97ms | 94ms | -3ms | -3.09
| createDirectChannel | p99 | 495ms | 486ms | -9ms | -1.82
| getPostsForChannel | p99 | 184ms | 181ms | -3ms | -1.63
| autocompleteUsers | p99 | 151ms | 149ms | -2ms | -1.32
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.307
| BotStore.Get |  Avg| 5ms| 3ms | -2ms | -41.888
| |  P99| 45ms| 10ms | -35ms | -76.923
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.397
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.176
| ChannelStore.Autocomplete |  Avg| 34ms| 33ms | -1ms | -2.982
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 15ms| 28ms | 13ms | 88.231
| |  P99| 49ms| 131ms | 82ms | 166.385
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 94ms| 79ms | -15ms | -15.873
| ChannelStore.CreateInitialSidebarCategories |  Avg| 14ms| 13ms | -1ms | -7.212
| |  P99| 70ms| 52ms | -18ms | -25.855
| ChannelStore.CreateSidebarCategory |  Avg| 15ms| 0s | -15ms | -102.124
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 13ms | -5ms | -27.260
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 10ms| 0s | -10ms | -104.178
| |  P99| 32ms| 0s | -32ms | -101.586
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 3ms | -2ms | -44.065
| |  P99| 23ms| 24ms | 1ms | 4.275
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 16ms| 14ms | -2ms | -12.545
| |  P99| 96ms| 96ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 39ms | 3ms | 8.385
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -38.302
| |  P99| 41ms| 8ms | -33ms | -80.486
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.336
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.905
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.163
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -24.632
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.274
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.462
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.078
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.307
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.598
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.790
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.120
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 14ms| 13ms | -1ms | -7.142
| |  P99| 50ms| 47ms | -3ms | -6.025
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 8ms | 1ms | 14.331
| |  P99| 24ms| 46ms | 22ms | 90.909
| ChannelStore.GetTeamChannels |  Avg| 10ms| 0s | -10ms | -97.412
| |  P99| 25ms| 0s | -25ms | -101.214
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -25.455
| ChannelStore.Save |  Avg| 8ms| 7ms | -1ms | -12.930
| |  P99| 27ms| 40ms | 13ms | 47.709
| ChannelStore.SaveMember |  Avg| 25ms| 24ms | -1ms | -4.051
| |  P99| 95ms| 87ms | -8ms | -8.424
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.045
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.592
| ChannelStore.UpdateSidebarCategories |  Avg| 28ms| 24ms | -4ms | -14.411
| |  P99| 50ms| 49ms | -1ms | -2.015
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 2ms | -1ms | -38.751
| |  P99| 16ms| 8ms | -8ms | -49.689
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.452
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 2ms | -1ms | -30.108
| |  P99| 24ms| 5ms | -19ms | -80.851
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -37.242
| |  P99| 17ms| 9ms | -8ms | -45.749
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.807
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.588
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -24.455
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.778
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 3ms | -1ms | -27.288
| |  P99| 16ms| 20ms | 4ms | 24.637
| FileInfoStore.SetContent |  Avg| 6ms| 5ms | -1ms | -17.630
| |  P99| 30ms| 17ms | -13ms | -42.975
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.640
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.320
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.195
| JobStore.Get |  Avg| 2ms| 0s | -2ms | -89.852
| |  P99| 8ms| 0s | -8ms | -104.575
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 18ms | -7ms | -28.256
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -37.258
| |  P99| 18ms| 5ms | -13ms | -73.654
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -36.877
| |  P99| 51ms| 10ms | -41ms | -80.392
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.216
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.331
| JobStore.UpdateStatus |  Avg| 3ms| 2ms | -1ms | -39.759
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -28.501
| |  P99| 21ms| 18ms | -3ms | -13.970
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 44.253
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.964
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.684
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.817
| PostStore.AnalyticsPostCount |  Avg| 484ms| 448ms | -36ms | -7.438
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.253
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -18.572
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.257
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -27.645
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.325
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 3ms | 1ms | 40.615
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 4ms| 3ms | -1ms | -28.400
| |  P99| 21ms| 20ms | -1ms | -4.678
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 20ms | 15ms | 303.030
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.396
| PostStore.GetPostsByThread |  Avg| 6ms| 5ms | -1ms | -18.104
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.852
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 34ms| 27ms | -7ms | -20.458
| PostStore.SearchPostsForUser |  Avg| 23ms| 26ms | 3ms | 13.020
| |  P99| 595ms| 611ms | 16ms | 2.689
| PostStore.SetPostReminder |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 10ms| 9ms | -1ms | -10.425
| |  P99| 42ms| 24ms | -18ms | -43.114
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 1ms | -1ms | -47.048
| |  P99| 10ms| 5ms | -5ms | -52.631
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -28.568
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.787
| PreferenceStore.Save |  Avg| 7ms| 6ms | -1ms | -15.358
| |  P99| 46ms| 40ms | -6ms | -13.185
| ProductNoticesStore.ClearOldNotices |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 128ms| 93ms | -35ms | -27.339
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.330
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 4ms | 1ms | 29.479
| |  P99| 20ms| 21ms | 1ms | 5.063
| RoleStore.GetByNames |  Avg| 0s| 3ms | 3ms | 1053787.728
| |  P99| 5ms| 23ms | 18ms | 363.636
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 30ms | -7ms | -18.740
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 15ms | -4ms | -20.831
| SessionStore.GetSessionsExpired |  Avg| 3ms| 2ms | -1ms | -38.397
| |  P99| 10ms| 5ms | -5ms | -51.813
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.252
| SessionStore.Remove |  Avg| 3ms| 2ms | -1ms | -36.702
| |  P99| 10ms| 5ms | -5ms | -51.948
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.123
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 13ms | -5ms | -27.040
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 24ms| 3ms | -21ms | -86.252
| |  P99| 428ms| 10ms | -418ms | -97.734
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 9ms | -13ms | -58.296
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.323
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 11ms | -4ms | -26.137
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.508
| TeamStore.GetActiveMemberCount |  Avg| 37ms| 0s | -37ms | -101.085
| |  P99| 50ms| 0s | -50ms | -100.503
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.459
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 2ms | -1ms | -39.365
| |  P99| 20ms| 18ms | -2ms | -10.040
| TeamStore.GetMember |  Avg| 1ms| 2ms | 1ms | 102.998
| |  P99| 5ms| 12ms | 7ms | 140.381
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.423
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.739
| TeamStore.GetTotalMemberCount |  Avg| 36ms| 0s | -36ms | -99.519
| |  P99| 50ms| 0s | -50ms | -100.503
| TeamStore.SaveMember |  Avg| 21ms| 20ms | -1ms | -4.832
| |  P99| 73ms| 62ms | -11ms | -15.159
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.134
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.707
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -36.871
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 3ms | -1ms | -28.551
| |  P99| 18ms| 16ms | -2ms | -11.357
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.412
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -20.190
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.480
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 2ms | -1ms | -38.925
| |  P99| 20ms| 17ms | -3ms | -15.331
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.005
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.619
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 1ms | -1ms | -40.235
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.896
| TokenStore.Cleanup |  Avg| 2ms| 1ms | -1ms | -59.189
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 37ms| 37ms | 0s | 0.000
| |  P99| 169ms| 170ms | 1ms | 0.591
| UserStore.Count |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.109
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.035
| UserStore.GetAllProfilesInChannel |  Avg| 170ms| 156ms | -14ms | -8.240
| |  P99| 486ms| 477ms | -9ms | -1.852
| UserStore.GetByUsername |  Avg| 3ms| 2ms | -1ms | -32.937
| |  P99| 24ms| 10ms | -14ms | -59.385
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.382
| UserStore.GetMany |  Avg| 3ms| 4ms | 1ms | 34.233
| |  P99| 24ms| 46ms | 22ms | 93.024
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.566
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.708
| UserStore.GetProfilesInChannel |  Avg| 11ms| 122ms | 111ms | 1055.264
| |  P99| 25ms| 249ms | 224ms | 901.255
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 0s | -4ms | -95.434
| |  P99| 5ms| 0s | -5ms | -100.966
| UserStore.GetUnreadCount |  Avg| 2ms| 3ms | 1ms | 40.405
| |  P99| 11ms| 17ms | 6ms | 53.086
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.164
| UserStore.Save |  Avg| 73ms| 73ms | 0s | 0.000
| |  P99| 205ms| 205ms | 0s | 0.000
| UserStore.Search |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 65ms| 68ms | 3ms | 4.632
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 67ms| 10ms | -57ms | -84.449
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.399
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.134
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.114
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 30ms| 34ms | 4ms | 13.239
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 216ms| 169ms | -47ms | -21.754
| | P99| 487ms| 459ms | -28ms | -5.744
| addTeamMember | Avg| 631ms| 588ms | -43ms | -6.812
| | P99| 2.289s| 2.011s | -278ms | -12.145
| autocompleteChannelsForTeamForSearch | Avg| 15ms| 28ms | 13ms | 87.886
| | P99| 49ms| 131ms | 82ms | 166.307
| autocompleteUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 151ms| 149ms | -2ms | -1.324
| createCategoryForTeamForUser | Avg| 17ms| 0s | -17ms | -100.103
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 186ms| 0s | -186ms | -100.199
| | P99| 249ms| 0s | -249ms | -100.201
| createDirectChannel | Avg| 231ms| 183ms | -48ms | -20.809
| | P99| 495ms| 486ms | -9ms | -1.820
| createGroupChannel | Avg| 353ms| 270ms | -83ms | -23.520
| | P99| 894ms| 496ms | -398ms | -44.531
| createPost | Avg| 244ms| 175ms | -69ms | -28.248
| | P99| 945ms| 798ms | -147ms | -15.557
| createUser | Avg| 136ms| 121ms | -15ms | -11.043
| | P99| 456ms| 359ms | -97ms | -21.276
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.352
| deletePost | Avg| 16ms| 15ms | -1ms | -6.325
| | P99| 48ms| 25ms | -23ms | -48.421
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.149
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 21ms | -2ms | -8.827
| getCategoriesForTeamForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 58ms| 48ms | -10ms | -17.374
| getChannel | Avg| 9ms| 5ms | -4ms | -44.419
| | P99| 99ms| 22ms | -77ms | -78.168
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 41ms| 34ms | -7ms | -17.279
| getChannelMembers | Avg| 4ms| 3ms | -1ms | -22.495
| | P99| 10ms| 5ms | -5ms | -50.505
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.567
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.007
| getChannelStats | Avg| 3ms| 2ms | -1ms | -39.171
| | P99| 32ms| 27ms | -5ms | -15.502
| getChannelUnread | Avg| 4ms| 2ms | -2ms | -48.614
| | P99| 82ms| 8ms | -74ms | -90.242
| getChannelsForTeamForUser | Avg| 3ms| 2ms | -1ms | -39.248
| | P99| 17ms| 13ms | -4ms | -23.481
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.629
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 38ms| 30ms | -8ms | -21.212
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 9ms | -9ms | -49.689
| getFilePreview | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 96ms| 95ms | -1ms | -1.044
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 90ms| 90ms | 0s | 0.000
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 31ms| 29ms | -2ms | -6.402
| getPostsForChannel | Avg| 21ms| 20ms | -1ms | -4.865
| | P99| 184ms| 181ms | -3ms | -1.628
| getPostsForChannelAroundLastUnread | Avg| 15ms| 14ms | -1ms | -6.680
| | P99| 84ms| 66ms | -18ms | -21.441
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 21ms | -2ms | -8.582
| getProfileImage | Avg| 92ms| 86ms | -6ms | -6.510
| | P99| 484ms| 468ms | -16ms | -3.305
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 48ms | 23ms | 92.555
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.001
| getTeamStats | Avg| 39ms| 0s | -39ms | -99.175
| | P99| 50ms| 0s | -50ms | -100.503
| getTeamsForUser | Avg| 3ms| 2ms | -1ms | -38.995
| | P99| 22ms| 19ms | -3ms | -13.922
| getTeamsUnreadForUser | Avg| 5ms| 4ms | -1ms | -20.928
| | P99| 30ms| 24ms | -6ms | -20.011
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -8.949
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 3ms | -1ms | -26.459
| | P99| 25ms| 22ms | -3ms | -12.242
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 2ms | -1ms | -39.145
| | P99| 11ms| 9ms | -2ms | -17.450
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 9ms | -2ms | -18.106
| login | Avg| 80ms| 57ms | -23ms | -28.718
| | P99| 459ms| 242ms | -217ms | -47.302
| logout | Avg| 40ms| 23ms | -17ms | -42.482
| | P99| 93ms| 49ms | -44ms | -47.567
| patchPost | Avg| 66ms| 22ms | -44ms | -66.970
| | P99| 1.772s| 48ms | -1.724s | -97.264
| removeUserCustomStatus | Avg| 155ms| 112ms | -43ms | -27.787
| | P99| 419ms| 248ms | -171ms | -40.835
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 40ms| 30ms | -10ms | -24.829
| searchAllChannels | Avg| 34ms| 33ms | -1ms | -2.963
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 3ms | -1ms | -28.469
| | P99| 23ms| 20ms | -3ms | -13.022
| searchPostsInTeam | Avg| 31ms| 33ms | 2ms | 6.524
| | P99| 595ms| 611ms | 16ms | 2.689
| searchUsers | Avg| 15ms| 16ms | 1ms | 6.520
| | P99| 68ms| 72ms | 4ms | 5.889
| setPostReminder | Avg| 14ms| 16ms | 2ms | 13.910
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 11ms | 1ms | 10.373
| | P99| 25ms| 43ms | 18ms | 73.097
| updateCategoriesForTeamForUser | Avg| 44ms| 42ms | -2ms | -4.541
| | P99| 96ms| 224ms | 128ms | 133.316
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 23ms| 18ms | -5ms | -21.942
| updateReadStateAllThreadsByUser | Avg| 3ms| 1ms | -2ms | -77.617
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 97ms| 94ms | -3ms | -3.094
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 476ms| 456ms | -20ms | -4.202
| | P99| 1.124s| 993ms | -131ms | -11.653
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 15ms | -2ms | -11.500
| viewChannel | Avg| 8ms| 10ms | 2ms | 24.553
| | P99| 36ms| 39ms | 3ms | 8.363

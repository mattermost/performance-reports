### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 591ms | 589ms | 28781.42
| PluginStore.List | avg | 1ms | 7ms | 6ms | 735.91
| TeamStore.AnalyticsTeamCount | avg | 1ms | 3ms | 2ms | 301.56
| PostAcknowledgementStore.GetForPost | avg | 1ms | 4ms | 3ms | 222.72
| ComplianceStore.MessageExport | avg | 1ms | 3ms | 2ms | 141.45
| PostPriorityStore.GetForPost | avg | 2ms | 4ms | 2ms | 114.95
| ChannelStore.CreateSidebarCategory | avg | 8ms | 10ms | 2ms | 25.52
| ChannelStore.GetChannelsByUser | avg | 15ms | 17ms | 2ms | 13.28
| ChannelStore.GetTeamChannels | avg | 31ms | 35ms | 4ms | 13.00
| TeamStore.GetTotalMemberCount | avg | 110ms | 114ms | 4ms | 3.63
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 2.47s | 2.465s | 49785.72
| PluginStore.List | p99 | 8ms | 196ms | 188ms | 2292.92
| ComplianceStore.MessageExport | p99 | 5ms | 24ms | 19ms | 383.84
| PostAcknowledgementStore.GetForPost | p99 | 33ms | 94ms | 61ms | 186.28
| ChannelStore.CreateSidebarCategory | p99 | 10ms | 25ms | 15ms | 150.71
| PostStore.GetPostsByThread | p99 | 6ms | 14ms | 8ms | 139.80
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 101.01
| PostStore.SetPostReminder | p99 | 5ms | 10ms | 5ms | 101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 10ms | 5ms | 101.01
| ThreadStore.GetThreadUnreadReplyCount | p99 | 9ms | 16ms | 7ms | 77.30
| LinkMetadataStore.Save | p99 | 5ms | 8ms | 3ms | 60.60
| UserStore.UpdateLastLogin | p99 | 10ms | 16ms | 6ms | 60.02
| DraftStore.Delete | p99 | 5ms | 8ms | 3ms | 60.00
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 10ms | 15ms | 5ms | 48.60
| ChannelStore.GetChannelsByUser | p99 | 194ms | 251ms | 57ms | 29.34
| PostPriorityStore.GetForPost | p99 | 38ms | 49ms | 11ms | 28.57
| AuditStore.Save | p99 | 16ms | 20ms | 4ms | 24.29
| ChannelStore.GetAllChannelMembersForUser | p99 | 48ms | 59ms | 11ms | 22.83
| JobStore.GetCountByStatusAndType | p99 | 36ms | 44ms | 8ms | 22.22
| UserStore.AutocompleteUsersInChannel | p99 | 556ms | 668ms | 112ms | 20.13
| PostStore.GetSingle | p99 | 25ms | 30ms | 5ms | 19.83
| EmojiStore.GetByName | p99 | 38ms | 45ms | 7ms | 18.55
| UserStore.UpdateUpdateAt | p99 | 13ms | 15ms | 2ms | 15.00
| LinkMetadataStore.Get | p99 | 30ms | 34ms | 4ms | 13.35
| ChannelStore.GetFileCount | p99 | 70ms | 78ms | 8ms | 11.42
| GroupStore.GetByName | p99 | 118ms | 128ms | 10ms | 8.50
| ChannelStore.GetMemberForPost | p99 | 36ms | 39ms | 3ms | 8.31
| UserStore.IsEmpty | p99 | 74ms | 80ms | 6ms | 8.09
| ChannelStore.GetPinnedPostCount | p99 | 38ms | 41ms | 3ms | 7.85
| TeamStore.Get | p99 | 40ms | 43ms | 3ms | 7.43
| ChannelStore.Save | p99 | 72ms | 77ms | 5ms | 6.94
| ChannelStore.GetMemberLastViewedAt | p99 | 88ms | 93ms | 5ms | 5.71
| StatusStore.Get | p99 | 85ms | 88ms | 3ms | 3.54
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 242ms | 248ms | 6ms | 2.48
| UserStore.GetForLogin | p99 | 136ms | 138ms | 2ms | 1.47
| ChannelStore.SaveMember | p99 | 395ms | 400ms | 5ms | 1.26
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 15ms | 3ms | -12ms | -78.48
| SessionStore.GetSessionsExpired | avg | 6ms | 1ms | -5ms | -78.39
| BotStore.Get | avg | 3ms | 1ms | -2ms | -72.06
| PostStore.SearchPostsForUser | avg | 124ms | 54ms | -70ms | -56.58
| ReactionStore.GetForPost | avg | 4ms | 2ms | -2ms | -54.87
| ChannelStore.GetPublicChannelsForTeam | avg | 17ms | 10ms | -7ms | -42.09
| FileInfoStore.GetByIds | avg | 5ms | 3ms | -2ms | -39.60
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 20ms | 16ms | -4ms | -20.29
| ChannelStore.GetMemberCount | avg | 177ms | 156ms | -21ms | -11.85
| ChannelStore.AutocompleteInTeamForSearch | avg | 130ms | 123ms | -7ms | -5.37
| UserStore.Count | avg | 81ms | 77ms | -4ms | -4.91
| UserStore.GetAllProfilesInChannel | avg | 480ms | 465ms | -15ms | -3.13
| TeamStore.GetActiveMemberCount | avg | 152ms | 149ms | -3ms | -1.97
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| UserAccessTokenStore.GetByToken | p99 | 62ms | 5ms | -57ms | -91.92
| StatusStore.SaveOrUpdate | p99 | 226ms | 21ms | -205ms | -90.61
| BotStore.Get | p99 | 46ms | 5ms | -41ms | -89.62
| SessionStore.GetSessionsExpired | p99 | 48ms | 5ms | -43ms | -89.12
| ReactionStore.GetForPost | p99 | 72ms | 8ms | -64ms | -88.76
| PostStore.GetPostsAfter | p99 | 41ms | 5ms | -36ms | -87.27
| FileInfoStore.GetForPost | p99 | 37ms | 6ms | -31ms | -83.00
| ChannelStore.GetPublicChannelsForTeam | p99 | 145ms | 31ms | -114ms | -78.38
| DraftStore.GetDraftsForUser | p99 | 49ms | 20ms | -29ms | -58.68
| FileInfoStore.GetByIds | p99 | 151ms | 65ms | -86ms | -56.77
| DraftStore.Get | p99 | 31ms | 15ms | -16ms | -51.00
| UserStore.GetByUsername | p99 | 58ms | 30ms | -28ms | -48.68
| ChannelStore.UpdateSidebarCategories | p99 | 94ms | 49ms | -45ms | -47.87
| JobStore.Save | p99 | 9ms | 5ms | -4ms | -44.82
| FileInfoStore.Get | p99 | 21ms | 12ms | -9ms | -42.39
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 164ms | 98ms | -66ms | -40.12
| JobStore.UpdateStatus | p99 | 8ms | 5ms | -3ms | -38.49
| ThreadStore.MarkAllAsReadByChannels | p99 | 8ms | 5ms | -3ms | -37.04
| PostStore.Update | p99 | 39ms | 25ms | -14ms | -36.24
| ChannelStore.CreateDirectChannel | p99 | 115ms | 78ms | -37ms | -32.19
| ChannelStore.SearchGroupChannels | p99 | 87ms | 61ms | -26ms | -29.80
| JobStore.Get | p99 | 41ms | 30ms | -11ms | -26.59
| UserStore.GetUnreadCount | p99 | 41ms | 30ms | -11ms | -26.52
| ThreadStore.GetMembershipForUser | p99 | 39ms | 29ms | -10ms | -25.97
| ChannelStore.GetMemberCount | p99 | 804ms | 599ms | -205ms | -25.48
| ThreadStore.GetThreadsForUser | p99 | 60ms | 46ms | -14ms | -23.23
| SessionStore.Get | p99 | 129ms | 99ms | -30ms | -23.18
| ThreadStore.GetThreadFollowers | p99 | 58ms | 45ms | -13ms | -22.30
| PostStore.SearchPostsForUser | p99 | 317ms | 249ms | -68ms | -21.43
| ChannelStore.GetMember | p99 | 10ms | 8ms | -2ms | -20.36
| ChannelStore.CreateInitialSidebarCategories | p99 | 143ms | 114ms | -29ms | -20.25
| PostPersistentNotificationStore.GetSingle | p99 | 61ms | 50ms | -11ms | -18.13
| UserStore.Save | p99 | 138ms | 114ms | -24ms | -17.39
| PreferenceStore.GetAll | p99 | 131ms | 109ms | -22ms | -16.84
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 22ms | 19ms | -3ms | -13.66
| ThreadStore.GetThreadForUser | p99 | 45ms | 40ms | -5ms | -11.22
| ThreadStore.GetTeamsUnreadForUser | p99 | 95ms | 85ms | -10ms | -10.51
| UserStore.UpdateFailedPasswordAttempts | p99 | 20ms | 18ms | -2ms | -10.11
| WebhookStore.GetOutgoingByTeam | p99 | 45ms | 41ms | -4ms | -8.79
| TeamStore.GetTeamsForUser | p99 | 107ms | 98ms | -9ms | -8.43
| PostStore.GetPostReminders | p99 | 24ms | 22ms | -2ms | -8.28
| PostStore.GetPostsBefore | p99 | 61ms | 56ms | -5ms | -8.17
| ChannelStore.GetGuestCount | p99 | 160ms | 147ms | -13ms | -8.15
| UserStore.GetAllProfiles | p99 | 86ms | 79ms | -7ms | -8.11
| ChannelStore.GetMembersForUser | p99 | 74ms | 69ms | -5ms | -6.74
| PreferenceStore.Save | p99 | 30ms | 28ms | -2ms | -6.74
| PreferenceStore.Get | p99 | 46ms | 43ms | -3ms | -6.48
| SessionStore.GetLRUSessions | p99 | 157ms | 147ms | -10ms | -6.38
| GroupStore.GetGroups | p99 | 65ms | 61ms | -4ms | -6.15
| ChannelStore.Get | p99 | 106ms | 100ms | -6ms | -5.67
| PostPriorityStore.GetForPosts | p99 | 54ms | 51ms | -3ms | -5.61
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 93ms | 88ms | -5ms | -5.37
| ChannelStore.GetChannels | p99 | 81ms | 77ms | -4ms | -4.93
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 87ms | 83ms | -4ms | -4.57
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 46ms | 44ms | -2ms | -4.36
| PostAcknowledgementStore.GetForPosts | p99 | 49ms | 47ms | -2ms | -4.12
| ThreadStore.GetTotalThreads | p99 | 88ms | 85ms | -3ms | -3.41
| ThreadStore.GetTotalUnreadMentions | p99 | 88ms | 85ms | -3ms | -3.39
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 89ms | 86ms | -3ms | -3.37
| TeamStore.GetTeamsByUserId | p99 | 93ms | 90ms | -3ms | -3.21
| ChannelStore.GetByName | p99 | 97ms | 94ms | -3ms | -3.10
| TeamStore.GetAllPage | p99 | 97ms | 94ms | -3ms | -3.09
| SessionStore.Save | p99 | 151ms | 147ms | -4ms | -2.65
| ProductNoticesStore.View | p99 | 85ms | 83ms | -2ms | -2.36
| UserStore.GetAllProfilesInChannel | p99 | 2.229s | 2.18s | -49ms | -2.20
| PostStore.GetEtag | p99 | 100ms | 98ms | -2ms | -2.01
| UserTermsOfServiceStore.GetByUser | p99 | 100ms | 98ms | -2ms | -2.00
| UserStore.Search | p99 | 388ms | 382ms | -6ms | -1.55
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 24ms | 33ms | 9ms | 36.99
| removeUserCustomStatus | avg | 96ms | 120ms | 24ms | 24.93
| createCategoryForTeamForUser | avg | 9ms | 11ms | 2ms | 22.59
| createChannel | avg | 191ms | 219ms | 28ms | 14.64
| updateReadStateThreadByUser | avg | 14ms | 16ms | 2ms | 13.93
| getChannelsForUser | avg | 16ms | 18ms | 2ms | 12.64
| updateCategoriesForTeamForUser | avg | 18ms | 20ms | 2ms | 11.31
| getFileThumbnail | avg | 30ms | 32ms | 2ms | 6.57
| uploadFileStream | avg | 365ms | 377ms | 12ms | 3.29
| createUser | avg | 107ms | 110ms | 3ms | 2.79
| createPost | avg | 353ms | 361ms | 8ms | 2.27
| autocompleteUsers | avg | 174ms | 176ms | 2ms | 1.15
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 10ms | 25ms | 15ms | 150.71
| setPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| patchPost | p99 | 273ms | 585ms | 312ms | 114.47
| updateCategoriesForTeamForUser | p99 | 25ms | 48ms | 23ms | 92.55
| updateReadStateThreadByUser | p99 | 89ms | 164ms | 75ms | 84.43
| getPostThread | p99 | 52ms | 70ms | 18ms | 34.82
| getChannelsForUser | p99 | 204ms | 269ms | 65ms | 31.88
| saveReaction | p99 | 152ms | 182ms | 30ms | 19.67
| autocompleteUsers | p99 | 496ms | 574ms | 78ms | 15.72
| getTeamMembersForUser | p99 | 125ms | 136ms | 11ms | 8.81
| getPostsForChannelAroundLastUnread | p99 | 426ms | 453ms | 27ms | 6.33
| getCategoriesForTeamForUser | p99 | 242ms | 248ms | 6ms | 2.48
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateCategoryForTeamForUser | avg | 63ms | 0s | -63ms | -99.89
| searchPostsInTeam | avg | 131ms | 57ms | -74ms | -56.46
| getFilteredUsersStats | avg | 55ms | 27ms | -28ms | -50.65
| getPublicChannelsForTeam | avg | 18ms | 11ms | -7ms | -39.42
| logout | avg | 37ms | 24ms | -13ms | -35.32
| getProfileImage | avg | 85ms | 77ms | -8ms | -9.42
| login | avg | 67ms | 63ms | -4ms | -5.99
| autocompleteChannelsForTeamForSearch | avg | 130ms | 123ms | -7ms | -5.36
| addTeamMember | avg | 1.28s | 1.239s | -41ms | -3.20
| searchUsers | avg | 95ms | 93ms | -2ms | -2.11
| getTeamStats | avg | 152ms | 149ms | -3ms | -1.97
| addChannelMember | avg | 178ms | 175ms | -3ms | -1.68
| createDirectChannel | avg | 167ms | 165ms | -2ms | -1.20
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| updateCategoryForTeamForUser | p99 | 100ms | 0s | -100ms | -100.50
| getFilteredUsersStats | p99 | 246ms | 50ms | -196ms | -79.84
| getPublicChannelsForTeam | p99 | 145ms | 31ms | -114ms | -78.38
| createGroupChannel | p99 | 1.735s | 494ms | -1.241s | -71.53
| addChannelMember | p99 | 812ms | 295ms | -517ms | -63.63
| getDrafts | p99 | 49ms | 20ms | -29ms | -58.59
| getChannel | p99 | 126ms | 59ms | -67ms | -53.38
| followThreadByUser | p99 | 10ms | 5ms | -5ms | -50.59
| deleteDraft | p99 | 32ms | 16ms | -16ms | -50.11
| searchPostsInTeam | p99 | 740ms | 376ms | -364ms | -49.20
| logout | p99 | 91ms | 48ms | -43ms | -47.25
| getChannelUnread | p99 | 8ms | 5ms | -3ms | -37.04
| upsertDraft | p99 | 20ms | 13ms | -7ms | -34.50
| searchGroupChannels | p99 | 87ms | 61ms | -26ms | -29.80
| getUser | p99 | 122ms | 101ms | -21ms | -17.18
| getThreadsForUser | p99 | 76ms | 65ms | -11ms | -14.47
| getClientConfig | p99 | 46ms | 40ms | -6ms | -12.96
| getUsers | p99 | 81ms | 71ms | -10ms | -12.41
| getPreferences | p99 | 138ms | 121ms | -17ms | -12.31
| createDirectChannel | p99 | 448ms | 398ms | -50ms | -11.16
| viewChannel | p99 | 109ms | 98ms | -11ms | -10.07
| getTeamsUnreadForUser | p99 | 165ms | 150ms | -15ms | -9.09
| getChannelStats | p99 | 423ms | 397ms | -26ms | -6.14
| getChannelMember | p99 | 163ms | 154ms | -9ms | -5.52
| createPost | p99 | 2.286s | 2.165s | -121ms | -5.29
| login | p99 | 457ms | 433ms | -24ms | -5.26
| getProfileImage | p99 | 408ms | 387ms | -21ms | -5.14
| getAllTeams | p99 | 104ms | 99ms | -5ms | -4.80
| getTeamsForUser | p99 | 94ms | 90ms | -4ms | -4.26
| getChannelsForTeamForUser | p99 | 92ms | 90ms | -2ms | -2.18
| getPostsForChannel | p99 | 254ms | 249ms | -5ms | -1.97
| searchUsers | p99 | 397ms | 390ms | -7ms | -1.76
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 20ms | 4ms | 24.291
| BotStore.Get |  Avg| 3ms| 1ms | -2ms | -72.059
| |  P99| 46ms| 5ms | -41ms | -89.617
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 275ms| 275ms | 0s | 0.000
| |  P99| 498ms| 498ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 48.599
| ChannelStore.AnalyticsTypeCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 1.497s| 1.497s | 0s | 0.000
| |  P99| 4.993s| 4.956s | -37ms | -0.741
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 130ms| 123ms | -7ms | -5.367
| |  P99| 818ms| 822ms | 4ms | 0.489
| ChannelStore.CreateDirectChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 115ms| 78ms | -37ms | -32.186
| ChannelStore.CreateInitialSidebarCategories |  Avg| 15ms| 14ms | -1ms | -6.841
| |  P99| 143ms| 114ms | -29ms | -20.254
| ChannelStore.CreateSidebarCategory |  Avg| 8ms| 10ms | 2ms | 25.522
| |  P99| 10ms| 25ms | 15ms | 150.710
| ChannelStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 106ms| 100ms | -6ms | -5.674
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 13ms| 12ms | -1ms | -7.779
| |  P99| 93ms| 88ms | -5ms | -5.369
| ChannelStore.GetAllChannelMembersForUser |  Avg| 8ms| 9ms | 1ms | 12.769
| |  P99| 48ms| 59ms | 11ms | 22.829
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 16ms | -4ms | -20.288
| |  P99| 164ms| 98ms | -66ms | -40.122
| ChannelStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 97ms| 94ms | -3ms | -3.102
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 4ms| 3ms | -1ms | -27.995
| |  P99| 81ms| 77ms | -4ms | -4.932
| ChannelStore.GetChannelsByUser |  Avg| 15ms| 17ms | 2ms | 13.281
| |  P99| 194ms| 251ms | 57ms | 29.338
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 46ms| 44ms | -2ms | -4.362
| ChannelStore.GetFileCount |  Avg| 4ms| 5ms | 1ms | 23.105
| |  P99| 70ms| 78ms | 8ms | 11.419
| ChannelStore.GetGuestCount |  Avg| 8ms| 7ms | -1ms | -12.709
| |  P99| 160ms| 147ms | -13ms | -8.149
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.355
| ChannelStore.GetMemberCount |  Avg| 177ms| 156ms | -21ms | -11.846
| |  P99| 804ms| 599ms | -205ms | -25.483
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 39ms | 3ms | 8.306
| ChannelStore.GetMemberLastViewedAt |  Avg| 4ms| 5ms | 1ms | 22.735
| |  P99| 88ms| 93ms | 5ms | 5.709
| ChannelStore.GetMembersForUser |  Avg| 4ms| 3ms | -1ms | -28.462
| |  P99| 74ms| 69ms | -5ms | -6.737
| ChannelStore.GetMembersForUserWithPagination |  Avg| 12ms| 13ms | 1ms | 8.057
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.849
| ChannelStore.GetPublicChannelsForTeam |  Avg| 17ms| 10ms | -7ms | -42.089
| |  P99| 145ms| 31ms | -114ms | -78.385
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 16ms| 17ms | 1ms | 6.115
| |  P99| 242ms| 248ms | 6ms | 2.482
| ChannelStore.GetSidebarCategory |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 31ms| 35ms | 4ms | 13.003
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 72ms| 77ms | 5ms | 6.945
| ChannelStore.SaveMember |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 395ms| 400ms | 5ms | 1.264
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 87ms| 61ms | -26ms | -29.800
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 94ms| 49ms | -45ms | -47.872
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.305
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 1ms| 3ms | 2ms | 141.451
| |  P99| 5ms| 24ms | 19ms | 383.838
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.003
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 11ms | -1ms | -8.636
| |  P99| 25ms| 25ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 1ms | -1ms | -63.044
| |  P99| 31ms| 15ms | -16ms | -51.003
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 49ms| 20ms | -29ms | -58.685
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 45ms | 7ms | 18.551
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.298
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 12ms | -9ms | -42.388
| FileInfoStore.GetByIds |  Avg| 5ms| 3ms | -2ms | -39.601
| |  P99| 151ms| 65ms | -86ms | -56.768
| FileInfoStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -51.996
| |  P99| 37ms| 6ms | -31ms | -83.001
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 87ms| 83ms | -4ms | -4.572
| GroupStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 118ms| 128ms | 10ms | 8.500
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 65ms| 61ms | -4ms | -6.150
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 1ms | -1ms | -61.926
| |  P99| 41ms| 30ms | -11ms | -26.586
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 44ms | 8ms | 22.222
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 50ms| 51ms | 1ms | 2.005
| JobStore.Save |  Avg| 3ms| 2ms | -1ms | -36.683
| |  P99| 9ms| 5ms | -4ms | -44.818
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.487
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 2ms | 1ms | 67.547
| |  P99| 30ms| 34ms | 4ms | 13.348
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.597
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 7ms | 6ms | 735.913
| |  P99| 8ms| 196ms | 188ms | 2292.916
| PluginStore.SetWithOptions |  Avg| 3ms| 4ms | 1ms | 29.009
| |  P99| 16ms| 17ms | 1ms | 6.379
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 4ms | 3ms | 222.721
| |  P99| 33ms| 94ms | 61ms | 186.277
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 49ms| 47ms | -2ms | -4.121
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 61ms| 50ms | -11ms | -18.130
| PostPriorityStore.GetForPost |  Avg| 2ms| 4ms | 2ms | 114.946
| |  P99| 38ms| 49ms | 11ms | 28.573
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 54ms| 51ms | -3ms | -5.607
| PostStore.AnalyticsPostCount |  Avg| 2ms| 591ms | 589ms | 28781.422
| |  P99| 5ms| 2.47s | 2.465s | 49785.724
| PostStore.Delete |  Avg| 6ms| 7ms | 1ms | 16.154
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 56ms| 56ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 100ms| 98ms | -2ms | -2.007
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.282
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 94ms| 95ms | 1ms | 1.068
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -32.994
| |  P99| 41ms| 5ms | -36ms | -87.269
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 61ms| 56ms | -5ms | -8.170
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 14ms | 8ms | 139.803
| PostStore.GetPostsSince |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 83ms| 82ms | -1ms | -1.198
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 30ms | 5ms | 19.827
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 124ms| 54ms | -70ms | -56.581
| |  P99| 317ms| 249ms | -68ms | -21.427
| PostStore.SetPostReminder |  Avg| 3ms| 4ms | 1ms | 29.262
| |  P99| 5ms| 10ms | 5ms | 101.010
| PostStore.Update |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -36.244
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.484
| PreferenceStore.GetAll |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 131ms| 109ms | -22ms | -16.844
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 30ms| 28ms | -2ms | -6.736
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 16ms| 17ms | 1ms | 6.317
| |  P99| 85ms| 83ms | -2ms | -2.358
| ReactionStore.GetForPost |  Avg| 4ms| 2ms | -2ms | -54.868
| |  P99| 72ms| 8ms | -64ms | -88.759
| RetentionPolicyStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 129ms| 99ms | -30ms | -23.183
| SessionStore.GetLRUSessions |  Avg| 7ms| 6ms | -1ms | -14.399
| |  P99| 157ms| 147ms | -10ms | -6.380
| SessionStore.GetSessionsExpired |  Avg| 6ms| 1ms | -5ms | -78.394
| |  P99| 48ms| 5ms | -43ms | -89.119
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.660
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.Save |  Avg| 10ms| 9ms | -1ms | -10.285
| |  P99| 151ms| 147ms | -4ms | -2.650
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| StatusStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 85ms| 88ms | 3ms | 3.543
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 15ms| 3ms | -12ms | -78.478
| |  P99| 226ms| 21ms | -205ms | -90.614
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| SystemStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 3ms | 2ms | 301.561
| |  P99| 5ms| 10ms | 5ms | 101.010
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 40ms| 43ms | 3ms | 7.434
| TeamStore.GetActiveMemberCount |  Avg| 152ms| 149ms | -3ms | -1.975
| |  P99| 248ms| 249ms | 1ms | 0.402
| TeamStore.GetAllPage |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 97ms| 94ms | -3ms | -3.086
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 88ms| 87ms | -1ms | -1.134
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 93ms| 90ms | -3ms | -3.209
| TeamStore.GetTeamsForUser |  Avg| 6ms| 5ms | -1ms | -17.033
| |  P99| 107ms| 98ms | -9ms | -8.427
| TeamStore.GetTotalMemberCount |  Avg| 110ms| 114ms | 4ms | 3.626
| |  P99| 248ms| 249ms | 1ms | 0.402
| TeamStore.SaveMember |  Avg| 96ms| 96ms | 0s | 0.000
| |  P99| 245ms| 245ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 39ms| 29ms | -10ms | -25.967
| ThreadStore.GetTeamsUnreadForUser |  Avg| 6ms| 5ms | -1ms | -16.875
| |  P99| 95ms| 85ms | -10ms | -10.511
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 58ms| 45ms | -13ms | -22.302
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 40ms | -5ms | -11.225
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 77.296
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 60ms| 46ms | -14ms | -23.228
| ThreadStore.GetTotalThreads |  Avg| 5ms| 4ms | -1ms | -21.952
| |  P99| 88ms| 85ms | -3ms | -3.411
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 88ms| 85ms | -3ms | -3.392
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 84ms| 83ms | -1ms | -1.188
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 5ms| 4ms | -1ms | -21.424
| |  P99| 89ms| 86ms | -3ms | -3.366
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 1ms | -1ms | -63.520
| |  P99| 8ms| 5ms | -3ms | -37.038
| ThreadStore.MarkAllAsReadByTeam |  Avg| 1ms| 0s | -1ms | -144.900
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.690
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -59.799
| |  P99| 62ms| 5ms | -57ms | -91.925
| UserStore.AnalyticsActiveCount |  Avg| 216ms| 217ms | 1ms | 0.463
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 1ms | 1ms | 232.006
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 200ms| 202ms | 2ms | 0.999
| |  P99| 556ms| 668ms | 112ms | 20.127
| UserStore.Count |  Avg| 81ms| 77ms | -4ms | -4.915
| |  P99| 247ms| 247ms | 0s | 0.000
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 86ms| 79ms | -7ms | -8.111
| UserStore.GetAllProfilesInChannel |  Avg| 480ms| 465ms | -15ms | -3.127
| |  P99| 2.229s| 2.18s | -49ms | -2.199
| UserStore.GetByUsername |  Avg| 2ms| 1ms | -1ms | -45.168
| |  P99| 58ms| 30ms | -28ms | -48.685
| UserStore.GetForLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 136ms| 138ms | 2ms | 1.468
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 3ms | 1ms | 43.470
| |  P99| 41ms| 30ms | -11ms | -26.523
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 74ms| 80ms | 6ms | 8.093
| UserStore.Save |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 138ms| 114ms | -24ms | -17.387
| UserStore.Search |  Avg| 93ms| 92ms | -1ms | -1.073
| |  P99| 388ms| 382ms | -6ms | -1.548
| UserStore.Update |  Avg| 4ms| 3ms | -1ms | -28.557
| |  P99| 9ms| 8ms | -1ms | -10.801
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.113
| UserStore.UpdateLastLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.021
| UserStore.UpdateUpdateAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.000
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 5ms | -1ms | -17.947
| |  P99| 100ms| 98ms | -2ms | -2.004
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 41ms | -4ms | -8.793
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 178ms| 175ms | -3ms | -1.682
| | P99| 812ms| 295ms | -517ms | -63.633
| addTeamMember | Avg| 1.28s| 1.239s | -41ms | -3.203
| | P99| 4.671s| 4.63s | -41ms | -0.878
| autocompleteChannelsForTeamForSearch | Avg| 130ms| 123ms | -7ms | -5.364
| | P99| 818ms| 822ms | 4ms | 0.489
| autocompleteUsers | Avg| 174ms| 176ms | 2ms | 1.149
| | P99| 496ms| 574ms | 78ms | 15.724
| createCategoryForTeamForUser | Avg| 9ms| 11ms | 2ms | 22.585
| | P99| 10ms| 25ms | 15ms | 150.710
| createChannel | Avg| 191ms| 219ms | 28ms | 14.637
| | P99| 249ms| 249ms | 0s | 0.000
| createDirectChannel | Avg| 167ms| 165ms | -2ms | -1.198
| | P99| 448ms| 398ms | -50ms | -11.158
| createGroupChannel | Avg| 245ms| 244ms | -1ms | -0.408
| | P99| 1.735s| 494ms | -1.241s | -71.533
| createPost | Avg| 353ms| 361ms | 8ms | 2.268
| | P99| 2.286s| 2.165s | -121ms | -5.293
| createUser | Avg| 107ms| 110ms | 3ms | 2.794
| | P99| 430ms| 428ms | -2ms | -0.465
| deleteDraft | Avg| 2ms| 1ms | -1ms | -57.272
| | P99| 32ms| 16ms | -16ms | -50.106
| deletePost | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -50.590
| getAllTeams | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 104ms| 99ms | -5ms | -4.801
| getAnalytics | Avg| 318ms| 319ms | 1ms | 0.315
| | P99| 498ms| 498ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 242ms| 248ms | 6ms | 2.482
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 126ms| 59ms | -67ms | -53.382
| getChannelMember | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 163ms| 154ms | -9ms | -5.518
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 77ms| 76ms | -1ms | -1.291
| getChannelMembersForUser | Avg| 13ms| 14ms | 1ms | 7.544
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 18ms| 17ms | -1ms | -5.428
| | P99| 423ms| 397ms | -26ms | -6.141
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -37.035
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 92ms| 90ms | -2ms | -2.180
| getChannelsForUser | Avg| 16ms| 18ms | 2ms | 12.639
| | P99| 204ms| 269ms | 65ms | 31.882
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 46ms| 40ms | -6ms | -12.958
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 49ms| 20ms | -29ms | -58.586
| getFilePreview | Avg| 46ms| 47ms | 1ms | 2.152
| | P99| 225ms| 226ms | 1ms | 0.445
| getFileThumbnail | Avg| 30ms| 32ms | 2ms | 6.570
| | P99| 97ms| 98ms | 1ms | 1.030
| getFilteredUsersStats | Avg| 55ms| 27ms | -28ms | -50.653
| | P99| 246ms| 50ms | -196ms | -79.837
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 52ms| 70ms | 18ms | 34.817
| getPostsForChannel | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 254ms| 249ms | -5ms | -1.970
| getPostsForChannelAroundLastUnread | Avg| 30ms| 31ms | 1ms | 3.375
| | P99| 426ms| 453ms | 27ms | 6.335
| getPreferences | Avg| 8ms| 7ms | -1ms | -13.125
| | P99| 138ms| 121ms | -17ms | -12.305
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 85ms| 77ms | -8ms | -9.423
| | P99| 408ms| 387ms | -21ms | -5.145
| getPublicChannelsForTeam | Avg| 18ms| 11ms | -7ms | -39.419
| | P99| 145ms| 31ms | -114ms | -78.385
| getRolesByNames | Avg| 0s| 1ms | 1ms | 248.810
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 7ms| 6ms | -1ms | -14.714
| | P99| 125ms| 136ms | 11ms | 8.806
| getTeamStats | Avg| 152ms| 149ms | -3ms | -1.974
| | P99| 248ms| 249ms | 1ms | 0.402
| getTeamsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 94ms| 90ms | -4ms | -4.263
| getTeamsUnreadForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 165ms| 150ms | -15ms | -9.089
| getThreadsForUser | Avg| 4ms| 3ms | -1ms | -27.749
| | P99| 76ms| 65ms | -11ms | -14.466
| getUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 122ms| 101ms | -21ms | -17.178
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 81ms| 71ms | -10ms | -12.411
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 42ms| 42ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 67ms| 63ms | -4ms | -5.988
| | P99| 457ms| 433ms | -24ms | -5.256
| logout | Avg| 37ms| 24ms | -13ms | -35.324
| | P99| 91ms| 48ms | -43ms | -47.252
| patchPost | Avg| 24ms| 33ms | 9ms | 36.994
| | P99| 273ms| 585ms | 312ms | 114.474
| removeUserCustomStatus | Avg| 96ms| 120ms | 24ms | 24.933
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 8ms | 1ms | 14.265
| | P99| 152ms| 182ms | 30ms | 19.673
| searchAllChannels | Avg| 1.498s| 1.497s | -1ms | -0.067
| | P99| 4.993s| 4.956s | -37ms | -0.741
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 87ms| 61ms | -26ms | -29.800
| searchPostsInTeam | Avg| 131ms| 57ms | -74ms | -56.463
| | P99| 740ms| 376ms | -364ms | -49.197
| searchUsers | Avg| 95ms| 93ms | -2ms | -2.109
| | P99| 397ms| 390ms | -7ms | -1.762
| setPostReminder | Avg| 8ms| 9ms | 1ms | 11.947
| | P99| 10ms| 24ms | 14ms | 140.704
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 18ms| 20ms | 2ms | 11.308
| | P99| 25ms| 48ms | 23ms | 92.546
| updateCategoryForTeamForUser | Avg| 63ms| 0s | -63ms | -99.886
| | P99| 100ms| 0s | -100ms | -100.503
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 1ms| 0s | -1ms | -131.539
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 14ms| 16ms | 2ms | 13.931
| | P99| 89ms| 164ms | 75ms | 84.428
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 365ms| 377ms | 12ms | 3.290
| | P99| 983ms| 986ms | 3ms | 0.305
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 13ms | -7ms | -34.498
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 109ms| 98ms | -11ms | -10.071

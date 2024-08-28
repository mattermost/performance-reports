### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 2ms | 2ms | 614283.22
| UserAccessTokenStore.GetByToken | avg | 2ms | 11ms | 9ms | 397.98
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 4ms | 2ms | 101.39
| BotStore.Save | avg | 5ms | 9ms | 4ms | 74.90
| JobStore.Get | avg | 3ms | 5ms | 2ms | 70.58
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 12ms | 16ms | 4ms | 33.96
| ChannelStore.Save | avg | 14ms | 16ms | 2ms | 14.76
| StatusStore.SaveOrUpdate | avg | 15ms | 17ms | 2ms | 13.58
| UserStore.AutocompleteUsersInChannel | avg | 199ms | 201ms | 2ms | 1.01
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserAccessTokenStore.GetByToken | p99 | 5ms | 94ms | 89ms | 1797.38
| PostPriorityStore.GetForPost | p99 | 10ms | 46ms | 36ms | 366.73
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 21ms | 16ms | 323.23
| PostPersistentNotificationStore.Get | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.Get | p99 | 21ms | 88ms | 67ms | 313.08
| PostAcknowledgementStore.GetForPost | p99 | 16ms | 46ms | 30ms | 189.30
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| LinkMetadataStore.Save | p99 | 10ms | 20ms | 10ms | 103.79
| ChannelStore.GetPinnedPostCount | p99 | 10ms | 20ms | 10ms | 102.13
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 101.01
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 10ms | 5ms | 100.99
| FileInfoStore.GetByIds | p99 | 64ms | 127ms | 63ms | 99.17
| ChannelStore.GetMemberForPost | p99 | 30ms | 45ms | 15ms | 50.09
| FileInfoStore.Get | p99 | 7ms | 9ms | 2ms | 30.03
| UserStore.AutocompleteUsersInChannel | p99 | 585ms | 744ms | 159ms | 27.16
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 15ms | 18ms | 3ms | 19.95
| ChannelStore.GetFileCount | p99 | 69ms | 77ms | 8ms | 11.65
| UserStore.IsEmpty | p99 | 68ms | 75ms | 7ms | 10.28
| EmojiStore.GetByName | p99 | 45ms | 47ms | 2ms | 4.45
| StatusStore.SaveOrUpdate | p99 | 219ms | 228ms | 9ms | 4.12
| UserStore.Search | p99 | 381ms | 394ms | 13ms | 3.42
| StatusStore.Get | p99 | 81ms | 83ms | 2ms | 2.47
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetCountByStatusAndType | avg | 12ms | 3ms | -9ms | -75.66
| SessionStore.GetSessionsExpired | avg | 8ms | 2ms | -6ms | -72.42
| PostStore.GetPostsAfter | avg | 12ms | 4ms | -8ms | -64.06
| ChannelStore.GetChannelsByUser | avg | 27ms | 11ms | -16ms | -59.86
| StatusStore.GetByIds | avg | 4ms | 2ms | -2ms | -52.15
| JobStore.GetNewestJobByStatusesAndType | avg | 8ms | 4ms | -4ms | -47.71
| UserStore.GetByUsername | avg | 6ms | 3ms | -3ms | -47.69
| ChannelStore.GetSidebarCategory | avg | 9ms | 5ms | -4ms | -46.11
| ReactionStore.GetForPost | avg | 7ms | 4ms | -3ms | -41.81
| JobStore.UpdateStatusOptimistically | avg | 6ms | 4ms | -2ms | -36.36
| PostStore.SearchPostsForUser | avg | 92ms | 62ms | -30ms | -32.44
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 7ms | 5ms | -2ms | -30.68
| UserStore.Count | avg | 125ms | 87ms | -38ms | -30.42
| ChannelStore.GetMemberLastViewedAt | avg | 7ms | 5ms | -2ms | -29.16
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 7ms | 5ms | -2ms | -28.15
| UserStore.GetUnreadCount | avg | 7ms | 5ms | -2ms | -27.72
| TeamStore.GetChannelUnreadsForAllTeams | avg | 8ms | 6ms | -2ms | -26.28
| ChannelStore.Get | avg | 8ms | 6ms | -2ms | -25.93
| ThreadStore.GetTeamsUnreadForUser | avg | 8ms | 6ms | -2ms | -25.66
| ChannelStore.GetByName | avg | 9ms | 7ms | -2ms | -22.82
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 23ms | 18ms | -5ms | -21.81
| PostStore.GetPosts | avg | 10ms | 8ms | -2ms | -20.42
| ChannelStore.GetGuestCount | avg | 10ms | 8ms | -2ms | -19.86
| ChannelStore.GetAllChannelMembersForUser | avg | 11ms | 9ms | -2ms | -18.87
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 21ms | 17ms | -4ms | -18.71
| SessionStore.Get | avg | 11ms | 9ms | -2ms | -18.01
| PreferenceStore.GetAll | avg | 11ms | 9ms | -2ms | -17.81
| ChannelStore.CreateInitialSidebarCategories | avg | 28ms | 24ms | -4ms | -14.52
| ChannelStore.SaveMember | avg | 53ms | 46ms | -7ms | -13.30
| PostStore.AnalyticsPostCount | avg | 1.147s | 1.021s | -126ms | -10.99
| ChannelStore.AutocompleteInTeamForSearch | avg | 125ms | 116ms | -9ms | -7.19
| ChannelStore.UpdateSidebarCategories | avg | 34ms | 32ms | -2ms | -5.94
| ChannelStore.GetMemberCount | avg | 164ms | 156ms | -8ms | -4.87
| UserStore.GetAllProfilesInChannel | avg | 466ms | 451ms | -15ms | -3.22
| TeamStore.SaveMember | avg | 103ms | 101ms | -2ms | -1.95
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsAfter | p99 | 218ms | 5ms | -213ms | -97.49
| ReactionStore.GetForPost | p99 | 124ms | 9ms | -115ms | -92.96
| JobStore.GetCountByStatusAndType | p99 | 378ms | 38ms | -340ms | -90.07
| SessionStore.GetSessionsExpired | p99 | 48ms | 5ms | -43ms | -89.12
| ChannelStore.GetSidebarCategory | p99 | 86ms | 10ms | -76ms | -88.37
| StatusStore.GetByIds | p99 | 78ms | 14ms | -64ms | -81.79
| JobStore.UpdateStatusOptimistically | p99 | 44ms | 10ms | -34ms | -77.27
| ChannelStore.GetChannelUnread | p99 | 22ms | 5ms | -17ms | -77.06
| UserStore.GetByUsername | p99 | 113ms | 26ms | -87ms | -76.65
| JobStore.UpdateOptimistically | p99 | 76ms | 18ms | -58ms | -76.32
| JobStore.GetNewestJobByStatusesAndType | p99 | 213ms | 51ms | -162ms | -75.97
| PostStore.GetSingle | p99 | 30ms | 9ms | -21ms | -69.39
| LinkMetadataStore.Get | p99 | 35ms | 11ms | -24ms | -67.68
| UserStore.GetUnreadCount | p99 | 126ms | 45ms | -81ms | -64.48
| ChannelStore.GetChannelsByUser | p99 | 398ms | 153ms | -245ms | -61.56
| TeamStore.Get | p99 | 53ms | 24ms | -29ms | -54.98
| ThreadStore.GetMembershipForUser | p99 | 65ms | 30ms | -35ms | -53.67
| StatusStore.UpdateExpiredDNDStatuses | p99 | 22ms | 10ms | -12ms | -53.45
| JobStore.UpdateStatus | p99 | 38ms | 18ms | -20ms | -52.63
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 93ms | 45ms | -48ms | -51.43
| JobStore.Save | p99 | 18ms | 9ms | -9ms | -50.14
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 164ms | 84ms | -80ms | -48.70
| JobStore.GetAllByStatus | p99 | 78ms | 40ms | -38ms | -48.66
| UserStore.Count | p99 | 477ms | 248ms | -229ms | -47.96
| PluginStore.List | p99 | 41ms | 22ms | -19ms | -46.34
| ChannelStore.UpdateSidebarCategories | p99 | 93ms | 50ms | -43ms | -46.24
| ChannelStore.GetByName | p99 | 178ms | 97ms | -81ms | -45.44
| ChannelStore.GetMemberLastViewedAt | p99 | 153ms | 84ms | -69ms | -45.11
| PostStore.SearchPostsForUser | p99 | 2.057s | 1.135s | -922ms | -44.82
| ChannelStore.Get | p99 | 187ms | 110ms | -77ms | -41.18
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 154ms | 92ms | -62ms | -40.14
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 407ms | 244ms | -163ms | -40.02
| PostPersistentNotificationStore.GetSingle | p99 | 63ms | 38ms | -25ms | -39.89
| TeamStore.GetTeamsByUserId | p99 | 179ms | 108ms | -71ms | -39.65
| ThreadStore.GetTeamsUnreadForUser | p99 | 151ms | 92ms | -59ms | -39.18
| TeamStore.GetAllPage | p99 | 158ms | 97ms | -61ms | -38.64
| ChannelStore.SearchGroupChannels | p99 | 40ms | 25ms | -15ms | -37.51
| PostStore.GetEtag | p99 | 157ms | 100ms | -57ms | -36.41
| PostStore.Update | p99 | 40ms | 26ms | -14ms | -35.44
| SessionStore.Get | p99 | 183ms | 119ms | -64ms | -35.06
| DraftStore.Get | p99 | 24ms | 16ms | -8ms | -33.52
| UserStore.Get | p99 | 9ms | 6ms | -3ms | -32.15
| PostStore.GetPosts | p99 | 140ms | 95ms | -45ms | -32.04
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 135ms | 92ms | -43ms | -31.93
| ChannelStore.IncrementMentionCount | p99 | 16ms | 11ms | -5ms | -31.65
| ThreadStore.GetThreadsForUser | p99 | 73ms | 50ms | -23ms | -31.43
| UserTermsOfServiceStore.GetByUser | p99 | 162ms | 112ms | -50ms | -30.82
| ThreadStore.GetTotalThreads | p99 | 126ms | 89ms | -37ms | -29.36
| ChannelStore.SaveMember | p99 | 584ms | 413ms | -171ms | -29.30
| ChannelStore.CreateInitialSidebarCategories | p99 | 218ms | 156ms | -62ms | -28.49
| ChannelStore.GetMembersForUser | p99 | 92ms | 67ms | -25ms | -27.22
| ChannelStore.GetChannels | p99 | 107ms | 78ms | -29ms | -27.09
| TeamStore.GetTeamsForUser | p99 | 130ms | 95ms | -35ms | -26.90
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 9ms | -3ms | -25.75
| ThreadStore.GetTotalUnreadThreads | p99 | 121ms | 90ms | -31ms | -25.54
| GroupStore.GetGroups | p99 | 80ms | 60ms | -20ms | -25.12
| ThreadStore.GetTotalUnreadMentions | p99 | 120ms | 91ms | -29ms | -24.15
| PostStore.GetPostIdAfterTime | p99 | 21ms | 16ms | -5ms | -23.68
| ChannelStore.GetGuestCount | p99 | 209ms | 160ms | -49ms | -23.40
| ThreadStore.GetThreadFollowers | p99 | 57ms | 44ms | -13ms | -22.62
| PostStore.Get | p99 | 49ms | 38ms | -11ms | -22.58
| PostPriorityStore.GetForPosts | p99 | 62ms | 48ms | -14ms | -22.42
| DraftStore.GetDraftsForUser | p99 | 91ms | 71ms | -20ms | -22.02
| FileInfoStore.GetForPost | p99 | 15ms | 12ms | -3ms | -20.13
| UserStore.GetProfilesByUsernames | p99 | 47ms | 38ms | -9ms | -19.32
| SessionStore.Save | p99 | 148ms | 120ms | -28ms | -18.90
| ThreadStore.GetThreadForUser | p99 | 48ms | 39ms | -9ms | -18.77
| PostStore.GetPostsBefore | p99 | 59ms | 48ms | -11ms | -18.64
| UserStore.GetForLogin | p99 | 148ms | 122ms | -26ms | -17.61
| UserStore.UpdateUpdateAt | p99 | 23ms | 19ms | -4ms | -17.58
| PreferenceStore.GetAll | p99 | 200ms | 166ms | -34ms | -17.01
| ChannelStore.Save | p99 | 178ms | 148ms | -30ms | -16.85
| UserStore.Save | p99 | 179ms | 149ms | -30ms | -16.80
| FileInfoStore.AttachToPost | p99 | 18ms | 15ms | -3ms | -16.72
| SystemStore.GetByName | p99 | 18ms | 15ms | -3ms | -16.56
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 46ms | 39ms | -7ms | -15.26
| PostAcknowledgementStore.GetForPosts | p99 | 53ms | 45ms | -8ms | -15.04
| PluginStore.Delete | p99 | 14ms | 12ms | -2ms | -14.38
| ProductNoticesStore.View | p99 | 151ms | 131ms | -20ms | -13.27
| ThreadStore.GetThreadUnreadReplyCount | p99 | 15ms | 13ms | -2ms | -12.98
| PreferenceStore.Get | p99 | 49ms | 43ms | -6ms | -12.26
| ChannelStore.GetAllChannelMembersForUser | p99 | 53ms | 47ms | -6ms | -11.26
| GroupStore.GetByName | p99 | 124ms | 111ms | -13ms | -10.47
| UserStore.GetAllProfiles | p99 | 96ms | 86ms | -10ms | -10.38
| ChannelStore.AutocompleteInTeamForSearch | p99 | 543ms | 489ms | -54ms | -9.94
| ChannelStore.CreateDirectChannel | p99 | 575ms | 520ms | -55ms | -9.57
| AuditStore.Save | p99 | 23ms | 21ms | -2ms | -8.83
| ChannelStore.GetMember | p99 | 23ms | 21ms | -2ms | -8.80
| PluginStore.SetWithOptions | p99 | 24ms | 22ms | -2ms | -8.49
| BotStore.Get | p99 | 24ms | 22ms | -2ms | -8.43
| PreferenceStore.Save | p99 | 49ms | 45ms | -4ms | -8.22
| ChannelStore.GetPublicChannelsForTeam | p99 | 158ms | 145ms | -13ms | -8.22
| PostStore.GetPostsSince | p99 | 88ms | 83ms | -5ms | -5.68
| SessionStore.GetLRUSessions | p99 | 159ms | 154ms | -5ms | -3.15
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | avg | 10ms | 15ms | 5ms | 50.35
| logout | avg | 35ms | 38ms | 3ms | 8.57
| removeUserCustomStatus | avg | 123ms | 126ms | 3ms | 2.44
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | p99 | 81ms | 280ms | 199ms | 246.71
| addChannelMember | p99 | 690ms | 1.21s | 520ms | 75.35
| autocompleteUsers | p99 | 497ms | 665ms | 168ms | 33.78
| saveReaction | p99 | 179ms | 199ms | 20ms | 11.15
| searchUsers | p99 | 388ms | 407ms | 19ms | 4.90
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelsForUser | avg | 27ms | 11ms | -16ms | -59.48
| searchPostsInTeam | avg | 104ms | 69ms | -35ms | -33.68
| getUser | avg | 11ms | 8ms | -3ms | -27.27
| getChannelsForTeamForUser | avg | 8ms | 6ms | -2ms | -26.67
| getPreferences | avg | 12ms | 9ms | -3ms | -25.81
| getTeamsUnreadForUser | avg | 13ms | 10ms | -3ms | -23.93
| getChannelMember | avg | 22ms | 17ms | -5ms | -22.27
| getCategoriesForTeamForUser | avg | 23ms | 18ms | -5ms | -21.45
| followThreadByUser | avg | 15ms | 12ms | -3ms | -20.32
| getPostsForChannelAroundLastUnread | avg | 46ms | 38ms | -8ms | -17.23
| updateCategoriesForTeamForUser | avg | 54ms | 45ms | -9ms | -16.66
| getProfileImage | avg | 83ms | 75ms | -8ms | -9.69
| createPost | avg | 440ms | 404ms | -36ms | -8.18
| autocompleteChannelsForTeamForSearch | avg | 125ms | 116ms | -9ms | -7.19
| getPostsForChannel | avg | 30ms | 28ms | -2ms | -6.77
| addTeamMember | avg | 1.372s | 1.297s | -75ms | -5.47
| addChannelMember | avg | 230ms | 221ms | -9ms | -3.90
| createDirectChannel | avg | 235ms | 226ms | -9ms | -3.83
| uploadFileStream | avg | 387ms | 375ms | -12ms | -3.10
| createUser | avg | 139ms | 136ms | -3ms | -2.15
| createGroupChannel | avg | 361ms | 354ms | -7ms | -1.94
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateCategoriesForTeamForUser | p99 | 229ms | 50ms | -179ms | -78.17
| getChannelUnread | p99 | 22ms | 5ms | -17ms | -77.06
| getChannelsForUser | p99 | 398ms | 153ms | -245ms | -61.56
| createDirectChannel | p99 | 1.315s | 560ms | -755ms | -57.43
| searchPostsInTeam | p99 | 2.279s | 1.135s | -1.144s | -50.21
| getChannelsForTeamForUser | p99 | 165ms | 98ms | -67ms | -40.52
| getCategoriesForTeamForUser | p99 | 409ms | 244ms | -165ms | -40.32
| getTeamsForUser | p99 | 180ms | 108ms | -72ms | -40.04
| getTeamMember | p99 | 8ms | 5ms | -3ms | -37.62
| searchGroupChannels | p99 | 40ms | 25ms | -15ms | -37.51
| getPostsForChannelAroundLastUnread | p99 | 686ms | 436ms | -250ms | -36.46
| getChannelMember | p99 | 353ms | 238ms | -115ms | -32.60
| getAllTeams | p99 | 164ms | 115ms | -49ms | -29.94
| getUser | p99 | 201ms | 142ms | -59ms | -29.40
| viewChannel | p99 | 135ms | 99ms | -36ms | -26.73
| getClientConfig | p99 | 73ms | 54ms | -19ms | -26.01
| getTeamsUnreadForUser | p99 | 222ms | 165ms | -57ms | -25.64
| getChannelMembersForTeamForUser | p99 | 97ms | 73ms | -24ms | -24.65
| deleteDraft | p99 | 24ms | 18ms | -6ms | -24.57
| getThreadsForUser | p99 | 92ms | 70ms | -22ms | -23.98
| getDrafts | p99 | 91ms | 71ms | -20ms | -22.02
| getTeamMembersForUser | p99 | 142ms | 113ms | -29ms | -20.35
| getUsersByNames | p99 | 47ms | 38ms | -9ms | -19.25
| getPreferences | p99 | 205ms | 168ms | -37ms | -18.03
| getPostsForChannel | p99 | 295ms | 243ms | -52ms | -17.62
| upsertDraft | p99 | 24ms | 20ms | -4ms | -16.80
| createGroupChannel | p99 | 1.78s | 1.555s | -225ms | -12.64
| getPostThread | p99 | 43ms | 38ms | -5ms | -11.53
| patchPost | p99 | 290ms | 257ms | -33ms | -11.38
| getUsers | p99 | 90ms | 81ms | -9ms | -9.99
| autocompleteChannelsForTeamForSearch | p99 | 543ms | 489ms | -54ms | -9.94
| getPublicChannelsForTeam | p99 | 158ms | 145ms | -13ms | -8.22
| getProfileImage | p99 | 389ms | 358ms | -31ms | -7.98
| updateReadStateThreadByUser | p99 | 139ms | 133ms | -6ms | -4.31
| addTeamMember | p99 | 4.834s | 4.633s | -201ms | -4.16
| login | p99 | 484ms | 471ms | -13ms | -2.68
| createUser | p99 | 474ms | 462ms | -12ms | -2.53
| getChannelStats | p99 | 418ms | 410ms | -8ms | -1.92
| getFilePreview | p99 | 194ms | 191ms | -3ms | -1.55
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 4ms | -1ms | -22.182
| |  P99| 23ms| 21ms | -2ms | -8.832
| BotStore.Get |  Avg| 4ms| 3ms | -1ms | -26.102
| |  P99| 24ms| 22ms | -2ms | -8.430
| BotStore.Save |  Avg| 5ms| 9ms | 4ms | 74.900
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.689
| ChannelStore.Autocomplete |  Avg| 1.56s| 1.545s | -15ms | -0.962
| |  P99| 4.996s| 4.95s | -46ms | -0.921
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 125ms| 116ms | -9ms | -7.194
| |  P99| 543ms| 489ms | -54ms | -9.941
| ChannelStore.CreateDirectChannel |  Avg| 28ms| 29ms | 1ms | 3.535
| |  P99| 575ms| 520ms | -55ms | -9.567
| ChannelStore.CreateInitialSidebarCategories |  Avg| 28ms| 24ms | -4ms | -14.524
| |  P99| 218ms| 156ms | -62ms | -28.488
| ChannelStore.Get |  Avg| 8ms| 6ms | -2ms | -25.927
| |  P99| 187ms| 110ms | -77ms | -41.176
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 14ms| 13ms | -1ms | -7.028
| |  P99| 93ms| 45ms | -48ms | -51.426
| ChannelStore.GetAllChannelMembersForUser |  Avg| 11ms| 9ms | -2ms | -18.870
| |  P99| 53ms| 47ms | -6ms | -11.258
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 21ms| 17ms | -4ms | -18.713
| |  P99| 100ms| 99ms | -1ms | -1.001
| ChannelStore.GetByName |  Avg| 9ms| 7ms | -2ms | -22.817
| |  P99| 178ms| 97ms | -81ms | -45.441
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -32.508
| |  P99| 22ms| 5ms | -17ms | -77.056
| ChannelStore.GetChannels |  Avg| 6ms| 5ms | -1ms | -18.131
| |  P99| 107ms| 78ms | -29ms | -27.093
| ChannelStore.GetChannelsByUser |  Avg| 27ms| 11ms | -16ms | -59.858
| |  P99| 398ms| 153ms | -245ms | -61.556
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 4ms| 3ms | -1ms | -27.321
| |  P99| 46ms| 39ms | -7ms | -15.263
| ChannelStore.GetFileCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 77ms | 8ms | 11.648
| ChannelStore.GetGuestCount |  Avg| 10ms| 8ms | -2ms | -19.855
| |  P99| 209ms| 160ms | -49ms | -23.396
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.796
| ChannelStore.GetMemberCount |  Avg| 164ms| 156ms | -8ms | -4.873
| |  P99| 800ms| 801ms | 1ms | 0.125
| ChannelStore.GetMemberForPost |  Avg| 3ms| 4ms | 1ms | 29.144
| |  P99| 30ms| 45ms | 15ms | 50.086
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 5ms | -2ms | -29.157
| |  P99| 153ms| 84ms | -69ms | -45.113
| ChannelStore.GetMembersForUser |  Avg| 5ms| 4ms | -1ms | -18.719
| |  P99| 92ms| 67ms | -25ms | -27.223
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 102.131
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 158ms| 145ms | -13ms | -8.216
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 23ms| 18ms | -5ms | -21.814
| |  P99| 407ms| 244ms | -163ms | -40.020
| ChannelStore.GetSidebarCategory |  Avg| 9ms| 5ms | -4ms | -46.109
| |  P99| 86ms| 10ms | -76ms | -88.372
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 11ms | -5ms | -31.652
| ChannelStore.Save |  Avg| 14ms| 16ms | 2ms | 14.756
| |  P99| 178ms| 148ms | -30ms | -16.851
| ChannelStore.SaveMember |  Avg| 53ms| 46ms | -7ms | -13.298
| |  P99| 584ms| 413ms | -171ms | -29.298
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 3ms | -1ms | -27.846
| |  P99| 40ms| 25ms | -15ms | -37.508
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.763
| ChannelStore.UpdateSidebarCategories |  Avg| 34ms| 32ms | -2ms | -5.940
| |  P99| 93ms| 50ms | -43ms | -46.237
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -25.751
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 3ms | -1ms | -28.268
| |  P99| 10ms| 9ms | -1ms | -10.318
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 16ms | 4ms | 33.960
| |  P99| 25ms| 25ms | 0s | 0.000
| DraftStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 16ms | -8ms | -33.525
| DraftStore.GetDraftsForUser |  Avg| 5ms| 4ms | -1ms | -20.489
| |  P99| 91ms| 71ms | -20ms | -22.020
| DraftStore.Upsert |  Avg| 4ms| 3ms | -1ms | -28.326
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.447
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.722
| FileInfoStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 30.033
| FileInfoStore.GetByIds |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 64ms| 127ms | 63ms | 99.173
| FileInfoStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -20.126
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.120
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 7ms| 5ms | -2ms | -28.150
| |  P99| 164ms| 84ms | -80ms | -48.698
| GroupStore.GetByName |  Avg| 7ms| 6ms | -1ms | -14.981
| |  P99| 124ms| 111ms | -13ms | -10.475
| GroupStore.GetGroups |  Avg| 5ms| 4ms | -1ms | -20.637
| |  P99| 80ms| 60ms | -20ms | -25.120
| JobStore.Get |  Avg| 3ms| 5ms | 2ms | 70.579
| |  P99| 21ms| 88ms | 67ms | 313.084
| JobStore.GetAllByStatus |  Avg| 4ms| 3ms | -1ms | -23.713
| |  P99| 78ms| 40ms | -38ms | -48.655
| JobStore.GetCountByStatusAndType |  Avg| 12ms| 3ms | -9ms | -75.661
| |  P99| 378ms| 38ms | -340ms | -90.066
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 4ms | -4ms | -47.707
| |  P99| 213ms| 51ms | -162ms | -75.967
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -50.139
| JobStore.UpdateOptimistically |  Avg| 5ms| 4ms | -1ms | -19.886
| |  P99| 76ms| 18ms | -58ms | -76.316
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -21.857
| |  P99| 38ms| 18ms | -20ms | -52.632
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 4ms | -2ms | -36.358
| |  P99| 44ms| 10ms | -34ms | -77.273
| LinkMetadataStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 11ms | -24ms | -67.683
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 103.794
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.385
| PluginStore.List |  Avg| 4ms| 3ms | -1ms | -26.562
| |  P99| 41ms| 22ms | -19ms | -46.341
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.491
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 46ms | 30ms | 189.300
| PostAcknowledgementStore.GetForPosts |  Avg| 5ms| 4ms | -1ms | -20.385
| |  P99| 53ms| 45ms | -8ms | -15.038
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.GetSingle |  Avg| 4ms| 3ms | -1ms | -26.202
| |  P99| 63ms| 38ms | -25ms | -39.893
| PostPriorityStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 39.573
| |  P99| 10ms| 46ms | 36ms | 366.732
| PostPriorityStore.GetForPosts |  Avg| 5ms| 4ms | -1ms | -20.503
| |  P99| 62ms| 48ms | -14ms | -22.418
| PostStore.AnalyticsPostCount |  Avg| 1.147s| 1.021s | -126ms | -10.987
| |  P99| 2.485s| 2.485s | 0s | 0.000
| PostStore.Delete |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 7ms| 6ms | -1ms | -15.271
| |  P99| 49ms| 38ms | -11ms | -22.575
| PostStore.GetEtag |  Avg| 7ms| 6ms | -1ms | -14.904
| |  P99| 157ms| 100ms | -57ms | -36.414
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 2ms | -1ms | -38.818
| |  P99| 21ms| 16ms | -5ms | -23.684
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 10ms| 8ms | -2ms | -20.415
| |  P99| 140ms| 95ms | -45ms | -32.040
| PostStore.GetPostsAfter |  Avg| 12ms| 4ms | -8ms | -64.060
| |  P99| 218ms| 5ms | -213ms | -97.486
| PostStore.GetPostsBefore |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 59ms| 48ms | -11ms | -18.639
| PostStore.GetPostsByThread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.360
| PostStore.GetPostsSince |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 88ms| 83ms | -5ms | -5.682
| PostStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 9ms | -21ms | -69.388
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 92ms| 62ms | -30ms | -32.441
| |  P99| 2.057s| 1.135s | -922ms | -44.822
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 15.190
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 16ms| 15ms | -1ms | -6.400
| |  P99| 40ms| 26ms | -14ms | -35.441
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 4ms | 2ms | 101.392
| |  P99| 5ms| 10ms | 5ms | 100.993
| PreferenceStore.Get |  Avg| 4ms| 3ms | -1ms | -26.604
| |  P99| 49ms| 43ms | -6ms | -12.264
| PreferenceStore.GetAll |  Avg| 11ms| 9ms | -2ms | -17.809
| |  P99| 200ms| 166ms | -34ms | -17.013
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 49ms| 45ms | -4ms | -8.219
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 151ms| 131ms | -20ms | -13.271
| ReactionStore.GetForPost |  Avg| 7ms| 4ms | -3ms | -41.810
| |  P99| 124ms| 9ms | -115ms | -92.962
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 2ms | 2ms | 614283.224
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 11ms| 9ms | -2ms | -18.008
| |  P99| 183ms| 119ms | -64ms | -35.060
| SessionStore.GetLRUSessions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 159ms| 154ms | -5ms | -3.153
| SessionStore.GetSessionsExpired |  Avg| 8ms| 2ms | -6ms | -72.421
| |  P99| 48ms| 5ms | -43ms | -89.119
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 18ms | 3ms | 19.954
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 148ms| 120ms | -28ms | -18.900
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 81ms| 83ms | 2ms | 2.465
| StatusStore.GetByIds |  Avg| 4ms| 2ms | -2ms | -52.151
| |  P99| 78ms| 14ms | -64ms | -81.794
| StatusStore.SaveOrUpdate |  Avg| 15ms| 17ms | 2ms | 13.576
| |  P99| 219ms| 228ms | 9ms | 4.117
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.452
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.516
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.565
| TeamStore.Get |  Avg| 4ms| 3ms | -1ms | -27.138
| |  P99| 53ms| 24ms | -29ms | -54.981
| TeamStore.GetAllPage |  Avg| 7ms| 6ms | -1ms | -13.590
| |  P99| 158ms| 97ms | -61ms | -38.639
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 6ms | -2ms | -26.283
| |  P99| 154ms| 92ms | -62ms | -40.135
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 8ms| 7ms | -1ms | -11.953
| |  P99| 179ms| 108ms | -71ms | -39.647
| TeamStore.GetTeamsForUser |  Avg| 7ms| 6ms | -1ms | -15.076
| |  P99| 130ms| 95ms | -35ms | -26.902
| TeamStore.SaveMember |  Avg| 103ms| 101ms | -2ms | -1.949
| |  P99| 249ms| 248ms | -1ms | -0.401
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 4ms| 3ms | -1ms | -24.812
| |  P99| 65ms| 30ms | -35ms | -53.668
| ThreadStore.GetTeamsUnreadForUser |  Avg| 8ms| 6ms | -2ms | -25.656
| |  P99| 151ms| 92ms | -59ms | -39.175
| ThreadStore.GetThreadFollowers |  Avg| 4ms| 3ms | -1ms | -26.240
| |  P99| 57ms| 44ms | -13ms | -22.623
| ThreadStore.GetThreadForUser |  Avg| 6ms| 5ms | -1ms | -16.873
| |  P99| 48ms| 39ms | -9ms | -18.768
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -12.978
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 4ms | -1ms | -22.152
| |  P99| 73ms| 50ms | -23ms | -31.431
| ThreadStore.GetTotalThreads |  Avg| 6ms| 5ms | -1ms | -15.730
| |  P99| 126ms| 89ms | -37ms | -29.363
| ThreadStore.GetTotalUnreadMentions |  Avg| 6ms| 5ms | -1ms | -16.381
| |  P99| 120ms| 91ms | -29ms | -24.145
| ThreadStore.GetTotalUnreadThreads |  Avg| 6ms| 5ms | -1ms | -15.996
| |  P99| 121ms| 90ms | -31ms | -25.539
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 7ms| 5ms | -2ms | -30.684
| |  P99| 135ms| 92ms | -43ms | -31.933
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 11ms | 9ms | 397.980
| |  P99| 5ms| 94ms | 89ms | 1797.375
| UserStore.AutocompleteUsersInChannel |  Avg| 199ms| 201ms | 2ms | 1.007
| |  P99| 585ms| 744ms | 159ms | 27.164
| UserStore.Count |  Avg| 125ms| 87ms | -38ms | -30.415
| |  P99| 477ms| 248ms | -229ms | -47.958
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 6ms | -3ms | -32.146
| UserStore.GetAllProfiles |  Avg| 8ms| 7ms | -1ms | -13.279
| |  P99| 96ms| 86ms | -10ms | -10.377
| UserStore.GetAllProfilesInChannel |  Avg| 466ms| 451ms | -15ms | -3.218
| |  P99| 2.18s| 2.165s | -15ms | -0.688
| UserStore.GetByUsername |  Avg| 6ms| 3ms | -3ms | -47.690
| |  P99| 113ms| 26ms | -87ms | -76.652
| UserStore.GetForLogin |  Avg| 8ms| 7ms | -1ms | -13.332
| |  P99| 148ms| 122ms | -26ms | -17.610
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 38ms | -9ms | -19.324
| UserStore.GetUnreadCount |  Avg| 7ms| 5ms | -2ms | -27.721
| |  P99| 126ms| 45ms | -81ms | -64.484
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 68ms| 75ms | 7ms | 10.281
| UserStore.Save |  Avg| 69ms| 69ms | 0s | 0.000
| |  P99| 179ms| 149ms | -30ms | -16.796
| UserStore.Search |  Avg| 93ms| 93ms | 0s | 0.000
| |  P99| 381ms| 394ms | 13ms | 3.415
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.342
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 4ms | -1ms | -22.219
| |  P99| 23ms| 19ms | -4ms | -17.580
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 162ms| 112ms | -50ms | -30.817
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 230ms| 221ms | -9ms | -3.905
| | P99| 690ms| 1.21s | 520ms | 75.353
| addTeamMember | Avg| 1.372s| 1.297s | -75ms | -5.466
| | P99| 4.834s| 4.633s | -201ms | -4.158
| autocompleteChannelsForTeamForSearch | Avg| 125ms| 116ms | -9ms | -7.191
| | P99| 543ms| 489ms | -54ms | -9.941
| autocompleteUsers | Avg| 173ms| 172ms | -1ms | -0.578
| | P99| 497ms| 665ms | 168ms | 33.780
| createDirectChannel | Avg| 235ms| 226ms | -9ms | -3.828
| | P99| 1.315s| 560ms | -755ms | -57.429
| createGroupChannel | Avg| 361ms| 354ms | -7ms | -1.942
| | P99| 1.78s| 1.555s | -225ms | -12.639
| createPost | Avg| 440ms| 404ms | -36ms | -8.185
| | P99| 2.313s| 2.315s | 2ms | 0.086
| createUser | Avg| 139ms| 136ms | -3ms | -2.155
| | P99| 474ms| 462ms | -12ms | -2.533
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 18ms | -6ms | -24.573
| deletePost | Avg| 20ms| 21ms | 1ms | 4.940
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 15ms| 12ms | -3ms | -20.316
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 8ms| 7ms | -1ms | -12.233
| | P99| 164ms| 115ms | -49ms | -29.936
| getCategoriesForTeamForUser | Avg| 23ms| 18ms | -5ms | -21.455
| | P99| 409ms| 244ms | -165ms | -40.322
| getChannel | Avg| 10ms| 15ms | 5ms | 50.347
| | P99| 81ms| 280ms | 199ms | 246.707
| getChannelMember | Avg| 22ms| 17ms | -5ms | -22.269
| | P99| 353ms| 238ms | -115ms | -32.604
| getChannelMembersForTeamForUser | Avg| 6ms| 5ms | -1ms | -16.559
| | P99| 97ms| 73ms | -24ms | -24.655
| getChannelStats | Avg| 18ms| 17ms | -1ms | -5.619
| | P99| 418ms| 410ms | -8ms | -1.915
| getChannelUnread | Avg| 4ms| 3ms | -1ms | -23.844
| | P99| 22ms| 5ms | -17ms | -77.056
| getChannelsForTeamForUser | Avg| 8ms| 6ms | -2ms | -26.666
| | P99| 165ms| 98ms | -67ms | -40.516
| getChannelsForUser | Avg| 27ms| 11ms | -16ms | -59.484
| | P99| 398ms| 153ms | -245ms | -61.556
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 73ms| 54ms | -19ms | -26.007
| getDrafts | Avg| 5ms| 4ms | -1ms | -19.876
| | P99| 91ms| 71ms | -20ms | -22.020
| getFilePreview | Avg| 43ms| 43ms | 0s | 0.000
| | P99| 194ms| 191ms | -3ms | -1.548
| getFileThumbnail | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 93ms| 94ms | 1ms | 1.079
| getPostThread | Avg| 14ms| 13ms | -1ms | -7.187
| | P99| 43ms| 38ms | -5ms | -11.530
| getPostsForChannel | Avg| 30ms| 28ms | -2ms | -6.769
| | P99| 295ms| 243ms | -52ms | -17.622
| getPostsForChannelAroundLastUnread | Avg| 46ms| 38ms | -8ms | -17.227
| | P99| 686ms| 436ms | -250ms | -36.459
| getPreferences | Avg| 12ms| 9ms | -3ms | -25.808
| | P99| 205ms| 168ms | -37ms | -18.033
| getProfileImage | Avg| 83ms| 75ms | -8ms | -9.692
| | P99| 389ms| 358ms | -31ms | -7.978
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 158ms| 145ms | -13ms | -8.216
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -37.617
| getTeamMembersForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 142ms| 113ms | -29ms | -20.354
| getTeamsForUser | Avg| 8ms| 7ms | -1ms | -11.831
| | P99| 180ms| 108ms | -72ms | -40.042
| getTeamsUnreadForUser | Avg| 13ms| 10ms | -3ms | -23.929
| | P99| 222ms| 165ms | -57ms | -25.638
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 92ms| 70ms | -22ms | -23.977
| getUser | Avg| 11ms| 8ms | -3ms | -27.271
| | P99| 201ms| 142ms | -59ms | -29.396
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 8ms| 7ms | -1ms | -12.183
| | P99| 90ms| 81ms | -9ms | -9.995
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getUsersByNames | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 47ms| 38ms | -9ms | -19.251
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 84ms| 83ms | -1ms | -1.185
| | P99| 484ms| 471ms | -13ms | -2.685
| logout | Avg| 35ms| 38ms | 3ms | 8.574
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 34ms| 35ms | 1ms | 2.982
| | P99| 290ms| 257ms | -33ms | -11.378
| removeUserCustomStatus | Avg| 123ms| 126ms | 3ms | 2.437
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 13ms| 12ms | -1ms | -7.900
| | P99| 179ms| 199ms | 20ms | 11.153
| searchAllChannels | Avg| 1.56s| 1.545s | -15ms | -0.962
| | P99| 4.996s| 4.951s | -45ms | -0.901
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 40ms| 25ms | -15ms | -37.508
| searchPostsInTeam | Avg| 104ms| 69ms | -35ms | -33.677
| | P99| 2.279s| 1.135s | -1.144s | -50.208
| searchUsers | Avg| 95ms| 95ms | 0s | 0.000
| | P99| 388ms| 407ms | 19ms | 4.900
| setPostReminder | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 11ms | -1ms | -8.591
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 54ms| 45ms | -9ms | -16.658
| | P99| 229ms| 50ms | -179ms | -78.166
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 32ms| 31ms | -1ms | -3.110
| | P99| 139ms| 133ms | -6ms | -4.306
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 387ms| 375ms | -12ms | -3.104
| | P99| 997ms| 990ms | -7ms | -0.702
| upsertDraft | Avg| 5ms| 4ms | -1ms | -20.412
| | P99| 24ms| 20ms | -4ms | -16.797
| viewChannel | Avg| 15ms| 14ms | -1ms | -6.795
| | P99| 135ms| 99ms | -36ms | -26.733

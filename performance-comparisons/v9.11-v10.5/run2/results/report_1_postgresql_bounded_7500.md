### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 3ms | 3ms | 1141679.29
| PostStore.SearchPostsForUser | avg | 22ms | 31ms | 9ms | 40.73
| TeamStore.GetTotalMemberCount | avg | 26ms | 30ms | 4ms | 15.19
| TeamStore.GetActiveMemberCount | avg | 37ms | 39ms | 2ms | 5.47
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 21ms | 16ms | 323.23
| ChannelStore.AutocompleteInTeamForSearch | p99 | 98ms | 377ms | 279ms | 284.04
| ThreadStore.MarkAllAsReadByChannels | p99 | 8ms | 22ms | 14ms | 164.72
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 21ms | 12ms | 137.92
| TeamStore.GetMember | p99 | 5ms | 11ms | 6ms | 120.48
| PostStore.SearchPostsForUser | p99 | 285ms | 608ms | 323ms | 113.33
| PluginStore.List | p99 | 5ms | 9ms | 4ms | 80.81
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 9ms | 4ms | 80.79
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 9ms | 4ms | 80.78
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 45ms | 20ms | 80.47
| ReactionStore.GetForPost | p99 | 11ms | 18ms | 7ms | 64.14
| FileInfoStore.Save | p99 | 15ms | 20ms | 5ms | 33.66
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 8ms | 10ms | 2ms | 25.56
| ChannelStore.Save | p99 | 32ms | 40ms | 8ms | 25.19
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Get | avg | 3ms | 0s | -3ms | -116.23
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 10ms | 0s | -10ms | -101.42
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 1ms | -2ms | -64.93
| UserStore.GetProfilesInChannel | avg | 29ms | 13ms | -16ms | -54.82
| UserStore.GetMany | avg | 4ms | 2ms | -2ms | -49.93
| ChannelStore.GetTeamChannels | avg | 19ms | 11ms | -8ms | -43.21
| ChannelStore.GetAllChannelMembersForUser | avg | 5ms | 3ms | -2ms | -38.44
| StatusStore.SaveOrUpdate | avg | 17ms | 11ms | -6ms | -34.49
| ChannelStore.UpdateSidebarCategories | avg | 28ms | 21ms | -7ms | -25.24
| ChannelStore.AutocompleteInTeamForSearch | avg | 41ms | 36ms | -5ms | -12.13
| UserStore.GetAllProfilesInChannel | avg | 163ms | 147ms | -16ms | -9.80
| PostStore.AnalyticsPostCount | avg | 263ms | 260ms | -3ms | -1.14
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 25ms | 0s | -25ms | -101.12
| JobStore.Get | p99 | 18ms | 0s | -18ms | -100.28
| UserStore.GetProfilesInChannel | p99 | 241ms | 25ms | -216ms | -89.63
| JobStore.UpdateStatus | p99 | 38ms | 5ms | -33ms | -86.27
| JobStore.GetCountByStatusAndType | p99 | 38ms | 9ms | -29ms | -76.82
| SessionStore.Remove | p99 | 22ms | 5ms | -17ms | -75.71
| JobStore.Save | p99 | 18ms | 5ms | -13ms | -72.42
| JobStore.UpdateOptimistically | p99 | 18ms | 5ms | -13ms | -72.42
| ThreadStore.Get | p99 | 18ms | 6ms | -12ms | -68.00
| UserStore.GetByUsername | p99 | 15ms | 5ms | -10ms | -65.88
| UserStore.GetMany | p99 | 24ms | 9ms | -15ms | -63.83
| JobStore.GetNewestJobByStatusesAndType | p99 | 25ms | 10ms | -15ms | -58.82
| StatusStore.SaveOrUpdate | p99 | 399ms | 198ms | -201ms | -50.43
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -49.23
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.78
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -45.98
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 5ms | -4ms | -45.33
| UserStore.Update | p99 | 16ms | 9ms | -7ms | -45.01
| PostStore.GetPostReminderMetadata | p99 | 9ms | 5ms | -4ms | -43.75
| PostPersistentNotificationStore.Get | p99 | 9ms | 5ms | -4ms | -43.13
| FileInfoStore.GetByIds | p99 | 10ms | 6ms | -4ms | -40.94
| FileInfoStore.AttachToPost | p99 | 15ms | 9ms | -6ms | -40.59
| DraftStore.GetDraftsForUser | p99 | 20ms | 12ms | -8ms | -40.38
| ThreadStore.GetMembershipForUser | p99 | 13ms | 9ms | -4ms | -31.49
| SessionStore.GetLRUSessions | p99 | 19ms | 13ms | -6ms | -30.80
| PreferenceStore.Get | p99 | 14ms | 10ms | -4ms | -29.12
| UserStore.GetAllProfiles | p99 | 19ms | 14ms | -5ms | -26.70
| SystemStore.GetByName | p99 | 11ms | 8ms | -3ms | -26.14
| SessionStore.Get | p99 | 33ms | 25ms | -8ms | -24.27
| ThreadStore.GetThreadFollowers | p99 | 13ms | 10ms | -3ms | -23.68
| FileInfoStore.Get | p99 | 9ms | 7ms | -2ms | -23.47
| ChannelStore.IncrementMentionCount | p99 | 13ms | 10ms | -3ms | -23.45
| ChannelStore.GetMember | p99 | 17ms | 13ms | -4ms | -23.07
| ChannelStore.GetMemberLastViewedAt | p99 | 19ms | 15ms | -4ms | -21.45
| StatusStore.UpdateLastActivityAt | p99 | 9ms | 7ms | -2ms | -21.40
| UserStore.UpdateLastLogin | p99 | 19ms | 15ms | -4ms | -21.36
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 14ms | 11ms | -3ms | -20.70
| PostStore.GetPostIdAfterTime | p99 | 10ms | 8ms | -2ms | -20.57
| ChannelStore.CreateDirectChannel | p99 | 42ms | 34ms | -8ms | -18.84
| TeamStore.GetTeamsByUserId | p99 | 22ms | 18ms | -4ms | -18.55
| ThreadStore.GetThreadsForUser | p99 | 17ms | 14ms | -3ms | -17.64
| UserStore.GetProfileByIds | p99 | 12ms | 10ms | -2ms | -17.10
| StatusStore.Get | p99 | 18ms | 15ms | -3ms | -16.87
| ChannelStore.Get | p99 | 18ms | 15ms | -3ms | -16.58
| ThreadStore.MaintainMembership | p99 | 12ms | 10ms | -2ms | -16.42
| UserStore.UpdateUpdateAt | p99 | 19ms | 16ms | -3ms | -16.05
| PostStore.GetEtag | p99 | 19ms | 16ms | -3ms | -15.57
| ThreadStore.GetTotalThreads | p99 | 19ms | 16ms | -3ms | -15.45
| PostPriorityStore.GetForPost | p99 | 13ms | 11ms | -2ms | -15.04
| ChannelStore.GetChannelsByUser | p99 | 20ms | 17ms | -3ms | -14.93
| UserStore.GetForLogin | p99 | 21ms | 18ms | -3ms | -14.13
| UserStore.AutocompleteUsersInChannel | p99 | 176ms | 152ms | -24ms | -13.66
| ChannelStore.GetChannels | p99 | 15ms | 13ms | -2ms | -13.18
| PostAcknowledgementStore.GetForPost | p99 | 31ms | 27ms | -4ms | -13.11
| PreferenceStore.Save | p99 | 39ms | 34ms | -5ms | -12.90
| TeamStore.SaveMember | p99 | 65ms | 57ms | -8ms | -12.33
| GroupStore.GetGroups | p99 | 16ms | 14ms | -2ms | -12.18
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 107ms | 94ms | -13ms | -12.17
| ChannelStore.GetAllChannelMembersForUser | p99 | 25ms | 22ms | -3ms | -12.12
| ChannelStore.CreateInitialSidebarCategories | p99 | 50ms | 44ms | -6ms | -12.11
| PostStore.GetPostsBefore | p99 | 17ms | 15ms | -2ms | -11.64
| ChannelStore.GetMembersForUser | p99 | 17ms | 15ms | -2ms | -11.47
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 17ms | 15ms | -2ms | -11.45
| ThreadStore.GetTotalUnreadThreads | p99 | 19ms | 17ms | -2ms | -10.55
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 19ms | 17ms | -2ms | -10.45
| FileInfoStore.SetContent | p99 | 20ms | 18ms | -2ms | -10.18
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 20ms | 18ms | -2ms | -10.15
| ThreadStore.GetTotalUnreadMentions | p99 | 20ms | 18ms | -2ms | -9.98
| UserStore.GetUnreadCount | p99 | 20ms | 18ms | -2ms | -9.96
| TeamStore.GetAllPage | p99 | 20ms | 18ms | -2ms | -9.81
| JobStore.GetAllByStatus | p99 | 21ms | 19ms | -2ms | -9.56
| LinkMetadataStore.Save | p99 | 22ms | 20ms | -2ms | -9.28
| ThreadStore.GetTeamsUnreadForUser | p99 | 22ms | 20ms | -2ms | -9.03
| AuditStore.Save | p99 | 22ms | 20ms | -2ms | -8.96
| PreferenceStore.GetAll | p99 | 23ms | 21ms | -2ms | -8.85
| ChannelStore.GetGuestCount | p99 | 23ms | 21ms | -2ms | -8.69
| ProductNoticesStore.View | p99 | 95ms | 87ms | -8ms | -8.38
| ChannelStore.SaveMember | p99 | 88ms | 81ms | -7ms | -7.99
| UserStore.Search | p99 | 67ms | 62ms | -5ms | -7.52
| ChannelStore.GetMemberCount | p99 | 49ms | 46ms | -3ms | -6.16
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 47ms | -3ms | -6.04
| PostStore.GetPostsSince | p99 | 47ms | 45ms | -2ms | -4.29
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 49ms | 47ms | -2ms | -4.09
| UserStore.GetAllProfilesInChannel | p99 | 481ms | 467ms | -14ms | -2.91
| UserStore.Save | p99 | 184ms | 181ms | -3ms | -1.63
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 30ms | 41ms | 11ms | 36.15
| viewChannel | avg | 9ms | 11ms | 2ms | 22.56
| getPostsForChannel | avg | 23ms | 25ms | 2ms | 8.77
| uploadFileStream | avg | 451ms | 470ms | 19ms | 4.21
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 98ms | 377ms | 279ms | 284.04
| createChannel | p99 | 249ms | 485ms | 236ms | 94.97
| getTeamStats | p99 | 50ms | 97ms | 47ms | 94.47
| searchPostsInTeam | p99 | 357ms | 657ms | 300ms | 84.11
| getPublicChannelsForTeam | p99 | 25ms | 45ms | 20ms | 80.47
| viewChannel | p99 | 34ms | 38ms | 4ms | 11.94
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 3ms | 1ms | -2ms | -62.57
| getChannel | avg | 8ms | 5ms | -3ms | -39.21
| followThreadByUser | avg | 15ms | 10ms | -5ms | -33.54
| createPost | avg | 247ms | 169ms | -78ms | -31.58
| login | avg | 76ms | 53ms | -23ms | -30.23
| logout | avg | 36ms | 27ms | -9ms | -25.28
| patchPost | avg | 32ms | 24ms | -8ms | -25.17
| createChannel | avg | 205ms | 161ms | -44ms | -21.51
| updateCategoriesForTeamForUser | avg | 46ms | 39ms | -7ms | -15.18
| createUser | avg | 129ms | 111ms | -18ms | -13.93
| removeUserCustomStatus | avg | 133ms | 115ms | -18ms | -13.56
| deletePost | avg | 16ms | 14ms | -2ms | -12.44
| autocompleteChannelsForTeamForSearch | avg | 41ms | 36ms | -5ms | -12.11
| getProfileImage | avg | 102ms | 91ms | -11ms | -10.77
| addTeamMember | avg | 606ms | 548ms | -58ms | -9.57
| addChannelMember | avg | 195ms | 177ms | -18ms | -9.23
| createDirectChannel | avg | 210ms | 196ms | -14ms | -6.66
| createGroupChannel | avg | 310ms | 290ms | -20ms | -6.46
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 359ms | 82ms | -277ms | -77.21
| getChannel | p99 | 24ms | 10ms | -14ms | -57.30
| getTeamMember | p99 | 11ms | 5ms | -6ms | -52.67
| followThreadByUser | p99 | 48ms | 25ms | -23ms | -48.17
| login | p99 | 444ms | 239ms | -205ms | -46.22
| createUser | p99 | 440ms | 250ms | -190ms | -43.20
| getDrafts | p99 | 20ms | 12ms | -8ms | -40.38
| addTeamMember | p99 | 2.156s | 1.468s | -688ms | -31.91
| getPostsForChannelAroundLastUnread | p99 | 81ms | 56ms | -25ms | -30.88
| getClientConfig | p99 | 32ms | 23ms | -9ms | -28.21
| getChannelMember | p99 | 38ms | 28ms | -10ms | -26.64
| createPost | p99 | 951ms | 698ms | -253ms | -26.60
| autocompleteUsers | p99 | 152ms | 117ms | -35ms | -23.06
| getTeamsUnreadForUser | p99 | 31ms | 24ms | -7ms | -22.24
| getChannelsForTeamForUser | p99 | 16ms | 13ms | -3ms | -18.99
| getUsersByNames | p99 | 11ms | 9ms | -2ms | -18.39
| getChannelStats | p99 | 35ms | 29ms | -6ms | -17.18
| getChannelMembersForTeamForUser | p99 | 18ms | 15ms | -3ms | -16.71
| getChannelsForUser | p99 | 20ms | 17ms | -3ms | -14.81
| getTeamsForUser | p99 | 22ms | 19ms | -3ms | -13.69
| getUsers | p99 | 23ms | 20ms | -3ms | -13.10
| getChannelMembersForUser | p99 | 22ms | 20ms | -2ms | -9.27
| getTeamMembersForUser | p99 | 22ms | 20ms | -2ms | -9.27
| getThreadsForUser | p99 | 22ms | 20ms | -2ms | -9.24
| getAllTeams | p99 | 22ms | 20ms | -2ms | -9.13
| getUser | p99 | 24ms | 22ms | -2ms | -8.35
| uploadFileStream | p99 | 1.084s | 995ms | -89ms | -8.21
| updateCategoriesForTeamForUser | p99 | 96ms | 90ms | -6ms | -6.25
| searchUsers | p99 | 71ms | 67ms | -4ms | -5.64
| addChannelMember | p99 | 482ms | 457ms | -25ms | -5.18
| getCategoriesForTeamForUser | p99 | 50ms | 48ms | -2ms | -4.03
| getPostsForChannel | p99 | 201ms | 194ms | -7ms | -3.48
| getProfileImage | p99 | 485ms | 472ms | -13ms | -2.68
| getFileThumbnail | p99 | 93ms | 91ms | -2ms | -2.16
| logout | p99 | 96ms | 94ms | -2ms | -2.09
| getFilePreview | p99 | 98ms | 96ms | -2ms | -2.05
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.964
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.490
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 2ms | -1ms | -39.246
| |  P99| 14ms| 11ms | -3ms | -20.700
| ChannelStore.Autocomplete |  Avg| 34ms| 33ms | -1ms | -2.954
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 41ms| 36ms | -5ms | -12.131
| |  P99| 98ms| 377ms | 279ms | 284.042
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 16ms | -1ms | -5.858
| |  P99| 42ms| 34ms | -8ms | -18.845
| ChannelStore.CreateInitialSidebarCategories |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 50ms| 44ms | -6ms | -12.109
| ChannelStore.CreateSidebarCategory |  Avg| 16ms| 15ms | -1ms | -6.203
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.581
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 10ms| 0s | -10ms | -101.422
| |  P99| 25ms| 0s | -25ms | -101.122
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 3ms | -2ms | -38.441
| |  P99| 25ms| 22ms | -3ms | -12.118
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 16ms| 15ms | -1ms | -6.099
| |  P99| 107ms| 94ms | -13ms | -12.172
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 35ms | -1ms | -2.810
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.181
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 17ms | -3ms | -14.926
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.190
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.690
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 13ms | -4ms | -23.074
| ChannelStore.GetMemberCount |  Avg| 16ms| 15ms | -1ms | -6.303
| |  P99| 49ms| 46ms | -3ms | -6.164
| ChannelStore.GetMemberForPost |  Avg| 5ms| 4ms | -1ms | -22.114
| |  P99| 16ms| 15ms | -1ms | -6.267
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 2ms | -1ms | -39.946
| |  P99| 19ms| 15ms | -4ms | -21.454
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.474
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.675
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.901
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 14ms | 1ms | 7.602
| |  P99| 25ms| 45ms | 20ms | 80.471
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 15ms| 14ms | -1ms | -6.619
| |  P99| 49ms| 47ms | -2ms | -4.090
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 19ms| 11ms | -8ms | -43.209
| |  P99| 49ms| 25ms | -24ms | -49.231
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -23.455
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 32ms| 40ms | 8ms | 25.191
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 88ms| 81ms | -7ms | -7.986
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.721
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.163
| ChannelStore.UpdateSidebarCategories |  Avg| 28ms| 21ms | -7ms | -25.244
| |  P99| 50ms| 47ms | -3ms | -6.040
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 0s | -1ms | -191.415
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 3ms | 1ms | 41.526
| |  P99| 9ms| 21ms | 12ms | 137.919
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 3ms | 1ms | 46.526
| |  P99| 5ms| 9ms | 4ms | 80.778
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.579
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 12ms | -8ms | -40.381
| DraftStore.Upsert |  Avg| 3ms| 2ms | -1ms | -37.967
| |  P99| 11ms| 10ms | -1ms | -9.410
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.745
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 9ms | -6ms | -40.591
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -23.467
| FileInfoStore.GetByIds |  Avg| 3ms| 2ms | -1ms | -39.958
| |  P99| 10ms| 6ms | -4ms | -40.942
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 3ms | -1ms | -28.093
| |  P99| 15ms| 20ms | 5ms | 33.660
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.184
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.447
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.984
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.177
| JobStore.Get |  Avg| 3ms| 0s | -3ms | -116.234
| |  P99| 18ms| 0s | -18ms | -100.279
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.564
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -29.847
| |  P99| 38ms| 9ms | -29ms | -76.821
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -32.948
| |  P99| 25ms| 10ms | -15ms | -58.824
| JobStore.Save |  Avg| 3ms| 2ms | -1ms | -35.316
| |  P99| 18ms| 5ms | -13ms | -72.423
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -72.423
| JobStore.UpdateStatus |  Avg| 3ms| 2ms | -1ms | -29.726
| |  P99| 38ms| 5ms | -33ms | -86.275
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 2ms | -1ms | -35.327
| |  P99| 9ms| 5ms | -4ms | -45.326
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.424
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.280
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -11.867
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.168
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 27ms | -4ms | -13.114
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.784
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.127
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.900
| PostPriorityStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -39.390
| |  P99| 13ms| 11ms | -2ms | -15.039
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 263ms| 260ms | -3ms | -1.141
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 9ms| 8ms | -1ms | -10.618
| |  P99| 24ms| 23ms | -1ms | -4.107
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.875
| PostStore.GetEtag |  Avg| 3ms| 2ms | -1ms | -38.427
| |  P99| 19ms| 16ms | -3ms | -15.566
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.569
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.975
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.753
| PostStore.GetPostReminders |  Avg| 3ms| 2ms | -1ms | -32.652
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.544
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.981
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.639
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.295
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.061
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.806
| PostStore.SearchPostsForUser |  Avg| 22ms| 31ms | 9ms | 40.728
| |  P99| 285ms| 608ms | 323ms | 113.332
| PostStore.SetPostReminder |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 10ms| 9ms | -1ms | -9.814
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 2ms | -1ms | -39.563
| |  P99| 14ms| 10ms | -4ms | -29.118
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.847
| PreferenceStore.Save |  Avg| 6ms| 5ms | -1ms | -17.526
| |  P99| 39ms| 34ms | -5ms | -12.897
| ProductNoticesStore.ClearOldNotices |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 17ms| 16ms | -1ms | -6.050
| |  P99| 95ms| 87ms | -8ms | -8.384
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 18ms | 7ms | 64.144
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.792
| RoleStore.GetByNames |  Avg| 0s| 3ms | 3ms | 1141679.288
| |  P99| 5ms| 21ms | 16ms | 323.232
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 25ms | -8ms | -24.267
| SessionStore.GetLRUSessions |  Avg| 3ms| 2ms | -1ms | -37.406
| |  P99| 19ms| 13ms | -6ms | -30.798
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.558
| SessionStore.Remove |  Avg| 3ms| 2ms | -1ms | -31.361
| |  P99| 22ms| 5ms | -17ms | -75.714
| SessionStore.Save |  Avg| 6ms| 5ms | -1ms | -17.355
| |  P99| 24ms| 23ms | -1ms | -4.167
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.240
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.874
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.382
| StatusStore.SaveOrUpdate |  Avg| 17ms| 11ms | -6ms | -34.486
| |  P99| 399ms| 198ms | -201ms | -50.426
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.398
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 8ms | -3ms | -26.142
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 37ms| 39ms | 2ms | 5.469
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.808
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.146
| TeamStore.GetMember |  Avg| 1ms| 2ms | 1ms | 116.936
| |  P99| 5ms| 11ms | 6ms | 120.480
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -18.551
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.911
| TeamStore.GetTotalMemberCount |  Avg| 26ms| 30ms | 4ms | 15.189
| |  P99| 49ms| 50ms | 1ms | 2.030
| TeamStore.SaveMember |  Avg| 21ms| 20ms | -1ms | -4.824
| |  P99| 65ms| 57ms | -8ms | -12.328
| ThreadStore.Get |  Avg| 3ms| 2ms | -1ms | -39.297
| |  P99| 18ms| 6ms | -12ms | -68.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 9ms | -4ms | -31.491
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.028
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -23.680
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.636
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.447
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.977
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.548
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.447
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.422
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 22ms | 14ms | 164.717
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 1ms | -2ms | -64.927
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 2ms | -1ms | -38.802
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 38ms| 37ms | -1ms | -2.654
| |  P99| 176ms| 152ms | -24ms | -13.665
| UserStore.Count |  Avg| 10ms| 11ms | 1ms | 9.783
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.257
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 14ms | -5ms | -26.703
| UserStore.GetAllProfilesInChannel |  Avg| 163ms| 147ms | -16ms | -9.801
| |  P99| 481ms| 467ms | -14ms | -2.913
| UserStore.GetByUsername |  Avg| 3ms| 2ms | -1ms | -36.367
| |  P99| 15ms| 5ms | -10ms | -65.881
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.131
| UserStore.GetMany |  Avg| 4ms| 2ms | -2ms | -49.931
| |  P99| 24ms| 9ms | -15ms | -63.829
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.104
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.880
| UserStore.GetProfilesInChannel |  Avg| 29ms| 13ms | -16ms | -54.818
| |  P99| 241ms| 25ms | -216ms | -89.627
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.962
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.313
| UserStore.Save |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 184ms| 181ms | -3ms | -1.632
| UserStore.Search |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 67ms| 62ms | -5ms | -7.516
| UserStore.Update |  Avg| 5ms| 4ms | -1ms | -21.019
| |  P99| 16ms| 9ms | -7ms | -45.005
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.353
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 15ms | -4ms | -21.355
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.050
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 2ms | -1ms | -39.677
| |  P99| 19ms| 18ms | -1ms | -5.175
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 31ms| 31ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 195ms| 177ms | -18ms | -9.227
| | P99| 482ms| 457ms | -25ms | -5.184
| addTeamMember | Avg| 606ms| 548ms | -58ms | -9.566
| | P99| 2.156s| 1.468s | -688ms | -31.911
| autocompleteChannelsForTeamForSearch | Avg| 41ms| 36ms | -5ms | -12.112
| | P99| 98ms| 377ms | 279ms | 284.042
| autocompleteUsers | Avg| 32ms| 31ms | -1ms | -3.151
| | P99| 152ms| 117ms | -35ms | -23.059
| createCategoryForTeamForUser | Avg| 19ms| 18ms | -1ms | -5.361
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 205ms| 161ms | -44ms | -21.508
| | P99| 249ms| 485ms | 236ms | 94.970
| createDirectChannel | Avg| 210ms| 196ms | -14ms | -6.659
| | P99| 490ms| 488ms | -2ms | -0.408
| createGroupChannel | Avg| 310ms| 290ms | -20ms | -6.460
| | P99| 497ms| 497ms | 0s | 0.000
| createPost | Avg| 247ms| 169ms | -78ms | -31.575
| | P99| 951ms| 698ms | -253ms | -26.603
| createUser | Avg| 129ms| 111ms | -18ms | -13.933
| | P99| 440ms| 250ms | -190ms | -43.204
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 16ms| 14ms | -2ms | -12.442
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 15ms| 10ms | -5ms | -33.544
| | P99| 48ms| 25ms | -23ms | -48.169
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.127
| getCategoriesForTeamForUser | Avg| 16ms| 15ms | -1ms | -6.424
| | P99| 50ms| 48ms | -2ms | -4.029
| getChannel | Avg| 8ms| 5ms | -3ms | -39.213
| | P99| 24ms| 10ms | -14ms | -57.300
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 38ms| 28ms | -10ms | -26.639
| getChannelMembers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 15ms | -3ms | -16.713
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.269
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 35ms| 29ms | -6ms | -17.178
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.226
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 13ms | -3ms | -18.994
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 17ms | -3ms | -14.813
| getClientConfig | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 32ms| 23ms | -9ms | -28.205
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 12ms | -8ms | -40.381
| getFilePreview | Avg| 40ms| 39ms | -1ms | -2.528
| | P99| 98ms| 96ms | -2ms | -2.048
| getFileThumbnail | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 93ms| 91ms | -2ms | -2.156
| getPostThread | Avg| 12ms| 13ms | 1ms | 8.369
| | P99| 35ms| 36ms | 1ms | 2.838
| getPostsForChannel | Avg| 23ms| 25ms | 2ms | 8.765
| | P99| 201ms| 194ms | -7ms | -3.476
| getPostsForChannelAroundLastUnread | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 81ms| 56ms | -25ms | -30.881
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.374
| getProfileImage | Avg| 102ms| 91ms | -11ms | -10.774
| | P99| 485ms| 472ms | -13ms | -2.683
| getPublicChannelsForTeam | Avg| 14ms| 15ms | 1ms | 7.098
| | P99| 25ms| 45ms | 20ms | 80.471
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 11ms| 5ms | -6ms | -52.674
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.268
| getTeamStats | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 50ms| 97ms | 47ms | 94.472
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 19ms | -3ms | -13.688
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 31ms| 24ms | -7ms | -22.243
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.241
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.345
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 3ms | -1ms | -27.733
| | P99| 23ms| 20ms | -3ms | -13.098
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 9ms | -2ms | -18.391
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -9.689
| login | Avg| 76ms| 53ms | -23ms | -30.233
| | P99| 444ms| 239ms | -205ms | -46.218
| logout | Avg| 36ms| 27ms | -9ms | -25.276
| | P99| 96ms| 94ms | -2ms | -2.089
| patchPost | Avg| 32ms| 24ms | -8ms | -25.175
| | P99| 359ms| 82ms | -277ms | -77.214
| removeUserCustomStatus | Avg| 133ms| 115ms | -18ms | -13.561
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 37ms| 36ms | -1ms | -2.674
| searchAllChannels | Avg| 34ms| 33ms | -1ms | -2.936
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.721
| searchPostsInTeam | Avg| 30ms| 41ms | 11ms | 36.152
| | P99| 357ms| 657ms | 300ms | 84.112
| searchUsers | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 71ms| 67ms | -4ms | -5.639
| setPostReminder | Avg| 16ms| 15ms | -1ms | -6.255
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 46ms| 39ms | -7ms | -15.183
| | P99| 96ms| 90ms | -6ms | -6.250
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 1ms | -2ms | -62.566
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 97ms| 96ms | -1ms | -1.031
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 451ms| 470ms | 19ms | 4.210
| | P99| 1.084s| 995ms | -89ms | -8.213
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 15ms | -1ms | -6.303
| viewChannel | Avg| 9ms| 11ms | 2ms | 22.558
| | P99| 34ms| 38ms | 4ms | 11.939

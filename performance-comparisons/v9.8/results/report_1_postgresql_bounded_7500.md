### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 15ms | 13ms | 599.41
| ChannelStore.AutocompleteInTeamForSearch | avg | 19ms | 64ms | 45ms | 239.47
| StatusStore.SaveOrUpdate | avg | 14ms | 39ms | 25ms | 174.81
| ChannelStore.SearchGroupChannels | avg | 5ms | 13ms | 8ms | 172.10
| PostPersistentNotificationStore.Get | avg | 2ms | 5ms | 3ms | 130.30
| UserStore.GetMany | avg | 2ms | 4ms | 2ms | 104.81
| ChannelStore.CreateSidebarCategory | avg | 24ms | 44ms | 20ms | 84.74
| ChannelStore.CreateInitialSidebarCategories | avg | 26ms | 48ms | 22ms | 84.35
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 19ms | 35ms | 16ms | 82.93
| ChannelStore.GetSidebarCategory | avg | 11ms | 18ms | 7ms | 66.64
| ChannelStore.UpdateSidebarCategories | avg | 60ms | 90ms | 30ms | 49.66
| ChannelStore.AnalyticsTypeCount | avg | 8ms | 10ms | 2ms | 26.23
| ChannelStore.CreateDirectChannel | avg | 24ms | 26ms | 2ms | 8.49
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 71ms | 3.234s | 3.163s | 4470.58
| PostStore.AnalyticsPostCount | p99 | 5ms | 25ms | 20ms | 403.70
| UserStore.GetMany | p99 | 5ms | 23ms | 18ms | 363.64
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 21ms | 16ms | 323.23
| LinkMetadataStore.Save | p99 | 7ms | 23ms | 16ms | 235.30
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 25ms | 15ms | 150.79
| PostStore.GetPostReminderMetadata | p99 | 9ms | 22ms | 13ms | 146.62
| JobStore.Save | p99 | 8ms | 19ms | 11ms | 139.24
| ChannelStore.GetChannelUnread | p99 | 8ms | 19ms | 11ms | 130.18
| JobStore.UpdateStatusOptimistically | p99 | 19ms | 39ms | 20ms | 106.95
| PostPersistentNotificationStore.Get | p99 | 21ms | 43ms | 22ms | 104.27
| ComplianceStore.MessageExport | p99 | 19ms | 39ms | 20ms | 103.23
| JobStore.Get | p99 | 10ms | 20ms | 10ms | 101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 10ms | 5ms | 101.01
| StatusStore.SaveOrUpdate | p99 | 383ms | 757ms | 374ms | 97.67
| ChannelStore.CreateDirectChannel | p99 | 115ms | 190ms | 75ms | 65.22
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 44ms | 61ms | 17ms | 38.86
| PluginStore.List | p99 | 18ms | 22ms | 4ms | 21.92
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 142ms | 173ms | 31ms | 21.86
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 97ms | 116ms | 19ms | 19.62
| UserStore.AutocompleteUsersInChannel | p99 | 294ms | 342ms | 48ms | 16.33
| ChannelStore.GetSidebarCategory | p99 | 44ms | 50ms | 6ms | 13.79
| ThreadStore.GetThreadForUser | p99 | 35ms | 39ms | 4ms | 11.56
| ChannelStore.GetAllChannelMembersForUser | p99 | 28ms | 31ms | 3ms | 10.63
| ThreadStore.GetThreadFollowers | p99 | 21ms | 23ms | 2ms | 9.49
| EmojiStore.GetByName | p99 | 21ms | 23ms | 2ms | 9.42
| ThreadStore.GetMembershipForUser | p99 | 21ms | 23ms | 2ms | 9.32
| ChannelStore.CreateInitialSidebarCategories | p99 | 204ms | 221ms | 17ms | 8.34
| ThreadStore.MaintainMembership | p99 | 38ms | 40ms | 2ms | 5.21
| ChannelStore.GetGuestCount | p99 | 41ms | 43ms | 2ms | 4.91
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 204ms | 210ms | 6ms | 2.94
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -130.36
| ChannelStore.GetMemberCountsByGroup | avg | 6ms | 0s | -6ms | -106.65
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 0s | -4ms | -97.94
| RetentionPolicyStore.GetCount | avg | 5ms | 1ms | -4ms | -83.64
| UserStore.GetProfilesInChannel | avg | 163ms | 30ms | -133ms | -81.69
| DraftStore.GetDraftsForUser | avg | 12ms | 3ms | -9ms | -72.38
| StatusStore.UpdateExpiredDNDStatuses | avg | 5ms | 2ms | -3ms | -65.22
| PostPriorityStore.GetForPost | avg | 4ms | 2ms | -2ms | -53.81
| BotStore.Get | avg | 8ms | 4ms | -4ms | -47.69
| UserAccessTokenStore.GetByToken | avg | 4ms | 2ms | -2ms | -47.63
| SessionStore.GetSessionsExpired | avg | 4ms | 2ms | -2ms | -47.60
| ChannelStore.GetMembersForUserWithPagination | avg | 19ms | 13ms | -6ms | -31.86
| PostStore.SearchPostsForUser | avg | 180ms | 133ms | -47ms | -26.07
| TeamStore.GetActiveMemberCount | avg | 59ms | 52ms | -7ms | -11.90
| UserStore.AutocompleteUsersInChannel | avg | 49ms | 47ms | -2ms | -4.12
| UserStore.GetAllProfilesInChannel | avg | 266ms | 260ms | -6ms | -2.26
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 55ms | 0s | -55ms | -100.15
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 5ms | -41ms | -89.62
| ThreadStore.Get | p99 | 64ms | 8ms | -56ms | -87.49
| DraftStore.GetDraftsForUser | p99 | 25ms | 5ms | -20ms | -80.48
| UserStore.GetProfilesInChannel | p99 | 248ms | 50ms | -198ms | -79.71
| SessionStore.GetSessionsExpired | p99 | 24ms | 5ms | -19ms | -78.35
| RetentionPolicyStore.GetCount | p99 | 24ms | 5ms | -19ms | -77.87
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 22ms | 5ms | -17ms | -76.75
| PostStore.GetPostsAfter | p99 | 20ms | 5ms | -15ms | -74.81
| BotStore.Get | p99 | 91ms | 24ms | -67ms | -74.03
| ChannelStore.GetMembersForUserWithPagination | p99 | 83ms | 25ms | -58ms | -70.09
| UserStore.Update | p99 | 65ms | 22ms | -43ms | -66.50
| PreferenceStore.DeleteCategoryAndName | p99 | 22ms | 9ms | -13ms | -58.69
| JobStore.UpdateOptimistically | p99 | 21ms | 10ms | -11ms | -53.56
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| PostAcknowledgementStore.GetForPost | p99 | 55ms | 26ms | -29ms | -52.73
| ClusterDiscoveryStore.SetLastPingAt | p99 | 43ms | 21ms | -22ms | -50.58
| UserStore.GetByUsername | p99 | 40ms | 20ms | -20ms | -50.31
| PostPriorityStore.GetForPost | p99 | 46ms | 26ms | -20ms | -43.48
| TeamStore.GetMember | p99 | 16ms | 10ms | -6ms | -37.15
| FileInfoStore.SetContent | p99 | 69ms | 45ms | -24ms | -34.91
| ThreadStore.UpdateMembership | p99 | 18ms | 13ms | -5ms | -28.55
| JobStore.GetNewestJobByStatusesAndType | p99 | 9ms | 7ms | -2ms | -21.22
| JobStore.UpdateStatus | p99 | 22ms | 18ms | -4ms | -18.31
| FileInfoStore.Get | p99 | 17ms | 14ms | -3ms | -17.31
| ThreadStore.MarkAsRead | p99 | 18ms | 15ms | -3ms | -16.90
| PostStore.GetSingle | p99 | 18ms | 15ms | -3ms | -16.83
| StatusStore.Get | p99 | 36ms | 30ms | -6ms | -16.72
| ChannelStore.GetChannelsByUser | p99 | 25ms | 21ms | -4ms | -16.10
| UserStore.UpdateUpdateAt | p99 | 31ms | 26ms | -5ms | -15.91
| PostStore.Update | p99 | 83ms | 70ms | -13ms | -15.69
| TeamStore.SaveMember | p99 | 155ms | 131ms | -24ms | -15.47
| ChannelStore.Save | p99 | 140ms | 119ms | -21ms | -14.95
| SystemStore.GetByName | p99 | 35ms | 30ms | -5ms | -14.46
| ChannelStore.Get | p99 | 28ms | 24ms | -4ms | -14.36
| ReactionStore.GetForPost | p99 | 21ms | 18ms | -3ms | -14.36
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 28ms | 24ms | -4ms | -14.20
| ThreadStore.GetThreadsForUser | p99 | 29ms | 25ms | -4ms | -13.87
| UserStore.Get | p99 | 22ms | 19ms | -3ms | -13.53
| FileInfoStore.GetForPost | p99 | 15ms | 13ms | -2ms | -13.49
| UserStore.Count | p99 | 46ms | 40ms | -6ms | -13.11
| UserAccessTokenStore.GetByToken | p99 | 24ms | 21ms | -3ms | -12.68
| PostStore.GetEtag | p99 | 35ms | 31ms | -4ms | -11.58
| ChannelStore.GetMember | p99 | 35ms | 31ms | -4ms | -11.43
| ChannelStore.GetPublicChannelsForTeam | p99 | 46ms | 41ms | -5ms | -10.94
| SessionStore.Get | p99 | 73ms | 65ms | -8ms | -10.94
| PostStore.GetPostIdAfterTime | p99 | 28ms | 25ms | -3ms | -10.69
| PluginStore.SetWithOptions | p99 | 48ms | 43ms | -5ms | -10.50
| LinkMetadataStore.Get | p99 | 19ms | 17ms | -2ms | -10.42
| TeamStore.Get | p99 | 19ms | 17ms | -2ms | -10.38
| ChannelStore.GetFileCount | p99 | 24ms | 22ms | -2ms | -8.36
| ChannelStore.IncrementMentionCount | p99 | 26ms | 24ms | -2ms | -7.81
| TeamStore.GetTeamsForUser | p99 | 38ms | 35ms | -3ms | -7.80
| SessionStore.Save | p99 | 53ms | 49ms | -4ms | -7.57
| ThreadStore.GetTeamsUnreadForUser | p99 | 40ms | 37ms | -3ms | -7.56
| UserStore.GetProfileByIds | p99 | 28ms | 26ms | -2ms | -7.12
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 31ms | 29ms | -2ms | -6.49
| WebhookStore.GetOutgoingByTeam | p99 | 46ms | 43ms | -3ms | -6.48
| PreferenceStore.Save | p99 | 96ms | 90ms | -6ms | -6.27
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 32ms | 30ms | -2ms | -6.18
| UserTermsOfServiceStore.GetByUser | p99 | 34ms | 32ms | -2ms | -5.82
| FileInfoStore.Save | p99 | 37ms | 35ms | -2ms | -5.40
| UserStore.UpdateFailedPasswordAttempts | p99 | 40ms | 38ms | -2ms | -4.98
| ChannelStore.GetByName | p99 | 46ms | 44ms | -2ms | -4.33
| ChannelStore.GetTeamChannels | p99 | 49ms | 47ms | -2ms | -4.12
| PostStore.SearchPostsForUser | p99 | 2.33s | 2.244s | -86ms | -3.69
| PostStore.Save | p99 | 82ms | 79ms | -3ms | -3.67
| ProductNoticesStore.View | p99 | 312ms | 306ms | -6ms | -1.92
| UserStore.GetAllProfilesInChannel | p99 | 937ms | 922ms | -15ms | -1.60
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 19ms | 64ms | 45ms | 238.67
| getRolesByNames | avg | 2ms | 6ms | 4ms | 191.72
| searchGroupChannels | avg | 5ms | 13ms | 8ms | 168.82
| createCategoryForTeamForUser | avg | 26ms | 46ms | 20ms | 78.30
| getCategoriesForTeamForUser | avg | 20ms | 35ms | 15ms | 76.30
| upsertDraft | avg | 4ms | 6ms | 2ms | 50.70
| updateCategoriesForTeamForUser | avg | 88ms | 122ms | 34ms | 38.65
| createChannel | avg | 252ms | 288ms | 36ms | 14.30
| removeUserCustomStatus | avg | 174ms | 184ms | 10ms | 5.74
| addTeamMember | avg | 903ms | 926ms | 23ms | 2.55
| createDirectChannel | avg | 257ms | 262ms | 5ms | 1.95
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 71ms | 3.234s | 3.163s | 4470.58
| deleteDraft | p99 | 5ms | 10ms | 5ms | 101.01
| getCategoriesForTeamForUser | p99 | 98ms | 132ms | 34ms | 34.56
| autocompleteUsers | p99 | 198ms | 255ms | 57ms | 28.83
| getTeamMember | p99 | 24ms | 26ms | 2ms | 8.37
| unfollowThreadByUser | p99 | 72ms | 77ms | 5ms | 6.90
| saveReaction | p99 | 78ms | 80ms | 2ms | 2.56
| createPost | p99 | 1.892s | 1.93s | 38ms | 2.01
| uploadFileStream | p99 | 994ms | 1.012s | 18ms | 1.81
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 7ms | 0s | -7ms | -106.69
| getDrafts | avg | 13ms | 0s | -13ms | -103.99
| updateReadStateAllThreadsByUser | avg | 4ms | 0s | -4ms | -96.01
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -93.01
| patchPost | avg | 78ms | 35ms | -43ms | -55.08
| deleteDraft | avg | 4ms | 2ms | -2ms | -49.61
| searchPostsInTeam | avg | 192ms | 140ms | -52ms | -27.02
| getUsers | avg | 8ms | 6ms | -2ms | -26.12
| deletePost | avg | 22ms | 19ms | -3ms | -13.83
| getAnalytics | avg | 26ms | 23ms | -3ms | -11.75
| getTeamStats | avg | 60ms | 53ms | -7ms | -11.72
| logout | avg | 60ms | 54ms | -6ms | -10.06
| createGroupChannel | avg | 379ms | 358ms | -21ms | -5.54
| login | avg | 80ms | 77ms | -3ms | -3.75
| createPost | avg | 356ms | 343ms | -13ms | -3.65
| createUser | avg | 148ms | 143ms | -5ms | -3.38
| getProfileImage | avg | 94ms | 91ms | -3ms | -3.19
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getSelfHostedProducts | p99 | 5ms | 0s | -5ms | -100.94
| getDrafts | p99 | 25ms | 0s | -25ms | -100.60
| channelMemberCountsByGroup | p99 | 62ms | 0s | -62ms | -100.58
| getRolesByNames | p99 | 24ms | 10ms | -14ms | -58.09
| logout | p99 | 233ms | 99ms | -134ms | -57.39
| patchPost | p99 | 495ms | 243ms | -252ms | -50.91
| deletePost | p99 | 48ms | 25ms | -23ms | -47.50
| getChannel | p99 | 58ms | 31ms | -27ms | -46.36
| getUsers | p99 | 99ms | 57ms | -42ms | -42.29
| addChannelMember | p99 | 752ms | 498ms | -254ms | -33.79
| createUser | p99 | 619ms | 496ms | -123ms | -19.88
| createDirectChannel | p99 | 582ms | 496ms | -86ms | -14.76
| getPublicChannelsForTeam | p99 | 48ms | 41ms | -7ms | -14.64
| updateReadStateThreadByUser | p99 | 195ms | 171ms | -24ms | -12.31
| getUser | p99 | 68ms | 60ms | -8ms | -11.76
| getThreadsForUser | p99 | 38ms | 34ms | -4ms | -10.59
| getClientConfig | p99 | 92ms | 83ms | -9ms | -9.79
| getChannelMembersForTeamForUser | p99 | 33ms | 30ms | -3ms | -9.05
| getChannelsForTeamForUser | p99 | 36ms | 33ms | -3ms | -8.36
| getPostThread | p99 | 86ms | 79ms | -7ms | -8.18
| updateCategoriesForTeamForUser | p99 | 462ms | 427ms | -35ms | -7.57
| viewChannel | p99 | 86ms | 81ms | -5ms | -5.78
| getChannelMember | p99 | 88ms | 83ms | -5ms | -5.67
| getTeamsUnreadForUser | p99 | 53ms | 50ms | -3ms | -5.64
| login | p99 | 479ms | 453ms | -26ms | -5.42
| getAllTeams | p99 | 43ms | 41ms | -2ms | -4.62
| getProfileImage | p99 | 483ms | 461ms | -22ms | -4.56
| getFilePreview | p99 | 112ms | 107ms | -5ms | -4.47
| getTeamMembersForUser | p99 | 48ms | 46ms | -2ms | -4.17
| searchPostsInTeam | p99 | 2.353s | 2.297s | -56ms | -2.38
| createGroupChannel | p99 | 968ms | 954ms | -14ms | -1.45
| getChannelsForUser | p99 | 211ms | 208ms | -3ms | -1.42
| getPostsForChannel | p99 | 225ms | 222ms | -3ms | -1.34
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 38ms | -1ms | -2.567
| BotStore.Get |  Avg| 8ms| 4ms | -4ms | -47.690
| |  P99| 91ms| 24ms | -67ms | -74.033
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 75ms| 74ms | -1ms | -1.328
| |  P99| 142ms| 173ms | 31ms | 21.860
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 8ms| 10ms | 2ms | 26.226
| |  P99| 10ms| 25ms | 15ms | 150.787
| ChannelStore.Autocomplete |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 19ms| 64ms | 45ms | 239.468
| |  P99| 71ms| 3.234s | 3.163s | 4470.576
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 26ms | 2ms | 8.488
| |  P99| 115ms| 190ms | 75ms | 65.217
| ChannelStore.CreateInitialSidebarCategories |  Avg| 26ms| 48ms | 22ms | 84.347
| |  P99| 204ms| 221ms | 17ms | 8.345
| ChannelStore.CreateSidebarCategory |  Avg| 24ms| 44ms | 20ms | 84.745
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.364
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 14ms| 13ms | -1ms | -7.235
| |  P99| 44ms| 61ms | 17ms | 38.857
| ChannelStore.GetAllChannelMembersForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 28ms| 31ms | 3ms | 10.627
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 21ms| 20ms | -1ms | -4.707
| |  P99| 204ms| 210ms | 6ms | 2.944
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 44ms | -2ms | -4.332
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 19ms | 11ms | 130.181
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.002
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 21ms | -4ms | -16.096
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.370
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.363
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.912
| ChannelStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 31ms | -4ms | -11.426
| ChannelStore.GetMemberCount |  Avg| 22ms| 23ms | 1ms | 4.534
| |  P99| 84ms| 85ms | 1ms | 1.187
| ChannelStore.GetMemberCountsByGroup |  Avg| 6ms| 0s | -6ms | -106.655
| |  P99| 55ms| 0s | -55ms | -100.152
| ChannelStore.GetMemberForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 33ms | 1ms | 3.159
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 26ms | -1ms | -3.675
| ChannelStore.GetMembersForUserWithPagination |  Avg| 19ms| 13ms | -6ms | -31.855
| |  P99| 83ms| 25ms | -58ms | -70.089
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.531
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 46ms| 41ms | -5ms | -10.943
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 19ms| 35ms | 16ms | 82.932
| |  P99| 97ms| 116ms | 19ms | 19.619
| ChannelStore.GetSidebarCategory |  Avg| 11ms| 18ms | 7ms | 66.643
| |  P99| 44ms| 50ms | 6ms | 13.793
| ChannelStore.GetTeamChannels |  Avg| 19ms| 18ms | -1ms | -5.381
| |  P99| 49ms| 47ms | -2ms | -4.118
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 24ms | -2ms | -7.813
| ChannelStore.Save |  Avg| 14ms| 13ms | -1ms | -7.310
| |  P99| 140ms| 119ms | -21ms | -14.947
| ChannelStore.SaveMember |  Avg| 37ms| 37ms | 0s | 0.000
| |  P99| 215ms| 215ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 5ms| 13ms | 8ms | 172.099
| |  P99| 40ms| 41ms | 1ms | 2.505
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.252
| ChannelStore.UpdateSidebarCategories |  Avg| 60ms| 90ms | 30ms | 49.659
| |  P99| 462ms| 462ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.420
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 21ms | -22ms | -50.577
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 4ms| 5ms | 1ms | 24.931
| |  P99| 19ms| 39ms | 20ms | 103.226
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 2ms | -1ms | -35.406
| |  P99| 22ms| 5ms | -17ms | -76.748
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 12ms| 3ms | -9ms | -72.383
| |  P99| 25ms| 5ms | -20ms | -80.483
| DraftStore.Upsert |  Avg| 3ms| 4ms | 1ms | 34.637
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.418
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 2ms| 1ms | -1ms | -46.073
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.124
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.306
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.494
| FileInfoStore.Save |  Avg| 6ms| 5ms | -1ms | -18.070
| |  P99| 37ms| 35ms | -2ms | -5.396
| FileInfoStore.SetContent |  Avg| 10ms| 9ms | -1ms | -10.447
| |  P99| 69ms| 45ms | -24ms | -34.910
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.201
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 101.010
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 38ms | 1ms | 2.718
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.242
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.220
| JobStore.Save |  Avg| 3ms| 4ms | 1ms | 29.700
| |  P99| 8ms| 19ms | 11ms | 139.241
| JobStore.UpdateOptimistically |  Avg| 3ms| 4ms | 1ms | 29.273
| |  P99| 21ms| 10ms | -11ms | -53.561
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -18.307
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 5ms | 1ms | 26.772
| |  P99| 19ms| 39ms | 20ms | 106.954
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.419
| LinkMetadataStore.Save |  Avg| 3ms| 4ms | 1ms | 29.200
| |  P99| 7ms| 23ms | 16ms | 235.301
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.188
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 21.918
| PluginStore.SetWithOptions |  Avg| 7ms| 6ms | -1ms | -15.175
| |  P99| 48ms| 43ms | -5ms | -10.499
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 55ms| 26ms | -29ms | -52.727
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.006
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 3ms | 1ms | 66.075
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.Get |  Avg| 2ms| 5ms | 3ms | 130.303
| |  P99| 21ms| 43ms | 22ms | 104.268
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.560
| PostPriorityStore.GetForPost |  Avg| 4ms| 2ms | -2ms | -53.812
| |  P99| 46ms| 26ms | -20ms | -43.479
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 26ms | -1ms | -3.648
| PostStore.AnalyticsPostCount |  Avg| 2ms| 15ms | 13ms | 599.413
| |  P99| 5ms| 25ms | 20ms | 403.702
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.580
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 31ms | -4ms | -11.576
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.690
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 22ms | 13ms | 146.616
| PostStore.GetPostReminders |  Avg| 6ms| 5ms | -1ms | -16.040
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 33ms | -1ms | -2.943
| PostStore.GetPostsAfter |  Avg| 4ms| 3ms | -1ms | -25.738
| |  P99| 20ms| 5ms | -15ms | -74.810
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.809
| PostStore.GetPostsByThread |  Avg| 6ms| 5ms | -1ms | -17.826
| |  P99| 25ms| 24ms | -1ms | -4.066
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 76ms| 75ms | -1ms | -1.316
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.825
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 13ms | -1ms | -7.394
| |  P99| 82ms| 79ms | -3ms | -3.671
| PostStore.SearchPostsForUser |  Avg| 180ms| 133ms | -47ms | -26.068
| |  P99| 2.33s| 2.244s | -86ms | -3.690
| PostStore.SetPostReminder |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 16ms| 15ms | -1ms | -6.317
| |  P99| 83ms| 70ms | -13ms | -15.694
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -36.950
| |  P99| 22ms| 9ms | -13ms | -58.690
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.048
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 39ms | 1ms | 2.633
| PreferenceStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 96ms| 90ms | -6ms | -6.270
| ProductNoticesStore.GetViews |  Avg| 3ms| 2ms | -1ms | -33.212
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 46ms| 45ms | -1ms | -2.181
| |  P99| 312ms| 306ms | -6ms | -1.920
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.361
| RetentionPolicyStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 5ms| 1ms | -4ms | -83.637
| |  P99| 24ms| 5ms | -19ms | -77.869
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 5ms | -1ms | -16.235
| |  P99| 24ms| 24ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -130.361
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 73ms| 65ms | -8ms | -10.940
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 30ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 4ms| 2ms | -2ms | -47.604
| |  P99| 24ms| 5ms | -19ms | -78.351
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.856
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 53ms| 49ms | -4ms | -7.573
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 30ms | -6ms | -16.719
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 14ms| 39ms | 25ms | 174.805
| |  P99| 383ms| 757ms | 374ms | 97.669
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 5ms| 2ms | -3ms | -65.218
| |  P99| 46ms| 5ms | -41ms | -89.617
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.859
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 30ms | -5ms | -14.460
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 3ms | 1ms | 55.075
| |  P99| 5ms| 10ms | 5ms | 101.010
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.376
| TeamStore.GetActiveMemberCount |  Avg| 59ms| 52ms | -7ms | -11.903
| |  P99| 99ms| 99ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.833
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 30ms | -2ms | -6.179
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.152
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 33ms | -1ms | -2.969
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 35ms | -3ms | -7.796
| TeamStore.GetTotalMemberCount |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 31ms| 32ms | 1ms | 3.214
| |  P99| 155ms| 131ms | -24ms | -15.471
| ThreadStore.Get |  Avg| 3ms| 2ms | -1ms | -35.475
| |  P99| 64ms| 8ms | -56ms | -87.494
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.323
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 37ms | -3ms | -7.562
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.485
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 35ms| 39ms | 4ms | 11.565
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 29ms| 25ms | -4ms | -13.867
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 29ms | -1ms | -3.293
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 30ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 30ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 29ms | -2ms | -6.491
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 40ms | 2ms | 5.212
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.811
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 0s | -4ms | -97.942
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.900
| ThreadStore.UpdateMembership |  Avg| 4ms| 3ms | -1ms | -28.397
| |  P99| 18ms| 13ms | -5ms | -28.552
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 4ms| 2ms | -2ms | -47.632
| |  P99| 24ms| 21ms | -3ms | -12.685
| UserStore.AnalyticsActiveCount |  Avg| 21ms| 20ms | -1ms | -4.845
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 1ms | -1ms | -59.561
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 49ms| 47ms | -2ms | -4.116
| |  P99| 294ms| 342ms | 48ms | 16.328
| UserStore.Count |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 46ms| 40ms | -6ms | -13.115
| UserStore.Get |  Avg| 3ms| 2ms | -1ms | -39.076
| |  P99| 22ms| 19ms | -3ms | -13.527
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.057
| UserStore.GetAllProfilesInChannel |  Avg| 266ms| 260ms | -6ms | -2.256
| |  P99| 937ms| 922ms | -15ms | -1.600
| UserStore.GetByUsername |  Avg| 3ms| 2ms | -1ms | -34.533
| |  P99| 40ms| 20ms | -20ms | -50.314
| UserStore.GetForLogin |  Avg| 4ms| 3ms | -1ms | -27.864
| |  P99| 37ms| 36ms | -1ms | -2.700
| UserStore.GetMany |  Avg| 2ms| 4ms | 2ms | 104.811
| |  P99| 5ms| 23ms | 18ms | 363.636
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 26ms | -2ms | -7.118
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.351
| UserStore.GetProfilesInChannel |  Avg| 163ms| 30ms | -133ms | -81.693
| |  P99| 248ms| 50ms | -198ms | -79.713
| UserStore.GetProfilesNotInChannel |  Avg| 6ms| 5ms | -1ms | -18.017
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.691
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.Save |  Avg| 73ms| 74ms | 1ms | 1.366
| |  P99| 228ms| 228ms | 0s | 0.000
| UserStore.Search |  Avg| 36ms| 37ms | 1ms | 2.751
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 8ms| 7ms | -1ms | -12.304
| |  P99| 65ms| 22ms | -43ms | -66.500
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 40ms| 38ms | -2ms | -4.977
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 31ms| 31ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 31ms| 26ms | -5ms | -15.909
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 32ms | -2ms | -5.823
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.485
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 249ms| 247ms | -2ms | -0.803
| | P99| 752ms| 498ms | -254ms | -33.791
| addTeamMember | Avg| 903ms| 926ms | 23ms | 2.547
| | P99| 2.492s| 2.487s | -5ms | -0.201
| autocompleteChannelsForTeamForSearch | Avg| 19ms| 64ms | 45ms | 238.665
| | P99| 71ms| 3.234s | 3.163s | 4470.576
| autocompleteEmojis | Avg| 2ms| 1ms | -1ms | -44.834
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 41ms| 40ms | -1ms | -2.426
| | P99| 198ms| 255ms | 57ms | 28.832
| channelMemberCountsByGroup | Avg| 7ms| 0s | -7ms | -106.694
| | P99| 62ms| 0s | -62ms | -100.578
| createCategoryForTeamForUser | Avg| 26ms| 46ms | 20ms | 78.303
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 252ms| 288ms | 36ms | 14.305
| | P99| 493ms| 496ms | 3ms | 0.609
| createDirectChannel | Avg| 257ms| 262ms | 5ms | 1.949
| | P99| 582ms| 496ms | -86ms | -14.765
| createGroupChannel | Avg| 379ms| 358ms | -21ms | -5.544
| | P99| 968ms| 954ms | -14ms | -1.447
| createPost | Avg| 356ms| 343ms | -13ms | -3.648
| | P99| 1.892s| 1.93s | 38ms | 2.009
| createUser | Avg| 148ms| 143ms | -5ms | -3.378
| | P99| 619ms| 496ms | -123ms | -19.885
| deleteDraft | Avg| 4ms| 2ms | -2ms | -49.613
| | P99| 5ms| 10ms | 5ms | 101.010
| deletePost | Avg| 22ms| 19ms | -3ms | -13.834
| | P99| 48ms| 25ms | -23ms | -47.501
| followThreadByUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 43ms| 41ms | -2ms | -4.623
| getAnalytics | Avg| 26ms| 23ms | -3ms | -11.753
| | P99| 50ms| 49ms | -1ms | -2.019
| getCategoriesForTeamForUser | Avg| 20ms| 35ms | 15ms | 76.303
| | P99| 98ms| 132ms | 34ms | 34.556
| getChannel | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 58ms| 31ms | -27ms | -46.356
| getChannelMember | Avg| 10ms| 9ms | -1ms | -10.244
| | P99| 88ms| 83ms | -5ms | -5.670
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 33ms| 30ms | -3ms | -9.052
| getChannelMembersForUser | Avg| 10ms| 11ms | 1ms | 10.184
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -4.914
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 36ms| 33ms | -3ms | -8.357
| getChannelsForUser | Avg| 8ms| 7ms | -1ms | -12.230
| | P99| 211ms| 208ms | -3ms | -1.422
| getClientConfig | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 92ms| 83ms | -9ms | -9.790
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 13ms| 0s | -13ms | -103.990
| | P99| 25ms| 0s | -25ms | -100.604
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 112ms| 107ms | -5ms | -4.472
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 96ms| 95ms | -1ms | -1.042
| getFilteredUsersStats | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -93.006
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 86ms| 79ms | -7ms | -8.176
| getPostsForChannel | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 225ms| 222ms | -3ms | -1.336
| getPostsForChannelAroundLastUnread | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 203ms| 203ms | 0s | 0.000
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 40ms| 41ms | 1ms | 2.471
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 94ms| 91ms | -3ms | -3.194
| | P99| 483ms| 461ms | -22ms | -4.558
| getPublicChannelsForTeam | Avg| 20ms| 19ms | -1ms | -5.087
| | P99| 48ms| 41ms | -7ms | -14.635
| getRolesByNames | Avg| 2ms| 6ms | 4ms | 191.719
| | P99| 24ms| 10ms | -14ms | -58.092
| getSelfHostedProducts | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.936
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 26ms | 2ms | 8.373
| getTeamMembersForUser | Avg| 5ms| 4ms | -1ms | -21.298
| | P99| 48ms| 46ms | -2ms | -4.170
| getTeamStats | Avg| 60ms| 53ms | -7ms | -11.719
| | P99| 100ms| 100ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 34ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 53ms| 50ms | -3ms | -5.641
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 38ms| 34ms | -4ms | -10.591
| getUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 68ms| 60ms | -8ms | -11.760
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 8ms| 6ms | -2ms | -26.122
| | P99| 99ms| 57ms | -42ms | -42.292
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 80ms| 77ms | -3ms | -3.752
| | P99| 479ms| 453ms | -26ms | -5.424
| logout | Avg| 60ms| 54ms | -6ms | -10.062
| | P99| 233ms| 99ms | -134ms | -57.388
| patchPost | Avg| 78ms| 35ms | -43ms | -55.085
| | P99| 495ms| 243ms | -252ms | -50.913
| removeUserCustomStatus | Avg| 174ms| 184ms | 10ms | 5.740
| | P99| 488ms| 484ms | -4ms | -0.819
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 11ms| 12ms | 1ms | 8.758
| | P99| 78ms| 80ms | 2ms | 2.563
| searchAllChannels | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 100ms| 100ms | 0s | 0.000
| searchGroupChannels | Avg| 5ms| 13ms | 8ms | 168.825
| | P99| 41ms| 41ms | 0s | 0.000
| searchPostsInTeam | Avg| 192ms| 140ms | -52ms | -27.020
| | P99| 2.353s| 2.297s | -56ms | -2.380
| searchUsers | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 99ms| 98ms | -1ms | -1.015
| setPostReminder | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 72ms| 77ms | 5ms | 6.901
| updateCategoriesForTeamForUser | Avg| 88ms| 122ms | 34ms | 38.653
| | P99| 462ms| 427ms | -35ms | -7.568
| updatePreferences | Avg| 10ms| 9ms | -1ms | -10.413
| | P99| 43ms| 42ms | -1ms | -2.352
| updateReadStateAllThreadsByUser | Avg| 4ms| 0s | -4ms | -96.007
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 44ms| 43ms | -1ms | -2.263
| | P99| 195ms| 171ms | -24ms | -12.308
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 406ms| 408ms | 2ms | 0.493
| | P99| 994ms| 1.012s | 18ms | 1.811
| upsertDraft | Avg| 4ms| 6ms | 2ms | 50.697
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 86ms| 81ms | -5ms | -5.782

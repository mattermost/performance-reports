### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 731ms | 729ms | 32043.20
| StatusStore.SaveOrUpdate | avg | 6ms | 34ms | 28ms | 495.04
| UserStore.AutocompleteUsersInChannel | avg | 13ms | 45ms | 32ms | 252.69
| UserStore.Search | avg | 7ms | 20ms | 13ms | 177.73
| ChannelStore.GetMembers | avg | 15ms | 26ms | 11ms | 74.07
| UserStore.Count | avg | 30ms | 47ms | 17ms | 56.59
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 18ms | 20ms | 2ms | 10.87
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 995ms | 990ms | 19992.21
| StatusStore.SaveOrUpdate | p99 | 81ms | 466ms | 385ms | 473.65
| UserStore.Search | p99 | 47ms | 98ms | 51ms | 108.21
| JobStore.UpdateStatus | p99 | 5ms | 8ms | 3ms | 60.61
| UserStore.AutocompleteUsersInChannel | p99 | 179ms | 272ms | 93ms | 52.05
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.545s | 1.93s | 385ms | 24.92
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | avg | 4ms | 0s | -4ms | -109.39
| PostPriorityStore.GetForPost | avg | 4ms | 0s | -4ms | -109.16
| WebhookStore.AnalyticsOutgoingCount | avg | 7ms | 0s | -7ms | -105.62
| FileInfoStore.Search | avg | 5ms | 0s | -5ms | -105.45
| SessionStore.AnalyticsSessionCount | avg | 4ms | 0s | -4ms | -103.47
| ChannelStore.AnalyticsTypeCount | avg | 17ms | 0s | -17ms | -101.44
| ComplianceStore.MessageExport | avg | 5ms | 0s | -5ms | -101.44
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 6ms | 0s | -6ms | -100.96
| PostAcknowledgementStore.GetForPosts | avg | 6ms | 0s | -6ms | -100.93
| ThreadStore.GetTopThreadsForUserSince | avg | 25ms | 0s | -25ms | -100.81
| ChannelStore.GetTopInactiveChannelsForUserSince | avg | 69ms | 0s | -69ms | -100.44
| ChannelStore.GetTopInactiveChannelsForTeamSince | avg | 87ms | 0s | -87ms | -100.30
| ReactionStore.GetTopForUserSince | avg | 119ms | 0s | -119ms | -100.17
| ChannelStore.GetTopChannelsForTeamSince | avg | 159ms | 0s | -159ms | -100.03
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 61ms | 0s | -61ms | -99.97
| PostStore.GetTopDMsForUserSince | avg | 146ms | 0s | -146ms | -99.92
| ChannelStore.GetMembersByIds | avg | 147ms | 0s | -147ms | -99.89
| ReactionStore.GetTopForTeamSince | avg | 133ms | 0s | -133ms | -99.77
| ThreadStore.GetTopThreadsForTeamSince | avg | 88ms | 0s | -88ms | -99.66
| ChannelStore.GetMembersForUserWithPagination | avg | 10ms | 0s | -10ms | -99.61
| TeamStore.GetNewTeamMembersSince | avg | 19ms | 0s | -19ms | -98.92
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -98.73
| ChannelStore.PostCountsByDuration | avg | 15ms | 0s | -15ms | -98.71
| UserStore.GetProfilesInChannelByAdmin | avg | 10ms | 0s | -10ms | -98.34
| UserStore.AnalyticsActiveCount | avg | 21ms | 0s | -21ms | -98.01
| ChannelStore.GetByNameIncludeDeleted | avg | 4ms | 0s | -4ms | -97.94
| ChannelStore.GetTopChannelsForUserSince | avg | 11ms | 0s | -11ms | -97.05
| DraftStore.GetDraftsForUser | avg | 9ms | 0s | -9ms | -96.18
| PostAcknowledgementStore.Save | avg | 9ms | 0s | -9ms | -95.94
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 3ms | 0s | -3ms | -95.20
| ProductNoticesStore.GetViews | avg | 8ms | 0s | -8ms | -95.17
| PostPriorityStore.GetForPosts | avg | 5ms | 0s | -5ms | -94.40
| DraftStore.Get | avg | 2ms | 0s | -2ms | -92.07
| ChannelStore.GetMemberCountsByGroup | avg | 5ms | 0s | -5ms | -91.56
| ChannelStore.GetFileCount | avg | 18ms | 2ms | -16ms | -90.79
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -90.62
| PostStore.HasAutoResponsePostByUserSince | avg | 3ms | 0s | -3ms | -89.77
| CommandStore.AnalyticsCommandCount | avg | 2ms | 0s | -2ms | -88.34
| PostAcknowledgementStore.GetForPost | avg | 3ms | 0s | -3ms | -86.80
| PluginStore.List | avg | 11ms | 2ms | -9ms | -85.66
| TokenStore.Cleanup | avg | 5ms | 1ms | -4ms | -82.31
| LicenseStore.GetAll | avg | 2ms | 0s | -2ms | -81.13
| CommandWebhookStore.Cleanup | avg | 5ms | 1ms | -4ms | -80.65
| ChannelStore.IncrementMentionCount | avg | 3ms | 1ms | -2ms | -78.40
| UserStore.IsEmpty | avg | 3ms | 1ms | -2ms | -74.14
| SystemStore.GetByName | avg | 3ms | 1ms | -2ms | -67.00
| StatusStore.Get | avg | 5ms | 2ms | -3ms | -65.45
| SessionStore.Get | avg | 8ms | 3ms | -5ms | -63.59
| TeamStore.GetAllPage | avg | 5ms | 2ms | -3ms | -61.68
| ThreadStore.GetTeamsUnreadForUser | avg | 7ms | 3ms | -4ms | -59.33
| GroupStore.GetByName | avg | 5ms | 2ms | -3ms | -57.18
| ThreadStore.GetMembershipForUser | avg | 4ms | 2ms | -2ms | -55.30
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 4ms | 2ms | -2ms | -54.52
| UserStore.UpdateFailedPasswordAttempts | avg | 6ms | 3ms | -3ms | -54.13
| JobStore.UpdateStatusOptimistically | avg | 6ms | 3ms | -3ms | -53.97
| PreferenceStore.GetAll | avg | 6ms | 3ms | -3ms | -53.53
| ChannelStore.GetMemberCount | avg | 6ms | 3ms | -3ms | -53.47
| TeamStore.GetMany | avg | 4ms | 2ms | -2ms | -53.37
| PluginStore.Get | avg | 4ms | 2ms | -2ms | -52.64
| UserTermsOfServiceStore.GetByUser | avg | 4ms | 2ms | -2ms | -52.05
| PostStore.SetPostReminder | avg | 8ms | 4ms | -4ms | -51.00
| TeamStore.GetMember | avg | 4ms | 2ms | -2ms | -50.80
| UserStore.InvalidateProfilesInChannelCacheByUser | avg | 129ms | 64ms | -65ms | -50.36
| ChannelStore.GetMembersInfoByChannelIds | avg | 8ms | 4ms | -4ms | -50.17
| JobStore.GetCountByStatusAndType | avg | 4ms | 2ms | -2ms | -50.15
| JobStore.GetAllByStatus | avg | 4ms | 2ms | -2ms | -50.06
| BotStore.Get | avg | 4ms | 2ms | -2ms | -48.18
| TeamStore.AnalyticsTeamCount | avg | 6ms | 3ms | -3ms | -48.07
| UserStore.GetAllProfiles | avg | 5ms | 3ms | -2ms | -43.77
| PluginStore.SetWithOptions | avg | 7ms | 4ms | -3ms | -43.67
| TeamStore.GetTeamsForUser | avg | 5ms | 3ms | -2ms | -42.84
| ThreadStore.GetTotalThreads | avg | 5ms | 3ms | -2ms | -42.70
| ThreadStore.GetTotalUnreadMentions | avg | 5ms | 3ms | -2ms | -42.46
| ThreadStore.GetTotalUnreadThreads | avg | 5ms | 3ms | -2ms | -42.08
| AuditStore.Save | avg | 5ms | 3ms | -2ms | -41.32
| ThreadStore.MaintainMembership | avg | 5ms | 3ms | -2ms | -40.95
| TeamStore.GetChannelUnreadsForAllTeams | avg | 5ms | 3ms | -2ms | -40.62
| SessionStore.Save | avg | 10ms | 6ms | -4ms | -40.11
| ClusterDiscoveryStore.SetLastPingAt | avg | 5ms | 3ms | -2ms | -40.03
| ChannelStore.Save | avg | 13ms | 8ms | -5ms | -39.81
| ChannelStore.GetByName | avg | 5ms | 3ms | -2ms | -39.48
| ProductNoticesStore.View | avg | 33ms | 20ms | -13ms | -38.84
| TeamStore.GetTeamsByUserId | avg | 5ms | 3ms | -2ms | -38.55
| UserStore.GetForLogin | avg | 5ms | 3ms | -2ms | -36.63
| PreferenceStore.Save | avg | 9ms | 6ms | -3ms | -34.78
| ThreadStore.GetThreadsForUser | avg | 6ms | 4ms | -2ms | -34.65
| UserStore.UpdateUpdateAt | avg | 6ms | 4ms | -2ms | -33.90
| PostStore.GetPostsBefore | avg | 6ms | 4ms | -2ms | -33.79
| ReactionStore.Save | avg | 10ms | 7ms | -3ms | -30.90
| PostStore.GetPosts | avg | 7ms | 5ms | -2ms | -30.09
| PostStore.Get | avg | 7ms | 5ms | -2ms | -29.39
| ThreadStore.GetThreadUnreadReplyCount | avg | 7ms | 5ms | -2ms | -27.87
| ChannelStore.CreateDirectChannel | avg | 18ms | 13ms | -5ms | -27.74
| ChannelStore.CreateInitialSidebarCategories | avg | 48ms | 35ms | -13ms | -27.35
| PostStore.Save | avg | 11ms | 8ms | -3ms | -26.67
| ThreadStore.GetThreadForUser | avg | 8ms | 6ms | -2ms | -25.11
| ChannelStore.SaveMember | avg | 32ms | 24ms | -8ms | -24.72
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 37ms | 29ms | -8ms | -21.84
| TeamStore.SaveMember | avg | 29ms | 23ms | -6ms | -20.76
| ChannelStore.GetTeamChannels | avg | 24ms | 19ms | -5ms | -20.55
| PostStore.SearchPostsForUser | avg | 185ms | 148ms | -37ms | -19.95
| ChannelStore.CreateSidebarCategory | avg | 40ms | 34ms | -6ms | -15.12
| UserStore.Save | avg | 77ms | 66ms | -11ms | -14.32
| ChannelStore.SearchGroupChannels | avg | 15ms | 13ms | -2ms | -13.02
| ChannelStore.UpdateSidebarCategories | avg | 70ms | 61ms | -9ms | -12.93
| ChannelStore.Autocomplete | avg | 48ms | 42ms | -6ms | -12.45
| UserStore.GetProfilesInChannel | avg | 27ms | 24ms | -3ms | -11.14
| ChannelStore.GetPublicChannelsForTeam | avg | 19ms | 17ms | -2ms | -10.75
| ChannelStore.AutocompleteInTeamForSearch | avg | 58ms | 56ms | -2ms | -3.46
| UserStore.GetAllProfilesInChannel | avg | 207ms | 201ms | -6ms | -2.90
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 10ms | 0s | -10ms | -102.57
| UserStore.GetProfilesInChannelByAdmin | p99 | 25ms | 0s | -25ms | -101.83
| ProductNoticesStore.GetViews | p99 | 25ms | 0s | -25ms | -101.79
| LicenseStore.GetAll | p99 | 23ms | 0s | -23ms | -101.77
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 24ms | 0s | -24ms | -101.48
| ChannelStore.GetByNameIncludeDeleted | p99 | 24ms | 0s | -24ms | -101.48
| DraftStore.GetDraftsForUser | p99 | 25ms | 0s | -25ms | -101.21
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| SessionStore.AnalyticsSessionCount | p99 | 5ms | 0s | -5ms | -101.01
| WebhookStore.AnalyticsIncomingCount | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Get | p99 | 5ms | 0s | -5ms | -100.97
| ComplianceStore.MessageExport | p99 | 26ms | 0s | -26ms | -100.97
| ChannelStore.PostCountsByDuration | p99 | 48ms | 0s | -48ms | -100.95
| PostPriorityStore.GetForPost | p99 | 48ms | 0s | -48ms | -100.88
| CommandStore.AnalyticsCommandCount | p99 | 5ms | 0s | -5ms | -100.87
| FileInfoStore.Search | p99 | 10ms | 0s | -10ms | -100.84
| PostAcknowledgementStore.GetForPosts | p99 | 61ms | 0s | -61ms | -100.72
| ChannelStore.GetMembersForUserWithPagination | p99 | 36ms | 0s | -36ms | -100.71
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 47ms | 0s | -47ms | -100.54
| WebhookStore.AnalyticsOutgoingCount | p99 | 10ms | 0s | -10ms | -100.50
| PostStore.HasAutoResponsePostByUserSince | p99 | 39ms | 0s | -39ms | -100.32
| ReactionStore.GetTopForUserSince | p99 | 249ms | 0s | -249ms | -100.20
| ReactionStore.GetTopForTeamSince | p99 | 249ms | 0s | -249ms | -100.20
| ChannelStore.GetMembersByIds | p99 | 249ms | 0s | -249ms | -100.20
| ChannelStore.GetTopInactiveChannelsForUserSince | p99 | 212ms | 0s | -212ms | -100.19
| ThreadStore.GetTopThreadsForUserSince | p99 | 95ms | 0s | -95ms | -100.15
| PostAcknowledgementStore.GetForPost | p99 | 37ms | 0s | -37ms | -100.01
| ChannelStore.GetTopChannelsForTeamSince | p99 | 2.14s | 0s | -2.14s | -100.01
| ChannelStore.GetTopInactiveChannelsForTeamSince | p99 | 246ms | 0s | -246ms | -100.00
| ChannelStore.GetTopChannelsForUserSince | p99 | 68ms | 0s | -68ms | -100.00
| ThreadStore.GetTopThreadsForTeamSince | p99 | 1.791s | 0s | -1.791s | -99.99
| PostStore.GetTopDMsForUserSince | p99 | 464ms | 0s | -464ms | -99.90
| PostAcknowledgementStore.Save | p99 | 93ms | 0s | -93ms | -99.81
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 178ms | 0s | -178ms | -99.79
| ChannelStore.GetMemberCountsByGroup | p99 | 78ms | 0s | -78ms | -99.70
| UserStore.AnalyticsActiveCount | p99 | 49ms | 0s | -49ms | -99.66
| TeamStore.GetNewTeamMembersSince | p99 | 44ms | 0s | -44ms | -99.48
| ChannelStore.AnalyticsTypeCount | p99 | 48ms | 0s | -48ms | -99.20
| PostPriorityStore.GetForPosts | p99 | 49ms | 0s | -49ms | -98.99
| PostStore.SetPostReminder | p99 | 86ms | 5ms | -81ms | -94.19
| PluginStore.List | p99 | 49ms | 5ms | -44ms | -89.90
| ChannelStore.GetMembersInfoByChannelIds | p99 | 205ms | 21ms | -184ms | -89.68
| ChannelStore.GetFileCount | p99 | 82ms | 9ms | -73ms | -88.99
| ChannelStore.GetMany | p99 | 33ms | 5ms | -28ms | -84.05
| ChannelStore.GetPinnedPostCount | p99 | 28ms | 5ms | -23ms | -83.47
| JobStore.GetNewestJobByStatusesAndType | p99 | 63ms | 11ms | -52ms | -82.54
| JobStore.GetCountByStatusAndType | p99 | 43ms | 8ms | -35ms | -81.87
| ChannelStore.GetGuestCount | p99 | 25ms | 5ms | -20ms | -81.24
| PostStore.GetPostIdBeforeTime | p99 | 35ms | 7ms | -28ms | -81.11
| BotStore.Get | p99 | 24ms | 5ms | -19ms | -80.59
| ClusterDiscoveryStore.SetLastPingAt | p99 | 46ms | 9ms | -37ms | -80.26
| TeamStore.GetByName | p99 | 31ms | 6ms | -25ms | -80.00
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 26ms | 5ms | -21ms | -79.88
| SystemStore.GetByName | p99 | 45ms | 9ms | -36ms | -79.71
| LinkMetadataStore.Save | p99 | 23ms | 5ms | -18ms | -79.43
| JobStore.UpdateStatusOptimistically | p99 | 24ms | 5ms | -19ms | -79.08
| ChannelStore.CreateDirectChannel | p99 | 195ms | 41ms | -154ms | -78.88
| UserStore.GetProfilesByUsernames | p99 | 42ms | 9ms | -33ms | -77.94
| ChannelStore.GetChannelsWithCursor | p99 | 35ms | 8ms | -27ms | -77.67
| TeamStore.Get | p99 | 32ms | 7ms | -25ms | -77.18
| ThreadStore.GetThreadFollowers | p99 | 37ms | 9ms | -28ms | -76.52
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 39ms | 9ms | -30ms | -76.30
| PostStore.Delete | p99 | 126ms | 30ms | -96ms | -76.06
| TeamStore.GetMember | p99 | 40ms | 10ms | -30ms | -75.37
| PreferenceStore.Save | p99 | 97ms | 24ms | -73ms | -75.37
| PluginStore.Delete | p99 | 40ms | 10ms | -30ms | -75.07
| EmojiStore.GetMultipleByName | p99 | 21ms | 5ms | -16ms | -75.06
| ThreadStore.GetMembershipForUser | p99 | 40ms | 10ms | -30ms | -74.90
| ReactionStore.Save | p99 | 96ms | 24ms | -72ms | -74.65
| ThreadStore.MaintainMembership | p99 | 62ms | 16ms | -46ms | -74.33
| UserStore.GetUnreadCountForChannel | p99 | 34ms | 9ms | -25ms | -74.14
| SessionStore.Get | p99 | 91ms | 24ms | -67ms | -74.03
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 20ms | 5ms | -15ms | -73.86
| PostStore.GetPostIdAfterTime | p99 | 35ms | 9ms | -26ms | -73.51
| LinkMetadataStore.Get | p99 | 18ms | 5ms | -13ms | -73.30
| PostStore.Save | p99 | 94ms | 25ms | -69ms | -73.21
| ThreadStore.MarkAllAsReadByChannels | p99 | 25ms | 7ms | -18ms | -72.82
| ThreadStore.GetTeamsUnreadForUser | p99 | 62ms | 17ms | -45ms | -72.79
| PluginStore.SetWithOptions | p99 | 79ms | 22ms | -57ms | -72.46
| PluginStore.Get | p99 | 40ms | 11ms | -29ms | -72.43
| SessionStore.Save | p99 | 86ms | 24ms | -62ms | -72.43
| ChannelStore.IncrementMentionCount | p99 | 39ms | 11ms | -28ms | -72.28
| PostStore.GetEtag | p99 | 28ms | 8ms | -20ms | -71.37
| TeamStore.GetMany | p99 | 44ms | 13ms | -31ms | -71.23
| ChannelStore.GetChannelsByUser | p99 | 30ms | 9ms | -21ms | -70.98
| UserStore.Update | p99 | 75ms | 22ms | -53ms | -70.64
| PostStore.Get | p99 | 63ms | 19ms | -44ms | -69.67
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 192ms | 59ms | -133ms | -69.38
| ThreadStore.UpdateMembership | p99 | 22ms | 7ms | -15ms | -69.33
| PreferenceStore.Get | p99 | 33ms | 10ms | -23ms | -69.18
| JobStore.UpdateOptimistically | p99 | 25ms | 8ms | -17ms | -69.14
| TeamStore.GetAllPage | p99 | 48ms | 15ms | -33ms | -69.00
| TeamStore.GetTeamsForUser | p99 | 46ms | 14ms | -32ms | -69.00
| ChannelStore.Get | p99 | 17ms | 5ms | -12ms | -68.94
| TeamStore.GetTeamsByUserId | p99 | 48ms | 15ms | -33ms | -68.59
| PostStore.GetSingle | p99 | 23ms | 7ms | -16ms | -68.35
| ChannelStore.GetChannelUnread | p99 | 25ms | 8ms | -17ms | -68.33
| StatusStore.Get | p99 | 45ms | 14ms | -31ms | -68.30
| UserStore.GetForLogin | p99 | 49ms | 16ms | -33ms | -67.97
| FileInfoStore.Get | p99 | 24ms | 8ms | -16ms | -67.81
| TeamStore.SaveMember | p99 | 156ms | 50ms | -106ms | -67.80
| FileInfoStore.AttachToPost | p99 | 47ms | 15ms | -32ms | -67.39
| ThreadStore.GetTotalUnreadThreads | p99 | 45ms | 15ms | -30ms | -67.07
| ThreadStore.Get | p99 | 26ms | 9ms | -17ms | -66.58
| ChannelStore.GetMembersForUserWithCursor | p99 | 36ms | 12ms | -24ms | -65.83
| ThreadStore.GetTotalUnreadMentions | p99 | 44ms | 15ms | -29ms | -65.61
| ThreadStore.GetTotalThreads | p99 | 44ms | 15ms | -29ms | -65.51
| PostStore.GetPostsAfter | p99 | 24ms | 8ms | -16ms | -65.40
| ChannelStore.GetChannels | p99 | 43ms | 15ms | -28ms | -65.11
| ChannelStore.SaveMember | p99 | 220ms | 77ms | -143ms | -65.04
| ThreadStore.GetThreadsForUser | p99 | 45ms | 16ms | -29ms | -65.02
| JobStore.Get | p99 | 22ms | 8ms | -14ms | -64.74
| ChannelStore.GetMember | p99 | 25ms | 9ms | -16ms | -64.56
| ChannelStore.CreateInitialSidebarCategories | p99 | 247ms | 88ms | -159ms | -64.50
| UserTermsOfServiceStore.GetByUser | p99 | 42ms | 15ms | -27ms | -64.23
| SessionStore.Remove | p99 | 25ms | 9ms | -16ms | -63.43
| JobStore.GetAllByStatus | p99 | 43ms | 16ms | -27ms | -62.22
| ChannelStore.CreateSidebarCategory | p99 | 225ms | 85ms | -140ms | -62.18
| GroupStore.GetByName | p99 | 50ms | 19ms | -31ms | -61.96
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 45ms | 17ms | -28ms | -61.55
| ChannelStore.GetMembersForUser | p99 | 44ms | 17ms | -27ms | -61.45
| ThreadStore.MarkAsRead | p99 | 23ms | 9ms | -14ms | -61.43
| PostStore.GetPostReminderMetadata | p99 | 23ms | 9ms | -14ms | -60.83
| PreferenceStore.GetAll | p99 | 48ms | 19ms | -29ms | -60.72
| PostStore.GetPostsBefore | p99 | 45ms | 18ms | -27ms | -60.61
| ChannelStore.Save | p99 | 99ms | 39ms | -60ms | -60.39
| UserStore.IsEmpty | p99 | 27ms | 11ms | -16ms | -60.20
| UserStore.GetByUsername | p99 | 42ms | 17ms | -25ms | -59.11
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 36ms | 15ms | -21ms | -59.04
| ChannelStore.UpdateLastViewedAt | p99 | 31ms | 13ms | -18ms | -58.61
| ChannelStore.GetAllChannelMembersForUser | p99 | 27ms | 11ms | -16ms | -58.58
| PostStore.GetPosts | p99 | 55ms | 23ms | -32ms | -58.14
| UserStore.GetUnreadCount | p99 | 41ms | 17ms | -24ms | -57.86
| UserStore.UpdateFailedPasswordAttempts | p99 | 49ms | 21ms | -28ms | -57.71
| GroupStore.GetGroups | p99 | 38ms | 16ms | -22ms | -57.67
| ProductNoticesStore.View | p99 | 298ms | 127ms | -171ms | -57.31
| AuditStore.Save | p99 | 46ms | 20ms | -26ms | -56.76
| StatusStore.UpdateLastActivityAt | p99 | 31ms | 14ms | -17ms | -55.37
| UserStore.UpdateUpdateAt | p99 | 44ms | 20ms | -24ms | -54.81
| ChannelStore.GetByName | p99 | 47ms | 22ms | -25ms | -53.51
| StatusStore.GetByIds | p99 | 24ms | 11ms | -13ms | -53.06
| UserStore.Save | p99 | 242ms | 115ms | -127ms | -52.57
| ThreadStore.GetThreadForUser | p99 | 48ms | 23ms | -25ms | -52.09
| TokenStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.51
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.50
| SessionStore.UpdateLastActivityAt | p99 | 26ms | 13ms | -13ms | -50.26
| UserStore.InvalidateProfilesInChannelCacheByUser | p99 | 490ms | 248ms | -242ms | -49.37
| ChannelStore.GetTeamChannels | p99 | 171ms | 89ms | -82ms | -48.04
| TeamStore.AnalyticsTeamCount | p99 | 42ms | 23ms | -19ms | -44.83
| ChannelStore.GetPublicChannelsForTeam | p99 | 67ms | 37ms | -30ms | -44.75
| ChannelStore.SearchGroupChannels | p99 | 59ms | 33ms | -26ms | -44.39
| UserStore.GetAllProfiles | p99 | 30ms | 17ms | -13ms | -43.57
| UserStore.GetProfilesInChannel | p99 | 85ms | 48ms | -37ms | -43.48
| WebhookStore.GetOutgoingByTeam | p99 | 49ms | 28ms | -21ms | -43.28
| ChannelStore.GetMemberCount | p99 | 51ms | 29ms | -22ms | -43.12
| FileInfoStore.Save | p99 | 34ms | 20ms | -14ms | -41.67
| PostStore.GetPostsByThread | p99 | 32ms | 19ms | -13ms | -40.08
| ChannelStore.UpdateSidebarCategories | p99 | 245ms | 147ms | -98ms | -39.94
| ChannelStore.Autocomplete | p99 | 162ms | 99ms | -63ms | -38.83
| ThreadStore.GetThreadUnreadReplyCount | p99 | 35ms | 22ms | -13ms | -37.32
| UserStore.GetProfileByIds | p99 | 8ms | 5ms | -3ms | -36.88
| UserStore.GetMany | p99 | 8ms | 5ms | -3ms | -36.64
| ChannelStore.GetMemberForPost | p99 | 25ms | 16ms | -9ms | -36.07
| UserAccessTokenStore.GetByToken | p99 | 37ms | 24ms | -13ms | -35.18
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 127ms | 90ms | -37ms | -29.18
| ChannelStore.GetSidebarCategory | p99 | 87ms | 66ms | -21ms | -24.07
| UserStore.GetAllProfilesInChannel | p99 | 983ms | 818ms | -165ms | -16.78
| PostStore.GetPostsSince | p99 | 95ms | 81ms | -14ms | -14.81
| PreferenceStore.DeleteCategoryAndName | p99 | 67ms | 59ms | -8ms | -11.85
| ThreadStore.MarkAllAsReadByTeam | p99 | 24ms | 22ms | -2ms | -8.17
| PostStore.SearchPostsForUser | p99 | 2.322s | 2.267s | -55ms | -2.37
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchUsers | avg | 8ms | 21ms | 13ms | 163.06
| autocompleteUsers | avg | 10ms | 24ms | 14ms | 134.65
| unfollowThreadByUser | avg | 10ms | 13ms | 3ms | 29.97
| createPost | avg | 451ms | 539ms | 88ms | 19.52
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchUsers | p99 | 48ms | 98ms | 50ms | 104.88
| autocompleteChannelsForTeamForSearch | p99 | 1.545s | 1.93s | 385ms | 24.92
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 3ms | 0s | -3ms | -119.11
| getGroups | avg | 5ms | 0s | -5ms | -107.29
| getPrevTrialLicense | avg | 3ms | 0s | -3ms | -103.51
| acknowledgePost | avg | 24ms | 0s | -24ms | -101.52
| getTopChannelsForUserSince | avg | 24ms | 0s | -24ms | -100.41
| getNewTeamMembersSince | avg | 22ms | 0s | -22ms | -100.34
| handleCheckCWSConnection | avg | 39ms | 0s | -39ms | -100.30
| getAnalytics | avg | 73ms | 0s | -73ms | -100.25
| updateConfig | avg | 375ms | 0s | -375ms | -100.08
| patchUser | avg | 317ms | 0s | -317ms | -100.06
| getFilteredUsersStats | avg | 48ms | 0s | -48ms | -100.05
| getTopInactiveChannelsForTeamSince | avg | 90ms | 0s | -90ms | -100.04
| getTopChannelsForTeamSince | avg | 184ms | 0s | -184ms | -100.02
| getChannelMembersByIds | avg | 148ms | 0s | -148ms | -99.96
| getTopReactionsForTeamSince | avg | 137ms | 0s | -137ms | -99.88
| updateCategoryForTeamForUser | avg | 141ms | 0s | -141ms | -99.87
| getTopDMsForUserSince | avg | 146ms | 0s | -146ms | -99.87
| getTopReactionsForUserSince | avg | 122ms | 0s | -122ms | -99.77
| getTopInactiveChannelsForUserSince | avg | 92ms | 0s | -92ms | -99.74
| getConfig | avg | 50ms | 0s | -50ms | -99.72
| getTotalUsersStats | avg | 67ms | 0s | -67ms | -99.55
| getTopThreadsForTeamSince | avg | 118ms | 2ms | -116ms | -98.68
| getEnvironmentConfig | avg | 24ms | 0s | -24ms | -98.24
| getProductNotices | avg | 10ms | 0s | -10ms | -98.06
| getDrafts | avg | 9ms | 0s | -9ms | -95.26
| searchFilesInTeam | avg | 7ms | 0s | -7ms | -94.64
| getTopThreadsForUserSince | avg | 33ms | 2ms | -31ms | -94.30
| getGroupsAssociatedToChannelsByTeam | avg | 3ms | 0s | -3ms | -93.77
| getClientConfig | avg | 39ms | 3ms | -36ms | -93.50
| channelMemberCountsByGroup | avg | 6ms | 0s | -6ms | -93.07
| deleteDraft | avg | 2ms | 0s | -2ms | -92.75
| getJobsByType | avg | 2ms | 0s | -2ms | -86.09
| getChannelsForTeamForUser | avg | 6ms | 2ms | -4ms | -71.34
| getUser | avg | 9ms | 3ms | -6ms | -69.41
| getTeamsUnreadForUser | avg | 9ms | 3ms | -6ms | -69.08
| getThreadsForUser | avg | 6ms | 2ms | -4ms | -66.44
| getChannelMembersForTeamForUser | avg | 6ms | 2ms | -4ms | -65.46
| getPostsForChannelAroundLastUnread | avg | 53ms | 19ms | -34ms | -63.70
| getChannelStats | avg | 11ms | 5ms | -6ms | -56.68
| getChannel | avg | 9ms | 4ms | -5ms | -56.43
| getPreferences | avg | 7ms | 3ms | -4ms | -55.25
| getAllTeams | avg | 6ms | 3ms | -3ms | -53.57
| createChannel | avg | 24ms | 11ms | -13ms | -53.13
| addChannelMember | avg | 250ms | 118ms | -132ms | -52.82
| getChannelMember | avg | 6ms | 3ms | -3ms | -52.03
| searchPostsInTeam | avg | 208ms | 105ms | -103ms | -49.43
| getTeamMembersForUser | avg | 6ms | 3ms | -3ms | -48.39
| getPublicChannelsForTeam | avg | 20ms | 11ms | -9ms | -44.89
| login | avg | 137ms | 78ms | -59ms | -43.19
| getPostThread | avg | 17ms | 10ms | -7ms | -41.92
| getUsers | avg | 12ms | 7ms | -5ms | -41.60
| getTeamsForUser | avg | 5ms | 3ms | -2ms | -37.93
| createUser | avg | 143ms | 91ms | -52ms | -36.24
| createGroupChannel | avg | 466ms | 304ms | -162ms | -34.80
| gqlWebCurrentUserInfo | avg | 57ms | 37ms | -20ms | -34.79
| createDirectChannel | avg | 296ms | 199ms | -97ms | -32.73
| addTeamMember | avg | 1.12s | 769ms | -351ms | -31.34
| searchAllChannels | avg | 61ms | 42ms | -19ms | -31.28
| gqlWebChannelsAndChannelMembers | avg | 34ms | 24ms | -10ms | -29.34
| setPostReminder | avg | 28ms | 20ms | -8ms | -28.63
| getChannelMembers | avg | 7ms | 5ms | -2ms | -28.42
| viewChannel | avg | 21ms | 15ms | -6ms | -28.21
| patchPost | avg | 43ms | 31ms | -12ms | -27.78
| followThreadByUser | avg | 18ms | 13ms | -5ms | -27.63
| removeUserCustomStatus | avg | 181ms | 131ms | -50ms | -27.57
| updatePreferences | avg | 8ms | 6ms | -2ms | -26.51
| updateUserCustomStatus | avg | 195ms | 150ms | -45ms | -23.08
| getCategoriesForTeamForUser | avg | 37ms | 29ms | -8ms | -21.67
| saveReaction | avg | 23ms | 18ms | -5ms | -21.29
| logout | avg | 56ms | 45ms | -11ms | -19.74
| createCategoryForTeamForUser | avg | 44ms | 37ms | -7ms | -15.85
| getProfileImage | avg | 124ms | 106ms | -18ms | -14.54
| searchGroupChannels | avg | 15ms | 13ms | -2ms | -12.95
| updateReadStateThreadByUser | avg | 41ms | 36ms | -5ms | -12.24
| deletePost | avg | 20ms | 18ms | -2ms | -9.92
| getFilePreview | avg | 44ms | 40ms | -4ms | -9.15
| updateCategoriesForTeamForUser | avg | 104ms | 95ms | -9ms | -8.63
| getPostsForChannel | avg | 103ms | 96ms | -7ms | -6.78
| getFileThumbnail | avg | 37ms | 35ms | -2ms | -5.39
| autocompleteChannelsForTeamForSearch | avg | 58ms | 56ms | -2ms | -3.46
| uploadFileStream | avg | 451ms | 437ms | -14ms | -3.10
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | p99 | 10ms | 0s | -10ms | -102.57
| getProductNotices | p99 | 25ms | 0s | -25ms | -101.79
| getRolesByNames | p99 | 10ms | 0s | -10ms | -101.78
| getDrafts | p99 | 25ms | 0s | -25ms | -101.21
| getPlugins | p99 | 5ms | 0s | -5ms | -101.01
| getJobsByType | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| deleteDraft | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 24ms | 0s | -24ms | -100.84
| getNewTeamMembersSince | p99 | 48ms | 0s | -48ms | -100.65
| getEnvironmentConfig | p99 | 25ms | 0s | -25ms | -100.60
| searchFilesInTeam | p99 | 10ms | 0s | -10ms | -100.50
| handleCheckCWSConnection | p99 | 50ms | 0s | -50ms | -100.50
| getTopReactionsForUserSince | p99 | 249ms | 0s | -249ms | -100.20
| getTopReactionsForTeamSince | p99 | 249ms | 0s | -249ms | -100.20
| getChannelMembersByIds | p99 | 249ms | 0s | -249ms | -100.20
| patchUser | p99 | 498ms | 0s | -498ms | -100.10
| updateConfig | p99 | 498ms | 0s | -498ms | -100.10
| getTopInactiveChannelsForUserSince | p99 | 243ms | 0s | -243ms | -100.05
| getTopChannelsForTeamSince | p99 | 2.14s | 0s | -2.14s | -100.01
| getTotalUsersStats | p99 | 99ms | 0s | -99ms | -100.00
| getConfig | p99 | 99ms | 0s | -99ms | -100.00
| getAnalytics | p99 | 242ms | 0s | -242ms | -100.00
| getTopInactiveChannelsForTeamSince | p99 | 246ms | 0s | -246ms | -99.91
| getTopDMsForUserSince | p99 | 464ms | 0s | -464ms | -99.90
| updateCategoryForTeamForUser | p99 | 248ms | 0s | -248ms | -99.80
| acknowledgePost | p99 | 223ms | 0s | -223ms | -99.80
| getFilteredUsersStats | p99 | 99ms | 0s | -99ms | -99.75
| getTopThreadsForTeamSince | p99 | 1.791s | 5ms | -1.786s | -99.71
| channelMemberCountsByGroup | p99 | 78ms | 0s | -78ms | -99.70
| getTopChannelsForUserSince | p99 | 96ms | 0s | -96ms | -99.48
| getGroups | p99 | 24ms | 0s | -24ms | -98.97
| getTopThreadsForUserSince | p99 | 215ms | 8ms | -207ms | -96.18
| getClientConfig | p99 | 230ms | 23ms | -207ms | -90.19
| getPostsForChannelAroundLastUnread | p99 | 849ms | 95ms | -754ms | -88.82
| setPostReminder | p99 | 208ms | 25ms | -183ms | -87.99
| getChannelMembersForTeamForUser | p99 | 50ms | 9ms | -41ms | -82.63
| getChannelsForTeamForUser | p99 | 59ms | 10ms | -49ms | -82.42
| unfollowThreadByUser | p99 | 140ms | 25ms | -115ms | -82.28
| getUser | p99 | 101ms | 18ms | -83ms | -82.04
| getPostThread | p99 | 172ms | 32ms | -140ms | -81.27
| getUsersByNames | p99 | 43ms | 9ms | -34ms | -79.03
| getThreadsForUser | p99 | 47ms | 10ms | -37ms | -78.95
| getChannelMember | p99 | 53ms | 11ms | -42ms | -78.72
| getChannel | p99 | 84ms | 18ms | -66ms | -78.60
| viewChannel | p99 | 208ms | 46ms | -162ms | -77.94
| getTeamsUnreadForUser | p99 | 86ms | 19ms | -67ms | -77.57
| updatePreferences | p99 | 86ms | 20ms | -66ms | -76.85
| gqlWebChannelsAndChannelMembers | p99 | 231ms | 54ms | -177ms | -76.54
| saveReaction | p99 | 207ms | 49ms | -158ms | -76.50
| followThreadByUser | p99 | 183ms | 46ms | -137ms | -75.07
| patchPost | p99 | 213ms | 58ms | -155ms | -72.76
| getAllTeams | p99 | 59ms | 16ms | -43ms | -72.42
| getChannelUnread | p99 | 37ms | 10ms | -27ms | -72.37
| getTeamMembersForUser | p99 | 69ms | 19ms | -50ms | -72.09
| getChannelsForUser | p99 | 30ms | 9ms | -21ms | -70.68
| gqlWebCurrentUserInfo | p99 | 221ms | 67ms | -154ms | -69.79
| getCategoriesForTeamForUser | p99 | 197ms | 60ms | -137ms | -69.55
| getPreferences | p99 | 62ms | 19ms | -43ms | -69.53
| getTeamsForUser | p99 | 48ms | 16ms | -32ms | -66.28
| deletePost | p99 | 126ms | 47ms | -79ms | -62.59
| updateReadStateThreadByUser | p99 | 227ms | 88ms | -139ms | -61.21
| getChannelMembers | p99 | 47ms | 18ms | -29ms | -61.07
| createDirectChannel | p99 | 1.208s | 492ms | -716ms | -59.28
| createCategoryForTeamForUser | p99 | 231ms | 96ms | -135ms | -58.40
| createGroupChannel | p99 | 1.976s | 867ms | -1.109s | -56.13
| login | p99 | 894ms | 395ms | -499ms | -55.85
| getUsers | p99 | 99ms | 44ms | -55ms | -55.78
| getPublicChannelsForTeam | p99 | 74ms | 34ms | -40ms | -54.15
| searchAllChannels | p99 | 216ms | 99ms | -117ms | -54.10
| createPost | p99 | 2.152s | 999ms | -1.153s | -53.57
| createChannel | p99 | 171ms | 80ms | -91ms | -53.31
| getChannelStats | p99 | 99ms | 47ms | -52ms | -52.72
| createUser | p99 | 494ms | 242ms | -252ms | -50.97
| addChannelMember | p99 | 945ms | 474ms | -471ms | -49.85
| addTeamMember | p99 | 4.393s | 2.401s | -1.992s | -45.34
| searchGroupChannels | p99 | 59ms | 33ms | -26ms | -44.21
| logout | p99 | 235ms | 135ms | -100ms | -42.59
| getUsersByIds | p99 | 13ms | 8ms | -5ms | -37.66
| getFileThumbnail | p99 | 143ms | 97ms | -46ms | -32.10
| updateUserCustomStatus | p99 | 614ms | 470ms | -144ms | -23.44
| getFilePreview | p99 | 202ms | 158ms | -44ms | -21.79
| updateCategoriesForTeamForUser | p99 | 304ms | 240ms | -64ms | -21.07
| getPostsForChannel | p99 | 1.107s | 916ms | -191ms | -17.26
| updateReadStateAllThreadsByUser | p99 | 24ms | 21ms | -3ms | -12.26
| autocompleteUsers | p99 | 112ms | 99ms | -13ms | -11.62
| removeUserCustomStatus | p99 | 498ms | 449ms | -49ms | -9.83
| searchPostsInTeam | p99 | 2.364s | 2.242s | -122ms | -5.16
| getProfileImage | p99 | 474ms | 453ms | -21ms | -4.43
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 3ms | -2ms | -41.324
| |  P99| 46ms| 20ms | -26ms | -56.760
| BotStore.Get |  Avg| 4ms| 2ms | -2ms | -48.183
| |  P99| 24ms| 5ms | -19ms | -80.594
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 61ms| 0s | -61ms | -99.969
| |  P99| 178ms| 0s | -178ms | -99.790
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 3ms | -1ms | -27.167
| |  P99| 36ms| 15ms | -21ms | -59.042
| ChannelStore.AnalyticsTypeCount |  Avg| 17ms| 0s | -17ms | -101.443
| |  P99| 48ms| 0s | -48ms | -99.198
| ChannelStore.Autocomplete |  Avg| 48ms| 42ms | -6ms | -12.452
| |  P99| 162ms| 99ms | -63ms | -38.826
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 58ms| 56ms | -2ms | -3.460
| |  P99| 1.545s| 1.93s | 385ms | 24.917
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 13ms | -5ms | -27.740
| |  P99| 195ms| 41ms | -154ms | -78.883
| ChannelStore.CreateInitialSidebarCategories |  Avg| 48ms| 35ms | -13ms | -27.350
| |  P99| 247ms| 88ms | -159ms | -64.500
| ChannelStore.CreateSidebarCategory |  Avg| 40ms| 34ms | -6ms | -15.117
| |  P99| 225ms| 85ms | -140ms | -62.178
| ChannelStore.Get |  Avg| 1ms| 0s | -1ms | -127.193
| |  P99| 17ms| 5ms | -12ms | -68.937
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 1ms | -1ms | -49.369
| |  P99| 27ms| 11ms | -16ms | -58.580
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 20ms | 2ms | 10.870
| |  P99| 127ms| 90ms | -37ms | -29.185
| ChannelStore.GetByName |  Avg| 5ms| 3ms | -2ms | -39.482
| |  P99| 47ms| 22ms | -25ms | -53.514
| ChannelStore.GetByNameIncludeDeleted |  Avg| 4ms| 0s | -4ms | -97.943
| |  P99| 24ms| 0s | -24ms | -101.478
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -32.355
| |  P99| 25ms| 8ms | -17ms | -68.329
| ChannelStore.GetChannels |  Avg| 4ms| 3ms | -1ms | -22.356
| |  P99| 43ms| 15ms | -28ms | -65.106
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 3ms | -1ms | -28.164
| |  P99| 30ms| 9ms | -21ms | -70.977
| ChannelStore.GetChannelsWithCursor |  Avg| 4ms| 3ms | -1ms | -25.304
| |  P99| 35ms| 8ms | -27ms | -77.671
| ChannelStore.GetFileCount |  Avg| 18ms| 2ms | -16ms | -90.794
| |  P99| 82ms| 9ms | -73ms | -88.987
| ChannelStore.GetGuestCount |  Avg| 2ms| 1ms | -1ms | -63.573
| |  P99| 25ms| 5ms | -20ms | -81.239
| ChannelStore.GetMany |  Avg| 2ms| 1ms | -1ms | -40.569
| |  P99| 33ms| 5ms | -28ms | -84.055
| ChannelStore.GetMember |  Avg| 4ms| 3ms | -1ms | -27.504
| |  P99| 25ms| 9ms | -16ms | -64.555
| ChannelStore.GetMemberCount |  Avg| 6ms| 3ms | -3ms | -53.466
| |  P99| 51ms| 29ms | -22ms | -43.116
| ChannelStore.GetMemberCountsByGroup |  Avg| 5ms| 0s | -5ms | -91.562
| |  P99| 78ms| 0s | -78ms | -99.695
| ChannelStore.GetMemberForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 16ms | -9ms | -36.068
| ChannelStore.GetMembers |  Avg| 15ms| 26ms | 11ms | 74.075
| |  P99| 234ms| 236ms | 2ms | 0.857
| ChannelStore.GetMembersByIds |  Avg| 147ms| 0s | -147ms | -99.892
| |  P99| 249ms| 0s | -249ms | -100.201
| ChannelStore.GetMembersForUser |  Avg| 5ms| 4ms | -1ms | -18.482
| |  P99| 44ms| 17ms | -27ms | -61.453
| ChannelStore.GetMembersForUserWithCursor |  Avg| 5ms| 4ms | -1ms | -20.230
| |  P99| 36ms| 12ms | -24ms | -65.835
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 0s | -10ms | -99.607
| |  P99| 36ms| 0s | -36ms | -100.710
| ChannelStore.GetMembersInfoByChannelIds |  Avg| 8ms| 4ms | -4ms | -50.168
| |  P99| 205ms| 21ms | -184ms | -89.677
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 1ms | -1ms | -47.291
| |  P99| 28ms| 5ms | -23ms | -83.474
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 17ms | -2ms | -10.747
| |  P99| 67ms| 37ms | -30ms | -44.747
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 37ms| 29ms | -8ms | -21.837
| |  P99| 192ms| 59ms | -133ms | -69.382
| ChannelStore.GetSidebarCategory |  Avg| 17ms| 16ms | -1ms | -5.867
| |  P99| 87ms| 66ms | -21ms | -24.070
| ChannelStore.GetTeamChannels |  Avg| 24ms| 19ms | -5ms | -20.554
| |  P99| 171ms| 89ms | -82ms | -48.041
| ChannelStore.GetTopChannelsForTeamSince |  Avg| 159ms| 0s | -159ms | -100.033
| |  P99| 2.14s| 0s | -2.14s | -100.006
| ChannelStore.GetTopChannelsForUserSince |  Avg| 11ms| 0s | -11ms | -97.045
| |  P99| 68ms| 0s | -68ms | -99.999
| ChannelStore.GetTopInactiveChannelsForTeamSince |  Avg| 87ms| 0s | -87ms | -100.298
| |  P99| 246ms| 0s | -246ms | -100.000
| ChannelStore.GetTopInactiveChannelsForUserSince |  Avg| 69ms| 0s | -69ms | -100.444
| |  P99| 212ms| 0s | -212ms | -100.192
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 1ms | -2ms | -78.400
| |  P99| 39ms| 11ms | -28ms | -72.284
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
| ChannelStore.PostCountsByDuration |  Avg| 15ms| 0s | -15ms | -98.715
| |  P99| 48ms| 0s | -48ms | -100.947
| ChannelStore.Save |  Avg| 13ms| 8ms | -5ms | -39.806
| |  P99| 99ms| 39ms | -60ms | -60.391
| ChannelStore.SaveMember |  Avg| 32ms| 24ms | -8ms | -24.723
| |  P99| 220ms| 77ms | -143ms | -65.043
| ChannelStore.SearchGroupChannels |  Avg| 15ms| 13ms | -2ms | -13.015
| |  P99| 59ms| 33ms | -26ms | -44.388
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 3ms | -1ms | -24.555
| |  P99| 31ms| 13ms | -18ms | -58.610
| ChannelStore.UpdateSidebarCategories |  Avg| 70ms| 61ms | -9ms | -12.930
| |  P99| 245ms| 147ms | -98ms | -39.943
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 5ms | -15ms | -73.857
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 3ms | -2ms | -40.033
| |  P99| 46ms| 9ms | -37ms | -80.263
| CommandStore.AnalyticsCommandCount |  Avg| 2ms| 0s | -2ms | -88.343
| |  P99| 5ms| 0s | -5ms | -100.867
| CommandWebhookStore.Cleanup |  Avg| 5ms| 1ms | -4ms | -80.651
| |  P99| 10ms| 5ms | -5ms | -50.505
| ComplianceStore.MessageExport |  Avg| 5ms| 0s | -5ms | -101.435
| |  P99| 26ms| 0s | -26ms | -100.971
| DraftStore.Get |  Avg| 2ms| 0s | -2ms | -92.072
| |  P99| 5ms| 0s | -5ms | -100.974
| DraftStore.GetDraftsForUser |  Avg| 9ms| 0s | -9ms | -96.177
| |  P99| 25ms| 0s | -25ms | -101.214
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -75.056
| FileInfoStore.AttachToPost |  Avg| 6ms| 5ms | -1ms | -17.289
| |  P99| 47ms| 15ms | -32ms | -67.391
| FileInfoStore.DeleteForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 3ms| 2ms | -1ms | -34.983
| |  P99| 24ms| 8ms | -16ms | -67.807
| FileInfoStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.InvalidateFileInfosForPostCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 20ms | -14ms | -41.673
| FileInfoStore.Search |  Avg| 5ms| 0s | -5ms | -105.447
| |  P99| 10ms| 0s | -10ms | -100.840
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 2ms | -2ms | -54.518
| |  P99| 39ms| 9ms | -30ms | -76.297
| GroupStore.GetByName |  Avg| 5ms| 2ms | -3ms | -57.184
| |  P99| 50ms| 19ms | -31ms | -61.963
| GroupStore.GetGroups |  Avg| 4ms| 3ms | -1ms | -24.283
| |  P99| 38ms| 16ms | -22ms | -57.669
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 0s | -3ms | -95.196
| |  P99| 10ms| 0s | -10ms | -102.565
| JobStore.Get |  Avg| 3ms| 2ms | -1ms | -34.070
| |  P99| 22ms| 8ms | -14ms | -64.740
| JobStore.GetAllByStatus |  Avg| 4ms| 2ms | -2ms | -50.063
| |  P99| 43ms| 16ms | -27ms | -62.218
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -90.616
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 4ms| 2ms | -2ms | -50.146
| |  P99| 43ms| 8ms | -35ms | -81.871
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -29.089
| |  P99| 63ms| 11ms | -52ms | -82.540
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 8ms | -17ms | -69.141
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 3ms | -3ms | -53.968
| |  P99| 24ms| 5ms | -19ms | -79.084
| LicenseStore.GetAll |  Avg| 2ms| 0s | -2ms | -81.127
| |  P99| 23ms| 0s | -23ms | -101.768
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -73.305
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 5ms | -18ms | -79.431
| PluginStore.Delete |  Avg| 3ms| 2ms | -1ms | -34.198
| |  P99| 40ms| 10ms | -30ms | -75.074
| PluginStore.Get |  Avg| 4ms| 2ms | -2ms | -52.637
| |  P99| 40ms| 11ms | -29ms | -72.429
| PluginStore.List |  Avg| 11ms| 2ms | -9ms | -85.663
| |  P99| 49ms| 5ms | -44ms | -89.901
| PluginStore.SetWithOptions |  Avg| 7ms| 4ms | -3ms | -43.673
| |  P99| 79ms| 22ms | -57ms | -72.459
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 0s | -3ms | -86.804
| |  P99| 37ms| 0s | -37ms | -100.006
| PostAcknowledgementStore.GetForPosts |  Avg| 6ms| 0s | -6ms | -100.930
| |  P99| 61ms| 0s | -61ms | -100.717
| PostAcknowledgementStore.Save |  Avg| 9ms| 0s | -9ms | -95.943
| |  P99| 93ms| 0s | -93ms | -99.806
| PostPriorityStore.GetForPost |  Avg| 4ms| 0s | -4ms | -109.160
| |  P99| 48ms| 0s | -48ms | -100.880
| PostPriorityStore.GetForPosts |  Avg| 5ms| 0s | -5ms | -94.400
| |  P99| 49ms| 0s | -49ms | -98.993
| PostStore.AnalyticsPostCount |  Avg| 2ms| 731ms | 729ms | 32043.195
| |  P99| 5ms| 995ms | 990ms | 19992.205
| PostStore.Delete |  Avg| 12ms| 11ms | -1ms | -8.652
| |  P99| 126ms| 30ms | -96ms | -76.057
| PostStore.Get |  Avg| 7ms| 5ms | -2ms | -29.386
| |  P99| 63ms| 19ms | -44ms | -69.673
| PostStore.GetEtag |  Avg| 2ms| 1ms | -1ms | -50.889
| |  P99| 28ms| 8ms | -20ms | -71.371
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 1ms | -1ms | -41.290
| |  P99| 35ms| 9ms | -26ms | -73.507
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 1ms | -1ms | -45.220
| |  P99| 35ms| 7ms | -28ms | -81.112
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 9ms | -14ms | -60.827
| PostStore.GetPostReminders |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 7ms| 5ms | -2ms | -30.087
| |  P99| 55ms| 23ms | -32ms | -58.138
| PostStore.GetPostsAfter |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 8ms | -16ms | -65.397
| PostStore.GetPostsBefore |  Avg| 6ms| 4ms | -2ms | -33.790
| |  P99| 45ms| 18ms | -27ms | -60.609
| PostStore.GetPostsByThread |  Avg| 6ms| 5ms | -1ms | -15.475
| |  P99| 32ms| 19ms | -13ms | -40.077
| PostStore.GetPostsSince |  Avg| 15ms| 14ms | -1ms | -6.477
| |  P99| 95ms| 81ms | -14ms | -14.811
| PostStore.GetSingle |  Avg| 3ms| 2ms | -1ms | -33.290
| |  P99| 23ms| 7ms | -16ms | -68.352
| PostStore.GetTopDMsForUserSince |  Avg| 146ms| 0s | -146ms | -99.916
| |  P99| 464ms| 0s | -464ms | -99.904
| PostStore.HasAutoResponsePostByUserSince |  Avg| 3ms| 0s | -3ms | -89.773
| |  P99| 39ms| 0s | -39ms | -100.323
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 8ms | -3ms | -26.673
| |  P99| 94ms| 25ms | -69ms | -73.209
| PostStore.SearchPostsForUser |  Avg| 185ms| 148ms | -37ms | -19.955
| |  P99| 2.322s| 2.267s | -55ms | -2.369
| PostStore.SetPostReminder |  Avg| 8ms| 4ms | -4ms | -51.000
| |  P99| 86ms| 5ms | -81ms | -94.192
| PostStore.Update |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 5ms| 4ms | -1ms | -21.106
| |  P99| 67ms| 59ms | -8ms | -11.853
| PreferenceStore.Get |  Avg| 3ms| 2ms | -1ms | -30.427
| |  P99| 33ms| 10ms | -23ms | -69.175
| PreferenceStore.GetAll |  Avg| 6ms| 3ms | -3ms | -53.531
| |  P99| 48ms| 19ms | -29ms | -60.717
| PreferenceStore.Save |  Avg| 9ms| 6ms | -3ms | -34.782
| |  P99| 97ms| 24ms | -73ms | -75.368
| ProductNoticesStore.GetViews |  Avg| 8ms| 0s | -8ms | -95.168
| |  P99| 25ms| 0s | -25ms | -101.793
| ProductNoticesStore.View |  Avg| 33ms| 20ms | -13ms | -38.835
| |  P99| 298ms| 127ms | -171ms | -57.315
| ReactionStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetTopForTeamSince |  Avg| 133ms| 0s | -133ms | -99.767
| |  P99| 249ms| 0s | -249ms | -100.201
| ReactionStore.GetTopForUserSince |  Avg| 119ms| 0s | -119ms | -100.174
| |  P99| 249ms| 0s | -249ms | -100.201
| ReactionStore.Save |  Avg| 10ms| 7ms | -3ms | -30.897
| |  P99| 96ms| 24ms | -72ms | -74.646
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -98.735
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.AnalyticsSessionCount |  Avg| 4ms| 0s | -4ms | -103.471
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 8ms| 3ms | -5ms | -63.591
| |  P99| 91ms| 24ms | -67ms | -74.030
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 2ms | -1ms | -30.156
| |  P99| 26ms| 5ms | -21ms | -79.880
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 9ms | -16ms | -63.431
| SessionStore.Save |  Avg| 10ms| 6ms | -4ms | -40.106
| |  P99| 86ms| 24ms | -62ms | -72.425
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 3ms | -1ms | -26.400
| |  P99| 26ms| 13ms | -13ms | -50.261
| StatusStore.Get |  Avg| 5ms| 2ms | -3ms | -65.450
| |  P99| 45ms| 14ms | -31ms | -68.299
| StatusStore.GetByIds |  Avg| 3ms| 2ms | -1ms | -36.078
| |  P99| 24ms| 11ms | -13ms | -53.062
| StatusStore.SaveOrUpdate |  Avg| 6ms| 34ms | 28ms | 495.038
| |  P99| 81ms| 466ms | 385ms | 473.650
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 14ms | -17ms | -55.369
| SystemStore.GetByName |  Avg| 3ms| 1ms | -2ms | -66.999
| |  P99| 45ms| 9ms | -36ms | -79.708
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 3ms | -3ms | -48.074
| |  P99| 42ms| 23ms | -19ms | -44.826
| TeamStore.Get |  Avg| 3ms| 2ms | -1ms | -31.274
| |  P99| 32ms| 7ms | -25ms | -77.175
| TeamStore.GetAllPage |  Avg| 5ms| 2ms | -3ms | -61.681
| |  P99| 48ms| 15ms | -33ms | -69.001
| TeamStore.GetByName |  Avg| 3ms| 2ms | -1ms | -33.418
| |  P99| 31ms| 6ms | -25ms | -79.997
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 5ms| 3ms | -2ms | -40.620
| |  P99| 45ms| 17ms | -28ms | -61.547
| TeamStore.GetMany |  Avg| 4ms| 2ms | -2ms | -53.367
| |  P99| 44ms| 13ms | -31ms | -71.232
| TeamStore.GetMember |  Avg| 4ms| 2ms | -2ms | -50.795
| |  P99| 40ms| 10ms | -30ms | -75.369
| TeamStore.GetNewTeamMembersSince |  Avg| 19ms| 0s | -19ms | -98.924
| |  P99| 44ms| 0s | -44ms | -99.478
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 3ms | -2ms | -38.549
| |  P99| 48ms| 15ms | -33ms | -68.592
| TeamStore.GetTeamsForUser |  Avg| 5ms| 3ms | -2ms | -42.836
| |  P99| 46ms| 14ms | -32ms | -68.997
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 29ms| 23ms | -6ms | -20.761
| |  P99| 156ms| 50ms | -106ms | -67.795
| ThreadStore.Get |  Avg| 3ms| 2ms | -1ms | -32.992
| |  P99| 26ms| 9ms | -17ms | -66.584
| ThreadStore.GetMembershipForUser |  Avg| 4ms| 2ms | -2ms | -55.304
| |  P99| 40ms| 10ms | -30ms | -74.898
| ThreadStore.GetTeamsUnreadForUser |  Avg| 7ms| 3ms | -4ms | -59.331
| |  P99| 62ms| 17ms | -45ms | -72.786
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 2ms | -1ms | -28.822
| |  P99| 37ms| 9ms | -28ms | -76.517
| ThreadStore.GetThreadForUser |  Avg| 8ms| 6ms | -2ms | -25.115
| |  P99| 48ms| 23ms | -25ms | -52.089
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 7ms| 5ms | -2ms | -27.872
| |  P99| 35ms| 22ms | -13ms | -37.316
| ThreadStore.GetThreadsForUser |  Avg| 6ms| 4ms | -2ms | -34.646
| |  P99| 45ms| 16ms | -29ms | -65.020
| ThreadStore.GetTopThreadsForTeamSince |  Avg| 88ms| 0s | -88ms | -99.661
| |  P99| 1.791s| 0s | -1.791s | -99.994
| ThreadStore.GetTopThreadsForUserSince |  Avg| 25ms| 0s | -25ms | -100.809
| |  P99| 95ms| 0s | -95ms | -100.151
| ThreadStore.GetTotalThreads |  Avg| 5ms| 3ms | -2ms | -42.700
| |  P99| 44ms| 15ms | -29ms | -65.509
| ThreadStore.GetTotalUnreadMentions |  Avg| 5ms| 3ms | -2ms | -42.461
| |  P99| 44ms| 15ms | -29ms | -65.612
| ThreadStore.GetTotalUnreadThreads |  Avg| 5ms| 3ms | -2ms | -42.076
| |  P99| 45ms| 15ms | -30ms | -67.066
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 6ms| 0s | -6ms | -100.959
| |  P99| 47ms| 0s | -47ms | -100.541
| ThreadStore.MaintainMembership |  Avg| 5ms| 3ms | -2ms | -40.949
| |  P99| 62ms| 16ms | -46ms | -74.334
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 7ms | -18ms | -72.817
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.172
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 9ms | -14ms | -61.431
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 7ms | -15ms | -69.331
| TokenStore.Cleanup |  Avg| 5ms| 1ms | -4ms | -82.314
| |  P99| 10ms| 5ms | -5ms | -50.505
| UserAccessTokenStore.GetByToken |  Avg| 4ms| 3ms | -1ms | -27.770
| |  P99| 37ms| 24ms | -13ms | -35.180
| UserStore.AnalyticsActiveCount |  Avg| 21ms| 0s | -21ms | -98.008
| |  P99| 49ms| 0s | -49ms | -99.661
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 4ms| 0s | -4ms | -109.387
| |  P99| 24ms| 0s | -24ms | -101.481
| UserStore.AutocompleteUsersInChannel |  Avg| 13ms| 45ms | 32ms | 252.691
| |  P99| 179ms| 272ms | 93ms | 52.052
| UserStore.Count |  Avg| 30ms| 47ms | 17ms | 56.593
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 5ms| 3ms | -2ms | -43.769
| |  P99| 30ms| 17ms | -13ms | -43.567
| UserStore.GetAllProfilesInChannel |  Avg| 207ms| 201ms | -6ms | -2.902
| |  P99| 983ms| 818ms | -165ms | -16.779
| UserStore.GetByUsername |  Avg| 4ms| 3ms | -1ms | -23.588
| |  P99| 42ms| 17ms | -25ms | -59.113
| UserStore.GetForLogin |  Avg| 5ms| 3ms | -2ms | -36.629
| |  P99| 49ms| 16ms | -33ms | -67.968
| UserStore.GetMany |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.636
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.879
| UserStore.GetProfilesByUsernames |  Avg| 4ms| 3ms | -1ms | -24.098
| |  P99| 42ms| 9ms | -33ms | -77.938
| UserStore.GetProfilesInChannel |  Avg| 27ms| 24ms | -3ms | -11.139
| |  P99| 85ms| 48ms | -37ms | -43.479
| UserStore.GetProfilesInChannelByAdmin |  Avg| 10ms| 0s | -10ms | -98.345
| |  P99| 25ms| 0s | -25ms | -101.833
| UserStore.GetUnreadCount |  Avg| 4ms| 3ms | -1ms | -24.196
| |  P99| 41ms| 17ms | -24ms | -57.856
| UserStore.GetUnreadCountForChannel |  Avg| 3ms| 2ms | -1ms | -30.094
| |  P99| 34ms| 9ms | -25ms | -74.142
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 129ms| 64ms | -65ms | -50.359
| |  P99| 490ms| 248ms | -242ms | -49.366
| UserStore.IsEmpty |  Avg| 3ms| 1ms | -2ms | -74.137
| |  P99| 27ms| 11ms | -16ms | -60.200
| UserStore.Save |  Avg| 77ms| 66ms | -11ms | -14.320
| |  P99| 242ms| 115ms | -127ms | -52.565
| UserStore.Search |  Avg| 7ms| 20ms | 13ms | 177.727
| |  P99| 47ms| 98ms | 51ms | 108.213
| UserStore.Update |  Avg| 7ms| 6ms | -1ms | -13.448
| |  P99| 75ms| 22ms | -53ms | -70.638
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 3ms | -3ms | -54.130
| |  P99| 49ms| 21ms | -28ms | -57.712
| UserStore.UpdateUpdateAt |  Avg| 6ms| 4ms | -2ms | -33.895
| |  P99| 44ms| 20ms | -24ms | -54.811
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 2ms | -2ms | -52.047
| |  P99| 42ms| 15ms | -27ms | -64.225
| WebhookStore.AnalyticsIncomingCount |  Avg| 1ms| 0s | -1ms | -75.354
| |  P99| 5ms| 0s | -5ms | -101.010
| WebhookStore.AnalyticsOutgoingCount |  Avg| 7ms| 0s | -7ms | -105.620
| |  P99| 10ms| 0s | -10ms | -100.503
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 5ms | -1ms | -15.902
| |  P99| 49ms| 28ms | -21ms | -43.285
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| acknowledgePost | Avg| 24ms| 0s | -24ms | -101.517
| | P99| 223ms| 0s | -223ms | -99.796
| addChannelMember | Avg| 250ms| 118ms | -132ms | -52.817
| | P99| 945ms| 474ms | -471ms | -49.850
| addTeamMember | Avg| 1.12s| 769ms | -351ms | -31.341
| | P99| 4.393s| 2.401s | -1.992s | -45.341
| autocompleteChannelsForTeamForSearch | Avg| 58ms| 56ms | -2ms | -3.456
| | P99| 1.545s| 1.93s | 385ms | 24.917
| autocompleteUsers | Avg| 10ms| 24ms | 14ms | 134.646
| | P99| 112ms| 99ms | -13ms | -11.622
| channelMemberCountsByGroup | Avg| 6ms| 0s | -6ms | -93.065
| | P99| 78ms| 0s | -78ms | -99.695
| createCategoryForTeamForUser | Avg| 44ms| 37ms | -7ms | -15.853
| | P99| 231ms| 96ms | -135ms | -58.396
| createChannel | Avg| 24ms| 11ms | -13ms | -53.127
| | P99| 171ms| 80ms | -91ms | -53.313
| createDirectChannel | Avg| 296ms| 199ms | -97ms | -32.732
| | P99| 1.208s| 492ms | -716ms | -59.278
| createGroupChannel | Avg| 466ms| 304ms | -162ms | -34.800
| | P99| 1.976s| 867ms | -1.109s | -56.129
| createPost | Avg| 451ms| 539ms | 88ms | 19.516
| | P99| 2.152s| 999ms | -1.153s | -53.571
| createUser | Avg| 143ms| 91ms | -52ms | -36.245
| | P99| 494ms| 242ms | -252ms | -50.971
| deleteDraft | Avg| 2ms| 0s | -2ms | -92.754
| | P99| 5ms| 0s | -5ms | -101.010
| deletePost | Avg| 20ms| 18ms | -2ms | -9.916
| | P99| 126ms| 47ms | -79ms | -62.589
| followThreadByUser | Avg| 18ms| 13ms | -5ms | -27.627
| | P99| 183ms| 46ms | -137ms | -75.065
| getAllTeams | Avg| 6ms| 3ms | -3ms | -53.571
| | P99| 59ms| 16ms | -43ms | -72.416
| getAnalytics | Avg| 73ms| 0s | -73ms | -100.254
| | P99| 242ms| 0s | -242ms | -100.000
| getCategoriesForTeamForUser | Avg| 37ms| 29ms | -8ms | -21.673
| | P99| 197ms| 60ms | -137ms | -69.551
| getChannel | Avg| 9ms| 4ms | -5ms | -56.431
| | P99| 84ms| 18ms | -66ms | -78.595
| getChannelMember | Avg| 6ms| 3ms | -3ms | -52.032
| | P99| 53ms| 11ms | -42ms | -78.717
| getChannelMembers | Avg| 7ms| 5ms | -2ms | -28.420
| | P99| 47ms| 18ms | -29ms | -61.074
| getChannelMembersByIds | Avg| 148ms| 0s | -148ms | -99.961
| | P99| 249ms| 0s | -249ms | -100.201
| getChannelMembersForTeamForUser | Avg| 6ms| 2ms | -4ms | -65.456
| | P99| 50ms| 9ms | -41ms | -82.632
| getChannelStats | Avg| 11ms| 5ms | -6ms | -56.677
| | P99| 99ms| 47ms | -52ms | -52.717
| getChannelUnread | Avg| 5ms| 4ms | -1ms | -22.207
| | P99| 37ms| 10ms | -27ms | -72.369
| getChannelsForTeamForUser | Avg| 6ms| 2ms | -4ms | -71.338
| | P99| 59ms| 10ms | -49ms | -82.422
| getChannelsForUser | Avg| 4ms| 3ms | -1ms | -27.507
| | P99| 30ms| 9ms | -21ms | -70.681
| getClientConfig | Avg| 39ms| 3ms | -36ms | -93.499
| | P99| 230ms| 23ms | -207ms | -90.192
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getConfig | Avg| 50ms| 0s | -50ms | -99.720
| | P99| 99ms| 0s | -99ms | -100.000
| getDrafts | Avg| 9ms| 0s | -9ms | -95.261
| | P99| 25ms| 0s | -25ms | -101.214
| getEnvironmentConfig | Avg| 24ms| 0s | -24ms | -98.245
| | P99| 25ms| 0s | -25ms | -100.604
| getFilePreview | Avg| 44ms| 40ms | -4ms | -9.155
| | P99| 202ms| 158ms | -44ms | -21.789
| getFileThumbnail | Avg| 37ms| 35ms | -2ms | -5.392
| | P99| 143ms| 97ms | -46ms | -32.098
| getFilteredUsersStats | Avg| 48ms| 0s | -48ms | -100.050
| | P99| 99ms| 0s | -99ms | -99.748
| getGroups | Avg| 5ms| 0s | -5ms | -107.291
| | P99| 24ms| 0s | -24ms | -98.967
| getGroupsAssociatedToChannelsByTeam | Avg| 3ms| 0s | -3ms | -93.772
| | P99| 10ms| 0s | -10ms | -102.565
| getJobsByType | Avg| 2ms| 0s | -2ms | -86.088
| | P99| 5ms| 0s | -5ms | -101.010
| getNewTeamMembersSince | Avg| 22ms| 0s | -22ms | -100.340
| | P99| 48ms| 0s | -48ms | -100.645
| getPlugins | Avg| 1ms| 0s | -1ms | -145.953
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 17ms| 10ms | -7ms | -41.919
| | P99| 172ms| 32ms | -140ms | -81.269
| getPostsForChannel | Avg| 103ms| 96ms | -7ms | -6.783
| | P99| 1.107s| 916ms | -191ms | -17.261
| getPostsForChannelAroundLastUnread | Avg| 53ms| 19ms | -34ms | -63.704
| | P99| 849ms| 95ms | -754ms | -88.821
| getPreferences | Avg| 7ms| 3ms | -4ms | -55.254
| | P99| 62ms| 19ms | -43ms | -69.529
| getPrevTrialLicense | Avg| 3ms| 0s | -3ms | -103.514
| | P99| 24ms| 0s | -24ms | -100.840
| getProductNotices | Avg| 10ms| 0s | -10ms | -98.060
| | P99| 25ms| 0s | -25ms | -101.793
| getProfileImage | Avg| 124ms| 106ms | -18ms | -14.544
| | P99| 474ms| 453ms | -21ms | -4.428
| getPublicChannelsForTeam | Avg| 20ms| 11ms | -9ms | -44.891
| | P99| 74ms| 34ms | -40ms | -54.155
| getRolesByNames | Avg| 3ms| 0s | -3ms | -119.111
| | P99| 10ms| 0s | -10ms | -101.779
| getTeamMembersForUser | Avg| 6ms| 3ms | -3ms | -48.391
| | P99| 69ms| 19ms | -50ms | -72.085
| getTeamsForUser | Avg| 5ms| 3ms | -2ms | -37.927
| | P99| 48ms| 16ms | -32ms | -66.279
| getTeamsUnreadForUser | Avg| 9ms| 3ms | -6ms | -69.081
| | P99| 86ms| 19ms | -67ms | -77.566
| getThreadsForUser | Avg| 6ms| 2ms | -4ms | -66.436
| | P99| 47ms| 10ms | -37ms | -78.953
| getTopChannelsForTeamSince | Avg| 184ms| 0s | -184ms | -100.017
| | P99| 2.14s| 0s | -2.14s | -100.006
| getTopChannelsForUserSince | Avg| 24ms| 0s | -24ms | -100.408
| | P99| 96ms| 0s | -96ms | -99.485
| getTopDMsForUserSince | Avg| 146ms| 0s | -146ms | -99.872
| | P99| 464ms| 0s | -464ms | -99.904
| getTopInactiveChannelsForTeamSince | Avg| 90ms| 0s | -90ms | -100.044
| | P99| 246ms| 0s | -246ms | -99.915
| getTopInactiveChannelsForUserSince | Avg| 92ms| 0s | -92ms | -99.742
| | P99| 243ms| 0s | -243ms | -100.046
| getTopReactionsForTeamSince | Avg| 137ms| 0s | -137ms | -99.877
| | P99| 249ms| 0s | -249ms | -100.201
| getTopReactionsForUserSince | Avg| 122ms| 0s | -122ms | -99.768
| | P99| 249ms| 0s | -249ms | -100.201
| getTopThreadsForTeamSince | Avg| 118ms| 2ms | -116ms | -98.677
| | P99| 1.791s| 5ms | -1.786s | -99.715
| getTopThreadsForUserSince | Avg| 33ms| 2ms | -31ms | -94.301
| | P99| 215ms| 8ms | -207ms | -96.179
| getTotalUsersStats | Avg| 67ms| 0s | -67ms | -99.552
| | P99| 99ms| 0s | -99ms | -100.000
| getUser | Avg| 9ms| 3ms | -6ms | -69.409
| | P99| 101ms| 18ms | -83ms | -82.038
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 0s | -1ms | -195.387
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 12ms| 7ms | -5ms | -41.605
| | P99| 99ms| 44ms | -55ms | -55.784
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 13ms| 8ms | -5ms | -37.659
| getUsersByNames | Avg| 4ms| 3ms | -1ms | -22.989
| | P99| 43ms| 9ms | -34ms | -79.029
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| gqlWebChannelsAndChannelMembers | Avg| 34ms| 24ms | -10ms | -29.339
| | P99| 231ms| 54ms | -177ms | -76.543
| gqlWebCurrentUserInfo | Avg| 57ms| 37ms | -20ms | -34.791
| | P99| 221ms| 67ms | -154ms | -69.786
| handleCheckCWSConnection | Avg| 39ms| 0s | -39ms | -100.304
| | P99| 50ms| 0s | -50ms | -100.503
| login | Avg| 137ms| 78ms | -59ms | -43.193
| | P99| 894ms| 395ms | -499ms | -55.847
| logout | Avg| 56ms| 45ms | -11ms | -19.745
| | P99| 235ms| 135ms | -100ms | -42.592
| patchPost | Avg| 43ms| 31ms | -12ms | -27.781
| | P99| 213ms| 58ms | -155ms | -72.764
| patchUser | Avg| 317ms| 0s | -317ms | -100.062
| | P99| 498ms| 0s | -498ms | -100.101
| removeUserCustomStatus | Avg| 181ms| 131ms | -50ms | -27.568
| | P99| 498ms| 449ms | -49ms | -9.834
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 23ms| 18ms | -5ms | -21.288
| | P99| 207ms| 49ms | -158ms | -76.501
| searchAllChannels | Avg| 61ms| 42ms | -19ms | -31.282
| | P99| 216ms| 99ms | -117ms | -54.098
| searchFilesInTeam | Avg| 7ms| 0s | -7ms | -94.637
| | P99| 10ms| 0s | -10ms | -100.503
| searchGroupChannels | Avg| 15ms| 13ms | -2ms | -12.946
| | P99| 59ms| 33ms | -26ms | -44.213
| searchPostsInTeam | Avg| 208ms| 105ms | -103ms | -49.426
| | P99| 2.364s| 2.242s | -122ms | -5.162
| searchUsers | Avg| 8ms| 21ms | 13ms | 163.062
| | P99| 48ms| 98ms | 50ms | 104.883
| setPostReminder | Avg| 28ms| 20ms | -8ms | -28.634
| | P99| 208ms| 25ms | -183ms | -87.987
| unfollowThreadByUser | Avg| 10ms| 13ms | 3ms | 29.967
| | P99| 140ms| 25ms | -115ms | -82.279
| updateCategoriesForTeamForUser | Avg| 104ms| 95ms | -9ms | -8.629
| | P99| 304ms| 240ms | -64ms | -21.070
| updateCategoryForTeamForUser | Avg| 141ms| 0s | -141ms | -99.875
| | P99| 248ms| 0s | -248ms | -99.799
| updateConfig | Avg| 375ms| 0s | -375ms | -100.083
| | P99| 498ms| 0s | -498ms | -100.101
| updatePreferences | Avg| 8ms| 6ms | -2ms | -26.514
| | P99| 86ms| 20ms | -66ms | -76.853
| updateReadStateAllThreadsByUser | Avg| 3ms| 2ms | -1ms | -34.203
| | P99| 24ms| 21ms | -3ms | -12.258
| updateReadStateThreadByUser | Avg| 41ms| 36ms | -5ms | -12.240
| | P99| 227ms| 88ms | -139ms | -61.207
| updateUserCustomStatus | Avg| 195ms| 150ms | -45ms | -23.079
| | P99| 614ms| 470ms | -144ms | -23.438
| uploadFileStream | Avg| 451ms| 437ms | -14ms | -3.105
| | P99| 993ms| 997ms | 4ms | 0.403
| viewChannel | Avg| 21ms| 15ms | -6ms | -28.209
| | P99| 208ms| 46ms | -162ms | -77.937

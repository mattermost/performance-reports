### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 1ms | 7ms | 6ms | 459.03
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 5ms | 3ms | 188.66
| UserStore.GetMany | avg | 1ms | 3ms | 2ms | 153.96
| ComplianceStore.MessageExport | avg | 3ms | 5ms | 2ms | 62.77
| UserStore.GetProfilesInChannel | avg | 111ms | 170ms | 59ms | 53.34
| ChannelStore.AnalyticsTypeCount | avg | 8ms | 11ms | 3ms | 39.54
| ChannelStore.GetTeamChannels | avg | 18ms | 22ms | 4ms | 22.01
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 19ms | 23ms | 4ms | 20.84
| PostStore.Update | avg | 11ms | 13ms | 2ms | 17.52
| UserStore.AnalyticsActiveCount | avg | 18ms | 21ms | 3ms | 16.22
| PostStore.SearchPostsForUser | avg | 151ms | 172ms | 21ms | 13.88
| ChannelStore.UpdateSidebarCategories | avg | 43ms | 45ms | 2ms | 4.63
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 9ms | 140ms | 131ms | 1416.22
| TokenStore.Cleanup | p99 | 5ms | 25ms | 20ms | 403.89
| PostStore.GetPostsAfter | p99 | 8ms | 40ms | 32ms | 402.47
| UserStore.GetMany | p99 | 5ms | 24ms | 19ms | 383.84
| PostStore.Update | p99 | 25ms | 71ms | 46ms | 185.34
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 25ms | 15ms | 150.74
| JobStore.Save | p99 | 9ms | 23ms | 14ms | 147.76
| PluginStore.List | p99 | 9ms | 22ms | 13ms | 138.30
| RoleStore.ChannelHigherScopedPermissions | p99 | 18ms | 40ms | 22ms | 125.15
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 10ms | 5ms | 101.01
| PluginStore.Get | p99 | 5ms | 10ms | 5ms | 101.01
| UserStore.AnalyticsActiveCount | p99 | 25ms | 48ms | 23ms | 92.56
| PostAcknowledgementStore.GetForPost | p99 | 23ms | 43ms | 20ms | 86.60
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 18ms | 8ms | 83.77
| ChannelStore.AutocompleteInTeamForSearch | p99 | 99ms | 181ms | 82ms | 82.57
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 9ms | 4ms | 80.76
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 9ms | 4ms | 80.76
| PostPriorityStore.GetForPost | p99 | 21ms | 37ms | 16ms | 76.37
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 149ms | 201ms | 52ms | 34.96
| ChannelStore.GetPinnedPostCount | p99 | 17ms | 20ms | 3ms | 17.38
| ClusterDiscoveryStore.SetLastPingAt | p99 | 21ms | 24ms | 3ms | 14.60
| UserStore.GetUnreadCount | p99 | 22ms | 25ms | 3ms | 13.47
| PostStore.GetSingle | p99 | 18ms | 20ms | 2ms | 10.92
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 212ms | 234ms | 22ms | 10.36
| UserAccessTokenStore.GetByToken | p99 | 21ms | 23ms | 2ms | 9.35
| PostStore.Get | p99 | 43ms | 47ms | 4ms | 9.26
| ChannelStore.GetAllChannelMembersForUser | p99 | 33ms | 35ms | 2ms | 6.02
| ChannelStore.UpdateSidebarCategories | p99 | 211ms | 223ms | 12ms | 5.69
| ChannelStore.GetGuestCount | p99 | 43ms | 45ms | 2ms | 4.60
| ThreadStore.MaintainMembership | p99 | 45ms | 47ms | 2ms | 4.45
| PostStore.SearchPostsForUser | p99 | 2.275s | 2.332s | 57ms | 2.51
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -116.52
| SchemeStore.GetAllPage | avg | 4ms | 0s | -4ms | -114.23
| DraftStore.Upsert | avg | 3ms | 0s | -3ms | -106.48
| AuditStore.Get | avg | 16ms | 0s | -16ms | -100.14
| FileInfoStore.Search | avg | 7ms | 0s | -7ms | -99.13
| BotStore.Save | avg | 2ms | 0s | -2ms | -85.90
| LicenseStore.GetAll | avg | 3ms | 1ms | -2ms | -64.25
| StatusStore.SaveOrUpdate | avg | 11ms | 4ms | -7ms | -62.72
| PostStore.AnalyticsPostCount | avg | 398ms | 228ms | -170ms | -42.70
| ChannelStore.CreateDirectChannel | avg | 23ms | 19ms | -4ms | -17.02
| ChannelStore.Save | avg | 15ms | 13ms | -2ms | -13.74
| TeamStore.GetTotalMemberCount | avg | 30ms | 28ms | -2ms | -6.70
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| FileInfoStore.GetByIds | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.86
| AuditStore.Get | p99 | 25ms | 0s | -25ms | -100.60
| FileInfoStore.Search | p99 | 10ms | 0s | -10ms | -100.50
| StatusStore.SaveOrUpdate | p99 | 210ms | 31ms | -179ms | -85.42
| LicenseStore.GetAll | p99 | 24ms | 5ms | -19ms | -79.83
| JobStore.UpdateStatus | p99 | 22ms | 5ms | -17ms | -77.81
| JobStore.GetCountByStatusAndType | p99 | 50ms | 18ms | -32ms | -64.32
| JobStore.UpdateOptimistically | p99 | 18ms | 7ms | -11ms | -60.03
| ThreadStore.MarkAllAsReadByChannels | p99 | 39ms | 18ms | -21ms | -53.51
| ThreadStore.Get | p99 | 34ms | 16ms | -18ms | -52.54
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 5ms | -5ms | -51.02
| PostStore.AnalyticsPostCount | p99 | 990ms | 495ms | -495ms | -50.00
| ChannelStore.CreateSidebarCategory | p99 | 49ms | 25ms | -24ms | -49.48
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -48.98
| TeamStore.GetTotalMemberCount | p99 | 94ms | 50ms | -44ms | -46.81
| PostPersistentNotificationStore.Get | p99 | 9ms | 5ms | -4ms | -45.99
| PostStore.GetPostReminderMetadata | p99 | 9ms | 5ms | -4ms | -43.22
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 16ms | 9ms | -7ms | -42.78
| ChannelStore.CreateDirectChannel | p99 | 221ms | 138ms | -83ms | -37.55
| JobStore.GetAllByTypePage | p99 | 8ms | 5ms | -3ms | -37.16
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 60ms | 38ms | -22ms | -36.66
| TeamStore.GetMember | p99 | 13ms | 9ms | -4ms | -29.70
| UserStore.GetByUsername | p99 | 42ms | 30ms | -12ms | -28.73
| FileInfoStore.SetContent | p99 | 68ms | 49ms | -19ms | -27.94
| ReactionStore.GetForPost | p99 | 29ms | 21ms | -8ms | -27.77
| ChannelStore.GetChannelsByUser | p99 | 38ms | 28ms | -10ms | -26.23
| JobStore.GetAllByStatus | p99 | 46ms | 37ms | -9ms | -19.66
| UserStore.GetAllProfiles | p99 | 31ms | 25ms | -6ms | -19.22
| PluginStore.Delete | p99 | 31ms | 25ms | -6ms | -19.11
| JobStore.UpdateStatusOptimistically | p99 | 22ms | 18ms | -4ms | -18.31
| SessionStore.Save | p99 | 70ms | 58ms | -12ms | -17.04
| ProductNoticesStore.View | p99 | 340ms | 283ms | -57ms | -16.78
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 38ms | 32ms | -6ms | -15.64
| ChannelStore.GetMemberForPost | p99 | 34ms | 29ms | -5ms | -14.84
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 34ms | 29ms | -5ms | -14.76
| PluginStore.SetWithOptions | p99 | 56ms | 48ms | -8ms | -14.26
| ChannelStore.Get | p99 | 36ms | 32ms | -4ms | -11.26
| ChannelStore.GetMembersForUser | p99 | 36ms | 32ms | -4ms | -11.03
| UserStore.GetForLogin | p99 | 45ms | 40ms | -5ms | -11.00
| PostStore.GetPostIdAfterTime | p99 | 38ms | 34ms | -4ms | -10.62
| UserStore.GetProfilesByUsernames | p99 | 28ms | 25ms | -3ms | -10.58
| ChannelStore.GetMember | p99 | 50ms | 45ms | -5ms | -10.09
| FileInfoStore.Get | p99 | 22ms | 20ms | -2ms | -9.23
| PostStore.GetPostsBefore | p99 | 33ms | 30ms | -3ms | -9.20
| FileInfoStore.Save | p99 | 34ms | 31ms | -3ms | -8.89
| FileInfoStore.AttachToPost | p99 | 46ms | 42ms | -4ms | -8.77
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 109ms | 100ms | -9ms | -8.24
| TeamStore.SaveMember | p99 | 187ms | 172ms | -15ms | -8.01
| UserStore.UpdateLastLogin | p99 | 37ms | 34ms | -3ms | -8.01
| ThreadStore.GetTotalUnreadThreads | p99 | 39ms | 36ms | -3ms | -7.76
| ThreadStore.GetTotalUnreadMentions | p99 | 39ms | 36ms | -3ms | -7.74
| ThreadStore.GetTotalThreads | p99 | 40ms | 37ms | -3ms | -7.50
| UserStore.AutocompleteUsersInChannel | p99 | 294ms | 272ms | -22ms | -7.49
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 41ms | 38ms | -3ms | -7.40
| ChannelStore.GetMemberLastViewedAt | p99 | 41ms | 38ms | -3ms | -7.37
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 42ms | 39ms | -3ms | -7.13
| SessionStore.Get | p99 | 85ms | 79ms | -6ms | -7.10
| PreferenceStore.Get | p99 | 30ms | 28ms | -2ms | -6.64
| PreferenceStore.GetAll | p99 | 46ms | 43ms | -3ms | -6.57
| ChannelStore.IncrementMentionCount | p99 | 32ms | 30ms | -2ms | -6.34
| ChannelStore.GetChannels | p99 | 33ms | 31ms | -2ms | -6.01
| PostAcknowledgementStore.GetForPosts | p99 | 34ms | 32ms | -2ms | -5.88
| PostPriorityStore.GetForPosts | p99 | 37ms | 35ms | -2ms | -5.46
| ChannelStore.SearchGroupChannels | p99 | 37ms | 35ms | -2ms | -5.41
| ChannelStore.Save | p99 | 93ms | 88ms | -5ms | -5.36
| UserStore.UpdateUpdateAt | p99 | 38ms | 36ms | -2ms | -5.24
| TeamStore.GetTeamsByUserId | p99 | 41ms | 39ms | -2ms | -4.92
| PostStore.GetPosts | p99 | 41ms | 39ms | -2ms | -4.87
| SystemStore.GetByName | p99 | 41ms | 39ms | -2ms | -4.87
| StatusStore.Get | p99 | 41ms | 39ms | -2ms | -4.85
| UserTermsOfServiceStore.GetByUser | p99 | 41ms | 39ms | -2ms | -4.85
| TeamStore.GetAllPage | p99 | 43ms | 41ms | -2ms | -4.63
| AuditStore.Save | p99 | 44ms | 42ms | -2ms | -4.58
| WebhookStore.GetOutgoingByTeam | p99 | 45ms | 43ms | -2ms | -4.47
| GroupStore.GetByName | p99 | 45ms | 43ms | -2ms | -4.40
| ThreadStore.GetTeamsUnreadForUser | p99 | 47ms | 45ms | -2ms | -4.26
| ChannelStore.GetByName | p99 | 48ms | 46ms | -2ms | -4.20
| PreferenceStore.Save | p99 | 100ms | 96ms | -4ms | -4.02
| ChannelStore.SaveMember | p99 | 233ms | 224ms | -9ms | -3.87
| ChannelStore.CreateInitialSidebarCategories | p99 | 225ms | 218ms | -7ms | -3.12
| ChannelStore.GetSidebarCategory | p99 | 88ms | 86ms | -2ms | -2.27
| PostStore.Save | p99 | 91ms | 89ms | -2ms | -2.20
| ChannelStore.GetMemberCount | p99 | 92ms | 90ms | -2ms | -2.18
| UserStore.GetAllProfilesInChannel | p99 | 951ms | 941ms | -10ms | -1.05
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 2ms | 5ms | 3ms | 180.06
| getAnalytics | avg | 24ms | 28ms | 4ms | 16.40
| getFilteredUsersStats | avg | 12ms | 14ms | 2ms | 16.37
| unfollowThreadByUser | avg | 13ms | 15ms | 2ms | 14.99
| logout | avg | 48ms | 54ms | 6ms | 12.60
| searchPostsInTeam | avg | 160ms | 179ms | 19ms | 11.90
| addChannelMember | avg | 267ms | 296ms | 29ms | 10.86
| patchPost | avg | 30ms | 33ms | 3ms | 9.88
| getPostsForChannel | avg | 23ms | 25ms | 2ms | 8.75
| updateCategoriesForTeamForUser | avg | 63ms | 65ms | 2ms | 3.17
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembersForUser | p99 | 10ms | 24ms | 14ms | 140.70
| logout | p99 | 98ms | 233ms | 135ms | 137.75
| updateReadStateAllThreadsByUser | p99 | 5ms | 10ms | 5ms | 101.01
| unfollowThreadByUser | p99 | 88ms | 172ms | 84ms | 95.62
| addChannelMember | p99 | 499ms | 967ms | 468ms | 93.75
| autocompleteChannelsForTeamForSearch | p99 | 99ms | 189ms | 90ms | 90.62
| getChannel | p99 | 88ms | 145ms | 57ms | 65.13
| patchPost | p99 | 492ms | 713ms | 221ms | 44.88
| getTeamMember | p99 | 39ms | 47ms | 8ms | 20.68
| getPostThread | p99 | 84ms | 99ms | 15ms | 17.89
| getPostsForChannel | p99 | 226ms | 248ms | 22ms | 9.75
| getChannelsForUser | p99 | 40ms | 42ms | 2ms | 4.97
| updateCategoriesForTeamForUser | p99 | 438ms | 455ms | 17ms | 3.89
| searchPostsInTeam | p99 | 2.318s | 2.354s | 36ms | 1.55
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | avg | 9ms | 0s | -9ms | -104.24
| getChannelMembers | avg | 3ms | 0s | -3ms | -100.39
| patchConfig | avg | 311ms | 0s | -311ms | -99.89
| getAudits | avg | 16ms | 0s | -16ms | -99.10
| getPrevTrialLicense | avg | 5ms | 1ms | -4ms | -79.80
| upsertDraft | avg | 4ms | 2ms | -2ms | -48.34
| followThreadByUser | avg | 19ms | 11ms | -8ms | -41.63
| autocompleteUsers | avg | 44ms | 42ms | -2ms | -4.57
| createChannel | avg | 312ms | 304ms | -8ms | -2.56
| getProfileImage | avg | 85ms | 83ms | -2ms | -2.34
| createUser | avg | 187ms | 183ms | -4ms | -2.14
| createGroupChannel | avg | 521ms | 511ms | -10ms | -1.92
| removeUserCustomStatus | avg | 215ms | 211ms | -4ms | -1.86
| createPost | avg | 348ms | 342ms | -6ms | -1.73
| addTeamMember | avg | 964ms | 953ms | -11ms | -1.14
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| getAudits | p99 | 25ms | 0s | -25ms | -100.60
| searchFiles | p99 | 10ms | 0s | -10ms | -100.50
| patchConfig | p99 | 498ms | 0s | -498ms | -100.10
| followThreadByUser | p99 | 232ms | 25ms | -207ms | -89.22
| getPrevTrialLicense | p99 | 24ms | 5ms | -19ms | -78.35
| upsertDraft | p99 | 10ms | 5ms | -5ms | -51.31
| getJobsByType | p99 | 8ms | 5ms | -3ms | -37.16
| updatePreferences | p99 | 65ms | 44ms | -21ms | -32.23
| removeUserCustomStatus | p99 | 670ms | 489ms | -181ms | -27.02
| createGroupChannel | p99 | 2.005s | 1.495s | -510ms | -25.44
| addTeamMember | p99 | 4.03s | 3.496s | -534ms | -13.25
| getUsersByNames | p99 | 31ms | 27ms | -4ms | -12.83
| getClientConfig | p99 | 113ms | 99ms | -14ms | -12.34
| createDirectChannel | p99 | 975ms | 860ms | -115ms | -11.79
| autocompleteUsers | p99 | 230ms | 207ms | -23ms | -10.00
| getCategoriesForTeamForUser | p99 | 132ms | 119ms | -13ms | -9.82
| getAllTeams | p99 | 52ms | 47ms | -5ms | -9.68
| getUser | p99 | 94ms | 86ms | -8ms | -8.48
| getChannelStats | p99 | 61ms | 56ms | -5ms | -8.25
| getTeamsUnreadForUser | p99 | 81ms | 75ms | -6ms | -7.43
| getChannelMember | p99 | 170ms | 159ms | -11ms | -6.46
| saveReaction | p99 | 89ms | 84ms | -5ms | -5.65
| createUser | p99 | 915ms | 864ms | -51ms | -5.57
| searchGroupChannels | p99 | 37ms | 35ms | -2ms | -5.41
| login | p99 | 779ms | 737ms | -42ms | -5.39
| getTeamsForUser | p99 | 44ms | 42ms | -2ms | -4.58
| getChannelMembersForTeamForUser | p99 | 44ms | 42ms | -2ms | -4.57
| getChannelsForTeamForUser | p99 | 46ms | 44ms | -2ms | -4.34
| getPreferences | p99 | 49ms | 47ms | -2ms | -4.12
| getPublicChannelsForTeam | p99 | 49ms | 47ms | -2ms | -4.05
| getPostsForChannelAroundLastUnread | p99 | 230ms | 221ms | -9ms | -3.92
| getFilePreview | p99 | 195ms | 188ms | -7ms | -3.60
| getUsers | p99 | 89ms | 86ms | -3ms | -3.36
| viewChannel | p99 | 97ms | 94ms | -3ms | -3.08
| getTeamMembersForUser | p99 | 68ms | 66ms | -2ms | -2.95
| updateReadStateThreadByUser | p99 | 219ms | 213ms | -6ms | -2.74
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Get |  Avg| 16ms| 0s | -16ms | -100.138
| |  P99| 25ms| 0s | -25ms | -100.604
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.584
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 61.081
| |  P99| 9ms| 10ms | 1ms | 11.173
| BotStore.Save |  Avg| 2ms| 0s | -2ms | -85.902
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 74ms| 74ms | 0s | 0.000
| |  P99| 149ms| 201ms | 52ms | 34.958
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 29ms | -5ms | -14.756
| ChannelStore.AnalyticsTypeCount |  Avg| 8ms| 11ms | 3ms | 39.544
| |  P99| 10ms| 25ms | 15ms | 150.737
| ChannelStore.Autocomplete |  Avg| 45ms| 46ms | 1ms | 2.228
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 22ms| 23ms | 1ms | 4.569
| |  P99| 99ms| 181ms | 82ms | 82.567
| ChannelStore.CreateDirectChannel |  Avg| 23ms| 19ms | -4ms | -17.025
| |  P99| 221ms| 138ms | -83ms | -37.553
| ChannelStore.CreateInitialSidebarCategories |  Avg| 25ms| 24ms | -1ms | -3.995
| |  P99| 225ms| 218ms | -7ms | -3.118
| ChannelStore.CreateSidebarCategory |  Avg| 23ms| 24ms | 1ms | 4.343
| |  P99| 49ms| 25ms | -24ms | -49.479
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 32ms | -4ms | -11.259
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 60ms| 38ms | -22ms | -36.664
| ChannelStore.GetAllChannelMembersForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 33ms| 35ms | 2ms | 6.025
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 19ms| 23ms | 4ms | 20.837
| |  P99| 212ms| 234ms | 22ms | 10.362
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.204
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 31ms | -2ms | -6.012
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 3ms | -1ms | -28.297
| |  P99| 38ms| 28ms | -10ms | -26.226
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.047
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.599
| ChannelStore.GetMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 50ms| 45ms | -5ms | -10.092
| ChannelStore.GetMemberCount |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 92ms| 90ms | -2ms | -2.181
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 29ms | -5ms | -14.841
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 38ms | -3ms | -7.371
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -116.523
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 32ms | -4ms | -11.030
| ChannelStore.GetMembersForUserWithPagination |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.576
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 2ms | 1ms | 69.580
| |  P99| 17ms| 20ms | 3ms | 17.384
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 19ms | 1ms | 5.604
| |  P99| 46ms| 47ms | 1ms | 2.177
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 18ms| 19ms | 1ms | 5.466
| |  P99| 109ms| 100ms | -9ms | -8.244
| ChannelStore.GetSidebarCategory |  Avg| 10ms| 11ms | 1ms | 10.344
| |  P99| 88ms| 86ms | -2ms | -2.273
| ChannelStore.GetTeamChannels |  Avg| 18ms| 22ms | 4ms | 22.008
| |  P99| 49ms| 25ms | -24ms | -48.980
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 30ms | -2ms | -6.343
| ChannelStore.Save |  Avg| 15ms| 13ms | -2ms | -13.736
| |  P99| 93ms| 88ms | -5ms | -5.357
| ChannelStore.SaveMember |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 233ms| 224ms | -9ms | -3.866
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 35ms | -2ms | -5.412
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.064
| ChannelStore.UpdateSidebarCategories |  Avg| 43ms| 45ms | 2ms | 4.626
| |  P99| 211ms| 223ms | 12ms | 5.687
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -42.775
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 4ms | 1ms | 31.343
| |  P99| 21ms| 24ms | 3ms | 14.599
| CommandWebhookStore.Cleanup |  Avg| 3ms| 2ms | -1ms | -31.094
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 5ms | 2ms | 62.768
| |  P99| 9ms| 140ms | 131ms | 1416.216
| DraftStore.Delete |  Avg| 2ms| 1ms | -1ms | -60.035
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.755
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 0s | -3ms | -106.479
| |  P99| 5ms| 0s | -5ms | -100.859
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.169
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 1ms| 0s | -1ms | -86.282
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 46ms| 42ms | -4ms | -8.770
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.230
| FileInfoStore.GetByIds |  Avg| 1ms| 0s | -1ms | -82.663
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 31ms | -3ms | -8.888
| FileInfoStore.Search |  Avg| 7ms| 0s | -7ms | -99.125
| |  P99| 10ms| 0s | -10ms | -100.503
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.688
| |  P99| 68ms| 49ms | -19ms | -27.943
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 2ms | -1ms | -36.778
| |  P99| 38ms| 32ms | -6ms | -15.643
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.403
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 28ms | -1ms | -3.477
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 1ms | -1ms | -62.954
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 1ms | -1ms | -66.402
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 3ms| 2ms | -1ms | -37.362
| |  P99| 46ms| 37ms | -9ms | -19.657
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.164
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -36.639
| |  P99| 50ms| 18ms | -32ms | -64.322
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 2ms | 1ms | 72.294
| |  P99| 10ms| 18ms | 8ms | 83.770
| JobStore.Save |  Avg| 3ms| 4ms | 1ms | 29.837
| |  P99| 9ms| 23ms | 14ms | 147.757
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 7ms | -11ms | -60.029
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -77.805
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -24.269
| |  P99| 22ms| 18ms | -4ms | -18.307
| LicenseStore.GetAll |  Avg| 3ms| 1ms | -2ms | -64.248
| |  P99| 24ms| 5ms | -19ms | -79.827
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.074
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 25ms | -6ms | -19.109
| PluginStore.Get |  Avg| 1ms| 2ms | 1ms | 93.407
| |  P99| 5ms| 10ms | 5ms | 101.010
| PluginStore.List |  Avg| 2ms| 3ms | 1ms | 56.545
| |  P99| 9ms| 22ms | 13ms | 138.302
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 56ms| 48ms | -8ms | -14.258
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 50.679
| |  P99| 23ms| 43ms | 20ms | 86.603
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 32ms | -2ms | -5.885
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 1ms | -1ms | -57.368
| |  P99| 9ms| 5ms | -4ms | -45.985
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.757
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 37ms | 16ms | 76.370
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 35ms | -2ms | -5.458
| PostStore.AnalyticsPostCount |  Avg| 398ms| 228ms | -170ms | -42.701
| |  P99| 990ms| 495ms | -495ms | -50.000
| PostStore.Delete |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 5ms | 1ms | 22.478
| |  P99| 43ms| 47ms | 4ms | 9.263
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 38ms | -1ms | -2.587
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 34ms | -4ms | -10.618
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.220
| PostStore.GetPostReminders |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 5ms| 4ms | -1ms | -21.915
| |  P99| 41ms| 39ms | -2ms | -4.868
| PostStore.GetPostsAfter |  Avg| 3ms| 4ms | 1ms | 39.558
| |  P99| 8ms| 40ms | 32ms | 402.473
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 30ms | -3ms | -9.200
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 79ms| 79ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.918
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 91ms| 89ms | -2ms | -2.202
| PostStore.SearchPostsForUser |  Avg| 151ms| 172ms | 21ms | 13.878
| |  P99| 2.275s| 2.332s | 57ms | 2.506
| PostStore.SetPostReminder |  Avg| 6ms| 5ms | -1ms | -16.900
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 11ms| 13ms | 2ms | 17.516
| |  P99| 25ms| 71ms | 46ms | 185.345
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.755
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 28ms | -2ms | -6.642
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.574
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 100ms| 96ms | -4ms | -4.017
| ProductNoticesStore.ClearOldNotices |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 38ms| 37ms | -1ms | -2.658
| |  P99| 340ms| 283ms | -57ms | -16.781
| ReactionStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -37.258
| |  P99| 29ms| 21ms | -8ms | -27.768
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -69.442
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 1ms | 1ms | 212.513
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 5ms | 1ms | 27.499
| |  P99| 18ms| 40ms | 22ms | 125.154
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 4ms| 0s | -4ms | -114.229
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 8ms| 7ms | -1ms | -13.328
| |  P99| 85ms| 79ms | -6ms | -7.098
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.662
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.267
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 8ms| 7ms | -1ms | -13.070
| |  P99| 70ms| 58ms | -12ms | -17.040
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 39ms | -2ms | -4.851
| StatusStore.GetByIds |  Avg| 3ms| 2ms | -1ms | -39.293
| |  P99| 24ms| 23ms | -1ms | -4.103
| StatusStore.SaveOrUpdate |  Avg| 11ms| 4ms | -7ms | -62.723
| |  P99| 210ms| 31ms | -179ms | -85.416
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 39ms | -2ms | -4.867
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.882
| TeamStore.GetActiveMemberCount |  Avg| 53ms| 53ms | 0s | 0.000
| |  P99| 99ms| 100ms | 1ms | 1.005
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.628
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 3ms | -1ms | -28.141
| |  P99| 42ms| 39ms | -3ms | -7.133
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 9ms | -4ms | -29.703
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 39ms | -2ms | -4.915
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 43ms | -1ms | -2.260
| TeamStore.GetTotalMemberCount |  Avg| 30ms| 28ms | -2ms | -6.699
| |  P99| 94ms| 50ms | -44ms | -46.810
| TeamStore.SaveMember |  Avg| 31ms| 32ms | 1ms | 3.244
| |  P99| 187ms| 172ms | -15ms | -8.014
| ThreadStore.Get |  Avg| 2ms| 1ms | -1ms | -51.410
| |  P99| 34ms| 16ms | -18ms | -52.545
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.238
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.260
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.231
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.361
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 7ms | 1ms | 15.588
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 31ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 37ms | -3ms | -7.501
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 36ms | -3ms | -7.741
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 36ms | -3ms | -7.764
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 38ms | -3ms | -7.402
| ThreadStore.MaintainMembership |  Avg| 5ms| 6ms | 1ms | 18.200
| |  P99| 45ms| 47ms | 2ms | 4.452
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 18ms | -21ms | -53.511
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 5ms | 3ms | 188.662
| |  P99| 5ms| 10ms | 5ms | 101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 7ms | 6ms | 459.026
| |  P99| 5ms| 25ms | 20ms | 403.892
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.345
| UserStore.AnalyticsActiveCount |  Avg| 18ms| 21ms | 3ms | 16.217
| |  P99| 25ms| 48ms | 23ms | 92.555
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 50ms| 49ms | -1ms | -1.989
| |  P99| 294ms| 272ms | -22ms | -7.487
| UserStore.Count |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.395
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 25ms | -6ms | -19.220
| UserStore.GetAllProfilesInChannel |  Avg| 267ms| 268ms | 1ms | 0.375
| |  P99| 951ms| 941ms | -10ms | -1.052
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 42ms| 30ms | -12ms | -28.734
| UserStore.GetForLogin |  Avg| 4ms| 3ms | -1ms | -27.909
| |  P99| 45ms| 40ms | -5ms | -11.002
| UserStore.GetMany |  Avg| 1ms| 3ms | 2ms | 153.964
| |  P99| 5ms| 24ms | 19ms | 383.838
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 36ms | -1ms | -2.678
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.583
| UserStore.GetProfilesInChannel |  Avg| 111ms| 170ms | 59ms | 53.339
| |  P99| 247ms| 248ms | 1ms | 0.404
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.021
| UserStore.GetUnreadCount |  Avg| 2ms| 3ms | 1ms | 43.874
| |  P99| 22ms| 25ms | 3ms | 13.474
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.Save |  Avg| 75ms| 75ms | 0s | 0.000
| |  P99| 238ms| 237ms | -1ms | -0.420
| UserStore.Search |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 99ms| 98ms | -1ms | -1.013
| UserStore.Update |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 83ms| 83ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.336
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 37ms| 34ms | -3ms | -8.013
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.244
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 39ms | -2ms | -4.847
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.474
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 267ms| 296ms | 29ms | 10.862
| | P99| 499ms| 967ms | 468ms | 93.746
| addTeamMember | Avg| 964ms| 953ms | -11ms | -1.141
| | P99| 4.03s| 3.496s | -534ms | -13.250
| autocompleteChannelsForTeamForSearch | Avg| 22ms| 23ms | 1ms | 4.557
| | P99| 99ms| 189ms | 90ms | 90.622
| autocompleteEmojis | Avg| 1ms| 0s | -1ms | -83.313
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 44ms| 42ms | -2ms | -4.575
| | P99| 230ms| 207ms | -23ms | -10.005
| createCategoryForTeamForUser | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 312ms| 304ms | -8ms | -2.561
| | P99| 498ms| 498ms | 0s | 0.000
| createDirectChannel | Avg| 341ms| 342ms | 1ms | 0.293
| | P99| 975ms| 860ms | -115ms | -11.795
| createGroupChannel | Avg| 521ms| 511ms | -10ms | -1.918
| | P99| 2.005s| 1.495s | -510ms | -25.437
| createPost | Avg| 348ms| 342ms | -6ms | -1.725
| | P99| 2.076s| 2.094s | 18ms | 0.867
| createUser | Avg| 187ms| 183ms | -4ms | -2.139
| | P99| 915ms| 864ms | -51ms | -5.571
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 19ms| 11ms | -8ms | -41.626
| | P99| 232ms| 25ms | -207ms | -89.220
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 52ms| 47ms | -5ms | -9.679
| getAnalytics | Avg| 24ms| 28ms | 4ms | 16.402
| | P99| 49ms| 50ms | 1ms | 2.021
| getAudits | Avg| 16ms| 0s | -16ms | -99.103
| | P99| 25ms| 0s | -25ms | -100.604
| getCategoriesForTeamForUser | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 132ms| 119ms | -13ms | -9.822
| getChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 88ms| 145ms | 57ms | 65.131
| getChannelMember | Avg| 14ms| 13ms | -1ms | -7.378
| | P99| 170ms| 159ms | -11ms | -6.457
| getChannelMembers | Avg| 3ms| 0s | -3ms | -100.395
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 44ms| 42ms | -2ms | -4.569
| getChannelMembersForUser | Avg| 8ms| 9ms | 1ms | 12.691
| | P99| 10ms| 24ms | 14ms | 140.704
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 61ms| 56ms | -5ms | -8.247
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 39ms| 39ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 46ms| 44ms | -2ms | -4.340
| getChannelsForUser | Avg| 4ms| 3ms | -1ms | -22.803
| | P99| 40ms| 42ms | 2ms | 4.968
| getClientConfig | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 113ms| 99ms | -14ms | -12.339
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 43ms| 43ms | 0s | 0.000
| | P99| 195ms| 188ms | -7ms | -3.599
| getFileThumbnail | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 97ms| 96ms | -1ms | -1.031
| getFilteredUsersStats | Avg| 12ms| 14ms | 2ms | 16.366
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -37.164
| getPostThread | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 84ms| 99ms | 15ms | 17.894
| getPostsForChannel | Avg| 23ms| 25ms | 2ms | 8.752
| | P99| 226ms| 248ms | 22ms | 9.751
| getPostsForChannelAroundLastUnread | Avg| 23ms| 22ms | -1ms | -4.338
| | P99| 230ms| 221ms | -9ms | -3.919
| getPreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 49ms| 47ms | -2ms | -4.119
| getPrevTrialLicense | Avg| 5ms| 1ms | -4ms | -79.803
| | P99| 24ms| 5ms | -19ms | -78.348
| getProductNotices | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 85ms| 83ms | -2ms | -2.340
| | P99| 442ms| 438ms | -4ms | -0.904
| getPublicChannelsForTeam | Avg| 19ms| 20ms | 1ms | 5.233
| | P99| 49ms| 47ms | -2ms | -4.047
| getRolesByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 39ms| 47ms | 8ms | 20.684
| getTeamMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 68ms| 66ms | -2ms | -2.948
| getTeamStats | Avg| 55ms| 54ms | -1ms | -1.809
| | P99| 99ms| 100ms | 1ms | 1.005
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 44ms| 42ms | -2ms | -4.578
| getTeamsUnreadForUser | Avg| 7ms| 6ms | -1ms | -15.034
| | P99| 81ms| 75ms | -6ms | -7.427
| getThreadsForUser | Avg| 5ms| 4ms | -1ms | -21.881
| | P99| 44ms| 43ms | -1ms | -2.290
| getUser | Avg| 6ms| 5ms | -1ms | -16.676
| | P99| 94ms| 86ms | -8ms | -8.481
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 89ms| 86ms | -3ms | -3.363
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 27ms | -4ms | -12.828
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 99ms| 98ms | -1ms | -1.005
| | P99| 779ms| 737ms | -42ms | -5.393
| logout | Avg| 48ms| 54ms | 6ms | 12.600
| | P99| 98ms| 233ms | 135ms | 137.753
| patchConfig | Avg| 311ms| 0s | -311ms | -99.889
| | P99| 498ms| 0s | -498ms | -100.101
| patchPost | Avg| 30ms| 33ms | 3ms | 9.876
| | P99| 492ms| 713ms | 221ms | 44.885
| removeUserCustomStatus | Avg| 215ms| 211ms | -4ms | -1.862
| | P99| 670ms| 489ms | -181ms | -27.022
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 89ms| 84ms | -5ms | -5.648
| searchAllChannels | Avg| 45ms| 46ms | 1ms | 2.213
| | P99| 100ms| 100ms | 0s | 0.000
| searchFiles | Avg| 9ms| 0s | -9ms | -104.244
| | P99| 10ms| 0s | -10ms | -100.503
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 37ms| 35ms | -2ms | -5.412
| searchPostsInTeam | Avg| 160ms| 179ms | 19ms | 11.900
| | P99| 2.318s| 2.354s | 36ms | 1.553
| searchUsers | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| setPostReminder | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 15ms | 2ms | 14.988
| | P99| 88ms| 172ms | 84ms | 95.622
| updateCategoriesForTeamForUser | Avg| 63ms| 65ms | 2ms | 3.174
| | P99| 438ms| 455ms | 17ms | 3.885
| updatePreferences | Avg| 8ms| 7ms | -1ms | -12.745
| | P99| 65ms| 44ms | -21ms | -32.232
| updateReadStateAllThreadsByUser | Avg| 2ms| 5ms | 3ms | 180.063
| | P99| 5ms| 10ms | 5ms | 101.010
| updateReadStateThreadByUser | Avg| 40ms| 41ms | 1ms | 2.472
| | P99| 219ms| 213ms | -6ms | -2.741
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 410ms| 408ms | -2ms | -0.488
| | P99| 997ms| 992ms | -5ms | -0.501
| upsertDraft | Avg| 4ms| 2ms | -2ms | -48.337
| | P99| 10ms| 5ms | -5ms | -51.311
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 97ms| 94ms | -3ms | -3.082

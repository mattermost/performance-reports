### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 8ms | 6ms | 285.90
| CommandWebhookStore.Cleanup | avg | 1ms | 3ms | 2ms | 256.65
| ChannelStore.GetSidebarCategory | avg | 20ms | 56ms | 36ms | 178.87
| StatusStore.UpdateExpiredDNDStatuses | avg | 11ms | 27ms | 16ms | 139.89
| ChannelStore.CreateSidebarCategory | avg | 12ms | 27ms | 15ms | 121.57
| UserAccessTokenStore.GetByToken | avg | 3ms | 6ms | 3ms | 105.84
| ChannelStore.UpdateSidebarCategories | avg | 72ms | 124ms | 52ms | 72.37
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 6ms | 2ms | 47.91
| ThreadStore.Get | avg | 15ms | 22ms | 7ms | 46.21
| ComplianceStore.MessageExport | avg | 15ms | 21ms | 6ms | 40.11
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 197ms | 271ms | 74ms | 37.54
| LinkMetadataStore.Save | avg | 5ms | 7ms | 2ms | 36.59
| PostStore.GetPostReminders | avg | 19ms | 26ms | 7ms | 36.59
| ChannelStore.GetMember | avg | 5ms | 7ms | 2ms | 36.49
| DraftStore.GetDraftsForUser | avg | 46ms | 62ms | 16ms | 35.12
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 13ms | 17ms | 4ms | 30.28
| JobStore.Get | avg | 27ms | 35ms | 8ms | 29.48
| JobStore.GetAllByStatus | avg | 17ms | 22ms | 5ms | 29.36
| UserStore.Get | avg | 7ms | 9ms | 2ms | 27.24
| PreferenceStore.DeleteCategoryAndName | avg | 12ms | 15ms | 3ms | 25.70
| JobStore.UpdateOptimistically | avg | 8ms | 10ms | 2ms | 25.46
| ThreadStore.GetMembershipForUser | avg | 17ms | 21ms | 4ms | 24.18
| ReactionStore.GetUniqueCountForPost | avg | 17ms | 21ms | 4ms | 23.61
| ChannelStore.GetChannelsByUser | avg | 18ms | 22ms | 4ms | 22.73
| ThreadStore.GetThreadsForUser | avg | 22ms | 27ms | 5ms | 22.31
| UserStore.GetProfileByIds | avg | 14ms | 17ms | 3ms | 21.83
| PostStore.Update | avg | 25ms | 30ms | 5ms | 20.12
| FileInfoStore.GetForPost | avg | 20ms | 24ms | 4ms | 19.73
| PostStore.GetSingle | avg | 16ms | 19ms | 3ms | 18.25
| PostPersistentNotificationStore.GetSingle | avg | 17ms | 20ms | 3ms | 17.82
| SessionStore.GetSessionsExpired | avg | 12ms | 14ms | 2ms | 17.30
| ThreadStore.GetThreadFollowers | avg | 18ms | 21ms | 3ms | 17.01
| PostStore.Get | avg | 36ms | 42ms | 6ms | 16.66
| ReactionStore.Save | avg | 19ms | 22ms | 3ms | 15.97
| ThreadStore.GetThreadForUser | avg | 25ms | 29ms | 4ms | 15.90
| ChannelStore.GetMemberForPost | avg | 13ms | 15ms | 2ms | 15.68
| PostStore.AnalyticsPostCount | avg | 3.023s | 3.483s | 460ms | 15.22
| TeamStore.GetByName | avg | 13ms | 15ms | 2ms | 15.03
| FileInfoStore.Get | avg | 14ms | 16ms | 2ms | 14.36
| ReactionStore.GetForPost | avg | 21ms | 24ms | 3ms | 14.34
| FileInfoStore.SetContent | avg | 14ms | 16ms | 2ms | 14.31
| WebhookStore.GetOutgoingByTeam | avg | 21ms | 24ms | 3ms | 14.17
| PostStore.SearchPostsForUser | avg | 121ms | 138ms | 17ms | 14.10
| UserStore.Search | avg | 144ms | 164ms | 20ms | 13.84
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 15ms | 17ms | 2ms | 13.47
| PostAcknowledgementStore.GetForPosts | avg | 23ms | 26ms | 3ms | 13.15
| UserStore.GetAllProfiles | avg | 15ms | 17ms | 2ms | 13.03
| PostStore.GetPostsSince | avg | 39ms | 44ms | 5ms | 12.95
| TeamStore.Get | avg | 16ms | 18ms | 2ms | 12.89
| PostPriorityStore.GetForPosts | avg | 24ms | 27ms | 3ms | 12.46
| PreferenceStore.Get | avg | 17ms | 19ms | 2ms | 11.84
| LinkMetadataStore.Get | avg | 17ms | 19ms | 2ms | 11.65
| GroupStore.GetGroups | avg | 18ms | 20ms | 2ms | 11.33
| UserStore.AutocompleteUsersInChannel | avg | 327ms | 364ms | 37ms | 11.32
| ChannelStore.GetPinnedPostCount | avg | 18ms | 20ms | 2ms | 11.10
| ThreadStore.GetTeamsUnreadForUser | avg | 18ms | 20ms | 2ms | 11.02
| ChannelStore.GetMembersForUser | avg | 19ms | 21ms | 2ms | 10.71
| PostStore.GetPostsByThread | avg | 19ms | 21ms | 2ms | 10.71
| StatusStore.SaveOrUpdate | avg | 59ms | 65ms | 6ms | 10.25
| ChannelStore.GetChannels | avg | 20ms | 22ms | 2ms | 10.03
| PostStore.GetPostsBefore | avg | 20ms | 22ms | 2ms | 9.86
| ThreadStore.GetThreadUnreadReplyCount | avg | 21ms | 23ms | 2ms | 9.67
| PostStore.GetEtag | avg | 22ms | 24ms | 2ms | 9.10
| PostStore.Save | avg | 22ms | 24ms | 2ms | 9.04
| ChannelStore.Get | avg | 34ms | 37ms | 3ms | 8.75
| ChannelStore.Autocomplete | avg | 106ms | 115ms | 9ms | 8.49
| ChannelStore.SearchGroupChannels | avg | 26ms | 28ms | 2ms | 7.59
| ChannelStore.CreateInitialSidebarCategories | avg | 36ms | 38ms | 2ms | 5.58
| UserStore.GetAllProfilesInChannel | avg | 851ms | 895ms | 44ms | 5.17
| ChannelStore.GetMemberCount | avg | 236ms | 241ms | 5ms | 2.12
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetSidebarCategory | p99 | 227ms | 1.18s | 953ms | 420.57
| UserAccessTokenStore.GetByToken | p99 | 32ms | 163ms | 131ms | 406.20
| SchemeStore.GetAllPage | p99 | 5ms | 25ms | 20ms | 404.04
| DraftStore.GetDraftsForUser | p99 | 99ms | 244ms | 145ms | 146.46
| PostStore.SearchPostsForUser | p99 | 1.027s | 2.325s | 1.298s | 126.33
| ChannelStore.UpdateSidebarCategories | p99 | 805ms | 1.81s | 1.005s | 124.85
| LinkMetadataStore.Save | p99 | 42ms | 86ms | 44ms | 103.53
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.00
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 50ms | 25ms | 100.81
| PreferenceStore.DeleteCategoryAndName | p99 | 49ms | 94ms | 45ms | 92.54
| FileInfoStore.SetContent | p99 | 98ms | 176ms | 78ms | 79.64
| UserStore.GetProfilesInChannel | p99 | 122ms | 211ms | 89ms | 73.10
| UserStore.GetAllProfilesInChannel | p99 | 2.7s | 4.397s | 1.697s | 62.85
| UserStore.AutocompleteUsersInChannel | p99 | 1.106s | 1.795s | 689ms | 62.30
| ThreadStore.GetThreadUnreadReplyCount | p99 | 249ms | 353ms | 104ms | 41.72
| ComplianceStore.MessageExport | p99 | 230ms | 316ms | 86ms | 37.34
| PostPersistentNotificationStore.GetSingle | p99 | 249ms | 341ms | 92ms | 36.93
| ThreadStore.GetThreadFollowers | p99 | 239ms | 325ms | 86ms | 36.02
| ReactionStore.GetUniqueCountForPost | p99 | 244ms | 330ms | 86ms | 35.21
| WebhookStore.GetOutgoingByTeam | p99 | 243ms | 325ms | 82ms | 33.68
| JobStore.GetAllByStatus | p99 | 237ms | 316ms | 79ms | 33.37
| ThreadStore.GetThreadsForUser | p99 | 274ms | 365ms | 91ms | 33.27
| ChannelStore.GetChannels | p99 | 248ms | 326ms | 78ms | 31.46
| ClusterDiscoveryStore.SetLastPingAt | p99 | 90ms | 118ms | 28ms | 31.26
| ChannelStore.Autocomplete | p99 | 704ms | 911ms | 207ms | 29.42
| FileInfoStore.GetForPost | p99 | 266ms | 341ms | 75ms | 28.18
| ThreadStore.GetTeamsUnreadForUser | p99 | 252ms | 318ms | 66ms | 26.16
| ThreadStore.GetMembershipForUser | p99 | 239ms | 292ms | 53ms | 22.20
| ReactionStore.ExistsOnPost | p99 | 248ms | 299ms | 51ms | 20.58
| ReactionStore.GetForPost | p99 | 274ms | 325ms | 51ms | 18.59
| ChannelStore.UpdateLastViewedAt | p99 | 132ms | 156ms | 24ms | 18.19
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 62ms | 73ms | 11ms | 17.78
| PostStore.GetPostsByThread | p99 | 239ms | 281ms | 42ms | 17.56
| GroupStore.GetGroups | p99 | 241ms | 283ms | 42ms | 17.41
| PostStore.GetEtag | p99 | 290ms | 340ms | 50ms | 17.21
| UserStore.Get | p99 | 154ms | 180ms | 26ms | 16.85
| ChannelStore.GetMembersForUser | p99 | 244ms | 285ms | 41ms | 16.82
| ThreadStore.Get | p99 | 242ms | 282ms | 40ms | 16.53
| PostStore.GetPostsBefore | p99 | 246ms | 285ms | 39ms | 15.86
| PostStore.GetPostsSince | p99 | 372ms | 429ms | 57ms | 15.30
| ChannelStore.GetChannelsByUser | p99 | 231ms | 266ms | 35ms | 15.18
| ChannelStore.GetPinnedPostCount | p99 | 246ms | 281ms | 35ms | 14.21
| SessionStore.UpdateLastActivityAt | p99 | 67ms | 76ms | 9ms | 13.41
| ChannelStore.GetGuestCount | p99 | 361ms | 409ms | 48ms | 13.28
| ChannelStore.CreateInitialSidebarCategories | p99 | 388ms | 437ms | 49ms | 12.63
| StatusStore.UpdateExpiredDNDStatuses | p99 | 214ms | 241ms | 27ms | 12.62
| ChannelStore.Get | p99 | 404ms | 453ms | 49ms | 12.13
| TeamStore.GetTeamsForUser | p99 | 185ms | 207ms | 22ms | 11.88
| SystemStore.GetByName | p99 | 59ms | 66ms | 7ms | 11.81
| PostPersistentNotificationStore.DeleteExpired | p99 | 80ms | 89ms | 9ms | 11.18
| FileInfoStore.Save | p99 | 85ms | 94ms | 9ms | 10.54
| PostStore.GetPostReminderMetadata | p99 | 400ms | 440ms | 40ms | 10.00
| PostPriorityStore.GetForPosts | p99 | 408ms | 448ms | 40ms | 9.79
| PostAcknowledgementStore.GetForPosts | p99 | 395ms | 433ms | 38ms | 9.61
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 219ms | 240ms | 21ms | 9.60
| JobStore.UpdateOptimistically | p99 | 86ms | 94ms | 8ms | 9.29
| UserStore.GetProfileByIds | p99 | 219ms | 239ms | 20ms | 9.14
| ChannelStore.GetFileCount | p99 | 208ms | 227ms | 19ms | 9.13
| PostStore.Get | p99 | 459ms | 498ms | 39ms | 8.49
| ThreadStore.GetThreadForUser | p99 | 405ms | 439ms | 34ms | 8.40
| PostStore.GetPostReminders | p99 | 214ms | 231ms | 17ms | 7.94
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 2.159s | 2.328s | 169ms | 7.83
| UserStore.GetAllProfiles | p99 | 222ms | 239ms | 17ms | 7.67
| PostStore.GetPostIdBeforeTime | p99 | 78ms | 84ms | 6ms | 7.65
| ThreadStore.MaintainMembership | p99 | 177ms | 189ms | 12ms | 6.80
| ChannelStore.IncrementMentionCount | p99 | 78ms | 83ms | 5ms | 6.38
| PreferenceStore.Get | p99 | 239ms | 253ms | 14ms | 5.87
| ThreadStore.GetTotalThreads | p99 | 225ms | 238ms | 13ms | 5.78
| PostStore.Save | p99 | 225ms | 238ms | 13ms | 5.78
| ChannelStore.GetChannelUnread | p99 | 199ms | 210ms | 11ms | 5.51
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 227ms | 239ms | 12ms | 5.28
| ThreadStore.GetTotalUnreadMentions | p99 | 227ms | 239ms | 12ms | 5.28
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 230ms | 242ms | 12ms | 5.22
| ChannelStore.GetMemberForPost | p99 | 214ms | 225ms | 11ms | 5.14
| PostStore.GetSingle | p99 | 236ms | 248ms | 12ms | 5.09
| PluginStore.Delete | p99 | 40ms | 42ms | 2ms | 5.03
| ThreadStore.UpdateMembership | p99 | 81ms | 85ms | 4ms | 4.95
| ReactionStore.Save | p99 | 223ms | 234ms | 11ms | 4.93
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 227ms | 238ms | 11ms | 4.84
| ChannelStore.GetByName | p99 | 227ms | 238ms | 11ms | 4.84
| TeamStore.Get | p99 | 234ms | 245ms | 11ms | 4.71
| LinkMetadataStore.Get | p99 | 239ms | 250ms | 11ms | 4.61
| FileInfoStore.Get | p99 | 222ms | 232ms | 10ms | 4.51
| UserStore.Search | p99 | 897ms | 937ms | 40ms | 4.46
| TeamStore.GetByName | p99 | 225ms | 235ms | 10ms | 4.44
| PostStore.GetPosts | p99 | 208ms | 217ms | 9ms | 4.34
| TeamStore.GetTeamsByUserId | p99 | 235ms | 245ms | 10ms | 4.26
| ThreadStore.GetTotalUnreadThreads | p99 | 229ms | 238ms | 9ms | 3.93
| PostStore.GetPostsAfter | p99 | 238ms | 247ms | 9ms | 3.77
| UserStore.GetForLogin | p99 | 189ms | 196ms | 7ms | 3.71
| PluginStore.SetWithOptions | p99 | 83ms | 86ms | 3ms | 3.63
| GroupStore.GetByName | p99 | 193ms | 200ms | 7ms | 3.63
| ChannelStore.SaveMember | p99 | 939ms | 973ms | 34ms | 3.62
| ThreadStore.MarkAllAsReadByChannels | p99 | 84ms | 87ms | 3ms | 3.57
| UserTermsOfServiceStore.GetByUser | p99 | 225ms | 233ms | 8ms | 3.56
| PostStore.Update | p99 | 212ms | 219ms | 7ms | 3.30
| UserStore.UpdateUpdateAt | p99 | 62ms | 64ms | 2ms | 3.21
| SessionStore.Get | p99 | 242ms | 249ms | 7ms | 2.89
| ThreadStore.MarkAsRead | p99 | 70ms | 72ms | 2ms | 2.84
| UserStore.UpdateFailedPasswordAttempts | p99 | 72ms | 74ms | 2ms | 2.79
| AuditStore.Save | p99 | 72ms | 74ms | 2ms | 2.76
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 483ms | 496ms | 13ms | 2.69
| ChannelStore.CreateDirectChannel | p99 | 899ms | 922ms | 23ms | 2.56
| StatusStore.SaveOrUpdate | p99 | 883ms | 905ms | 22ms | 2.49
| StatusStore.UpdateLastActivityAt | p99 | 83ms | 85ms | 2ms | 2.41
| TeamStore.SaveMember | p99 | 418ms | 428ms | 10ms | 2.39
| PreferenceStore.GetAll | p99 | 241ms | 246ms | 5ms | 2.08
| SessionStore.Save | p99 | 203ms | 207ms | 4ms | 1.97
| ChannelStore.GetMemberCount | p99 | 974ms | 988ms | 14ms | 1.44
| TeamStore.GetAllPage | p99 | 229ms | 232ms | 3ms | 1.31
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Delete | avg | 2ms | 0s | -2ms | -120.33
| SystemStore.PermanentDeleteByName | avg | 4ms | 0s | -4ms | -110.67
| PostPersistentNotificationStore.UpdateLastActivity | avg | 5ms | 0s | -5ms | -106.35
| ChannelStore.GetMemberCountsByGroup | avg | 4ms | 0s | -4ms | -102.93
| EmojiStore.GetMultipleByName | avg | 10ms | 0s | -10ms | -102.26
| ChannelStore.GetByNameIncludeDeleted | avg | 30ms | 0s | -30ms | -101.56
| ChannelStore.GetChannelsByIds | avg | 125ms | 0s | -125ms | -100.30
| PostStore.GetPostsByIds | avg | 68ms | 0s | -68ms | -100.24
| ChannelStore.GetMembers | avg | 198ms | 0s | -198ms | -99.96
| EmojiStore.Search | avg | 12ms | 0s | -12ms | -98.07
| DraftStore.Upsert | avg | 13ms | 0s | -13ms | -97.25
| SystemStore.SaveOrUpdate | avg | 3ms | 0s | -3ms | -96.78
| TeamStore.GetMany | avg | 10ms | 0s | -10ms | -96.39
| UserStore.AnalyticsGetInactiveUsersCount | avg | 48ms | 3ms | -45ms | -93.79
| RetentionPolicyStore.GetCount | avg | 19ms | 1ms | -18ms | -93.12
| RetentionPolicyStore.GetAll | avg | 16ms | 1ms | -15ms | -92.70
| PluginStore.List | avg | 64ms | 9ms | -55ms | -85.73
| TeamStore.AnalyticsTeamCount | avg | 90ms | 20ms | -70ms | -77.66
| PostStore.Delete | avg | 364ms | 88ms | -276ms | -75.74
| JobStore.GetCountByStatusAndType | avg | 64ms | 18ms | -46ms | -71.44
| PluginStore.Get | avg | 27ms | 8ms | -19ms | -70.27
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 32ms | 10ms | -22ms | -69.00
| JobStore.GetNewestJobByStatusesAndType | avg | 55ms | 23ms | -32ms | -58.11
| ChannelStore.GetAllChannelMembersForUser | avg | 3ms | 1ms | -2ms | -57.83
| ProductNoticesStore.GetViews | avg | 93ms | 48ms | -45ms | -48.65
| UserStore.GetMany | avg | 28ms | 15ms | -13ms | -45.94
| JobStore.UpdateStatusOptimistically | avg | 12ms | 7ms | -5ms | -40.92
| UserStore.GetProfilesInChannel | avg | 19ms | 12ms | -7ms | -37.20
| RoleStore.ChannelHigherScopedPermissions | avg | 8ms | 5ms | -3ms | -36.91
| PostStore.SetPostReminder | avg | 17ms | 11ms | -6ms | -35.83
| SessionStore.Remove | avg | 11ms | 7ms | -4ms | -34.99
| UserStore.AnalyticsActiveCount | avg | 592ms | 387ms | -205ms | -34.63
| ChannelStore.GetTeamChannels | avg | 74ms | 49ms | -25ms | -33.76
| ChannelStore.GetMembersForUserWithPagination | avg | 175ms | 116ms | -59ms | -33.69
| LicenseStore.GetAll | avg | 23ms | 16ms | -7ms | -29.83
| UserStore.Count | avg | 288ms | 209ms | -79ms | -27.46
| BotStore.Get | avg | 19ms | 14ms | -5ms | -26.62
| ChannelStore.AutocompleteInTeamForSearch | avg | 295ms | 217ms | -78ms | -26.46
| ChannelStore.AnalyticsTypeCount | avg | 218ms | 177ms | -41ms | -18.83
| PostAcknowledgementStore.GetForPost | avg | 16ms | 13ms | -3ms | -18.20
| UserStore.GetUnreadCount | avg | 20ms | 18ms | -2ms | -9.79
| StatusStore.GetByIds | avg | 27ms | 25ms | -2ms | -7.41
| ProductNoticesStore.View | avg | 51ms | 49ms | -2ms | -3.93
| ChannelStore.CreateDirectChannel | avg | 94ms | 91ms | -3ms | -3.18
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 10ms | 0s | -10ms | -101.52
| EmojiStore.Search | p99 | 25ms | 0s | -25ms | -101.09
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Delete | p99 | 5ms | 0s | -5ms | -100.82
| EmojiStore.GetMultipleByName | p99 | 94ms | 0s | -94ms | -100.53
| ChannelStore.GetByNameIncludeDeleted | p99 | 50ms | 0s | -50ms | -100.50
| PostStore.GetPostsByIds | p99 | 246ms | 0s | -246ms | -100.20
| ChannelStore.GetChannelsByIds | p99 | 490ms | 0s | -490ms | -100.00
| TeamStore.GetMany | p99 | 49ms | 0s | -49ms | -100.00
| ChannelStore.GetMemberCountsByGroup | p99 | 45ms | 0s | -45ms | -100.00
| ChannelStore.GetMembers | p99 | 941ms | 0s | -941ms | -99.95
| DraftStore.Upsert | p99 | 49ms | 0s | -49ms | -99.49
| RetentionPolicyStore.GetCount | p99 | 50ms | 5ms | -45ms | -90.91
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 244ms | 23ms | -221ms | -90.57
| PostStore.Delete | p99 | 4.725s | 870ms | -3.855s | -81.59
| RetentionPolicyStore.GetAll | p99 | 25ms | 5ms | -20ms | -80.48
| JobStore.GetCountByStatusAndType | p99 | 1.06s | 230ms | -830ms | -78.30
| PluginStore.List | p99 | 429ms | 145ms | -284ms | -66.27
| ChannelStore.GetAllChannelMembersForUser | p99 | 91ms | 32ms | -59ms | -64.84
| ChannelStore.GetMembersForUserWithPagination | p99 | 1.825s | 715ms | -1.11s | -60.82
| JobStore.GetNewestJobByStatusesAndType | p99 | 850ms | 338ms | -512ms | -60.24
| PostPersistentNotificationStore.Get | p99 | 185ms | 78ms | -107ms | -57.68
| UserStore.GetMany | p99 | 450ms | 209ms | -241ms | -53.56
| TeamStore.AnalyticsTeamCount | p99 | 485ms | 230ms | -255ms | -52.58
| BotStore.Get | p99 | 435ms | 210ms | -225ms | -51.72
| RoleStore.ChannelHigherScopedPermissions | p99 | 83ms | 41ms | -42ms | -50.91
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 99ms | 49ms | -50ms | -50.51
| UserStore.GetUnreadCount | p99 | 410ms | 290ms | -120ms | -29.24
| ChannelStore.Save | p99 | 326ms | 246ms | -80ms | -24.52
| JobStore.UpdateStatus | p99 | 85ms | 66ms | -19ms | -22.42
| UserStore.Update | p99 | 196ms | 165ms | -31ms | -15.78
| ChannelStore.GetPublicChannelsForTeam | p99 | 378ms | 325ms | -53ms | -14.01
| PostAcknowledgementStore.GetForPost | p99 | 237ms | 205ms | -32ms | -13.50
| JobStore.UpdateStatusOptimistically | p99 | 95ms | 83ms | -12ms | -12.65
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.413s | 2.123s | -290ms | -12.02
| SessionStore.Remove | p99 | 94ms | 86ms | -8ms | -8.53
| FileInfoStore.AttachToPost | p99 | 101ms | 94ms | -7ms | -6.91
| PluginStore.Get | p99 | 98ms | 92ms | -6ms | -6.11
| UserStore.Count | p99 | 982ms | 935ms | -47ms | -4.79
| JobStore.Save | p99 | 69ms | 66ms | -3ms | -4.35
| LicenseStore.GetAll | p99 | 97ms | 93ms | -4ms | -4.12
| JobStore.Get | p99 | 452ms | 438ms | -14ms | -3.09
| ProductNoticesStore.View | p99 | 485ms | 473ms | -12ms | -2.47
| ChannelStore.GetTeamChannels | p99 | 245ms | 239ms | -6ms | -2.45
| StatusStore.GetByIds | p99 | 347ms | 339ms | -8ms | -2.30
| PostPriorityStore.GetForPost | p99 | 224ms | 219ms | -5ms | -2.24
| StatusStore.Get | p99 | 182ms | 178ms | -4ms | -2.20
| JobStore.GetAllByTypePage | p99 | 234ms | 229ms | -5ms | -2.13
| UserStore.GetByUsername | p99 | 309ms | 303ms | -6ms | -1.94
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getSelfHostedProducts | avg | 0s | 16ms | 16ms | 7140.94
| updateCategoriesForTeamForUser | avg | 130ms | 267ms | 137ms | 105.61
| followThreadByUser | avg | 34ms | 58ms | 24ms | 69.88
| setPostReminder | avg | 60ms | 85ms | 25ms | 41.78
| unfollowThreadByUser | avg | 51ms | 69ms | 18ms | 35.34
| getChannelsForUser | avg | 18ms | 22ms | 4ms | 22.48
| removeUserCustomStatus | avg | 221ms | 264ms | 43ms | 19.47
| getThreadsForUser | avg | 22ms | 26ms | 4ms | 17.96
| getUsers | avg | 21ms | 24ms | 3ms | 14.14
| searchUsers | avg | 146ms | 166ms | 20ms | 13.68
| getJobsByType | avg | 22ms | 25ms | 3ms | 13.62
| saveReaction | avg | 117ms | 133ms | 16ms | 13.62
| createGroupChannel | avg | 605ms | 683ms | 78ms | 12.90
| updateReadStateThreadByUser | avg | 166ms | 187ms | 21ms | 12.62
| viewChannel | avg | 48ms | 54ms | 6ms | 12.51
| getPostThread | avg | 115ms | 129ms | 14ms | 12.17
| autocompleteUsers | avg | 263ms | 291ms | 28ms | 10.63
| getChannelMembersForTeamForUser | avg | 19ms | 21ms | 2ms | 10.44
| searchPostsInTeam | avg | 172ms | 189ms | 17ms | 9.91
| getUser | avg | 21ms | 23ms | 2ms | 9.69
| logout | avg | 114ms | 125ms | 11ms | 9.64
| getChannelsForTeamForUser | avg | 21ms | 23ms | 2ms | 9.63
| updatePreferences | avg | 23ms | 25ms | 2ms | 8.63
| searchAllChannels | avg | 107ms | 116ms | 9ms | 8.41
| getTeamsUnreadForUser | avg | 25ms | 27ms | 2ms | 7.91
| searchGroupChannels | avg | 26ms | 28ms | 2ms | 7.55
| getFileThumbnail | avg | 61ms | 65ms | 4ms | 6.55
| getPostsForChannel | avg | 183ms | 191ms | 8ms | 4.38
| login | avg | 146ms | 151ms | 5ms | 3.43
| getPostsForChannelAroundLastUnread | avg | 75ms | 77ms | 2ms | 2.68
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getSelfHostedProducts | p99 | 5ms | 96ms | 91ms | 1838.38
| setPostReminder | p99 | 447ms | 2.14s | 1.693s | 378.33
| updateCategoriesForTeamForUser | p99 | 951ms | 3.85s | 2.899s | 304.76
| getDrafts | p99 | 100ms | 245ms | 145ms | 145.73
| getGroups | p99 | 99ms | 242ms | 143ms | 143.90
| createGroupChannel | p99 | 2.39s | 4.755s | 2.365s | 98.94
| getFilteredUsersStats | p99 | 248ms | 480ms | 232ms | 93.36
| followThreadByUser | p99 | 236ms | 422ms | 186ms | 78.65
| searchPostsInTeam | p99 | 2.272s | 3.677s | 1.405s | 61.84
| autocompleteUsers | p99 | 997ms | 1.576s | 579ms | 58.07
| getUserStatusesByIds | p99 | 12ms | 16ms | 4ms | 34.00
| viewChannel | p99 | 497ms | 649ms | 152ms | 30.56
| searchAllChannels | p99 | 704ms | 914ms | 210ms | 29.85
| getThreadsForUser | p99 | 294ms | 376ms | 82ms | 27.91
| getChannelsForTeamForUser | p99 | 265ms | 338ms | 73ms | 27.60
| getUser | p99 | 272ms | 342ms | 70ms | 25.76
| getChannelsForUser | p99 | 230ms | 289ms | 59ms | 25.61
| getUsers | p99 | 260ms | 319ms | 59ms | 22.69
| getPostsForChannelAroundLastUnread | p99 | 986ms | 1.207s | 221ms | 22.42
| getChannelMembersForTeamForUser | p99 | 246ms | 295ms | 49ms | 19.92
| saveReaction | p99 | 1.699s | 1.985s | 286ms | 16.83
| getPostThread | p99 | 1.794s | 2.077s | 283ms | 15.78
| removeUserCustomStatus | p99 | 884ms | 994ms | 110ms | 12.44
| getTeamsUnreadForUser | p99 | 400ms | 439ms | 39ms | 9.76
| getTeamMembersForUser | p99 | 204ms | 221ms | 17ms | 8.32
| updateReadStateThreadByUser | p99 | 2.17s | 2.325s | 155ms | 7.14
| getUsersByIds | p99 | 43ms | 46ms | 3ms | 6.91
| getPostsForChannel | p99 | 3.053s | 3.238s | 185ms | 6.06
| getFileThumbnail | p99 | 463ms | 486ms | 23ms | 4.97
| getChannelMember | p99 | 401ms | 420ms | 19ms | 4.74
| getTeamsForUser | p99 | 235ms | 246ms | 11ms | 4.67
| searchUsers | p99 | 899ms | 938ms | 39ms | 4.34
| getFilePreview | p99 | 467ms | 483ms | 16ms | 3.43
| getClientConfig | p99 | 208ms | 215ms | 7ms | 3.37
| login | p99 | 960ms | 989ms | 29ms | 3.02
| getCategoriesForTeamForUser | p99 | 484ms | 498ms | 14ms | 2.89
| getChannelStats | p99 | 853ms | 873ms | 20ms | 2.34
| getChannelUnread | p99 | 214ms | 219ms | 5ms | 2.33
| createUser | p99 | 734ms | 750ms | 16ms | 2.18
| getAllTeams | p99 | 235ms | 240ms | 5ms | 2.13
| getPreferences | p99 | 243ms | 248ms | 5ms | 2.05
| addTeamMember | p99 | 9.473s | 9.643s | 170ms | 1.79
| updatePreferences | p99 | 240ms | 243ms | 3ms | 1.25
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 5ms | 0s | -5ms | -105.17
| getEmojisByNames | avg | 10ms | 0s | -10ms | -101.58
| upsertDraft | avg | 81ms | 0s | -81ms | -100.42
| updateUserCustomStatus | avg | 255ms | 0s | -255ms | -99.89
| autocompleteEmojis | avg | 12ms | 0s | -12ms | -97.62
| getChannelMembers | avg | 6ms | 0s | -6ms | -93.17
| getSchemes | avg | 2ms | 0s | -2ms | -92.51
| getRolesByNames | avg | 8ms | 1ms | -7ms | -84.55
| getGroupsAssociatedToChannelsByTeam | avg | 62ms | 12ms | -50ms | -80.54
| deleteDraft | avg | 8ms | 2ms | -6ms | -72.96
| patchPost | avg | 455ms | 131ms | -324ms | -71.14
| deletePost | avg | 497ms | 162ms | -335ms | -67.40
| getChannelMembersForUser | avg | 414ms | 140ms | -274ms | -66.15
| getProductNotices | avg | 138ms | 64ms | -74ms | -53.48
| getFilteredUsersStats | avg | 232ms | 126ms | -106ms | -45.76
| getPrevTrialLicense | avg | 35ms | 19ms | -16ms | -45.38
| getLicenseSelfServeStatus | avg | 594ms | 332ms | -262ms | -44.07
| getGroups | avg | 62ms | 37ms | -25ms | -40.16
| createChannel | avg | 74ms | 49ms | -25ms | -33.69
| updateReadStateAllThreadsByUser | avg | 7ms | 5ms | -2ms | -30.44
| getAnalytics | avg | 742ms | 540ms | -202ms | -27.24
| autocompleteChannelsForTeamForSearch | avg | 295ms | 217ms | -78ms | -26.45
| createCategoryForTeamForUser | avg | 49ms | 41ms | -8ms | -16.27
| createPost | avg | 1.365s | 1.174s | -191ms | -13.99
| getProfileImage | avg | 97ms | 90ms | -7ms | -7.18
| getDrafts | avg | 83ms | 78ms | -5ms | -5.99
| addChannelMember | avg | 536ms | 510ms | -26ms | -4.85
| uploadFileStream | avg | 464ms | 443ms | -21ms | -4.52
| addTeamMember | avg | 1.904s | 1.828s | -76ms | -3.99
| createUser | avg | 137ms | 134ms | -3ms | -2.18
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 25ms | 0s | -25ms | -101.09
| getSchemes | p99 | 5ms | 0s | -5ms | -101.01
| getEmojisByNames | p99 | 94ms | 0s | -94ms | -100.53
| upsertDraft | p99 | 485ms | 0s | -485ms | -100.00
| channelMemberCountsByGroup | p99 | 45ms | 0s | -45ms | -100.00
| updateUserCustomStatus | p99 | 989ms | 5ms | -984ms | -99.47
| getChannelMembers | p99 | 24ms | 0s | -24ms | -98.97
| getChannelMembersForUser | p99 | 2.41s | 490ms | -1.92s | -79.67
| getRolesByNames | p99 | 96ms | 20ms | -76ms | -79.17
| patchPost | p99 | 3.75s | 1.412s | -2.338s | -62.35
| createCategoryForTeamForUser | p99 | 244ms | 99ms | -145ms | -59.43
| deletePost | p99 | 4.725s | 2.11s | -2.615s | -55.34
| getGroupsAssociatedToChannelsByTeam | p99 | 100ms | 49ms | -51ms | -51.26
| deleteDraft | p99 | 10ms | 5ms | -5ms | -50.21
| createPost | p99 | 9.11s | 6.132s | -2.978s | -32.69
| getChannel | p99 | 732ms | 505ms | -227ms | -31.03
| addChannelMember | p99 | 3.975s | 3.008s | -967ms | -24.33
| getPublicChannelsForTeam | p99 | 409ms | 325ms | -84ms | -20.55
| autocompleteChannelsForTeamForSearch | p99 | 2.413s | 2.123s | -290ms | -12.02
| logout | p99 | 479ms | 430ms | -49ms | -10.23
| unfollowThreadByUser | p99 | 520ms | 487ms | -33ms | -6.35
| getLicenseSelfServeStatus | p99 | 995ms | 960ms | -35ms | -3.52
| getPrevTrialLicense | p99 | 98ms | 95ms | -3ms | -3.06
| createChannel | p99 | 245ms | 239ms | -6ms | -2.45
| uploadFileStream | p99 | 1.757s | 1.717s | -40ms | -2.28
| getJobsByType | p99 | 234ms | 230ms | -4ms | -1.71
| getProfileImage | p99 | 481ms | 474ms | -7ms | -1.46
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 74ms | 2ms | 2.760
| BotStore.Get |  Avg| 19ms| 14ms | -5ms | -26.619
| |  P99| 435ms| 210ms | -225ms | -51.724
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 197ms| 271ms | 74ms | 37.545
| |  P99| 2.159s| 2.328s | 169ms | 7.827
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 63ms| 63ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 218ms| 177ms | -41ms | -18.834
| |  P99| 494ms| 490ms | -4ms | -0.810
| ChannelStore.Autocomplete |  Avg| 106ms| 115ms | 9ms | 8.486
| |  P99| 704ms| 911ms | 207ms | 29.424
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 295ms| 217ms | -78ms | -26.461
| |  P99| 2.413s| 2.123s | -290ms | -12.017
| ChannelStore.CreateDirectChannel |  Avg| 94ms| 91ms | -3ms | -3.180
| |  P99| 899ms| 922ms | 23ms | 2.557
| ChannelStore.CreateInitialSidebarCategories |  Avg| 36ms| 38ms | 2ms | 5.577
| |  P99| 388ms| 437ms | 49ms | 12.630
| ChannelStore.CreateSidebarCategory |  Avg| 12ms| 27ms | 15ms | 121.568
| |  P99| 25ms| 50ms | 25ms | 100.806
| ChannelStore.Get |  Avg| 34ms| 37ms | 3ms | 8.749
| |  P99| 404ms| 453ms | 49ms | 12.127
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 1ms | -2ms | -57.833
| |  P99| 91ms| 32ms | -59ms | -64.842
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 39ms| 38ms | -1ms | -2.575
| |  P99| 237ms| 235ms | -2ms | -0.845
| ChannelStore.GetByName |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 227ms| 238ms | 11ms | 4.842
| ChannelStore.GetByNameIncludeDeleted |  Avg| 30ms| 0s | -30ms | -101.563
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.GetChannelUnread |  Avg| 12ms| 13ms | 1ms | 8.219
| |  P99| 199ms| 210ms | 11ms | 5.514
| ChannelStore.GetChannels |  Avg| 20ms| 22ms | 2ms | 10.026
| |  P99| 248ms| 326ms | 78ms | 31.462
| ChannelStore.GetChannelsByIds |  Avg| 125ms| 0s | -125ms | -100.301
| |  P99| 490ms| 0s | -490ms | -100.000
| ChannelStore.GetChannelsByUser |  Avg| 18ms| 22ms | 4ms | 22.731
| |  P99| 231ms| 266ms | 35ms | 15.178
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 15ms| 17ms | 2ms | 13.466
| |  P99| 230ms| 242ms | 12ms | 5.220
| ChannelStore.GetFileCount |  Avg| 14ms| 15ms | 1ms | 7.305
| |  P99| 208ms| 227ms | 19ms | 9.125
| ChannelStore.GetGuestCount |  Avg| 25ms| 26ms | 1ms | 3.939
| |  P99| 361ms| 409ms | 48ms | 13.281
| ChannelStore.GetMember |  Avg| 5ms| 7ms | 2ms | 36.491
| |  P99| 91ms| 90ms | -1ms | -1.095
| ChannelStore.GetMemberCount |  Avg| 236ms| 241ms | 5ms | 2.120
| |  P99| 974ms| 988ms | 14ms | 1.437
| ChannelStore.GetMemberCountsByGroup |  Avg| 4ms| 0s | -4ms | -102.928
| |  P99| 45ms| 0s | -45ms | -99.999
| ChannelStore.GetMemberForPost |  Avg| 13ms| 15ms | 2ms | 15.684
| |  P99| 214ms| 225ms | 11ms | 5.140
| ChannelStore.GetMembers |  Avg| 198ms| 0s | -198ms | -99.961
| |  P99| 941ms| 0s | -941ms | -99.954
| ChannelStore.GetMembersForUser |  Avg| 19ms| 21ms | 2ms | 10.707
| |  P99| 244ms| 285ms | 41ms | 16.825
| ChannelStore.GetMembersForUserWithPagination |  Avg| 175ms| 116ms | -59ms | -33.690
| |  P99| 1.825s| 715ms | -1.11s | -60.822
| ChannelStore.GetPinnedPostCount |  Avg| 18ms| 20ms | 2ms | 11.099
| |  P99| 246ms| 281ms | 35ms | 14.209
| ChannelStore.GetPublicChannelsForTeam |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 378ms| 325ms | -53ms | -14.009
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 37ms| 38ms | 1ms | 2.738
| |  P99| 483ms| 496ms | 13ms | 2.690
| ChannelStore.GetSidebarCategory |  Avg| 20ms| 56ms | 36ms | 178.868
| |  P99| 227ms| 1.18s | 953ms | 420.565
| ChannelStore.GetTeamChannels |  Avg| 74ms| 49ms | -25ms | -33.762
| |  P99| 245ms| 239ms | -6ms | -2.451
| ChannelStore.IncrementMentionCount |  Avg| 5ms| 6ms | 1ms | 19.658
| |  P99| 78ms| 83ms | 5ms | 6.377
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 326ms| 246ms | -80ms | -24.521
| ChannelStore.SaveMember |  Avg| 85ms| 86ms | 1ms | 1.171
| |  P99| 939ms| 973ms | 34ms | 3.620
| ChannelStore.SearchGroupChannels |  Avg| 26ms| 28ms | 2ms | 7.589
| |  P99| 388ms| 389ms | 1ms | 0.257
| ChannelStore.UpdateLastViewedAt |  Avg| 12ms| 13ms | 1ms | 8.680
| |  P99| 132ms| 156ms | 24ms | 18.195
| ChannelStore.UpdateSidebarCategories |  Avg| 72ms| 124ms | 52ms | 72.372
| |  P99| 805ms| 1.81s | 1.005s | 124.845
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 4ms| 5ms | 1ms | 24.114
| |  P99| 62ms| 73ms | 11ms | 17.777
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 118ms | 28ms | 31.260
| CommandWebhookStore.Cleanup |  Avg| 1ms| 3ms | 2ms | 256.645
| |  P99| 5ms| 10ms | 5ms | 100.997
| ComplianceStore.MessageExport |  Avg| 15ms| 21ms | 6ms | 40.108
| |  P99| 230ms| 316ms | 86ms | 37.337
| DraftStore.Delete |  Avg| 2ms| 0s | -2ms | -120.332
| |  P99| 5ms| 0s | -5ms | -100.816
| DraftStore.GetDraftsForUser |  Avg| 46ms| 62ms | 16ms | 35.122
| |  P99| 99ms| 244ms | 145ms | 146.465
| DraftStore.Upsert |  Avg| 13ms| 0s | -13ms | -97.251
| |  P99| 49ms| 0s | -49ms | -99.487
| EmojiStore.GetMultipleByName |  Avg| 10ms| 0s | -10ms | -102.256
| |  P99| 94ms| 0s | -94ms | -100.534
| EmojiStore.Search |  Avg| 12ms| 0s | -12ms | -98.071
| |  P99| 25ms| 0s | -25ms | -101.091
| FileInfoStore.AttachToPost |  Avg| 11ms| 10ms | -1ms | -9.328
| |  P99| 101ms| 94ms | -7ms | -6.909
| FileInfoStore.Get |  Avg| 14ms| 16ms | 2ms | 14.359
| |  P99| 222ms| 232ms | 10ms | 4.512
| FileInfoStore.GetForPost |  Avg| 20ms| 24ms | 4ms | 19.728
| |  P99| 266ms| 341ms | 75ms | 28.178
| FileInfoStore.Save |  Avg| 9ms| 10ms | 1ms | 11.161
| |  P99| 85ms| 94ms | 9ms | 10.540
| FileInfoStore.SetContent |  Avg| 14ms| 16ms | 2ms | 14.306
| |  P99| 98ms| 176ms | 78ms | 79.643
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 15ms| 14ms | -1ms | -6.660
| |  P99| 233ms| 234ms | 1ms | 0.429
| GroupStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 193ms| 200ms | 7ms | 3.630
| GroupStore.GetGroups |  Avg| 18ms| 20ms | 2ms | 11.329
| |  P99| 241ms| 283ms | 42ms | 17.411
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 32ms| 10ms | -22ms | -69.001
| |  P99| 99ms| 49ms | -50ms | -50.505
| JobStore.Get |  Avg| 27ms| 35ms | 8ms | 29.484
| |  P99| 452ms| 438ms | -14ms | -3.094
| JobStore.GetAllByStatus |  Avg| 17ms| 22ms | 5ms | 29.359
| |  P99| 237ms| 316ms | 79ms | 33.365
| JobStore.GetAllByTypePage |  Avg| 22ms| 23ms | 1ms | 4.595
| |  P99| 234ms| 229ms | -5ms | -2.133
| JobStore.GetCountByStatusAndType |  Avg| 64ms| 18ms | -46ms | -71.440
| |  P99| 1.06s| 230ms | -830ms | -78.302
| JobStore.GetNewestJobByStatusesAndType |  Avg| 55ms| 23ms | -32ms | -58.112
| |  P99| 850ms| 338ms | -512ms | -60.235
| JobStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 66ms | -3ms | -4.348
| JobStore.UpdateOptimistically |  Avg| 8ms| 10ms | 2ms | 25.461
| |  P99| 86ms| 94ms | 8ms | 9.292
| JobStore.UpdateStatus |  Avg| 8ms| 7ms | -1ms | -12.274
| |  P99| 85ms| 66ms | -19ms | -22.419
| JobStore.UpdateStatusOptimistically |  Avg| 12ms| 7ms | -5ms | -40.919
| |  P99| 95ms| 83ms | -12ms | -12.654
| LicenseStore.GetAll |  Avg| 23ms| 16ms | -7ms | -29.827
| |  P99| 97ms| 93ms | -4ms | -4.124
| LinkMetadataStore.Get |  Avg| 17ms| 19ms | 2ms | 11.652
| |  P99| 239ms| 250ms | 11ms | 4.612
| LinkMetadataStore.Save |  Avg| 5ms| 7ms | 2ms | 36.590
| |  P99| 42ms| 86ms | 44ms | 103.529
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 5.030
| PluginStore.Get |  Avg| 27ms| 8ms | -19ms | -70.270
| |  P99| 98ms| 92ms | -6ms | -6.107
| PluginStore.List |  Avg| 64ms| 9ms | -55ms | -85.732
| |  P99| 429ms| 145ms | -284ms | -66.267
| PluginStore.SetWithOptions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 86ms | 3ms | 3.635
| PostAcknowledgementStore.GetForPost |  Avg| 16ms| 13ms | -3ms | -18.201
| |  P99| 237ms| 205ms | -32ms | -13.500
| PostAcknowledgementStore.GetForPosts |  Avg| 23ms| 26ms | 3ms | 13.148
| |  P99| 395ms| 433ms | 38ms | 9.610
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 6ms | 2ms | 47.909
| |  P99| 80ms| 89ms | 9ms | 11.180
| PostPersistentNotificationStore.Get |  Avg| 6ms| 5ms | -1ms | -17.970
| |  P99| 185ms| 78ms | -107ms | -57.682
| PostPersistentNotificationStore.GetSingle |  Avg| 17ms| 20ms | 3ms | 17.817
| |  P99| 249ms| 341ms | 92ms | 36.929
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 5ms| 0s | -5ms | -106.355
| |  P99| 10ms| 0s | -10ms | -101.517
| PostPriorityStore.GetForPost |  Avg| 15ms| 14ms | -1ms | -6.735
| |  P99| 224ms| 219ms | -5ms | -2.237
| PostPriorityStore.GetForPosts |  Avg| 24ms| 27ms | 3ms | 12.455
| |  P99| 408ms| 448ms | 40ms | 9.794
| PostStore.AnalyticsPostCount |  Avg| 3.023s| 3.483s | 460ms | 15.219
| |  P99| 9.9s| 9.85s | -50ms | -0.505
| PostStore.Delete |  Avg| 364ms| 88ms | -276ms | -75.739
| |  P99| 4.725s| 870ms | -3.855s | -81.588
| PostStore.Get |  Avg| 36ms| 42ms | 6ms | 16.657
| |  P99| 459ms| 498ms | 39ms | 8.493
| PostStore.GetEtag |  Avg| 22ms| 24ms | 2ms | 9.099
| |  P99| 290ms| 340ms | 50ms | 17.213
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 66ms| 66ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 6ms | 1ms | 19.646
| |  P99| 78ms| 84ms | 6ms | 7.654
| PostStore.GetPostReminderMetadata |  Avg| 22ms| 23ms | 1ms | 4.461
| |  P99| 400ms| 440ms | 40ms | 10.000
| PostStore.GetPostReminders |  Avg| 19ms| 26ms | 7ms | 36.589
| |  P99| 214ms| 231ms | 17ms | 7.944
| PostStore.GetPosts |  Avg| 14ms| 15ms | 1ms | 7.169
| |  P99| 208ms| 217ms | 9ms | 4.335
| PostStore.GetPostsAfter |  Avg| 19ms| 18ms | -1ms | -5.359
| |  P99| 238ms| 247ms | 9ms | 3.774
| PostStore.GetPostsBefore |  Avg| 20ms| 22ms | 2ms | 9.861
| |  P99| 246ms| 285ms | 39ms | 15.862
| PostStore.GetPostsByIds |  Avg| 68ms| 0s | -68ms | -100.240
| |  P99| 246ms| 0s | -246ms | -100.204
| PostStore.GetPostsByThread |  Avg| 19ms| 21ms | 2ms | 10.706
| |  P99| 239ms| 281ms | 42ms | 17.557
| PostStore.GetPostsSince |  Avg| 39ms| 44ms | 5ms | 12.951
| |  P99| 372ms| 429ms | 57ms | 15.304
| PostStore.GetSingle |  Avg| 16ms| 19ms | 3ms | 18.254
| |  P99| 236ms| 248ms | 12ms | 5.086
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 22ms| 24ms | 2ms | 9.044
| |  P99| 225ms| 238ms | 13ms | 5.776
| PostStore.SearchPostsForUser |  Avg| 121ms| 138ms | 17ms | 14.105
| |  P99| 1.027s| 2.325s | 1.298s | 126.326
| PostStore.SetPostReminder |  Avg| 17ms| 11ms | -6ms | -35.830
| |  P99| 89ms| 88ms | -1ms | -1.117
| PostStore.Update |  Avg| 25ms| 30ms | 5ms | 20.116
| |  P99| 212ms| 219ms | 7ms | 3.298
| PreferenceStore.DeleteCategoryAndName |  Avg| 12ms| 15ms | 3ms | 25.700
| |  P99| 49ms| 94ms | 45ms | 92.545
| PreferenceStore.Get |  Avg| 17ms| 19ms | 2ms | 11.838
| |  P99| 239ms| 253ms | 14ms | 5.870
| PreferenceStore.GetAll |  Avg| 19ms| 20ms | 1ms | 5.296
| |  P99| 241ms| 246ms | 5ms | 2.079
| PreferenceStore.Save |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 207ms| 207ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 93ms| 48ms | -45ms | -48.647
| |  P99| 246ms| 244ms | -2ms | -0.815
| ProductNoticesStore.View |  Avg| 51ms| 49ms | -2ms | -3.934
| |  P99| 485ms| 473ms | -12ms | -2.475
| ReactionStore.ExistsOnPost |  Avg| 21ms| 22ms | 1ms | 4.859
| |  P99| 248ms| 299ms | 51ms | 20.575
| ReactionStore.GetForPost |  Avg| 21ms| 24ms | 3ms | 14.339
| |  P99| 274ms| 325ms | 51ms | 18.594
| ReactionStore.GetUniqueCountForPost |  Avg| 17ms| 21ms | 4ms | 23.611
| |  P99| 244ms| 330ms | 86ms | 35.206
| ReactionStore.Save |  Avg| 19ms| 22ms | 3ms | 15.967
| |  P99| 223ms| 234ms | 11ms | 4.933
| RetentionPolicyStore.GetAll |  Avg| 16ms| 1ms | -15ms | -92.699
| |  P99| 25ms| 5ms | -20ms | -80.483
| RetentionPolicyStore.GetCount |  Avg| 19ms| 1ms | -18ms | -93.122
| |  P99| 50ms| 5ms | -45ms | -90.909
| RoleStore.ChannelHigherScopedPermissions |  Avg| 8ms| 5ms | -3ms | -36.907
| |  P99| 83ms| 41ms | -42ms | -50.909
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 8ms | 6ms | 285.902
| |  P99| 5ms| 25ms | 20ms | 404.040
| SessionStore.Get |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 242ms| 249ms | 7ms | 2.893
| SessionStore.GetSessionsExpired |  Avg| 12ms| 14ms | 2ms | 17.300
| |  P99| 95ms| 95ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 13ms| 17ms | 4ms | 30.283
| |  P99| 219ms| 240ms | 21ms | 9.601
| SessionStore.Remove |  Avg| 11ms| 7ms | -4ms | -34.992
| |  P99| 94ms| 86ms | -8ms | -8.533
| SessionStore.Save |  Avg| 15ms| 16ms | 1ms | 6.581
| |  P99| 203ms| 207ms | 4ms | 1.971
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 8ms | 1ms | 14.336
| |  P99| 67ms| 76ms | 9ms | 13.415
| StatusStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 182ms| 178ms | -4ms | -2.198
| StatusStore.GetByIds |  Avg| 27ms| 25ms | -2ms | -7.409
| |  P99| 347ms| 339ms | -8ms | -2.302
| StatusStore.SaveOrUpdate |  Avg| 59ms| 65ms | 6ms | 10.248
| |  P99| 883ms| 905ms | 22ms | 2.491
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 11ms| 27ms | 16ms | 139.892
| |  P99| 214ms| 241ms | 27ms | 12.617
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 85ms | 2ms | 2.413
| SystemStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 59ms| 66ms | 7ms | 11.813
| SystemStore.PermanentDeleteByName |  Avg| 4ms| 0s | -4ms | -110.669
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 3ms| 0s | -3ms | -96.781
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 90ms| 20ms | -70ms | -77.660
| |  P99| 485ms| 230ms | -255ms | -52.579
| TeamStore.Get |  Avg| 16ms| 18ms | 2ms | 12.894
| |  P99| 234ms| 245ms | 11ms | 4.708
| TeamStore.GetAllPage |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 229ms| 232ms | 3ms | 1.308
| TeamStore.GetByName |  Avg| 13ms| 15ms | 2ms | 15.032
| |  P99| 225ms| 235ms | 10ms | 4.443
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 15ms| 16ms | 1ms | 6.631
| |  P99| 227ms| 238ms | 11ms | 4.845
| TeamStore.GetMany |  Avg| 10ms| 0s | -10ms | -96.391
| |  P99| 49ms| 0s | -49ms | -100.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 32ms | 1ms | 3.244
| TeamStore.GetTeamsByUserId |  Avg| 17ms| 18ms | 1ms | 6.020
| |  P99| 235ms| 245ms | 10ms | 4.258
| TeamStore.GetTeamsForUser |  Avg| 11ms| 12ms | 1ms | 9.463
| |  P99| 185ms| 207ms | 22ms | 11.884
| TeamStore.SaveMember |  Avg| 93ms| 94ms | 1ms | 1.076
| |  P99| 418ms| 428ms | 10ms | 2.395
| ThreadStore.Get |  Avg| 15ms| 22ms | 7ms | 46.214
| |  P99| 242ms| 282ms | 40ms | 16.529
| ThreadStore.GetMembershipForUser |  Avg| 17ms| 21ms | 4ms | 24.179
| |  P99| 239ms| 292ms | 53ms | 22.202
| ThreadStore.GetTeamsUnreadForUser |  Avg| 18ms| 20ms | 2ms | 11.019
| |  P99| 252ms| 318ms | 66ms | 26.159
| ThreadStore.GetThreadFollowers |  Avg| 18ms| 21ms | 3ms | 17.015
| |  P99| 239ms| 325ms | 86ms | 36.023
| ThreadStore.GetThreadForUser |  Avg| 25ms| 29ms | 4ms | 15.902
| |  P99| 405ms| 439ms | 34ms | 8.399
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 21ms| 23ms | 2ms | 9.667
| |  P99| 249ms| 353ms | 104ms | 41.725
| ThreadStore.GetThreadsForUser |  Avg| 22ms| 27ms | 5ms | 22.308
| |  P99| 274ms| 365ms | 91ms | 33.268
| ThreadStore.GetTotalThreads |  Avg| 14ms| 15ms | 1ms | 7.069
| |  P99| 225ms| 238ms | 13ms | 5.781
| ThreadStore.GetTotalUnreadMentions |  Avg| 14ms| 15ms | 1ms | 7.178
| |  P99| 227ms| 239ms | 12ms | 5.280
| ThreadStore.GetTotalUnreadThreads |  Avg| 14ms| 15ms | 1ms | 7.243
| |  P99| 229ms| 238ms | 9ms | 3.935
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 14ms| 15ms | 1ms | 7.100
| |  P99| 227ms| 239ms | 12ms | 5.280
| ThreadStore.MaintainMembership |  Avg| 12ms| 13ms | 1ms | 8.524
| |  P99| 177ms| 189ms | 12ms | 6.796
| ThreadStore.MarkAllAsReadByChannels |  Avg| 6ms| 7ms | 1ms | 16.594
| |  P99| 84ms| 87ms | 3ms | 3.570
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 5ms | -1ms | -15.546
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 7ms| 8ms | 1ms | 13.608
| |  P99| 70ms| 72ms | 2ms | 2.838
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 81ms| 85ms | 4ms | 4.952
| TokenStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 45.898
| |  P99| 10ms| 10ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 3ms| 6ms | 3ms | 105.842
| |  P99| 32ms| 163ms | 131ms | 406.202
| UserStore.AnalyticsActiveCount |  Avg| 592ms| 387ms | -205ms | -34.633
| |  P99| 992ms| 985ms | -7ms | -0.706
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 48ms| 3ms | -45ms | -93.794
| |  P99| 244ms| 23ms | -221ms | -90.574
| UserStore.AutocompleteUsersInChannel |  Avg| 327ms| 364ms | 37ms | 11.322
| |  P99| 1.106s| 1.795s | 689ms | 62.300
| UserStore.Count |  Avg| 288ms| 209ms | -79ms | -27.460
| |  P99| 982ms| 935ms | -47ms | -4.787
| UserStore.Get |  Avg| 7ms| 9ms | 2ms | 27.238
| |  P99| 154ms| 180ms | 26ms | 16.850
| UserStore.GetAllProfiles |  Avg| 15ms| 17ms | 2ms | 13.030
| |  P99| 222ms| 239ms | 17ms | 7.669
| UserStore.GetAllProfilesInChannel |  Avg| 851ms| 895ms | 44ms | 5.171
| |  P99| 2.7s| 4.397s | 1.697s | 62.852
| UserStore.GetByUsername |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 309ms| 303ms | -6ms | -1.941
| UserStore.GetForLogin |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 189ms| 196ms | 7ms | 3.710
| UserStore.GetMany |  Avg| 28ms| 15ms | -13ms | -45.938
| |  P99| 450ms| 209ms | -241ms | -53.555
| UserStore.GetProfileByIds |  Avg| 14ms| 17ms | 3ms | 21.827
| |  P99| 219ms| 239ms | 20ms | 9.137
| UserStore.GetProfilesByUsernames |  Avg| 16ms| 17ms | 1ms | 6.169
| |  P99| 234ms| 236ms | 2ms | 0.855
| UserStore.GetProfilesInChannel |  Avg| 19ms| 12ms | -7ms | -37.201
| |  P99| 122ms| 211ms | 89ms | 73.101
| UserStore.GetUnreadCount |  Avg| 20ms| 18ms | -2ms | -9.787
| |  P99| 410ms| 290ms | -120ms | -29.239
| UserStore.IsEmpty |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 97ms| 98ms | 1ms | 1.031
| UserStore.Save |  Avg| 80ms| 79ms | -1ms | -1.253
| |  P99| 249ms| 251ms | 2ms | 0.804
| UserStore.Search |  Avg| 144ms| 164ms | 20ms | 13.842
| |  P99| 897ms| 937ms | 40ms | 4.458
| UserStore.Update |  Avg| 13ms| 14ms | 1ms | 7.632
| |  P99| 196ms| 165ms | -31ms | -15.782
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 74ms | 2ms | 2.795
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 64ms | 2ms | 3.214
| UserTermsOfServiceStore.GetByUser |  Avg| 13ms| 14ms | 1ms | 7.518
| |  P99| 225ms| 233ms | 8ms | 3.561
| WebhookStore.GetOutgoingByTeam |  Avg| 21ms| 24ms | 3ms | 14.169
| |  P99| 243ms| 325ms | 82ms | 33.679
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 536ms| 510ms | -26ms | -4.847
| | P99| 3.975s| 3.008s | -967ms | -24.327
| addTeamMember | Avg| 1.904s| 1.828s | -76ms | -3.992
| | P99| 9.473s| 9.643s | 170ms | 1.795
| autocompleteChannelsForTeamForSearch | Avg| 295ms| 217ms | -78ms | -26.455
| | P99| 2.413s| 2.123s | -290ms | -12.017
| autocompleteEmojis | Avg| 12ms| 0s | -12ms | -97.621
| | P99| 25ms| 0s | -25ms | -101.091
| autocompleteUsers | Avg| 263ms| 291ms | 28ms | 10.633
| | P99| 997ms| 1.576s | 579ms | 58.073
| channelMemberCountsByGroup | Avg| 5ms| 0s | -5ms | -105.168
| | P99| 45ms| 0s | -45ms | -99.999
| createCategoryForTeamForUser | Avg| 49ms| 41ms | -8ms | -16.268
| | P99| 244ms| 99ms | -145ms | -59.427
| createChannel | Avg| 74ms| 49ms | -25ms | -33.690
| | P99| 245ms| 239ms | -6ms | -2.451
| createDirectChannel | Avg| 426ms| 422ms | -4ms | -0.939
| | P99| 2.339s| 2.324s | -15ms | -0.641
| createGroupChannel | Avg| 605ms| 683ms | 78ms | 12.897
| | P99| 2.39s| 4.755s | 2.365s | 98.943
| createPost | Avg| 1.365s| 1.174s | -191ms | -13.993
| | P99| 9.11s| 6.132s | -2.978s | -32.691
| createUser | Avg| 137ms| 134ms | -3ms | -2.185
| | P99| 734ms| 750ms | 16ms | 2.179
| deleteDraft | Avg| 8ms| 2ms | -6ms | -72.961
| | P99| 10ms| 5ms | -5ms | -50.208
| deletePost | Avg| 497ms| 162ms | -335ms | -67.399
| | P99| 4.725s| 2.11s | -2.615s | -55.344
| followThreadByUser | Avg| 34ms| 58ms | 24ms | 69.883
| | P99| 236ms| 422ms | 186ms | 78.647
| getAllTeams | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 235ms| 240ms | 5ms | 2.127
| getAnalytics | Avg| 742ms| 540ms | -202ms | -27.235
| | P99| 2.447s| 2.435s | -12ms | -0.490
| getCategoriesForTeamForUser | Avg| 37ms| 38ms | 1ms | 2.708
| | P99| 484ms| 498ms | 14ms | 2.893
| getChannel | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 732ms| 505ms | -227ms | -31.025
| getChannelMember | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 401ms| 420ms | 19ms | 4.739
| getChannelMembers | Avg| 6ms| 0s | -6ms | -93.168
| | P99| 24ms| 0s | -24ms | -98.969
| getChannelMembersForTeamForUser | Avg| 19ms| 21ms | 2ms | 10.437
| | P99| 246ms| 295ms | 49ms | 19.919
| getChannelMembersForUser | Avg| 414ms| 140ms | -274ms | -66.146
| | P99| 2.41s| 490ms | -1.92s | -79.668
| getChannelStats | Avg| 42ms| 42ms | 0s | 0.000
| | P99| 853ms| 873ms | 20ms | 2.344
| getChannelUnread | Avg| 14ms| 15ms | 1ms | 7.347
| | P99| 214ms| 219ms | 5ms | 2.331
| getChannelsForTeamForUser | Avg| 21ms| 23ms | 2ms | 9.632
| | P99| 265ms| 338ms | 73ms | 27.597
| getChannelsForUser | Avg| 18ms| 22ms | 4ms | 22.479
| | P99| 230ms| 289ms | 59ms | 25.608
| getClientConfig | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 208ms| 215ms | 7ms | 3.371
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 83ms| 78ms | -5ms | -5.993
| | P99| 100ms| 245ms | 145ms | 145.729
| getEmojisByNames | Avg| 10ms| 0s | -10ms | -101.581
| | P99| 94ms| 0s | -94ms | -100.534
| getFilePreview | Avg| 73ms| 74ms | 1ms | 1.367
| | P99| 467ms| 483ms | 16ms | 3.427
| getFileThumbnail | Avg| 61ms| 65ms | 4ms | 6.548
| | P99| 463ms| 486ms | 23ms | 4.967
| getFilteredUsersStats | Avg| 232ms| 126ms | -106ms | -45.765
| | P99| 248ms| 480ms | 232ms | 93.360
| getGroups | Avg| 62ms| 37ms | -25ms | -40.164
| | P99| 99ms| 242ms | 143ms | 143.899
| getGroupsAssociatedToChannelsByTeam | Avg| 62ms| 12ms | -50ms | -80.541
| | P99| 100ms| 49ms | -51ms | -51.256
| getJobsByType | Avg| 22ms| 25ms | 3ms | 13.620
| | P99| 234ms| 230ms | -4ms | -1.706
| getLicenseSelfServeStatus | Avg| 594ms| 332ms | -262ms | -44.074
| | P99| 995ms| 960ms | -35ms | -3.518
| getPostThread | Avg| 115ms| 129ms | 14ms | 12.173
| | P99| 1.794s| 2.077s | 283ms | 15.778
| getPostsForChannel | Avg| 183ms| 191ms | 8ms | 4.377
| | P99| 3.053s| 3.238s | 185ms | 6.059
| getPostsForChannelAroundLastUnread | Avg| 75ms| 77ms | 2ms | 2.681
| | P99| 986ms| 1.207s | 221ms | 22.416
| getPreferences | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 243ms| 248ms | 5ms | 2.055
| getPrevTrialLicense | Avg| 35ms| 19ms | -16ms | -45.376
| | P99| 98ms| 95ms | -3ms | -3.061
| getProductNotices | Avg| 138ms| 64ms | -74ms | -53.484
| | P99| 247ms| 245ms | -2ms | -0.810
| getProfileImage | Avg| 97ms| 90ms | -7ms | -7.181
| | P99| 481ms| 474ms | -7ms | -1.456
| getPublicChannelsForTeam | Avg| 37ms| 36ms | -1ms | -2.692
| | P99| 409ms| 325ms | -84ms | -20.550
| getRolesByNames | Avg| 8ms| 1ms | -7ms | -84.554
| | P99| 96ms| 20ms | -76ms | -79.167
| getSchemes | Avg| 2ms| 0s | -2ms | -92.514
| | P99| 5ms| 0s | -5ms | -101.010
| getSelfHostedProducts | Avg| 0s| 16ms | 16ms | 7140.944
| | P99| 5ms| 96ms | 91ms | 1838.384
| getTeamMember | Avg| 7ms| 8ms | 1ms | 13.414
| | P99| 98ms| 97ms | -1ms | -1.022
| getTeamMembersForUser | Avg| 12ms| 13ms | 1ms | 8.162
| | P99| 204ms| 221ms | 17ms | 8.316
| getTeamsForUser | Avg| 17ms| 18ms | 1ms | 5.963
| | P99| 235ms| 246ms | 11ms | 4.671
| getTeamsUnreadForUser | Avg| 25ms| 27ms | 2ms | 7.909
| | P99| 400ms| 439ms | 39ms | 9.760
| getThreadsForUser | Avg| 22ms| 26ms | 4ms | 17.955
| | P99| 294ms| 376ms | 82ms | 27.915
| getUser | Avg| 21ms| 23ms | 2ms | 9.691
| | P99| 272ms| 342ms | 70ms | 25.755
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 12ms| 16ms | 4ms | 34.003
| getUsers | Avg| 21ms| 24ms | 3ms | 14.143
| | P99| 260ms| 319ms | 59ms | 22.687
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 43ms| 46ms | 3ms | 6.909
| getUsersByNames | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 236ms| 238ms | 2ms | 0.849
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 146ms| 151ms | 5ms | 3.429
| | P99| 960ms| 989ms | 29ms | 3.022
| logout | Avg| 114ms| 125ms | 11ms | 9.645
| | P99| 479ms| 430ms | -49ms | -10.226
| patchPost | Avg| 455ms| 131ms | -324ms | -71.145
| | P99| 3.75s| 1.412s | -2.338s | -62.347
| removeUserCustomStatus | Avg| 221ms| 264ms | 43ms | 19.468
| | P99| 884ms| 994ms | 110ms | 12.443
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 117ms| 133ms | 16ms | 13.619
| | P99| 1.699s| 1.985s | 286ms | 16.830
| searchAllChannels | Avg| 107ms| 116ms | 9ms | 8.411
| | P99| 704ms| 914ms | 210ms | 29.850
| searchGroupChannels | Avg| 26ms| 28ms | 2ms | 7.552
| | P99| 388ms| 389ms | 1ms | 0.257
| searchPostsInTeam | Avg| 172ms| 189ms | 17ms | 9.911
| | P99| 2.272s| 3.677s | 1.405s | 61.844
| searchUsers | Avg| 146ms| 166ms | 20ms | 13.683
| | P99| 899ms| 938ms | 39ms | 4.337
| setPostReminder | Avg| 60ms| 85ms | 25ms | 41.781
| | P99| 447ms| 2.14s | 1.693s | 378.326
| unfollowThreadByUser | Avg| 51ms| 69ms | 18ms | 35.344
| | P99| 520ms| 487ms | -33ms | -6.346
| updateCategoriesForTeamForUser | Avg| 130ms| 267ms | 137ms | 105.615
| | P99| 951ms| 3.85s | 2.899s | 304.757
| updatePreferences | Avg| 23ms| 25ms | 2ms | 8.631
| | P99| 240ms| 243ms | 3ms | 1.250
| updateReadStateAllThreadsByUser | Avg| 7ms| 5ms | -2ms | -30.445
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 166ms| 187ms | 21ms | 12.620
| | P99| 2.17s| 2.325s | 155ms | 7.142
| updateUserCustomStatus | Avg| 255ms| 0s | -255ms | -99.894
| | P99| 989ms| 5ms | -984ms | -99.466
| uploadFileStream | Avg| 464ms| 443ms | -21ms | -4.522
| | P99| 1.757s| 1.717s | -40ms | -2.276
| upsertDraft | Avg| 81ms| 0s | -81ms | -100.424
| | P99| 485ms| 0s | -485ms | -100.000
| viewChannel | Avg| 48ms| 54ms | 6ms | 12.513
| | P99| 497ms| 649ms | 152ms | 30.557

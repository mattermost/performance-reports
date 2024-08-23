### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 10ms | 10ms | 2380390.40
| ChannelStore.GetMembers | avg | 5ms | 21ms | 16ms | 342.59
| EmojiStore.GetMultipleByName | avg | 14ms | 51ms | 37ms | 272.37
| ThreadStore.MarkAllAsReadByTeam | avg | 8ms | 28ms | 20ms | 256.70
| PostStore.AnalyticsPostCount | avg | 238ms | 593ms | 355ms | 148.92
| RetentionPolicyStore.GetAll | avg | 2ms | 4ms | 2ms | 96.50
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 9ms | 17ms | 8ms | 93.29
| SessionStore.Remove | avg | 10ms | 19ms | 9ms | 89.72
| StatusStore.SaveOrUpdate | avg | 14ms | 26ms | 12ms | 84.30
| CommandWebhookStore.Cleanup | avg | 15ms | 27ms | 12ms | 80.91
| TokenStore.Cleanup | avg | 18ms | 30ms | 12ms | 65.99
| ChannelStore.CreateInitialSidebarCategories | avg | 46ms | 64ms | 18ms | 39.16
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 33ms | 45ms | 12ms | 36.26
| ChannelStore.UpdateSidebarCategories | avg | 153ms | 200ms | 47ms | 30.74
| UserStore.GetByUsername | avg | 11ms | 14ms | 3ms | 27.52
| ChannelStore.SearchGroupChannels | avg | 17ms | 21ms | 4ms | 23.04
| LinkMetadataStore.Save | avg | 9ms | 11ms | 2ms | 22.33
| PostStore.Update | avg | 37ms | 45ms | 8ms | 21.65
| ProductNoticesStore.ClearOldNotices | avg | 24ms | 29ms | 5ms | 21.00
| ChannelStore.GetSidebarCategory | avg | 39ms | 47ms | 8ms | 20.32
| JobStore.UpdateStatusOptimistically | avg | 11ms | 13ms | 2ms | 18.78
| ClusterDiscoveryStore.SetLastPingAt | avg | 12ms | 14ms | 2ms | 17.35
| ChannelStore.CreateSidebarCategory | avg | 90ms | 100ms | 10ms | 11.08
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 33ms | 36ms | 3ms | 8.97
| PostStore.SearchPostsForUser | avg | 278ms | 283ms | 5ms | 1.80
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 74ms | 69ms | 1393.93
| ChannelStore.GetMembers | p99 | 10ms | 97ms | 87ms | 887.30
| EmojiStore.GetMultipleByName | p99 | 49ms | 245ms | 196ms | 401.36
| TokenStore.Cleanup | p99 | 50ms | 244ms | 194ms | 391.92
| JobStore.UpdateStatusOptimistically | p99 | 60ms | 190ms | 130ms | 218.48
| SessionStore.Remove | p99 | 81ms | 199ms | 118ms | 144.79
| StatusStore.SaveOrUpdate | p99 | 163ms | 391ms | 228ms | 139.62
| ChannelStore.UpdateSidebarCategories | p99 | 963ms | 2.05s | 1.087s | 112.86
| ThreadStore.MarkAllAsReadByTeam | p99 | 47ms | 98ms | 51ms | 107.37
| RetentionPolicyStore.GetAll | p99 | 5ms | 10ms | 5ms | 101.01
| PostStore.AnalyticsPostCount | p99 | 495ms | 993ms | 498ms | 100.61
| ProductNoticesStore.ClearOldNotices | p99 | 25ms | 50ms | 25ms | 100.60
| SessionStore.GetSessionsExpired | p99 | 47ms | 94ms | 47ms | 100.00
| CommandWebhookStore.Cleanup | p99 | 49ms | 98ms | 49ms | 100.00
| ClusterDiscoveryStore.SetLastPingAt | p99 | 88ms | 173ms | 85ms | 96.84
| ChannelStore.CreateSidebarCategory | p99 | 246ms | 477ms | 231ms | 94.09
| PostAcknowledgementStore.GetForPost | p99 | 90ms | 157ms | 67ms | 74.74
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 227ms | 390ms | 163ms | 71.77
| ReactionStore.GetForPost | p99 | 113ms | 169ms | 56ms | 49.68
| PostStore.Update | p99 | 259ms | 353ms | 94ms | 36.33
| UserStore.GetByUsername | p99 | 94ms | 117ms | 23ms | 24.56
| ChannelStore.GetSidebarCategory | p99 | 360ms | 407ms | 47ms | 13.06
| PostStore.GetPostsAfter | p99 | 125ms | 139ms | 14ms | 11.22
| TeamStore.GetMember | p99 | 44ms | 48ms | 4ms | 9.16
| PluginStore.List | p99 | 154ms | 160ms | 6ms | 3.90
| UserStore.GetForLogin | p99 | 91ms | 93ms | 2ms | 2.20
| PostPriorityStore.GetForPost | p99 | 94ms | 96ms | 2ms | 2.12
| DraftStore.Upsert | p99 | 161ms | 164ms | 3ms | 1.86
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | avg | 3ms | 0s | -3ms | -106.73
| ChannelStore.GetMemberCountsByGroup | avg | 14ms | 0s | -14ms | -102.67
| UserStore.GetProfilesInChannel | avg | 134ms | 13ms | -121ms | -90.15
| ProductNoticesStore.GetViews | avg | 23ms | 3ms | -20ms | -87.72
| JobStore.GetAllByTypePage | avg | 27ms | 6ms | -21ms | -76.66
| UserStore.GetProfilesNotInChannel | avg | 24ms | 6ms | -18ms | -75.92
| TeamStore.AnalyticsTeamCount | avg | 13ms | 3ms | -10ms | -74.80
| UserStore.AnalyticsGetInactiveUsersCount | avg | 6ms | 2ms | -4ms | -70.42
| PostStore.GetPostReminders | avg | 37ms | 13ms | -24ms | -64.67
| EmojiStore.Search | avg | 39ms | 16ms | -23ms | -59.18
| StatusStore.UpdateExpiredDNDStatuses | avg | 19ms | 8ms | -11ms | -57.30
| ChannelStore.GetMembersForUserWithPagination | avg | 36ms | 17ms | -19ms | -52.99
| PostStore.Delete | avg | 125ms | 60ms | -65ms | -51.86
| LicenseStore.GetAll | avg | 10ms | 5ms | -5ms | -50.80
| BotStore.Get | avg | 13ms | 7ms | -6ms | -47.72
| ChannelStore.AnalyticsTypeCount | avg | 23ms | 13ms | -10ms | -43.45
| JobStore.Save | avg | 17ms | 10ms | -7ms | -41.71
| JobStore.GetNewestJobByStatusesAndType | avg | 14ms | 9ms | -5ms | -34.54
| JobStore.GetCountByStatusAndType | avg | 15ms | 10ms | -5ms | -33.13
| PreferenceStore.DeleteCategoryAndName | avg | 17ms | 12ms | -5ms | -30.17
| PluginStore.Get | avg | 10ms | 7ms | -3ms | -29.99
| TeamStore.GetActiveMemberCount | avg | 83ms | 59ms | -24ms | -28.75
| ChannelStore.GetTeamChannels | avg | 49ms | 35ms | -14ms | -28.64
| PostPersistentNotificationStore.DeleteExpired | avg | 11ms | 8ms | -3ms | -28.52
| UserStore.AnalyticsActiveCount | avg | 45ms | 33ms | -12ms | -26.89
| ChannelStore.GetChannelsByUser | avg | 16ms | 12ms | -4ms | -25.66
| PostStore.SetPostReminder | avg | 37ms | 28ms | -9ms | -24.44
| UserStore.Update | avg | 34ms | 26ms | -8ms | -23.56
| UserStore.Count | avg | 29ms | 23ms | -6ms | -20.89
| ChannelStore.GetChannelUnread | avg | 15ms | 12ms | -3ms | -20.53
| TeamStore.GetTotalMemberCount | avg | 68ms | 55ms | -13ms | -19.12
| JobStore.Get | avg | 26ms | 21ms | -5ms | -18.96
| UserAccessTokenStore.GetByToken | avg | 16ms | 13ms | -3ms | -18.88
| RoleStore.ChannelHigherScopedPermissions | avg | 11ms | 9ms | -2ms | -18.61
| ComplianceStore.MessageExport | avg | 23ms | 19ms | -4ms | -17.56
| PluginStore.List | avg | 17ms | 14ms | -3ms | -17.17
| ChannelStore.AutocompleteInTeamForSearch | avg | 116ms | 97ms | -19ms | -16.42
| FileInfoStore.SetContent | avg | 25ms | 21ms | -4ms | -16.18
| PluginStore.SetWithOptions | avg | 13ms | 11ms | -2ms | -15.64
| UserStore.GetUnreadCount | avg | 13ms | 11ms | -2ms | -15.27
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 20ms | 17ms | -3ms | -14.66
| FileInfoStore.GetByIds | avg | 14ms | 12ms | -2ms | -14.00
| ChannelStore.CreateDirectChannel | avg | 95ms | 83ms | -12ms | -12.65
| ThreadStore.MaintainMembership | avg | 25ms | 22ms | -3ms | -12.20
| DraftStore.GetDraftsForUser | avg | 17ms | 15ms | -2ms | -12.10
| ChannelStore.Save | avg | 53ms | 47ms | -6ms | -11.31
| FileInfoStore.AttachToPost | avg | 21ms | 19ms | -2ms | -9.73
| ChannelStore.Get | avg | 21ms | 19ms | -2ms | -9.73
| PostStore.Save | avg | 40ms | 37ms | -3ms | -7.52
| PostStore.Get | avg | 29ms | 27ms | -2ms | -6.87
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 138ms | 129ms | -9ms | -6.51
| ChannelStore.GetPublicChannelsForTeam | avg | 36ms | 34ms | -2ms | -5.62
| ChannelStore.SaveMember | avg | 67ms | 65ms | -2ms | -2.99
| UserStore.GetAllProfilesInChannel | avg | 508ms | 493ms | -15ms | -2.95
| UserStore.AutocompleteUsersInChannel | avg | 79ms | 77ms | -2ms | -2.53
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 151ms | 0s | -151ms | -100.01
| ProductNoticesStore.GetViews | p99 | 238ms | 10ms | -228ms | -95.80
| JobStore.GetAllByTypePage | p99 | 448ms | 24ms | -424ms | -94.74
| UserStore.GetProfilesInChannel | p99 | 489ms | 49ms | -440ms | -90.03
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 24ms | 5ms | -19ms | -77.55
| BotStore.Get | p99 | 188ms | 42ms | -146ms | -77.45
| PostStore.GetPostReminders | p99 | 422ms | 95ms | -327ms | -77.40
| StatusStore.UpdateExpiredDNDStatuses | p99 | 203ms | 46ms | -157ms | -77.15
| TeamStore.AnalyticsTeamCount | p99 | 94ms | 23ms | -71ms | -75.13
| UserStore.GetProfilesNotInChannel | p99 | 97ms | 24ms | -73ms | -74.87
| ChannelStore.GetTeamChannels | p99 | 239ms | 97ms | -142ms | -59.48
| JobStore.Save | p99 | 209ms | 87ms | -122ms | -58.23
| TeamStore.GetActiveMemberCount | p99 | 239ms | 100ms | -139ms | -58.22
| PostPersistentNotificationStore.DeleteExpired | p99 | 177ms | 75ms | -102ms | -57.77
| TeamStore.GetTotalMemberCount | p99 | 228ms | 99ms | -129ms | -56.70
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.105s | 484ms | -621ms | -56.21
| JobStore.GetCountByStatusAndType | p99 | 186ms | 82ms | -104ms | -55.76
| PostStore.Delete | p99 | 945ms | 440ms | -505ms | -53.44
| EmojiStore.Search | p99 | 99ms | 50ms | -49ms | -49.75
| PluginStore.Get | p99 | 48ms | 24ms | -24ms | -49.55
| ChannelStore.AnalyticsTypeCount | p99 | 95ms | 48ms | -47ms | -49.39
| PostStore.SetPostReminder | p99 | 420ms | 214ms | -206ms | -49.05
| UserStore.Count | p99 | 185ms | 95ms | -90ms | -48.52
| ThreadStore.Get | p99 | 174ms | 94ms | -80ms | -46.01
| LinkMetadataStore.Save | p99 | 157ms | 86ms | -71ms | -45.22
| PostStore.GetPostReminderMetadata | p99 | 151ms | 92ms | -59ms | -39.07
| JobStore.GetNewestJobByStatusesAndType | p99 | 145ms | 91ms | -54ms | -37.24
| UserStore.GetUnreadCount | p99 | 151ms | 99ms | -52ms | -34.49
| FileInfoStore.Save | p99 | 167ms | 119ms | -48ms | -28.82
| UserStore.Update | p99 | 289ms | 208ms | -81ms | -28.05
| ChannelStore.GetChannelUnread | p99 | 178ms | 131ms | -47ms | -26.39
| ChannelStore.GetChannelsByUser | p99 | 166ms | 123ms | -43ms | -25.86
| ThreadStore.GetThreadFollowers | p99 | 130ms | 98ms | -32ms | -24.56
| TeamStore.GetTeamsByUserId | p99 | 125ms | 97ms | -28ms | -22.38
| FileInfoStore.GetForPost | p99 | 172ms | 136ms | -36ms | -20.92
| UserAccessTokenStore.GetByToken | p99 | 168ms | 138ms | -30ms | -17.91
| ChannelStore.GetMembersForUserWithPagination | p99 | 227ms | 190ms | -37ms | -16.26
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 119ms | 100ms | -19ms | -16.00
| PluginStore.SetWithOptions | p99 | 182ms | 153ms | -29ms | -15.94
| StatusStore.GetByIds | p99 | 208ms | 177ms | -31ms | -14.92
| TeamStore.Get | p99 | 116ms | 99ms | -17ms | -14.70
| PostStore.GetEtag | p99 | 168ms | 145ms | -23ms | -13.69
| LinkMetadataStore.Get | p99 | 134ms | 116ms | -18ms | -13.44
| StatusStore.UpdateLastActivityAt | p99 | 112ms | 97ms | -15ms | -13.43
| PostStore.GetPostsByThread | p99 | 150ms | 130ms | -20ms | -13.31
| GroupStore.GetGroups | p99 | 135ms | 117ms | -18ms | -13.31
| ComplianceStore.MessageExport | p99 | 235ms | 204ms | -31ms | -13.18
| PostStore.GetSingle | p99 | 129ms | 112ms | -17ms | -13.14
| ThreadStore.GetMembershipForUser | p99 | 138ms | 120ms | -18ms | -13.01
| FileInfoStore.SetContent | p99 | 232ms | 203ms | -29ms | -12.48
| JobStore.GetAllByStatus | p99 | 184ms | 162ms | -22ms | -11.97
| UserStore.GetProfileByIds | p99 | 176ms | 156ms | -20ms | -11.37
| PreferenceStore.GetAll | p99 | 110ms | 98ms | -12ms | -10.94
| ChannelStore.GetPinnedPostCount | p99 | 167ms | 149ms | -18ms | -10.80
| ChannelStore.GetMember | p99 | 153ms | 137ms | -16ms | -10.47
| ChannelStore.UpdateLastViewedAt | p99 | 110ms | 99ms | -11ms | -9.99
| ThreadStore.GetTeamsUnreadForUser | p99 | 190ms | 171ms | -19ms | -9.99
| ChannelStore.SaveMember | p99 | 546ms | 492ms | -54ms | -9.88
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 143ms | 129ms | -14ms | -9.82
| ChannelStore.GetMembersForUser | p99 | 170ms | 154ms | -16ms | -9.42
| PostStore.GetPostIdBeforeTime | p99 | 109ms | 99ms | -10ms | -9.16
| SessionStore.Save | p99 | 189ms | 172ms | -17ms | -9.01
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 104ms | 95ms | -9ms | -8.61
| FileInfoStore.Get | p99 | 167ms | 153ms | -14ms | -8.39
| ChannelStore.GetFileCount | p99 | 120ms | 110ms | -10ms | -8.30
| JobStore.Get | p99 | 233ms | 214ms | -19ms | -8.15
| UserStore.AnalyticsActiveCount | p99 | 99ms | 91ms | -8ms | -8.10
| FileInfoStore.AttachToPost | p99 | 222ms | 205ms | -17ms | -7.65
| PluginStore.Delete | p99 | 79ms | 73ms | -6ms | -7.58
| PreferenceStore.Get | p99 | 168ms | 156ms | -12ms | -7.16
| DraftStore.Get | p99 | 198ms | 184ms | -14ms | -7.08
| PostPersistentNotificationStore.GetSingle | p99 | 100ms | 93ms | -7ms | -7.03
| UserStore.GetProfilesByUsernames | p99 | 172ms | 160ms | -12ms | -6.96
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 497ms | 463ms | -34ms | -6.84
| StatusStore.Get | p99 | 88ms | 82ms | -6ms | -6.82
| ThreadStore.GetThreadsForUser | p99 | 186ms | 174ms | -12ms | -6.46
| RoleStore.ChannelHigherScopedPermissions | p99 | 47ms | 44ms | -3ms | -6.37
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 94ms | 88ms | -6ms | -6.35
| ChannelStore.GetChannels | p99 | 175ms | 164ms | -11ms | -6.28
| UserTermsOfServiceStore.GetByUser | p99 | 97ms | 91ms | -6ms | -6.19
| PostStore.GetPostsBefore | p99 | 180ms | 169ms | -11ms | -6.12
| UserStore.UpdateLastLogin | p99 | 85ms | 80ms | -5ms | -5.88
| DraftStore.GetDraftsForUser | p99 | 189ms | 178ms | -11ms | -5.84
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 491ms | 463ms | -28ms | -5.71
| EmojiStore.GetByName | p99 | 141ms | 133ms | -8ms | -5.69
| WebhookStore.GetOutgoingByTeam | p99 | 195ms | 184ms | -11ms | -5.65
| FileInfoStore.GetByIds | p99 | 165ms | 156ms | -9ms | -5.45
| PostStore.Save | p99 | 428ms | 406ms | -22ms | -5.14
| ChannelStore.GetMemberForPost | p99 | 201ms | 191ms | -10ms | -4.99
| ChannelStore.SearchGroupChannels | p99 | 193ms | 184ms | -9ms | -4.66
| TeamStore.SaveMember | p99 | 332ms | 317ms | -15ms | -4.52
| ChannelStore.GetPublicChannelsForTeam | p99 | 225ms | 215ms | -10ms | -4.45
| SystemStore.GetByName | p99 | 93ms | 89ms | -4ms | -4.30
| PostAcknowledgementStore.GetForPosts | p99 | 222ms | 213ms | -9ms | -4.06
| TeamStore.GetTeamsForUser | p99 | 100ms | 96ms | -4ms | -4.01
| JobStore.UpdateOptimistically | p99 | 175ms | 168ms | -7ms | -4.01
| ThreadStore.GetThreadForUser | p99 | 226ms | 217ms | -9ms | -3.98
| ChannelStore.CreateDirectChannel | p99 | 686ms | 659ms | -27ms | -3.94
| DraftStore.Delete | p99 | 155ms | 149ms | -6ms | -3.88
| ChannelStore.Get | p99 | 209ms | 201ms | -8ms | -3.83
| UserStore.GetAllProfiles | p99 | 79ms | 76ms | -3ms | -3.82
| PostPriorityStore.GetForPosts | p99 | 222ms | 214ms | -8ms | -3.60
| ThreadStore.GetThreadUnreadReplyCount | p99 | 168ms | 162ms | -6ms | -3.57
| ChannelStore.GetMemberLastViewedAt | p99 | 91ms | 88ms | -3ms | -3.31
| ThreadStore.MaintainMembership | p99 | 244ms | 236ms | -8ms | -3.28
| UserStore.Get | p99 | 98ms | 95ms | -3ms | -3.07
| ChannelStore.IncrementMentionCount | p99 | 99ms | 96ms | -3ms | -3.04
| ChannelStore.GetByName | p99 | 100ms | 97ms | -3ms | -3.01
| ThreadStore.GetTotalUnreadMentions | p99 | 100ms | 97ms | -3ms | -3.00
| ThreadStore.MarkAllAsReadByChannels | p99 | 102ms | 99ms | -3ms | -2.93
| PostStore.GetPostIdAfterTime | p99 | 82ms | 80ms | -2ms | -2.45
| UserStore.UpdateUpdateAt | p99 | 83ms | 81ms | -2ms | -2.41
| ChannelStore.GetMemberCount | p99 | 211ms | 206ms | -5ms | -2.37
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 88ms | 86ms | -2ms | -2.28
| SessionStore.GetLRUSessions | p99 | 89ms | 87ms | -2ms | -2.25
| AuditStore.Save | p99 | 92ms | 90ms | -2ms | -2.17
| LicenseStore.GetAll | p99 | 93ms | 91ms | -2ms | -2.15
| TeamStore.GetAllPage | p99 | 98ms | 96ms | -2ms | -2.05
| ThreadStore.GetTotalUnreadThreads | p99 | 99ms | 97ms | -2ms | -2.03
| SessionStore.UpdateLastActivityAt | p99 | 99ms | 97ms | -2ms | -2.02
| ThreadStore.UpdateMembership | p99 | 99ms | 97ms | -2ms | -2.02
| ThreadStore.GetTotalThreads | p99 | 99ms | 97ms | -2ms | -2.01
| PostStore.GetPostsSince | p99 | 224ms | 220ms | -4ms | -1.79
| PostStore.SearchPostsForUser | p99 | 2.489s | 2.446s | -43ms | -1.73
| PostStore.Get | p99 | 242ms | 238ms | -4ms | -1.65
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 245ms | 241ms | -4ms | -1.63
| PreferenceStore.Save | p99 | 249ms | 245ms | -4ms | -1.61
| ChannelStore.Save | p99 | 447ms | 440ms | -7ms | -1.57
| UserStore.Search | p99 | 241ms | 238ms | -3ms | -1.24
| UserStore.GetAllProfilesInChannel | p99 | 2.375s | 2.351s | -24ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 5ms | 22ms | 17ms | 317.51
| updateReadStateAllThreadsByUser | avg | 8ms | 28ms | 20ms | 253.48
| getAnalytics | avg | 113ms | 357ms | 244ms | 215.22
| getGroupsAssociatedToChannelsByTeam | avg | 10ms | 26ms | 16ms | 167.29
| login | avg | 256ms | 420ms | 164ms | 63.95
| getPrevTrialLicense | avg | 5ms | 7ms | 2ms | 43.07
| getCategoriesForTeamForUser | avg | 34ms | 46ms | 12ms | 35.36
| patchPost | avg | 188ms | 240ms | 52ms | 27.63
| updateCategoriesForTeamForUser | avg | 251ms | 308ms | 57ms | 22.75
| searchGroupChannels | avg | 18ms | 21ms | 3ms | 16.63
| logout | avg | 234ms | 268ms | 34ms | 14.54
| removeUserCustomStatus | avg | 497ms | 556ms | 59ms | 11.86
| getChannelMember | avg | 27ms | 29ms | 2ms | 7.49
| getChannel | avg | 38ms | 40ms | 2ms | 5.26
| unfollowThreadByUser | avg | 70ms | 73ms | 3ms | 4.31
| searchPostsInTeam | avg | 309ms | 319ms | 10ms | 3.24
| createGroupChannel | avg | 1.401s | 1.444s | 43ms | 3.07
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getAnalytics | p99 | 248ms | 4.8s | 4.552s | 1838.45
| getChannelMembers | p99 | 10ms | 97ms | 87ms | 878.57
| getPrevTrialLicense | p99 | 24ms | 93ms | 69ms | 284.15
| updateReadStateAllThreadsByUser | p99 | 47ms | 98ms | 51ms | 107.37
| setPostReminder | p99 | 473ms | 880ms | 407ms | 85.99
| unfollowThreadByUser | p99 | 482ms | 707ms | 225ms | 46.68
| updateCategoriesForTeamForUser | p99 | 1.63s | 2.326s | 696ms | 42.70
| getChannelMembersForUser | p99 | 214ms | 226ms | 12ms | 5.61
| login | p99 | 2.276s | 2.387s | 111ms | 4.88
| removeUserCustomStatus | p99 | 2.334s | 2.443s | 109ms | 4.67
| getChannelMember | p99 | 289ms | 301ms | 12ms | 4.16
| getGroupsAssociatedToChannelsByTeam | p99 | 48ms | 50ms | 2ms | 4.15
| getChannel | p99 | 358ms | 370ms | 12ms | 3.36
| autocompleteUsers | p99 | 372ms | 381ms | 9ms | 2.42
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| saveReaction | avg | 47ms | 0s | -47ms | -100.65
| channelMemberCountsByGroup | avg | 13ms | 0s | -13ms | -99.27
| getProductNotices | avg | 26ms | 5ms | -21ms | -81.82
| getJobsByType | avg | 31ms | 7ms | -24ms | -76.28
| getGroups | avg | 51ms | 20ms | -31ms | -61.24
| autocompleteEmojis | avg | 39ms | 16ms | -23ms | -59.05
| getFilteredUsersStats | avg | 39ms | 16ms | -23ms | -58.88
| followThreadByUser | avg | 91ms | 46ms | -45ms | -49.67
| getTeamStats | avg | 122ms | 64ms | -58ms | -47.58
| createChannel | avg | 1.161s | 679ms | -482ms | -41.53
| deletePost | avg | 171ms | 120ms | -51ms | -29.87
| getChannelsForUser | avg | 16ms | 12ms | -4ms | -24.59
| getChannelMembersForUser | avg | 34ms | 26ms | -8ms | -23.65
| getChannelUnread | avg | 17ms | 14ms | -3ms | -17.98
| addChannelMember | avg | 791ms | 662ms | -129ms | -16.31
| autocompleteChannelsForTeamForSearch | avg | 116ms | 98ms | -18ms | -15.53
| getUser | avg | 19ms | 17ms | -2ms | -10.72
| getPostsForChannel | avg | 137ms | 123ms | -14ms | -10.26
| getTeamsUnreadForUser | avg | 20ms | 18ms | -2ms | -10.08
| getClientConfig | avg | 23ms | 21ms | -2ms | -8.67
| getProfileImage | avg | 86ms | 80ms | -6ms | -7.00
| getPostThread | avg | 75ms | 70ms | -5ms | -6.65
| createPost | avg | 1.006s | 940ms | -66ms | -6.56
| updateReadStateThreadByUser | avg | 167ms | 157ms | -10ms | -6.00
| updatePreferences | avg | 50ms | 47ms | -3ms | -5.95
| viewChannel | avg | 54ms | 51ms | -3ms | -5.60
| createDirectChannel | avg | 924ms | 874ms | -50ms | -5.41
| getPublicChannelsForTeam | avg | 38ms | 36ms | -2ms | -5.20
| getFileThumbnail | avg | 61ms | 58ms | -3ms | -4.96
| getFilePreview | avg | 73ms | 70ms | -3ms | -4.09
| uploadFileStream | avg | 483ms | 464ms | -19ms | -3.94
| getPostsForChannelAroundLastUnread | avg | 56ms | 54ms | -2ms | -3.56
| searchAllChannels | avg | 64ms | 62ms | -2ms | -3.14
| createCategoryForTeamForUser | avg | 123ms | 120ms | -3ms | -2.45
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateUserCustomStatus | p99 | 7ms | 0s | -7ms | -105.25
| saveReaction | p99 | 416ms | 0s | -416ms | -99.93
| channelMemberCountsByGroup | p99 | 155ms | 0s | -155ms | -99.69
| getProductNotices | p99 | 239ms | 10ms | -229ms | -95.62
| getJobsByType | p99 | 448ms | 24ms | -424ms | -94.74
| getFilteredUsersStats | p99 | 235ms | 25ms | -210ms | -89.36
| getGroups | p99 | 462ms | 49ms | -413ms | -89.30
| getRolesByNames | p99 | 82ms | 23ms | -59ms | -71.95
| patchPost | p99 | 3.417s | 1.36s | -2.057s | -60.20
| getTeamStats | p99 | 248ms | 100ms | -148ms | -59.80
| autocompleteChannelsForTeamForSearch | p99 | 1.105s | 484ms | -621ms | -56.21
| logout | p99 | 1.99s | 960ms | -1.03s | -51.76
| autocompleteEmojis | p99 | 99ms | 50ms | -49ms | -49.75
| followThreadByUser | p99 | 473ms | 239ms | -234ms | -49.52
| createChannel | p99 | 4.625s | 2.41s | -2.215s | -47.89
| getTeamsForUser | p99 | 145ms | 99ms | -46ms | -31.72
| searchPostsInTeam | p99 | 3.348s | 2.49s | -858ms | -25.63
| addChannelMember | p99 | 4.313s | 3.505s | -808ms | -18.74
| getChannelsForUser | p99 | 183ms | 149ms | -34ms | -18.63
| getPostsForChannel | p99 | 1.77s | 1.472s | -298ms | -16.84
| getUserStatusesByIds | p99 | 59ms | 50ms | -9ms | -15.20
| getPreferences | p99 | 142ms | 123ms | -19ms | -13.35
| getChannelUnread | p99 | 198ms | 172ms | -26ms | -13.14
| getUsersByIds | p99 | 58ms | 52ms | -6ms | -10.38
| createGroupChannel | p99 | 8.47s | 7.687s | -783ms | -9.24
| createDirectChannel | p99 | 4.525s | 4.125s | -400ms | -8.84
| getChannelStats | p99 | 132ms | 121ms | -11ms | -8.36
| getTeamMembersForUser | p99 | 179ms | 165ms | -14ms | -7.84
| getAllTeams | p99 | 169ms | 156ms | -13ms | -7.69
| getDrafts | p99 | 218ms | 203ms | -15ms | -6.89
| deletePost | p99 | 945ms | 880ms | -65ms | -6.88
| getChannelMembersForTeamForUser | p99 | 187ms | 175ms | -12ms | -6.41
| getTeamMember | p99 | 182ms | 171ms | -11ms | -6.03
| getFileThumbnail | p99 | 379ms | 358ms | -21ms | -5.55
| getPublicChannelsForTeam | p99 | 235ms | 222ms | -13ms | -5.54
| getUsersByNames | p99 | 185ms | 175ms | -10ms | -5.39
| deleteDraft | p99 | 211ms | 200ms | -11ms | -5.22
| updatePreferences | p99 | 445ms | 422ms | -23ms | -5.17
| getChannelsForTeamForUser | p99 | 199ms | 189ms | -10ms | -5.03
| getPostsForChannelAroundLastUnread | p99 | 515ms | 490ms | -25ms | -4.85
| searchGroupChannels | p99 | 200ms | 192ms | -8ms | -3.99
| getTeamsUnreadForUser | p99 | 230ms | 221ms | -9ms | -3.92
| getFilePreview | p99 | 419ms | 404ms | -15ms | -3.58
| getPostThread | p99 | 514ms | 496ms | -18ms | -3.50
| getThreadsForUser | p99 | 202ms | 196ms | -6ms | -2.96
| getUser | p99 | 247ms | 240ms | -7ms | -2.83
| uploadFileStream | p99 | 2.239s | 2.18s | -59ms | -2.64
| addTeamMember | p99 | 9.001s | 8.783s | -218ms | -2.42
| getClientConfig | p99 | 250ms | 244ms | -6ms | -2.40
| viewChannel | p99 | 474ms | 464ms | -10ms | -2.11
| createPost | p99 | 4.981s | 4.877s | -104ms | -2.09
| createCategoryForTeamForUser | p99 | 485ms | 477ms | -8ms | -1.65
| getCategoriesForTeamForUser | p99 | 248ms | 244ms | -4ms | -1.61
| getProfileImage | p99 | 468ms | 462ms | -6ms | -1.28
| getUsers | p99 | 242ms | 239ms | -3ms | -1.24
| searchUsers | p99 | 244ms | 241ms | -3ms | -1.23
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 8ms | -1ms | -11.648
| |  P99| 92ms| 90ms | -2ms | -2.169
| BotStore.Get |  Avg| 13ms| 7ms | -6ms | -47.719
| |  P99| 188ms| 42ms | -146ms | -77.454
| BotStore.Save |  Avg| 3ms| 0s | -3ms | -106.731
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 138ms| 129ms | -9ms | -6.513
| |  P99| 491ms| 463ms | -28ms | -5.708
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 80ms | -1ms | -1.235
| ChannelStore.AnalyticsTypeCount |  Avg| 23ms| 13ms | -10ms | -43.446
| |  P99| 95ms| 48ms | -47ms | -49.394
| ChannelStore.Autocomplete |  Avg| 62ms| 61ms | -1ms | -1.603
| |  P99| 241ms| 242ms | 1ms | 0.416
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 116ms| 97ms | -19ms | -16.416
| |  P99| 1.105s| 484ms | -621ms | -56.210
| ChannelStore.CreateDirectChannel |  Avg| 95ms| 83ms | -12ms | -12.653
| |  P99| 686ms| 659ms | -27ms | -3.937
| ChannelStore.CreateInitialSidebarCategories |  Avg| 46ms| 64ms | 18ms | 39.158
| |  P99| 482ms| 483ms | 1ms | 0.208
| ChannelStore.CreateSidebarCategory |  Avg| 90ms| 100ms | 10ms | 11.080
| |  P99| 246ms| 477ms | 231ms | 94.092
| ChannelStore.Get |  Avg| 21ms| 19ms | -2ms | -9.730
| |  P99| 209ms| 201ms | -8ms | -3.831
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 33ms| 36ms | 3ms | 8.966
| |  P99| 227ms| 390ms | 163ms | 71.767
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.016
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 45ms| 44ms | -1ms | -2.246
| |  P99| 497ms| 463ms | -34ms | -6.843
| ChannelStore.GetByName |  Avg| 12ms| 11ms | -1ms | -8.667
| |  P99| 100ms| 97ms | -3ms | -3.010
| ChannelStore.GetChannelUnread |  Avg| 15ms| 12ms | -3ms | -20.527
| |  P99| 178ms| 131ms | -47ms | -26.393
| ChannelStore.GetChannels |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 175ms| 164ms | -11ms | -6.277
| ChannelStore.GetChannelsByUser |  Avg| 16ms| 12ms | -4ms | -25.655
| |  P99| 166ms| 123ms | -43ms | -25.860
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 13ms| 12ms | -1ms | -7.884
| |  P99| 143ms| 129ms | -14ms | -9.819
| ChannelStore.GetFileCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 120ms| 110ms | -10ms | -8.305
| ChannelStore.GetGuestCount |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 100ms| 99ms | -1ms | -1.005
| ChannelStore.GetMember |  Avg| 13ms| 12ms | -1ms | -7.599
| |  P99| 153ms| 137ms | -16ms | -10.473
| ChannelStore.GetMemberCount |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 211ms| 206ms | -5ms | -2.372
| ChannelStore.GetMemberCountsByGroup |  Avg| 14ms| 0s | -14ms | -102.666
| |  P99| 151ms| 0s | -151ms | -100.014
| ChannelStore.GetMemberForPost |  Avg| 20ms| 19ms | -1ms | -5.009
| |  P99| 201ms| 191ms | -10ms | -4.986
| ChannelStore.GetMemberLastViewedAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 88ms | -3ms | -3.307
| ChannelStore.GetMembers |  Avg| 5ms| 21ms | 16ms | 342.595
| |  P99| 10ms| 97ms | 87ms | 887.299
| ChannelStore.GetMembersForUser |  Avg| 15ms| 14ms | -1ms | -6.750
| |  P99| 170ms| 154ms | -16ms | -9.420
| ChannelStore.GetMembersForUserWithPagination |  Avg| 36ms| 17ms | -19ms | -52.986
| |  P99| 227ms| 190ms | -37ms | -16.264
| ChannelStore.GetPinnedPostCount |  Avg| 14ms| 13ms | -1ms | -7.038
| |  P99| 167ms| 149ms | -18ms | -10.800
| ChannelStore.GetPublicChannelsForTeam |  Avg| 36ms| 34ms | -2ms | -5.621
| |  P99| 225ms| 215ms | -10ms | -4.449
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 33ms| 45ms | 12ms | 36.263
| |  P99| 245ms| 241ms | -4ms | -1.634
| ChannelStore.GetSidebarCategory |  Avg| 39ms| 47ms | 8ms | 20.325
| |  P99| 360ms| 407ms | 47ms | 13.055
| ChannelStore.GetTeamChannels |  Avg| 49ms| 35ms | -14ms | -28.637
| |  P99| 239ms| 97ms | -142ms | -59.476
| ChannelStore.IncrementMentionCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 96ms | -3ms | -3.038
| ChannelStore.Save |  Avg| 53ms| 47ms | -6ms | -11.309
| |  P99| 447ms| 440ms | -7ms | -1.566
| ChannelStore.SaveMember |  Avg| 67ms| 65ms | -2ms | -2.989
| |  P99| 546ms| 492ms | -54ms | -9.883
| ChannelStore.SearchGroupChannels |  Avg| 17ms| 21ms | 4ms | 23.039
| |  P99| 193ms| 184ms | -9ms | -4.662
| ChannelStore.UpdateLastViewedAt |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 110ms| 99ms | -11ms | -9.992
| ChannelStore.UpdateSidebarCategories |  Avg| 153ms| 200ms | 47ms | 30.736
| |  P99| 963ms| 2.05s | 1.087s | 112.862
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 11ms| 10ms | -1ms | -9.012
| |  P99| 119ms| 100ms | -19ms | -16.004
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 14ms | 2ms | 17.351
| |  P99| 88ms| 173ms | 85ms | 96.845
| CommandWebhookStore.Cleanup |  Avg| 15ms| 27ms | 12ms | 80.908
| |  P99| 49ms| 98ms | 49ms | 100.000
| ComplianceStore.MessageExport |  Avg| 23ms| 19ms | -4ms | -17.563
| |  P99| 235ms| 204ms | -31ms | -13.176
| DraftStore.Delete |  Avg| 14ms| 13ms | -1ms | -7.007
| |  P99| 155ms| 149ms | -6ms | -3.879
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 20ms| 17ms | -3ms | -14.664
| |  P99| 94ms| 88ms | -6ms | -6.349
| DraftStore.Get |  Avg| 17ms| 16ms | -1ms | -5.920
| |  P99| 198ms| 184ms | -14ms | -7.077
| DraftStore.GetDraftsForUser |  Avg| 17ms| 15ms | -2ms | -12.102
| |  P99| 189ms| 178ms | -11ms | -5.836
| DraftStore.Upsert |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 161ms| 164ms | 3ms | 1.861
| EmojiStore.GetByName |  Avg| 12ms| 11ms | -1ms | -8.201
| |  P99| 141ms| 133ms | -8ms | -5.692
| EmojiStore.GetMultipleByName |  Avg| 14ms| 51ms | 37ms | 272.366
| |  P99| 49ms| 245ms | 196ms | 401.365
| EmojiStore.Search |  Avg| 39ms| 16ms | -23ms | -59.175
| |  P99| 99ms| 50ms | -49ms | -49.745
| FileInfoStore.AttachToPost |  Avg| 21ms| 19ms | -2ms | -9.733
| |  P99| 222ms| 205ms | -17ms | -7.649
| FileInfoStore.Get |  Avg| 14ms| 13ms | -1ms | -7.387
| |  P99| 167ms| 153ms | -14ms | -8.388
| FileInfoStore.GetByIds |  Avg| 14ms| 12ms | -2ms | -14.004
| |  P99| 165ms| 156ms | -9ms | -5.446
| FileInfoStore.GetForPost |  Avg| 13ms| 12ms | -1ms | -7.409
| |  P99| 172ms| 136ms | -36ms | -20.917
| FileInfoStore.Save |  Avg| 15ms| 14ms | -1ms | -6.477
| |  P99| 167ms| 119ms | -48ms | -28.823
| FileInfoStore.SetContent |  Avg| 25ms| 21ms | -4ms | -16.177
| |  P99| 232ms| 203ms | -29ms | -12.481
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 86ms | -2ms | -2.284
| GroupStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.125
| GroupStore.GetGroups |  Avg| 13ms| 12ms | -1ms | -7.785
| |  P99| 135ms| 117ms | -18ms | -13.308
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 9ms| 17ms | 8ms | 93.290
| |  P99| 48ms| 49ms | 1ms | 2.083
| JobStore.Get |  Avg| 26ms| 21ms | -5ms | -18.961
| |  P99| 233ms| 214ms | -19ms | -8.153
| JobStore.GetAllByStatus |  Avg| 14ms| 13ms | -1ms | -7.039
| |  P99| 184ms| 162ms | -22ms | -11.970
| JobStore.GetAllByTypePage |  Avg| 27ms| 6ms | -21ms | -76.660
| |  P99| 448ms| 24ms | -424ms | -94.744
| JobStore.GetCountByStatusAndType |  Avg| 15ms| 10ms | -5ms | -33.131
| |  P99| 186ms| 82ms | -104ms | -55.764
| JobStore.GetNewestJobByStatusesAndType |  Avg| 14ms| 9ms | -5ms | -34.538
| |  P99| 145ms| 91ms | -54ms | -37.241
| JobStore.Save |  Avg| 17ms| 10ms | -7ms | -41.708
| |  P99| 209ms| 87ms | -122ms | -58.234
| JobStore.UpdateOptimistically |  Avg| 16ms| 17ms | 1ms | 6.255
| |  P99| 175ms| 168ms | -7ms | -4.007
| JobStore.UpdateStatus |  Avg| 10ms| 9ms | -1ms | -9.943
| |  P99| 130ms| 131ms | 1ms | 0.769
| JobStore.UpdateStatusOptimistically |  Avg| 11ms| 13ms | 2ms | 18.778
| |  P99| 60ms| 190ms | 130ms | 218.481
| LicenseStore.GetAll |  Avg| 10ms| 5ms | -5ms | -50.804
| |  P99| 93ms| 91ms | -2ms | -2.151
| LinkMetadataStore.Get |  Avg| 12ms| 11ms | -1ms | -8.157
| |  P99| 134ms| 116ms | -18ms | -13.442
| LinkMetadataStore.Save |  Avg| 9ms| 11ms | 2ms | 22.333
| |  P99| 157ms| 86ms | -71ms | -45.220
| PluginStore.Delete |  Avg| 6ms| 5ms | -1ms | -17.715
| |  P99| 79ms| 73ms | -6ms | -7.576
| PluginStore.Get |  Avg| 10ms| 7ms | -3ms | -29.991
| |  P99| 48ms| 24ms | -24ms | -49.548
| PluginStore.List |  Avg| 17ms| 14ms | -3ms | -17.169
| |  P99| 154ms| 160ms | 6ms | 3.896
| PluginStore.SetWithOptions |  Avg| 13ms| 11ms | -2ms | -15.644
| |  P99| 182ms| 153ms | -29ms | -15.936
| PostAcknowledgementStore.GetForPost |  Avg| 9ms| 10ms | 1ms | 10.527
| |  P99| 90ms| 157ms | 67ms | 74.741
| PostAcknowledgementStore.GetForPosts |  Avg| 17ms| 16ms | -1ms | -5.858
| |  P99| 222ms| 213ms | -9ms | -4.058
| PostPersistentNotificationStore.DeleteExpired |  Avg| 11ms| 8ms | -3ms | -28.523
| |  P99| 177ms| 75ms | -102ms | -57.767
| PostPersistentNotificationStore.Get |  Avg| 8ms| 9ms | 1ms | 11.830
| |  P99| 76ms| 75ms | -1ms | -1.324
| PostPersistentNotificationStore.GetSingle |  Avg| 10ms| 9ms | -1ms | -9.598
| |  P99| 100ms| 93ms | -7ms | -7.033
| PostPriorityStore.GetForPost |  Avg| 10ms| 11ms | 1ms | 9.655
| |  P99| 94ms| 96ms | 2ms | 2.118
| PostPriorityStore.GetForPosts |  Avg| 18ms| 17ms | -1ms | -5.701
| |  P99| 222ms| 214ms | -8ms | -3.600
| PostStore.AnalyticsPostCount |  Avg| 238ms| 593ms | 355ms | 148.921
| |  P99| 495ms| 993ms | 498ms | 100.606
| PostStore.Delete |  Avg| 125ms| 60ms | -65ms | -51.861
| |  P99| 945ms| 440ms | -505ms | -53.439
| PostStore.Get |  Avg| 29ms| 27ms | -2ms | -6.874
| |  P99| 242ms| 238ms | -4ms | -1.653
| PostStore.GetEtag |  Avg| 14ms| 13ms | -1ms | -7.310
| |  P99| 168ms| 145ms | -23ms | -13.690
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 82ms| 80ms | -2ms | -2.448
| PostStore.GetPostIdBeforeTime |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 109ms| 99ms | -10ms | -9.159
| PostStore.GetPostReminderMetadata |  Avg| 14ms| 13ms | -1ms | -7.153
| |  P99| 151ms| 92ms | -59ms | -39.071
| PostStore.GetPostReminders |  Avg| 37ms| 13ms | -24ms | -64.670
| |  P99| 422ms| 95ms | -327ms | -77.396
| PostStore.GetPosts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 90ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 13ms| 12ms | -1ms | -7.692
| |  P99| 125ms| 139ms | 14ms | 11.222
| PostStore.GetPostsBefore |  Avg| 16ms| 15ms | -1ms | -6.171
| |  P99| 180ms| 169ms | -11ms | -6.121
| PostStore.GetPostsByThread |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 150ms| 130ms | -20ms | -13.313
| PostStore.GetPostsSince |  Avg| 30ms| 29ms | -1ms | -3.342
| |  P99| 224ms| 220ms | -4ms | -1.788
| PostStore.GetSingle |  Avg| 12ms| 11ms | -1ms | -8.239
| |  P99| 129ms| 112ms | -17ms | -13.135
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 40ms| 37ms | -3ms | -7.525
| |  P99| 428ms| 406ms | -22ms | -5.136
| PostStore.SearchPostsForUser |  Avg| 278ms| 283ms | 5ms | 1.799
| |  P99| 2.489s| 2.446s | -43ms | -1.728
| PostStore.SetPostReminder |  Avg| 37ms| 28ms | -9ms | -24.441
| |  P99| 420ms| 214ms | -206ms | -49.046
| PostStore.Update |  Avg| 37ms| 45ms | 8ms | 21.653
| |  P99| 259ms| 353ms | 94ms | 36.325
| PreferenceStore.DeleteCategoryAndName |  Avg| 17ms| 12ms | -5ms | -30.175
| |  P99| 49ms| 49ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 14ms| 13ms | -1ms | -7.085
| |  P99| 168ms| 156ms | -12ms | -7.159
| PreferenceStore.GetAll |  Avg| 11ms| 10ms | -1ms | -9.230
| |  P99| 110ms| 98ms | -12ms | -10.935
| PreferenceStore.Save |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 249ms| 245ms | -4ms | -1.609
| ProductNoticesStore.ClearOldNotices |  Avg| 24ms| 29ms | 5ms | 21.004
| |  P99| 25ms| 50ms | 25ms | 100.604
| ProductNoticesStore.GetViews |  Avg| 23ms| 3ms | -20ms | -87.724
| |  P99| 238ms| 10ms | -228ms | -95.799
| ProductNoticesStore.View |  Avg| 65ms| 66ms | 1ms | 1.538
| |  P99| 709ms| 702ms | -7ms | -0.988
| ReactionStore.GetForPost |  Avg| 14ms| 13ms | -1ms | -7.396
| |  P99| 113ms| 169ms | 56ms | 49.679
| RetentionPolicyStore.GetAll |  Avg| 2ms| 4ms | 2ms | 96.497
| |  P99| 5ms| 10ms | 5ms | 101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 11ms| 9ms | -2ms | -18.612
| |  P99| 47ms| 44ms | -3ms | -6.372
| RoleStore.GetByNames |  Avg| 0s| 10ms | 10ms | 2380390.398
| |  P99| 5ms| 74ms | 69ms | 1393.933
| SessionStore.Get |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 220ms| 219ms | -1ms | -0.454
| SessionStore.GetLRUSessions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 87ms | -2ms | -2.249
| SessionStore.GetSessionsExpired |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 47ms| 94ms | 47ms | 100.002
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 11ms| 10ms | -1ms | -9.314
| |  P99| 104ms| 95ms | -9ms | -8.614
| SessionStore.Remove |  Avg| 10ms| 19ms | 9ms | 89.723
| |  P99| 81ms| 199ms | 118ms | 144.791
| SessionStore.Save |  Avg| 16ms| 15ms | -1ms | -6.449
| |  P99| 189ms| 172ms | -17ms | -9.006
| SessionStore.UpdateLastActivityAt |  Avg| 12ms| 11ms | -1ms | -8.521
| |  P99| 99ms| 97ms | -2ms | -2.024
| StatusStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 82ms | -6ms | -6.816
| StatusStore.GetByIds |  Avg| 17ms| 16ms | -1ms | -5.955
| |  P99| 208ms| 177ms | -31ms | -14.923
| StatusStore.SaveOrUpdate |  Avg| 14ms| 26ms | 12ms | 84.300
| |  P99| 163ms| 391ms | 228ms | 139.616
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 19ms| 8ms | -11ms | -57.297
| |  P99| 203ms| 46ms | -157ms | -77.150
| StatusStore.UpdateLastActivityAt |  Avg| 11ms| 10ms | -1ms | -8.959
| |  P99| 112ms| 97ms | -15ms | -13.431
| SystemStore.GetByName |  Avg| 7ms| 6ms | -1ms | -14.373
| |  P99| 93ms| 89ms | -4ms | -4.303
| TeamStore.AnalyticsTeamCount |  Avg| 13ms| 3ms | -10ms | -74.799
| |  P99| 94ms| 23ms | -71ms | -75.134
| TeamStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 116ms| 99ms | -17ms | -14.696
| TeamStore.GetActiveMemberCount |  Avg| 83ms| 59ms | -24ms | -28.753
| |  P99| 239ms| 100ms | -139ms | -58.221
| TeamStore.GetAllPage |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 96ms | -2ms | -2.046
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 98ms | -1ms | -1.011
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 48ms | 4ms | 9.164
| TeamStore.GetTeamsByUserId |  Avg| 10ms| 9ms | -1ms | -10.142
| |  P99| 125ms| 97ms | -28ms | -22.385
| TeamStore.GetTeamsForUser |  Avg| 10ms| 9ms | -1ms | -10.227
| |  P99| 100ms| 96ms | -4ms | -4.015
| TeamStore.GetTotalMemberCount |  Avg| 68ms| 55ms | -13ms | -19.123
| |  P99| 228ms| 99ms | -129ms | -56.701
| TeamStore.SaveMember |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 332ms| 317ms | -15ms | -4.525
| ThreadStore.Get |  Avg| 12ms| 11ms | -1ms | -8.127
| |  P99| 174ms| 94ms | -80ms | -46.009
| ThreadStore.GetMembershipForUser |  Avg| 12ms| 11ms | -1ms | -8.451
| |  P99| 138ms| 120ms | -18ms | -13.005
| ThreadStore.GetTeamsUnreadForUser |  Avg| 14ms| 13ms | -1ms | -6.910
| |  P99| 190ms| 171ms | -19ms | -9.991
| ThreadStore.GetThreadFollowers |  Avg| 12ms| 11ms | -1ms | -8.263
| |  P99| 130ms| 98ms | -32ms | -24.561
| ThreadStore.GetThreadForUser |  Avg| 22ms| 21ms | -1ms | -4.451
| |  P99| 226ms| 217ms | -9ms | -3.984
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 168ms| 162ms | -6ms | -3.571
| ThreadStore.GetThreadsForUser |  Avg| 17ms| 16ms | -1ms | -5.888
| |  P99| 186ms| 174ms | -12ms | -6.455
| ThreadStore.GetTotalThreads |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 97ms | -2ms | -2.015
| ThreadStore.GetTotalUnreadMentions |  Avg| 11ms| 10ms | -1ms | -9.405
| |  P99| 100ms| 97ms | -3ms | -3.001
| ThreadStore.GetTotalUnreadThreads |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 97ms | -2ms | -2.030
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 25ms| 22ms | -3ms | -12.200
| |  P99| 244ms| 236ms | -8ms | -3.278
| ThreadStore.MarkAllAsReadByChannels |  Avg| 12ms| 11ms | -1ms | -8.262
| |  P99| 102ms| 99ms | -3ms | -2.929
| ThreadStore.MarkAllAsReadByTeam |  Avg| 8ms| 28ms | 20ms | 256.699
| |  P99| 47ms| 98ms | 51ms | 107.370
| ThreadStore.MarkAsRead |  Avg| 12ms| 11ms | -1ms | -8.606
| |  P99| 96ms| 96ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 12ms| 11ms | -1ms | -8.683
| |  P99| 99ms| 97ms | -2ms | -2.019
| TokenStore.Cleanup |  Avg| 18ms| 30ms | 12ms | 65.994
| |  P99| 50ms| 244ms | 194ms | 391.919
| UserAccessTokenStore.GetByToken |  Avg| 16ms| 13ms | -3ms | -18.881
| |  P99| 168ms| 138ms | -30ms | -17.910
| UserStore.AnalyticsActiveCount |  Avg| 45ms| 33ms | -12ms | -26.890
| |  P99| 99ms| 91ms | -8ms | -8.101
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 6ms| 2ms | -4ms | -70.420
| |  P99| 24ms| 5ms | -19ms | -77.551
| UserStore.AutocompleteUsersInChannel |  Avg| 79ms| 77ms | -2ms | -2.532
| |  P99| 389ms| 387ms | -2ms | -0.514
| UserStore.Count |  Avg| 29ms| 23ms | -6ms | -20.895
| |  P99| 185ms| 95ms | -90ms | -48.518
| UserStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 98ms| 95ms | -3ms | -3.074
| UserStore.GetAllProfiles |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 76ms | -3ms | -3.816
| UserStore.GetAllProfilesInChannel |  Avg| 508ms| 493ms | -15ms | -2.953
| |  P99| 2.375s| 2.351s | -24ms | -1.010
| UserStore.GetByUsername |  Avg| 11ms| 14ms | 3ms | 27.521
| |  P99| 94ms| 117ms | 23ms | 24.555
| UserStore.GetForLogin |  Avg| 8ms| 9ms | 1ms | 11.958
| |  P99| 91ms| 93ms | 2ms | 2.200
| UserStore.GetMany |  Avg| 11ms| 12ms | 1ms | 8.783
| |  P99| 93ms| 94ms | 1ms | 1.078
| UserStore.GetProfileByIds |  Avg| 14ms| 13ms | -1ms | -7.064
| |  P99| 176ms| 156ms | -20ms | -11.367
| UserStore.GetProfilesByUsernames |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 172ms| 160ms | -12ms | -6.965
| UserStore.GetProfilesInChannel |  Avg| 134ms| 13ms | -121ms | -90.153
| |  P99| 489ms| 49ms | -440ms | -90.026
| UserStore.GetProfilesNotInChannel |  Avg| 24ms| 6ms | -18ms | -75.921
| |  P99| 97ms| 24ms | -73ms | -74.872
| UserStore.GetUnreadCount |  Avg| 13ms| 11ms | -2ms | -15.271
| |  P99| 151ms| 99ms | -52ms | -34.491
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| UserStore.Save |  Avg| 94ms| 94ms | 0s | 0.000
| |  P99| 415ms| 414ms | -1ms | -0.241
| UserStore.Search |  Avg| 58ms| 57ms | -1ms | -1.727
| |  P99| 241ms| 238ms | -3ms | -1.245
| UserStore.Update |  Avg| 34ms| 26ms | -8ms | -23.556
| |  P99| 289ms| 208ms | -81ms | -28.052
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.110
| UserStore.UpdateLastLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 85ms| 80ms | -5ms | -5.885
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 81ms | -2ms | -2.414
| UserTermsOfServiceStore.GetByUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 97ms| 91ms | -6ms | -6.193
| WebhookStore.GetOutgoingByTeam |  Avg| 17ms| 16ms | -1ms | -6.037
| |  P99| 195ms| 184ms | -11ms | -5.649
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 791ms| 662ms | -129ms | -16.312
| | P99| 4.313s| 3.505s | -808ms | -18.736
| addTeamMember | Avg| 1.586s| 1.576s | -10ms | -0.631
| | P99| 9.001s| 8.783s | -218ms | -2.422
| autocompleteChannelsForTeamForSearch | Avg| 116ms| 98ms | -18ms | -15.526
| | P99| 1.105s| 484ms | -621ms | -56.210
| autocompleteEmojis | Avg| 39ms| 16ms | -23ms | -59.055
| | P99| 99ms| 50ms | -49ms | -49.745
| autocompleteUsers | Avg| 73ms| 72ms | -1ms | -1.374
| | P99| 372ms| 381ms | 9ms | 2.420
| channelMemberCountsByGroup | Avg| 13ms| 0s | -13ms | -99.267
| | P99| 155ms| 0s | -155ms | -99.692
| createCategoryForTeamForUser | Avg| 123ms| 120ms | -3ms | -2.448
| | P99| 485ms| 477ms | -8ms | -1.649
| createChannel | Avg| 1.161s| 679ms | -482ms | -41.525
| | P99| 4.625s| 2.41s | -2.215s | -47.892
| createDirectChannel | Avg| 924ms| 874ms | -50ms | -5.413
| | P99| 4.525s| 4.125s | -400ms | -8.840
| createGroupChannel | Avg| 1.401s| 1.444s | 43ms | 3.070
| | P99| 8.47s| 7.687s | -783ms | -9.244
| createPost | Avg| 1.006s| 940ms | -66ms | -6.563
| | P99| 4.981s| 4.877s | -104ms | -2.088
| createUser | Avg| 360ms| 360ms | 0s | 0.000
| | P99| 2.307s| 2.299s | -8ms | -0.347
| deleteDraft | Avg| 18ms| 17ms | -1ms | -5.496
| | P99| 211ms| 200ms | -11ms | -5.224
| deletePost | Avg| 171ms| 120ms | -51ms | -29.869
| | P99| 945ms| 880ms | -65ms | -6.878
| followThreadByUser | Avg| 91ms| 46ms | -45ms | -49.675
| | P99| 473ms| 239ms | -234ms | -49.524
| getAllTeams | Avg| 12ms| 11ms | -1ms | -8.671
| | P99| 169ms| 156ms | -13ms | -7.688
| getAnalytics | Avg| 113ms| 357ms | 244ms | 215.222
| | P99| 248ms| 4.8s | 4.552s | 1838.448
| getCategoriesForTeamForUser | Avg| 34ms| 46ms | 12ms | 35.355
| | P99| 248ms| 244ms | -4ms | -1.612
| getChannel | Avg| 38ms| 40ms | 2ms | 5.265
| | P99| 358ms| 370ms | 12ms | 3.357
| getChannelMember | Avg| 27ms| 29ms | 2ms | 7.491
| | P99| 289ms| 301ms | 12ms | 4.156
| getChannelMembers | Avg| 5ms| 22ms | 17ms | 317.511
| | P99| 10ms| 97ms | 87ms | 878.566
| getChannelMembersForTeamForUser | Avg| 16ms| 15ms | -1ms | -6.310
| | P99| 187ms| 175ms | -12ms | -6.414
| getChannelMembersForUser | Avg| 34ms| 26ms | -8ms | -23.650
| | P99| 214ms| 226ms | 12ms | 5.608
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 132ms| 121ms | -11ms | -8.362
| getChannelUnread | Avg| 17ms| 14ms | -3ms | -17.979
| | P99| 198ms| 172ms | -26ms | -13.135
| getChannelsForTeamForUser | Avg| 16ms| 15ms | -1ms | -6.183
| | P99| 199ms| 189ms | -10ms | -5.031
| getChannelsForUser | Avg| 16ms| 12ms | -4ms | -24.586
| | P99| 183ms| 149ms | -34ms | -18.626
| getClientConfig | Avg| 23ms| 21ms | -2ms | -8.669
| | P99| 250ms| 244ms | -6ms | -2.404
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 18ms| 17ms | -1ms | -5.411
| | P99| 218ms| 203ms | -15ms | -6.887
| getFilePreview | Avg| 73ms| 70ms | -3ms | -4.093
| | P99| 419ms| 404ms | -15ms | -3.579
| getFileThumbnail | Avg| 61ms| 58ms | -3ms | -4.958
| | P99| 379ms| 358ms | -21ms | -5.548
| getFilteredUsersStats | Avg| 39ms| 16ms | -23ms | -58.878
| | P99| 235ms| 25ms | -210ms | -89.361
| getGroups | Avg| 51ms| 20ms | -31ms | -61.236
| | P99| 462ms| 49ms | -413ms | -89.299
| getGroupsAssociatedToChannelsByTeam | Avg| 10ms| 26ms | 16ms | 167.288
| | P99| 48ms| 50ms | 2ms | 4.145
| getJobsByType | Avg| 31ms| 7ms | -24ms | -76.275
| | P99| 448ms| 24ms | -424ms | -94.744
| getPostThread | Avg| 75ms| 70ms | -5ms | -6.648
| | P99| 514ms| 496ms | -18ms | -3.503
| getPostsForChannel | Avg| 137ms| 123ms | -14ms | -10.256
| | P99| 1.77s| 1.472s | -298ms | -16.838
| getPostsForChannelAroundLastUnread | Avg| 56ms| 54ms | -2ms | -3.560
| | P99| 515ms| 490ms | -25ms | -4.851
| getPreferences | Avg| 12ms| 11ms | -1ms | -8.592
| | P99| 142ms| 123ms | -19ms | -13.355
| getPrevTrialLicense | Avg| 5ms| 7ms | 2ms | 43.072
| | P99| 24ms| 93ms | 69ms | 284.152
| getProductNotices | Avg| 26ms| 5ms | -21ms | -81.816
| | P99| 239ms| 10ms | -229ms | -95.617
| getProfileImage | Avg| 86ms| 80ms | -6ms | -7.003
| | P99| 468ms| 462ms | -6ms | -1.282
| getPublicChannelsForTeam | Avg| 38ms| 36ms | -2ms | -5.204
| | P99| 235ms| 222ms | -13ms | -5.544
| getRolesByNames | Avg| 3ms| 2ms | -1ms | -35.535
| | P99| 82ms| 23ms | -59ms | -71.946
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 14ms| 13ms | -1ms | -7.030
| | P99| 182ms| 171ms | -11ms | -6.031
| getTeamMembersForUser | Avg| 13ms| 12ms | -1ms | -7.963
| | P99| 179ms| 165ms | -14ms | -7.836
| getTeamStats | Avg| 122ms| 64ms | -58ms | -47.580
| | P99| 248ms| 100ms | -148ms | -59.798
| getTeamsForUser | Avg| 10ms| 9ms | -1ms | -9.601
| | P99| 145ms| 99ms | -46ms | -31.722
| getTeamsUnreadForUser | Avg| 20ms| 18ms | -2ms | -10.078
| | P99| 230ms| 221ms | -9ms | -3.920
| getThreadsForUser | Avg| 18ms| 17ms | -1ms | -5.637
| | P99| 202ms| 196ms | -6ms | -2.964
| getUser | Avg| 19ms| 17ms | -2ms | -10.718
| | P99| 247ms| 240ms | -7ms | -2.828
| getUserStatus | Avg| 0s| 1ms | 1ms | 200.492
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 3ms| 2ms | -1ms | -39.223
| | P99| 59ms| 50ms | -9ms | -15.202
| getUsers | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 242ms| 239ms | -3ms | -1.240
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 58ms| 52ms | -6ms | -10.381
| getUsersByNames | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 185ms| 175ms | -10ms | -5.393
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 256ms| 420ms | 164ms | 63.950
| | P99| 2.276s| 2.387s | 111ms | 4.878
| logout | Avg| 234ms| 268ms | 34ms | 14.538
| | P99| 1.99s| 960ms | -1.03s | -51.757
| patchPost | Avg| 188ms| 240ms | 52ms | 27.632
| | P99| 3.417s| 1.36s | -2.057s | -60.204
| removeUserCustomStatus | Avg| 497ms| 556ms | 59ms | 11.861
| | P99| 2.334s| 2.443s | 109ms | 4.670
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 47ms| 0s | -47ms | -100.647
| | P99| 416ms| 0s | -416ms | -99.930
| searchAllChannels | Avg| 64ms| 62ms | -2ms | -3.144
| | P99| 242ms| 243ms | 1ms | 0.414
| searchGroupChannels | Avg| 18ms| 21ms | 3ms | 16.629
| | P99| 200ms| 192ms | -8ms | -3.991
| searchPostsInTeam | Avg| 309ms| 319ms | 10ms | 3.238
| | P99| 3.348s| 2.49s | -858ms | -25.631
| searchUsers | Avg| 61ms| 60ms | -1ms | -1.639
| | P99| 244ms| 241ms | -3ms | -1.229
| setPostReminder | Avg| 93ms| 94ms | 1ms | 1.076
| | P99| 473ms| 880ms | 407ms | 85.985
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 70ms| 73ms | 3ms | 4.312
| | P99| 482ms| 707ms | 225ms | 46.676
| updateCategoriesForTeamForUser | Avg| 251ms| 308ms | 57ms | 22.750
| | P99| 1.63s| 2.326s | 696ms | 42.698
| updatePreferences | Avg| 50ms| 47ms | -3ms | -5.948
| | P99| 445ms| 422ms | -23ms | -5.171
| updateReadStateAllThreadsByUser | Avg| 8ms| 28ms | 20ms | 253.483
| | P99| 47ms| 98ms | 51ms | 107.370
| updateReadStateThreadByUser | Avg| 167ms| 157ms | -10ms | -6.003
| | P99| 984ms| 981ms | -3ms | -0.305
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -139.322
| | P99| 7ms| 0s | -7ms | -105.251
| uploadFileStream | Avg| 483ms| 464ms | -19ms | -3.938
| | P99| 2.239s| 2.18s | -59ms | -2.635
| upsertDraft | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 214ms| 212ms | -2ms | -0.936
| viewChannel | Avg| 54ms| 51ms | -3ms | -5.601
| | P99| 474ms| 464ms | -10ms | -2.111

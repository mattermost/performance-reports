### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | avg | 43ms | 108ms | 65ms | 152.50
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 7ms | 4ms | 130.32
| ChannelStore.UpdateSidebarCategories | avg | 58ms | 117ms | 59ms | 101.35
| PostStore.AnalyticsPostCount | avg | 2.76s | 4.653s | 1.893s | 68.58
| SessionStore.Remove | avg | 6ms | 9ms | 3ms | 54.48
| StatusStore.SaveOrUpdate | avg | 41ms | 63ms | 22ms | 53.25
| SessionStore.GetSessionsExpired | avg | 4ms | 6ms | 2ms | 46.30
| SessionStore.Get | avg | 10ms | 14ms | 4ms | 39.50
| ChannelStore.AutocompleteInTeamForSearch | avg | 243ms | 268ms | 25ms | 10.28
| ChannelStore.GetTeamChannels | avg | 46ms | 50ms | 4ms | 8.67
| ChannelStore.GetMemberCount | avg | 187ms | 193ms | 6ms | 3.20
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 25ms | 20ms | 404.04
| ChannelStore.UpdateSidebarCategories | p99 | 245ms | 930ms | 685ms | 280.08
| TokenStore.Cleanup | p99 | 10ms | 24ms | 14ms | 141.41
| PostStore.GetPostReminders | p99 | 94ms | 214ms | 120ms | 127.66
| ChannelStore.CreateSidebarCategory | p99 | 246ms | 490ms | 244ms | 99.39
| ClusterDiscoveryStore.SetLastPingAt | p99 | 89ms | 128ms | 39ms | 43.78
| ChannelStore.GetSidebarCategory | p99 | 225ms | 315ms | 90ms | 39.93
| SessionStore.Get | p99 | 155ms | 211ms | 56ms | 36.03
| FileInfoStore.SetContent | p99 | 144ms | 171ms | 27ms | 18.74
| ChannelStore.CreateDirectChannel | p99 | 476ms | 565ms | 89ms | 18.69
| JobStore.Get | p99 | 172ms | 200ms | 28ms | 16.29
| StatusStore.GetByIds | p99 | 112ms | 129ms | 17ms | 15.15
| UserStore.UpdateUpdateAt | p99 | 62ms | 70ms | 8ms | 12.92
| ChannelStore.GetChannelsByUser | p99 | 151ms | 169ms | 18ms | 11.96
| ChannelStore.GetFileCount | p99 | 134ms | 149ms | 15ms | 11.19
| ChannelStore.CreateInitialSidebarCategories | p99 | 351ms | 389ms | 38ms | 10.81
| PostAcknowledgementStore.GetForPost | p99 | 87ms | 96ms | 9ms | 10.31
| SessionStore.Remove | p99 | 44ms | 48ms | 4ms | 9.14
| ThreadStore.GetTotalUnreadThreads | p99 | 150ms | 163ms | 13ms | 8.69
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 148ms | 159ms | 11ms | 7.43
| StatusStore.SaveOrUpdate | p99 | 835ms | 895ms | 60ms | 7.18
| ChannelStore.GetTeamChannels | p99 | 224ms | 240ms | 16ms | 7.13
| PostStore.Update | p99 | 220ms | 233ms | 13ms | 5.90
| ThreadStore.GetTotalThreads | p99 | 153ms | 162ms | 9ms | 5.89
| UserStore.IsEmpty | p99 | 53ms | 56ms | 3ms | 5.64
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.293s | 2.413s | 120ms | 5.23
| TeamStore.SaveMember | p99 | 353ms | 368ms | 15ms | 4.25
| ChannelStore.GetMemberCount | p99 | 913ms | 943ms | 30ms | 3.29
| StatusStore.Get | p99 | 93ms | 96ms | 3ms | 3.23
| TeamStore.GetTeamsByUserId | p99 | 172ms | 177ms | 5ms | 2.91
| ProductNoticesStore.View | p99 | 467ms | 479ms | 12ms | 2.57
| FileInfoStore.AttachToPost | p99 | 92ms | 94ms | 2ms | 2.16
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 155ms | 158ms | 3ms | 1.93
| PostStore.SetPostReminder | p99 | 216ms | 220ms | 4ms | 1.86
| PostStore.GetPosts | p99 | 133ms | 135ms | 2ms | 1.51
| ChannelStore.GetGuestCount | p99 | 225ms | 228ms | 3ms | 1.33
| ThreadStore.GetTotalUnreadMentions | p99 | 152ms | 154ms | 2ms | 1.32
| ChannelStore.GetByName | p99 | 171ms | 173ms | 2ms | 1.17
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -118.37
| UserStore.AnalyticsGetInactiveUsersCount | avg | 2ms | 0s | -2ms | -115.33
| LicenseStore.GetAll | avg | 4ms | 0s | -4ms | -113.94
| ProductNoticesStore.GetViews | avg | 8ms | 0s | -8ms | -104.61
| ChannelStore.GetMemberCountsByGroup | avg | 16ms | 0s | -16ms | -102.95
| TeamStore.AnalyticsTeamCount | avg | 16ms | 0s | -16ms | -102.41
| ComplianceStore.MessageExport | avg | 11ms | 0s | -11ms | -100.76
| UserStore.AnalyticsActiveCount | avg | 337ms | 0s | -337ms | -100.11
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 149ms | 0s | -149ms | -99.97
| ChannelStore.AnalyticsTypeCount | avg | 127ms | 0s | -127ms | -99.94
| PluginStore.Get | avg | 63ms | 1ms | -62ms | -98.52
| DraftStore.Get | avg | 61ms | 1ms | -60ms | -97.82
| DraftStore.GetDraftsForUser | avg | 4ms | 0s | -4ms | -97.40
| JobStore.GetAllByTypePage | avg | 4ms | 0s | -4ms | -97.30
| DraftStore.Upsert | avg | 35ms | 4ms | -31ms | -88.54
| FileInfoStore.Search | avg | 49ms | 10ms | -39ms | -80.35
| UserAccessTokenStore.GetByToken | avg | 9ms | 2ms | -7ms | -79.92
| PostPersistentNotificationStore.Get | avg | 8ms | 2ms | -6ms | -74.05
| RoleStore.ChannelHigherScopedPermissions | avg | 13ms | 4ms | -9ms | -71.65
| UserStore.GetMany | avg | 8ms | 2ms | -6ms | -71.24
| PostPersistentNotificationStore.DeleteExpired | avg | 6ms | 2ms | -4ms | -64.10
| CommandWebhookStore.Cleanup | avg | 11ms | 4ms | -7ms | -63.46
| ProductNoticesStore.ClearOldNotices | avg | 3ms | 1ms | -2ms | -58.14
| PostStore.GetPostReminderMetadata | avg | 18ms | 8ms | -10ms | -55.81
| UserStore.GetProfilesInChannel | avg | 15ms | 7ms | -8ms | -54.51
| UserStore.GetByUsername | avg | 12ms | 6ms | -6ms | -51.66
| ChannelStore.GetMembersForUserWithPagination | avg | 77ms | 38ms | -39ms | -50.49
| StatusStore.UpdateExpiredDNDStatuses | avg | 22ms | 11ms | -11ms | -50.41
| JobStore.UpdateOptimistically | avg | 8ms | 4ms | -4ms | -49.05
| TokenStore.Cleanup | avg | 5ms | 3ms | -2ms | -44.28
| JobStore.UpdateStatus | avg | 7ms | 4ms | -3ms | -40.19
| BotStore.Get | avg | 8ms | 5ms | -3ms | -38.60
| JobStore.Save | avg | 9ms | 6ms | -3ms | -33.40
| JobStore.UpdateStatusOptimistically | avg | 10ms | 7ms | -3ms | -30.92
| PostStore.GetPostsAfter | avg | 10ms | 7ms | -3ms | -29.35
| ThreadStore.Get | avg | 10ms | 7ms | -3ms | -29.19
| UserStore.Count | avg | 184ms | 132ms | -52ms | -28.25
| TeamStore.GetByName | avg | 7ms | 5ms | -2ms | -27.98
| ChannelStore.SearchGroupChannels | avg | 15ms | 11ms | -4ms | -26.16
| PostPriorityStore.GetForPost | avg | 8ms | 6ms | -2ms | -24.71
| PluginStore.List | avg | 12ms | 9ms | -3ms | -24.57
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 8ms | 6ms | -2ms | -24.01
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 9ms | 7ms | -2ms | -23.11
| JobStore.GetAllByStatus | avg | 14ms | 11ms | -3ms | -22.08
| ChannelStore.GetPublicChannelsForTeam | avg | 23ms | 18ms | -5ms | -21.95
| FileInfoStore.GetForPost | avg | 10ms | 8ms | -2ms | -21.02
| ThreadStore.GetMembershipForUser | avg | 10ms | 8ms | -2ms | -20.32
| ReactionStore.Save | avg | 20ms | 16ms | -4ms | -20.23
| JobStore.GetCountByStatusAndType | avg | 10ms | 8ms | -2ms | -19.66
| LinkMetadataStore.Save | avg | 10ms | 8ms | -2ms | -19.62
| PostStore.Get | avg | 21ms | 17ms | -4ms | -19.06
| PreferenceStore.Get | avg | 11ms | 9ms | -2ms | -18.92
| ChannelStore.GetPinnedPostCount | avg | 11ms | 9ms | -2ms | -18.79
| ThreadStore.GetThreadUnreadReplyCount | avg | 11ms | 9ms | -2ms | -18.32
| PostAcknowledgementStore.GetForPosts | avg | 12ms | 10ms | -2ms | -17.34
| ChannelStore.UpdateLastViewedAt | avg | 12ms | 10ms | -2ms | -17.06
| ThreadStore.MaintainMembership | avg | 12ms | 10ms | -2ms | -17.02
| PostPriorityStore.GetForPosts | avg | 13ms | 11ms | -2ms | -15.99
| PostStore.GetPostsBefore | avg | 13ms | 11ms | -2ms | -15.58
| ThreadStore.GetThreadForUser | avg | 14ms | 12ms | -2ms | -14.76
| ThreadStore.GetThreadsForUser | avg | 14ms | 12ms | -2ms | -14.76
| PostStore.Update | avg | 27ms | 23ms | -4ms | -14.66
| FileInfoStore.SetContent | avg | 15ms | 13ms | -2ms | -13.56
| ChannelStore.CreateDirectChannel | avg | 52ms | 45ms | -7ms | -13.48
| UserStore.Update | avg | 16ms | 14ms | -2ms | -12.79
| UserStore.GetUnreadCount | avg | 16ms | 14ms | -2ms | -12.45
| UserStore.Search | avg | 76ms | 67ms | -9ms | -11.87
| PreferenceStore.DeleteCategoryAndName | avg | 18ms | 16ms | -2ms | -11.15
| ChannelStore.Autocomplete | avg | 101ms | 90ms | -11ms | -10.94
| ChannelStore.GetSidebarCategory | avg | 21ms | 19ms | -2ms | -9.69
| PostStore.Save | avg | 22ms | 20ms | -2ms | -9.13
| PostStore.GetPostsSince | avg | 27ms | 25ms | -2ms | -7.36
| UserStore.AutocompleteUsersInChannel | avg | 275ms | 255ms | -20ms | -7.27
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 40ms | 38ms | -2ms | -5.04
| UserStore.GetAllProfilesInChannel | avg | 739ms | 708ms | -31ms | -4.20
| ChannelStore.GetMembers | avg | 189ms | 185ms | -4ms | -2.11
| PostStore.SearchPostsForUser | avg | 128ms | 126ms | -2ms | -1.56
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 10ms | 0s | -10ms | -102.75
| JobStore.GetAllByTypePage | p99 | 24ms | 0s | -24ms | -102.12
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -100.90
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 965ms | 0s | -965ms | -100.04
| UserStore.AnalyticsActiveCount | p99 | 941ms | 0s | -941ms | -100.01
| ChannelStore.GetMemberCountsByGroup | p99 | 95ms | 0s | -95ms | -99.95
| ChannelStore.AnalyticsTypeCount | p99 | 248ms | 0s | -248ms | -99.91
| ComplianceStore.MessageExport | p99 | 99ms | 0s | -99ms | -99.83
| TeamStore.AnalyticsTeamCount | p99 | 96ms | 0s | -96ms | -99.49
| PluginStore.Get | p99 | 470ms | 5ms | -465ms | -98.94
| LicenseStore.GetAll | p99 | 23ms | 0s | -23ms | -98.85
| ProductNoticesStore.GetViews | p99 | 24ms | 0s | -24ms | -98.36
| DraftStore.Get | p99 | 246ms | 5ms | -241ms | -98.17
| DraftStore.GetDraftsForUser | p99 | 24ms | 0s | -24ms | -97.96
| UserStore.GetMany | p99 | 220ms | 21ms | -199ms | -90.46
| DraftStore.Upsert | p99 | 99ms | 10ms | -89ms | -89.90
| RoleStore.ChannelHigherScopedPermissions | p99 | 231ms | 35ms | -196ms | -84.81
| ChannelStore.GetMembersForUserWithPagination | p99 | 451ms | 99ms | -352ms | -78.03
| UserAccessTokenStore.GetByToken | p99 | 94ms | 22ms | -72ms | -76.39
| PostPersistentNotificationStore.Get | p99 | 91ms | 22ms | -69ms | -76.04
| JobStore.UpdateOptimistically | p99 | 81ms | 22ms | -59ms | -73.22
| JobStore.UpdateStatusOptimistically | p99 | 161ms | 46ms | -115ms | -71.23
| PostPersistentNotificationStore.DeleteExpired | p99 | 81ms | 23ms | -58ms | -71.17
| UserStore.GetProfilesInChannel | p99 | 148ms | 65ms | -83ms | -56.08
| UserStore.GetByUsername | p99 | 192ms | 88ms | -104ms | -54.10
| JobStore.UpdateStatus | p99 | 47ms | 22ms | -25ms | -53.08
| ChannelStore.GetPublicChannelsForTeam | p99 | 208ms | 100ms | -108ms | -51.92
| CommandWebhookStore.Cleanup | p99 | 49ms | 24ms | -25ms | -51.02
| FileInfoStore.Search | p99 | 50ms | 25ms | -25ms | -50.18
| PostStore.Delete | p99 | 457ms | 234ms | -223ms | -48.74
| PostPriorityStore.GetForPost | p99 | 146ms | 80ms | -66ms | -45.28
| PostStore.GetPostsAfter | p99 | 146ms | 88ms | -58ms | -39.70
| UserStore.Count | p99 | 755ms | 476ms | -279ms | -36.95
| ChannelStore.UpdateLastViewedAt | p99 | 133ms | 99ms | -34ms | -25.51
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 142ms | 110ms | -32ms | -22.50
| JobStore.Save | p99 | 85ms | 66ms | -19ms | -22.49
| UserStore.GetAllProfiles | p99 | 138ms | 107ms | -31ms | -22.48
| TeamStore.GetByName | p99 | 147ms | 115ms | -32ms | -21.75
| UserStore.GetProfileByIds | p99 | 158ms | 126ms | -32ms | -20.20
| ThreadStore.MaintainMembership | p99 | 177ms | 142ms | -35ms | -19.82
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 71ms | 58ms | -13ms | -18.35
| TeamStore.Get | p99 | 144ms | 119ms | -25ms | -17.32
| SessionStore.Save | p99 | 164ms | 136ms | -28ms | -17.04
| ThreadStore.Get | p99 | 167ms | 139ms | -28ms | -16.79
| PluginStore.List | p99 | 210ms | 175ms | -35ms | -16.71
| PostStore.GetSingle | p99 | 151ms | 126ms | -25ms | -16.60
| ThreadStore.UpdateMembership | p99 | 80ms | 67ms | -13ms | -16.27
| SessionStore.UpdateLastActivityAt | p99 | 70ms | 59ms | -11ms | -15.77
| UserStore.GetUnreadCount | p99 | 395ms | 334ms | -61ms | -15.46
| PostStore.GetPostIdAfterTime | p99 | 61ms | 52ms | -9ms | -14.72
| LinkMetadataStore.Get | p99 | 163ms | 139ms | -24ms | -14.70
| FileInfoStore.GetForPost | p99 | 172ms | 147ms | -25ms | -14.52
| JobStore.GetCountByStatusAndType | p99 | 173ms | 148ms | -25ms | -14.47
| TeamStore.GetMember | p99 | 23ms | 20ms | -3ms | -13.02
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 148ms | 129ms | -19ms | -12.85
| ThreadStore.GetMembershipForUser | p99 | 175ms | 153ms | -22ms | -12.57
| ChannelStore.GetMember | p99 | 50ms | 44ms | -6ms | -11.99
| ChannelStore.GetMembers | p99 | 905ms | 797ms | -108ms | -11.93
| SystemStore.GetByName | p99 | 60ms | 53ms | -7ms | -11.72
| ChannelStore.Save | p99 | 248ms | 219ms | -29ms | -11.71
| PostStore.GetPostIdBeforeTime | p99 | 80ms | 71ms | -9ms | -11.19
| PostStore.GetPostsByThread | p99 | 170ms | 151ms | -19ms | -11.15
| ThreadStore.MarkAsRead | p99 | 72ms | 64ms | -8ms | -11.12
| JobStore.GetAllByStatus | p99 | 214ms | 191ms | -23ms | -10.74
| StatusStore.UpdateLastActivityAt | p99 | 88ms | 79ms | -9ms | -10.28
| StatusStore.UpdateExpiredDNDStatuses | p99 | 98ms | 88ms | -10ms | -10.25
| ChannelStore.SearchGroupChannels | p99 | 203ms | 183ms | -20ms | -9.83
| PreferenceStore.Get | p99 | 174ms | 157ms | -17ms | -9.78
| PostStore.GetPostReminderMetadata | p99 | 215ms | 194ms | -21ms | -9.74
| PostStore.Get | p99 | 264ms | 239ms | -25ms | -9.48
| ChannelStore.GetAllChannelMembersForUser | p99 | 58ms | 53ms | -5ms | -8.55
| ReactionStore.Save | p99 | 226ms | 207ms | -19ms | -8.39
| UserStore.GetProfilesByUsernames | p99 | 168ms | 154ms | -14ms | -8.34
| ThreadStore.MarkAllAsReadByChannels | p99 | 73ms | 67ms | -6ms | -8.27
| PluginStore.SetWithOptions | p99 | 89ms | 82ms | -7ms | -7.86
| ChannelStore.GetMembersForUser | p99 | 188ms | 174ms | -14ms | -7.45
| PluginStore.Delete | p99 | 43ms | 40ms | -3ms | -7.03
| UserStore.Search | p99 | 801ms | 746ms | -55ms | -6.87
| ChannelStore.GetChannels | p99 | 194ms | 181ms | -13ms | -6.71
| ThreadStore.GetThreadUnreadReplyCount | p99 | 196ms | 183ms | -13ms | -6.62
| PostAcknowledgementStore.GetForPosts | p99 | 207ms | 194ms | -13ms | -6.27
| PostStore.GetPostsBefore | p99 | 192ms | 180ms | -12ms | -6.26
| ChannelStore.GetPinnedPostCount | p99 | 193ms | 181ms | -12ms | -6.22
| WebhookStore.GetOutgoingByTeam | p99 | 190ms | 179ms | -11ms | -5.78
| FileInfoStore.Get | p99 | 146ms | 138ms | -8ms | -5.48
| UserStore.Update | p99 | 202ms | 191ms | -11ms | -5.45
| AuditStore.Save | p99 | 74ms | 70ms | -4ms | -5.42
| ChannelStore.Autocomplete | p99 | 838ms | 793ms | -45ms | -5.37
| FileInfoStore.Save | p99 | 94ms | 89ms | -5ms | -5.33
| UserStore.UpdateFailedPasswordAttempts | p99 | 76ms | 72ms | -4ms | -5.25
| PostPriorityStore.GetForPosts | p99 | 214ms | 203ms | -11ms | -5.14
| PostPersistentNotificationStore.GetSingle | p99 | 179ms | 170ms | -9ms | -5.02
| ChannelStore.IncrementMentionCount | p99 | 82ms | 78ms | -4ms | -4.89
| PostStore.Save | p99 | 227ms | 216ms | -11ms | -4.85
| ThreadStore.GetThreadForUser | p99 | 220ms | 210ms | -10ms | -4.55
| GroupStore.GetGroups | p99 | 185ms | 177ms | -8ms | -4.33
| ThreadStore.GetThreadFollowers | p99 | 189ms | 182ms | -7ms | -3.70
| ChannelStore.GetChannelUnread | p99 | 91ms | 88ms | -3ms | -3.31
| ChannelStore.Get | p99 | 232ms | 225ms | -7ms | -3.02
| PreferenceStore.Save | p99 | 193ms | 188ms | -5ms | -2.60
| PostStore.GetPostsSince | p99 | 234ms | 228ms | -6ms | -2.56
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 239ms | 233ms | -6ms | -2.52
| ThreadStore.GetThreadsForUser | p99 | 203ms | 198ms | -5ms | -2.46
| TeamStore.GetAllPage | p99 | 166ms | 162ms | -4ms | -2.41
| PostStore.GetEtag | p99 | 211ms | 206ms | -5ms | -2.36
| PreferenceStore.DeleteCategoryAndName | p99 | 224ms | 219ms | -5ms | -2.23
| LinkMetadataStore.Save | p99 | 92ms | 90ms | -2ms | -2.18
| TeamStore.GetTeamsForUser | p99 | 98ms | 96ms | -2ms | -2.05
| GroupStore.GetByName | p99 | 99ms | 97ms | -2ms | -2.02
| UserStore.GetForLogin | p99 | 99ms | 97ms | -2ms | -2.01
| UserTermsOfServiceStore.GetByUser | p99 | 150ms | 148ms | -2ms | -1.33
| PreferenceStore.GetAll | p99 | 186ms | 184ms | -2ms | -1.07
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 0s | 2ms | 2ms | 1253.11
| getRolesByNames | avg | 1ms | 4ms | 3ms | 371.46
| createCategoryForTeamForUser | avg | 50ms | 149ms | 99ms | 199.78
| updateReadStateAllThreadsByUser | avg | 3ms | 7ms | 4ms | 125.73
| setPostReminder | avg | 41ms | 84ms | 43ms | 106.11
| updateCategoriesForTeamForUser | avg | 107ms | 165ms | 58ms | 54.35
| patchPost | avg | 258ms | 324ms | 66ms | 25.63
| autocompleteChannelsForTeamForSearch | avg | 243ms | 269ms | 26ms | 10.69
| createChannel | avg | 46ms | 50ms | 4ms | 8.63
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 25ms | 20ms | 404.04
| patchPost | p99 | 2.072s | 10s | 7.928s | 382.55
| createCategoryForTeamForUser | p99 | 246ms | 980ms | 734ms | 298.98
| updateCategoriesForTeamForUser | p99 | 885ms | 1.885s | 1s | 113.00
| root | p99 | 5ms | 10ms | 5ms | 101.01
| setPostReminder | p99 | 238ms | 475ms | 237ms | 99.37
| createPost | p99 | 5.268s | 7.133s | 1.865s | 35.40
| getChannelStats | p99 | 571ms | 686ms | 115ms | 20.13
| getChannelsForUser | p99 | 156ms | 173ms | 17ms | 10.90
| createUser | p99 | 575ms | 628ms | 53ms | 9.22
| createChannel | p99 | 224ms | 240ms | 16ms | 7.13
| searchPostsInTeam | p99 | 3.025s | 3.233s | 208ms | 6.88
| autocompleteChannelsForTeamForSearch | p99 | 2.293s | 2.413s | 120ms | 5.23
| getTeamMember | p99 | 85ms | 88ms | 3ms | 3.55
| getTeamsForUser | p99 | 173ms | 179ms | 6ms | 3.46
| saveReaction | p99 | 536ms | 553ms | 17ms | 3.17
| addTeamMember | p99 | 8.878s | 9.142s | 264ms | 2.97
| getChannelMember | p99 | 235ms | 240ms | 5ms | 2.13
| uploadFileStream | p99 | 2.173s | 2.213s | 40ms | 1.84
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroups | avg | 6ms | 0s | -6ms | -109.03
| updateViewedProductNotices | avg | 8ms | 0s | -8ms | -103.25
| channelMemberCountsByGroup | avg | 17ms | 0s | -17ms | -101.32
| getFilteredUsersStats | avg | 110ms | 0s | -110ms | -100.28
| getLicenseSelfServeStatus | avg | 159ms | 0s | -159ms | -100.23
| queryLogs | avg | 145ms | 0s | -145ms | -100.14
| getAnalytics | avg | 393ms | 0s | -393ms | -99.94
| patchUser | avg | 114ms | 0s | -114ms | -99.86
| getDrafts | avg | 11ms | 0s | -11ms | -99.50
| getSelfHostedProducts | avg | 18ms | 0s | -18ms | -99.08
| handleCheckCWSConnection | avg | 40ms | 0s | -40ms | -99.02
| getProductNotices | avg | 23ms | 0s | -23ms | -97.88
| getPrevTrialLicense | avg | 4ms | 0s | -4ms | -97.70
| deleteDraft | avg | 53ms | 2ms | -51ms | -96.01
| searchFiles | avg | 299ms | 16ms | -283ms | -94.71
| getJobsByType | avg | 4ms | 0s | -4ms | -93.24
| upsertDraft | avg | 38ms | 5ms | -33ms | -86.17
| followThreadByUser | avg | 75ms | 26ms | -49ms | -65.26
| getChannelMembersForUser | avg | 53ms | 36ms | -17ms | -32.11
| updatePreferences | avg | 23ms | 17ms | -6ms | -25.68
| deletePost | avg | 99ms | 74ms | -25ms | -25.37
| addChannelMember | avg | 434ms | 349ms | -85ms | -19.59
| searchGroupChannels | avg | 15ms | 12ms | -3ms | -19.51
| createGroupChannel | avg | 631ms | 509ms | -122ms | -19.33
| getUsersByNames | avg | 11ms | 9ms | -2ms | -18.57
| updateReadStateThreadByUser | avg | 100ms | 82ms | -18ms | -17.96
| getChannelMembersForTeamForUser | avg | 12ms | 10ms | -2ms | -17.27
| getPostThread | avg | 59ms | 49ms | -10ms | -16.97
| getPublicChannelsForTeam | avg | 24ms | 20ms | -4ms | -16.36
| unfollowThreadByUser | avg | 43ms | 36ms | -7ms | -16.31
| getChannelsForTeamForUser | avg | 13ms | 11ms | -2ms | -15.95
| getChannel | avg | 26ms | 22ms | -4ms | -15.68
| getThreadsForUser | avg | 14ms | 12ms | -2ms | -14.80
| viewChannel | avg | 35ms | 30ms | -5ms | -14.14
| updateUserCustomStatus | avg | 300ms | 270ms | -30ms | -9.99
| searchAllChannels | avg | 101ms | 91ms | -10ms | -9.90
| createDirectChannel | avg | 366ms | 330ms | -36ms | -9.84
| saveReaction | avg | 53ms | 48ms | -5ms | -9.38
| searchUsers | avg | 77ms | 70ms | -7ms | -9.06
| getPostsForChannel | avg | 101ms | 92ms | -9ms | -8.89
| searchPostsInTeam | avg | 161ms | 147ms | -14ms | -8.67
| getPostsForChannelAroundLastUnread | avg | 59ms | 54ms | -5ms | -8.54
| createPost | avg | 1.065s | 975ms | -90ms | -8.45
| login | avg | 147ms | 135ms | -12ms | -8.16
| autocompleteUsers | avg | 214ms | 200ms | -14ms | -6.54
| getFilePreview | avg | 64ms | 60ms | -4ms | -6.24
| getFileThumbnail | avg | 52ms | 49ms | -3ms | -5.77
| getProfileImage | avg | 105ms | 103ms | -2ms | -1.90
| logout | avg | 120ms | 118ms | -2ms | -1.67
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | p99 | 24ms | 0s | -24ms | -102.12
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -100.90
| getSelfHostedProducts | p99 | 50ms | 0s | -50ms | -100.84
| handleCheckCWSConnection | p99 | 50ms | 0s | -50ms | -100.50
| updateViewedProductNotices | p99 | 10ms | 0s | -10ms | -100.42
| queryLogs | p99 | 249ms | 0s | -249ms | -100.20
| patchUser | p99 | 249ms | 0s | -249ms | -100.10
| getProductNotices | p99 | 98ms | 0s | -98ms | -100.00
| getAnalytics | p99 | 979ms | 0s | -979ms | -99.99
| getLicenseSelfServeStatus | p99 | 935ms | 0s | -935ms | -99.98
| channelMemberCountsByGroup | p99 | 95ms | 0s | -95ms | -99.95
| getFilteredUsersStats | p99 | 247ms | 0s | -247ms | -99.90
| getDrafts | p99 | 49ms | 0s | -49ms | -99.67
| getPrevTrialLicense | p99 | 23ms | 0s | -23ms | -98.85
| getGroups | p99 | 24ms | 0s | -24ms | -98.47
| deleteDraft | p99 | 244ms | 10ms | -234ms | -95.90
| searchFiles | p99 | 497ms | 48ms | -449ms | -90.25
| upsertDraft | p99 | 99ms | 10ms | -89ms | -89.90
| getChannelMembersForUser | p99 | 468ms | 50ms | -418ms | -89.36
| getPublicChannelsForTeam | p99 | 212ms | 100ms | -112ms | -52.78
| deletePost | p99 | 915ms | 474ms | -441ms | -48.20
| logout | p99 | 870ms | 479ms | -391ms | -44.94
| getUserStatusesByIds | p99 | 16ms | 10ms | -6ms | -38.69
| getUsersByIds | p99 | 36ms | 28ms | -8ms | -22.14
| addChannelMember | p99 | 2.892s | 2.288s | -604ms | -20.89
| unfollowThreadByUser | p99 | 535ms | 424ms | -111ms | -20.75
| updateReadStateThreadByUser | p99 | 1.183s | 952ms | -231ms | -19.53
| createDirectChannel | p99 | 2.082s | 1.771s | -311ms | -14.94
| updatePreferences | p99 | 241ms | 217ms | -24ms | -9.95
| searchGroupChannels | p99 | 203ms | 183ms | -20ms | -9.83
| followThreadByUser | p99 | 480ms | 437ms | -43ms | -8.96
| getPostThread | p99 | 860ms | 791ms | -69ms | -8.02
| getUsersByNames | p99 | 172ms | 159ms | -13ms | -7.55
| createGroupChannel | p99 | 2.413s | 2.239s | -174ms | -7.21
| viewChannel | p99 | 414ms | 385ms | -29ms | -7.01
| login | p99 | 953ms | 898ms | -55ms | -5.77
| getChannelMembersForTeamForUser | p99 | 191ms | 181ms | -10ms | -5.24
| searchUsers | p99 | 799ms | 760ms | -39ms | -4.88
| removeUserCustomStatus | p99 | 990ms | 945ms | -45ms | -4.55
| updateUserCustomStatus | p99 | 969ms | 926ms | -43ms | -4.44
| getPostsForChannelAroundLastUnread | p99 | 881ms | 842ms | -39ms | -4.43
| getFilePreview | p99 | 389ms | 372ms | -17ms | -4.37
| searchAllChannels | p99 | 838ms | 804ms | -34ms | -4.06
| getFileThumbnail | p99 | 352ms | 338ms | -14ms | -3.98
| getUsers | p99 | 214ms | 207ms | -7ms | -3.27
| getChannelUnread | p99 | 97ms | 94ms | -3ms | -3.09
| getChannelsForTeamForUser | p99 | 198ms | 192ms | -6ms | -3.03
| getPostsForChannel | p99 | 1.598s | 1.55s | -48ms | -3.00
| getClientConfig | p99 | 194ms | 191ms | -3ms | -1.54
| getThreadsForUser | p99 | 206ms | 203ms | -3ms | -1.45
| autocompleteUsers | p99 | 962ms | 952ms | -10ms | -1.04
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 6ms | -1ms | -14.868
| |  P99| 74ms| 70ms | -4ms | -5.416
| BotStore.Get |  Avg| 8ms| 5ms | -3ms | -38.596
| |  P99| 87ms| 88ms | 1ms | 1.156
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 149ms| 0s | -149ms | -99.967
| |  P99| 965ms| 0s | -965ms | -100.041
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 62ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 127ms| 0s | -127ms | -99.936
| |  P99| 248ms| 0s | -248ms | -99.912
| ChannelStore.Autocomplete |  Avg| 101ms| 90ms | -11ms | -10.940
| |  P99| 838ms| 793ms | -45ms | -5.371
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 243ms| 268ms | 25ms | 10.280
| |  P99| 2.293s| 2.413s | 120ms | 5.232
| ChannelStore.CreateDirectChannel |  Avg| 52ms| 45ms | -7ms | -13.484
| |  P99| 476ms| 565ms | 89ms | 18.688
| ChannelStore.CreateInitialSidebarCategories |  Avg| 30ms| 31ms | 1ms | 3.360
| |  P99| 351ms| 389ms | 38ms | 10.815
| ChannelStore.CreateSidebarCategory |  Avg| 43ms| 108ms | 65ms | 152.500
| |  P99| 246ms| 490ms | 244ms | 99.389
| ChannelStore.Get |  Avg| 16ms| 15ms | -1ms | -6.299
| |  P99| 232ms| 225ms | -7ms | -3.020
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 58ms| 53ms | -5ms | -8.549
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 40ms| 38ms | -2ms | -5.040
| |  P99| 239ms| 233ms | -6ms | -2.516
| ChannelStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 171ms| 173ms | 2ms | 1.166
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 1ms | -1ms | -44.283
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 7ms| 6ms | -1ms | -14.380
| |  P99| 91ms| 88ms | -3ms | -3.309
| ChannelStore.GetChannels |  Avg| 12ms| 11ms | -1ms | -8.213
| |  P99| 194ms| 181ms | -13ms | -6.710
| ChannelStore.GetChannelsByUser |  Avg| 10ms| 9ms | -1ms | -9.799
| |  P99| 151ms| 169ms | 18ms | 11.958
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 7ms | -2ms | -23.114
| |  P99| 148ms| 129ms | -19ms | -12.853
| ChannelStore.GetFileCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 134ms| 149ms | 15ms | 11.194
| ChannelStore.GetGuestCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 225ms| 228ms | 3ms | 1.334
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 50ms| 44ms | -6ms | -11.991
| ChannelStore.GetMemberCount |  Avg| 187ms| 193ms | 6ms | 3.203
| |  P99| 913ms| 943ms | 30ms | 3.287
| ChannelStore.GetMemberCountsByGroup |  Avg| 16ms| 0s | -16ms | -102.945
| |  P99| 95ms| 0s | -95ms | -99.950
| ChannelStore.GetMemberForPost |  Avg| 8ms| 7ms | -1ms | -13.044
| |  P99| 113ms| 114ms | 1ms | 0.883
| ChannelStore.GetMembers |  Avg| 189ms| 185ms | -4ms | -2.113
| |  P99| 905ms| 797ms | -108ms | -11.934
| ChannelStore.GetMembersForUser |  Avg| 11ms| 10ms | -1ms | -8.860
| |  P99| 188ms| 174ms | -14ms | -7.451
| ChannelStore.GetMembersForUserWithPagination |  Avg| 77ms| 38ms | -39ms | -50.492
| |  P99| 451ms| 99ms | -352ms | -78.027
| ChannelStore.GetPinnedPostCount |  Avg| 11ms| 9ms | -2ms | -18.794
| |  P99| 193ms| 181ms | -12ms | -6.221
| ChannelStore.GetPublicChannelsForTeam |  Avg| 23ms| 18ms | -5ms | -21.949
| |  P99| 208ms| 100ms | -108ms | -51.917
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 22ms| 21ms | -1ms | -4.570
| |  P99| 343ms| 343ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 21ms| 19ms | -2ms | -9.695
| |  P99| 225ms| 315ms | 90ms | 39.929
| ChannelStore.GetTeamChannels |  Avg| 46ms| 50ms | 4ms | 8.670
| |  P99| 224ms| 240ms | 16ms | 7.127
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 5ms | -1ms | -17.835
| |  P99| 82ms| 78ms | -4ms | -4.893
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 22ms| 23ms | 1ms | 4.561
| |  P99| 248ms| 219ms | -29ms | -11.706
| ChannelStore.SaveMember |  Avg| 59ms| 60ms | 1ms | 1.688
| |  P99| 662ms| 667ms | 5ms | 0.755
| ChannelStore.SearchGroupChannels |  Avg| 15ms| 11ms | -4ms | -26.160
| |  P99| 203ms| 183ms | -20ms | -9.831
| ChannelStore.UpdateLastViewedAt |  Avg| 12ms| 10ms | -2ms | -17.057
| |  P99| 133ms| 99ms | -34ms | -25.506
| ChannelStore.UpdateSidebarCategories |  Avg| 58ms| 117ms | 59ms | 101.351
| |  P99| 245ms| 930ms | 685ms | 280.075
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 4ms| 3ms | -1ms | -23.263
| |  P99| 71ms| 58ms | -13ms | -18.346
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 9ms | -1ms | -9.854
| |  P99| 89ms| 128ms | 39ms | 43.775
| CommandWebhookStore.Cleanup |  Avg| 11ms| 4ms | -7ms | -63.457
| |  P99| 49ms| 24ms | -25ms | -51.020
| ComplianceStore.MessageExport |  Avg| 11ms| 0s | -11ms | -100.759
| |  P99| 99ms| 0s | -99ms | -99.831
| DraftStore.Get |  Avg| 61ms| 1ms | -60ms | -97.816
| |  P99| 246ms| 5ms | -241ms | -98.167
| DraftStore.GetDraftsForUser |  Avg| 4ms| 0s | -4ms | -97.401
| |  P99| 24ms| 0s | -24ms | -97.964
| DraftStore.Upsert |  Avg| 35ms| 4ms | -31ms | -88.539
| |  P99| 99ms| 10ms | -89ms | -89.899
| FileInfoStore.AttachToPost |  Avg| 10ms| 9ms | -1ms | -10.182
| |  P99| 92ms| 94ms | 2ms | 2.164
| FileInfoStore.Get |  Avg| 9ms| 8ms | -1ms | -11.012
| |  P99| 146ms| 138ms | -8ms | -5.485
| FileInfoStore.GetForPost |  Avg| 10ms| 8ms | -2ms | -21.015
| |  P99| 172ms| 147ms | -25ms | -14.520
| FileInfoStore.Save |  Avg| 10ms| 9ms | -1ms | -9.691
| |  P99| 94ms| 89ms | -5ms | -5.327
| FileInfoStore.Search |  Avg| 49ms| 10ms | -39ms | -80.345
| |  P99| 50ms| 25ms | -25ms | -50.181
| FileInfoStore.SetContent |  Avg| 15ms| 13ms | -2ms | -13.559
| |  P99| 144ms| 171ms | 27ms | 18.742
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 166ms| 166ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 99ms| 97ms | -2ms | -2.020
| GroupStore.GetGroups |  Avg| 10ms| 9ms | -1ms | -10.298
| |  P99| 185ms| 177ms | -8ms | -4.328
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 0s | -1ms | -79.012
| |  P99| 5ms| 0s | -5ms | -100.898
| JobStore.Get |  Avg| 10ms| 9ms | -1ms | -10.407
| |  P99| 172ms| 200ms | 28ms | 16.289
| JobStore.GetAllByStatus |  Avg| 14ms| 11ms | -3ms | -22.082
| |  P99| 214ms| 191ms | -23ms | -10.737
| JobStore.GetAllByTypePage |  Avg| 4ms| 0s | -4ms | -97.301
| |  P99| 24ms| 0s | -24ms | -102.123
| JobStore.GetCountByStatusAndType |  Avg| 10ms| 8ms | -2ms | -19.659
| |  P99| 173ms| 148ms | -25ms | -14.472
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 7ms | -1ms | -13.011
| |  P99| 86ms| 86ms | 0s | 0.000
| JobStore.Save |  Avg| 9ms| 6ms | -3ms | -33.398
| |  P99| 85ms| 66ms | -19ms | -22.485
| JobStore.UpdateOptimistically |  Avg| 8ms| 4ms | -4ms | -49.048
| |  P99| 81ms| 22ms | -59ms | -73.223
| JobStore.UpdateStatus |  Avg| 7ms| 4ms | -3ms | -40.187
| |  P99| 47ms| 22ms | -25ms | -53.080
| JobStore.UpdateStatusOptimistically |  Avg| 10ms| 7ms | -3ms | -30.919
| |  P99| 161ms| 46ms | -115ms | -71.227
| LicenseStore.GetAll |  Avg| 4ms| 0s | -4ms | -113.936
| |  P99| 23ms| 0s | -23ms | -98.848
| LinkMetadataStore.Get |  Avg| 9ms| 8ms | -1ms | -11.064
| |  P99| 163ms| 139ms | -24ms | -14.700
| LinkMetadataStore.Save |  Avg| 10ms| 8ms | -2ms | -19.617
| |  P99| 92ms| 90ms | -2ms | -2.177
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 40ms | -3ms | -7.026
| PluginStore.Get |  Avg| 63ms| 1ms | -62ms | -98.521
| |  P99| 470ms| 5ms | -465ms | -98.936
| PluginStore.List |  Avg| 12ms| 9ms | -3ms | -24.566
| |  P99| 210ms| 175ms | -35ms | -16.706
| PluginStore.SetWithOptions |  Avg| 8ms| 7ms | -1ms | -12.624
| |  P99| 89ms| 82ms | -7ms | -7.859
| PostAcknowledgementStore.GetForPost |  Avg| 6ms| 7ms | 1ms | 17.184
| |  P99| 87ms| 96ms | 9ms | 10.311
| PostAcknowledgementStore.GetForPosts |  Avg| 12ms| 10ms | -2ms | -17.339
| |  P99| 207ms| 194ms | -13ms | -6.272
| PostPersistentNotificationStore.DeleteExpired |  Avg| 6ms| 2ms | -4ms | -64.102
| |  P99| 81ms| 23ms | -58ms | -71.173
| PostPersistentNotificationStore.Get |  Avg| 8ms| 2ms | -6ms | -74.047
| |  P99| 91ms| 22ms | -69ms | -76.037
| PostPersistentNotificationStore.GetSingle |  Avg| 9ms| 8ms | -1ms | -11.570
| |  P99| 179ms| 170ms | -9ms | -5.017
| PostPriorityStore.GetForPost |  Avg| 8ms| 6ms | -2ms | -24.708
| |  P99| 146ms| 80ms | -66ms | -45.283
| PostPriorityStore.GetForPosts |  Avg| 13ms| 11ms | -2ms | -15.985
| |  P99| 214ms| 203ms | -11ms | -5.136
| PostStore.AnalyticsPostCount |  Avg| 2.76s| 4.653s | 1.893s | 68.578
| |  P99| 9.9s| 9.9s | 0s | 0.000
| PostStore.Delete |  Avg| 35ms| 36ms | 1ms | 2.880
| |  P99| 457ms| 234ms | -223ms | -48.744
| PostStore.Get |  Avg| 21ms| 17ms | -4ms | -19.060
| |  P99| 264ms| 239ms | -25ms | -9.481
| PostStore.GetEtag |  Avg| 13ms| 12ms | -1ms | -7.455
| |  P99| 211ms| 206ms | -5ms | -2.365
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 3ms | -1ms | -26.670
| |  P99| 61ms| 52ms | -9ms | -14.723
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 4ms | -1ms | -18.770
| |  P99| 80ms| 71ms | -9ms | -11.185
| PostStore.GetPostReminderMetadata |  Avg| 18ms| 8ms | -10ms | -55.812
| |  P99| 215ms| 194ms | -21ms | -9.745
| PostStore.GetPostReminders |  Avg| 16ms| 15ms | -1ms | -6.067
| |  P99| 94ms| 214ms | 120ms | 127.660
| PostStore.GetPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 133ms| 135ms | 2ms | 1.508
| PostStore.GetPostsAfter |  Avg| 10ms| 7ms | -3ms | -29.353
| |  P99| 146ms| 88ms | -58ms | -39.704
| PostStore.GetPostsBefore |  Avg| 13ms| 11ms | -2ms | -15.579
| |  P99| 192ms| 180ms | -12ms | -6.258
| PostStore.GetPostsByThread |  Avg| 9ms| 8ms | -1ms | -10.780
| |  P99| 170ms| 151ms | -19ms | -11.147
| PostStore.GetPostsSince |  Avg| 27ms| 25ms | -2ms | -7.361
| |  P99| 234ms| 228ms | -6ms | -2.561
| PostStore.GetSingle |  Avg| 8ms| 7ms | -1ms | -12.062
| |  P99| 151ms| 126ms | -25ms | -16.596
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 22ms| 20ms | -2ms | -9.129
| |  P99| 227ms| 216ms | -11ms | -4.849
| PostStore.SearchPostsForUser |  Avg| 128ms| 126ms | -2ms | -1.564
| |  P99| 2.959s| 2.982s | 23ms | 0.777
| PostStore.SetPostReminder |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 216ms| 220ms | 4ms | 1.856
| PostStore.Update |  Avg| 27ms| 23ms | -4ms | -14.660
| |  P99| 220ms| 233ms | 13ms | 5.899
| PreferenceStore.DeleteCategoryAndName |  Avg| 18ms| 16ms | -2ms | -11.145
| |  P99| 224ms| 219ms | -5ms | -2.227
| PreferenceStore.Get |  Avg| 11ms| 9ms | -2ms | -18.922
| |  P99| 174ms| 157ms | -17ms | -9.783
| PreferenceStore.GetAll |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 186ms| 184ms | -2ms | -1.073
| PreferenceStore.Save |  Avg| 15ms| 14ms | -1ms | -6.779
| |  P99| 193ms| 188ms | -5ms | -2.595
| ProductNoticesStore.ClearOldNotices |  Avg| 3ms| 1ms | -2ms | -58.140
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 8ms| 0s | -8ms | -104.607
| |  P99| 24ms| 0s | -24ms | -98.361
| ProductNoticesStore.View |  Avg| 50ms| 51ms | 1ms | 2.001
| |  P99| 467ms| 479ms | 12ms | 2.567
| ReactionStore.GetForPost |  Avg| 11ms| 10ms | -1ms | -8.747
| |  P99| 179ms| 179ms | 0s | 0.000
| ReactionStore.Save |  Avg| 20ms| 16ms | -4ms | -20.229
| |  P99| 226ms| 207ms | -19ms | -8.392
| RoleStore.ChannelHigherScopedPermissions |  Avg| 13ms| 4ms | -9ms | -71.654
| |  P99| 231ms| 35ms | -196ms | -84.812
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -118.368
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 10ms| 14ms | 4ms | 39.504
| |  P99| 155ms| 211ms | 56ms | 36.025
| SessionStore.GetSessionsExpired |  Avg| 4ms| 6ms | 2ms | 46.297
| |  P99| 24ms| 24ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 6ms | -2ms | -24.008
| |  P99| 142ms| 110ms | -32ms | -22.497
| SessionStore.Remove |  Avg| 6ms| 9ms | 3ms | 54.485
| |  P99| 44ms| 48ms | 4ms | 9.143
| SessionStore.Save |  Avg| 12ms| 11ms | -1ms | -8.270
| |  P99| 164ms| 136ms | -28ms | -17.041
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 6ms | -1ms | -14.216
| |  P99| 70ms| 59ms | -11ms | -15.766
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 93ms| 96ms | 3ms | 3.234
| StatusStore.GetByIds |  Avg| 10ms| 9ms | -1ms | -10.346
| |  P99| 112ms| 129ms | 17ms | 15.148
| StatusStore.SaveOrUpdate |  Avg| 41ms| 63ms | 22ms | 53.246
| |  P99| 835ms| 895ms | 60ms | 7.183
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 22ms| 11ms | -11ms | -50.410
| |  P99| 98ms| 88ms | -10ms | -10.246
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 7ms | -1ms | -12.385
| |  P99| 88ms| 79ms | -9ms | -10.285
| SystemStore.GetByName |  Avg| 4ms| 3ms | -1ms | -27.935
| |  P99| 60ms| 53ms | -7ms | -11.724
| TeamStore.AnalyticsTeamCount |  Avg| 16ms| 0s | -16ms | -102.411
| |  P99| 96ms| 0s | -96ms | -99.489
| TeamStore.Get |  Avg| 8ms| 7ms | -1ms | -13.120
| |  P99| 144ms| 119ms | -25ms | -17.322
| TeamStore.GetAllPage |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 166ms| 162ms | -4ms | -2.407
| TeamStore.GetByName |  Avg| 7ms| 5ms | -2ms | -27.981
| |  P99| 147ms| 115ms | -32ms | -21.754
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 155ms| 158ms | 3ms | 1.934
| TeamStore.GetMember |  Avg| 2ms| 1ms | -1ms | -66.264
| |  P99| 23ms| 20ms | -3ms | -13.020
| TeamStore.GetTeamsByUserId |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 172ms| 177ms | 5ms | 2.909
| TeamStore.GetTeamsForUser |  Avg| 7ms| 6ms | -1ms | -14.738
| |  P99| 98ms| 96ms | -2ms | -2.046
| TeamStore.SaveMember |  Avg| 86ms| 86ms | 0s | 0.000
| |  P99| 353ms| 368ms | 15ms | 4.249
| ThreadStore.Get |  Avg| 10ms| 7ms | -3ms | -29.193
| |  P99| 167ms| 139ms | -28ms | -16.791
| ThreadStore.GetMembershipForUser |  Avg| 10ms| 8ms | -2ms | -20.318
| |  P99| 175ms| 153ms | -22ms | -12.570
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 10ms | -1ms | -9.355
| |  P99| 181ms| 180ms | -1ms | -0.553
| ThreadStore.GetThreadFollowers |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 189ms| 182ms | -7ms | -3.704
| ThreadStore.GetThreadForUser |  Avg| 14ms| 12ms | -2ms | -14.761
| |  P99| 220ms| 210ms | -10ms | -4.549
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 11ms| 9ms | -2ms | -18.319
| |  P99| 196ms| 183ms | -13ms | -6.623
| ThreadStore.GetThreadsForUser |  Avg| 14ms| 12ms | -2ms | -14.757
| |  P99| 203ms| 198ms | -5ms | -2.458
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 153ms| 162ms | 9ms | 5.893
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 152ms| 154ms | 2ms | 1.317
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 150ms| 163ms | 13ms | 8.691
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 9ms| 8ms | -1ms | -11.626
| |  P99| 148ms| 159ms | 11ms | 7.432
| ThreadStore.MaintainMembership |  Avg| 12ms| 10ms | -2ms | -17.018
| |  P99| 177ms| 142ms | -35ms | -19.816
| ThreadStore.MarkAllAsReadByChannels |  Avg| 6ms| 5ms | -1ms | -16.826
| |  P99| 73ms| 67ms | -6ms | -8.269
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 7ms | 4ms | 130.322
| |  P99| 5ms| 25ms | 20ms | 404.040
| ThreadStore.MarkAsRead |  Avg| 7ms| 6ms | -1ms | -13.645
| |  P99| 72ms| 64ms | -8ms | -11.118
| ThreadStore.UpdateMembership |  Avg| 7ms| 6ms | -1ms | -13.549
| |  P99| 80ms| 67ms | -13ms | -16.269
| TokenStore.Cleanup |  Avg| 5ms| 3ms | -2ms | -44.284
| |  P99| 10ms| 24ms | 14ms | 141.414
| UserAccessTokenStore.GetByToken |  Avg| 9ms| 2ms | -7ms | -79.916
| |  P99| 94ms| 22ms | -72ms | -76.392
| UserStore.AnalyticsActiveCount |  Avg| 337ms| 0s | -337ms | -100.110
| |  P99| 941ms| 0s | -941ms | -100.008
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 0s | -2ms | -115.334
| |  P99| 10ms| 0s | -10ms | -102.750
| UserStore.AutocompleteUsersInChannel |  Avg| 275ms| 255ms | -20ms | -7.271
| |  P99| 972ms| 967ms | -5ms | -0.515
| UserStore.Count |  Avg| 184ms| 132ms | -52ms | -28.253
| |  P99| 755ms| 476ms | -279ms | -36.954
| UserStore.Get |  Avg| 5ms| 4ms | -1ms | -21.513
| |  P99| 84ms| 84ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 10ms| 9ms | -1ms | -10.455
| |  P99| 138ms| 107ms | -31ms | -22.477
| UserStore.GetAllProfilesInChannel |  Avg| 739ms| 708ms | -31ms | -4.197
| |  P99| 2.457s| 2.448s | -9ms | -0.366
| UserStore.GetByUsername |  Avg| 12ms| 6ms | -6ms | -51.659
| |  P99| 192ms| 88ms | -104ms | -54.096
| UserStore.GetForLogin |  Avg| 7ms| 6ms | -1ms | -14.583
| |  P99| 99ms| 97ms | -2ms | -2.011
| UserStore.GetMany |  Avg| 8ms| 2ms | -6ms | -71.238
| |  P99| 220ms| 21ms | -199ms | -90.456
| UserStore.GetProfileByIds |  Avg| 10ms| 9ms | -1ms | -10.238
| |  P99| 158ms| 126ms | -32ms | -20.196
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 9ms | -1ms | -9.609
| |  P99| 168ms| 154ms | -14ms | -8.344
| UserStore.GetProfilesInChannel |  Avg| 15ms| 7ms | -8ms | -54.511
| |  P99| 148ms| 65ms | -83ms | -56.078
| UserStore.GetUnreadCount |  Avg| 16ms| 14ms | -2ms | -12.449
| |  P99| 395ms| 334ms | -61ms | -15.461
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 53ms| 56ms | 3ms | 5.637
| UserStore.Save |  Avg| 81ms| 80ms | -1ms | -1.237
| |  P99| 258ms| 259ms | 1ms | 0.388
| UserStore.Search |  Avg| 76ms| 67ms | -9ms | -11.871
| |  P99| 801ms| 746ms | -55ms | -6.867
| UserStore.Update |  Avg| 16ms| 14ms | -2ms | -12.793
| |  P99| 202ms| 191ms | -11ms | -5.446
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 72ms | -4ms | -5.251
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 70ms | 8ms | 12.923
| UserTermsOfServiceStore.GetByUser |  Avg| 8ms| 7ms | -1ms | -13.013
| |  P99| 150ms| 148ms | -2ms | -1.330
| WebhookStore.GetOutgoingByTeam |  Avg| 15ms| 14ms | -1ms | -6.615
| |  P99| 190ms| 179ms | -11ms | -5.779
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 434ms| 349ms | -85ms | -19.592
| | P99| 2.892s| 2.288s | -604ms | -20.888
| addTeamMember | Avg| 1.687s| 1.69s | 3ms | 0.178
| | P99| 8.878s| 9.142s | 264ms | 2.974
| autocompleteChannelsForTeamForSearch | Avg| 243ms| 269ms | 26ms | 10.688
| | P99| 2.293s| 2.413s | 120ms | 5.232
| autocompleteUsers | Avg| 214ms| 200ms | -14ms | -6.544
| | P99| 962ms| 952ms | -10ms | -1.040
| channelMemberCountsByGroup | Avg| 17ms| 0s | -17ms | -101.324
| | P99| 95ms| 0s | -95ms | -99.950
| createCategoryForTeamForUser | Avg| 50ms| 149ms | 99ms | 199.785
| | P99| 246ms| 980ms | 734ms | 298.982
| createChannel | Avg| 46ms| 50ms | 4ms | 8.625
| | P99| 224ms| 240ms | 16ms | 7.127
| createDirectChannel | Avg| 366ms| 330ms | -36ms | -9.840
| | P99| 2.082s| 1.771s | -311ms | -14.940
| createGroupChannel | Avg| 631ms| 509ms | -122ms | -19.328
| | P99| 2.413s| 2.239s | -174ms | -7.210
| createPost | Avg| 1.065s| 975ms | -90ms | -8.448
| | P99| 5.268s| 7.133s | 1.865s | 35.404
| createUser | Avg| 131ms| 131ms | 0s | 0.000
| | P99| 575ms| 628ms | 53ms | 9.225
| deleteDraft | Avg| 53ms| 2ms | -51ms | -96.010
| | P99| 244ms| 10ms | -234ms | -95.902
| deletePost | Avg| 99ms| 74ms | -25ms | -25.374
| | P99| 915ms| 474ms | -441ms | -48.197
| followThreadByUser | Avg| 75ms| 26ms | -49ms | -65.261
| | P99| 480ms| 437ms | -43ms | -8.958
| getAllTeams | Avg| 10ms| 9ms | -1ms | -10.452
| | P99| 182ms| 182ms | 0s | 0.000
| getAnalytics | Avg| 393ms| 0s | -393ms | -99.936
| | P99| 979ms| 0s | -979ms | -99.987
| getCategoriesForTeamForUser | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 346ms| 345ms | -1ms | -0.289
| getChannel | Avg| 26ms| 22ms | -4ms | -15.685
| | P99| 431ms| 429ms | -2ms | -0.465
| getChannelMember | Avg| 18ms| 17ms | -1ms | -5.673
| | P99| 235ms| 240ms | 5ms | 2.126
| getChannelMembersForTeamForUser | Avg| 12ms| 10ms | -2ms | -17.273
| | P99| 191ms| 181ms | -10ms | -5.242
| getChannelMembersForUser | Avg| 53ms| 36ms | -17ms | -32.106
| | P99| 468ms| 50ms | -418ms | -89.362
| getChannelStats | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 571ms| 686ms | 115ms | 20.133
| getChannelUnread | Avg| 8ms| 7ms | -1ms | -12.366
| | P99| 97ms| 94ms | -3ms | -3.095
| getChannelsForTeamForUser | Avg| 13ms| 11ms | -2ms | -15.954
| | P99| 198ms| 192ms | -6ms | -3.033
| getChannelsForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 156ms| 173ms | 17ms | 10.896
| getClientConfig | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 194ms| 191ms | -3ms | -1.545
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 11ms| 0s | -11ms | -99.503
| | P99| 49ms| 0s | -49ms | -99.665
| getFilePreview | Avg| 64ms| 60ms | -4ms | -6.236
| | P99| 389ms| 372ms | -17ms | -4.373
| getFileThumbnail | Avg| 52ms| 49ms | -3ms | -5.768
| | P99| 352ms| 338ms | -14ms | -3.978
| getFilteredUsersStats | Avg| 110ms| 0s | -110ms | -100.280
| | P99| 247ms| 0s | -247ms | -99.900
| getGroups | Avg| 6ms| 0s | -6ms | -109.025
| | P99| 24ms| 0s | -24ms | -98.466
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 0s | -1ms | -75.721
| | P99| 5ms| 0s | -5ms | -100.898
| getJobsByType | Avg| 4ms| 0s | -4ms | -93.244
| | P99| 24ms| 0s | -24ms | -102.123
| getLicenseSelfServeStatus | Avg| 159ms| 0s | -159ms | -100.226
| | P99| 935ms| 0s | -935ms | -99.976
| getPostThread | Avg| 59ms| 49ms | -10ms | -16.973
| | P99| 860ms| 791ms | -69ms | -8.019
| getPostsForChannel | Avg| 101ms| 92ms | -9ms | -8.892
| | P99| 1.598s| 1.55s | -48ms | -3.005
| getPostsForChannelAroundLastUnread | Avg| 59ms| 54ms | -5ms | -8.538
| | P99| 881ms| 842ms | -39ms | -4.428
| getPreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 189ms| 190ms | 1ms | 0.529
| getPrevTrialLicense | Avg| 4ms| 0s | -4ms | -97.702
| | P99| 23ms| 0s | -23ms | -98.848
| getProductNotices | Avg| 23ms| 0s | -23ms | -97.879
| | P99| 98ms| 0s | -98ms | -100.000
| getProfileImage | Avg| 105ms| 103ms | -2ms | -1.900
| | P99| 489ms| 491ms | 2ms | 0.409
| getPublicChannelsForTeam | Avg| 24ms| 20ms | -4ms | -16.362
| | P99| 212ms| 100ms | -112ms | -52.780
| getRolesByNames | Avg| 1ms| 4ms | 3ms | 371.459
| | P99| 5ms| 5ms | 0s | 0.000
| getSelfHostedProducts | Avg| 18ms| 0s | -18ms | -99.078
| | P99| 50ms| 0s | -50ms | -100.842
| getTeamMember | Avg| 7ms| 6ms | -1ms | -14.797
| | P99| 85ms| 88ms | 3ms | 3.547
| getTeamMembersForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 130ms| 131ms | 1ms | 0.772
| getTeamsForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 173ms| 179ms | 6ms | 3.458
| getTeamsUnreadForUser | Avg| 15ms| 14ms | -1ms | -6.749
| | P99| 230ms| 231ms | 1ms | 0.434
| getThreadsForUser | Avg| 14ms| 12ms | -2ms | -14.800
| | P99| 206ms| 203ms | -3ms | -1.454
| getUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 226ms| 224ms | -2ms | -0.885
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 16ms| 10ms | -6ms | -38.689
| getUsers | Avg| 15ms| 14ms | -1ms | -6.853
| | P99| 214ms| 207ms | -7ms | -3.270
| getUsersByIds | Avg| 3ms| 2ms | -1ms | -36.128
| | P99| 36ms| 28ms | -8ms | -22.136
| getUsersByNames | Avg| 11ms| 9ms | -2ms | -18.573
| | P99| 172ms| 159ms | -13ms | -7.548
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 40ms| 0s | -40ms | -99.016
| | P99| 50ms| 0s | -50ms | -100.503
| login | Avg| 147ms| 135ms | -12ms | -8.157
| | P99| 953ms| 898ms | -55ms | -5.768
| logout | Avg| 120ms| 118ms | -2ms | -1.672
| | P99| 870ms| 479ms | -391ms | -44.943
| patchPost | Avg| 258ms| 324ms | 66ms | 25.631
| | P99| 2.072s| 10s | 7.928s | 382.551
| patchUser | Avg| 114ms| 0s | -114ms | -99.858
| | P99| 249ms| 0s | -249ms | -100.102
| queryLogs | Avg| 145ms| 0s | -145ms | -100.141
| | P99| 249ms| 0s | -249ms | -100.201
| removeUserCustomStatus | Avg| 255ms| 254ms | -1ms | -0.393
| | P99| 990ms| 945ms | -45ms | -4.545
| root | Avg| 0s| 2ms | 2ms | 1253.105
| | P99| 5ms| 10ms | 5ms | 101.010
| saveReaction | Avg| 53ms| 48ms | -5ms | -9.382
| | P99| 536ms| 553ms | 17ms | 3.173
| searchAllChannels | Avg| 101ms| 91ms | -10ms | -9.899
| | P99| 838ms| 804ms | -34ms | -4.058
| searchFiles | Avg| 299ms| 16ms | -283ms | -94.714
| | P99| 497ms| 48ms | -449ms | -90.251
| searchGroupChannels | Avg| 15ms| 12ms | -3ms | -19.512
| | P99| 203ms| 183ms | -20ms | -9.831
| searchPostsInTeam | Avg| 161ms| 147ms | -14ms | -8.670
| | P99| 3.025s| 3.233s | 208ms | 6.876
| searchUsers | Avg| 77ms| 70ms | -7ms | -9.063
| | P99| 799ms| 760ms | -39ms | -4.879
| setPostReminder | Avg| 41ms| 84ms | 43ms | 106.108
| | P99| 238ms| 475ms | 237ms | 99.371
| unfollowThreadByUser | Avg| 43ms| 36ms | -7ms | -16.313
| | P99| 535ms| 424ms | -111ms | -20.749
| updateCategoriesForTeamForUser | Avg| 107ms| 165ms | 58ms | 54.353
| | P99| 885ms| 1.885s | 1s | 112.996
| updatePreferences | Avg| 23ms| 17ms | -6ms | -25.682
| | P99| 241ms| 217ms | -24ms | -9.948
| updateReadStateAllThreadsByUser | Avg| 3ms| 7ms | 4ms | 125.725
| | P99| 5ms| 25ms | 20ms | 404.040
| updateReadStateThreadByUser | Avg| 100ms| 82ms | -18ms | -17.960
| | P99| 1.183s| 952ms | -231ms | -19.526
| updateUserCustomStatus | Avg| 300ms| 270ms | -30ms | -9.990
| | P99| 969ms| 926ms | -43ms | -4.440
| updateViewedProductNotices | Avg| 8ms| 0s | -8ms | -103.245
| | P99| 10ms| 0s | -10ms | -100.419
| uploadFileStream | Avg| 505ms| 505ms | 0s | 0.000
| | P99| 2.173s| 2.213s | 40ms | 1.841
| upsertDraft | Avg| 38ms| 5ms | -33ms | -86.165
| | P99| 99ms| 10ms | -89ms | -89.899
| viewChannel | Avg| 35ms| 30ms | -5ms | -14.144
| | P99| 414ms| 385ms | -29ms | -7.012

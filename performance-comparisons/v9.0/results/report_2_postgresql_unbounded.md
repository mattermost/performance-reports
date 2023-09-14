### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 5ms | 66ms | 61ms | 1272.56
| CommandWebhookStore.Cleanup | avg | 2ms | 26ms | 24ms | 1032.73
| PostStore.AnalyticsPostCount | avg | 773ms | 3.462s | 2.689s | 348.05
| TokenStore.Cleanup | avg | 9ms | 37ms | 28ms | 317.66
| RoleStore.ChannelHigherScopedPermissions | avg | 20ms | 73ms | 53ms | 265.47
| PreferenceStore.DeleteCategoryAndName | avg | 27ms | 82ms | 55ms | 204.15
| LinkMetadataStore.Save | avg | 9ms | 27ms | 18ms | 196.79
| StatusStore.GetByIds | avg | 29ms | 63ms | 34ms | 117.85
| BotStore.Get | avg | 14ms | 30ms | 16ms | 112.72
| ProductNoticesStore.ClearOldNotices | avg | 40ms | 82ms | 42ms | 105.54
| SessionStore.Remove | avg | 14ms | 29ms | 15ms | 104.97
| ThreadStore.MarkAllAsReadByChannels | avg | 15ms | 30ms | 15ms | 98.13
| UserStore.GetMany | avg | 21ms | 41ms | 20ms | 96.28
| ChannelStore.UpdateSidebarCategories | avg | 177ms | 347ms | 170ms | 95.92
| LinkMetadataStore.Get | avg | 25ms | 48ms | 23ms | 90.46
| PostPersistentNotificationStore.Get | avg | 10ms | 19ms | 9ms | 90.45
| PostStore.GetPostReminderMetadata | avg | 30ms | 57ms | 27ms | 89.44
| ChannelStore.UpdateSidebarChannelsByPreferences | avg | 13ms | 24ms | 11ms | 85.88
| PostPriorityStore.GetForPosts | avg | 41ms | 73ms | 32ms | 77.85
| JobStore.UpdateStatus | avg | 18ms | 32ms | 14ms | 77.79
| PostStore.Delete | avg | 95ms | 168ms | 73ms | 77.17
| PostStore.GetSingle | avg | 26ms | 46ms | 20ms | 75.98
| JobStore.Save | avg | 14ms | 24ms | 10ms | 73.88
| TeamStore.Get | avg | 25ms | 43ms | 18ms | 72.65
| PostPersistentNotificationStore.DeleteExpired | avg | 11ms | 19ms | 8ms | 71.82
| PostAcknowledgementStore.GetForPosts | avg | 41ms | 70ms | 29ms | 70.82
| PostStore.GetPostIdBeforeTime | avg | 14ms | 24ms | 10ms | 69.43
| ChannelStore.Get | avg | 36ms | 60ms | 24ms | 66.60
| ChannelStore.GetChannelUnread | avg | 36ms | 60ms | 24ms | 66.54
| PluginStore.List | avg | 27ms | 45ms | 18ms | 66.28
| ThreadStore.UpdateMembership | avg | 15ms | 25ms | 10ms | 65.63
| FileInfoStore.GetForPost | avg | 25ms | 41ms | 16ms | 64.73
| ReactionStore.GetForPost | avg | 32ms | 52ms | 20ms | 62.15
| ReactionStore.Save | avg | 60ms | 97ms | 37ms | 61.71
| UserStore.Update | avg | 41ms | 66ms | 25ms | 61.13
| PostStore.Update | avg | 56ms | 90ms | 34ms | 61.02
| ChannelStore.UpdateLastViewedAt | avg | 16ms | 26ms | 10ms | 60.97
| ThreadStore.MaintainMembership | avg | 37ms | 59ms | 22ms | 59.15
| PostStore.Save | avg | 53ms | 84ms | 31ms | 58.82
| PostStore.GetPostsAfter | avg | 41ms | 65ms | 24ms | 58.73
| PostStore.GetPostReminders | avg | 41ms | 65ms | 24ms | 58.72
| FileInfoStore.AttachToPost | avg | 31ms | 49ms | 18ms | 57.37
| ThreadStore.MarkAsRead | avg | 16ms | 25ms | 9ms | 56.94
| PostStore.SetPostReminder | avg | 52ms | 81ms | 29ms | 56.04
| PostStore.GetEtag | avg | 29ms | 45ms | 16ms | 54.68
| TeamStore.GetTeamsForUser | avg | 18ms | 28ms | 10ms | 54.34
| UserStore.GetProfileByIds | avg | 26ms | 40ms | 14ms | 53.83
| SessionStore.UpdateLastActivityAt | avg | 17ms | 26ms | 9ms | 53.78
| ThreadStore.GetThreadFollowers | avg | 28ms | 43ms | 15ms | 53.35
| StatusStore.UpdateLastActivityAt | avg | 17ms | 26ms | 9ms | 52.40
| TeamStore.GetMember | avg | 8ms | 12ms | 4ms | 52.21
| UserStore.Get | avg | 19ms | 29ms | 10ms | 51.59
| SystemStore.GetByName | avg | 12ms | 18ms | 6ms | 51.14
| UserAccessTokenStore.GetByToken | avg | 34ms | 51ms | 17ms | 50.28
| UserStore.GetUnreadCount | avg | 28ms | 42ms | 14ms | 49.94
| ChannelStore.GetChannels | avg | 32ms | 48ms | 16ms | 49.78
| PostStore.Get | avg | 64ms | 96ms | 32ms | 49.64
| PluginStore.Delete | avg | 10ms | 15ms | 5ms | 49.52
| ChannelStore.GetChannelsByUser | avg | 39ms | 58ms | 19ms | 49.15
| PostStore.GetPostIdAfterTime | avg | 10ms | 15ms | 5ms | 48.53
| UserStore.IsEmpty | avg | 8ms | 12ms | 4ms | 48.48
| PostPersistentNotificationStore.GetSingle | avg | 29ms | 43ms | 14ms | 48.38
| ChannelStore.GetPinnedPostCount | avg | 27ms | 40ms | 13ms | 48.19
| ChannelStore.GetForPost | avg | 69ms | 102ms | 33ms | 48.09
| TeamStore.GetChannelUnreadsForAllTeams | avg | 21ms | 31ms | 10ms | 47.64
| UserStore.Count | avg | 53ms | 78ms | 25ms | 46.90
| ChannelStore.IncrementMentionCount | avg | 15ms | 22ms | 7ms | 45.76
| ChannelStore.GetFileCount | avg | 26ms | 38ms | 12ms | 45.64
| UserStore.GetProfilesByUsernames | avg | 31ms | 45ms | 14ms | 45.33
| FileInfoStore.Get | avg | 31ms | 45ms | 14ms | 45.17
| TeamStore.GetAllPage | avg | 18ms | 26ms | 8ms | 44.51
| FileInfoStore.Save | avg | 20ms | 29ms | 9ms | 44.33
| PreferenceStore.Get | avg | 32ms | 46ms | 14ms | 44.16
| ThreadStore.GetMembershipForUser | avg | 32ms | 46ms | 14ms | 44.11
| ThreadStore.GetTeamsUnreadForUser | avg | 35ms | 50ms | 15ms | 43.21
| ThreadStore.GetTotalUnreadMentions | avg | 23ms | 33ms | 10ms | 42.61
| TeamStore.GetTeamsByUserId | avg | 19ms | 27ms | 8ms | 41.83
| PostStore.GetPostsBefore | avg | 36ms | 51ms | 15ms | 41.32
| GroupStore.GetGroups | avg | 27ms | 38ms | 11ms | 41.21
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 56ms | 79ms | 23ms | 40.92
| SessionStore.Save | avg | 30ms | 42ms | 12ms | 40.66
| ThreadStore.GetTotalThreads | avg | 22ms | 31ms | 9ms | 40.57
| ChannelStore.GetMembersForUser | avg | 35ms | 49ms | 14ms | 40.39
| ThreadStore.GetTotalUnreadThreads | avg | 22ms | 31ms | 9ms | 40.07
| UserTermsOfServiceStore.GetByUser | avg | 18ms | 25ms | 7ms | 39.98
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 15ms | 21ms | 6ms | 39.86
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 23ms | 32ms | 9ms | 39.78
| ChannelStore.CreateDirectChannel | avg | 186ms | 260ms | 74ms | 39.72
| ChannelStore.SearchGroupChannels | avg | 43ms | 59ms | 16ms | 37.40
| StatusStore.Get | avg | 13ms | 18ms | 5ms | 37.34
| ThreadStore.GetThreadsForUser | avg | 41ms | 56ms | 15ms | 36.80
| PluginStore.SetWithOptions | avg | 22ms | 30ms | 8ms | 36.43
| SessionStore.Get | avg | 25ms | 34ms | 9ms | 36.12
| ChannelStore.CreateInitialSidebarCategories | avg | 79ms | 107ms | 28ms | 35.27
| UserStore.GetForLogin | avg | 17ms | 23ms | 6ms | 34.97
| UserStore.UpdateFailedPasswordAttempts | avg | 15ms | 20ms | 5ms | 34.46
| ChannelStore.GetGuestCount | avg | 24ms | 32ms | 8ms | 33.98
| ClusterDiscoveryStore.SetLastPingAt | avg | 18ms | 24ms | 6ms | 33.76
| WebhookStore.GetOutgoingByTeam | avg | 39ms | 52ms | 13ms | 33.15
| UserStore.UpdateUpdateAt | avg | 12ms | 16ms | 4ms | 32.72
| ProductNoticesStore.View | avg | 144ms | 191ms | 47ms | 32.58
| PreferenceStore.GetAll | avg | 22ms | 29ms | 7ms | 32.40
| PostStore.GetPosts | avg | 19ms | 25ms | 6ms | 32.35
| ChannelStore.Save | avg | 98ms | 129ms | 31ms | 31.79
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 30ms | 39ms | 9ms | 30.27
| AuditStore.Save | avg | 14ms | 18ms | 4ms | 29.63
| JobStore.GetAllByStatus | avg | 31ms | 40ms | 9ms | 29.48
| ChannelStore.GetByName | avg | 17ms | 22ms | 5ms | 29.28
| ChannelStore.GetAllChannelMembersForUser | avg | 7ms | 9ms | 2ms | 28.97
| UserStore.GetAllProfiles | avg | 18ms | 23ms | 5ms | 28.11
| ThreadStore.GetThreadForUser | avg | 62ms | 79ms | 17ms | 27.59
| ChannelStore.GetMember | avg | 22ms | 28ms | 6ms | 27.33
| GroupStore.GetByName | avg | 15ms | 19ms | 4ms | 27.29
| ChannelStore.GetMembers | avg | 428ms | 542ms | 114ms | 26.64
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 69ms | 87ms | 18ms | 25.98
| ChannelMemberHistoryStore.LogJoinEvent | avg | 12ms | 15ms | 3ms | 25.82
| JobStore.GetCountByStatusAndType | avg | 32ms | 40ms | 8ms | 24.68
| TeamStore.SaveMember | avg | 65ms | 80ms | 15ms | 23.23
| ChannelStore.SaveMember | avg | 132ms | 161ms | 29ms | 22.02
| ChannelStore.GetMemberForPost | avg | 42ms | 51ms | 9ms | 21.50
| JobStore.UpdateOptimistically | avg | 19ms | 23ms | 4ms | 21.19
| PostStore.GetPostsByThread | avg | 50ms | 59ms | 9ms | 18.00
| PreferenceStore.Save | avg | 40ms | 46ms | 6ms | 14.97
| ThreadStore.Get | avg | 41ms | 47ms | 6ms | 14.54
| TeamStore.GetByName | avg | 32ms | 36ms | 4ms | 12.33
| UserStore.Save | avg | 107ms | 120ms | 13ms | 12.11
| ChannelStore.GetMemberCount | avg | 78ms | 87ms | 9ms | 11.54
| UserStore.GetAllProfilesInChannel | avg | 918ms | 1.014s | 96ms | 10.46
| ChannelStore.GetSidebarCategory | avg | 107ms | 118ms | 11ms | 10.26
| ThreadStore.GetThreadUnreadReplyCount | avg | 63ms | 68ms | 5ms | 7.93
| JobStore.Get | avg | 42ms | 44ms | 2ms | 4.81
| ChannelStore.GetPublicChannelsForTeam | avg | 132ms | 136ms | 4ms | 3.02
| StatusStore.SaveOrUpdate | avg | 158ms | 161ms | 3ms | 1.90
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 99ms | 94ms | 1896.54
| RoleStore.ChannelHigherScopedPermissions | p99 | 95ms | 1.45s | 1.355s | 1430.83
| CommandWebhookStore.Cleanup | p99 | 5ms | 50ms | 45ms | 908.52
| PostStore.AnalyticsPostCount | p99 | 995ms | 9.9s | 8.905s | 894.97
| PreferenceStore.DeleteCategoryAndName | p99 | 95ms | 885ms | 790ms | 827.25
| LinkMetadataStore.Save | p99 | 45ms | 222ms | 177ms | 395.54
| UserStore.GetMany | p99 | 91ms | 417ms | 326ms | 360.22
| TokenStore.Cleanup | p99 | 25ms | 98ms | 73ms | 295.55
| PostStore.Delete | p99 | 248ms | 885ms | 637ms | 256.98
| ChannelStore.UpdateSidebarCategories | p99 | 835ms | 2.295s | 1.46s | 174.84
| JobStore.Save | p99 | 77ms | 202ms | 125ms | 162.34
| BotStore.Get | p99 | 91ms | 232ms | 141ms | 154.10
| ChannelStore.GetForPost | p99 | 99ms | 249ms | 150ms | 151.52
| JobStore.UpdateStatus | p99 | 95ms | 235ms | 140ms | 148.14
| PostStore.GetPostReminderMetadata | p99 | 98ms | 239ms | 141ms | 144.15
| SessionStore.Remove | p99 | 94ms | 217ms | 123ms | 130.85
| ChannelStore.CreateDirectChannel | p99 | 956ms | 2.086s | 1.13s | 118.26
| StatusStore.GetByIds | p99 | 229ms | 495ms | 266ms | 116.30
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 100ms | 50ms | 100.50
| ChannelStore.UpdateLastViewedAt | p99 | 100ms | 200ms | 100ms | 99.67
| UserStore.Count | p99 | 233ms | 465ms | 232ms | 99.36
| PostPersistentNotificationStore.DeleteExpired | p99 | 48ms | 96ms | 48ms | 99.35
| UserStore.IsEmpty | p99 | 98ms | 189ms | 91ms | 93.25
| PostStore.GetPostIdBeforeTime | p99 | 104ms | 197ms | 93ms | 89.61
| ThreadStore.UpdateMembership | p99 | 99ms | 187ms | 88ms | 89.20
| ThreadStore.MarkAsRead | p99 | 99ms | 184ms | 85ms | 85.85
| PostPriorityStore.GetForPosts | p99 | 431ms | 794ms | 363ms | 84.14
| ChannelStore.GetTeamChannels | p99 | 247ms | 455ms | 208ms | 84.08
| PostStore.SetPostReminder | p99 | 242ms | 445ms | 203ms | 84.06
| ThreadStore.MarkAllAsReadByChannels | p99 | 112ms | 206ms | 94ms | 83.68
| SystemStore.GetByName | p99 | 98ms | 177ms | 79ms | 80.81
| PostAcknowledgementStore.GetForPosts | p99 | 430ms | 776ms | 346ms | 80.44
| StatusStore.UpdateLastActivityAt | p99 | 111ms | 200ms | 89ms | 79.83
| LinkMetadataStore.Get | p99 | 239ms | 429ms | 190ms | 79.59
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 112ms | 200ms | 88ms | 78.87
| SessionStore.UpdateLastActivityAt | p99 | 112ms | 200ms | 88ms | 78.34
| PostStore.GetSingle | p99 | 239ms | 424ms | 185ms | 77.35
| PostStore.GetPostsAfter | p99 | 306ms | 541ms | 235ms | 76.89
| ThreadStore.GetThreadFollowers | p99 | 240ms | 423ms | 183ms | 76.13
| TeamStore.Get | p99 | 238ms | 409ms | 171ms | 71.97
| AuditStore.Save | p99 | 98ms | 166ms | 68ms | 69.07
| UserStore.UpdateFailedPasswordAttempts | p99 | 102ms | 172ms | 70ms | 68.73
| PostPersistentNotificationStore.GetSingle | p99 | 250ms | 418ms | 168ms | 67.32
| ProductNoticesStore.View | p99 | 946ms | 1.559s | 613ms | 64.81
| UserStore.GetUnreadCount | p99 | 236ms | 388ms | 152ms | 64.39
| UserStore.GetProfilesByUsernames | p99 | 247ms | 405ms | 158ms | 63.94
| FileInfoStore.Get | p99 | 248ms | 402ms | 154ms | 62.19
| UserStore.GetProfileByIds | p99 | 236ms | 375ms | 139ms | 58.87
| ChannelStore.GetMemberForPost | p99 | 249ms | 395ms | 146ms | 58.62
| PostStore.Get | p99 | 488ms | 772ms | 284ms | 58.24
| ChannelStore.GetPinnedPostCount | p99 | 244ms | 385ms | 141ms | 57.77
| GroupStore.GetGroups | p99 | 244ms | 382ms | 138ms | 56.49
| ThreadStore.MaintainMembership | p99 | 244ms | 381ms | 137ms | 56.25
| PostStore.Save | p99 | 447ms | 694ms | 247ms | 55.31
| FileInfoStore.GetForPost | p99 | 242ms | 374ms | 132ms | 54.56
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 485ms | 743ms | 258ms | 53.19
| ThreadStore.GetMembershipForUser | p99 | 290ms | 435ms | 145ms | 49.92
| ChannelStore.GetChannelUnread | p99 | 314ms | 470ms | 156ms | 49.67
| SessionStore.Save | p99 | 247ms | 367ms | 120ms | 48.64
| PostStore.GetEtag | p99 | 294ms | 436ms | 142ms | 48.35
| ReactionStore.GetForPost | p99 | 309ms | 454ms | 145ms | 46.97
| PreferenceStore.Get | p99 | 295ms | 432ms | 137ms | 46.50
| ChannelStore.IncrementMentionCount | p99 | 134ms | 196ms | 62ms | 46.28
| PostStore.GetPostsBefore | p99 | 302ms | 440ms | 138ms | 45.74
| ChannelStore.CreateInitialSidebarCategories | p99 | 586ms | 853ms | 267ms | 45.56
| ChannelStore.GetChannels | p99 | 306ms | 444ms | 138ms | 45.09
| ChannelStore.GetAllChannelMembersForUser | p99 | 140ms | 202ms | 62ms | 44.23
| PluginStore.Delete | p99 | 92ms | 132ms | 40ms | 43.32
| ChannelStore.GetChannelsByUser | p99 | 331ms | 474ms | 143ms | 43.19
| PostStore.GetPostIdAfterTime | p99 | 93ms | 133ms | 40ms | 42.96
| ChannelStore.GetMembersForUser | p99 | 311ms | 444ms | 133ms | 42.74
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 236ms | 335ms | 99ms | 41.88
| ChannelStore.GetGuestCount | p99 | 238ms | 337ms | 99ms | 41.67
| ChannelStore.SaveMember | p99 | 939ms | 1.324s | 385ms | 40.99
| ThreadStore.GetTotalThreads | p99 | 239ms | 336ms | 97ms | 40.65
| ThreadStore.GetTotalUnreadMentions | p99 | 241ms | 334ms | 93ms | 38.57
| ChannelStore.GetPublicChannelsForTeam | p99 | 494ms | 682ms | 188ms | 38.03
| ThreadStore.GetThreadForUser | p99 | 470ms | 632ms | 162ms | 34.43
| ChannelStore.Get | p99 | 370ms | 489ms | 119ms | 32.20
| UserStore.UpdateUpdateAt | p99 | 89ms | 117ms | 28ms | 31.55
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 94ms | 123ms | 29ms | 31.01
| ChannelStore.GetFileCount | p99 | 229ms | 299ms | 70ms | 30.60
| ThreadStore.GetTotalUnreadThreads | p99 | 238ms | 304ms | 66ms | 27.73
| ThreadStore.GetThreadsForUser | p99 | 369ms | 469ms | 100ms | 27.07
| ChannelStore.SearchGroupChannels | p99 | 380ms | 475ms | 95ms | 25.01
| ThreadStore.GetTeamsUnreadForUser | p99 | 391ms | 485ms | 94ms | 24.02
| FileInfoStore.Save | p99 | 171ms | 211ms | 40ms | 23.33
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 229ms | 281ms | 52ms | 22.70
| StatusStore.Get | p99 | 180ms | 219ms | 39ms | 21.62
| WebhookStore.GetOutgoingByTeam | p99 | 376ms | 457ms | 81ms | 21.55
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 389ms | 471ms | 82ms | 21.07
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 196ms | 236ms | 40ms | 20.43
| TeamStore.GetMember | p99 | 84ms | 101ms | 17ms | 20.22
| FileInfoStore.AttachToPost | p99 | 228ms | 272ms | 44ms | 19.26
| TeamStore.GetTeamsForUser | p99 | 215ms | 256ms | 41ms | 19.09
| JobStore.UpdateOptimistically | p99 | 184ms | 219ms | 35ms | 19.02
| ClusterDiscoveryStore.SetLastPingAt | p99 | 161ms | 190ms | 29ms | 18.01
| UserStore.Get | p99 | 212ms | 250ms | 38ms | 17.95
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 246ms | 288ms | 42ms | 17.06
| GroupStore.GetByName | p99 | 196ms | 228ms | 32ms | 16.31
| TeamStore.GetAllPage | p99 | 213ms | 247ms | 34ms | 15.95
| PostStore.Update | p99 | 409ms | 473ms | 64ms | 15.64
| PostStore.GetPosts | p99 | 210ms | 239ms | 29ms | 13.79
| ReactionStore.Save | p99 | 420ms | 475ms | 55ms | 13.10
| UserTermsOfServiceStore.GetByUser | p99 | 215ms | 243ms | 28ms | 13.03
| TeamStore.SaveMember | p99 | 423ms | 478ms | 55ms | 13.01
| UserStore.GetForLogin | p99 | 215ms | 243ms | 28ms | 13.01
| ChannelStore.GetByName | p99 | 211ms | 238ms | 27ms | 12.81
| PostPersistentNotificationStore.Get | p99 | 86ms | 96ms | 10ms | 11.56
| ChannelStore.GetMember | p99 | 216ms | 239ms | 23ms | 10.66
| PluginStore.SetWithOptions | p99 | 213ms | 235ms | 22ms | 10.32
| TeamStore.GetTeamsByUserId | p99 | 224ms | 247ms | 23ms | 10.26
| PostStore.GetPostsByThread | p99 | 410ms | 451ms | 41ms | 10.01
| PreferenceStore.Save | p99 | 336ms | 369ms | 33ms | 9.81
| UserStore.GetAllProfiles | p99 | 215ms | 235ms | 20ms | 9.29
| PreferenceStore.GetAll | p99 | 228ms | 247ms | 19ms | 8.33
| PluginStore.List | p99 | 410ms | 440ms | 30ms | 7.32
| SessionStore.Get | p99 | 228ms | 243ms | 15ms | 6.58
| StatusStore.SaveOrUpdate | p99 | 2.144s | 2.243s | 99ms | 4.62
| UserStore.Save | p99 | 470ms | 491ms | 21ms | 4.47
| UserAccessTokenStore.GetByToken | p99 | 232ms | 242ms | 10ms | 4.31
| ChannelStore.GetMembers | p99 | 2.316s | 2.398s | 82ms | 3.54
| ThreadStore.GetThreadUnreadReplyCount | p99 | 463ms | 475ms | 12ms | 2.59
| StatusStore.UpdateExpiredDNDStatuses | p99 | 92ms | 94ms | 2ms | 2.19
| PostStore.GetPostReminders | p99 | 242ms | 245ms | 3ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | avg | 26ms | 0s | -26ms | -101.60
| UserStore.GetUnreadCountForChannel | avg | 27ms | 0s | -27ms | -99.60
| SessionStore.GetSessionsExpired | avg | 31ms | 15ms | -16ms | -51.42
| PostPriorityStore.GetForPost | avg | 41ms | 32ms | -9ms | -21.87
| ChannelStore.Autocomplete | avg | 255ms | 206ms | -49ms | -19.24
| UserStore.GetByUsername | avg | 49ms | 41ms | -8ms | -16.23
| ChannelStore.GetTeamChannels | avg | 136ms | 114ms | -22ms | -16.14
| UserStore.AutocompleteUsersInChannel | avg | 351ms | 300ms | -51ms | -14.54
| JobStore.GetNewestJobByStatusesAndType | avg | 49ms | 43ms | -6ms | -12.28
| PostStore.SearchPostsForUser | avg | 569ms | 517ms | -52ms | -9.13
| PostStore.GetPostsSince | avg | 130ms | 122ms | -8ms | -6.17
| ChannelStore.AutocompleteInTeamForSearch | avg | 277ms | 261ms | -16ms | -5.77
| UserStore.Search | avg | 130ms | 123ms | -7ms | -5.37
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetUnreadCountForChannel | p99 | 241ms | 0s | -241ms | -99.87
| EmojiStore.GetMultipleByName | p99 | 239ms | 0s | -239ms | -99.84
| ChannelStore.GetSidebarCategory | p99 | 2.005s | 590ms | -1.415s | -70.57
| JobStore.GetNewestJobByStatusesAndType | p99 | 1.09s | 338ms | -752ms | -68.99
| SessionStore.GetSessionsExpired | p99 | 98ms | 48ms | -50ms | -50.89
| PostStore.GetPostsSince | p99 | 1.357s | 926ms | -431ms | -31.76
| PostPriorityStore.GetForPost | p99 | 435ms | 306ms | -129ms | -29.65
| UserStore.Search | p99 | 1.934s | 1.388s | -546ms | -28.23
| UserStore.GetByUsername | p99 | 470ms | 346ms | -124ms | -26.38
| PostAcknowledgementStore.GetForPost | p99 | 312ms | 234ms | -78ms | -25.03
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.635s | 1.255s | -380ms | -23.24
| JobStore.UpdateStatusOptimistically | p99 | 182ms | 156ms | -26ms | -14.25
| ChannelStore.Autocomplete | p99 | 2.276s | 2.039s | -237ms | -10.41
| ThreadStore.Get | p99 | 420ms | 382ms | -38ms | -9.05
| UserStore.AutocompleteUsersInChannel | p99 | 2.381s | 2.167s | -214ms | -8.99
| TeamStore.GetByName | p99 | 321ms | 293ms | -28ms | -8.72
| PostStore.SearchPostsForUser | p99 | 8.927s | 8.273s | -654ms | -7.33
| JobStore.GetAllByStatus | p99 | 280ms | 263ms | -17ms | -6.06
| JobStore.GetCountByStatusAndType | p99 | 441ms | 419ms | -22ms | -4.99
| JobStore.Get | p99 | 445ms | 423ms | -22ms | -4.94
| UserStore.Update | p99 | 338ms | 322ms | -16ms | -4.73
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 5ms | 66ms | 61ms | 1244.38
| logout | avg | 190ms | 465ms | 275ms | 144.42
| removeUserCustomStatus | avg | 327ms | 716ms | 389ms | 118.89
| deletePost | avg | 183ms | 331ms | 148ms | 80.67
| updatePreferences | avg | 60ms | 102ms | 42ms | 70.30
| getUserStatusesByIds | avg | 3ms | 5ms | 2ms | 66.94
| getChannelUnread | avg | 41ms | 67ms | 26ms | 62.84
| updateCategoriesForTeamForUser | avg | 410ms | 648ms | 238ms | 57.99
| createGroupChannel | avg | 1.243s | 1.961s | 718ms | 57.76
| getUsersByIds | avg | 5ms | 8ms | 3ms | 56.00
| followThreadByUser | avg | 113ms | 176ms | 63ms | 55.70
| createDirectChannel | avg | 658ms | 1.02s | 362ms | 54.99
| updateUserCustomStatus | avg | 493ms | 760ms | 267ms | 54.21
| getTeamMembersForUser | avg | 21ms | 32ms | 11ms | 51.30
| getClientConfig | avg | 35ms | 53ms | 18ms | 51.10
| addChannelMember | avg | 1.022s | 1.537s | 515ms | 50.38
| getChannelsForUser | avg | 39ms | 58ms | 19ms | 49.01
| getUser | avg | 32ms | 47ms | 15ms | 46.93
| getChannel | avg | 60ms | 88ms | 28ms | 46.71
| getChannelsForTeamForUser | avg | 33ms | 48ms | 15ms | 45.43
| getAllTeams | avg | 20ms | 29ms | 9ms | 44.95
| getUsersByNames | avg | 32ms | 46ms | 14ms | 44.22
| getTeamMember | avg | 20ms | 29ms | 9ms | 44.22
| getTeamsUnreadForUser | avg | 39ms | 56ms | 17ms | 43.71
| saveReaction | avg | 180ms | 257ms | 77ms | 42.89
| login | avg | 215ms | 307ms | 92ms | 42.74
| getUsers | avg | 35ms | 50ms | 15ms | 42.74
| getChannelMembersForTeamForUser | avg | 35ms | 50ms | 15ms | 42.42
| getTeamsForUser | avg | 19ms | 27ms | 8ms | 41.26
| searchGroupChannels | avg | 43ms | 60ms | 17ms | 39.64
| createPost | avg | 3.424s | 4.702s | 1.278s | 37.33
| getChannelMembers | avg | 103ms | 140ms | 37ms | 35.81
| getPreferences | avg | 22ms | 30ms | 8ms | 35.65
| getThreadsForUser | avg | 43ms | 58ms | 15ms | 35.23
| getPostThread | avg | 215ms | 289ms | 74ms | 34.42
| getFileThumbnail | avg | 115ms | 154ms | 39ms | 33.98
| getFilePreview | avg | 123ms | 162ms | 39ms | 31.67
| updateReadStateThreadByUser | avg | 417ms | 536ms | 119ms | 28.54
| unfollowThreadByUser | avg | 170ms | 218ms | 48ms | 28.25
| getCategoriesForTeamForUser | avg | 70ms | 88ms | 18ms | 25.74
| setPostReminder | avg | 260ms | 324ms | 64ms | 24.61
| getChannelMember | avg | 49ms | 59ms | 10ms | 20.46
| patchPost | avg | 415ms | 485ms | 70ms | 16.88
| getChannelStats | avg | 36ms | 42ms | 6ms | 16.45
| addTeamMember | avg | 2.105s | 2.432s | 327ms | 15.53
| createUser | avg | 208ms | 239ms | 31ms | 14.87
| uploadFileStream | avg | 592ms | 675ms | 83ms | 14.01
| getPostsForChannelAroundLastUnread | avg | 140ms | 159ms | 19ms | 13.59
| getPublicChannelsForTeam | avg | 134ms | 139ms | 5ms | 3.73
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 99ms | 94ms | 1896.54
| deletePost | p99 | 489ms | 2.155s | 1.666s | 340.85
| logout | p99 | 490ms | 990ms | 500ms | 102.04
| followThreadByUser | p99 | 453ms | 895ms | 442ms | 97.68
| createGroupChannel | p99 | 4.82s | 9.1s | 4.28s | 88.80
| createChannel | p99 | 247ms | 455ms | 208ms | 84.08
| saveReaction | p99 | 991ms | 1.823s | 832ms | 83.94
| createDirectChannel | p99 | 2.466s | 4.518s | 2.052s | 83.23
| updateUserCustomStatus | p99 | 2.373s | 4.237s | 1.864s | 78.54
| getUserStatusesByIds | p99 | 69ms | 123ms | 54ms | 77.78
| getUsersByNames | p99 | 249ms | 416ms | 167ms | 67.06
| getUsersByIds | p99 | 88ms | 146ms | 58ms | 65.93
| createUser | p99 | 980ms | 1.575s | 595ms | 60.74
| getCategoriesForTeamForUser | p99 | 486ms | 747ms | 261ms | 53.71
| getClientConfig | p99 | 281ms | 415ms | 134ms | 47.70
| getChannelsForUser | p99 | 331ms | 474ms | 143ms | 43.19
| getTeamMembersForUser | p99 | 233ms | 333ms | 100ms | 42.95
| getChannelsForTeamForUser | p99 | 316ms | 449ms | 133ms | 42.11
| getFileThumbnail | p99 | 635ms | 899ms | 264ms | 41.58
| getChannelMembersForTeamForUser | p99 | 320ms | 448ms | 128ms | 39.95
| getPublicChannelsForTeam | p99 | 494ms | 682ms | 188ms | 38.03
| getFilePreview | p99 | 660ms | 909ms | 249ms | 37.75
| getChannel | p99 | 595ms | 793ms | 198ms | 33.28
| getChannelUnread | p99 | 376ms | 494ms | 118ms | 31.36
| getTeamsUnreadForUser | p99 | 446ms | 573ms | 127ms | 28.49
| getAllTeams | p99 | 227ms | 291ms | 64ms | 28.19
| searchGroupChannels | p99 | 380ms | 479ms | 99ms | 26.06
| removeUserCustomStatus | p99 | 2.01s | 2.489s | 479ms | 23.83
| getUser | p99 | 399ms | 472ms | 73ms | 18.29
| getThreadsForUser | p99 | 418ms | 493ms | 75ms | 17.94
| getChannelStats | p99 | 494ms | 577ms | 83ms | 16.81
| getPostsForChannelAroundLastUnread | p99 | 1.472s | 1.7s | 228ms | 15.49
| getPostThread | p99 | 1.966s | 2.237s | 271ms | 13.78
| getUsers | p99 | 415ms | 470ms | 55ms | 13.26
| updatePreferences | p99 | 435ms | 488ms | 53ms | 12.19
| addChannelMember | p99 | 4.393s | 4.899s | 506ms | 11.52
| login | p99 | 2.126s | 2.367s | 241ms | 11.34
| getTeamMember | p99 | 205ms | 228ms | 23ms | 11.20
| getTeamsForUser | p99 | 226ms | 250ms | 24ms | 10.60
| getChannelMember | p99 | 439ms | 480ms | 41ms | 9.35
| getPreferences | p99 | 234ms | 254ms | 20ms | 8.54
| updateReadStateThreadByUser | p99 | 2.341s | 2.472s | 131ms | 5.60
| uploadFileStream | p99 | 2.361s | 2.419s | 58ms | 2.46
| getProfileImage | p99 | 482ms | 493ms | 11ms | 2.28
| createPost | p99 | 9.718s | 9.935s | 217ms | 2.23
| addTeamMember | p99 | 9.798s | 10s | 202ms | 2.06
| unfollowThreadByUser | p99 | 928ms | 946ms | 18ms | 1.94
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPostsForChannel | avg | 1.245s | 658ms | -587ms | -47.14
| searchAllChannels | avg | 256ms | 208ms | -48ms | -18.77
| createChannel | avg | 136ms | 115ms | -21ms | -15.39
| autocompleteUsers | avg | 296ms | 252ms | -44ms | -14.84
| searchPostsInTeam | avg | 759ms | 657ms | -102ms | -13.44
| autocompleteChannelsForTeamForSearch | avg | 278ms | 261ms | -17ms | -6.12
| searchUsers | avg | 133ms | 129ms | -4ms | -3.00
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 2.245s | 982ms | -1.263s | -56.26
| updateCategoriesForTeamForUser | p99 | 4.175s | 2.439s | -1.736s | -41.58
| getPostsForChannel | p99 | 10s | 6.993s | -3.007s | -30.07
| searchUsers | p99 | 1.964s | 1.489s | -475ms | -24.18
| autocompleteChannelsForTeamForSearch | p99 | 1.635s | 1.255s | -380ms | -23.24
| patchPost | p99 | 3.637s | 2.813s | -824ms | -22.65
| autocompleteUsers | p99 | 2.335s | 2.073s | -262ms | -11.22
| searchAllChannels | p99 | 2.276s | 2.039s | -237ms | -10.41
| searchPostsInTeam | p99 | 9.958s | 8.955s | -1.003s | -10.07
| viewChannel | p99 | 999ms | 977ms | -22ms | -2.20
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 14ms| 18ms | 4ms | 29.626
| |  P99| 98ms| 166ms | 68ms | 69.073
| BotStore.Get |  Avg| 14ms| 30ms | 16ms | 112.717
| |  P99| 91ms| 232ms | 141ms | 154.098
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 12ms| 15ms | 3ms | 25.816
| |  P99| 94ms| 123ms | 29ms | 31.007
| ChannelStore.Autocomplete |  Avg| 255ms| 206ms | -49ms | -19.238
| |  P99| 2.276s| 2.039s | -237ms | -10.413
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 277ms| 261ms | -16ms | -5.767
| |  P99| 1.635s| 1.255s | -380ms | -23.243
| ChannelStore.CreateDirectChannel |  Avg| 186ms| 260ms | 74ms | 39.715
| |  P99| 956ms| 2.086s | 1.13s | 118.257
| ChannelStore.CreateInitialSidebarCategories |  Avg| 79ms| 107ms | 28ms | 35.265
| |  P99| 586ms| 853ms | 267ms | 45.559
| ChannelStore.Get |  Avg| 36ms| 60ms | 24ms | 66.599
| |  P99| 370ms| 489ms | 119ms | 32.199
| ChannelStore.GetAllChannelMembersForUser |  Avg| 7ms| 9ms | 2ms | 28.969
| |  P99| 140ms| 202ms | 62ms | 44.230
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 56ms| 79ms | 23ms | 40.918
| |  P99| 389ms| 471ms | 82ms | 21.066
| ChannelStore.GetByName |  Avg| 17ms| 22ms | 5ms | 29.276
| |  P99| 211ms| 238ms | 27ms | 12.814
| ChannelStore.GetChannelUnread |  Avg| 36ms| 60ms | 24ms | 66.537
| |  P99| 314ms| 470ms | 156ms | 49.667
| ChannelStore.GetChannels |  Avg| 32ms| 48ms | 16ms | 49.784
| |  P99| 306ms| 444ms | 138ms | 45.092
| ChannelStore.GetChannelsByUser |  Avg| 39ms| 58ms | 19ms | 49.155
| |  P99| 331ms| 474ms | 143ms | 43.192
| ChannelStore.GetFileCount |  Avg| 26ms| 38ms | 12ms | 45.644
| |  P99| 229ms| 299ms | 70ms | 30.600
| ChannelStore.GetForPost |  Avg| 69ms| 102ms | 33ms | 48.088
| |  P99| 99ms| 249ms | 150ms | 151.515
| ChannelStore.GetGuestCount |  Avg| 24ms| 32ms | 8ms | 33.978
| |  P99| 238ms| 337ms | 99ms | 41.673
| ChannelStore.GetMember |  Avg| 22ms| 28ms | 6ms | 27.335
| |  P99| 216ms| 239ms | 23ms | 10.658
| ChannelStore.GetMemberCount |  Avg| 78ms| 87ms | 9ms | 11.542
| |  P99| 735ms| 730ms | -5ms | -0.680
| ChannelStore.GetMemberForPost |  Avg| 42ms| 51ms | 9ms | 21.497
| |  P99| 249ms| 395ms | 146ms | 58.617
| ChannelStore.GetMembers |  Avg| 428ms| 542ms | 114ms | 26.640
| |  P99| 2.316s| 2.398s | 82ms | 3.540
| ChannelStore.GetMembersForUser |  Avg| 35ms| 49ms | 14ms | 40.386
| |  P99| 311ms| 444ms | 133ms | 42.737
| ChannelStore.GetPinnedPostCount |  Avg| 27ms| 40ms | 13ms | 48.188
| |  P99| 244ms| 385ms | 141ms | 57.766
| ChannelStore.GetPublicChannelsForTeam |  Avg| 132ms| 136ms | 4ms | 3.020
| |  P99| 494ms| 682ms | 188ms | 38.029
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 69ms| 87ms | 18ms | 25.985
| |  P99| 485ms| 743ms | 258ms | 53.185
| ChannelStore.GetSidebarCategory |  Avg| 107ms| 118ms | 11ms | 10.259
| |  P99| 2.005s| 590ms | -1.415s | -70.568
| ChannelStore.GetTeamChannels |  Avg| 136ms| 114ms | -22ms | -16.135
| |  P99| 247ms| 455ms | 208ms | 84.083
| ChannelStore.IncrementMentionCount |  Avg| 15ms| 22ms | 7ms | 45.756
| |  P99| 134ms| 196ms | 62ms | 46.277
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 98ms| 129ms | 31ms | 31.787
| |  P99| 500ms| 497ms | -3ms | -0.600
| ChannelStore.SaveMember |  Avg| 132ms| 161ms | 29ms | 22.020
| |  P99| 939ms| 1.324s | 385ms | 40.992
| ChannelStore.SearchGroupChannels |  Avg| 43ms| 59ms | 16ms | 37.398
| |  P99| 380ms| 475ms | 95ms | 25.006
| ChannelStore.UpdateLastViewedAt |  Avg| 16ms| 26ms | 10ms | 60.967
| |  P99| 100ms| 200ms | 100ms | 99.672
| ChannelStore.UpdateSidebarCategories |  Avg| 177ms| 347ms | 170ms | 95.919
| |  P99| 835ms| 2.295s | 1.46s | 174.839
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 13ms| 24ms | 11ms | 85.883
| |  P99| 112ms| 200ms | 88ms | 78.869
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 18ms| 24ms | 6ms | 33.765
| |  P99| 161ms| 190ms | 29ms | 18.013
| CommandWebhookStore.Cleanup |  Avg| 2ms| 26ms | 24ms | 1032.726
| |  P99| 5ms| 50ms | 45ms | 908.521
| EmojiStore.GetMultipleByName |  Avg| 26ms| 0s | -26ms | -101.603
| |  P99| 239ms| 0s | -239ms | -99.837
| FileInfoStore.AttachToPost |  Avg| 31ms| 49ms | 18ms | 57.371
| |  P99| 228ms| 272ms | 44ms | 19.256
| FileInfoStore.Get |  Avg| 31ms| 45ms | 14ms | 45.168
| |  P99| 248ms| 402ms | 154ms | 62.192
| FileInfoStore.GetForPost |  Avg| 25ms| 41ms | 16ms | 64.734
| |  P99| 242ms| 374ms | 132ms | 54.556
| FileInfoStore.Save |  Avg| 20ms| 29ms | 9ms | 44.334
| |  P99| 171ms| 211ms | 40ms | 23.334
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 15ms| 21ms | 6ms | 39.860
| |  P99| 196ms| 236ms | 40ms | 20.430
| GroupStore.GetByName |  Avg| 15ms| 19ms | 4ms | 27.290
| |  P99| 196ms| 228ms | 32ms | 16.310
| GroupStore.GetGroups |  Avg| 27ms| 38ms | 11ms | 41.210
| |  P99| 244ms| 382ms | 138ms | 56.486
| JobStore.Get |  Avg| 42ms| 44ms | 2ms | 4.812
| |  P99| 445ms| 423ms | -22ms | -4.944
| JobStore.GetAllByStatus |  Avg| 31ms| 40ms | 9ms | 29.477
| |  P99| 280ms| 263ms | -17ms | -6.064
| JobStore.GetCountByStatusAndType |  Avg| 32ms| 40ms | 8ms | 24.682
| |  P99| 441ms| 419ms | -22ms | -4.986
| JobStore.GetNewestJobByStatusesAndType |  Avg| 49ms| 43ms | -6ms | -12.284
| |  P99| 1.09s| 338ms | -752ms | -68.991
| JobStore.Save |  Avg| 14ms| 24ms | 10ms | 73.882
| |  P99| 77ms| 202ms | 125ms | 162.338
| JobStore.UpdateOptimistically |  Avg| 19ms| 23ms | 4ms | 21.195
| |  P99| 184ms| 219ms | 35ms | 19.024
| JobStore.UpdateStatus |  Avg| 18ms| 32ms | 14ms | 77.794
| |  P99| 95ms| 235ms | 140ms | 148.143
| JobStore.UpdateStatusOptimistically |  Avg| 22ms| 23ms | 1ms | 4.619
| |  P99| 182ms| 156ms | -26ms | -14.248
| LinkMetadataStore.Get |  Avg| 25ms| 48ms | 23ms | 90.464
| |  P99| 239ms| 429ms | 190ms | 79.594
| LinkMetadataStore.Save |  Avg| 9ms| 27ms | 18ms | 196.790
| |  P99| 45ms| 222ms | 177ms | 395.541
| PluginStore.Delete |  Avg| 10ms| 15ms | 5ms | 49.516
| |  P99| 92ms| 132ms | 40ms | 43.323
| PluginStore.List |  Avg| 27ms| 45ms | 18ms | 66.281
| |  P99| 410ms| 440ms | 30ms | 7.317
| PluginStore.SetWithOptions |  Avg| 22ms| 30ms | 8ms | 36.435
| |  P99| 213ms| 235ms | 22ms | 10.323
| PostAcknowledgementStore.GetForPost |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 312ms| 234ms | -78ms | -25.025
| PostAcknowledgementStore.GetForPosts |  Avg| 41ms| 70ms | 29ms | 70.824
| |  P99| 430ms| 776ms | 346ms | 80.438
| PostPersistentNotificationStore.DeleteExpired |  Avg| 11ms| 19ms | 8ms | 71.823
| |  P99| 48ms| 96ms | 48ms | 99.351
| PostPersistentNotificationStore.Get |  Avg| 10ms| 19ms | 9ms | 90.446
| |  P99| 86ms| 96ms | 10ms | 11.561
| PostPersistentNotificationStore.GetSingle |  Avg| 29ms| 43ms | 14ms | 48.384
| |  P99| 250ms| 418ms | 168ms | 67.318
| PostPriorityStore.GetForPost |  Avg| 41ms| 32ms | -9ms | -21.873
| |  P99| 435ms| 306ms | -129ms | -29.654
| PostPriorityStore.GetForPosts |  Avg| 41ms| 73ms | 32ms | 77.851
| |  P99| 431ms| 794ms | 363ms | 84.136
| PostStore.AnalyticsPostCount |  Avg| 773ms| 3.462s | 2.689s | 348.052
| |  P99| 995ms| 9.9s | 8.905s | 894.975
| PostStore.Delete |  Avg| 95ms| 168ms | 73ms | 77.170
| |  P99| 248ms| 885ms | 637ms | 256.981
| PostStore.Get |  Avg| 64ms| 96ms | 32ms | 49.642
| |  P99| 488ms| 772ms | 284ms | 58.240
| PostStore.GetEtag |  Avg| 29ms| 45ms | 16ms | 54.681
| |  P99| 294ms| 436ms | 142ms | 48.353
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 10ms| 15ms | 5ms | 48.528
| |  P99| 93ms| 133ms | 40ms | 42.956
| PostStore.GetPostIdBeforeTime |  Avg| 14ms| 24ms | 10ms | 69.431
| |  P99| 104ms| 197ms | 93ms | 89.610
| PostStore.GetPostReminderMetadata |  Avg| 30ms| 57ms | 27ms | 89.442
| |  P99| 98ms| 239ms | 141ms | 144.153
| PostStore.GetPostReminders |  Avg| 41ms| 65ms | 24ms | 58.719
| |  P99| 242ms| 245ms | 3ms | 1.242
| PostStore.GetPosts |  Avg| 19ms| 25ms | 6ms | 32.349
| |  P99| 210ms| 239ms | 29ms | 13.791
| PostStore.GetPostsAfter |  Avg| 41ms| 65ms | 24ms | 58.732
| |  P99| 306ms| 541ms | 235ms | 76.886
| PostStore.GetPostsBefore |  Avg| 36ms| 51ms | 15ms | 41.324
| |  P99| 302ms| 440ms | 138ms | 45.736
| PostStore.GetPostsByThread |  Avg| 50ms| 59ms | 9ms | 17.997
| |  P99| 410ms| 451ms | 41ms | 10.010
| PostStore.GetPostsSince |  Avg| 130ms| 122ms | -8ms | -6.166
| |  P99| 1.357s| 926ms | -431ms | -31.763
| PostStore.GetSingle |  Avg| 26ms| 46ms | 20ms | 75.980
| |  P99| 239ms| 424ms | 185ms | 77.353
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 53ms| 84ms | 31ms | 58.820
| |  P99| 447ms| 694ms | 247ms | 55.314
| PostStore.SearchPostsForUser |  Avg| 569ms| 517ms | -52ms | -9.131
| |  P99| 8.927s| 8.273s | -654ms | -7.326
| PostStore.SetPostReminder |  Avg| 52ms| 81ms | 29ms | 56.038
| |  P99| 242ms| 445ms | 203ms | 84.058
| PostStore.Update |  Avg| 56ms| 90ms | 34ms | 61.020
| |  P99| 409ms| 473ms | 64ms | 15.641
| PreferenceStore.DeleteCategoryAndName |  Avg| 27ms| 82ms | 55ms | 204.146
| |  P99| 95ms| 885ms | 790ms | 827.247
| PreferenceStore.Get |  Avg| 32ms| 46ms | 14ms | 44.162
| |  P99| 295ms| 432ms | 137ms | 46.504
| PreferenceStore.GetAll |  Avg| 22ms| 29ms | 7ms | 32.398
| |  P99| 228ms| 247ms | 19ms | 8.330
| PreferenceStore.Save |  Avg| 40ms| 46ms | 6ms | 14.971
| |  P99| 336ms| 369ms | 33ms | 9.807
| ProductNoticesStore.ClearOldNotices |  Avg| 40ms| 82ms | 42ms | 105.542
| |  P99| 50ms| 100ms | 50ms | 100.503
| ProductNoticesStore.View |  Avg| 144ms| 191ms | 47ms | 32.580
| |  P99| 946ms| 1.559s | 613ms | 64.807
| ReactionStore.GetForPost |  Avg| 32ms| 52ms | 20ms | 62.146
| |  P99| 309ms| 454ms | 145ms | 46.972
| ReactionStore.Save |  Avg| 60ms| 97ms | 37ms | 61.707
| |  P99| 420ms| 475ms | 55ms | 13.097
| RoleStore.ChannelHigherScopedPermissions |  Avg| 20ms| 73ms | 53ms | 265.474
| |  P99| 95ms| 1.45s | 1.355s | 1430.832
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 25ms| 34ms | 9ms | 36.121
| |  P99| 228ms| 243ms | 15ms | 6.583
| SessionStore.GetSessionsExpired |  Avg| 31ms| 15ms | -16ms | -51.416
| |  P99| 98ms| 48ms | -50ms | -50.891
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 30ms| 39ms | 9ms | 30.267
| |  P99| 246ms| 288ms | 42ms | 17.059
| SessionStore.Remove |  Avg| 14ms| 29ms | 15ms | 104.969
| |  P99| 94ms| 217ms | 123ms | 130.849
| SessionStore.Save |  Avg| 30ms| 42ms | 12ms | 40.658
| |  P99| 247ms| 367ms | 120ms | 48.642
| SessionStore.UpdateLastActivityAt |  Avg| 17ms| 26ms | 9ms | 53.778
| |  P99| 112ms| 200ms | 88ms | 78.336
| StatusStore.Get |  Avg| 13ms| 18ms | 5ms | 37.338
| |  P99| 180ms| 219ms | 39ms | 21.617
| StatusStore.GetByIds |  Avg| 29ms| 63ms | 34ms | 117.853
| |  P99| 229ms| 495ms | 266ms | 116.297
| StatusStore.SaveOrUpdate |  Avg| 158ms| 161ms | 3ms | 1.899
| |  P99| 2.144s| 2.243s | 99ms | 4.618
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 15ms| 16ms | 1ms | 6.529
| |  P99| 92ms| 94ms | 2ms | 2.186
| StatusStore.UpdateLastActivityAt |  Avg| 17ms| 26ms | 9ms | 52.398
| |  P99| 111ms| 200ms | 89ms | 79.831
| SystemStore.GetByName |  Avg| 12ms| 18ms | 6ms | 51.138
| |  P99| 98ms| 177ms | 79ms | 80.811
| TeamStore.Get |  Avg| 25ms| 43ms | 18ms | 72.654
| |  P99| 238ms| 409ms | 171ms | 71.972
| TeamStore.GetAllPage |  Avg| 18ms| 26ms | 8ms | 44.509
| |  P99| 213ms| 247ms | 34ms | 15.947
| TeamStore.GetByName |  Avg| 32ms| 36ms | 4ms | 12.326
| |  P99| 321ms| 293ms | -28ms | -8.719
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 21ms| 31ms | 10ms | 47.642
| |  P99| 229ms| 281ms | 52ms | 22.696
| TeamStore.GetMember |  Avg| 8ms| 12ms | 4ms | 52.206
| |  P99| 84ms| 101ms | 17ms | 20.220
| TeamStore.GetTeamsByUserId |  Avg| 19ms| 27ms | 8ms | 41.827
| |  P99| 224ms| 247ms | 23ms | 10.258
| TeamStore.GetTeamsForUser |  Avg| 18ms| 28ms | 10ms | 54.342
| |  P99| 215ms| 256ms | 41ms | 19.093
| TeamStore.SaveMember |  Avg| 65ms| 80ms | 15ms | 23.227
| |  P99| 423ms| 478ms | 55ms | 13.014
| ThreadStore.Get |  Avg| 41ms| 47ms | 6ms | 14.544
| |  P99| 420ms| 382ms | -38ms | -9.048
| ThreadStore.GetMembershipForUser |  Avg| 32ms| 46ms | 14ms | 44.113
| |  P99| 290ms| 435ms | 145ms | 49.921
| ThreadStore.GetTeamsUnreadForUser |  Avg| 35ms| 50ms | 15ms | 43.206
| |  P99| 391ms| 485ms | 94ms | 24.018
| ThreadStore.GetThreadFollowers |  Avg| 28ms| 43ms | 15ms | 53.349
| |  P99| 240ms| 423ms | 183ms | 76.125
| ThreadStore.GetThreadForUser |  Avg| 62ms| 79ms | 17ms | 27.593
| |  P99| 470ms| 632ms | 162ms | 34.433
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 63ms| 68ms | 5ms | 7.935
| |  P99| 463ms| 475ms | 12ms | 2.594
| ThreadStore.GetThreadsForUser |  Avg| 41ms| 56ms | 15ms | 36.799
| |  P99| 369ms| 469ms | 100ms | 27.071
| ThreadStore.GetTotalThreads |  Avg| 22ms| 31ms | 9ms | 40.566
| |  P99| 239ms| 336ms | 97ms | 40.647
| ThreadStore.GetTotalUnreadMentions |  Avg| 23ms| 33ms | 10ms | 42.610
| |  P99| 241ms| 334ms | 93ms | 38.571
| ThreadStore.GetTotalUnreadThreads |  Avg| 22ms| 31ms | 9ms | 40.068
| |  P99| 238ms| 304ms | 66ms | 27.727
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 23ms| 32ms | 9ms | 39.778
| |  P99| 236ms| 335ms | 99ms | 41.883
| ThreadStore.MaintainMembership |  Avg| 37ms| 59ms | 22ms | 59.146
| |  P99| 244ms| 381ms | 137ms | 56.251
| ThreadStore.MarkAllAsReadByChannels |  Avg| 15ms| 30ms | 15ms | 98.129
| |  P99| 112ms| 206ms | 94ms | 83.681
| ThreadStore.MarkAllAsReadByTeam |  Avg| 5ms| 66ms | 61ms | 1272.557
| |  P99| 5ms| 99ms | 94ms | 1896.544
| ThreadStore.MarkAsRead |  Avg| 16ms| 25ms | 9ms | 56.936
| |  P99| 99ms| 184ms | 85ms | 85.850
| ThreadStore.UpdateMembership |  Avg| 15ms| 25ms | 10ms | 65.625
| |  P99| 99ms| 187ms | 88ms | 89.203
| TokenStore.Cleanup |  Avg| 9ms| 37ms | 28ms | 317.663
| |  P99| 25ms| 98ms | 73ms | 295.545
| UserAccessTokenStore.GetByToken |  Avg| 34ms| 51ms | 17ms | 50.278
| |  P99| 232ms| 242ms | 10ms | 4.310
| UserStore.AutocompleteUsersInChannel |  Avg| 351ms| 300ms | -51ms | -14.538
| |  P99| 2.381s| 2.167s | -214ms | -8.986
| UserStore.Count |  Avg| 53ms| 78ms | 25ms | 46.899
| |  P99| 233ms| 465ms | 232ms | 99.358
| UserStore.Get |  Avg| 19ms| 29ms | 10ms | 51.591
| |  P99| 212ms| 250ms | 38ms | 17.948
| UserStore.GetAllProfiles |  Avg| 18ms| 23ms | 5ms | 28.115
| |  P99| 215ms| 235ms | 20ms | 9.294
| UserStore.GetAllProfilesInChannel |  Avg| 918ms| 1.014s | 96ms | 10.456
| |  P99| 4.791s| 4.79s | -1ms | -0.021
| UserStore.GetByUsername |  Avg| 49ms| 41ms | -8ms | -16.229
| |  P99| 470ms| 346ms | -124ms | -26.383
| UserStore.GetForLogin |  Avg| 17ms| 23ms | 6ms | 34.971
| |  P99| 215ms| 243ms | 28ms | 13.007
| UserStore.GetMany |  Avg| 21ms| 41ms | 20ms | 96.277
| |  P99| 91ms| 417ms | 326ms | 360.220
| UserStore.GetProfileByIds |  Avg| 26ms| 40ms | 14ms | 53.830
| |  P99| 236ms| 375ms | 139ms | 58.866
| UserStore.GetProfilesByUsernames |  Avg| 31ms| 45ms | 14ms | 45.327
| |  P99| 247ms| 405ms | 158ms | 63.942
| UserStore.GetUnreadCount |  Avg| 28ms| 42ms | 14ms | 49.943
| |  P99| 236ms| 388ms | 152ms | 64.395
| UserStore.GetUnreadCountForChannel |  Avg| 27ms| 0s | -27ms | -99.598
| |  P99| 241ms| 0s | -241ms | -99.871
| UserStore.IsEmpty |  Avg| 8ms| 12ms | 4ms | 48.480
| |  P99| 98ms| 189ms | 91ms | 93.248
| UserStore.Save |  Avg| 107ms| 120ms | 13ms | 12.110
| |  P99| 470ms| 491ms | 21ms | 4.465
| UserStore.Search |  Avg| 130ms| 123ms | -7ms | -5.368
| |  P99| 1.934s| 1.388s | -546ms | -28.234
| UserStore.Update |  Avg| 41ms| 66ms | 25ms | 61.133
| |  P99| 338ms| 322ms | -16ms | -4.729
| UserStore.UpdateFailedPasswordAttempts |  Avg| 15ms| 20ms | 5ms | 34.458
| |  P99| 102ms| 172ms | 70ms | 68.726
| UserStore.UpdateUpdateAt |  Avg| 12ms| 16ms | 4ms | 32.718
| |  P99| 89ms| 117ms | 28ms | 31.548
| UserTermsOfServiceStore.GetByUser |  Avg| 18ms| 25ms | 7ms | 39.984
| |  P99| 215ms| 243ms | 28ms | 13.030
| WebhookStore.GetOutgoingByTeam |  Avg| 39ms| 52ms | 13ms | 33.149
| |  P99| 376ms| 457ms | 81ms | 21.548
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.022s| 1.537s | 515ms | 50.379
| | P99| 4.393s| 4.899s | 506ms | 11.519
| addTeamMember | Avg| 2.105s| 2.432s | 327ms | 15.531
| | P99| 9.798s| 10s | 202ms | 2.062
| autocompleteChannelsForTeamForSearch | Avg| 278ms| 261ms | -17ms | -6.116
| | P99| 1.635s| 1.255s | -380ms | -23.243
| autocompleteUsers | Avg| 296ms| 252ms | -44ms | -14.842
| | P99| 2.335s| 2.073s | -262ms | -11.222
| createChannel | Avg| 136ms| 115ms | -21ms | -15.386
| | P99| 247ms| 455ms | 208ms | 84.083
| createDirectChannel | Avg| 658ms| 1.02s | 362ms | 54.987
| | P99| 2.466s| 4.518s | 2.052s | 83.227
| createGroupChannel | Avg| 1.243s| 1.961s | 718ms | 57.760
| | P99| 4.82s| 9.1s | 4.28s | 88.803
| createPost | Avg| 3.424s| 4.702s | 1.278s | 37.328
| | P99| 9.718s| 9.935s | 217ms | 2.233
| createUser | Avg| 208ms| 239ms | 31ms | 14.873
| | P99| 980ms| 1.575s | 595ms | 60.737
| deletePost | Avg| 183ms| 331ms | 148ms | 80.672
| | P99| 489ms| 2.155s | 1.666s | 340.854
| followThreadByUser | Avg| 113ms| 176ms | 63ms | 55.700
| | P99| 453ms| 895ms | 442ms | 97.679
| getAllTeams | Avg| 20ms| 29ms | 9ms | 44.952
| | P99| 227ms| 291ms | 64ms | 28.194
| getCategoriesForTeamForUser | Avg| 70ms| 88ms | 18ms | 25.740
| | P99| 486ms| 747ms | 261ms | 53.715
| getChannel | Avg| 60ms| 88ms | 28ms | 46.707
| | P99| 595ms| 793ms | 198ms | 33.282
| getChannelMember | Avg| 49ms| 59ms | 10ms | 20.463
| | P99| 439ms| 480ms | 41ms | 9.350
| getChannelMembers | Avg| 103ms| 140ms | 37ms | 35.812
| | P99| 249ms| 247ms | -2ms | -0.805
| getChannelMembersForTeamForUser | Avg| 35ms| 50ms | 15ms | 42.423
| | P99| 320ms| 448ms | 128ms | 39.948
| getChannelStats | Avg| 36ms| 42ms | 6ms | 16.453
| | P99| 494ms| 577ms | 83ms | 16.813
| getChannelUnread | Avg| 41ms| 67ms | 26ms | 62.844
| | P99| 376ms| 494ms | 118ms | 31.361
| getChannelsForTeamForUser | Avg| 33ms| 48ms | 15ms | 45.430
| | P99| 316ms| 449ms | 133ms | 42.112
| getChannelsForUser | Avg| 39ms| 58ms | 19ms | 49.006
| | P99| 331ms| 474ms | 143ms | 43.192
| getClientConfig | Avg| 35ms| 53ms | 18ms | 51.102
| | P99| 281ms| 415ms | 134ms | 47.697
| getFilePreview | Avg| 123ms| 162ms | 39ms | 31.667
| | P99| 660ms| 909ms | 249ms | 37.748
| getFileThumbnail | Avg| 115ms| 154ms | 39ms | 33.979
| | P99| 635ms| 899ms | 264ms | 41.584
| getPostThread | Avg| 215ms| 289ms | 74ms | 34.417
| | P99| 1.966s| 2.237s | 271ms | 13.785
| getPostsForChannel | Avg| 1.245s| 658ms | -587ms | -47.140
| | P99| 10s| 6.993s | -3.007s | -30.070
| getPostsForChannelAroundLastUnread | Avg| 140ms| 159ms | 19ms | 13.590
| | P99| 1.472s| 1.7s | 228ms | 15.493
| getPreferences | Avg| 22ms| 30ms | 8ms | 35.652
| | P99| 234ms| 254ms | 20ms | 8.540
| getProfileImage | Avg| 94ms| 93ms | -1ms | -1.060
| | P99| 482ms| 493ms | 11ms | 2.281
| getPublicChannelsForTeam | Avg| 134ms| 139ms | 5ms | 3.725
| | P99| 494ms| 682ms | 188ms | 38.029
| getTeamMember | Avg| 20ms| 29ms | 9ms | 44.221
| | P99| 205ms| 228ms | 23ms | 11.196
| getTeamMembersForUser | Avg| 21ms| 32ms | 11ms | 51.302
| | P99| 233ms| 333ms | 100ms | 42.952
| getTeamsForUser | Avg| 19ms| 27ms | 8ms | 41.260
| | P99| 226ms| 250ms | 24ms | 10.597
| getTeamsUnreadForUser | Avg| 39ms| 56ms | 17ms | 43.710
| | P99| 446ms| 573ms | 127ms | 28.493
| getThreadsForUser | Avg| 43ms| 58ms | 15ms | 35.228
| | P99| 418ms| 493ms | 75ms | 17.936
| getUser | Avg| 32ms| 47ms | 15ms | 46.930
| | P99| 399ms| 472ms | 73ms | 18.290
| getUserStatus | Avg| 0s| 1ms | 1ms | 281.921
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 3ms| 5ms | 2ms | 66.943
| | P99| 69ms| 123ms | 54ms | 77.775
| getUsers | Avg| 35ms| 50ms | 15ms | 42.742
| | P99| 415ms| 470ms | 55ms | 13.262
| getUsersByIds | Avg| 5ms| 8ms | 3ms | 56.000
| | P99| 88ms| 146ms | 58ms | 65.926
| getUsersByNames | Avg| 32ms| 46ms | 14ms | 44.225
| | P99| 249ms| 416ms | 167ms | 67.058
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 215ms| 307ms | 92ms | 42.744
| | P99| 2.126s| 2.367s | 241ms | 11.335
| logout | Avg| 190ms| 465ms | 275ms | 144.416
| | P99| 490ms| 990ms | 500ms | 102.041
| patchPost | Avg| 415ms| 485ms | 70ms | 16.879
| | P99| 3.637s| 2.813s | -824ms | -22.653
| removeUserCustomStatus | Avg| 327ms| 716ms | 389ms | 118.888
| | P99| 2.01s| 2.489s | 479ms | 23.831
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 180ms| 257ms | 77ms | 42.893
| | P99| 991ms| 1.823s | 832ms | 83.940
| searchAllChannels | Avg| 256ms| 208ms | -48ms | -18.771
| | P99| 2.276s| 2.039s | -237ms | -10.413
| searchGroupChannels | Avg| 43ms| 60ms | 17ms | 39.638
| | P99| 380ms| 479ms | 99ms | 26.058
| searchPostsInTeam | Avg| 759ms| 657ms | -102ms | -13.438
| | P99| 9.958s| 8.955s | -1.003s | -10.073
| searchUsers | Avg| 133ms| 129ms | -4ms | -2.998
| | P99| 1.964s| 1.489s | -475ms | -24.183
| setPostReminder | Avg| 260ms| 324ms | 64ms | 24.610
| | P99| 2.245s| 982ms | -1.263s | -56.257
| unfollowThreadByUser | Avg| 170ms| 218ms | 48ms | 28.248
| | P99| 928ms| 946ms | 18ms | 1.939
| updateCategoriesForTeamForUser | Avg| 410ms| 648ms | 238ms | 57.994
| | P99| 4.175s| 2.439s | -1.736s | -41.578
| updatePreferences | Avg| 60ms| 102ms | 42ms | 70.302
| | P99| 435ms| 488ms | 53ms | 12.185
| updateReadStateAllThreadsByUser | Avg| 5ms| 66ms | 61ms | 1244.382
| | P99| 5ms| 99ms | 94ms | 1896.544
| updateReadStateThreadByUser | Avg| 417ms| 536ms | 119ms | 28.542
| | P99| 2.341s| 2.472s | 131ms | 5.596
| updateUserCustomStatus | Avg| 493ms| 760ms | 267ms | 54.212
| | P99| 2.373s| 4.237s | 1.864s | 78.544
| uploadFileStream | Avg| 592ms| 675ms | 83ms | 14.010
| | P99| 2.361s| 2.419s | 58ms | 2.457
| viewChannel | Avg| 150ms| 151ms | 1ms | 0.665
| | P99| 999ms| 977ms | -22ms | -2.202

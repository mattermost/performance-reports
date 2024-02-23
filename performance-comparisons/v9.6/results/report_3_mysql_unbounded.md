### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 1ms | 53ms | 52ms | 7623.36
| EmojiStore.GetMultipleByName | avg | 7ms | 94ms | 87ms | 1263.96
| DraftStore.Get | avg | 14ms | 152ms | 138ms | 1018.07
| UserStore.AnalyticsGetInactiveUsersCount | avg | 12ms | 61ms | 49ms | 414.14
| ProductNoticesStore.GetViews | avg | 46ms | 215ms | 169ms | 370.43
| LicenseStore.GetAll | avg | 20ms | 92ms | 72ms | 365.87
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 45ms | 148ms | 103ms | 226.62
| TeamStore.AnalyticsTeamCount | avg | 18ms | 57ms | 39ms | 213.86
| ProductNoticesStore.ClearOldNotices | avg | 2ms | 6ms | 4ms | 168.48
| UserStore.GetProfilesInChannel | avg | 49ms | 112ms | 63ms | 129.14
| DraftStore.Upsert | avg | 4ms | 8ms | 4ms | 102.48
| CommandWebhookStore.Cleanup | avg | 2ms | 4ms | 2ms | 96.25
| ChannelStore.AnalyticsTypeCount | avg | 26ms | 50ms | 24ms | 92.15
| PluginStore.List | avg | 33ms | 61ms | 28ms | 85.75
| DraftStore.GetDraftsForUser | avg | 54ms | 96ms | 42ms | 78.27
| PluginStore.Get | avg | 44ms | 74ms | 30ms | 67.72
| PostPersistentNotificationStore.Get | avg | 3ms | 5ms | 2ms | 63.98
| ChannelStore.GetMembersForUserWithPagination | avg | 115ms | 187ms | 72ms | 62.43
| UserStore.AnalyticsActiveCount | avg | 333ms | 511ms | 178ms | 53.49
| ThreadStore.Get | avg | 46ms | 67ms | 21ms | 45.68
| JobStore.GetCountByStatusAndType | avg | 38ms | 55ms | 17ms | 45.20
| StatusStore.UpdateExpiredDNDStatuses | avg | 8ms | 10ms | 2ms | 24.85
| BotStore.Get | avg | 46ms | 57ms | 11ms | 23.67
| UserStore.Count | avg | 210ms | 257ms | 47ms | 22.41
| ChannelStore.CreateSidebarCategory | avg | 34ms | 41ms | 7ms | 20.38
| SessionStore.GetSessionsExpired | avg | 57ms | 66ms | 9ms | 15.66
| PostStore.AnalyticsPostCount | avg | 1.469s | 1.697s | 228ms | 15.52
| PostStore.SearchPostsForUser | avg | 114ms | 131ms | 17ms | 14.86
| StatusStore.GetByIds | avg | 59ms | 67ms | 8ms | 13.49
| PostStore.Delete | avg | 69ms | 78ms | 9ms | 13.03
| ChannelStore.SearchGroupChannels | avg | 50ms | 55ms | 5ms | 9.98
| ChannelStore.Save | avg | 54ms | 59ms | 5ms | 9.29
| ReactionStore.GetForPost | avg | 57ms | 62ms | 5ms | 8.83
| PostStore.Update | avg | 23ms | 25ms | 2ms | 8.65
| ChannelStore.GetSidebarCategory | avg | 71ms | 76ms | 5ms | 7.09
| UserStore.GetProfileByIds | avg | 29ms | 31ms | 2ms | 6.79
| JobStore.GetNewestJobByStatusesAndType | avg | 37ms | 39ms | 2ms | 5.41
| ChannelStore.UpdateSidebarCategories | avg | 166ms | 170ms | 4ms | 2.41
| ChannelStore.Autocomplete | avg | 2.405s | 2.433s | 28ms | 1.16
| ChannelStore.AutocompleteInTeamForSearch | avg | 271ms | 274ms | 3ms | 1.11
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 245ms | 240ms | 4848.48
| EmojiStore.GetMultipleByName | p99 | 48ms | 248ms | 200ms | 412.37
| DraftStore.Upsert | p99 | 5ms | 25ms | 20ms | 403.86
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 49ms | 244ms | 195ms | 400.00
| PostPersistentNotificationStore.Get | p99 | 22ms | 78ms | 56ms | 249.45
| LinkMetadataStore.Save | p99 | 22ms | 72ms | 50ms | 228.31
| ChannelStore.GetSidebarCategory | p99 | 530ms | 1.48s | 950ms | 179.23
| PluginStore.List | p99 | 239ms | 655ms | 416ms | 174.13
| DraftStore.Get | p99 | 94ms | 249ms | 155ms | 164.02
| TeamStore.AnalyticsTeamCount | p99 | 97ms | 241ms | 144ms | 148.07
| ChannelStore.CreateSidebarCategory | p99 | 99ms | 242ms | 143ms | 145.18
| ChannelStore.AnalyticsTypeCount | p99 | 97ms | 235ms | 138ms | 141.54
| ChannelStore.GetMembersForUserWithPagination | p99 | 449ms | 987ms | 538ms | 119.73
| LicenseStore.GetAll | p99 | 222ms | 467ms | 245ms | 110.61
| JobStore.GetCountByStatusAndType | p99 | 490ms | 1.015s | 525ms | 107.14
| BotStore.Get | p99 | 422ms | 855ms | 433ms | 102.49
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.99
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 10ms | 5ms | 100.98
| PostStore.AnalyticsPostCount | p99 | 2.485s | 4.95s | 2.465s | 99.20
| JobStore.Save | p99 | 41ms | 81ms | 40ms | 98.46
| StatusStore.UpdateExpiredDNDStatuses | p99 | 24ms | 47ms | 23ms | 96.18
| PostStore.Delete | p99 | 246ms | 478ms | 232ms | 94.40
| SessionStore.GetSessionsExpired | p99 | 486ms | 945ms | 459ms | 94.40
| UserAccessTokenStore.GetByToken | p99 | 920ms | 1.735s | 815ms | 88.59
| StatusStore.GetByIds | p99 | 494ms | 886ms | 392ms | 79.33
| UserStore.GetByUsername | p99 | 485ms | 830ms | 345ms | 71.10
| PostStore.Update | p99 | 123ms | 196ms | 73ms | 59.23
| JobStore.UpdateStatus | p99 | 14ms | 22ms | 8ms | 56.94
| ReactionStore.GetForPost | p99 | 481ms | 737ms | 256ms | 53.21
| ComplianceStore.MessageExport | p99 | 474ms | 723ms | 249ms | 52.56
| ClusterDiscoveryStore.SetLastPingAt | p99 | 45ms | 65ms | 20ms | 44.15
| FileInfoStore.SetContent | p99 | 59ms | 80ms | 21ms | 35.72
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 478ms | 614ms | 136ms | 28.48
| PostPersistentNotificationStore.DeleteExpired | p99 | 18ms | 23ms | 5ms | 27.40
| ChannelStore.SearchGroupChannels | p99 | 500ms | 628ms | 128ms | 25.60
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 31ms | 37ms | 6ms | 19.32
| ChannelStore.Save | p99 | 413ms | 489ms | 76ms | 18.40
| JobStore.GetNewestJobByStatusesAndType | p99 | 395ms | 462ms | 67ms | 16.96
| PluginStore.Get | p99 | 410ms | 468ms | 58ms | 14.15
| SessionStore.Remove | p99 | 21ms | 24ms | 3ms | 14.12
| UserStore.AnalyticsActiveCount | p99 | 900ms | 993ms | 93ms | 10.33
| UserStore.GetProfilesInChannel | p99 | 451ms | 495ms | 44ms | 9.76
| PostPersistentNotificationStore.GetSingle | p99 | 577ms | 622ms | 45ms | 7.80
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.052s | 2.196s | 144ms | 7.02
| ThreadStore.Get | p99 | 615ms | 653ms | 38ms | 6.18
| UserStore.GetProfileByIds | p99 | 439ms | 454ms | 15ms | 3.42
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 239ms | 247ms | 8ms | 3.34
| ProductNoticesStore.GetViews | p99 | 241ms | 249ms | 8ms | 3.32
| UserStore.Get | p99 | 316ms | 325ms | 9ms | 2.84
| ChannelStore.GetChannelsByUser | p99 | 435ms | 447ms | 12ms | 2.76
| GroupStore.GetByName | p99 | 400ms | 408ms | 8ms | 2.00
| ChannelStore.Get | p99 | 792ms | 803ms | 11ms | 1.39
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 4ms | 0s | -4ms | -103.55
| PostStore.GetPostsByIds | avg | 98ms | 0s | -98ms | -100.25
| FileInfoStore.Search | avg | 110ms | 0s | -110ms | -100.22
| TeamStore.GetMany | avg | 194ms | 0s | -194ms | -99.89
| ChannelStore.GetByNameIncludeDeleted | avg | 200ms | 0s | -200ms | -99.88
| ChannelStore.GetChannelsByIds | avg | 85ms | 0s | -85ms | -99.60
| ChannelStore.GetMembers | avg | 154ms | 3ms | -151ms | -98.17
| EmojiStore.Search | avg | 6ms | 0s | -6ms | -94.12
| PostPersistentNotificationStore.UpdateLastActivity | avg | 4ms | 0s | -4ms | -90.10
| RetentionPolicyStore.GetAll | avg | 3ms | 1ms | -2ms | -63.80
| PreferenceStore.DeleteCategoryAndName | avg | 9ms | 4ms | -5ms | -55.61
| UserStore.GetMany | avg | 41ms | 20ms | -21ms | -51.75
| DraftStore.Delete | avg | 16ms | 8ms | -8ms | -50.19
| PostStore.GetPostReminderMetadata | avg | 76ms | 41ms | -35ms | -46.13
| JobStore.GetAllByTypePage | avg | 70ms | 40ms | -30ms | -43.10
| ChannelStore.GetTeamChannels | avg | 171ms | 100ms | -71ms | -41.43
| StatusStore.SaveOrUpdate | avg | 62ms | 37ms | -25ms | -40.52
| UserAccessTokenStore.GetByToken | avg | 80ms | 58ms | -22ms | -27.59
| JobStore.UpdateStatusOptimistically | avg | 8ms | 6ms | -2ms | -24.23
| ChannelStore.GetPublicChannelsForTeam | avg | 74ms | 57ms | -17ms | -22.96
| JobStore.GetAllByStatus | avg | 56ms | 44ms | -12ms | -21.27
| PostStore.GetPostReminders | avg | 10ms | 8ms | -2ms | -19.60
| PostStore.GetPostsAfter | avg | 44ms | 36ms | -8ms | -18.13
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 46ms | 39ms | -7ms | -15.28
| PreferenceStore.GetAll | avg | 55ms | 48ms | -7ms | -12.72
| FileInfoStore.GetForPost | avg | 59ms | 52ms | -7ms | -11.78
| UserTermsOfServiceStore.GetByUser | avg | 43ms | 38ms | -5ms | -11.74
| ChannelStore.GetGuestCount | avg | 77ms | 68ms | -9ms | -11.67
| TeamStore.GetAllPage | avg | 45ms | 40ms | -5ms | -11.22
| ChannelStore.GetByName | avg | 45ms | 40ms | -5ms | -11.11
| PostPriorityStore.GetForPost | avg | 46ms | 41ms | -5ms | -10.97
| UserStore.GetAllProfiles | avg | 46ms | 41ms | -5ms | -10.89
| ChannelStore.GetChannelUnread | avg | 28ms | 25ms | -3ms | -10.63
| PostStore.GetPosts | avg | 38ms | 34ms | -4ms | -10.51
| ChannelStore.SaveMember | avg | 219ms | 196ms | -23ms | -10.49
| TeamStore.GetTeamsByUserId | avg | 48ms | 43ms | -5ms | -10.45
| TeamStore.Get | avg | 49ms | 44ms | -5ms | -10.19
| ThreadStore.GetMembershipForUser | avg | 50ms | 45ms | -5ms | -10.07
| JobStore.Get | avg | 70ms | 63ms | -7ms | -10.02
| ChannelStore.CreateInitialSidebarCategories | avg | 70ms | 63ms | -7ms | -9.94
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 41ms | 37ms | -4ms | -9.68
| ThreadStore.GetThreadForUser | avg | 73ms | 66ms | -7ms | -9.62
| TeamStore.GetTeamsForUser | avg | 31ms | 28ms | -3ms | -9.58
| PostAcknowledgementStore.GetForPosts | avg | 65ms | 59ms | -6ms | -9.28
| ChannelStore.CreateDirectChannel | avg | 151ms | 137ms | -14ms | -9.27
| PostStore.GetEtag | avg | 66ms | 60ms | -6ms | -9.13
| ChannelStore.GetMemberForPost | avg | 33ms | 30ms | -3ms | -8.99
| UserStore.GetForLogin | avg | 34ms | 31ms | -3ms | -8.94
| ChannelStore.GetFileCount | avg | 34ms | 31ms | -3ms | -8.92
| PreferenceStore.Get | avg | 45ms | 41ms | -4ms | -8.91
| PostPriorityStore.GetForPosts | avg | 67ms | 61ms | -6ms | -8.90
| FileInfoStore.Get | avg | 34ms | 31ms | -3ms | -8.81
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 107ms | 98ms | -9ms | -8.39
| ThreadStore.GetThreadUnreadReplyCount | avg | 60ms | 55ms | -5ms | -8.33
| ChannelStore.GetMemberLastViewedAt | avg | 36ms | 33ms | -3ms | -8.28
| SessionStore.Get | avg | 49ms | 45ms | -4ms | -8.20
| UserStore.GetProfilesByUsernames | avg | 37ms | 34ms | -3ms | -8.09
| PostStore.GetSingle | avg | 50ms | 46ms | -4ms | -7.94
| LinkMetadataStore.Get | avg | 51ms | 47ms | -4ms | -7.81
| PostStore.GetPostsBefore | avg | 52ms | 48ms | -4ms | -7.77
| ThreadStore.GetTotalUnreadThreads | avg | 40ms | 37ms | -3ms | -7.53
| ThreadStore.GetTotalThreads | avg | 40ms | 37ms | -3ms | -7.45
| ThreadStore.GetTotalUnreadMentions | avg | 40ms | 37ms | -3ms | -7.43
| GroupStore.GetGroups | avg | 54ms | 50ms | -4ms | -7.39
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 41ms | 38ms | -3ms | -7.28
| WebhookStore.GetOutgoingByTeam | avg | 55ms | 51ms | -4ms | -7.22
| UserStore.GetUnreadCount | avg | 42ms | 39ms | -3ms | -7.15
| PostStore.GetPostsSince | avg | 72ms | 67ms | -5ms | -6.96
| TeamStore.GetChannelUnreadsForAllTeams | avg | 43ms | 40ms | -3ms | -6.95
| ChannelStore.GetMemberCount | avg | 364ms | 339ms | -25ms | -6.86
| ChannelStore.Get | avg | 92ms | 86ms | -6ms | -6.50
| ChannelStore.GetPinnedPostCount | avg | 47ms | 44ms | -3ms | -6.33
| ThreadStore.GetTeamsUnreadForUser | avg | 49ms | 46ms | -3ms | -6.08
| ChannelStore.GetMembersForUser | avg | 49ms | 46ms | -3ms | -6.07
| ChannelStore.GetChannels | avg | 51ms | 48ms | -3ms | -5.92
| ThreadStore.GetThreadFollowers | avg | 53ms | 50ms | -3ms | -5.61
| PostStore.GetPostsByThread | avg | 54ms | 51ms | -3ms | -5.53
| PostPersistentNotificationStore.GetSingle | avg | 54ms | 51ms | -3ms | -5.53
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 73ms | 69ms | -4ms | -5.51
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 38ms | 36ms | -2ms | -5.30
| ThreadStore.GetThreadsForUser | avg | 58ms | 55ms | -3ms | -5.13
| TeamStore.SaveMember | avg | 153ms | 146ms | -7ms | -4.57
| PostStore.Get | avg | 91ms | 88ms | -3ms | -3.29
| UserStore.Search | avg | 218ms | 212ms | -6ms | -2.75
| UserStore.AutocompleteUsersInChannel | avg | 437ms | 425ms | -12ms | -2.74
| UserStore.GetAllProfilesInChannel | avg | 859ms | 836ms | -23ms | -2.68
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 10ms | 0s | -10ms | -101.27
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| FileInfoStore.Search | p99 | 249ms | 0s | -249ms | -100.20
| PostStore.GetPostsByIds | p99 | 488ms | 0s | -488ms | -100.10
| TeamStore.GetMany | p99 | 494ms | 0s | -494ms | -100.05
| ChannelStore.GetByNameIncludeDeleted | p99 | 496ms | 0s | -496ms | -99.95
| ChannelStore.GetChannelsByIds | p99 | 246ms | 0s | -246ms | -99.90
| ChannelStore.GetMemberCountsByGroup | p99 | 46ms | 0s | -46ms | -99.46
| EmojiStore.Search | p99 | 24ms | 0s | -24ms | -98.97
| ChannelStore.GetMembers | p99 | 492ms | 5ms | -487ms | -98.88
| DraftStore.Delete | p99 | 238ms | 25ms | -213ms | -89.50
| ChannelStore.GetTeamChannels | p99 | 2.23s | 245ms | -1.985s | -89.01
| JobStore.GetAllByTypePage | p99 | 865ms | 240ms | -625ms | -72.26
| JobStore.UpdateStatusOptimistically | p99 | 81ms | 23ms | -58ms | -71.83
| PostStore.SetPostReminder | p99 | 214ms | 91ms | -123ms | -57.48
| RetentionPolicyStore.GetAll | p99 | 10ms | 5ms | -5ms | -50.76
| PostStore.GetPostReminderMetadata | p99 | 480ms | 239ms | -241ms | -50.21
| PreferenceStore.DeleteCategoryAndName | p99 | 46ms | 24ms | -22ms | -48.09
| UserStore.GetMany | p99 | 432ms | 230ms | -202ms | -46.71
| ChannelStore.UpdateSidebarCategories | p99 | 1.765s | 956ms | -809ms | -45.83
| PostStore.GetPostReminders | p99 | 43ms | 24ms | -19ms | -44.44
| UserStore.Count | p99 | 1.615s | 922ms | -693ms | -42.91
| StatusStore.SaveOrUpdate | p99 | 905ms | 578ms | -327ms | -36.14
| ChannelStore.GetPublicChannelsForTeam | p99 | 750ms | 495ms | -255ms | -34.00
| ThreadStore.MarkAllAsReadByChannels | p99 | 53ms | 40ms | -13ms | -24.74
| ThreadStore.GetThreadUnreadReplyCount | p99 | 699ms | 529ms | -170ms | -24.33
| TeamStore.SaveMember | p99 | 650ms | 500ms | -150ms | -23.06
| ChannelStore.GetMemberCount | p99 | 1.388s | 1.114s | -274ms | -19.74
| ChannelStore.CreateDirectChannel | p99 | 1.428s | 1.195s | -233ms | -16.32
| RoleStore.ChannelHigherScopedPermissions | p99 | 265ms | 222ms | -43ms | -16.23
| ChannelStore.GetFileCount | p99 | 428ms | 361ms | -67ms | -15.64
| ThreadStore.UpdateMembership | p99 | 53ms | 45ms | -8ms | -15.16
| PostStore.GetPostIdAfterTime | p99 | 41ms | 35ms | -6ms | -14.76
| TeamStore.GetMember | p99 | 53ms | 46ms | -7ms | -13.30
| WebhookStore.GetOutgoingByTeam | p99 | 577ms | 506ms | -71ms | -12.32
| ThreadStore.GetMembershipForUser | p99 | 554ms | 494ms | -60ms | -10.83
| JobStore.Get | p99 | 726ms | 652ms | -74ms | -10.20
| UserStore.UpdateUpdateAt | p99 | 41ms | 37ms | -4ms | -9.70
| PostStore.SearchPostsForUser | p99 | 1.187s | 1.079s | -108ms | -9.09
| PostPriorityStore.GetForPost | p99 | 495ms | 451ms | -44ms | -8.89
| SystemStore.GetByName | p99 | 34ms | 31ms | -3ms | -8.87
| PostStore.GetPostsAfter | p99 | 486ms | 443ms | -43ms | -8.85
| ChannelStore.IncrementMentionCount | p99 | 40ms | 37ms | -3ms | -7.59
| ChannelStore.GetAllChannelMembersForUser | p99 | 81ms | 75ms | -6ms | -7.41
| AuditStore.Save | p99 | 41ms | 38ms | -3ms | -7.32
| ThreadStore.GetThreadsForUser | p99 | 615ms | 570ms | -45ms | -7.31
| PostStore.Save | p99 | 139ms | 129ms | -10ms | -7.19
| PostStore.GetPostsByThread | p99 | 606ms | 563ms | -43ms | -7.10
| FileInfoStore.GetForPost | p99 | 603ms | 561ms | -42ms | -6.97
| PluginStore.SetWithOptions | p99 | 45ms | 42ms | -3ms | -6.62
| ChannelStore.GetMember | p99 | 63ms | 59ms | -4ms | -6.34
| UserStore.UpdateLastLogin | p99 | 32ms | 30ms | -2ms | -6.24
| ProductNoticesStore.View | p99 | 260ms | 244ms | -16ms | -6.17
| PostStore.GetPosts | p99 | 447ms | 422ms | -25ms | -5.59
| ChannelStore.UpdateLastViewedAt | p99 | 78ms | 74ms | -4ms | -5.11
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 41ms | 39ms | -2ms | -4.93
| JobStore.GetAllByStatus | p99 | 558ms | 531ms | -27ms | -4.83
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 460ms | 438ms | -22ms | -4.79
| UserStore.GetAllProfiles | p99 | 480ms | 458ms | -22ms | -4.58
| PostAcknowledgementStore.GetForPosts | p99 | 883ms | 844ms | -39ms | -4.42
| PostStore.GetEtag | p99 | 646ms | 618ms | -28ms | -4.34
| PostPriorityStore.GetForPosts | p99 | 905ms | 868ms | -37ms | -4.09
| PreferenceStore.GetAll | p99 | 492ms | 472ms | -20ms | -4.07
| FileInfoStore.Save | p99 | 50ms | 48ms | -2ms | -4.02
| FileInfoStore.Get | p99 | 451ms | 433ms | -18ms | -3.99
| ChannelStore.GetMemberForPost | p99 | 438ms | 421ms | -17ms | -3.88
| ChannelStore.CreateInitialSidebarCategories | p99 | 488ms | 470ms | -18ms | -3.69
| UserStore.Update | p99 | 83ms | 80ms | -3ms | -3.64
| ThreadStore.MaintainMembership | p99 | 89ms | 86ms | -3ms | -3.38
| UserStore.GetUnreadCount | p99 | 481ms | 465ms | -16ms | -3.33
| UserStore.GetProfilesByUsernames | p99 | 459ms | 444ms | -15ms | -3.27
| ChannelStore.SaveMember | p99 | 2.182s | 2.111s | -71ms | -3.25
| TeamStore.GetAllPage | p99 | 474ms | 459ms | -15ms | -3.17
| ThreadStore.GetTeamsUnreadForUser | p99 | 607ms | 588ms | -19ms | -3.13
| UserTermsOfServiceStore.GetByUser | p99 | 469ms | 455ms | -14ms | -2.99
| ThreadStore.GetTotalUnreadMentions | p99 | 470ms | 456ms | -14ms | -2.98
| ChannelStore.GetByName | p99 | 477ms | 463ms | -14ms | -2.93
| TeamStore.GetTeamsForUser | p99 | 411ms | 399ms | -12ms | -2.92
| PostStore.GetPostsSince | p99 | 587ms | 570ms | -17ms | -2.89
| PostAcknowledgementStore.GetForPost | p99 | 464ms | 451ms | -13ms | -2.80
| TeamStore.GetByName | p99 | 473ms | 460ms | -13ms | -2.75
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 468ms | 456ms | -12ms | -2.56
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 467ms | 456ms | -11ms | -2.36
| ChannelStore.GetGuestCount | p99 | 705ms | 689ms | -16ms | -2.27
| UserStore.GetForLogin | p99 | 443ms | 433ms | -10ms | -2.26
| ThreadStore.GetTotalThreads | p99 | 466ms | 456ms | -10ms | -2.14
| PreferenceStore.Save | p99 | 96ms | 94ms | -2ms | -2.08
| ChannelStore.GetMemberLastViewedAt | p99 | 445ms | 437ms | -8ms | -1.80
| SessionStore.Save | p99 | 446ms | 438ms | -8ms | -1.79
| EmojiStore.GetByName | p99 | 493ms | 486ms | -7ms | -1.42
| ThreadStore.GetThreadForUser | p99 | 866ms | 854ms | -12ms | -1.39
| ThreadStore.GetTotalUnreadThreads | p99 | 465ms | 459ms | -6ms | -1.29
| PreferenceStore.Get | p99 | 489ms | 483ms | -6ms | -1.23
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 472ms | 467ms | -5ms | -1.06
| SessionStore.Get | p99 | 481ms | 476ms | -5ms | -1.04
| PostStore.GetPostsBefore | p99 | 495ms | 490ms | -5ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 12ms | 227ms | 215ms | 1859.93
| deleteDraft | avg | 21ms | 167ms | 146ms | 686.59
| getGroupsAssociatedToChannelsByTeam | avg | 50ms | 217ms | 167ms | 333.98
| getDrafts | avg | 48ms | 190ms | 142ms | 294.41
| getPrevTrialLicense | avg | 25ms | 78ms | 53ms | 213.59
| getGroups | avg | 48ms | 122ms | 74ms | 152.73
| getSelfHostedProducts | avg | 27ms | 44ms | 17ms | 63.09
| unfollowThreadByUser | avg | 99ms | 159ms | 60ms | 60.45
| deletePost | avg | 234ms | 356ms | 122ms | 52.12
| followThreadByUser | avg | 139ms | 181ms | 42ms | 30.13
| createGroupChannel | avg | 790ms | 961ms | 171ms | 21.64
| getChannelMembersForUser | avg | 139ms | 160ms | 21ms | 15.15
| updateCategoriesForTeamForUser | avg | 340ms | 388ms | 48ms | 14.14
| searchGroupChannels | avg | 50ms | 56ms | 6ms | 11.96
| createCategoryForTeamForUser | avg | 44ms | 48ms | 4ms | 9.15
| addChannelMember | avg | 722ms | 768ms | 46ms | 6.37
| getPostThread | avg | 297ms | 305ms | 8ms | 2.69
| searchAllChannels | avg | 2.406s | 2.434s | 28ms | 1.16
| autocompleteChannelsForTeamForSearch | avg | 271ms | 274ms | 3ms | 1.11
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | p99 | 49ms | 249ms | 200ms | 405.95
| createCategoryForTeamForUser | p99 | 99ms | 242ms | 143ms | 145.18
| getAnalytics | p99 | 993ms | 2.418s | 1.425s | 143.46
| logout | p99 | 885ms | 2.125s | 1.24s | 140.11
| deletePost | p99 | 972ms | 2.23s | 1.258s | 129.47
| getChannelMembersForUser | p99 | 248ms | 485ms | 237ms | 95.72
| createGroupChannel | p99 | 4.652s | 8.033s | 3.381s | 72.67
| addChannelMember | p99 | 4.792s | 7.275s | 2.483s | 51.82
| searchGroupChannels | p99 | 500ms | 628ms | 128ms | 25.60
| getUsers | p99 | 562ms | 626ms | 64ms | 11.38
| updateCategoriesForTeamForUser | p99 | 3.775s | 4.125s | 350ms | 9.27
| deleteDraft | p99 | 230ms | 249ms | 19ms | 8.24
| getPrevTrialLicense | p99 | 228ms | 246ms | 18ms | 7.91
| getChannel | p99 | 882ms | 948ms | 66ms | 7.48
| getPostThread | p99 | 2.455s | 2.637s | 182ms | 7.41
| autocompleteChannelsForTeamForSearch | p99 | 2.052s | 2.196s | 144ms | 7.02
| saveReaction | p99 | 1.867s | 1.97s | 103ms | 5.52
| unfollowThreadByUser | p99 | 945ms | 994ms | 49ms | 5.19
| getChannelsForUser | p99 | 430ms | 449ms | 19ms | 4.42
| searchPostsInTeam | p99 | 3.359s | 3.505s | 146ms | 4.35
| followThreadByUser | p99 | 2.215s | 2.29s | 75ms | 3.39
| getGroups | p99 | 239ms | 247ms | 8ms | 3.35
| getTeamMember | p99 | 81ms | 83ms | 2ms | 2.46
| getGroupsAssociatedToChannelsByTeam | p99 | 244ms | 249ms | 5ms | 2.05
| viewChannel | p99 | 971ms | 989ms | 18ms | 1.85
| login | p99 | 1.465s | 1.49s | 25ms | 1.71
| createUser | p99 | 860ms | 872ms | 12ms | 1.39
| getDrafts | p99 | 246ms | 249ms | 3ms | 1.22
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 5ms | 0s | -5ms | -102.98
| getEnvironmentConfig | avg | 17ms | 0s | -17ms | -102.95
| searchFiles | avg | 602ms | 0s | -602ms | -99.92
| getConfig | avg | 41ms | 0s | -41ms | -99.74
| getChannelMembers | avg | 154ms | 4ms | -150ms | -97.15
| getOnboarding | avg | 5ms | 0s | -5ms | -95.97
| autocompleteEmojis | avg | 6ms | 0s | -6ms | -93.33
| root | avg | 9ms | 1ms | -8ms | -86.29
| getClientLicense | avg | 2ms | 0s | -2ms | -83.87
| patchPost | avg | 2.158s | 357ms | -1.801s | -83.47
| getFilteredUsersStats | avg | 95ms | 52ms | -43ms | -45.32
| getTeamMember | avg | 9ms | 5ms | -4ms | -44.06
| createChannel | avg | 172ms | 100ms | -72ms | -41.98
| getJobsByType | avg | 72ms | 43ms | -29ms | -40.27
| upsertDraft | avg | 15ms | 10ms | -5ms | -32.48
| setPostReminder | avg | 388ms | 266ms | -122ms | -31.44
| getPublicChannelsForTeam | avg | 75ms | 58ms | -17ms | -22.52
| getPreferences | avg | 56ms | 49ms | -7ms | -12.45
| getUsersByNames | avg | 38ms | 34ms | -4ms | -10.62
| getAllTeams | avg | 48ms | 43ms | -5ms | -10.48
| getTeamsForUser | avg | 48ms | 43ms | -5ms | -10.42
| getPostsForChannelAroundLastUnread | avg | 205ms | 184ms | -21ms | -10.24
| getPostsForChannel | avg | 400ms | 360ms | -40ms | -9.99
| getChannelUnread | avg | 31ms | 28ms | -3ms | -9.76
| getUser | avg | 56ms | 51ms | -5ms | -8.86
| getTeamMembersForUser | avg | 34ms | 31ms | -3ms | -8.80
| getCategoriesForTeamForUser | avg | 108ms | 99ms | -9ms | -8.35
| getProfileImage | avg | 98ms | 90ms | -8ms | -8.17
| getFileThumbnail | avg | 103ms | 95ms | -8ms | -7.77
| updateReadStateThreadByUser | avg | 438ms | 404ms | -34ms | -7.76
| getFilePreview | avg | 104ms | 96ms | -8ms | -7.71
| uploadFileStream | avg | 457ms | 422ms | -35ms | -7.65
| getLicenseSelfServeStatus | avg | 340ms | 314ms | -26ms | -7.65
| getAnalytics | avg | 653ms | 604ms | -49ms | -7.50
| getChannelStats | avg | 69ms | 64ms | -5ms | -7.25
| getTeamsUnreadForUser | avg | 70ms | 65ms | -5ms | -7.16
| getThreadsForUser | avg | 58ms | 54ms | -4ms | -6.90
| getChannelMembersForTeamForUser | avg | 50ms | 47ms | -3ms | -5.98
| getChannelMember | avg | 53ms | 50ms | -3ms | -5.69
| addTeamMember | avg | 2.459s | 2.329s | -130ms | -5.29
| createDirectChannel | avg | 404ms | 384ms | -20ms | -4.95
| logout | avg | 161ms | 154ms | -7ms | -4.33
| getChannelsForTeamForUser | avg | 52ms | 50ms | -2ms | -3.81
| getUsers | avg | 53ms | 51ms | -2ms | -3.81
| autocompleteUsers | avg | 357ms | 345ms | -12ms | -3.36
| saveReaction | avg | 159ms | 154ms | -5ms | -3.14
| viewChannel | avg | 99ms | 96ms | -3ms | -3.02
| createPost | avg | 1.302s | 1.271s | -31ms | -2.38
| login | avg | 185ms | 181ms | -4ms | -2.16
| removeUserCustomStatus | avg | 161ms | 158ms | -3ms | -1.87
| searchUsers | avg | 219ms | 215ms | -4ms | -1.83
| createUser | avg | 152ms | 150ms | -2ms | -1.31
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPlugins | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 56ms | 0s | -56ms | -100.90
| getEnvironmentConfig | p99 | 25ms | 0s | -25ms | -100.57
| getOnboarding | p99 | 10ms | 0s | -10ms | -100.50
| getConfig | p99 | 50ms | 0s | -50ms | -100.50
| searchFiles | p99 | 995ms | 0s | -995ms | -100.00
| autocompleteEmojis | p99 | 24ms | 0s | -24ms | -98.97
| getChannelMembers | p99 | 492ms | 5ms | -487ms | -98.88
| root | p99 | 229ms | 5ms | -224ms | -97.82
| getClientLicense | p99 | 45ms | 5ms | -40ms | -89.38
| createChannel | p99 | 2.23s | 245ms | -1.985s | -89.01
| getFilteredUsersStats | p99 | 468ms | 99ms | -369ms | -78.84
| setPostReminder | p99 | 8.8s | 2.245s | -6.555s | -74.49
| upsertDraft | p99 | 96ms | 25ms | -71ms | -74.23
| getJobsByType | p99 | 870ms | 241ms | -629ms | -72.30
| patchPost | p99 | 10s | 3.508s | -6.492s | -64.92
| getRolesByNames | p99 | 208ms | 97ms | -111ms | -53.36
| getSelfHostedProducts | p99 | 97ms | 50ms | -47ms | -48.45
| getLicenseSelfServeStatus | p99 | 936ms | 496ms | -440ms | -47.02
| uploadFileStream | p99 | 1.538s | 991ms | -547ms | -35.56
| getPublicChannelsForTeam | p99 | 750ms | 495ms | -255ms | -34.00
| getChannelStats | p99 | 1.295s | 1.18s | -115ms | -8.88
| getThreadsForUser | p99 | 678ms | 641ms | -37ms | -5.46
| getPostsForChannel | p99 | 5.176s | 4.945s | -231ms | -4.46
| getPreferences | p99 | 498ms | 476ms | -22ms | -4.42
| getFilePreview | p99 | 881ms | 846ms | -35ms | -3.97
| createDirectChannel | p99 | 2.381s | 2.287s | -94ms | -3.95
| getTeamMembersForUser | p99 | 439ms | 423ms | -16ms | -3.64
| updateReadStateThreadByUser | p99 | 4.088s | 3.952s | -136ms | -3.33
| getUsersByNames | p99 | 462ms | 448ms | -14ms | -3.03
| removeUserCustomStatus | p99 | 497ms | 482ms | -15ms | -3.02
| getFileThumbnail | p99 | 915ms | 888ms | -27ms | -2.95
| getAllTeams | p99 | 488ms | 475ms | -13ms | -2.66
| createPost | p99 | 7.914s | 7.739s | -175ms | -2.21
| getProfileImage | p99 | 476ms | 466ms | -10ms | -2.10
| getTeamsUnreadForUser | p99 | 874ms | 859ms | -15ms | -1.72
| getClientConfig | p99 | 230ms | 227ms | -3ms | -1.31
| updatePreferences | p99 | 174ms | 172ms | -2ms | -1.15
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 38ms | -3ms | -7.324
| BotStore.Get |  Avg| 46ms| 57ms | 11ms | 23.665
| |  P99| 422ms| 855ms | 433ms | 102.485
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 542ms| 540ms | -2ms | -0.369
| |  P99| 2.305s| 2.318s | 13ms | 0.564
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 5ms | -1ms | -17.988
| |  P99| 41ms| 39ms | -2ms | -4.928
| ChannelStore.AnalyticsTypeCount |  Avg| 26ms| 50ms | 24ms | 92.151
| |  P99| 97ms| 235ms | 138ms | 141.539
| ChannelStore.Autocomplete |  Avg| 2.405s| 2.433s | 28ms | 1.164
| |  P99| 9.561s| 9.583s | 22ms | 0.230
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 271ms| 274ms | 3ms | 1.108
| |  P99| 2.052s| 2.196s | 144ms | 7.019
| ChannelStore.CreateDirectChannel |  Avg| 151ms| 137ms | -14ms | -9.272
| |  P99| 1.428s| 1.195s | -233ms | -16.322
| ChannelStore.CreateInitialSidebarCategories |  Avg| 70ms| 63ms | -7ms | -9.939
| |  P99| 488ms| 470ms | -18ms | -3.689
| ChannelStore.CreateSidebarCategory |  Avg| 34ms| 41ms | 7ms | 20.385
| |  P99| 99ms| 242ms | 143ms | 145.178
| ChannelStore.Get |  Avg| 92ms| 86ms | -6ms | -6.500
| |  P99| 792ms| 803ms | 11ms | 1.389
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 73ms| 69ms | -4ms | -5.511
| |  P99| 478ms| 614ms | 136ms | 28.482
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 81ms| 75ms | -6ms | -7.406
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 166ms| 165ms | -1ms | -0.603
| ChannelStore.GetByName |  Avg| 45ms| 40ms | -5ms | -11.109
| |  P99| 477ms| 463ms | -14ms | -2.933
| ChannelStore.GetByNameIncludeDeleted |  Avg| 200ms| 0s | -200ms | -99.877
| |  P99| 496ms| 0s | -496ms | -99.950
| ChannelStore.GetChannelUnread |  Avg| 28ms| 25ms | -3ms | -10.632
| |  P99| 375ms| 372ms | -3ms | -0.800
| ChannelStore.GetChannels |  Avg| 51ms| 48ms | -3ms | -5.924
| |  P99| 497ms| 496ms | -1ms | -0.201
| ChannelStore.GetChannelsByIds |  Avg| 85ms| 0s | -85ms | -99.595
| |  P99| 246ms| 0s | -246ms | -99.898
| ChannelStore.GetChannelsByUser |  Avg| 40ms| 39ms | -1ms | -2.526
| |  P99| 435ms| 447ms | 12ms | 2.761
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 41ms| 38ms | -3ms | -7.277
| |  P99| 472ms| 467ms | -5ms | -1.060
| ChannelStore.GetFileCount |  Avg| 34ms| 31ms | -3ms | -8.921
| |  P99| 428ms| 361ms | -67ms | -15.637
| ChannelStore.GetGuestCount |  Avg| 77ms| 68ms | -9ms | -11.670
| |  P99| 705ms| 689ms | -16ms | -2.269
| ChannelStore.GetMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 63ms| 59ms | -4ms | -6.340
| ChannelStore.GetMemberCount |  Avg| 364ms| 339ms | -25ms | -6.859
| |  P99| 1.388s| 1.114s | -274ms | -19.735
| ChannelStore.GetMemberCountsByGroup |  Avg| 4ms| 0s | -4ms | -103.549
| |  P99| 46ms| 0s | -46ms | -99.456
| ChannelStore.GetMemberForPost |  Avg| 33ms| 30ms | -3ms | -8.995
| |  P99| 438ms| 421ms | -17ms | -3.881
| ChannelStore.GetMemberLastViewedAt |  Avg| 36ms| 33ms | -3ms | -8.281
| |  P99| 445ms| 437ms | -8ms | -1.797
| ChannelStore.GetMembers |  Avg| 154ms| 3ms | -151ms | -98.167
| |  P99| 492ms| 5ms | -487ms | -98.883
| ChannelStore.GetMembersForUser |  Avg| 49ms| 46ms | -3ms | -6.067
| |  P99| 490ms| 486ms | -4ms | -0.817
| ChannelStore.GetMembersForUserWithPagination |  Avg| 115ms| 187ms | 72ms | 62.434
| |  P99| 449ms| 987ms | 538ms | 119.734
| ChannelStore.GetPinnedPostCount |  Avg| 47ms| 44ms | -3ms | -6.333
| |  P99| 488ms| 486ms | -2ms | -0.409
| ChannelStore.GetPublicChannelsForTeam |  Avg| 74ms| 57ms | -17ms | -22.959
| |  P99| 750ms| 495ms | -255ms | -34.001
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 107ms| 98ms | -9ms | -8.385
| |  P99| 990ms| 986ms | -4ms | -0.404
| ChannelStore.GetSidebarCategory |  Avg| 71ms| 76ms | 5ms | 7.086
| |  P99| 530ms| 1.48s | 950ms | 179.234
| ChannelStore.GetTeamChannels |  Avg| 171ms| 100ms | -71ms | -41.432
| |  P99| 2.23s| 245ms | -1.985s | -89.013
| ChannelStore.IncrementMentionCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 37ms | -3ms | -7.592
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 54ms| 59ms | 5ms | 9.294
| |  P99| 413ms| 489ms | 76ms | 18.396
| ChannelStore.SaveMember |  Avg| 219ms| 196ms | -23ms | -10.487
| |  P99| 2.182s| 2.111s | -71ms | -3.254
| ChannelStore.SearchGroupChannels |  Avg| 50ms| 55ms | 5ms | 9.982
| |  P99| 500ms| 628ms | 128ms | 25.601
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 9ms | -1ms | -10.507
| |  P99| 78ms| 74ms | -4ms | -5.107
| ChannelStore.UpdateSidebarCategories |  Avg| 166ms| 170ms | 4ms | 2.408
| |  P99| 1.765s| 956ms | -809ms | -45.834
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 37ms | 6ms | 19.322
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 65ms | 20ms | 44.149
| CommandWebhookStore.Cleanup |  Avg| 2ms| 4ms | 2ms | 96.246
| |  P99| 5ms| 10ms | 5ms | 100.989
| ComplianceStore.MessageExport |  Avg| 43ms| 44ms | 1ms | 2.333
| |  P99| 474ms| 723ms | 249ms | 52.562
| DraftStore.Delete |  Avg| 16ms| 8ms | -8ms | -50.191
| |  P99| 238ms| 25ms | -213ms | -89.496
| DraftStore.Get |  Avg| 14ms| 152ms | 138ms | 1018.074
| |  P99| 94ms| 249ms | 155ms | 164.023
| DraftStore.GetDraftsForUser |  Avg| 54ms| 96ms | 42ms | 78.272
| |  P99| 245ms| 247ms | 2ms | 0.817
| DraftStore.Upsert |  Avg| 4ms| 8ms | 4ms | 102.478
| |  P99| 5ms| 25ms | 20ms | 403.863
| EmojiStore.GetByName |  Avg| 48ms| 47ms | -1ms | -2.065
| |  P99| 493ms| 486ms | -7ms | -1.420
| EmojiStore.GetMultipleByName |  Avg| 7ms| 94ms | 87ms | 1263.958
| |  P99| 48ms| 248ms | 200ms | 412.372
| EmojiStore.Search |  Avg| 6ms| 0s | -6ms | -94.118
| |  P99| 24ms| 0s | -24ms | -98.969
| FileInfoStore.AttachToPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.175
| FileInfoStore.Get |  Avg| 34ms| 31ms | -3ms | -8.808
| |  P99| 451ms| 433ms | -18ms | -3.993
| FileInfoStore.GetForPost |  Avg| 59ms| 52ms | -7ms | -11.776
| |  P99| 603ms| 561ms | -42ms | -6.970
| FileInfoStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 50ms| 48ms | -2ms | -4.020
| FileInfoStore.Search |  Avg| 110ms| 0s | -110ms | -100.224
| |  P99| 249ms| 0s | -249ms | -100.201
| FileInfoStore.SetContent |  Avg| 11ms| 12ms | 1ms | 8.764
| |  P99| 59ms| 80ms | 21ms | 35.722
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 46ms| 39ms | -7ms | -15.275
| |  P99| 460ms| 438ms | -22ms | -4.786
| GroupStore.GetByName |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 400ms| 408ms | 8ms | 2.001
| GroupStore.GetGroups |  Avg| 54ms| 50ms | -4ms | -7.389
| |  P99| 497ms| 498ms | 1ms | 0.201
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 45ms| 148ms | 103ms | 226.625
| |  P99| 239ms| 247ms | 8ms | 3.340
| JobStore.Get |  Avg| 70ms| 63ms | -7ms | -10.021
| |  P99| 726ms| 652ms | -74ms | -10.197
| JobStore.GetAllByStatus |  Avg| 56ms| 44ms | -12ms | -21.267
| |  P99| 558ms| 531ms | -27ms | -4.834
| JobStore.GetAllByTypePage |  Avg| 70ms| 40ms | -30ms | -43.099
| |  P99| 865ms| 240ms | -625ms | -72.256
| JobStore.GetCountByStatusAndType |  Avg| 38ms| 55ms | 17ms | 45.202
| |  P99| 490ms| 1.015s | 525ms | 107.143
| JobStore.GetNewestJobByStatusesAndType |  Avg| 37ms| 39ms | 2ms | 5.413
| |  P99| 395ms| 462ms | 67ms | 16.962
| JobStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 81ms | 40ms | 98.462
| JobStore.UpdateOptimistically |  Avg| 7ms| 8ms | 1ms | 13.465
| |  P99| 48ms| 48ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 22ms | 8ms | 56.938
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 6ms | -2ms | -24.227
| |  P99| 81ms| 23ms | -58ms | -71.826
| LicenseStore.GetAll |  Avg| 20ms| 92ms | 72ms | 365.873
| |  P99| 222ms| 467ms | 245ms | 110.608
| LinkMetadataStore.Get |  Avg| 51ms| 47ms | -4ms | -7.814
| |  P99| 495ms| 494ms | -1ms | -0.202
| LinkMetadataStore.Save |  Avg| 5ms| 6ms | 1ms | 20.767
| |  P99| 22ms| 72ms | 50ms | 228.310
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PluginStore.Get |  Avg| 44ms| 74ms | 30ms | 67.717
| |  P99| 410ms| 468ms | 58ms | 14.147
| PluginStore.List |  Avg| 33ms| 61ms | 28ms | 85.747
| |  P99| 239ms| 655ms | 416ms | 174.131
| PluginStore.SetWithOptions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 42ms | -3ms | -6.623
| PostAcknowledgementStore.GetForPost |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 464ms| 451ms | -13ms | -2.802
| PostAcknowledgementStore.GetForPosts |  Avg| 65ms| 59ms | -6ms | -9.283
| |  P99| 883ms| 844ms | -39ms | -4.416
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 23ms | 5ms | 27.399
| PostPersistentNotificationStore.Get |  Avg| 3ms| 5ms | 2ms | 63.981
| |  P99| 22ms| 78ms | 56ms | 249.448
| PostPersistentNotificationStore.GetSingle |  Avg| 54ms| 51ms | -3ms | -5.528
| |  P99| 577ms| 622ms | 45ms | 7.800
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 0s | -4ms | -90.098
| |  P99| 10ms| 0s | -10ms | -101.266
| PostPriorityStore.GetForPost |  Avg| 46ms| 41ms | -5ms | -10.972
| |  P99| 495ms| 451ms | -44ms | -8.892
| PostPriorityStore.GetForPosts |  Avg| 67ms| 61ms | -6ms | -8.903
| |  P99| 905ms| 868ms | -37ms | -4.088
| PostStore.AnalyticsPostCount |  Avg| 1.469s| 1.697s | 228ms | 15.521
| |  P99| 2.485s| 4.95s | 2.465s | 99.195
| PostStore.Delete |  Avg| 69ms| 78ms | 9ms | 13.030
| |  P99| 246ms| 478ms | 232ms | 94.405
| PostStore.Get |  Avg| 91ms| 88ms | -3ms | -3.292
| |  P99| 943ms| 938ms | -5ms | -0.530
| PostStore.GetEtag |  Avg| 66ms| 60ms | -6ms | -9.126
| |  P99| 646ms| 618ms | -28ms | -4.336
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 3ms | -1ms | -28.284
| |  P99| 41ms| 35ms | -6ms | -14.761
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.314
| PostStore.GetPostReminderMetadata |  Avg| 76ms| 41ms | -35ms | -46.129
| |  P99| 480ms| 239ms | -241ms | -50.208
| PostStore.GetPostReminders |  Avg| 10ms| 8ms | -2ms | -19.595
| |  P99| 43ms| 24ms | -19ms | -44.444
| PostStore.GetPosts |  Avg| 38ms| 34ms | -4ms | -10.511
| |  P99| 447ms| 422ms | -25ms | -5.590
| PostStore.GetPostsAfter |  Avg| 44ms| 36ms | -8ms | -18.131
| |  P99| 486ms| 443ms | -43ms | -8.853
| PostStore.GetPostsBefore |  Avg| 52ms| 48ms | -4ms | -7.767
| |  P99| 495ms| 490ms | -5ms | -1.011
| PostStore.GetPostsByIds |  Avg| 98ms| 0s | -98ms | -100.253
| |  P99| 488ms| 0s | -488ms | -100.103
| PostStore.GetPostsByThread |  Avg| 54ms| 51ms | -3ms | -5.532
| |  P99| 606ms| 563ms | -43ms | -7.095
| PostStore.GetPostsSince |  Avg| 72ms| 67ms | -5ms | -6.957
| |  P99| 587ms| 570ms | -17ms | -2.895
| PostStore.GetSingle |  Avg| 50ms| 46ms | -4ms | -7.939
| |  P99| 493ms| 492ms | -1ms | -0.203
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 139ms| 129ms | -10ms | -7.186
| PostStore.SearchPostsForUser |  Avg| 114ms| 131ms | 17ms | 14.860
| |  P99| 1.187s| 1.079s | -108ms | -9.095
| PostStore.SetPostReminder |  Avg| 13ms| 14ms | 1ms | 7.482
| |  P99| 214ms| 91ms | -123ms | -57.478
| PostStore.Update |  Avg| 23ms| 25ms | 2ms | 8.645
| |  P99| 123ms| 196ms | 73ms | 59.229
| PreferenceStore.DeleteCategoryAndName |  Avg| 9ms| 4ms | -5ms | -55.612
| |  P99| 46ms| 24ms | -22ms | -48.087
| PreferenceStore.Get |  Avg| 45ms| 41ms | -4ms | -8.906
| |  P99| 489ms| 483ms | -6ms | -1.228
| PreferenceStore.GetAll |  Avg| 55ms| 48ms | -7ms | -12.722
| |  P99| 492ms| 472ms | -20ms | -4.069
| PreferenceStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 96ms| 94ms | -2ms | -2.076
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 6ms | 4ms | 168.476
| |  P99| 5ms| 10ms | 5ms | 100.983
| ProductNoticesStore.GetViews |  Avg| 46ms| 215ms | 169ms | 370.432
| |  P99| 241ms| 249ms | 8ms | 3.320
| ProductNoticesStore.View |  Avg| 51ms| 50ms | -1ms | -1.978
| |  P99| 260ms| 244ms | -16ms | -6.166
| ReactionStore.GetForPost |  Avg| 57ms| 62ms | 5ms | 8.833
| |  P99| 481ms| 737ms | 256ms | 53.211
| RetentionPolicyStore.GetAll |  Avg| 3ms| 1ms | -2ms | -63.799
| |  P99| 10ms| 5ms | -5ms | -50.761
| RetentionPolicyStore.GetCount |  Avg| 1ms| 53ms | 52ms | 7623.355
| |  P99| 5ms| 245ms | 240ms | 4848.485
| RoleStore.ChannelHigherScopedPermissions |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 265ms| 222ms | -43ms | -16.226
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -77.769
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 49ms| 45ms | -4ms | -8.200
| |  P99| 481ms| 476ms | -5ms | -1.040
| SessionStore.GetSessionsExpired |  Avg| 57ms| 66ms | 9ms | 15.664
| |  P99| 486ms| 945ms | 459ms | 94.396
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 38ms| 36ms | -2ms | -5.302
| |  P99| 467ms| 467ms | 0s | 0.000
| SessionStore.Remove |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.117
| SessionStore.Save |  Avg| 38ms| 37ms | -1ms | -2.602
| |  P99| 446ms| 438ms | -8ms | -1.793
| SessionStore.UpdateLastActivityAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 38ms | 0s | 0.000
| StatusStore.Get |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 396ms| 395ms | -1ms | -0.252
| StatusStore.GetByIds |  Avg| 59ms| 67ms | 8ms | 13.487
| |  P99| 494ms| 886ms | 392ms | 79.326
| StatusStore.SaveOrUpdate |  Avg| 62ms| 37ms | -25ms | -40.517
| |  P99| 905ms| 578ms | -327ms | -36.139
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 10ms | 2ms | 24.850
| |  P99| 24ms| 47ms | 23ms | 96.176
| StatusStore.UpdateLastActivityAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.180
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 31ms | -3ms | -8.867
| TeamStore.AnalyticsTeamCount |  Avg| 18ms| 57ms | 39ms | 213.859
| |  P99| 97ms| 241ms | 144ms | 148.073
| TeamStore.Get |  Avg| 49ms| 44ms | -5ms | -10.192
| |  P99| 490ms| 486ms | -4ms | -0.816
| TeamStore.GetAllPage |  Avg| 45ms| 40ms | -5ms | -11.219
| |  P99| 474ms| 459ms | -15ms | -3.167
| TeamStore.GetByName |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 473ms| 460ms | -13ms | -2.748
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 43ms| 40ms | -3ms | -6.946
| |  P99| 467ms| 456ms | -11ms | -2.357
| TeamStore.GetMany |  Avg| 194ms| 0s | -194ms | -99.889
| |  P99| 494ms| 0s | -494ms | -100.051
| TeamStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 53ms| 46ms | -7ms | -13.297
| TeamStore.GetTeamsByUserId |  Avg| 48ms| 43ms | -5ms | -10.453
| |  P99| 467ms| 464ms | -3ms | -0.642
| TeamStore.GetTeamsForUser |  Avg| 31ms| 28ms | -3ms | -9.580
| |  P99| 411ms| 399ms | -12ms | -2.919
| TeamStore.SaveMember |  Avg| 153ms| 146ms | -7ms | -4.573
| |  P99| 650ms| 500ms | -150ms | -23.061
| ThreadStore.Get |  Avg| 46ms| 67ms | 21ms | 45.677
| |  P99| 615ms| 653ms | 38ms | 6.179
| ThreadStore.GetMembershipForUser |  Avg| 50ms| 45ms | -5ms | -10.074
| |  P99| 554ms| 494ms | -60ms | -10.832
| ThreadStore.GetTeamsUnreadForUser |  Avg| 49ms| 46ms | -3ms | -6.084
| |  P99| 607ms| 588ms | -19ms | -3.131
| ThreadStore.GetThreadFollowers |  Avg| 53ms| 50ms | -3ms | -5.615
| |  P99| 500ms| 499ms | -1ms | -0.200
| ThreadStore.GetThreadForUser |  Avg| 73ms| 66ms | -7ms | -9.619
| |  P99| 866ms| 854ms | -12ms | -1.386
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 60ms| 55ms | -5ms | -8.332
| |  P99| 699ms| 529ms | -170ms | -24.331
| ThreadStore.GetThreadsForUser |  Avg| 58ms| 55ms | -3ms | -5.128
| |  P99| 615ms| 570ms | -45ms | -7.312
| ThreadStore.GetTotalThreads |  Avg| 40ms| 37ms | -3ms | -7.450
| |  P99| 466ms| 456ms | -10ms | -2.144
| ThreadStore.GetTotalUnreadMentions |  Avg| 40ms| 37ms | -3ms | -7.429
| |  P99| 470ms| 456ms | -14ms | -2.977
| ThreadStore.GetTotalUnreadThreads |  Avg| 40ms| 37ms | -3ms | -7.530
| |  P99| 465ms| 459ms | -6ms | -1.290
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 41ms| 37ms | -4ms | -9.685
| |  P99| 468ms| 456ms | -12ms | -2.564
| ThreadStore.MaintainMembership |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 86ms | -3ms | -3.379
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 53ms| 40ms | -13ms | -24.742
| ThreadStore.MarkAsRead |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 53ms| 45ms | -8ms | -15.164
| TokenStore.Cleanup |  Avg| 3ms| 4ms | 1ms | 32.233
| |  P99| 10ms| 10ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 80ms| 58ms | -22ms | -27.585
| |  P99| 920ms| 1.735s | 815ms | 88.587
| UserStore.AnalyticsActiveCount |  Avg| 333ms| 511ms | 178ms | 53.493
| |  P99| 900ms| 993ms | 93ms | 10.329
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 12ms| 61ms | 49ms | 414.140
| |  P99| 49ms| 244ms | 195ms | 400.001
| UserStore.AutocompleteUsersInChannel |  Avg| 437ms| 425ms | -12ms | -2.745
| |  P99| 1.993s| 2.002s | 9ms | 0.452
| UserStore.Count |  Avg| 210ms| 257ms | 47ms | 22.413
| |  P99| 1.615s| 922ms | -693ms | -42.910
| UserStore.Get |  Avg| 16ms| 17ms | 1ms | 6.293
| |  P99| 316ms| 325ms | 9ms | 2.845
| UserStore.GetAllProfiles |  Avg| 46ms| 41ms | -5ms | -10.886
| |  P99| 480ms| 458ms | -22ms | -4.584
| UserStore.GetAllProfilesInChannel |  Avg| 859ms| 836ms | -23ms | -2.679
| |  P99| 2.465s| 2.464s | -1ms | -0.041
| UserStore.GetByUsername |  Avg| 57ms| 58ms | 1ms | 1.747
| |  P99| 485ms| 830ms | 345ms | 71.097
| UserStore.GetForLogin |  Avg| 34ms| 31ms | -3ms | -8.938
| |  P99| 443ms| 433ms | -10ms | -2.259
| UserStore.GetMany |  Avg| 41ms| 20ms | -21ms | -51.754
| |  P99| 432ms| 230ms | -202ms | -46.705
| UserStore.GetProfileByIds |  Avg| 29ms| 31ms | 2ms | 6.792
| |  P99| 439ms| 454ms | 15ms | 3.419
| UserStore.GetProfilesByUsernames |  Avg| 37ms| 34ms | -3ms | -8.091
| |  P99| 459ms| 444ms | -15ms | -3.271
| UserStore.GetProfilesInChannel |  Avg| 49ms| 112ms | 63ms | 129.144
| |  P99| 451ms| 495ms | 44ms | 9.758
| UserStore.GetUnreadCount |  Avg| 42ms| 39ms | -3ms | -7.154
| |  P99| 481ms| 465ms | -16ms | -3.326
| UserStore.IsEmpty |  Avg| 20ms| 19ms | -1ms | -5.061
| |  P99| 248ms| 249ms | 1ms | 0.403
| UserStore.Save |  Avg| 73ms| 72ms | -1ms | -1.374
| |  P99| 222ms| 220ms | -2ms | -0.901
| UserStore.Search |  Avg| 218ms| 212ms | -6ms | -2.754
| |  P99| 971ms| 967ms | -4ms | -0.412
| UserStore.Update |  Avg| 10ms| 9ms | -1ms | -10.078
| |  P99| 83ms| 80ms | -3ms | -3.636
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 6ms| 5ms | -1ms | -18.131
| |  P99| 32ms| 30ms | -2ms | -6.239
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 37ms | -4ms | -9.698
| UserTermsOfServiceStore.GetByUser |  Avg| 43ms| 38ms | -5ms | -11.736
| |  P99| 469ms| 455ms | -14ms | -2.988
| WebhookStore.GetOutgoingByTeam |  Avg| 55ms| 51ms | -4ms | -7.219
| |  P99| 577ms| 506ms | -71ms | -12.315
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 722ms| 768ms | 46ms | 6.372
| | P99| 4.792s| 7.275s | 2.483s | 51.819
| addTeamMember | Avg| 2.459s| 2.329s | -130ms | -5.287
| | P99| 9.81s| 9.734s | -76ms | -0.775
| autocompleteChannelsForTeamForSearch | Avg| 271ms| 274ms | 3ms | 1.107
| | P99| 2.052s| 2.196s | 144ms | 7.019
| autocompleteEmojis | Avg| 6ms| 0s | -6ms | -93.326
| | P99| 24ms| 0s | -24ms | -98.969
| autocompleteUsers | Avg| 357ms| 345ms | -12ms | -3.360
| | P99| 1.841s| 1.856s | 15ms | 0.815
| channelMemberCountsByGroup | Avg| 5ms| 0s | -5ms | -102.978
| | P99| 56ms| 0s | -56ms | -100.897
| createCategoryForTeamForUser | Avg| 44ms| 48ms | 4ms | 9.151
| | P99| 99ms| 242ms | 143ms | 145.178
| createChannel | Avg| 172ms| 100ms | -72ms | -41.982
| | P99| 2.23s| 245ms | -1.985s | -89.013
| createDirectChannel | Avg| 404ms| 384ms | -20ms | -4.953
| | P99| 2.381s| 2.287s | -94ms | -3.948
| createGroupChannel | Avg| 790ms| 961ms | 171ms | 21.636
| | P99| 4.652s| 8.033s | 3.381s | 72.671
| createPost | Avg| 1.302s| 1.271s | -31ms | -2.380
| | P99| 7.914s| 7.739s | -175ms | -2.211
| createUser | Avg| 152ms| 150ms | -2ms | -1.312
| | P99| 860ms| 872ms | 12ms | 1.395
| deleteDraft | Avg| 21ms| 167ms | 146ms | 686.594
| | P99| 230ms| 249ms | 19ms | 8.243
| deletePost | Avg| 234ms| 356ms | 122ms | 52.117
| | P99| 972ms| 2.23s | 1.258s | 129.468
| followThreadByUser | Avg| 139ms| 181ms | 42ms | 30.125
| | P99| 2.215s| 2.29s | 75ms | 3.386
| getAllTeams | Avg| 48ms| 43ms | -5ms | -10.482
| | P99| 488ms| 475ms | -13ms | -2.664
| getAnalytics | Avg| 653ms| 604ms | -49ms | -7.499
| | P99| 993ms| 2.418s | 1.425s | 143.456
| getCategoriesForTeamForUser | Avg| 108ms| 99ms | -9ms | -8.350
| | P99| 990ms| 989ms | -1ms | -0.101
| getChannel | Avg| 81ms| 80ms | -1ms | -1.237
| | P99| 882ms| 948ms | 66ms | 7.481
| getChannelMember | Avg| 53ms| 50ms | -3ms | -5.691
| | P99| 728ms| 724ms | -4ms | -0.549
| getChannelMembers | Avg| 154ms| 4ms | -150ms | -97.155
| | P99| 492ms| 5ms | -487ms | -98.883
| getChannelMembersForTeamForUser | Avg| 50ms| 47ms | -3ms | -5.978
| | P99| 493ms| 491ms | -2ms | -0.406
| getChannelMembersForUser | Avg| 139ms| 160ms | 21ms | 15.151
| | P99| 248ms| 485ms | 237ms | 95.719
| getChannelStats | Avg| 69ms| 64ms | -5ms | -7.254
| | P99| 1.295s| 1.18s | -115ms | -8.879
| getChannelUnread | Avg| 31ms| 28ms | -3ms | -9.759
| | P99| 417ms| 417ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 52ms| 50ms | -2ms | -3.811
| | P99| 552ms| 552ms | 0s | 0.000
| getChannelsForUser | Avg| 40ms| 39ms | -1ms | -2.481
| | P99| 430ms| 449ms | 19ms | 4.416
| getClientConfig | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 230ms| 227ms | -3ms | -1.305
| getClientLicense | Avg| 2ms| 0s | -2ms | -83.874
| | P99| 45ms| 5ms | -40ms | -89.384
| getConfig | Avg| 41ms| 0s | -41ms | -99.738
| | P99| 50ms| 0s | -50ms | -100.503
| getDrafts | Avg| 48ms| 190ms | 142ms | 294.411
| | P99| 246ms| 249ms | 3ms | 1.222
| getEnvironmentConfig | Avg| 17ms| 0s | -17ms | -102.953
| | P99| 25ms| 0s | -25ms | -100.575
| getFilePreview | Avg| 104ms| 96ms | -8ms | -7.710
| | P99| 881ms| 846ms | -35ms | -3.971
| getFileThumbnail | Avg| 103ms| 95ms | -8ms | -7.775
| | P99| 915ms| 888ms | -27ms | -2.950
| getFilteredUsersStats | Avg| 95ms| 52ms | -43ms | -45.321
| | P99| 468ms| 99ms | -369ms | -78.843
| getGroups | Avg| 48ms| 122ms | 74ms | 152.728
| | P99| 239ms| 247ms | 8ms | 3.351
| getGroupsAssociatedToChannelsByTeam | Avg| 50ms| 217ms | 167ms | 333.983
| | P99| 244ms| 249ms | 5ms | 2.049
| getJobsByType | Avg| 72ms| 43ms | -29ms | -40.270
| | P99| 870ms| 241ms | -629ms | -72.300
| getLicenseSelfServeStatus | Avg| 340ms| 314ms | -26ms | -7.649
| | P99| 936ms| 496ms | -440ms | -47.016
| getOnboarding | Avg| 5ms| 0s | -5ms | -95.965
| | P99| 10ms| 0s | -10ms | -100.503
| getPlugins | Avg| 1ms| 0s | -1ms | -180.797
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 297ms| 305ms | 8ms | 2.693
| | P99| 2.455s| 2.637s | 182ms | 7.412
| getPostsForChannel | Avg| 400ms| 360ms | -40ms | -9.989
| | P99| 5.176s| 4.945s | -231ms | -4.463
| getPostsForChannelAroundLastUnread | Avg| 205ms| 184ms | -21ms | -10.238
| | P99| 2.344s| 2.337s | -7ms | -0.299
| getPreferences | Avg| 56ms| 49ms | -7ms | -12.450
| | P99| 498ms| 476ms | -22ms | -4.416
| getPrevTrialLicense | Avg| 25ms| 78ms | 53ms | 213.586
| | P99| 228ms| 246ms | 18ms | 7.912
| getProductNotices | Avg| 12ms| 227ms | 215ms | 1859.929
| | P99| 49ms| 249ms | 200ms | 405.952
| getProfileImage | Avg| 98ms| 90ms | -8ms | -8.166
| | P99| 476ms| 466ms | -10ms | -2.101
| getPublicChannelsForTeam | Avg| 75ms| 58ms | -17ms | -22.525
| | P99| 750ms| 495ms | -255ms | -34.001
| getRolesByNames | Avg| 14ms| 15ms | 1ms | 7.250
| | P99| 208ms| 97ms | -111ms | -53.364
| getSelfHostedProducts | Avg| 27ms| 44ms | 17ms | 63.092
| | P99| 97ms| 50ms | -47ms | -48.454
| getTeamMember | Avg| 9ms| 5ms | -4ms | -44.057
| | P99| 81ms| 83ms | 2ms | 2.461
| getTeamMembersForUser | Avg| 34ms| 31ms | -3ms | -8.796
| | P99| 439ms| 423ms | -16ms | -3.641
| getTeamsForUser | Avg| 48ms| 43ms | -5ms | -10.421
| | P99| 468ms| 465ms | -3ms | -0.641
| getTeamsUnreadForUser | Avg| 70ms| 65ms | -5ms | -7.158
| | P99| 874ms| 859ms | -15ms | -1.716
| getThreadsForUser | Avg| 58ms| 54ms | -4ms | -6.902
| | P99| 678ms| 641ms | -37ms | -5.459
| getUser | Avg| 56ms| 51ms | -5ms | -8.861
| | P99| 524ms| 520ms | -4ms | -0.764
| getUserLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 53ms| 51ms | -2ms | -3.809
| | P99| 562ms| 626ms | 64ms | 11.384
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 97ms| 97ms | 0s | 0.000
| getUsersByNames | Avg| 38ms| 34ms | -4ms | -10.621
| | P99| 462ms| 448ms | -14ms | -3.031
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 185ms| 181ms | -4ms | -2.157
| | P99| 1.465s| 1.49s | 25ms | 1.707
| logout | Avg| 161ms| 154ms | -7ms | -4.335
| | P99| 885ms| 2.125s | 1.24s | 140.110
| patchPost | Avg| 2.158s| 357ms | -1.801s | -83.468
| | P99| 10s| 3.508s | -6.492s | -64.920
| removeUserCustomStatus | Avg| 161ms| 158ms | -3ms | -1.865
| | P99| 497ms| 482ms | -15ms | -3.021
| root | Avg| 9ms| 1ms | -8ms | -86.286
| | P99| 229ms| 5ms | -224ms | -97.817
| saveReaction | Avg| 159ms| 154ms | -5ms | -3.138
| | P99| 1.867s| 1.97s | 103ms | 5.517
| searchAllChannels | Avg| 2.406s| 2.434s | 28ms | 1.164
| | P99| 9.561s| 9.583s | 22ms | 0.230
| searchFiles | Avg| 602ms| 0s | -602ms | -99.919
| | P99| 995ms| 0s | -995ms | -100.000
| searchGroupChannels | Avg| 50ms| 56ms | 6ms | 11.956
| | P99| 500ms| 628ms | 128ms | 25.601
| searchPostsInTeam | Avg| 240ms| 238ms | -2ms | -0.834
| | P99| 3.359s| 3.505s | 146ms | 4.346
| searchUsers | Avg| 219ms| 215ms | -4ms | -1.827
| | P99| 971ms| 969ms | -2ms | -0.206
| setPostReminder | Avg| 388ms| 266ms | -122ms | -31.439
| | P99| 8.8s| 2.245s | -6.555s | -74.490
| unfollowThreadByUser | Avg| 99ms| 159ms | 60ms | 60.445
| | P99| 945ms| 994ms | 49ms | 5.185
| updateCategoriesForTeamForUser | Avg| 340ms| 388ms | 48ms | 14.136
| | P99| 3.775s| 4.125s | 350ms | 9.271
| updatePreferences | Avg| 16ms| 17ms | 1ms | 6.251
| | P99| 174ms| 172ms | -2ms | -1.147
| updateReadStateThreadByUser | Avg| 438ms| 404ms | -34ms | -7.765
| | P99| 4.088s| 3.952s | -136ms | -3.327
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 457ms| 422ms | -35ms | -7.653
| | P99| 1.538s| 991ms | -547ms | -35.559
| upsertDraft | Avg| 15ms| 10ms | -5ms | -32.480
| | P99| 96ms| 25ms | -71ms | -74.228
| viewChannel | Avg| 99ms| 96ms | -3ms | -3.016
| | P99| 971ms| 989ms | 18ms | 1.854

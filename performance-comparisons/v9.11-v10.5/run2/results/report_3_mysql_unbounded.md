### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 65ms | 65ms | 9283252.23
| CommandWebhookStore.Cleanup | avg | 3ms | 10ms | 7ms | 233.00
| SessionStore.GetSessionsExpired | avg | 24ms | 77ms | 53ms | 217.76
| TokenStore.Cleanup | avg | 4ms | 12ms | 8ms | 213.12
| DesktopTokensStore.DeleteOlderThan | avg | 3ms | 8ms | 5ms | 185.38
| ChannelStore.GetMembers | avg | 28ms | 69ms | 41ms | 148.01
| TeamStore.GetMember | avg | 4ms | 10ms | 6ms | 142.13
| StatusStore.Get | avg | 15ms | 31ms | 16ms | 107.79
| JobStore.UpdateStatusOptimistically | avg | 10ms | 21ms | 11ms | 105.18
| UserStore.GetProfilesInChannel | avg | 44ms | 86ms | 42ms | 94.46
| UserStore.Get | avg | 13ms | 24ms | 11ms | 85.82
| ThreadStore.MarkAllAsReadByTeam | avg | 12ms | 20ms | 8ms | 65.82
| ChannelStore.GetSidebarCategory | avg | 37ms | 59ms | 22ms | 59.69
| ChannelStore.GetAllChannelMembersForUser | avg | 16ms | 25ms | 9ms | 54.73
| DraftStore.GetDraftsForUser | avg | 32ms | 47ms | 15ms | 46.85
| UserStore.Count | avg | 147ms | 212ms | 65ms | 44.08
| StatusStore.GetByIds | avg | 33ms | 47ms | 14ms | 42.05
| PostStore.SetPostReminder | avg | 20ms | 28ms | 8ms | 39.50
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 18ms | 25ms | 7ms | 38.51
| JobStore.GetAllByStatus | avg | 29ms | 40ms | 11ms | 37.58
| UserStore.GetMany | avg | 16ms | 22ms | 6ms | 36.52
| ChannelStore.GetMemberLastViewedAt | avg | 14ms | 19ms | 5ms | 34.54
| PreferenceStore.GetAll | avg | 24ms | 32ms | 8ms | 32.73
| UserStore.GetProfileByIds | avg | 22ms | 29ms | 7ms | 32.49
| ChannelStore.SearchGroupChannels | avg | 34ms | 45ms | 11ms | 32.38
| ChannelStore.AutocompleteInTeamForSearch | avg | 172ms | 227ms | 55ms | 31.99
| ChannelStore.GetGuestCount | avg | 31ms | 41ms | 10ms | 31.92
| ChannelStore.GetMembersForUserWithPagination | avg | 19ms | 25ms | 6ms | 31.43
| ThreadStore.GetTeamsUnreadForUser | avg | 26ms | 34ms | 8ms | 30.77
| GroupStore.GetByName | avg | 16ms | 21ms | 5ms | 30.53
| TeamStore.GetTeamsByUserId | avg | 20ms | 26ms | 6ms | 30.22
| TeamStore.GetChannelUnreadsForAllTeams | avg | 20ms | 26ms | 6ms | 29.43
| UserStore.IsEmpty | avg | 10ms | 13ms | 3ms | 29.43
| PostPriorityStore.GetForPosts | avg | 34ms | 44ms | 10ms | 29.09
| JobStore.GetCountByStatusAndType | avg | 35ms | 45ms | 10ms | 28.46
| ChannelStore.GetChannelsByUser | avg | 18ms | 23ms | 5ms | 28.00
| PostAcknowledgementStore.GetForPosts | avg | 32ms | 41ms | 9ms | 27.99
| ReactionStore.GetForPost | avg | 25ms | 32ms | 7ms | 27.96
| ChannelStore.GetByName | avg | 22ms | 28ms | 6ms | 27.60
| ThreadStore.GetMembershipForUser | avg | 26ms | 33ms | 7ms | 27.08
| ClusterDiscoveryStore.SetLastPingAt | avg | 12ms | 15ms | 3ms | 25.87
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 16ms | 20ms | 4ms | 25.52
| ThreadStore.GetTotalUnreadMentions | avg | 20ms | 25ms | 5ms | 25.31
| TeamStore.GetAllPage | avg | 20ms | 25ms | 5ms | 25.27
| ThreadStore.GetTotalThreads | avg | 20ms | 25ms | 5ms | 25.01
| ChannelStore.GetChannels | avg | 32ms | 40ms | 8ms | 24.95
| ThreadStore.GetTotalUnreadThreads | avg | 20ms | 25ms | 5ms | 24.91
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 20ms | 25ms | 5ms | 24.81
| ThreadStore.GetThreadsForUser | avg | 33ms | 41ms | 8ms | 24.38
| FileInfoStore.GetByIds | avg | 33ms | 41ms | 8ms | 24.29
| ChannelStore.GetPublicChannelsForTeam | avg | 46ms | 57ms | 11ms | 24.15
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 50ms | 62ms | 12ms | 23.91
| ChannelStore.GetMembersForUser | avg | 29ms | 36ms | 7ms | 23.82
| UserStore.GetAllProfiles | avg | 17ms | 21ms | 4ms | 23.59
| ThreadStore.GetThreadForUser | avg | 34ms | 42ms | 8ms | 23.56
| EmojiStore.GetByName | avg | 26ms | 32ms | 6ms | 23.51
| TeamStore.Get | avg | 21ms | 26ms | 5ms | 23.44
| ThreadStore.Get | avg | 30ms | 37ms | 7ms | 23.00
| PostStore.GetPostsByThread | avg | 26ms | 32ms | 6ms | 22.70
| PostStore.GetSingle | avg | 22ms | 27ms | 5ms | 22.41
| ChannelStore.GetMemberForPost | avg | 36ms | 44ms | 8ms | 22.40
| PostStore.GetEtag | avg | 32ms | 39ms | 7ms | 22.10
| DraftStore.Get | avg | 37ms | 45ms | 8ms | 21.88
| WebhookStore.GetOutgoingByTeam | avg | 32ms | 39ms | 7ms | 21.88
| ChannelStore.Get | avg | 60ms | 73ms | 13ms | 21.82
| GroupStore.GetGroups | avg | 28ms | 34ms | 6ms | 21.79
| ThreadStore.GetThreadFollowers | avg | 28ms | 34ms | 6ms | 21.69
| ChannelStore.SaveMember | avg | 98ms | 119ms | 21ms | 21.52
| ChannelStore.Save | avg | 58ms | 70ms | 12ms | 20.84
| TeamStore.GetTeamsForUser | avg | 19ms | 23ms | 4ms | 20.72
| PostPersistentNotificationStore.GetSingle | avg | 29ms | 35ms | 6ms | 20.53
| PostStore.GetPostsBefore | avg | 29ms | 35ms | 6ms | 20.47
| PostStore.GetPosts | avg | 15ms | 18ms | 3ms | 20.42
| PostStore.Get | avg | 56ms | 67ms | 11ms | 19.72
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 36ms | 43ms | 7ms | 19.62
| UserTermsOfServiceStore.GetByUser | avg | 21ms | 25ms | 4ms | 19.50
| FileInfoStore.GetForPost | avg | 32ms | 38ms | 6ms | 18.73
| UserStore.GetUnreadCount | avg | 22ms | 26ms | 4ms | 18.55
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 49ms | 58ms | 9ms | 18.31
| ChannelStore.GetPinnedPostCount | avg | 28ms | 33ms | 5ms | 17.85
| FileInfoStore.Get | avg | 22ms | 26ms | 4ms | 17.81
| PostStore.GetPostsSince | avg | 46ms | 54ms | 8ms | 17.31
| ChannelStore.GetFileCount | avg | 24ms | 28ms | 4ms | 16.90
| LinkMetadataStore.Get | avg | 24ms | 28ms | 4ms | 16.89
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 24ms | 28ms | 4ms | 16.89
| UserStore.GetProfilesByUsernames | avg | 25ms | 29ms | 4ms | 15.73
| UserStore.GetForLogin | avg | 19ms | 22ms | 3ms | 15.66
| PreferenceStore.Get | avg | 27ms | 31ms | 4ms | 14.62
| PostAcknowledgementStore.GetForPost | avg | 22ms | 25ms | 3ms | 13.67
| UserStore.GetByUsername | avg | 30ms | 34ms | 4ms | 13.15
| ThreadStore.GetThreadUnreadReplyCount | avg | 31ms | 35ms | 4ms | 12.81
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 16ms | 18ms | 2ms | 12.55
| UserStore.Search | avg | 96ms | 108ms | 12ms | 12.44
| PostPriorityStore.GetForPost | avg | 26ms | 29ms | 3ms | 11.34
| ChannelStore.CreateInitialSidebarCategories | avg | 51ms | 56ms | 5ms | 9.90
| PreferenceStore.Save | avg | 22ms | 24ms | 2ms | 8.89
| TeamStore.SaveMember | avg | 106ms | 115ms | 9ms | 8.49
| PostStore.SearchPostsForUser | avg | 73ms | 79ms | 6ms | 8.25
| UserStore.AutocompleteUsersInChannel | avg | 325ms | 348ms | 23ms | 7.07
| PostStore.GetPostsAfter | avg | 30ms | 32ms | 2ms | 6.72
| SessionStore.Get | avg | 31ms | 33ms | 2ms | 6.45
| UserStore.GetAllProfilesInChannel | avg | 638ms | 664ms | 26ms | 4.08
| ChannelStore.CreateDirectChannel | avg | 111ms | 115ms | 4ms | 3.61
| ChannelStore.GetMemberCount | avg | 212ms | 219ms | 7ms | 3.30
| ChannelStore.GetTeamChannels | avg | 73ms | 75ms | 2ms | 2.73
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 245ms | 240ms | 4848.45
| SessionStore.GetSessionsExpired | p99 | 238ms | 2.2s | 1.962s | 824.37
| CommandWebhookStore.Cleanup | p99 | 10ms | 49ms | 39ms | 402.05
| UserStore.GetProfilesInChannel | p99 | 440ms | 1.96s | 1.52s | 345.44
| UserStore.Count | p99 | 488ms | 2.11s | 1.622s | 332.04
| TeamStore.GetMember | p99 | 44ms | 190ms | 146ms | 328.44
| TokenStore.Cleanup | p99 | 24ms | 97ms | 73ms | 302.90
| PostStore.SetPostReminder | p99 | 96ms | 370ms | 274ms | 286.61
| ChannelStore.GetSidebarCategory | p99 | 247ms | 730ms | 483ms | 195.83
| ThreadStore.MarkAllAsReadByTeam | p99 | 96ms | 230ms | 134ms | 140.31
| UserStore.GetMany | p99 | 97ms | 226ms | 129ms | 132.79
| JobStore.UpdateStatusOptimistically | p99 | 99ms | 212ms | 113ms | 114.41
| ClusterDiscoveryStore.SetLastPingAt | p99 | 98ms | 203ms | 105ms | 107.58
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.AutocompleteInTeamForSearch | p99 | 973ms | 1.935s | 962ms | 98.87
| LinkMetadataStore.Save | p99 | 77ms | 146ms | 69ms | 89.61
| ChannelStore.CreateSidebarCategory | p99 | 248ms | 468ms | 220ms | 88.89
| StatusStore.Get | p99 | 234ms | 439ms | 205ms | 87.70
| UserStore.Get | p99 | 229ms | 379ms | 150ms | 65.58
| ChannelStore.SaveMember | p99 | 985ms | 1.609s | 624ms | 63.34
| ChannelStore.GetPublicChannelsForTeam | p99 | 454ms | 741ms | 287ms | 63.18
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 248ms | 402ms | 154ms | 62.00
| ChannelStore.GetAllChannelMembersForUser | p99 | 213ms | 333ms | 120ms | 56.28
| ThreadStore.Get | p99 | 366ms | 570ms | 204ms | 55.80
| PostPriorityStore.GetForPosts | p99 | 495ms | 757ms | 262ms | 52.95
| ChannelStore.GetMembersForUserWithPagination | p99 | 247ms | 377ms | 130ms | 52.69
| PostAcknowledgementStore.GetForPosts | p99 | 485ms | 732ms | 247ms | 50.93
| DraftStore.GetDraftsForUser | p99 | 416ms | 627ms | 211ms | 50.74
| UserStore.AutocompleteUsersInChannel | p99 | 987ms | 1.464s | 477ms | 48.32
| ChannelStore.Get | p99 | 490ms | 726ms | 236ms | 48.20
| FileInfoStore.Save | p99 | 98ms | 145ms | 47ms | 47.74
| TeamStore.GetAllPage | p99 | 261ms | 380ms | 119ms | 45.54
| ReactionStore.GetForPost | p99 | 307ms | 445ms | 138ms | 44.88
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 268ms | 387ms | 119ms | 44.35
| TeamStore.GetTeamsByUserId | p99 | 274ms | 395ms | 121ms | 44.18
| ChannelStore.GetChannelsByUser | p99 | 244ms | 348ms | 104ms | 42.70
| ChannelStore.GetByName | p99 | 278ms | 396ms | 118ms | 42.43
| GroupStore.GetByName | p99 | 241ms | 339ms | 98ms | 40.65
| UserStore.GetAllProfiles | p99 | 238ms | 332ms | 94ms | 39.51
| UserStore.GetUnreadCount | p99 | 291ms | 406ms | 115ms | 39.46
| TeamStore.GetTeamsForUser | p99 | 260ms | 357ms | 97ms | 37.31
| FileInfoStore.GetByIds | p99 | 446ms | 611ms | 165ms | 37.00
| ThreadStore.GetTotalUnreadMentions | p99 | 288ms | 390ms | 102ms | 35.40
| ChannelStore.SearchGroupChannels | p99 | 426ms | 576ms | 150ms | 35.25
| PostStore.SearchPostsForUser | p99 | 588ms | 795ms | 207ms | 35.22
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 292ms | 393ms | 101ms | 34.56
| ThreadStore.GetTotalUnreadThreads | p99 | 289ms | 388ms | 99ms | 34.22
| ThreadStore.GetThreadForUser | p99 | 469ms | 627ms | 158ms | 33.70
| UserStore.GetProfileByIds | p99 | 308ms | 407ms | 99ms | 32.14
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 241ms | 318ms | 77ms | 31.94
| ThreadStore.GetTotalThreads | p99 | 301ms | 397ms | 96ms | 31.92
| PostStore.Get | p99 | 645ms | 844ms | 199ms | 30.87
| TeamStore.Get | p99 | 316ms | 410ms | 94ms | 29.74
| PreferenceStore.GetAll | p99 | 336ms | 433ms | 97ms | 28.89
| PostStore.GetSingle | p99 | 321ms | 413ms | 92ms | 28.65
| UserTermsOfServiceStore.GetByUser | p99 | 307ms | 391ms | 84ms | 27.38
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 395ms | 497ms | 102ms | 25.81
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 324ms | 407ms | 83ms | 25.61
| ChannelStore.GetFileCount | p99 | 244ms | 305ms | 61ms | 24.99
| PostStore.GetPostsByThread | p99 | 365ms | 455ms | 90ms | 24.65
| UserStore.GetForLogin | p99 | 269ms | 335ms | 66ms | 24.56
| LinkMetadataStore.Get | p99 | 340ms | 422ms | 82ms | 24.12
| EmojiStore.GetByName | p99 | 358ms | 443ms | 85ms | 23.72
| FileInfoStore.Get | p99 | 306ms | 378ms | 72ms | 23.56
| ThreadStore.GetTeamsUnreadForUser | p99 | 401ms | 491ms | 90ms | 22.42
| ChannelStore.GetMemberLastViewedAt | p99 | 235ms | 285ms | 50ms | 21.30
| UserStore.IsEmpty | p99 | 193ms | 234ms | 41ms | 21.28
| ThreadStore.GetMembershipForUser | p99 | 377ms | 455ms | 78ms | 20.71
| JobStore.GetCountByStatusAndType | p99 | 410ms | 491ms | 81ms | 19.76
| UserStore.GetProfilesByUsernames | p99 | 336ms | 401ms | 65ms | 19.37
| ChannelStore.GetChannelUnread | p99 | 347ms | 414ms | 67ms | 19.31
| GroupStore.GetGroups | p99 | 384ms | 458ms | 74ms | 19.25
| UserStore.GetByUsername | p99 | 413ms | 490ms | 77ms | 18.64
| ChannelStore.GetMembersForUser | p99 | 391ms | 462ms | 71ms | 18.17
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 750ms | 883ms | 133ms | 17.74
| SessionStore.Remove | p99 | 47ms | 55ms | 8ms | 17.08
| PostStore.GetEtag | p99 | 403ms | 471ms | 68ms | 16.87
| PostStore.GetPostsAfter | p99 | 392ms | 458ms | 66ms | 16.82
| UserStore.UpdateLastLogin | p99 | 57ms | 66ms | 9ms | 15.87
| ThreadStore.GetThreadsForUser | p99 | 416ms | 481ms | 65ms | 15.64
| PostStore.GetPostsBefore | p99 | 381ms | 440ms | 59ms | 15.48
| ThreadStore.GetThreadFollowers | p99 | 394ms | 454ms | 60ms | 15.24
| WebhookStore.GetOutgoingByTeam | p99 | 407ms | 469ms | 62ms | 15.24
| PreferenceStore.Get | p99 | 381ms | 437ms | 56ms | 14.69
| ChannelStore.GetGuestCount | p99 | 423ms | 485ms | 62ms | 14.66
| ChannelStore.Save | p99 | 461ms | 528ms | 67ms | 14.52
| PostPersistentNotificationStore.GetSingle | p99 | 418ms | 473ms | 55ms | 13.16
| ChannelStore.GetChannels | p99 | 422ms | 477ms | 55ms | 13.04
| JobStore.GetAllByStatus | p99 | 413ms | 466ms | 53ms | 12.83
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 71ms | 80ms | 9ms | 12.73
| ChannelStore.GetMemberForPost | p99 | 443ms | 495ms | 52ms | 11.74
| PostStore.GetPostReminders | p99 | 193ms | 215ms | 22ms | 11.40
| SessionStore.UpdateLastActivityAt | p99 | 72ms | 80ms | 8ms | 11.16
| ChannelStore.GetPinnedPostCount | p99 | 406ms | 450ms | 44ms | 10.84
| UserStore.UpdateFailedPasswordAttempts | p99 | 75ms | 83ms | 8ms | 10.71
| PostStore.GetPostsSince | p99 | 432ms | 478ms | 46ms | 10.64
| UserStore.Search | p99 | 806ms | 891ms | 85ms | 10.54
| StatusStore.GetByIds | p99 | 447ms | 494ms | 47ms | 10.51
| ThreadStore.GetThreadUnreadReplyCount | p99 | 417ms | 459ms | 42ms | 10.08
| DraftStore.Get | p99 | 448ms | 492ms | 44ms | 9.83
| PostStore.GetPosts | p99 | 225ms | 246ms | 21ms | 9.31
| JobStore.UpdateOptimistically | p99 | 43ms | 47ms | 4ms | 9.21
| SessionStore.GetLRUSessions | p99 | 299ms | 326ms | 27ms | 9.02
| SessionStore.Save | p99 | 305ms | 332ms | 27ms | 8.84
| SessionStore.Get | p99 | 382ms | 415ms | 33ms | 8.64
| PreferenceStore.DeleteCategoryAndName | p99 | 205ms | 221ms | 16ms | 7.80
| ChannelStore.CreateInitialSidebarCategories | p99 | 439ms | 472ms | 33ms | 7.52
| SystemStore.GetByName | p99 | 68ms | 73ms | 5ms | 7.31
| DraftStore.Upsert | p99 | 98ms | 105ms | 7ms | 7.14
| PluginStore.SetWithOptions | p99 | 86ms | 92ms | 6ms | 6.98
| FileInfoStore.GetForPost | p99 | 445ms | 475ms | 30ms | 6.74
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 238ms | 254ms | 16ms | 6.72
| ThreadStore.UpdateMembership | p99 | 85ms | 90ms | 5ms | 5.88
| PostPriorityStore.GetForPost | p99 | 452ms | 478ms | 26ms | 5.76
| PreferenceStore.Save | p99 | 214ms | 226ms | 12ms | 5.61
| TeamStore.SaveMember | p99 | 461ms | 486ms | 25ms | 5.42
| ThreadStore.MarkAsRead | p99 | 76ms | 80ms | 4ms | 5.29
| ChannelStore.IncrementMentionCount | p99 | 84ms | 88ms | 4ms | 4.78
| PluginStore.Delete | p99 | 43ms | 45ms | 2ms | 4.64
| ChannelStore.GetMember | p99 | 91ms | 95ms | 4ms | 4.38
| StatusStore.UpdateLastActivityAt | p99 | 85ms | 88ms | 3ms | 3.52
| UserStore.Update | p99 | 207ms | 214ms | 7ms | 3.38
| ThreadStore.MaintainMembership | p99 | 188ms | 194ms | 6ms | 3.20
| ChannelStore.GetMemberCount | p99 | 933ms | 962ms | 29ms | 3.11
| UserStore.UpdateUpdateAt | p99 | 66ms | 68ms | 2ms | 3.03
| AuditStore.Save | p99 | 80ms | 82ms | 2ms | 2.49
| ChannelStore.CreateDirectChannel | p99 | 949ms | 972ms | 23ms | 2.42
| PostStore.GetPostIdBeforeTime | p99 | 87ms | 89ms | 2ms | 2.29
| UserStore.GetAllProfilesInChannel | p99 | 2.404s | 2.43s | 26ms | 1.08
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 36ms | 0s | -36ms | -99.99
| JobStore.Get | avg | 26ms | 0s | -26ms | -98.12
| StatusStore.UpdateExpiredDNDStatuses | avg | 31ms | 11ms | -20ms | -64.62
| RoleStore.ChannelHigherScopedPermissions | avg | 64ms | 27ms | -37ms | -58.24
| ChannelStore.UpdateSidebarCategories | avg | 153ms | 70ms | -83ms | -54.39
| PostPersistentNotificationStore.Get | avg | 8ms | 4ms | -4ms | -50.69
| ChannelStore.CreateSidebarCategory | avg | 125ms | 63ms | -62ms | -49.75
| PostStore.Delete | avg | 102ms | 53ms | -49ms | -48.26
| StatusStore.SaveOrUpdate | avg | 42ms | 23ms | -19ms | -45.56
| UserStore.GetProfilesNotInChannel | avg | 48ms | 32ms | -16ms | -33.17
| UserAccessTokenStore.GetByToken | avg | 21ms | 14ms | -7ms | -32.82
| BotStore.Get | avg | 41ms | 31ms | -10ms | -24.22
| JobStore.UpdateStatus | avg | 8ms | 6ms | -2ms | -23.65
| SessionStore.Remove | avg | 9ms | 7ms | -2ms | -23.24
| JobStore.Save | avg | 9ms | 7ms | -2ms | -23.11
| ThreadStore.MarkAllAsReadByChannels | avg | 10ms | 8ms | -2ms | -20.14
| TeamStore.GetActiveMemberCount | avg | 288ms | 235ms | -53ms | -18.43
| PostStore.GetPostReminders | avg | 24ms | 20ms | -4ms | -16.93
| TeamStore.GetTotalMemberCount | avg | 227ms | 189ms | -38ms | -16.73
| PostStore.GetPostReminderMetadata | avg | 26ms | 22ms | -4ms | -15.20
| PluginStore.List | avg | 29ms | 25ms | -4ms | -13.93
| FileInfoStore.SetContent | avg | 19ms | 17ms | -2ms | -10.45
| JobStore.GetNewestJobByStatusesAndType | avg | 33ms | 30ms | -3ms | -8.99
| PostStore.AnalyticsPostCount | avg | 1.522s | 1.407s | -115ms | -7.56
| EmojiStore.GetMultipleByName | avg | 42ms | 40ms | -2ms | -4.73
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.Get | p99 | 369ms | 0s | -369ms | -100.07
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 409ms | 0s | -409ms | -100.01
| StatusStore.UpdateExpiredDNDStatuses | p99 | 405ms | 44ms | -361ms | -89.14
| RoleStore.ChannelHigherScopedPermissions | p99 | 390ms | 99ms | -291ms | -74.61
| ChannelStore.UpdateSidebarCategories | p99 | 1.465s | 446ms | -1.019s | -69.55
| JobStore.UpdateStatus | p99 | 98ms | 39ms | -59ms | -60.49
| PostStore.Delete | p99 | 850ms | 403ms | -447ms | -52.59
| PostPersistentNotificationStore.Get | p99 | 84ms | 40ms | -44ms | -52.22
| StatusStore.SaveOrUpdate | p99 | 807ms | 399ms | -408ms | -50.53
| FileInfoStore.SetContent | p99 | 195ms | 99ms | -96ms | -49.34
| PostPersistentNotificationStore.DeleteExpired | p99 | 42ms | 22ms | -20ms | -47.48
| BotStore.Get | p99 | 805ms | 439ms | -366ms | -45.47
| UserAccessTokenStore.GetByToken | p99 | 380ms | 221ms | -159ms | -41.84
| PluginStore.List | p99 | 402ms | 265ms | -137ms | -34.04
| PostStore.GetPostReminderMetadata | p99 | 285ms | 225ms | -60ms | -21.05
| ThreadStore.MarkAllAsReadByChannels | p99 | 116ms | 92ms | -24ms | -20.62
| JobStore.GetNewestJobByStatusesAndType | p99 | 492ms | 443ms | -49ms | -9.96
| ChannelStore.GetTeamChannels | p99 | 474ms | 427ms | -47ms | -9.92
| EmojiStore.GetMultipleByName | p99 | 242ms | 235ms | -7ms | -2.89
| UserStore.GetProfilesNotInChannel | p99 | 242ms | 236ms | -6ms | -2.48
| DraftStore.Delete | p99 | 96ms | 94ms | -2ms | -2.08
| TeamStore.GetActiveMemberCount | p99 | 947ms | 930ms | -17ms | -1.79
| FileInfoStore.AttachToPost | p99 | 140ms | 138ms | -2ms | -1.43
| TeamStore.GetTotalMemberCount | p99 | 493ms | 488ms | -5ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 28ms | 89ms | 61ms | 215.80
| viewChannel | avg | 73ms | 120ms | 47ms | 64.57
| setPostReminder | avg | 118ms | 182ms | 64ms | 54.15
| followThreadByUser | avg | 68ms | 102ms | 34ms | 49.97
| getUsers | avg | 17ms | 25ms | 8ms | 46.71
| getUser | avg | 26ms | 38ms | 12ms | 45.69
| getDrafts | avg | 34ms | 49ms | 15ms | 43.71
| createChannel | avg | 703ms | 947ms | 244ms | 34.70
| getPostsForChannel | avg | 238ms | 315ms | 77ms | 32.35
| searchGroupChannels | avg | 34ms | 45ms | 11ms | 32.12
| autocompleteChannelsForTeamForSearch | avg | 172ms | 227ms | 55ms | 31.95
| getChannelMembersForUser | avg | 19ms | 25ms | 6ms | 31.09
| getTeamsForUser | avg | 20ms | 26ms | 6ms | 29.95
| getPreferences | avg | 25ms | 32ms | 7ms | 28.02
| getChannelsForUser | avg | 18ms | 23ms | 5ms | 27.69
| updateReadStateThreadByUser | avg | 238ms | 301ms | 63ms | 26.50
| updateReadStateAllThreadsByUser | avg | 16ms | 20ms | 4ms | 25.42
| getCategoriesForTeamForUser | avg | 51ms | 64ms | 13ms | 25.25
| getChannelsForTeamForUser | avg | 32ms | 40ms | 8ms | 24.71
| saveReaction | avg | 89ms | 111ms | 22ms | 24.69
| getThreadsForUser | avg | 33ms | 41ms | 8ms | 24.54
| getChannelMembersForTeamForUser | avg | 30ms | 37ms | 7ms | 23.60
| getTeamsUnreadForUser | avg | 39ms | 48ms | 9ms | 23.35
| getPostsForChannelAroundLastUnread | avg | 86ms | 106ms | 20ms | 23.34
| getPublicChannelsForTeam | avg | 47ms | 58ms | 11ms | 23.23
| getAllTeams | avg | 22ms | 27ms | 5ms | 22.72
| deleteDraft | avg | 37ms | 45ms | 8ms | 21.44
| getPostThread | avg | 163ms | 196ms | 33ms | 20.31
| getTeamMembersForUser | avg | 21ms | 25ms | 4ms | 19.29
| removeUserCustomStatus | avg | 281ms | 326ms | 45ms | 16.03
| getUsersByNames | avg | 26ms | 30ms | 4ms | 15.29
| upsertDraft | avg | 22ms | 25ms | 3ms | 13.77
| searchPostsInTeam | avg | 127ms | 144ms | 17ms | 13.34
| searchUsers | avg | 98ms | 111ms | 13ms | 13.22
| unfollowThreadByUser | avg | 95ms | 107ms | 12ms | 12.62
| listChannelBookmarksForChannel | avg | 19ms | 21ms | 2ms | 10.63
| getFileThumbnail | avg | 66ms | 70ms | 4ms | 6.10
| getFilePreview | avg | 72ms | 76ms | 4ms | 5.54
| addChannelMember | avg | 664ms | 696ms | 32ms | 4.82
| autocompleteUsers | avg | 279ms | 292ms | 13ms | 4.65
| addTeamMember | avg | 1.717s | 1.787s | 70ms | 4.08
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 248ms | 935ms | 687ms | 276.88
| createChannel | p99 | 2.421s | 8.55s | 6.129s | 253.13
| removeUserCustomStatus | p99 | 964ms | 2.395s | 1.431s | 148.42
| updateReadStateAllThreadsByUser | p99 | 96ms | 230ms | 134ms | 140.31
| viewChannel | p99 | 781ms | 1.824s | 1.043s | 133.58
| autocompleteChannelsForTeamForSearch | p99 | 973ms | 1.935s | 962ms | 98.87
| getChannelMembers | p99 | 244ms | 475ms | 231ms | 94.67
| followThreadByUser | p99 | 469ms | 909ms | 440ms | 93.74
| getPublicChannelsForTeam | p99 | 457ms | 741ms | 284ms | 62.10
| autocompleteUsers | p99 | 993ms | 1.609s | 616ms | 62.02
| saveReaction | p99 | 957ms | 1.533s | 576ms | 60.18
| getUsers | p99 | 243ms | 384ms | 141ms | 58.12
| getChannelMembersForUser | p99 | 247ms | 378ms | 131ms | 53.00
| getDrafts | p99 | 441ms | 673ms | 232ms | 52.64
| getTeamsForUser | p99 | 275ms | 395ms | 120ms | 43.57
| getChannelsForUser | p99 | 244ms | 349ms | 105ms | 43.03
| updateReadStateThreadByUser | p99 | 2.369s | 3.37s | 1.001s | 42.25
| getTeamsUnreadForUser | p99 | 554ms | 786ms | 232ms | 41.86
| getPostsForChannelAroundLastUnread | p99 | 1.318s | 1.841s | 523ms | 39.69
| searchGroupChannels | p99 | 426ms | 576ms | 150ms | 35.18
| getUserStatusesByIds | p99 | 24ms | 32ms | 8ms | 33.35
| getUser | p99 | 377ms | 483ms | 106ms | 28.08
| upsertDraft | p99 | 292ms | 373ms | 81ms | 27.71
| getAllTeams | p99 | 318ms | 405ms | 87ms | 27.37
| getPostsForChannel | p99 | 3.8s | 4.82s | 1.02s | 26.84
| getPreferences | p99 | 346ms | 438ms | 92ms | 26.62
| getTeamMembersForUser | p99 | 300ms | 377ms | 77ms | 25.63
| listChannelBookmarksForChannel | p99 | 311ms | 368ms | 57ms | 18.32
| getChannelMembersForTeamForUser | p99 | 392ms | 462ms | 70ms | 17.84
| getUsersByNames | p99 | 347ms | 407ms | 60ms | 17.31
| getCategoriesForTeamForUser | p99 | 762ms | 889ms | 127ms | 16.66
| searchPostsInTeam | p99 | 1.889s | 2.183s | 294ms | 15.57
| getThreadsForUser | p99 | 431ms | 498ms | 67ms | 15.54
| createUser | p99 | 1.673s | 1.919s | 246ms | 14.70
| getChannelStats | p99 | 574ms | 658ms | 84ms | 14.63
| getUsersByIds | p99 | 76ms | 87ms | 11ms | 14.56
| updatePreferences | p99 | 249ms | 283ms | 34ms | 13.66
| getChannelsForTeamForUser | p99 | 423ms | 477ms | 54ms | 12.76
| getChannel | p99 | 926ms | 1.024s | 98ms | 10.58
| searchUsers | p99 | 812ms | 897ms | 85ms | 10.46
| getPostThread | p99 | 2.139s | 2.353s | 214ms | 10.00
| deleteDraft | p99 | 449ms | 493ms | 44ms | 9.80
| createPost | p99 | 4.78s | 5.233s | 453ms | 9.48
| addTeamMember | p99 | 8.766s | 9.532s | 766ms | 8.74
| createGroupChannel | p99 | 4.454s | 4.726s | 272ms | 6.11
| getFileThumbnail | p99 | 464ms | 488ms | 24ms | 5.17
| getChannelUnread | p99 | 426ms | 446ms | 20ms | 4.69
| getFilePreview | p99 | 466ms | 485ms | 19ms | 4.08
| addChannelMember | p99 | 4.68s | 4.837s | 157ms | 3.35
| getChannelMember | p99 | 473ms | 487ms | 14ms | 2.96
| setPostReminder | p99 | 945ms | 967ms | 22ms | 2.33
| getTeamMember | p99 | 156ms | 158ms | 2ms | 1.28
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | avg | 6ms | 0s | -6ms | -99.83
| createCategoryForTeamForUser | avg | 175ms | 99ms | -76ms | -43.48
| login | avg | 247ms | 141ms | -106ms | -43.00
| logout | avg | 138ms | 97ms | -41ms | -29.71
| deletePost | avg | 217ms | 154ms | -63ms | -29.03
| getTeamStats | avg | 325ms | 248ms | -77ms | -23.67
| updateCategoriesForTeamForUser | avg | 260ms | 214ms | -46ms | -17.71
| getProfileImage | avg | 84ms | 71ms | -13ms | -15.54
| createDirectChannel | avg | 608ms | 527ms | -81ms | -13.33
| createPost | avg | 951ms | 844ms | -107ms | -11.26
| getChannel | avg | 79ms | 71ms | -8ms | -10.16
| getChannelUnread | avg | 34ms | 32ms | -2ms | -5.93
| createUser | avg | 275ms | 264ms | -11ms | -3.99
| uploadFileStream | avg | 555ms | 538ms | -17ms | -3.06
| createGroupChannel | avg | 965ms | 939ms | -26ms | -2.69
| patchPost | avg | 242ms | 237ms | -5ms | -2.07
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| updateUserCustomStatus | p99 | 20ms | 5ms | -15ms | -75.65
| login | p99 | 2.209s | 1.059s | -1.15s | -52.07
| unfollowThreadByUser | p99 | 1.18s | 969ms | -211ms | -17.88
| updateCategoriesForTeamForUser | p99 | 2.293s | 2.095s | -198ms | -8.63
| logout | p99 | 484ms | 444ms | -40ms | -8.26
| patchPost | p99 | 2.675s | 2.46s | -215ms | -8.04
| deletePost | p99 | 2.05s | 1.915s | -135ms | -6.59
| getProfileImage | p99 | 477ms | 460ms | -17ms | -3.57
| uploadFileStream | p99 | 2.175s | 2.107s | -68ms | -3.13
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 82ms | 2ms | 2.487
| BotStore.Get |  Avg| 41ms| 31ms | -10ms | -24.219
| |  P99| 805ms| 439ms | -366ms | -45.466
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 16ms| 18ms | 2ms | 12.553
| |  P99| 238ms| 254ms | 16ms | 6.720
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 64ms| 63ms | -1ms | -1.563
| ChannelStore.Autocomplete |  Avg| 1.408s| 1.399s | -9ms | -0.639
| |  P99| 4.842s| 4.848s | 6ms | 0.124
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 172ms| 227ms | 55ms | 31.986
| |  P99| 973ms| 1.935s | 962ms | 98.871
| ChannelStore.CreateDirectChannel |  Avg| 111ms| 115ms | 4ms | 3.608
| |  P99| 949ms| 972ms | 23ms | 2.424
| ChannelStore.CreateInitialSidebarCategories |  Avg| 51ms| 56ms | 5ms | 9.899
| |  P99| 439ms| 472ms | 33ms | 7.524
| ChannelStore.CreateSidebarCategory |  Avg| 125ms| 63ms | -62ms | -49.749
| |  P99| 248ms| 468ms | 220ms | 88.889
| ChannelStore.Get |  Avg| 60ms| 73ms | 13ms | 21.821
| |  P99| 490ms| 726ms | 236ms | 48.203
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 36ms| 0s | -36ms | -99.986
| |  P99| 409ms| 0s | -409ms | -100.009
| ChannelStore.GetAllChannelMembersForUser |  Avg| 16ms| 25ms | 9ms | 54.728
| |  P99| 213ms| 333ms | 120ms | 56.284
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 36ms| 43ms | 7ms | 19.622
| |  P99| 395ms| 497ms | 102ms | 25.812
| ChannelStore.GetByName |  Avg| 22ms| 28ms | 6ms | 27.599
| |  P99| 278ms| 396ms | 118ms | 42.427
| ChannelStore.GetChannelUnread |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 347ms| 414ms | 67ms | 19.311
| ChannelStore.GetChannels |  Avg| 32ms| 40ms | 8ms | 24.950
| |  P99| 422ms| 477ms | 55ms | 13.036
| ChannelStore.GetChannelsByUser |  Avg| 18ms| 23ms | 5ms | 27.996
| |  P99| 244ms| 348ms | 104ms | 42.705
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 24ms| 28ms | 4ms | 16.889
| |  P99| 324ms| 407ms | 83ms | 25.608
| ChannelStore.GetFileCount |  Avg| 24ms| 28ms | 4ms | 16.896
| |  P99| 244ms| 305ms | 61ms | 24.992
| ChannelStore.GetGuestCount |  Avg| 31ms| 41ms | 10ms | 31.921
| |  P99| 423ms| 485ms | 62ms | 14.660
| ChannelStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 95ms | 4ms | 4.383
| ChannelStore.GetMemberCount |  Avg| 212ms| 219ms | 7ms | 3.302
| |  P99| 933ms| 962ms | 29ms | 3.107
| ChannelStore.GetMemberForPost |  Avg| 36ms| 44ms | 8ms | 22.402
| |  P99| 443ms| 495ms | 52ms | 11.740
| ChannelStore.GetMemberLastViewedAt |  Avg| 14ms| 19ms | 5ms | 34.541
| |  P99| 235ms| 285ms | 50ms | 21.303
| ChannelStore.GetMembers |  Avg| 28ms| 69ms | 41ms | 148.013
| |  P99| 244ms| 246ms | 2ms | 0.820
| ChannelStore.GetMembersForUser |  Avg| 29ms| 36ms | 7ms | 23.820
| |  P99| 391ms| 462ms | 71ms | 18.173
| ChannelStore.GetMembersForUserWithPagination |  Avg| 19ms| 25ms | 6ms | 31.425
| |  P99| 247ms| 377ms | 130ms | 52.686
| ChannelStore.GetPinnedPostCount |  Avg| 28ms| 33ms | 5ms | 17.850
| |  P99| 406ms| 450ms | 44ms | 10.836
| ChannelStore.GetPublicChannelsForTeam |  Avg| 46ms| 57ms | 11ms | 24.147
| |  P99| 454ms| 741ms | 287ms | 63.178
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 50ms| 62ms | 12ms | 23.908
| |  P99| 750ms| 883ms | 133ms | 17.744
| ChannelStore.GetSidebarCategory |  Avg| 37ms| 59ms | 22ms | 59.690
| |  P99| 247ms| 730ms | 483ms | 195.825
| ChannelStore.GetTeamChannels |  Avg| 73ms| 75ms | 2ms | 2.732
| |  P99| 474ms| 427ms | -47ms | -9.921
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 88ms | 4ms | 4.775
| ChannelStore.Save |  Avg| 58ms| 70ms | 12ms | 20.843
| |  P99| 461ms| 528ms | 67ms | 14.519
| ChannelStore.SaveMember |  Avg| 98ms| 119ms | 21ms | 21.515
| |  P99| 985ms| 1.609s | 624ms | 63.336
| ChannelStore.SearchGroupChannels |  Avg| 34ms| 45ms | 11ms | 32.383
| |  P99| 426ms| 576ms | 150ms | 35.246
| ChannelStore.UpdateLastViewedAt |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 158ms| 159ms | 1ms | 0.632
| ChannelStore.UpdateSidebarCategories |  Avg| 153ms| 70ms | -83ms | -54.387
| |  P99| 1.465s| 446ms | -1.019s | -69.549
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 7ms | 1ms | 15.746
| |  P99| 71ms| 80ms | 9ms | 12.731
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 15ms | 3ms | 25.870
| |  P99| 98ms| 203ms | 105ms | 107.577
| CommandWebhookStore.Cleanup |  Avg| 3ms| 10ms | 7ms | 232.998
| |  P99| 10ms| 49ms | 39ms | 402.052
| DesktopTokensStore.DeleteOlderThan |  Avg| 3ms| 8ms | 5ms | 185.382
| |  P99| 5ms| 10ms | 5ms | 101.010
| DraftStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 94ms | -2ms | -2.079
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 49ms| 58ms | 9ms | 18.306
| |  P99| 235ms| 235ms | 0s | 0.000
| DraftStore.Get |  Avg| 37ms| 45ms | 8ms | 21.882
| |  P99| 448ms| 492ms | 44ms | 9.827
| DraftStore.GetDraftsForUser |  Avg| 32ms| 47ms | 15ms | 46.846
| |  P99| 416ms| 627ms | 211ms | 50.744
| DraftStore.Upsert |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 105ms | 7ms | 7.138
| EmojiStore.GetByName |  Avg| 26ms| 32ms | 6ms | 23.515
| |  P99| 358ms| 443ms | 85ms | 23.723
| EmojiStore.GetMultipleByName |  Avg| 42ms| 40ms | -2ms | -4.732
| |  P99| 242ms| 235ms | -7ms | -2.893
| FileInfoStore.AttachToPost |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 140ms| 138ms | -2ms | -1.425
| FileInfoStore.Get |  Avg| 22ms| 26ms | 4ms | 17.809
| |  P99| 306ms| 378ms | 72ms | 23.555
| FileInfoStore.GetByIds |  Avg| 33ms| 41ms | 8ms | 24.289
| |  P99| 446ms| 611ms | 165ms | 37.002
| FileInfoStore.GetForPost |  Avg| 32ms| 38ms | 6ms | 18.734
| |  P99| 445ms| 475ms | 30ms | 6.739
| FileInfoStore.Save |  Avg| 12ms| 13ms | 1ms | 8.560
| |  P99| 98ms| 145ms | 47ms | 47.738
| FileInfoStore.SetContent |  Avg| 19ms| 17ms | -2ms | -10.454
| |  P99| 195ms| 99ms | -96ms | -49.335
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 16ms| 20ms | 4ms | 25.518
| |  P99| 241ms| 318ms | 77ms | 31.936
| GroupStore.GetByName |  Avg| 16ms| 21ms | 5ms | 30.533
| |  P99| 241ms| 339ms | 98ms | 40.653
| GroupStore.GetGroups |  Avg| 28ms| 34ms | 6ms | 21.790
| |  P99| 384ms| 458ms | 74ms | 19.252
| JobStore.Get |  Avg| 26ms| 0s | -26ms | -98.121
| |  P99| 369ms| 0s | -369ms | -100.066
| JobStore.GetAllByStatus |  Avg| 29ms| 40ms | 11ms | 37.584
| |  P99| 413ms| 466ms | 53ms | 12.830
| JobStore.GetCountByStatusAndType |  Avg| 35ms| 45ms | 10ms | 28.461
| |  P99| 410ms| 491ms | 81ms | 19.756
| JobStore.GetNewestJobByStatusesAndType |  Avg| 33ms| 30ms | -3ms | -8.991
| |  P99| 492ms| 443ms | -49ms | -9.959
| JobStore.Save |  Avg| 9ms| 7ms | -2ms | -23.108
| |  P99| 50ms| 49ms | -1ms | -2.010
| JobStore.UpdateOptimistically |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 43ms| 47ms | 4ms | 9.208
| JobStore.UpdateStatus |  Avg| 8ms| 6ms | -2ms | -23.654
| |  P99| 98ms| 39ms | -59ms | -60.495
| JobStore.UpdateStatusOptimistically |  Avg| 10ms| 21ms | 11ms | 105.184
| |  P99| 99ms| 212ms | 113ms | 114.414
| LinkMetadataStore.Get |  Avg| 24ms| 28ms | 4ms | 16.893
| |  P99| 340ms| 422ms | 82ms | 24.117
| LinkMetadataStore.Save |  Avg| 8ms| 7ms | -1ms | -12.158
| |  P99| 77ms| 146ms | 69ms | 89.607
| PluginStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.643
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -87.057
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 29ms| 25ms | -4ms | -13.925
| |  P99| 402ms| 265ms | -137ms | -34.037
| PluginStore.SetWithOptions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 86ms| 92ms | 6ms | 6.983
| PostAcknowledgementStore.GetForPost |  Avg| 22ms| 25ms | 3ms | 13.674
| |  P99| 412ms| 410ms | -2ms | -0.486
| PostAcknowledgementStore.GetForPosts |  Avg| 32ms| 41ms | 9ms | 27.988
| |  P99| 485ms| 732ms | 247ms | 50.932
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 4ms | -1ms | -19.391
| |  P99| 42ms| 22ms | -20ms | -47.477
| PostPersistentNotificationStore.Get |  Avg| 8ms| 4ms | -4ms | -50.690
| |  P99| 84ms| 40ms | -44ms | -52.225
| PostPersistentNotificationStore.GetSingle |  Avg| 29ms| 35ms | 6ms | 20.529
| |  P99| 418ms| 473ms | 55ms | 13.158
| PostPriorityStore.GetForPost |  Avg| 26ms| 29ms | 3ms | 11.336
| |  P99| 452ms| 478ms | 26ms | 5.757
| PostPriorityStore.GetForPosts |  Avg| 34ms| 44ms | 10ms | 29.093
| |  P99| 495ms| 757ms | 262ms | 52.945
| PostStore.AnalyticsPostCount |  Avg| 1.522s| 1.407s | -115ms | -7.556
| |  P99| 2.485s| 2.485s | 0s | 0.000
| PostStore.Delete |  Avg| 102ms| 53ms | -49ms | -48.260
| |  P99| 850ms| 403ms | -447ms | -52.591
| PostStore.Get |  Avg| 56ms| 67ms | 11ms | 19.715
| |  P99| 645ms| 844ms | 199ms | 30.873
| PostStore.GetEtag |  Avg| 32ms| 39ms | 7ms | 22.096
| |  P99| 403ms| 471ms | 68ms | 16.872
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 5ms | -1ms | -17.942
| |  P99| 66ms| 67ms | 1ms | 1.506
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 89ms | 2ms | 2.295
| PostStore.GetPostReminderMetadata |  Avg| 26ms| 22ms | -4ms | -15.197
| |  P99| 285ms| 225ms | -60ms | -21.054
| PostStore.GetPostReminders |  Avg| 24ms| 20ms | -4ms | -16.927
| |  P99| 193ms| 215ms | 22ms | 11.399
| PostStore.GetPosts |  Avg| 15ms| 18ms | 3ms | 20.422
| |  P99| 225ms| 246ms | 21ms | 9.314
| PostStore.GetPostsAfter |  Avg| 30ms| 32ms | 2ms | 6.718
| |  P99| 392ms| 458ms | 66ms | 16.816
| PostStore.GetPostsBefore |  Avg| 29ms| 35ms | 6ms | 20.473
| |  P99| 381ms| 440ms | 59ms | 15.478
| PostStore.GetPostsByThread |  Avg| 26ms| 32ms | 6ms | 22.698
| |  P99| 365ms| 455ms | 90ms | 24.648
| PostStore.GetPostsSince |  Avg| 46ms| 54ms | 8ms | 17.305
| |  P99| 432ms| 478ms | 46ms | 10.639
| PostStore.GetSingle |  Avg| 22ms| 27ms | 5ms | 22.414
| |  P99| 321ms| 413ms | 92ms | 28.654
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 30ms| 31ms | 1ms | 3.332
| |  P99| 240ms| 241ms | 1ms | 0.417
| PostStore.SearchPostsForUser |  Avg| 73ms| 79ms | 6ms | 8.246
| |  P99| 588ms| 795ms | 207ms | 35.216
| PostStore.SetPostReminder |  Avg| 20ms| 28ms | 8ms | 39.496
| |  P99| 96ms| 370ms | 274ms | 286.612
| PostStore.Update |  Avg| 30ms| 31ms | 1ms | 3.318
| |  P99| 214ms| 214ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 14ms| 13ms | -1ms | -7.042
| |  P99| 205ms| 221ms | 16ms | 7.805
| PreferenceStore.Get |  Avg| 27ms| 31ms | 4ms | 14.624
| |  P99| 381ms| 437ms | 56ms | 14.688
| PreferenceStore.GetAll |  Avg| 24ms| 32ms | 8ms | 32.731
| |  P99| 336ms| 433ms | 97ms | 28.888
| PreferenceStore.Save |  Avg| 22ms| 24ms | 2ms | 8.893
| |  P99| 214ms| 226ms | 12ms | 5.612
| ProductNoticesStore.ClearOldNotices |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 442ms| 440ms | -2ms | -0.453
| ReactionStore.GetForPost |  Avg| 25ms| 32ms | 7ms | 27.960
| |  P99| 307ms| 445ms | 138ms | 44.879
| RoleStore.ChannelHigherScopedPermissions |  Avg| 64ms| 27ms | -37ms | -58.239
| |  P99| 390ms| 99ms | -291ms | -74.605
| RoleStore.GetByNames |  Avg| 0s| 65ms | 65ms | 9283252.234
| |  P99| 5ms| 245ms | 240ms | 4848.450
| SessionStore.Get |  Avg| 31ms| 33ms | 2ms | 6.452
| |  P99| 382ms| 415ms | 33ms | 8.637
| SessionStore.GetLRUSessions |  Avg| 20ms| 21ms | 1ms | 4.903
| |  P99| 299ms| 326ms | 27ms | 9.025
| SessionStore.GetSessionsExpired |  Avg| 24ms| 77ms | 53ms | 217.757
| |  P99| 238ms| 2.2s | 1.962s | 824.367
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 18ms| 25ms | 7ms | 38.513
| |  P99| 248ms| 402ms | 154ms | 61.999
| SessionStore.Remove |  Avg| 9ms| 7ms | -2ms | -23.241
| |  P99| 47ms| 55ms | 8ms | 17.082
| SessionStore.Save |  Avg| 25ms| 26ms | 1ms | 3.935
| |  P99| 305ms| 332ms | 27ms | 8.845
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 9ms | 1ms | 12.113
| |  P99| 72ms| 80ms | 8ms | 11.155
| StatusStore.Get |  Avg| 15ms| 31ms | 16ms | 107.794
| |  P99| 234ms| 439ms | 205ms | 87.700
| StatusStore.GetByIds |  Avg| 33ms| 47ms | 14ms | 42.054
| |  P99| 447ms| 494ms | 47ms | 10.513
| StatusStore.SaveOrUpdate |  Avg| 42ms| 23ms | -19ms | -45.562
| |  P99| 807ms| 399ms | -408ms | -50.527
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 31ms| 11ms | -20ms | -64.619
| |  P99| 405ms| 44ms | -361ms | -89.136
| StatusStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 85ms| 88ms | 3ms | 3.523
| SystemStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 68ms| 73ms | 5ms | 7.310
| TeamStore.Get |  Avg| 21ms| 26ms | 5ms | 23.439
| |  P99| 316ms| 410ms | 94ms | 29.741
| TeamStore.GetActiveMemberCount |  Avg| 288ms| 235ms | -53ms | -18.433
| |  P99| 947ms| 930ms | -17ms | -1.794
| TeamStore.GetAllPage |  Avg| 20ms| 25ms | 5ms | 25.272
| |  P99| 261ms| 380ms | 119ms | 45.537
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 20ms| 26ms | 6ms | 29.431
| |  P99| 268ms| 387ms | 119ms | 44.346
| TeamStore.GetMember |  Avg| 4ms| 10ms | 6ms | 142.129
| |  P99| 44ms| 190ms | 146ms | 328.438
| TeamStore.GetTeamsByUserId |  Avg| 20ms| 26ms | 6ms | 30.217
| |  P99| 274ms| 395ms | 121ms | 44.180
| TeamStore.GetTeamsForUser |  Avg| 19ms| 23ms | 4ms | 20.715
| |  P99| 260ms| 357ms | 97ms | 37.310
| TeamStore.GetTotalMemberCount |  Avg| 227ms| 189ms | -38ms | -16.728
| |  P99| 493ms| 488ms | -5ms | -1.013
| TeamStore.SaveMember |  Avg| 106ms| 115ms | 9ms | 8.489
| |  P99| 461ms| 486ms | 25ms | 5.419
| ThreadStore.Get |  Avg| 30ms| 37ms | 7ms | 23.002
| |  P99| 366ms| 570ms | 204ms | 55.796
| ThreadStore.GetMembershipForUser |  Avg| 26ms| 33ms | 7ms | 27.080
| |  P99| 377ms| 455ms | 78ms | 20.711
| ThreadStore.GetTeamsUnreadForUser |  Avg| 26ms| 34ms | 8ms | 30.769
| |  P99| 401ms| 491ms | 90ms | 22.420
| ThreadStore.GetThreadFollowers |  Avg| 28ms| 34ms | 6ms | 21.689
| |  P99| 394ms| 454ms | 60ms | 15.242
| ThreadStore.GetThreadForUser |  Avg| 34ms| 42ms | 8ms | 23.557
| |  P99| 469ms| 627ms | 158ms | 33.700
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 31ms| 35ms | 4ms | 12.810
| |  P99| 417ms| 459ms | 42ms | 10.076
| ThreadStore.GetThreadsForUser |  Avg| 33ms| 41ms | 8ms | 24.379
| |  P99| 416ms| 481ms | 65ms | 15.643
| ThreadStore.GetTotalThreads |  Avg| 20ms| 25ms | 5ms | 25.011
| |  P99| 301ms| 397ms | 96ms | 31.922
| ThreadStore.GetTotalUnreadMentions |  Avg| 20ms| 25ms | 5ms | 25.315
| |  P99| 288ms| 390ms | 102ms | 35.397
| ThreadStore.GetTotalUnreadThreads |  Avg| 20ms| 25ms | 5ms | 24.907
| |  P99| 289ms| 388ms | 99ms | 34.218
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 20ms| 25ms | 5ms | 24.814
| |  P99| 292ms| 393ms | 101ms | 34.560
| ThreadStore.MaintainMembership |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 188ms| 194ms | 6ms | 3.197
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 8ms | -2ms | -20.142
| |  P99| 116ms| 92ms | -24ms | -20.622
| ThreadStore.MarkAllAsReadByTeam |  Avg| 12ms| 20ms | 8ms | 65.818
| |  P99| 96ms| 230ms | 134ms | 140.313
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 76ms| 80ms | 4ms | 5.287
| ThreadStore.UpdateMembership |  Avg| 9ms| 10ms | 1ms | 10.667
| |  P99| 85ms| 90ms | 5ms | 5.882
| TokenStore.Cleanup |  Avg| 4ms| 12ms | 8ms | 213.121
| |  P99| 24ms| 97ms | 73ms | 302.903
| UserAccessTokenStore.GetByToken |  Avg| 21ms| 14ms | -7ms | -32.816
| |  P99| 380ms| 221ms | -159ms | -41.839
| UserStore.AutocompleteUsersInChannel |  Avg| 325ms| 348ms | 23ms | 7.069
| |  P99| 987ms| 1.464s | 477ms | 48.321
| UserStore.Count |  Avg| 147ms| 212ms | 65ms | 44.081
| |  P99| 488ms| 2.11s | 1.622s | 332.037
| UserStore.Get |  Avg| 13ms| 24ms | 11ms | 85.820
| |  P99| 229ms| 379ms | 150ms | 65.584
| UserStore.GetAllProfiles |  Avg| 17ms| 21ms | 4ms | 23.591
| |  P99| 238ms| 332ms | 94ms | 39.506
| UserStore.GetAllProfilesInChannel |  Avg| 638ms| 664ms | 26ms | 4.078
| |  P99| 2.404s| 2.43s | 26ms | 1.082
| UserStore.GetByUsername |  Avg| 30ms| 34ms | 4ms | 13.147
| |  P99| 413ms| 490ms | 77ms | 18.639
| UserStore.GetForLogin |  Avg| 19ms| 22ms | 3ms | 15.657
| |  P99| 269ms| 335ms | 66ms | 24.560
| UserStore.GetMany |  Avg| 16ms| 22ms | 6ms | 36.517
| |  P99| 97ms| 226ms | 129ms | 132.794
| UserStore.GetProfileByIds |  Avg| 22ms| 29ms | 7ms | 32.491
| |  P99| 308ms| 407ms | 99ms | 32.144
| UserStore.GetProfilesByUsernames |  Avg| 25ms| 29ms | 4ms | 15.725
| |  P99| 336ms| 401ms | 65ms | 19.370
| UserStore.GetProfilesInChannel |  Avg| 44ms| 86ms | 42ms | 94.455
| |  P99| 440ms| 1.96s | 1.52s | 345.444
| UserStore.GetProfilesNotInChannel |  Avg| 48ms| 32ms | -16ms | -33.172
| |  P99| 242ms| 236ms | -6ms | -2.478
| UserStore.GetUnreadCount |  Avg| 22ms| 26ms | 4ms | 18.547
| |  P99| 291ms| 406ms | 115ms | 39.460
| UserStore.IsEmpty |  Avg| 10ms| 13ms | 3ms | 29.425
| |  P99| 193ms| 234ms | 41ms | 21.279
| UserStore.Save |  Avg| 81ms| 81ms | 0s | 0.000
| |  P99| 249ms| 250ms | 1ms | 0.402
| UserStore.Search |  Avg| 96ms| 108ms | 12ms | 12.440
| |  P99| 806ms| 891ms | 85ms | 10.541
| UserStore.Update |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 207ms| 214ms | 7ms | 3.381
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 75ms| 83ms | 8ms | 10.705
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 57ms| 66ms | 9ms | 15.871
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 66ms| 68ms | 2ms | 3.026
| UserTermsOfServiceStore.GetByUser |  Avg| 21ms| 25ms | 4ms | 19.496
| |  P99| 307ms| 391ms | 84ms | 27.381
| WebhookStore.GetOutgoingByTeam |  Avg| 32ms| 39ms | 7ms | 21.878
| |  P99| 407ms| 469ms | 62ms | 15.240
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 664ms| 696ms | 32ms | 4.819
| | P99| 4.68s| 4.837s | 157ms | 3.355
| addTeamMember | Avg| 1.717s| 1.787s | 70ms | 4.076
| | P99| 8.766s| 9.532s | 766ms | 8.738
| autocompleteChannelsForTeamForSearch | Avg| 172ms| 227ms | 55ms | 31.954
| | P99| 973ms| 1.935s | 962ms | 98.871
| autocompleteUsers | Avg| 279ms| 292ms | 13ms | 4.652
| | P99| 993ms| 1.609s | 616ms | 62.023
| createCategoryForTeamForUser | Avg| 175ms| 99ms | -76ms | -43.476
| | P99| 248ms| 935ms | 687ms | 276.876
| createChannel | Avg| 703ms| 947ms | 244ms | 34.696
| | P99| 2.421s| 8.55s | 6.129s | 253.134
| createDirectChannel | Avg| 608ms| 527ms | -81ms | -13.331
| | P99| 2.426s| 2.449s | 23ms | 0.948
| createEmoji | Avg| 6ms| 0s | -6ms | -99.831
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 965ms| 939ms | -26ms | -2.693
| | P99| 4.454s| 4.726s | 272ms | 6.107
| createPost | Avg| 951ms| 844ms | -107ms | -11.255
| | P99| 4.78s| 5.233s | 453ms | 9.478
| createUser | Avg| 275ms| 264ms | -11ms | -3.994
| | P99| 1.673s| 1.919s | 246ms | 14.702
| deleteDraft | Avg| 37ms| 45ms | 8ms | 21.437
| | P99| 449ms| 493ms | 44ms | 9.799
| deletePost | Avg| 217ms| 154ms | -63ms | -29.034
| | P99| 2.05s| 1.915s | -135ms | -6.586
| followThreadByUser | Avg| 68ms| 102ms | 34ms | 49.966
| | P99| 469ms| 909ms | 440ms | 93.742
| getAllTeams | Avg| 22ms| 27ms | 5ms | 22.717
| | P99| 318ms| 405ms | 87ms | 27.373
| getCategoriesForTeamForUser | Avg| 51ms| 64ms | 13ms | 25.250
| | P99| 762ms| 889ms | 127ms | 16.662
| getChannel | Avg| 79ms| 71ms | -8ms | -10.157
| | P99| 926ms| 1.024s | 98ms | 10.584
| getChannelMember | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 473ms| 487ms | 14ms | 2.957
| getChannelMembers | Avg| 28ms| 89ms | 61ms | 215.805
| | P99| 244ms| 475ms | 231ms | 94.672
| getChannelMembersForTeamForUser | Avg| 30ms| 37ms | 7ms | 23.603
| | P99| 392ms| 462ms | 70ms | 17.836
| getChannelMembersForUser | Avg| 19ms| 25ms | 6ms | 31.088
| | P99| 247ms| 378ms | 131ms | 53.001
| getChannelStats | Avg| 28ms| 27ms | -1ms | -3.607
| | P99| 574ms| 658ms | 84ms | 14.632
| getChannelUnread | Avg| 34ms| 32ms | -2ms | -5.932
| | P99| 426ms| 446ms | 20ms | 4.693
| getChannelsForTeamForUser | Avg| 32ms| 40ms | 8ms | 24.708
| | P99| 423ms| 477ms | 54ms | 12.760
| getChannelsForUser | Avg| 18ms| 23ms | 5ms | 27.694
| | P99| 244ms| 349ms | 105ms | 43.033
| getClientConfig | Avg| 20ms| 19ms | -1ms | -5.101
| | P99| 232ms| 231ms | -1ms | -0.432
| getDrafts | Avg| 34ms| 49ms | 15ms | 43.710
| | P99| 441ms| 673ms | 232ms | 52.639
| getFilePreview | Avg| 72ms| 76ms | 4ms | 5.539
| | P99| 466ms| 485ms | 19ms | 4.075
| getFileThumbnail | Avg| 66ms| 70ms | 4ms | 6.101
| | P99| 464ms| 488ms | 24ms | 5.171
| getPostThread | Avg| 163ms| 196ms | 33ms | 20.305
| | P99| 2.139s| 2.353s | 214ms | 10.005
| getPostsForChannel | Avg| 238ms| 315ms | 77ms | 32.348
| | P99| 3.8s| 4.82s | 1.02s | 26.840
| getPostsForChannelAroundLastUnread | Avg| 86ms| 106ms | 20ms | 23.343
| | P99| 1.318s| 1.841s | 523ms | 39.692
| getPreferences | Avg| 25ms| 32ms | 7ms | 28.023
| | P99| 346ms| 438ms | 92ms | 26.618
| getProfileImage | Avg| 84ms| 71ms | -13ms | -15.541
| | P99| 477ms| 460ms | -17ms | -3.566
| getPublicChannelsForTeam | Avg| 47ms| 58ms | 11ms | 23.231
| | P99| 457ms| 741ms | 284ms | 62.101
| getTeamMember | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 156ms| 158ms | 2ms | 1.283
| getTeamMembersForUser | Avg| 21ms| 25ms | 4ms | 19.286
| | P99| 300ms| 377ms | 77ms | 25.629
| getTeamStats | Avg| 325ms| 248ms | -77ms | -23.672
| | P99| 947ms| 953ms | 6ms | 0.633
| getTeamsForUser | Avg| 20ms| 26ms | 6ms | 29.951
| | P99| 275ms| 395ms | 120ms | 43.571
| getTeamsUnreadForUser | Avg| 39ms| 48ms | 9ms | 23.351
| | P99| 554ms| 786ms | 232ms | 41.858
| getThreadsForUser | Avg| 33ms| 41ms | 8ms | 24.541
| | P99| 431ms| 498ms | 67ms | 15.539
| getUser | Avg| 26ms| 38ms | 12ms | 45.693
| | P99| 377ms| 483ms | 106ms | 28.083
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 2ms | 1ms | 75.219
| | P99| 24ms| 32ms | 8ms | 33.349
| getUsers | Avg| 17ms| 25ms | 8ms | 46.710
| | P99| 243ms| 384ms | 141ms | 58.121
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 76ms| 87ms | 11ms | 14.561
| getUsersByNames | Avg| 26ms| 30ms | 4ms | 15.288
| | P99| 347ms| 407ms | 60ms | 17.305
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 19ms| 21ms | 2ms | 10.631
| | P99| 311ms| 368ms | 57ms | 18.319
| login | Avg| 247ms| 141ms | -106ms | -42.997
| | P99| 2.209s| 1.059s | -1.15s | -52.069
| logout | Avg| 138ms| 97ms | -41ms | -29.709
| | P99| 484ms| 444ms | -40ms | -8.262
| patchPost | Avg| 242ms| 237ms | -5ms | -2.066
| | P99| 2.675s| 2.46s | -215ms | -8.038
| removeUserCustomStatus | Avg| 281ms| 326ms | 45ms | 16.035
| | P99| 964ms| 2.395s | 1.431s | 148.420
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 89ms| 111ms | 22ms | 24.690
| | P99| 957ms| 1.533s | 576ms | 60.180
| searchAllChannels | Avg| 1.409s| 1.4s | -9ms | -0.639
| | P99| 4.842s| 4.848s | 6ms | 0.124
| searchGroupChannels | Avg| 34ms| 45ms | 11ms | 32.121
| | P99| 426ms| 576ms | 150ms | 35.182
| searchPostsInTeam | Avg| 127ms| 144ms | 17ms | 13.343
| | P99| 1.889s| 2.183s | 294ms | 15.567
| searchUsers | Avg| 98ms| 111ms | 13ms | 13.216
| | P99| 812ms| 897ms | 85ms | 10.464
| setPostReminder | Avg| 118ms| 182ms | 64ms | 54.151
| | P99| 945ms| 967ms | 22ms | 2.328
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 95ms| 107ms | 12ms | 12.624
| | P99| 1.18s| 969ms | -211ms | -17.882
| updateCategoriesForTeamForUser | Avg| 260ms| 214ms | -46ms | -17.712
| | P99| 2.293s| 2.095s | -198ms | -8.635
| updatePreferences | Avg| 32ms| 33ms | 1ms | 3.157
| | P99| 249ms| 283ms | 34ms | 13.665
| updateReadStateAllThreadsByUser | Avg| 16ms| 20ms | 4ms | 25.418
| | P99| 96ms| 230ms | 134ms | 140.313
| updateReadStateThreadByUser | Avg| 238ms| 301ms | 63ms | 26.496
| | P99| 2.369s| 3.37s | 1.001s | 42.249
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -142.869
| | P99| 20ms| 5ms | -15ms | -75.652
| uploadFileStream | Avg| 555ms| 538ms | -17ms | -3.063
| | P99| 2.175s| 2.107s | -68ms | -3.127
| upsertDraft | Avg| 22ms| 25ms | 3ms | 13.767
| | P99| 292ms| 373ms | 81ms | 27.708
| viewChannel | Avg| 73ms| 120ms | 47ms | 64.566
| | P99| 781ms| 1.824s | 1.043s | 133.576

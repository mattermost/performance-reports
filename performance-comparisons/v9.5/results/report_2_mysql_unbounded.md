### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| LicenseStore.GetAll | avg | 1ms | 6ms | 5ms | 500.14
| TeamStore.AnalyticsTeamCount | avg | 3ms | 18ms | 15ms | 492.37
| UserAccessTokenStore.GetByToken | avg | 10ms | 40ms | 30ms | 298.46
| PreferenceStore.DeleteCategoryAndName | avg | 3ms | 8ms | 5ms | 148.22
| StatusStore.UpdateExpiredDNDStatuses | avg | 4ms | 8ms | 4ms | 94.63
| PostStore.GetPostReminders | avg | 7ms | 13ms | 6ms | 82.24
| PluginStore.Get | avg | 8ms | 12ms | 4ms | 49.51
| ChannelStore.GetMembersForUserWithPagination | avg | 80ms | 115ms | 35ms | 43.89
| JobStore.Get | avg | 25ms | 33ms | 8ms | 31.83
| UserStore.Update | avg | 6ms | 8ms | 2ms | 31.67
| ChannelStore.GetTeamChannels | avg | 71ms | 90ms | 19ms | 26.67
| ChannelStore.UpdateSidebarCategories | avg | 78ms | 95ms | 17ms | 21.88
| BotStore.Get | avg | 27ms | 29ms | 2ms | 7.35
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 96ms | 91ms | 1837.52
| LicenseStore.GetAll | p99 | 5ms | 48ms | 43ms | 868.69
| UserAccessTokenStore.GetByToken | p99 | 216ms | 1.735s | 1.519s | 702.42
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 25ms | 20ms | 404.04
| StatusStore.UpdateExpiredDNDStatuses | p99 | 21ms | 89ms | 68ms | 320.00
| ChannelStore.GetMembersForUserWithPagination | p99 | 238ms | 850ms | 612ms | 257.13
| UserStore.Update | p99 | 41ms | 143ms | 102ms | 245.78
| PostStore.GetPostReminders | p99 | 87ms | 218ms | 131ms | 149.71
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 10ms | 24ms | 14ms | 140.70
| PreferenceStore.DeleteCategoryAndName | p99 | 23ms | 48ms | 25ms | 109.89
| ChannelStore.Save | p99 | 290ms | 590ms | 300ms | 103.43
| ChannelStore.UpdateSidebarCategories | p99 | 472ms | 850ms | 378ms | 80.00
| PluginStore.Get | p99 | 148ms | 219ms | 71ms | 48.14
| ChannelStore.GetAllChannelMembersForUser | p99 | 52ms | 75ms | 23ms | 44.46
| JobStore.Get | p99 | 328ms | 438ms | 110ms | 33.55
| PostStore.SearchPostsForUser | p99 | 1.257s | 1.453s | 196ms | 15.59
| UserStore.GetProfilesInChannel | p99 | 300ms | 326ms | 26ms | 8.68
| ChannelStore.GetTeamChannels | p99 | 232ms | 243ms | 11ms | 4.74
| PostStore.GetPostReminderMetadata | p99 | 456ms | 463ms | 7ms | 1.53
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | avg | 2ms | 0s | -2ms | -114.09
| ChannelStore.GetChannelsByIds | avg | 2ms | 0s | -2ms | -113.70
| ChannelStore.GetMemberOnly | avg | 26ms | 0s | -26ms | -99.28
| RoleStore.ChannelHigherScopedPermissions | avg | 228ms | 6ms | -222ms | -97.51
| ChannelStore.Update | avg | 8ms | 0s | -8ms | -96.94
| PostStore.GetPostsByIds | avg | 2ms | 0s | -2ms | -94.73
| PostPersistentNotificationStore.UpdateLastActivity | avg | 3ms | 0s | -3ms | -90.47
| UserStore.GetMany | avg | 55ms | 9ms | -46ms | -83.83
| DraftStore.Upsert | avg | 2ms | 0s | -2ms | -83.79
| PostStore.AnalyticsPostCount | avg | 2.755s | 571ms | -2.184s | -79.27
| JobStore.GetCountByStatusAndType | avg | 51ms | 12ms | -39ms | -76.53
| SessionStore.GetSessionsExpired | avg | 18ms | 5ms | -13ms | -73.84
| JobStore.GetNewestJobByStatusesAndType | avg | 41ms | 12ms | -29ms | -70.01
| ChannelStore.GetMembers | avg | 85ms | 37ms | -48ms | -56.20
| PostStore.GetPostReminderMetadata | avg | 77ms | 37ms | -40ms | -52.21
| PostStore.SetPostReminder | avg | 10ms | 5ms | -5ms | -48.32
| StatusStore.SaveOrUpdate | avg | 41ms | 22ms | -19ms | -46.25
| SessionStore.Remove | avg | 5ms | 3ms | -2ms | -44.27
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 33ms | 19ms | -14ms | -42.68
| ChannelStore.CreateDirectChannel | avg | 112ms | 66ms | -46ms | -40.90
| JobStore.GetAllByStatus | avg | 32ms | 19ms | -13ms | -40.83
| ChannelStore.GetGuestCount | avg | 52ms | 31ms | -21ms | -40.28
| PostAcknowledgementStore.GetForPost | avg | 33ms | 20ms | -13ms | -39.90
| PostPersistentNotificationStore.GetSingle | avg | 33ms | 20ms | -13ms | -39.75
| StatusStore.Get | avg | 21ms | 13ms | -8ms | -38.33
| UserStore.GetAllProfiles | avg | 29ms | 18ms | -11ms | -38.31
| TeamStore.GetAllPage | avg | 29ms | 18ms | -11ms | -38.22
| UserStore.IsEmpty | avg | 16ms | 10ms | -6ms | -38.02
| TeamStore.GetTeamsByUserId | avg | 32ms | 20ms | -12ms | -37.76
| UserTermsOfServiceStore.GetByUser | avg | 27ms | 17ms | -10ms | -37.39
| ChannelStore.GetByName | avg | 32ms | 20ms | -12ms | -37.39
| PostStore.GetEtag | avg | 44ms | 28ms | -16ms | -36.70
| ReactionStore.GetForPost | avg | 33ms | 21ms | -12ms | -36.40
| PreferenceStore.GetAll | avg | 36ms | 23ms | -13ms | -36.40
| ThreadStore.Get | avg | 33ms | 21ms | -12ms | -36.34
| GroupStore.GetByName | avg | 25ms | 16ms | -9ms | -36.19
| ThreadStore.GetThreadFollowers | avg | 34ms | 22ms | -12ms | -35.52
| ThreadStore.GetMembershipForUser | avg | 31ms | 20ms | -11ms | -35.41
| PostPriorityStore.GetForPost | avg | 28ms | 18ms | -10ms | -35.38
| ThreadStore.GetThreadForUser | avg | 46ms | 30ms | -16ms | -35.15
| ThreadStore.GetThreadsForUser | avg | 37ms | 24ms | -13ms | -35.03
| PostAcknowledgementStore.GetForPosts | avg | 40ms | 26ms | -14ms | -34.92
| UserStore.GetForLogin | avg | 23ms | 15ms | -8ms | -34.72
| TeamStore.GetChannelUnreadsForAllTeams | avg | 29ms | 19ms | -10ms | -34.61
| StatusStore.GetByIds | avg | 38ms | 25ms | -13ms | -34.42
| GroupStore.GetGroups | avg | 35ms | 23ms | -12ms | -33.97
| ChannelStore.GetPinnedPostCount | avg | 32ms | 21ms | -11ms | -33.93
| PostPriorityStore.GetForPosts | avg | 41ms | 27ms | -14ms | -33.83
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 24ms | 16ms | -8ms | -33.60
| UserStore.Get | avg | 12ms | 8ms | -4ms | -33.56
| ChannelStore.SaveMember | avg | 158ms | 105ms | -53ms | -33.52
| SessionStore.Get | avg | 33ms | 22ms | -11ms | -33.02
| PluginStore.List | avg | 31ms | 21ms | -10ms | -32.56
| WebhookStore.GetOutgoingByTeam | avg | 34ms | 23ms | -11ms | -32.29
| ThreadStore.GetTeamsUnreadForUser | avg | 31ms | 21ms | -10ms | -32.28
| ReactionStore.GetUniqueCountForPost | avg | 31ms | 21ms | -10ms | -32.24
| ChannelStore.GetFileCount | avg | 25ms | 17ms | -8ms | -31.85
| PreferenceStore.Get | avg | 28ms | 19ms | -9ms | -31.82
| PostStore.GetPostsBefore | avg | 35ms | 24ms | -11ms | -31.71
| TeamStore.GetTeamsForUser | avg | 19ms | 13ms | -6ms | -31.12
| ChannelStore.GetMembersForUser | avg | 32ms | 22ms | -10ms | -31.08
| ChannelStore.GetChannels | avg | 32ms | 22ms | -10ms | -31.08
| UserStore.GetProfilesByUsernames | avg | 26ms | 18ms | -8ms | -30.88
| ChannelStore.CreateInitialSidebarCategories | avg | 49ms | 34ms | -15ms | -30.86
| PostStore.GetPosts | avg | 29ms | 20ms | -9ms | -30.75
| ThreadStore.MaintainMembership | avg | 7ms | 5ms | -2ms | -30.59
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 26ms | 18ms | -8ms | -30.38
| ThreadStore.GetTotalUnreadThreads | avg | 26ms | 18ms | -8ms | -30.19
| ThreadStore.GetTotalThreads | avg | 27ms | 19ms | -8ms | -29.92
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 27ms | 19ms | -8ms | -29.81
| ChannelStore.Get | avg | 61ms | 43ms | -18ms | -29.53
| PostStore.SearchPostsForUser | avg | 139ms | 98ms | -41ms | -29.46
| ReactionStore.ExistsOnPost | avg | 34ms | 24ms | -10ms | -29.34
| ChannelStore.AutocompleteInTeamForSearch | avg | 279ms | 198ms | -81ms | -29.07
| PostStore.GetPostsSince | avg | 49ms | 35ms | -14ms | -28.83
| SessionStore.Save | avg | 24ms | 17ms | -7ms | -28.81
| ChannelStore.SearchGroupChannels | avg | 35ms | 25ms | -10ms | -28.73
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 74ms | 53ms | -21ms | -28.37
| PostStore.GetPostsByThread | avg | 32ms | 23ms | -9ms | -28.34
| FileInfoStore.Get | avg | 22ms | 16ms | -6ms | -27.79
| PostStore.Get | avg | 54ms | 39ms | -15ms | -27.57
| UserStore.GetProfileByIds | avg | 18ms | 13ms | -5ms | -27.20
| ThreadStore.GetTotalUnreadMentions | avg | 26ms | 19ms | -7ms | -26.80
| ChannelStore.GetChannelUnread | avg | 15ms | 11ms | -4ms | -26.58
| ThreadStore.GetThreadUnreadReplyCount | avg | 35ms | 26ms | -9ms | -25.49
| ChannelStore.GetChannelsByUser | avg | 24ms | 18ms | -6ms | -25.02
| UserStore.GetUnreadCount | avg | 29ms | 22ms | -7ms | -24.21
| TeamStore.Get | avg | 29ms | 22ms | -7ms | -24.17
| ChannelStore.GetMemberForPost | avg | 22ms | 17ms | -5ms | -23.25
| TeamStore.GetByName | avg | 20ms | 16ms | -4ms | -20.27
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 50ms | 40ms | -10ms | -20.12
| LinkMetadataStore.Get | avg | 30ms | 24ms | -6ms | -20.03
| ChannelStore.GetSidebarCategory | avg | 50ms | 40ms | -10ms | -19.85
| PostStore.Update | avg | 20ms | 16ms | -4ms | -19.55
| ChannelStore.GetMemberCount | avg | 306ms | 247ms | -59ms | -19.30
| ReactionStore.Save | avg | 11ms | 9ms | -2ms | -18.70
| PostStore.GetSingle | avg | 29ms | 24ms | -5ms | -16.98
| ChannelStore.GetPublicChannelsForTeam | avg | 55ms | 46ms | -9ms | -16.43
| FileInfoStore.GetForPost | avg | 32ms | 27ms | -5ms | -15.52
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 27ms | 23ms | -4ms | -14.78
| PostStore.Save | avg | 14ms | 12ms | -2ms | -14.45
| TeamStore.SaveMember | avg | 137ms | 119ms | -18ms | -13.18
| UserStore.GetAllProfilesInChannel | avg | 751ms | 655ms | -96ms | -12.78
| UserStore.Search | avg | 178ms | 157ms | -21ms | -11.80
| UserStore.AutocompleteUsersInChannel | avg | 367ms | 325ms | -42ms | -11.44
| PostStore.GetPostsAfter | avg | 22ms | 20ms | -2ms | -9.17
| ProductNoticesStore.View | avg | 33ms | 30ms | -3ms | -9.01
| ChannelStore.Autocomplete | avg | 2.196s | 2.072s | -124ms | -5.65
| UserStore.Count | avg | 191ms | 183ms | -8ms | -4.19
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.Update | p99 | 10ms | 0s | -10ms | -100.50
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.44
| ChannelStore.GetMemberOnly | p99 | 363ms | 0s | -363ms | -100.06
| RoleStore.ChannelHigherScopedPermissions | p99 | 1.963s | 89ms | -1.874s | -95.47
| UserStore.GetMany | p99 | 895ms | 88ms | -807ms | -90.17
| SessionStore.GetSessionsExpired | p99 | 236ms | 24ms | -212ms | -89.99
| PostStore.SetPostReminder | p99 | 92ms | 10ms | -82ms | -89.62
| JobStore.GetCountByStatusAndType | p99 | 1.435s | 283ms | -1.152s | -80.28
| SessionStore.Remove | p99 | 21ms | 5ms | -16ms | -74.77
| JobStore.GetNewestJobByStatusesAndType | p99 | 468ms | 178ms | -290ms | -62.00
| ChannelStore.GetMembers | p99 | 246ms | 99ms | -147ms | -59.88
| PostPersistentNotificationStore.Get | p99 | 18ms | 8ms | -10ms | -54.75
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.101s | 981ms | -1.12s | -53.30
| PostStore.AnalyticsPostCount | p99 | 4.975s | 2.471s | -2.504s | -50.33
| JobStore.Save | p99 | 33ms | 17ms | -16ms | -48.85
| PostStore.Update | p99 | 96ms | 49ms | -47ms | -48.83
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 32ms | 17ms | -15ms | -47.39
| PostAcknowledgementStore.GetForPost | p99 | 454ms | 246ms | -208ms | -45.84
| BotStore.Get | p99 | 438ms | 239ms | -199ms | -45.49
| FileInfoStore.Save | p99 | 45ms | 25ms | -20ms | -44.07
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 167ms | 99ms | -68ms | -40.82
| TeamStore.GetMember | p99 | 39ms | 23ms | -16ms | -40.58
| ChannelStore.SaveMember | p99 | 1.646s | 982ms | -664ms | -40.35
| FileInfoStore.SetContent | p99 | 65ms | 39ms | -26ms | -40.25
| ThreadStore.GetThreadFollowers | p99 | 424ms | 254ms | -170ms | -40.13
| ThreadStore.MaintainMembership | p99 | 74ms | 46ms | -28ms | -37.86
| PluginStore.SetWithOptions | p99 | 38ms | 24ms | -14ms | -36.85
| TeamStore.GetTeamsByUserId | p99 | 406ms | 258ms | -148ms | -36.44
| ThreadStore.MarkAllAsReadByChannels | p99 | 38ms | 24ms | -14ms | -36.42
| TeamStore.GetAllPage | p99 | 386ms | 248ms | -138ms | -35.78
| UserStore.GetProfilesByUsernames | p99 | 383ms | 248ms | -135ms | -35.25
| ThreadStore.MarkAsRead | p99 | 37ms | 24ms | -13ms | -35.23
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 382ms | 248ms | -134ms | -35.11
| UserTermsOfServiceStore.GetByUser | p99 | 377ms | 246ms | -131ms | -34.79
| StatusStore.SaveOrUpdate | p99 | 712ms | 466ms | -246ms | -34.54
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 361ms | 237ms | -124ms | -34.37
| ChannelStore.GetMember | p99 | 41ms | 27ms | -14ms | -34.24
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 381ms | 252ms | -129ms | -33.84
| JobStore.UpdateStatusOptimistically | p99 | 33ms | 22ms | -11ms | -33.60
| GroupStore.GetByName | p99 | 362ms | 242ms | -120ms | -33.17
| PostStore.GetPosts | p99 | 365ms | 245ms | -120ms | -32.89
| PostPersistentNotificationStore.GetSingle | p99 | 438ms | 296ms | -142ms | -32.42
| JobStore.GetAllByStatus | p99 | 482ms | 327ms | -155ms | -32.19
| PostStore.Get | p99 | 723ms | 491ms | -232ms | -32.10
| PreferenceStore.GetAll | p99 | 425ms | 289ms | -136ms | -31.99
| ChannelStore.GetByName | p99 | 407ms | 278ms | -129ms | -31.71
| ReactionStore.ExistsOnPost | p99 | 436ms | 298ms | -138ms | -31.67
| PostStore.GetPostIdBeforeTime | p99 | 35ms | 24ms | -11ms | -31.61
| StatusStore.UpdateLastActivityAt | p99 | 35ms | 24ms | -11ms | -31.32
| UserStore.GetForLogin | p99 | 341ms | 235ms | -106ms | -31.06
| SessionStore.Get | p99 | 410ms | 285ms | -125ms | -30.49
| UserStore.GetAllProfiles | p99 | 341ms | 237ms | -104ms | -30.47
| ReactionStore.GetForPost | p99 | 433ms | 302ms | -131ms | -30.23
| ChannelStore.UpdateLastViewedAt | p99 | 60ms | 42ms | -18ms | -29.99
| ThreadStore.GetTotalUnreadThreads | p99 | 374ms | 262ms | -112ms | -29.92
| ChannelStore.GetChannelsByUser | p99 | 353ms | 248ms | -105ms | -29.75
| PluginStore.Delete | p99 | 17ms | 12ms | -5ms | -29.70
| PreferenceStore.Get | p99 | 410ms | 289ms | -121ms | -29.49
| PostPriorityStore.GetForPost | p99 | 345ms | 244ms | -101ms | -29.28
| AuditStore.Save | p99 | 34ms | 24ms | -10ms | -29.04
| PostPriorityStore.GetForPosts | p99 | 608ms | 434ms | -174ms | -28.63
| ThreadStore.GetTotalThreads | p99 | 381ms | 273ms | -108ms | -28.37
| ChannelStore.IncrementMentionCount | p99 | 32ms | 23ms | -9ms | -28.16
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 385ms | 277ms | -108ms | -28.06
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 32ms | 23ms | -9ms | -27.85
| ThreadStore.GetTotalUnreadMentions | p99 | 370ms | 267ms | -103ms | -27.84
| ChannelStore.GetMembersForUser | p99 | 417ms | 302ms | -115ms | -27.57
| ChannelStore.GetPinnedPostCount | p99 | 429ms | 312ms | -117ms | -27.30
| UserStore.UpdateFailedPasswordAttempts | p99 | 33ms | 24ms | -9ms | -27.18
| SessionStore.UpdateLastActivityAt | p99 | 30ms | 22ms | -8ms | -26.99
| ChannelStore.GetFileCount | p99 | 306ms | 225ms | -81ms | -26.51
| ThreadStore.GetMembershipForUser | p99 | 416ms | 306ms | -110ms | -26.42
| PostAcknowledgementStore.GetForPosts | p99 | 575ms | 424ms | -151ms | -26.26
| FileInfoStore.Get | p99 | 330ms | 246ms | -84ms | -25.44
| SystemStore.GetByName | p99 | 24ms | 18ms | -6ms | -25.28
| PostStore.GetPostIdAfterTime | p99 | 32ms | 24ms | -8ms | -24.99
| ReactionStore.GetUniqueCountForPost | p99 | 427ms | 321ms | -106ms | -24.80
| PostStore.Save | p99 | 93ms | 70ms | -23ms | -24.63
| JobStore.UpdateOptimistically | p99 | 33ms | 25ms | -8ms | -24.44
| GroupStore.GetGroups | p99 | 433ms | 329ms | -104ms | -24.01
| ChannelStore.GetChannels | p99 | 430ms | 327ms | -103ms | -23.97
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 374ms | 285ms | -89ms | -23.77
| PreferenceStore.Save | p99 | 84ms | 64ms | -20ms | -23.73
| UserStore.AutocompleteUsersInChannel | p99 | 1.3s | 995ms | -305ms | -23.46
| ChannelStore.CreateInitialSidebarCategories | p99 | 434ms | 333ms | -101ms | -23.25
| ThreadStore.UpdateMembership | p99 | 44ms | 34ms | -10ms | -22.88
| PostStore.GetPostsBefore | p99 | 434ms | 335ms | -99ms | -22.82
| ThreadStore.GetTeamsUnreadForUser | p99 | 427ms | 330ms | -97ms | -22.72
| UserStore.UpdateUpdateAt | p99 | 31ms | 24ms | -7ms | -22.70
| PostStore.GetPostsByThread | p99 | 420ms | 326ms | -94ms | -22.37
| UserStore.GetProfileByIds | p99 | 302ms | 235ms | -67ms | -22.21
| SessionStore.Save | p99 | 296ms | 231ms | -65ms | -21.94
| ThreadStore.GetThreadsForUser | p99 | 455ms | 358ms | -97ms | -21.33
| ThreadStore.GetThreadForUser | p99 | 581ms | 458ms | -123ms | -21.17
| TeamStore.Get | p99 | 389ms | 307ms | -82ms | -21.07
| ChannelStore.GetMemberForPost | p99 | 307ms | 243ms | -64ms | -20.87
| ReactionStore.Save | p99 | 98ms | 78ms | -20ms | -20.38
| ThreadStore.GetThreadUnreadReplyCount | p99 | 447ms | 356ms | -91ms | -20.37
| StatusStore.Get | p99 | 288ms | 230ms | -58ms | -20.15
| WebhookStore.GetOutgoingByTeam | p99 | 433ms | 349ms | -84ms | -19.39
| PostStore.GetPostsSince | p99 | 451ms | 364ms | -87ms | -19.30
| UserStore.Count | p99 | 895ms | 725ms | -170ms | -18.99
| PostStore.GetSingle | p99 | 391ms | 318ms | -73ms | -18.67
| UserStore.Get | p99 | 237ms | 193ms | -44ms | -18.54
| ThreadStore.Get | p99 | 382ms | 313ms | -69ms | -18.04
| UserStore.GetUnreadCount | p99 | 441ms | 363ms | -78ms | -17.68
| PluginStore.List | p99 | 431ms | 355ms | -76ms | -17.62
| LinkMetadataStore.Get | p99 | 401ms | 331ms | -70ms | -17.46
| UserStore.IsEmpty | p99 | 232ms | 192ms | -40ms | -17.21
| PostStore.GetEtag | p99 | 468ms | 388ms | -80ms | -17.10
| StatusStore.GetByIds | p99 | 454ms | 378ms | -76ms | -16.73
| TeamStore.GetByName | p99 | 281ms | 235ms | -46ms | -16.35
| ChannelStore.GetSidebarCategory | p99 | 452ms | 380ms | -72ms | -15.94
| ChannelStore.GetGuestCount | p99 | 486ms | 410ms | -76ms | -15.65
| ChannelStore.CreateDirectChannel | p99 | 942ms | 796ms | -146ms | -15.50
| PostStore.GetPostsAfter | p99 | 335ms | 286ms | -49ms | -14.65
| ClusterDiscoveryStore.SetLastPingAt | p99 | 43ms | 37ms | -6ms | -14.04
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 435ms | 374ms | -61ms | -14.03
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 890ms | 779ms | -111ms | -12.47
| UserStore.UpdateLastLogin | p99 | 25ms | 22ms | -3ms | -12.19
| ChannelStore.GetChannelUnread | p99 | 242ms | 213ms | -29ms | -12.00
| FileInfoStore.AttachToPost | p99 | 35ms | 31ms | -4ms | -11.43
| TeamStore.GetTeamsForUser | p99 | 250ms | 223ms | -27ms | -10.81
| FileInfoStore.GetForPost | p99 | 421ms | 377ms | -44ms | -10.45
| ChannelStore.GetPublicChannelsForTeam | p99 | 455ms | 415ms | -40ms | -8.79
| TeamStore.SaveMember | p99 | 494ms | 452ms | -42ms | -8.51
| ProductNoticesStore.View | p99 | 226ms | 208ms | -18ms | -7.95
| ChannelStore.Get | p99 | 485ms | 448ms | -37ms | -7.62
| UserStore.Search | p99 | 903ms | 844ms | -59ms | -6.54
| UserStore.Save | p99 | 221ms | 207ms | -14ms | -6.32
| ChannelStore.SearchGroupChannels | p99 | 432ms | 409ms | -23ms | -5.32
| UserStore.GetByUsername | p99 | 455ms | 439ms | -16ms | -3.52
| ChannelStore.Autocomplete | p99 | 9.401s | 9.208s | -193ms | -2.05
| ChannelStore.GetMemberCount | p99 | 988ms | 968ms | -20ms | -2.02
| UserStore.GetAllProfilesInChannel | p99 | 2.449s | 2.424s | -25ms | -1.02
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteDraft | avg | 5ms | 70ms | 65ms | 1369.80
| getGroups | avg | 2ms | 20ms | 18ms | 866.92
| getPrevTrialLicense | avg | 2ms | 12ms | 10ms | 657.41
| getRolesByNames | avg | 2ms | 9ms | 7ms | 447.89
| logout | avg | 72ms | 113ms | 41ms | 56.56
| upsertDraft | avg | 4ms | 6ms | 2ms | 55.06
| createChannel | avg | 71ms | 90ms | 19ms | 26.61
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteDraft | p99 | 5ms | 243ms | 238ms | 4808.08
| getGroups | p99 | 5ms | 98ms | 93ms | 1878.79
| getPrevTrialLicense | p99 | 5ms | 49ms | 44ms | 888.89
| getRolesByNames | p99 | 5ms | 48ms | 43ms | 868.69
| updateReadStateAllThreadsByUser | p99 | 5ms | 25ms | 20ms | 404.04
| upsertDraft | p99 | 10ms | 25ms | 15ms | 153.01
| logout | p99 | 232ms | 480ms | 248ms | 106.74
| root | p99 | 5ms | 9ms | 4ms | 80.81
| getConfig | p99 | 99ms | 115ms | 16ms | 16.17
| unfollowThreadByUser | p99 | 625ms | 695ms | 70ms | 11.20
| createChannel | p99 | 232ms | 243ms | 11ms | 4.74
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 639ms | 272ms | -367ms | -57.43
| getChannelMembers | avg | 86ms | 37ms | -49ms | -56.98
| getChannel | avg | 65ms | 36ms | -29ms | -44.63
| getChannelMember | avg | 15ms | 9ms | -6ms | -41.21
| followThreadByUser | avg | 109ms | 64ms | -45ms | -41.19
| getAllTeams | avg | 31ms | 19ms | -12ms | -39.05
| getTeamsForUser | avg | 32ms | 20ms | -12ms | -37.64
| getPreferences | avg | 36ms | 23ms | -13ms | -35.67
| setPostReminder | avg | 266ms | 174ms | -92ms | -34.57
| getUser | avg | 38ms | 25ms | -13ms | -34.09
| createDirectChannel | avg | 406ms | 269ms | -137ms | -33.77
| getThreadsForUser | avg | 36ms | 24ms | -12ms | -33.07
| getTeamsUnreadForUser | avg | 46ms | 31ms | -15ms | -32.66
| saveReaction | avg | 184ms | 125ms | -59ms | -32.07
| getPostsForChannel | avg | 250ms | 170ms | -80ms | -31.97
| getChannelsForTeamForUser | avg | 35ms | 24ms | -11ms | -31.82
| getUsersByNames | avg | 26ms | 18ms | -8ms | -30.38
| getChannelMembersForTeamForUser | avg | 33ms | 23ms | -10ms | -30.26
| getChannelUnread | avg | 17ms | 12ms | -5ms | -29.84
| getPostsForChannelAroundLastUnread | avg | 156ms | 110ms | -46ms | -29.45
| getPostThread | avg | 191ms | 135ms | -56ms | -29.31
| autocompleteChannelsForTeamForSearch | avg | 279ms | 198ms | -81ms | -29.06
| getTeamMembersForUser | avg | 21ms | 15ms | -6ms | -28.16
| viewChannel | avg | 72ms | 52ms | -20ms | -27.96
| getUsers | avg | 40ms | 29ms | -11ms | -27.74
| updateReadStateThreadByUser | avg | 256ms | 185ms | -71ms | -27.74
| updatePreferences | avg | 11ms | 8ms | -3ms | -27.50
| searchPostsInTeam | avg | 207ms | 151ms | -56ms | -27.11
| getCategoriesForTeamForUser | avg | 74ms | 54ms | -20ms | -26.89
| addChannelMember | avg | 686ms | 504ms | -182ms | -26.55
| searchGroupChannels | avg | 35ms | 26ms | -9ms | -25.81
| removeUserCustomStatus | avg | 194ms | 144ms | -50ms | -25.74
| getProfileImage | avg | 88ms | 66ms | -22ms | -25.02
| getChannelStats | avg | 61ms | 47ms | -14ms | -22.96
| unfollowThreadByUser | avg | 70ms | 55ms | -15ms | -21.34
| deletePost | avg | 230ms | 181ms | -49ms | -21.28
| createGroupChannel | avg | 767ms | 612ms | -155ms | -20.22
| getClientConfig | avg | 10ms | 8ms | -2ms | -19.93
| getChannelsForUser | avg | 25ms | 20ms | -5ms | -19.91
| login | avg | 160ms | 130ms | -30ms | -18.81
| addTeamMember | avg | 2.164s | 1.77s | -394ms | -18.21
| getPublicChannelsForTeam | avg | 56ms | 47ms | -9ms | -16.03
| getFileThumbnail | avg | 76ms | 64ms | -12ms | -15.82
| createUser | avg | 140ms | 121ms | -19ms | -13.52
| searchUsers | avg | 183ms | 159ms | -24ms | -13.15
| getFilePreview | avg | 82ms | 73ms | -9ms | -10.94
| autocompleteUsers | avg | 292ms | 264ms | -28ms | -9.59
| createPost | avg | 1.064s | 998ms | -66ms | -6.20
| searchAllChannels | avg | 2.197s | 2.072s | -125ms | -5.69
| updateCategoriesForTeamForUser | avg | 192ms | 189ms | -3ms | -1.56
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 246ms | 99ms | -147ms | -59.88
| createDirectChannel | p99 | 2.318s | 984ms | -1.334s | -57.55
| autocompleteChannelsForTeamForSearch | p99 | 2.101s | 981ms | -1.12s | -53.30
| updateCategoriesForTeamForUser | p99 | 2.005s | 950ms | -1.055s | -52.62
| getTeamMember | p99 | 61ms | 31ms | -30ms | -49.31
| getChannel | p99 | 788ms | 435ms | -353ms | -44.82
| updatePreferences | p99 | 138ms | 79ms | -59ms | -42.72
| getUsersByIds | p99 | 60ms | 37ms | -23ms | -38.24
| getTeamsForUser | p99 | 407ms | 260ms | -147ms | -36.10
| getUsersByNames | p99 | 388ms | 249ms | -139ms | -35.85
| getClientConfig | p99 | 189ms | 122ms | -67ms | -35.49
| getPostsForChannel | p99 | 3.966s | 2.629s | -1.337s | -33.72
| createUser | p99 | 778ms | 522ms | -256ms | -32.89
| getChannelMember | p99 | 319ms | 214ms | -105ms | -32.87
| getAllTeams | p99 | 406ms | 274ms | -132ms | -32.48
| getPreferences | p99 | 430ms | 308ms | -122ms | -28.37
| getFileThumbnail | p99 | 692ms | 499ms | -193ms | -27.91
| getChannelMembersForTeamForUser | p99 | 426ms | 317ms | -109ms | -25.60
| getTeamMembersForUser | p99 | 308ms | 231ms | -77ms | -25.02
| getFilePreview | p99 | 656ms | 494ms | -162ms | -24.69
| getTeamsUnreadForUser | p99 | 602ms | 459ms | -143ms | -23.74
| viewChannel | p99 | 855ms | 680ms | -175ms | -20.47
| getThreadsForUser | p99 | 460ms | 368ms | -92ms | -20.02
| getUsers | p99 | 439ms | 355ms | -84ms | -19.14
| getChannelUnread | p99 | 276ms | 224ms | -52ms | -18.86
| getChannelsForTeamForUser | p99 | 451ms | 373ms | -78ms | -17.31
| getUser | p99 | 438ms | 363ms | -75ms | -17.13
| getChannelsForUser | p99 | 363ms | 302ms | -61ms | -16.81
| getPostsForChannelAroundLastUnread | p99 | 2.135s | 1.808s | -327ms | -15.31
| createPost | p99 | 5.446s | 4.661s | -785ms | -14.42
| addChannelMember | p99 | 4.743s | 4.15s | -593ms | -12.50
| getCategoriesForTeamForUser | p99 | 891ms | 782ms | -109ms | -12.23
| saveReaction | p99 | 2.228s | 1.958s | -270ms | -12.12
| getPostThread | p99 | 2.285s | 2.03s | -255ms | -11.16
| getChannelStats | p99 | 964ms | 873ms | -91ms | -9.44
| login | p99 | 976ms | 888ms | -88ms | -9.02
| getPublicChannelsForTeam | p99 | 455ms | 415ms | -40ms | -8.79
| updateReadStateThreadByUser | p99 | 2.45s | 2.255s | -195ms | -7.96
| addTeamMember | p99 | 9.459s | 8.816s | -643ms | -6.80
| searchUsers | p99 | 909ms | 848ms | -61ms | -6.71
| createGroupChannel | p99 | 4.58s | 4.333s | -247ms | -5.39
| searchGroupChannels | p99 | 432ms | 409ms | -23ms | -5.32
| removeUserCustomStatus | p99 | 500ms | 481ms | -19ms | -3.80
| getProfileImage | p99 | 469ms | 453ms | -16ms | -3.41
| followThreadByUser | p99 | 486ms | 470ms | -16ms | -3.29
| searchPostsInTeam | p99 | 2.365s | 2.295s | -70ms | -2.96
| deletePost | p99 | 963ms | 940ms | -23ms | -2.39
| searchAllChannels | p99 | 9.407s | 9.22s | -187ms | -1.99
| autocompleteUsers | p99 | 997ms | 983ms | -14ms | -1.40
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 24ms | -10ms | -29.035
| BotStore.Get |  Avg| 27ms| 29ms | 2ms | 7.348
| |  P99| 438ms| 239ms | -199ms | -45.486
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 23ms | -9ms | -27.848
| ChannelStore.Autocomplete |  Avg| 2.196s| 2.072s | -124ms | -5.647
| |  P99| 9.401s| 9.208s | -193ms | -2.053
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 279ms| 198ms | -81ms | -29.065
| |  P99| 2.101s| 981ms | -1.12s | -53.297
| ChannelStore.CreateDirectChannel |  Avg| 112ms| 66ms | -46ms | -40.897
| |  P99| 942ms| 796ms | -146ms | -15.504
| ChannelStore.CreateInitialSidebarCategories |  Avg| 49ms| 34ms | -15ms | -30.862
| |  P99| 434ms| 333ms | -101ms | -23.250
| ChannelStore.CreateSidebarCategory |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 61ms| 43ms | -18ms | -29.534
| |  P99| 485ms| 448ms | -37ms | -7.622
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 50ms| 40ms | -10ms | -20.119
| |  P99| 435ms| 374ms | -61ms | -14.031
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 3ms | 1ms | 40.291
| |  P99| 52ms| 75ms | 23ms | 44.457
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 27ms| 23ms | -4ms | -14.775
| |  P99| 167ms| 99ms | -68ms | -40.823
| ChannelStore.GetByName |  Avg| 32ms| 20ms | -12ms | -37.388
| |  P99| 407ms| 278ms | -129ms | -31.707
| ChannelStore.GetChannelUnread |  Avg| 15ms| 11ms | -4ms | -26.582
| |  P99| 242ms| 213ms | -29ms | -11.997
| ChannelStore.GetChannels |  Avg| 32ms| 22ms | -10ms | -31.079
| |  P99| 430ms| 327ms | -103ms | -23.971
| ChannelStore.GetChannelsByIds |  Avg| 2ms| 0s | -2ms | -113.703
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 24ms| 18ms | -6ms | -25.023
| |  P99| 353ms| 248ms | -105ms | -29.751
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 26ms| 18ms | -8ms | -30.376
| |  P99| 382ms| 248ms | -134ms | -35.107
| ChannelStore.GetFileCount |  Avg| 25ms| 17ms | -8ms | -31.847
| |  P99| 306ms| 225ms | -81ms | -26.511
| ChannelStore.GetGuestCount |  Avg| 52ms| 31ms | -21ms | -40.281
| |  P99| 486ms| 410ms | -76ms | -15.649
| ChannelStore.GetMember |  Avg| 3ms| 2ms | -1ms | -35.196
| |  P99| 41ms| 27ms | -14ms | -34.237
| ChannelStore.GetMemberCount |  Avg| 306ms| 247ms | -59ms | -19.299
| |  P99| 988ms| 968ms | -20ms | -2.025
| ChannelStore.GetMemberForPost |  Avg| 22ms| 17ms | -5ms | -23.255
| |  P99| 307ms| 243ms | -64ms | -20.874
| ChannelStore.GetMemberOnly |  Avg| 26ms| 0s | -26ms | -99.284
| |  P99| 363ms| 0s | -363ms | -100.056
| ChannelStore.GetMembers |  Avg| 85ms| 37ms | -48ms | -56.205
| |  P99| 246ms| 99ms | -147ms | -59.877
| ChannelStore.GetMembersForUser |  Avg| 32ms| 22ms | -10ms | -31.083
| |  P99| 417ms| 302ms | -115ms | -27.567
| ChannelStore.GetMembersForUserWithPagination |  Avg| 80ms| 115ms | 35ms | 43.894
| |  P99| 238ms| 850ms | 612ms | 257.129
| ChannelStore.GetPinnedPostCount |  Avg| 32ms| 21ms | -11ms | -33.933
| |  P99| 429ms| 312ms | -117ms | -27.297
| ChannelStore.GetPublicChannelsForTeam |  Avg| 55ms| 46ms | -9ms | -16.434
| |  P99| 455ms| 415ms | -40ms | -8.791
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 74ms| 53ms | -21ms | -28.367
| |  P99| 890ms| 779ms | -111ms | -12.469
| ChannelStore.GetSidebarCategory |  Avg| 50ms| 40ms | -10ms | -19.847
| |  P99| 452ms| 380ms | -72ms | -15.942
| ChannelStore.GetTeamChannels |  Avg| 71ms| 90ms | 19ms | 26.673
| |  P99| 232ms| 243ms | 11ms | 4.741
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 23ms | -9ms | -28.160
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 36ms| 37ms | 1ms | 2.745
| |  P99| 290ms| 590ms | 300ms | 103.434
| ChannelStore.SaveMember |  Avg| 158ms| 105ms | -53ms | -33.519
| |  P99| 1.646s| 982ms | -664ms | -40.352
| ChannelStore.SearchGroupChannels |  Avg| 35ms| 25ms | -10ms | -28.731
| |  P99| 432ms| 409ms | -23ms | -5.321
| ChannelStore.Update |  Avg| 8ms| 0s | -8ms | -96.944
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 6ms | -1ms | -14.952
| |  P99| 60ms| 42ms | -18ms | -29.988
| ChannelStore.UpdateSidebarCategories |  Avg| 78ms| 95ms | 17ms | 21.881
| |  P99| 472ms| 850ms | 378ms | 80.001
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 1ms | -1ms | -56.225
| |  P99| 32ms| 17ms | -15ms | -47.387
| ClusterDiscoveryStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 37ms | -6ms | -14.035
| CommandWebhookStore.Cleanup |  Avg| 2ms| 1ms | -1ms | -66.633
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 2ms| 0s | -2ms | -83.790
| |  P99| 5ms| 0s | -5ms | -100.444
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 35ms| 31ms | -4ms | -11.429
| FileInfoStore.Get |  Avg| 22ms| 16ms | -6ms | -27.786
| |  P99| 330ms| 246ms | -84ms | -25.441
| FileInfoStore.GetForPost |  Avg| 32ms| 27ms | -5ms | -15.525
| |  P99| 421ms| 377ms | -44ms | -10.448
| FileInfoStore.Save |  Avg| 6ms| 5ms | -1ms | -17.181
| |  P99| 45ms| 25ms | -20ms | -44.074
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -10.539
| |  P99| 65ms| 39ms | -26ms | -40.246
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 33ms| 19ms | -14ms | -42.681
| |  P99| 385ms| 277ms | -108ms | -28.059
| GroupStore.GetByName |  Avg| 25ms| 16ms | -9ms | -36.186
| |  P99| 362ms| 242ms | -120ms | -33.166
| GroupStore.GetGroups |  Avg| 35ms| 23ms | -12ms | -33.974
| |  P99| 433ms| 329ms | -104ms | -24.008
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 140.704
| JobStore.Get |  Avg| 25ms| 33ms | 8ms | 31.829
| |  P99| 328ms| 438ms | 110ms | 33.546
| JobStore.GetAllByStatus |  Avg| 32ms| 19ms | -13ms | -40.827
| |  P99| 482ms| 327ms | -155ms | -32.186
| JobStore.GetCountByStatusAndType |  Avg| 51ms| 12ms | -39ms | -76.531
| |  P99| 1.435s| 283ms | -1.152s | -80.279
| JobStore.GetNewestJobByStatusesAndType |  Avg| 41ms| 12ms | -29ms | -70.005
| |  P99| 468ms| 178ms | -290ms | -62.002
| JobStore.Save |  Avg| 5ms| 4ms | -1ms | -22.102
| |  P99| 33ms| 17ms | -16ms | -48.855
| JobStore.UpdateOptimistically |  Avg| 4ms| 5ms | 1ms | 28.023
| |  P99| 33ms| 25ms | -8ms | -24.436
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -21.735
| |  P99| 33ms| 22ms | -11ms | -33.599
| LicenseStore.GetAll |  Avg| 1ms| 6ms | 5ms | 500.139
| |  P99| 5ms| 48ms | 43ms | 868.687
| LinkMetadataStore.Get |  Avg| 30ms| 24ms | -6ms | -20.032
| |  P99| 401ms| 331ms | -70ms | -17.460
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.066
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 12ms | -5ms | -29.704
| PluginStore.Get |  Avg| 8ms| 12ms | 4ms | 49.508
| |  P99| 148ms| 219ms | 71ms | 48.136
| PluginStore.List |  Avg| 31ms| 21ms | -10ms | -32.564
| |  P99| 431ms| 355ms | -76ms | -17.623
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 24ms | -14ms | -36.845
| PostAcknowledgementStore.GetForPost |  Avg| 33ms| 20ms | -13ms | -39.896
| |  P99| 454ms| 246ms | -208ms | -45.838
| PostAcknowledgementStore.GetForPosts |  Avg| 40ms| 26ms | -14ms | -34.921
| |  P99| 575ms| 424ms | -151ms | -26.258
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.301
| PostPersistentNotificationStore.Get |  Avg| 2ms| 1ms | -1ms | -64.566
| |  P99| 18ms| 8ms | -10ms | -54.749
| PostPersistentNotificationStore.GetSingle |  Avg| 33ms| 20ms | -13ms | -39.753
| |  P99| 438ms| 296ms | -142ms | -32.416
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 0s | -3ms | -90.466
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 28ms| 18ms | -10ms | -35.376
| |  P99| 345ms| 244ms | -101ms | -29.277
| PostPriorityStore.GetForPosts |  Avg| 41ms| 27ms | -14ms | -33.832
| |  P99| 608ms| 434ms | -174ms | -28.626
| PostStore.AnalyticsPostCount |  Avg| 2.755s| 571ms | -2.184s | -79.265
| |  P99| 4.975s| 2.471s | -2.504s | -50.327
| PostStore.Delete |  Avg| 46ms| 47ms | 1ms | 2.160
| |  P99| 243ms| 241ms | -2ms | -0.825
| PostStore.Get |  Avg| 54ms| 39ms | -15ms | -27.568
| |  P99| 723ms| 491ms | -232ms | -32.099
| PostStore.GetEtag |  Avg| 44ms| 28ms | -16ms | -36.702
| |  P99| 468ms| 388ms | -80ms | -17.103
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 24ms | -8ms | -24.988
| PostStore.GetPostIdBeforeTime |  Avg| 4ms| 3ms | -1ms | -28.318
| |  P99| 35ms| 24ms | -11ms | -31.610
| PostStore.GetPostReminderMetadata |  Avg| 77ms| 37ms | -40ms | -52.210
| |  P99| 456ms| 463ms | 7ms | 1.534
| PostStore.GetPostReminders |  Avg| 7ms| 13ms | 6ms | 82.242
| |  P99| 87ms| 218ms | 131ms | 149.714
| PostStore.GetPosts |  Avg| 29ms| 20ms | -9ms | -30.749
| |  P99| 365ms| 245ms | -120ms | -32.888
| PostStore.GetPostsAfter |  Avg| 22ms| 20ms | -2ms | -9.174
| |  P99| 335ms| 286ms | -49ms | -14.649
| PostStore.GetPostsBefore |  Avg| 35ms| 24ms | -11ms | -31.705
| |  P99| 434ms| 335ms | -99ms | -22.821
| PostStore.GetPostsByIds |  Avg| 2ms| 0s | -2ms | -94.730
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 32ms| 23ms | -9ms | -28.336
| |  P99| 420ms| 326ms | -94ms | -22.366
| PostStore.GetPostsSince |  Avg| 49ms| 35ms | -14ms | -28.833
| |  P99| 451ms| 364ms | -87ms | -19.298
| PostStore.GetSingle |  Avg| 29ms| 24ms | -5ms | -16.982
| |  P99| 391ms| 318ms | -73ms | -18.667
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 12ms | -2ms | -14.450
| |  P99| 93ms| 70ms | -23ms | -24.626
| PostStore.SearchPostsForUser |  Avg| 139ms| 98ms | -41ms | -29.461
| |  P99| 1.257s| 1.453s | 196ms | 15.590
| PostStore.SetPostReminder |  Avg| 10ms| 5ms | -5ms | -48.318
| |  P99| 92ms| 10ms | -82ms | -89.617
| PostStore.Update |  Avg| 20ms| 16ms | -4ms | -19.550
| |  P99| 96ms| 49ms | -47ms | -48.831
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 8ms | 5ms | 148.218
| |  P99| 23ms| 48ms | 25ms | 109.892
| PreferenceStore.Get |  Avg| 28ms| 19ms | -9ms | -31.821
| |  P99| 410ms| 289ms | -121ms | -29.489
| PreferenceStore.GetAll |  Avg| 36ms| 23ms | -13ms | -36.400
| |  P99| 425ms| 289ms | -136ms | -31.987
| PreferenceStore.Save |  Avg| 10ms| 9ms | -1ms | -10.298
| |  P99| 84ms| 64ms | -20ms | -23.731
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 33ms| 30ms | -3ms | -9.006
| |  P99| 226ms| 208ms | -18ms | -7.949
| ReactionStore.ExistsOnPost |  Avg| 34ms| 24ms | -10ms | -29.338
| |  P99| 436ms| 298ms | -138ms | -31.670
| ReactionStore.GetForPost |  Avg| 33ms| 21ms | -12ms | -36.402
| |  P99| 433ms| 302ms | -131ms | -30.229
| ReactionStore.GetUniqueCountForPost |  Avg| 31ms| 21ms | -10ms | -32.241
| |  P99| 427ms| 321ms | -106ms | -24.801
| ReactionStore.Save |  Avg| 11ms| 9ms | -2ms | -18.702
| |  P99| 98ms| 78ms | -20ms | -20.381
| RoleStore.ChannelHigherScopedPermissions |  Avg| 228ms| 6ms | -222ms | -97.514
| |  P99| 1.963s| 89ms | -1.874s | -95.466
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 33ms| 22ms | -11ms | -33.023
| |  P99| 410ms| 285ms | -125ms | -30.488
| SessionStore.GetSessionsExpired |  Avg| 18ms| 5ms | -13ms | -73.841
| |  P99| 236ms| 24ms | -212ms | -89.993
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 24ms| 16ms | -8ms | -33.596
| |  P99| 361ms| 237ms | -124ms | -34.370
| SessionStore.Remove |  Avg| 5ms| 3ms | -2ms | -44.265
| |  P99| 21ms| 5ms | -16ms | -74.769
| SessionStore.Save |  Avg| 24ms| 17ms | -7ms | -28.810
| |  P99| 296ms| 231ms | -65ms | -21.939
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 22ms | -8ms | -26.987
| StatusStore.Get |  Avg| 21ms| 13ms | -8ms | -38.327
| |  P99| 288ms| 230ms | -58ms | -20.150
| StatusStore.GetByIds |  Avg| 38ms| 25ms | -13ms | -34.417
| |  P99| 454ms| 378ms | -76ms | -16.728
| StatusStore.SaveOrUpdate |  Avg| 41ms| 22ms | -19ms | -46.255
| |  P99| 712ms| 466ms | -246ms | -34.543
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 8ms | 4ms | 94.632
| |  P99| 21ms| 89ms | 68ms | 320.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 24ms | -11ms | -31.316
| SystemStore.GetByName |  Avg| 2ms| 1ms | -1ms | -55.963
| |  P99| 24ms| 18ms | -6ms | -25.281
| TeamStore.AnalyticsTeamCount |  Avg| 3ms| 18ms | 15ms | 492.370
| |  P99| 5ms| 96ms | 91ms | 1837.520
| TeamStore.Get |  Avg| 29ms| 22ms | -7ms | -24.168
| |  P99| 389ms| 307ms | -82ms | -21.066
| TeamStore.GetAllPage |  Avg| 29ms| 18ms | -11ms | -38.224
| |  P99| 386ms| 248ms | -138ms | -35.777
| TeamStore.GetByName |  Avg| 20ms| 16ms | -4ms | -20.274
| |  P99| 281ms| 235ms | -46ms | -16.346
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 29ms| 19ms | -10ms | -34.609
| |  P99| 381ms| 252ms | -129ms | -33.844
| TeamStore.GetMany |  Avg| 2ms| 0s | -2ms | -114.088
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 3ms| 2ms | -1ms | -38.513
| |  P99| 39ms| 23ms | -16ms | -40.582
| TeamStore.GetTeamsByUserId |  Avg| 32ms| 20ms | -12ms | -37.763
| |  P99| 406ms| 258ms | -148ms | -36.436
| TeamStore.GetTeamsForUser |  Avg| 19ms| 13ms | -6ms | -31.124
| |  P99| 250ms| 223ms | -27ms | -10.808
| TeamStore.SaveMember |  Avg| 137ms| 119ms | -18ms | -13.179
| |  P99| 494ms| 452ms | -42ms | -8.508
| ThreadStore.Get |  Avg| 33ms| 21ms | -12ms | -36.343
| |  P99| 382ms| 313ms | -69ms | -18.039
| ThreadStore.GetMembershipForUser |  Avg| 31ms| 20ms | -11ms | -35.411
| |  P99| 416ms| 306ms | -110ms | -26.423
| ThreadStore.GetTeamsUnreadForUser |  Avg| 31ms| 21ms | -10ms | -32.279
| |  P99| 427ms| 330ms | -97ms | -22.719
| ThreadStore.GetThreadFollowers |  Avg| 34ms| 22ms | -12ms | -35.524
| |  P99| 424ms| 254ms | -170ms | -40.129
| ThreadStore.GetThreadForUser |  Avg| 46ms| 30ms | -16ms | -35.148
| |  P99| 581ms| 458ms | -123ms | -21.173
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 35ms| 26ms | -9ms | -25.489
| |  P99| 447ms| 356ms | -91ms | -20.374
| ThreadStore.GetThreadsForUser |  Avg| 37ms| 24ms | -13ms | -35.028
| |  P99| 455ms| 358ms | -97ms | -21.331
| ThreadStore.GetTotalThreads |  Avg| 27ms| 19ms | -8ms | -29.920
| |  P99| 381ms| 273ms | -108ms | -28.375
| ThreadStore.GetTotalUnreadMentions |  Avg| 26ms| 19ms | -7ms | -26.800
| |  P99| 370ms| 267ms | -103ms | -27.839
| ThreadStore.GetTotalUnreadThreads |  Avg| 26ms| 18ms | -8ms | -30.193
| |  P99| 374ms| 262ms | -112ms | -29.919
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 27ms| 19ms | -8ms | -29.810
| |  P99| 374ms| 285ms | -89ms | -23.774
| ThreadStore.MaintainMembership |  Avg| 7ms| 5ms | -2ms | -30.589
| |  P99| 74ms| 46ms | -28ms | -37.864
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -38.996
| |  P99| 38ms| 24ms | -14ms | -36.422
| ThreadStore.MarkAllAsReadByTeam |  Avg| 5ms| 6ms | 1ms | 20.812
| |  P99| 5ms| 25ms | 20ms | 404.040
| ThreadStore.MarkAsRead |  Avg| 5ms| 4ms | -1ms | -21.021
| |  P99| 37ms| 24ms | -13ms | -35.230
| ThreadStore.UpdateMembership |  Avg| 5ms| 4ms | -1ms | -20.731
| |  P99| 44ms| 34ms | -10ms | -22.880
| TokenStore.Cleanup |  Avg| 2ms| 1ms | -1ms | -63.709
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 10ms| 40ms | 30ms | 298.460
| |  P99| 216ms| 1.735s | 1.519s | 702.424
| UserStore.AutocompleteUsersInChannel |  Avg| 367ms| 325ms | -42ms | -11.436
| |  P99| 1.3s| 995ms | -305ms | -23.462
| UserStore.Count |  Avg| 191ms| 183ms | -8ms | -4.188
| |  P99| 895ms| 725ms | -170ms | -18.994
| UserStore.Get |  Avg| 12ms| 8ms | -4ms | -33.561
| |  P99| 237ms| 193ms | -44ms | -18.537
| UserStore.GetAllProfiles |  Avg| 29ms| 18ms | -11ms | -38.305
| |  P99| 341ms| 237ms | -104ms | -30.475
| UserStore.GetAllProfilesInChannel |  Avg| 751ms| 655ms | -96ms | -12.782
| |  P99| 2.449s| 2.424s | -25ms | -1.021
| UserStore.GetByUsername |  Avg| 28ms| 27ms | -1ms | -3.528
| |  P99| 455ms| 439ms | -16ms | -3.516
| UserStore.GetForLogin |  Avg| 23ms| 15ms | -8ms | -34.722
| |  P99| 341ms| 235ms | -106ms | -31.056
| UserStore.GetMany |  Avg| 55ms| 9ms | -46ms | -83.832
| |  P99| 895ms| 88ms | -807ms | -90.170
| UserStore.GetProfileByIds |  Avg| 18ms| 13ms | -5ms | -27.196
| |  P99| 302ms| 235ms | -67ms | -22.205
| UserStore.GetProfilesByUsernames |  Avg| 26ms| 18ms | -8ms | -30.877
| |  P99| 383ms| 248ms | -135ms | -35.249
| UserStore.GetProfilesInChannel |  Avg| 26ms| 25ms | -1ms | -3.880
| |  P99| 300ms| 326ms | 26ms | 8.675
| UserStore.GetUnreadCount |  Avg| 29ms| 22ms | -7ms | -24.209
| |  P99| 441ms| 363ms | -78ms | -17.680
| UserStore.IsEmpty |  Avg| 16ms| 10ms | -6ms | -38.020
| |  P99| 232ms| 192ms | -40ms | -17.205
| UserStore.Save |  Avg| 71ms| 70ms | -1ms | -1.406
| |  P99| 221ms| 207ms | -14ms | -6.324
| UserStore.Search |  Avg| 178ms| 157ms | -21ms | -11.798
| |  P99| 903ms| 844ms | -59ms | -6.536
| UserStore.Update |  Avg| 6ms| 8ms | 2ms | 31.670
| |  P99| 41ms| 143ms | 102ms | 245.784
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 24ms | -9ms | -27.183
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 22ms | -3ms | -12.187
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 24ms | -7ms | -22.697
| UserTermsOfServiceStore.GetByUser |  Avg| 27ms| 17ms | -10ms | -37.395
| |  P99| 377ms| 246ms | -131ms | -34.788
| WebhookStore.GetOutgoingByTeam |  Avg| 34ms| 23ms | -11ms | -32.290
| |  P99| 433ms| 349ms | -84ms | -19.394
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 686ms| 504ms | -182ms | -26.550
| | P99| 4.743s| 4.15s | -593ms | -12.503
| addTeamMember | Avg| 2.164s| 1.77s | -394ms | -18.209
| | P99| 9.459s| 8.816s | -643ms | -6.798
| autocompleteChannelsForTeamForSearch | Avg| 279ms| 198ms | -81ms | -29.059
| | P99| 2.101s| 981ms | -1.12s | -53.297
| autocompleteUsers | Avg| 292ms| 264ms | -28ms | -9.587
| | P99| 997ms| 983ms | -14ms | -1.404
| createCategoryForTeamForUser | Avg| 16ms| 15ms | -1ms | -6.379
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 71ms| 90ms | 19ms | 26.613
| | P99| 232ms| 243ms | 11ms | 4.741
| createDirectChannel | Avg| 406ms| 269ms | -137ms | -33.772
| | P99| 2.318s| 984ms | -1.334s | -57.554
| createGroupChannel | Avg| 767ms| 612ms | -155ms | -20.217
| | P99| 4.58s| 4.333s | -247ms | -5.393
| createPost | Avg| 1.064s| 998ms | -66ms | -6.201
| | P99| 5.446s| 4.661s | -785ms | -14.415
| createUser | Avg| 140ms| 121ms | -19ms | -13.525
| | P99| 778ms| 522ms | -256ms | -32.886
| deleteDraft | Avg| 5ms| 70ms | 65ms | 1369.798
| | P99| 5ms| 243ms | 238ms | 4808.081
| deletePost | Avg| 230ms| 181ms | -49ms | -21.283
| | P99| 963ms| 940ms | -23ms | -2.390
| followThreadByUser | Avg| 109ms| 64ms | -45ms | -41.191
| | P99| 486ms| 470ms | -16ms | -3.293
| getAllTeams | Avg| 31ms| 19ms | -12ms | -39.046
| | P99| 406ms| 274ms | -132ms | -32.479
| getCategoriesForTeamForUser | Avg| 74ms| 54ms | -20ms | -26.887
| | P99| 891ms| 782ms | -109ms | -12.229
| getChannel | Avg| 65ms| 36ms | -29ms | -44.634
| | P99| 788ms| 435ms | -353ms | -44.825
| getChannelMember | Avg| 15ms| 9ms | -6ms | -41.213
| | P99| 319ms| 214ms | -105ms | -32.870
| getChannelMembers | Avg| 86ms| 37ms | -49ms | -56.978
| | P99| 246ms| 99ms | -147ms | -59.877
| getChannelMembersForTeamForUser | Avg| 33ms| 23ms | -10ms | -30.257
| | P99| 426ms| 317ms | -109ms | -25.604
| getChannelStats | Avg| 61ms| 47ms | -14ms | -22.960
| | P99| 964ms| 873ms | -91ms | -9.442
| getChannelUnread | Avg| 17ms| 12ms | -5ms | -29.840
| | P99| 276ms| 224ms | -52ms | -18.862
| getChannelsForTeamForUser | Avg| 35ms| 24ms | -11ms | -31.822
| | P99| 451ms| 373ms | -78ms | -17.305
| getChannelsForUser | Avg| 25ms| 20ms | -5ms | -19.910
| | P99| 363ms| 302ms | -61ms | -16.809
| getClientConfig | Avg| 10ms| 8ms | -2ms | -19.932
| | P99| 189ms| 122ms | -67ms | -35.486
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 28ms| 29ms | 1ms | 3.534
| | P99| 99ms| 115ms | 16ms | 16.173
| getFilePreview | Avg| 82ms| 73ms | -9ms | -10.941
| | P99| 656ms| 494ms | -162ms | -24.694
| getFileThumbnail | Avg| 76ms| 64ms | -12ms | -15.823
| | P99| 692ms| 499ms | -193ms | -27.909
| getGroups | Avg| 2ms| 20ms | 18ms | 866.923
| | P99| 5ms| 98ms | 93ms | 1878.788
| getPostThread | Avg| 191ms| 135ms | -56ms | -29.311
| | P99| 2.285s| 2.03s | -255ms | -11.159
| getPostsForChannel | Avg| 250ms| 170ms | -80ms | -31.971
| | P99| 3.966s| 2.629s | -1.337s | -33.716
| getPostsForChannelAroundLastUnread | Avg| 156ms| 110ms | -46ms | -29.449
| | P99| 2.135s| 1.808s | -327ms | -15.315
| getPreferences | Avg| 36ms| 23ms | -13ms | -35.674
| | P99| 430ms| 308ms | -122ms | -28.369
| getPrevTrialLicense | Avg| 2ms| 12ms | 10ms | 657.412
| | P99| 5ms| 49ms | 44ms | 888.889
| getProfileImage | Avg| 88ms| 66ms | -22ms | -25.019
| | P99| 469ms| 453ms | -16ms | -3.412
| getPublicChannelsForTeam | Avg| 56ms| 47ms | -9ms | -16.030
| | P99| 455ms| 415ms | -40ms | -8.791
| getRolesByNames | Avg| 2ms| 9ms | 7ms | 447.895
| | P99| 5ms| 48ms | 43ms | 868.687
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 61ms| 31ms | -30ms | -49.313
| getTeamMembersForUser | Avg| 21ms| 15ms | -6ms | -28.157
| | P99| 308ms| 231ms | -77ms | -25.017
| getTeamsForUser | Avg| 32ms| 20ms | -12ms | -37.641
| | P99| 407ms| 260ms | -147ms | -36.099
| getTeamsUnreadForUser | Avg| 46ms| 31ms | -15ms | -32.662
| | P99| 602ms| 459ms | -143ms | -23.738
| getThreadsForUser | Avg| 36ms| 24ms | -12ms | -33.070
| | P99| 460ms| 368ms | -92ms | -20.020
| getUser | Avg| 38ms| 25ms | -13ms | -34.093
| | P99| 438ms| 363ms | -75ms | -17.134
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 40ms| 29ms | -11ms | -27.745
| | P99| 439ms| 355ms | -84ms | -19.138
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 60ms| 37ms | -23ms | -38.236
| getUsersByNames | Avg| 26ms| 18ms | -8ms | -30.377
| | P99| 388ms| 249ms | -139ms | -35.846
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 160ms| 130ms | -30ms | -18.807
| | P99| 976ms| 888ms | -88ms | -9.016
| logout | Avg| 72ms| 113ms | 41ms | 56.555
| | P99| 232ms| 480ms | 248ms | 106.736
| patchPost | Avg| 639ms| 272ms | -367ms | -57.430
| | P99| 2.462s| 2.449s | -13ms | -0.528
| removeUserCustomStatus | Avg| 194ms| 144ms | -50ms | -25.735
| | P99| 500ms| 481ms | -19ms | -3.800
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 80.808
| saveReaction | Avg| 184ms| 125ms | -59ms | -32.070
| | P99| 2.228s| 1.958s | -270ms | -12.118
| searchAllChannels | Avg| 2.197s| 2.072s | -125ms | -5.690
| | P99| 9.407s| 9.22s | -187ms | -1.988
| searchGroupChannels | Avg| 35ms| 26ms | -9ms | -25.806
| | P99| 432ms| 409ms | -23ms | -5.321
| searchPostsInTeam | Avg| 207ms| 151ms | -56ms | -27.112
| | P99| 2.365s| 2.295s | -70ms | -2.960
| searchUsers | Avg| 183ms| 159ms | -24ms | -13.146
| | P99| 909ms| 848ms | -61ms | -6.712
| setPostReminder | Avg| 266ms| 174ms | -92ms | -34.573
| | P99| 2.372s| 2.365s | -7ms | -0.295
| unfollowThreadByUser | Avg| 70ms| 55ms | -15ms | -21.341
| | P99| 625ms| 695ms | 70ms | 11.201
| updateCategoriesForTeamForUser | Avg| 192ms| 189ms | -3ms | -1.559
| | P99| 2.005s| 950ms | -1.055s | -52.622
| updatePreferences | Avg| 11ms| 8ms | -3ms | -27.495
| | P99| 138ms| 79ms | -59ms | -42.721
| updateReadStateAllThreadsByUser | Avg| 5ms| 6ms | 1ms | 20.243
| | P99| 5ms| 25ms | 20ms | 404.040
| updateReadStateThreadByUser | Avg| 256ms| 185ms | -71ms | -27.739
| | P99| 2.45s| 2.255s | -195ms | -7.958
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 432ms| 434ms | 2ms | 0.462
| | P99| 998ms| 992ms | -6ms | -0.601
| upsertDraft | Avg| 4ms| 6ms | 2ms | 55.056
| | P99| 10ms| 25ms | 15ms | 153.010
| viewChannel | Avg| 72ms| 52ms | -20ms | -27.958
| | P99| 855ms| 680ms | -175ms | -20.470

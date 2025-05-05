### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | avg | 1ms | 196ms | 195ms | 13670.35
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 19ms | 1.243s | 1.224s | 6492.19
| TeamStore.AnalyticsTeamCount | avg | 2ms | 61ms | 59ms | 3396.44
| LicenseStore.GetAll | avg | 3ms | 48ms | 45ms | 1648.60
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 45ms | 532ms | 487ms | 1073.31
| TokenStore.Cleanup | avg | 2ms | 23ms | 21ms | 1036.60
| CommandWebhookStore.Cleanup | avg | 2ms | 18ms | 16ms | 756.70
| ChannelStore.GetMembersForUserWithPagination | avg | 55ms | 322ms | 267ms | 486.43
| ProductNoticesStore.GetViews | avg | 20ms | 78ms | 58ms | 283.18
| EmojiStore.GetMultipleByName | avg | 47ms | 159ms | 112ms | 235.98
| PluginStore.Get | avg | 53ms | 130ms | 77ms | 145.59
| ChannelStore.AnalyticsCountAll | avg | 130ms | 311ms | 181ms | 139.39
| ChannelBookmarkStore.UpdateSortOrder | avg | 59ms | 139ms | 80ms | 134.97
| PostStore.Delete | avg | 54ms | 127ms | 73ms | 134.42
| PluginStore.List | avg | 34ms | 80ms | 46ms | 133.38
| BotStore.Get | avg | 67ms | 116ms | 49ms | 72.71
| RoleStore.GetByNames | avg | 108ms | 182ms | 74ms | 68.41
| PostStore.AnalyticsPostCount | avg | 940ms | 1.55s | 610ms | 64.92
| PostStore.AnalyticsPostCountByTeam | avg | 807ms | 1.303s | 496ms | 61.49
| PostStore.GetPostReminders | avg | 17ms | 26ms | 9ms | 52.54
| RoleStore.ChannelHigherScopedPermissions | avg | 98ms | 144ms | 46ms | 46.97
| SessionStore.Remove | avg | 6ms | 9ms | 3ms | 46.70
| LinkMetadataStore.Save | avg | 7ms | 10ms | 3ms | 42.64
| UserStore.GetProfilesInChannel | avg | 55ms | 78ms | 23ms | 41.74
| JobStore.GetAllByTypePage | avg | 71ms | 100ms | 29ms | 40.98
| ScheduledPostStore.GetPendingScheduledPosts | avg | 91ms | 128ms | 37ms | 40.81
| StatusStore.UpdateExpiredDNDStatuses | avg | 15ms | 21ms | 6ms | 40.36
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 43ms | 57ms | 14ms | 32.35
| ClusterDiscoveryStore.SetLastPingAt | avg | 11ms | 14ms | 3ms | 27.79
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 40ms | 51ms | 11ms | 27.22
| ChannelStore.GetSidebarCategory | avg | 68ms | 86ms | 18ms | 26.52
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 98ms | 122ms | 24ms | 24.56
| PostStore.SetPostReminder | avg | 25ms | 31ms | 6ms | 24.17
| PostStore.GetPosts | avg | 30ms | 37ms | 7ms | 23.31
| JobStore.UpdateStatusOptimistically | avg | 18ms | 22ms | 4ms | 22.30
| UserStore.IsEmpty | avg | 18ms | 22ms | 4ms | 21.83
| ReactionStore.GetForPost | avg | 60ms | 73ms | 13ms | 21.73
| ChannelStore.GetMemberLastViewedAt | avg | 32ms | 39ms | 7ms | 21.68
| ScheduledPostStore.GetScheduledPostsForUser | avg | 32ms | 39ms | 7ms | 21.67
| ThreadStore.GetTotalUnreadThreads | avg | 43ms | 51ms | 8ms | 18.39
| TeamStore.GetMember | avg | 17ms | 20ms | 3ms | 18.13
| UserStore.GetAllProfiles | avg | 35ms | 41ms | 6ms | 17.24
| TeamStore.GetTeamsByUserId | avg | 47ms | 55ms | 8ms | 17.14
| PostStore.GetPostReminderMetadata | avg | 83ms | 97ms | 14ms | 16.93
| JobStore.GetCountByStatusAndType | avg | 54ms | 63ms | 9ms | 16.76
| TeamStore.GetAllPage | avg | 43ms | 50ms | 7ms | 16.43
| ThreadStore.GetTotalUnreadMentions | avg | 49ms | 57ms | 8ms | 16.17
| ChannelStore.GetPublicChannelsForTeam | avg | 87ms | 101ms | 14ms | 16.11
| ThreadStore.GetTotalThreads | avg | 45ms | 52ms | 7ms | 15.58
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 45ms | 52ms | 7ms | 15.57
| UserStore.Update | avg | 20ms | 23ms | 3ms | 14.77
| PostPriorityStore.GetForPost | avg | 54ms | 62ms | 8ms | 14.69
| ChannelStore.GetChannelsByUser | avg | 55ms | 63ms | 8ms | 14.55
| UserStore.Count | avg | 208ms | 238ms | 30ms | 14.43
| TeamStore.GetChannelUnreadsForAllTeams | avg | 49ms | 56ms | 7ms | 14.32
| GroupStore.GetByName | avg | 28ms | 32ms | 4ms | 14.10
| StatusStore.Get | avg | 50ms | 57ms | 7ms | 13.90
| ChannelStore.GetByName | avg | 45ms | 51ms | 6ms | 13.33
| PostPriorityStore.GetForPosts | avg | 98ms | 111ms | 13ms | 13.20
| UserStore.GetProfilesNotInChannel | avg | 68ms | 77ms | 9ms | 13.14
| PreferenceStore.Save | avg | 23ms | 26ms | 3ms | 13.05
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 54ms | 61ms | 7ms | 12.94
| ChannelStore.CreateInitialSidebarCategories | avg | 70ms | 79ms | 9ms | 12.86
| PostAcknowledgementStore.GetForPosts | avg | 95ms | 107ms | 12ms | 12.68
| SessionStore.Get | avg | 48ms | 54ms | 6ms | 12.54
| ChannelStore.SaveMember | avg | 192ms | 216ms | 24ms | 12.51
| ChannelStore.GetGuestCount | avg | 65ms | 73ms | 8ms | 12.24
| UserStore.Get | avg | 41ms | 46ms | 5ms | 12.17
| TeamStore.GetTeamsForUser | avg | 33ms | 37ms | 4ms | 12.12
| ChannelStore.IsReadOnlyChannel | avg | 33ms | 37ms | 4ms | 11.95
| TeamStore.Get | avg | 59ms | 66ms | 7ms | 11.93
| ThreadStore.GetThreadForUser | avg | 93ms | 104ms | 11ms | 11.89
| ChannelStore.GetMembersForUser | avg | 68ms | 76ms | 8ms | 11.69
| ThreadStore.MaintainMembership | avg | 17ms | 19ms | 2ms | 11.57
| UserStore.GetByUsername | avg | 69ms | 77ms | 8ms | 11.55
| PostStore.GetSingle | avg | 61ms | 68ms | 7ms | 11.52
| PreferenceStore.GetAll | avg | 62ms | 69ms | 7ms | 11.29
| ChannelStore.GetMembers | avg | 36ms | 40ms | 4ms | 11.21
| ChannelStore.SearchGroupChannels | avg | 73ms | 81ms | 8ms | 10.94
| UserStore.GetUnreadCount | avg | 57ms | 63ms | 6ms | 10.56
| PostStore.Save | avg | 29ms | 32ms | 3ms | 10.29
| GroupStore.GetGroups | avg | 68ms | 75ms | 7ms | 10.22
| PreferenceStore.Get | avg | 59ms | 65ms | 6ms | 10.14
| ThreadStore.GetMembershipForUser | avg | 70ms | 77ms | 7ms | 9.99
| UserStore.GetForLogin | avg | 30ms | 33ms | 3ms | 9.95
| ChannelStore.GetChannels | avg | 71ms | 78ms | 7ms | 9.88
| PostPersistentNotificationStore.GetSingle | avg | 72ms | 79ms | 7ms | 9.78
| LinkMetadataStore.Get | avg | 63ms | 69ms | 6ms | 9.58
| ChannelStore.GetAllChannelMembersForUser | avg | 42ms | 46ms | 4ms | 9.49
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 54ms | 59ms | 5ms | 9.32
| UserStore.GetProfileByIds | avg | 54ms | 59ms | 5ms | 9.32
| UserTermsOfServiceStore.GetByUser | avg | 44ms | 48ms | 4ms | 9.05
| UserStore.GetProfilesByUsernames | avg | 44ms | 48ms | 4ms | 8.99
| ThreadStore.GetThreadFollowers | avg | 69ms | 75ms | 6ms | 8.66
| SessionStore.Save | avg | 35ms | 38ms | 3ms | 8.57
| PostStore.GetPostsBefore | avg | 62ms | 67ms | 5ms | 8.13
| SharedChannelStore.HasChannel | avg | 37ms | 40ms | 3ms | 8.09
| ChannelStore.CreateDirectChannel | avg | 221ms | 238ms | 17ms | 7.70
| PostStore.GetPostsAfter | avg | 65ms | 70ms | 5ms | 7.68
| ThreadStore.GetThreadsForUser | avg | 78ms | 84ms | 6ms | 7.66
| PostStore.GetPostsSince | avg | 92ms | 99ms | 7ms | 7.61
| PostStore.GetEtag | avg | 66ms | 71ms | 5ms | 7.53
| FileInfoStore.GetForPost | avg | 82ms | 88ms | 6ms | 7.34
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 29ms | 31ms | 2ms | 6.97
| TeamStore.SaveMember | avg | 131ms | 140ms | 9ms | 6.88
| SessionStore.GetLRUSessions | avg | 30ms | 32ms | 2ms | 6.76
| WebhookStore.GetOutgoingByTeam | avg | 75ms | 80ms | 5ms | 6.66
| ProductNoticesStore.View | avg | 61ms | 65ms | 4ms | 6.52
| StatusStore.GetByIds | avg | 93ms | 99ms | 6ms | 6.49
| PostStore.Get | avg | 130ms | 138ms | 8ms | 6.14
| ChannelStore.Get | avg | 121ms | 128ms | 7ms | 5.79
| ChannelStore.GetMemberForPost | avg | 88ms | 93ms | 5ms | 5.70
| EmojiStore.GetByName | avg | 70ms | 74ms | 4ms | 5.69
| DraftStore.Get | avg | 89ms | 94ms | 5ms | 5.65
| PostStore.GetPostsByThread | avg | 73ms | 77ms | 4ms | 5.46
| FileInfoStore.GetByIds | avg | 78ms | 82ms | 4ms | 5.10
| UserAccessTokenStore.GetByToken | avg | 43ms | 45ms | 2ms | 4.66
| FileInfoStore.Get | avg | 43ms | 45ms | 2ms | 4.61
| ChannelStore.GetChannelUnread | avg | 48ms | 50ms | 2ms | 4.16
| ChannelStore.GetMemberCount | avg | 242ms | 252ms | 10ms | 4.14
| JobStore.GetAllByStatus | avg | 73ms | 76ms | 3ms | 4.12
| ThreadStore.GetThreadUnreadReplyCount | avg | 78ms | 81ms | 3ms | 3.85
| DraftStore.GetDraftsForUser | avg | 83ms | 86ms | 3ms | 3.63
| PostAcknowledgementStore.GetForPost | avg | 58ms | 60ms | 2ms | 3.42
| ChannelStore.GetPinnedPostCount | avg | 73ms | 75ms | 2ms | 2.76
| UserStore.Search | avg | 205ms | 209ms | 4ms | 1.95
| ChannelStore.Autocomplete | avg | 1.588s | 1.613s | 25ms | 1.57
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 985ms | 980ms | 19791.75
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 50ms | 2.485s | 2.435s | 4917.64
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 244ms | 239ms | 4826.76
| LicenseStore.GetAll | p99 | 10ms | 244ms | 234ms | 2398.09
| TokenStore.Cleanup | p99 | 5ms | 98ms | 93ms | 1878.42
| CommandWebhookStore.Cleanup | p99 | 5ms | 96ms | 91ms | 1838.02
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 99ms | 995ms | 896ms | 904.77
| BotStore.Get | p99 | 478ms | 2.132s | 1.654s | 346.03
| ChannelStore.AnalyticsCountAll | p99 | 248ms | 980ms | 732ms | 295.09
| PluginStore.List | p99 | 285ms | 1.03s | 745ms | 261.37
| SessionStore.Remove | p99 | 24ms | 83ms | 59ms | 244.81
| EmojiStore.GetMultipleByName | p99 | 240ms | 805ms | 565ms | 235.42
| RoleStore.GetByNames | p99 | 490ms | 1.313s | 823ms | 167.86
| PostPersistentNotificationStore.DeleteExpired | p99 | 23ms | 60ms | 37ms | 158.97
| PostStore.AnalyticsPostCountByTeam | p99 | 995ms | 2.478s | 1.483s | 149.02
| RoleStore.ChannelHigherScopedPermissions | p99 | 683ms | 1.675s | 992ms | 145.23
| JobStore.GetAllByTypePage | p99 | 472ms | 1.158s | 686ms | 145.19
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 893ms | 2.14s | 1.247s | 139.72
| UserStore.GetProfilesInChannel | p99 | 795ms | 1.795s | 1s | 125.78
| ChannelStore.GetMembersForUserWithPagination | p99 | 455ms | 970ms | 515ms | 113.18
| ChannelBookmarkStore.UpdateSortOrder | p99 | 245ms | 493ms | 248ms | 101.17
| ProductNoticesStore.GetViews | p99 | 50ms | 100ms | 50ms | 100.98
| JobStore.UpdateStatusOptimistically | p99 | 99ms | 199ms | 100ms | 100.71
| ChannelStore.GetMembers | p99 | 243ms | 483ms | 240ms | 98.97
| TeamStore.GetActiveMemberCount | p99 | 971ms | 1.915s | 944ms | 97.24
| PostStore.Delete | p99 | 443ms | 868ms | 425ms | 96.04
| ScheduledPostStore.CreateScheduledPost | p99 | 88ms | 156ms | 68ms | 77.49
| PostStore.GetPostReminders | p99 | 218ms | 380ms | 162ms | 74.40
| TeamStore.GetMember | p99 | 259ms | 405ms | 146ms | 56.44
| PostStore.SetPostReminder | p99 | 227ms | 330ms | 103ms | 45.35
| UserStore.GetAllProfiles | p99 | 490ms | 700ms | 210ms | 42.81
| PostPersistentNotificationStore.Get | p99 | 44ms | 60ms | 16ms | 36.57
| ChannelStore.GetChannelUnread | p99 | 487ms | 650ms | 163ms | 33.46
| ChannelStore.GetMemberLastViewedAt | p99 | 465ms | 618ms | 153ms | 32.91
| ChannelStore.GetPublicChannelsForTeam | p99 | 890ms | 1.178s | 288ms | 32.36
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 600ms | 788ms | 188ms | 31.36
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 181ms | 234ms | 53ms | 29.28
| PostStore.SearchPostsForUser | p99 | 1.043s | 1.347s | 304ms | 29.14
| DraftStore.Upsert | p99 | 99ms | 127ms | 28ms | 28.18
| ThreadStore.GetTotalUnreadThreads | p99 | 602ms | 759ms | 157ms | 26.10
| UserStore.IsEmpty | p99 | 320ms | 402ms | 82ms | 25.59
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 621ms | 779ms | 158ms | 25.43
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 1.557s | 1.951s | 394ms | 25.31
| TeamStore.GetAllPage | p99 | 596ms | 743ms | 147ms | 24.65
| SharedChannelStore.HasChannel | p99 | 494ms | 608ms | 114ms | 23.06
| UserStore.Save | p99 | 274ms | 337ms | 63ms | 22.95
| ChannelStore.GetAllChannelMembersForUser | p99 | 556ms | 678ms | 122ms | 21.95
| FileInfoStore.AttachToPost | p99 | 110ms | 134ms | 24ms | 21.86
| ChannelStore.IsReadOnlyChannel | p99 | 490ms | 595ms | 105ms | 21.42
| UserStore.GetProfilesByUsernames | p99 | 544ms | 660ms | 116ms | 21.32
| SessionStore.Get | p99 | 613ms | 743ms | 130ms | 21.22
| ChannelStore.GetSidebarCategory | p99 | 778ms | 942ms | 164ms | 21.09
| UserStore.Get | p99 | 624ms | 752ms | 128ms | 20.51
| ChannelStore.CreateInitialSidebarCategories | p99 | 707ms | 833ms | 126ms | 17.82
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 691ms | 812ms | 121ms | 17.50
| StatusStore.UpdateExpiredDNDStatuses | p99 | 196ms | 230ms | 34ms | 17.39
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 463ms | 543ms | 80ms | 17.29
| ThreadStore.GetTotalThreads | p99 | 653ms | 765ms | 112ms | 17.16
| TeamStore.GetTeamsByUserId | p99 | 683ms | 800ms | 117ms | 17.12
| ChannelStore.GetByName | p99 | 657ms | 765ms | 108ms | 16.45
| PostStore.GetPostIdAfterTime | p99 | 69ms | 80ms | 11ms | 15.88
| PostPriorityStore.GetForPost | p99 | 750ms | 869ms | 119ms | 15.87
| FileInfoStore.Save | p99 | 128ms | 148ms | 20ms | 15.57
| ChannelStore.GetChannelsByUser | p99 | 695ms | 803ms | 108ms | 15.53
| ThreadStore.GetThreadForUser | p99 | 1.405s | 1.615s | 210ms | 14.95
| ThreadStore.GetTotalUnreadMentions | p99 | 726ms | 834ms | 108ms | 14.87
| PostStore.GetPosts | p99 | 436ms | 499ms | 63ms | 14.43
| PluginStore.Delete | p99 | 44ms | 50ms | 6ms | 13.60
| UserStore.GetProfilesNotInChannel | p99 | 825ms | 935ms | 110ms | 13.33
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 77ms | 87ms | 10ms | 13.04
| FileInfoStore.Get | p99 | 550ms | 621ms | 71ms | 12.92
| ChannelStore.GetFileCount | p99 | 491ms | 548ms | 57ms | 11.60
| PluginStore.SetWithOptions | p99 | 95ms | 106ms | 11ms | 11.57
| ChannelStore.GetMember | p99 | 173ms | 192ms | 19ms | 11.01
| SystemStore.GetByName | p99 | 74ms | 82ms | 8ms | 10.74
| ChannelStore.UpdateLastViewedAt | p99 | 169ms | 186ms | 17ms | 10.08
| UserTermsOfServiceStore.GetByUser | p99 | 655ms | 717ms | 62ms | 9.47
| TeamStore.GetTeamsForUser | p99 | 442ms | 483ms | 41ms | 9.27
| UserStore.UpdateUpdateAt | p99 | 77ms | 84ms | 7ms | 9.09
| PostAcknowledgementStore.GetForPosts | p99 | 1.784s | 1.944s | 160ms | 8.97
| AuditStore.Save | p99 | 81ms | 88ms | 7ms | 8.65
| TeamStore.SaveMember | p99 | 811ms | 879ms | 68ms | 8.38
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 781ms | 845ms | 64ms | 8.19
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 440ms | 476ms | 36ms | 8.19
| ProductNoticesStore.View | p99 | 436ms | 471ms | 35ms | 8.02
| GroupStore.GetByName | p99 | 427ms | 460ms | 33ms | 7.73
| PostPriorityStore.GetForPosts | p99 | 1.827s | 1.965s | 138ms | 7.55
| ThreadStore.MaintainMembership | p99 | 202ms | 217ms | 15ms | 7.42
| UserStore.UpdateLastLogin | p99 | 70ms | 75ms | 5ms | 7.17
| UserStore.GetProfileByIds | p99 | 787ms | 843ms | 56ms | 7.12
| ChannelStore.IncrementMentionCount | p99 | 87ms | 93ms | 6ms | 6.91
| PostStore.GetPostsBefore | p99 | 815ms | 868ms | 53ms | 6.50
| ThreadStore.UpdateMembership | p99 | 93ms | 99ms | 6ms | 6.43
| SessionStore.Save | p99 | 439ms | 467ms | 28ms | 6.38
| UserStore.GetUnreadCount | p99 | 833ms | 885ms | 52ms | 6.24
| PreferenceStore.Get | p99 | 828ms | 876ms | 48ms | 5.79
| ThreadStore.MarkAsRead | p99 | 87ms | 92ms | 5ms | 5.73
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 825ms | 872ms | 47ms | 5.69
| UserStore.GetForLogin | p99 | 441ms | 466ms | 25ms | 5.67
| TeamStore.Get | p99 | 852ms | 900ms | 48ms | 5.63
| PostStore.GetPostIdBeforeTime | p99 | 89ms | 94ms | 5ms | 5.60
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 74ms | 78ms | 4ms | 5.42
| SessionStore.GetLRUSessions | p99 | 445ms | 469ms | 24ms | 5.39
| ThreadStore.Get | p99 | 919ms | 968ms | 49ms | 5.33
| ChannelStore.CreateDirectChannel | p99 | 2.272s | 2.391s | 119ms | 5.24
| ClusterDiscoveryStore.SetLastPingAt | p99 | 96ms | 101ms | 5ms | 5.22
| PostStore.GetSingle | p99 | 863ms | 907ms | 44ms | 5.10
| LinkMetadataStore.Get | p99 | 872ms | 912ms | 40ms | 4.59
| UserStore.Search | p99 | 1.318s | 1.377s | 59ms | 4.48
| PreferenceStore.Save | p99 | 228ms | 238ms | 10ms | 4.39
| UserStore.Update | p99 | 216ms | 225ms | 9ms | 4.17
| ChannelStore.GetGuestCount | p99 | 893ms | 927ms | 34ms | 3.81
| PreferenceStore.GetAll | p99 | 852ms | 883ms | 31ms | 3.64
| UserStore.UpdateFailedPasswordAttempts | p99 | 84ms | 87ms | 3ms | 3.59
| SessionStore.UpdateLastActivityAt | p99 | 87ms | 90ms | 3ms | 3.45
| PostPersistentNotificationStore.GetSingle | p99 | 922ms | 952ms | 30ms | 3.25
| ThreadStore.MarkAllAsReadByChannels | p99 | 93ms | 96ms | 3ms | 3.23
| ChannelStore.GetChannels | p99 | 905ms | 934ms | 29ms | 3.20
| FileInfoStore.SetContent | p99 | 198ms | 204ms | 6ms | 3.02
| PostStore.GetEtag | p99 | 862ms | 888ms | 26ms | 3.02
| JobStore.GetAllByStatus | p99 | 863ms | 889ms | 26ms | 3.01
| PostStore.Save | p99 | 241ms | 248ms | 7ms | 2.91
| ChannelStore.GetMembersForUser | p99 | 901ms | 925ms | 24ms | 2.66
| PostStore.GetPostsSince | p99 | 934ms | 954ms | 20ms | 2.14
| StatusStore.UpdateLastActivityAt | p99 | 94ms | 96ms | 2ms | 2.13
| ChannelStore.SearchGroupChannels | p99 | 899ms | 918ms | 19ms | 2.11
| GroupStore.GetGroups | p99 | 919ms | 937ms | 18ms | 1.96
| StatusStore.Get | p99 | 793ms | 808ms | 15ms | 1.89
| StatusStore.SaveOrUpdate | p99 | 219ms | 223ms | 4ms | 1.82
| ThreadStore.GetThreadsForUser | p99 | 942ms | 959ms | 17ms | 1.80
| ChannelStore.SaveMember | p99 | 2.385s | 2.423s | 38ms | 1.59
| ThreadStore.GetMembershipForUser | p99 | 931ms | 942ms | 11ms | 1.18
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | avg | 6ms | 0s | -6ms | -102.95
| PostPersistentNotificationStore.UpdateLastActivity | avg | 15ms | 0s | -15ms | -100.35
| TeamStore.GetMany | avg | 165ms | 0s | -165ms | -100.18
| PostStore.GetPostsByIds | avg | 375ms | 0s | -375ms | -99.92
| ChannelStore.GetChannelsByIds | avg | 237ms | 0s | -237ms | -99.82
| ChannelStore.GetMemberCountsByGroup | avg | 8ms | 0s | -8ms | -98.11
| ChannelStore.CreateSidebarCategory | avg | 131ms | 44ms | -87ms | -66.55
| ThreadStore.MarkAllAsReadByTeam | avg | 23ms | 8ms | -15ms | -64.98
| ProductNoticesStore.ClearOldNotices | avg | 5ms | 2ms | -3ms | -64.84
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 9ms | 5ms | -4ms | -46.11
| ChannelStore.GetTeamChannels | avg | 213ms | 120ms | -93ms | -43.57
| ChannelBookmarkStore.Save | avg | 69ms | 40ms | -29ms | -42.30
| ChannelBookmarkStore.Delete | avg | 27ms | 16ms | -11ms | -41.15
| SystemStore.PermanentDeleteByName | avg | 6ms | 4ms | -2ms | -31.41
| ChannelBookmarkStore.Get | avg | 81ms | 58ms | -23ms | -28.23
| UserStore.GetMany | avg | 69ms | 52ms | -17ms | -24.56
| JobStore.UpdateOptimistically | avg | 10ms | 8ms | -2ms | -20.87
| ChannelStore.UpdateSidebarCategories | avg | 273ms | 225ms | -48ms | -17.61
| PreferenceStore.DeleteCategoryAndName | avg | 19ms | 17ms | -2ms | -10.58
| SessionStore.GetSessionsExpired | avg | 103ms | 93ms | -10ms | -9.68
| TeamStore.GetTotalMemberCount | avg | 300ms | 276ms | -24ms | -7.99
| TeamStore.GetActiveMemberCount | avg | 328ms | 305ms | -23ms | -7.01
| PostStore.SearchPostsForUser | avg | 129ms | 122ms | -7ms | -5.42
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 96ms | 93ms | -3ms | -3.14
| ChannelStore.Save | avg | 112ms | 109ms | -3ms | -2.69
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | p99 | 25ms | 0s | -25ms | -101.83
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 975ms | 0s | -975ms | -100.00
| TeamStore.GetMany | p99 | 975ms | 0s | -975ms | -100.00
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 49ms | 0s | -49ms | -100.00
| PostStore.GetPostsByIds | p99 | 2.44s | 0s | -2.44s | -100.00
| ChannelStore.GetMemberCountsByGroup | p99 | 88ms | 0s | -88ms | -99.71
| ThreadStore.MarkAllAsReadByTeam | p99 | 238ms | 25ms | -213ms | -89.50
| UserAccessTokenStore.GetByToken | p99 | 1.42s | 464ms | -956ms | -67.32
| ChannelStore.GetTeamChannels | p99 | 2.32s | 897ms | -1.423s | -61.34
| ChannelStore.UpdateSidebarCategories | p99 | 5.45s | 2.19s | -3.26s | -59.81
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 186ms | 76ms | -110ms | -59.30
| ChannelBookmarkStore.Delete | p99 | 232ms | 96ms | -136ms | -58.62
| UserStore.AnalyticsActiveCount | p99 | 2.35s | 987ms | -1.363s | -58.00
| ChannelBookmarkStore.Save | p99 | 780ms | 373ms | -407ms | -52.18
| ChannelStore.CreateSidebarCategory | p99 | 489ms | 237ms | -252ms | -51.52
| UserStore.GetMany | p99 | 990ms | 486ms | -504ms | -50.91
| ProductNoticesStore.ClearOldNotices | p99 | 10ms | 5ms | -5ms | -50.51
| SystemStore.SaveOrUpdate | p99 | 10ms | 5ms | -5ms | -50.50
| SystemStore.PermanentDeleteByName | p99 | 10ms | 5ms | -5ms | -50.25
| UserStore.Count | p99 | 1.915s | 954ms | -961ms | -50.18
| PluginStore.Get | p99 | 463ms | 248ms | -215ms | -46.49
| PreferenceStore.DeleteCategoryAndName | p99 | 385ms | 224ms | -161ms | -41.82
| ChannelStore.Save | p99 | 1.62s | 993ms | -627ms | -38.70
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 1.517s | 994ms | -523ms | -34.47
| JobStore.GetCountByStatusAndType | p99 | 685ms | 488ms | -197ms | -28.76
| JobStore.GetNewestJobByStatusesAndType | p99 | 949ms | 708ms | -241ms | -25.40
| ThreadStore.GetTeamsUnreadForUser | p99 | 1.29s | 993ms | -297ms | -23.02
| JobStore.UpdateOptimistically | p99 | 89ms | 73ms | -16ms | -18.08
| JobStore.Save | p99 | 92ms | 77ms | -15ms | -16.32
| TeamStore.GetTotalMemberCount | p99 | 2.238s | 1.915s | -323ms | -14.44
| FileInfoStore.GetByIds | p99 | 1.039s | 898ms | -141ms | -13.57
| ChannelStore.Get | p99 | 1.39s | 1.211s | -179ms | -12.87
| ChannelStore.GetMemberCount | p99 | 1.756s | 1.557s | -199ms | -11.33
| StatusStore.GetByIds | p99 | 1.094s | 994ms | -100ms | -9.14
| JobStore.UpdateStatus | p99 | 72ms | 66ms | -6ms | -8.33
| UserStore.GetAllProfilesInChannel | p99 | 2.653s | 2.463s | -190ms | -7.16
| PostStore.GetPostsAfter | p99 | 929ms | 882ms | -47ms | -5.06
| PostStore.GetPostReminderMetadata | p99 | 1.585s | 1.51s | -75ms | -4.73
| ChannelBookmarkStore.Get | p99 | 825ms | 796ms | -29ms | -3.52
| PostAcknowledgementStore.GetForPost | p99 | 1.12s | 1.082s | -38ms | -3.39
| ChannelStore.GetPinnedPostCount | p99 | 974ms | 942ms | -32ms | -3.29
| UserStore.AutocompleteUsersInChannel | p99 | 2.289s | 2.216s | -73ms | -3.19
| ThreadStore.GetThreadFollowers | p99 | 952ms | 923ms | -29ms | -3.05
| PostStore.GetPostsByThread | p99 | 967ms | 944ms | -23ms | -2.38
| SessionStore.GetSessionsExpired | p99 | 915ms | 895ms | -20ms | -2.19
| EmojiStore.GetByName | p99 | 945ms | 925ms | -20ms | -2.12
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.404s | 2.36s | -44ms | -1.83
| ChannelStore.Autocomplete | p99 | 4.96s | 4.899s | -61ms | -1.23
| DraftStore.GetDraftsForUser | p99 | 957ms | 946ms | -11ms | -1.15
| DraftStore.Get | p99 | 993ms | 982ms | -11ms | -1.11
| ThreadStore.GetThreadUnreadReplyCount | p99 | 980ms | 970ms | -10ms | -1.02
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | avg | 37ms | 1.243s | 1.206s | 3278.36
| getGroups | avg | 39ms | 859ms | 820ms | 2129.15
| getChannelMembersForUser | avg | 112ms | 534ms | 422ms | 378.33
| deletePost | avg | 168ms | 337ms | 169ms | 100.54
| getFilteredUsersStats | avg | 133ms | 234ms | 101ms | 76.07
| logout | avg | 120ms | 210ms | 90ms | 75.00
| getAnalytics | avg | 479ms | 794ms | 315ms | 65.81
| setPostReminder | avg | 300ms | 487ms | 187ms | 62.25
| getJobsByType | avg | 71ms | 100ms | 29ms | 40.65
| updateChannelBookmark | avg | 101ms | 137ms | 36ms | 35.57
| getCategoriesForTeamForUser | avg | 98ms | 123ms | 25ms | 25.45
| removeUserCustomStatus | avg | 279ms | 338ms | 59ms | 21.12
| getPostsForChannelAroundLastUnread | avg | 184ms | 222ms | 38ms | 20.66
| getTeamScheduledPosts | avg | 65ms | 78ms | 13ms | 20.07
| getChannelMembers | avg | 36ms | 43ms | 7ms | 19.36
| getPostsForChannel | avg | 656ms | 770ms | 114ms | 17.37
| getTeamMember | avg | 12ms | 14ms | 2ms | 17.15
| getTeamsForUser | avg | 47ms | 55ms | 8ms | 17.08
| getPublicChannelsForTeam | avg | 88ms | 102ms | 14ms | 15.90
| getAllTeams | avg | 46ms | 53ms | 7ms | 15.17
| getChannelsForUser | avg | 55ms | 63ms | 8ms | 14.46
| updatePreferences | avg | 33ms | 37ms | 4ms | 12.17
| getChannelsForTeamForUser | avg | 71ms | 79ms | 8ms | 11.19
| getPreferences | avg | 63ms | 70ms | 7ms | 11.04
| searchGroupChannels | avg | 73ms | 81ms | 8ms | 10.92
| getTeamMembersForUser | avg | 37ms | 41ms | 4ms | 10.89
| getChannelMembersForTeamForUser | avg | 69ms | 76ms | 7ms | 10.16
| getTeamsUnreadForUser | avg | 93ms | 102ms | 9ms | 9.66
| getClientConfig | avg | 21ms | 23ms | 2ms | 9.36
| saveReaction | avg | 222ms | 242ms | 20ms | 9.02
| getUsersByNames | avg | 45ms | 49ms | 4ms | 8.83
| listChannelBookmarksForChannel | avg | 34ms | 37ms | 3ms | 8.76
| updateChannelBookmarkSortOrder | avg | 96ms | 104ms | 8ms | 8.33
| getUsers | avg | 51ms | 55ms | 4ms | 7.87
| getChannel | avg | 133ms | 143ms | 10ms | 7.51
| login | avg | 163ms | 175ms | 12ms | 7.37
| createDirectChannel | avg | 739ms | 793ms | 54ms | 7.31
| viewChannel | avg | 224ms | 240ms | 16ms | 7.16
| getDrafts | avg | 87ms | 93ms | 6ms | 6.88
| getChannelMember | avg | 74ms | 79ms | 5ms | 6.78
| updateReadStateThreadByUser | avg | 638ms | 681ms | 43ms | 6.74
| deleteDraft | avg | 89ms | 95ms | 6ms | 6.73
| getPostThread | avg | 410ms | 437ms | 27ms | 6.58
| getThreadsForUser | avg | 80ms | 85ms | 5ms | 6.23
| addTeamMember | avg | 2.197s | 2.326s | 129ms | 5.87
| createUser | avg | 284ms | 300ms | 16ms | 5.63
| upsertDraft | avg | 41ms | 43ms | 2ms | 4.90
| createGroupChannel | avg | 1.504s | 1.57s | 66ms | 4.39
| getChannelUnread | avg | 52ms | 54ms | 2ms | 3.88
| createPost | avg | 1.229s | 1.275s | 46ms | 3.74
| getFileThumbnail | avg | 93ms | 95ms | 2ms | 2.16
| uploadFileStream | avg | 521ms | 532ms | 11ms | 2.11
| getFilePreview | avg | 95ms | 97ms | 2ms | 2.10
| updateCategoriesForTeamForUser | avg | 457ms | 464ms | 7ms | 1.53
| searchAllChannels | avg | 1.591s | 1.615s | 24ms | 1.51
| searchUsers | avg | 207ms | 210ms | 3ms | 1.45
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | p99 | 50ms | 2.485s | 2.435s | 4893.71
| getGroups | p99 | 99ms | 995ms | 896ms | 904.98
| getJobsByType | p99 | 472ms | 1.158s | 686ms | 145.19
| logout | p99 | 900ms | 1.99s | 1.09s | 121.11
| removeUserCustomStatus | p99 | 1.03s | 2.129s | 1.099s | 106.69
| getChannelMembersForUser | p99 | 485ms | 992ms | 507ms | 104.54
| getChannelMembers | p99 | 243ms | 483ms | 240ms | 98.97
| setPostReminder | p99 | 3.475s | 6.6s | 3.125s | 89.92
| deletePost | p99 | 1.81s | 2.401s | 591ms | 32.65
| getPublicChannelsForTeam | p99 | 890ms | 1.178s | 288ms | 32.36
| getPostsForChannelAroundLastUnread | p99 | 2.566s | 3.313s | 747ms | 29.11
| getCategoriesForTeamForUser | p99 | 1.564s | 1.958s | 394ms | 25.20
| listChannelBookmarksForChannel | p99 | 499ms | 623ms | 124ms | 24.85
| updatePreferences | p99 | 287ms | 349ms | 62ms | 21.62
| getUserStatusesByIds | p99 | 34ms | 41ms | 7ms | 20.59
| getUsersByNames | p99 | 566ms | 676ms | 110ms | 19.44
| getChannelUnread | p99 | 607ms | 720ms | 113ms | 18.62
| getUsersByIds | p99 | 156ms | 185ms | 29ms | 18.59
| getClientConfig | p99 | 246ms | 291ms | 45ms | 18.29
| getAllTeams | p99 | 666ms | 783ms | 117ms | 17.56
| getTeamsForUser | p99 | 686ms | 802ms | 116ms | 16.92
| getTeamMember | p99 | 199ms | 232ms | 33ms | 16.57
| getChannelMember | p99 | 1.134s | 1.309s | 175ms | 15.43
| getChannelsForUser | p99 | 703ms | 805ms | 102ms | 14.51
| upsertDraft | p99 | 656ms | 742ms | 86ms | 13.10
| createChannel | p99 | 8.2s | 9s | 800ms | 9.76
| getTeamMembersForUser | p99 | 472ms | 510ms | 38ms | 8.06
| getTeamScheduledPosts | p99 | 916ms | 984ms | 68ms | 7.43
| getUsers | p99 | 896ms | 944ms | 48ms | 5.36
| getProfileImage | p99 | 461ms | 485ms | 24ms | 5.21
| login | p99 | 1.845s | 1.932s | 87ms | 4.72
| getPostsForChannel | p99 | 9.599s | 10s | 401ms | 4.18
| getPreferences | p99 | 865ms | 898ms | 33ms | 3.82
| searchUsers | p99 | 1.344s | 1.393s | 49ms | 3.65
| updateChannelBookmarkSortOrder | p99 | 473ms | 490ms | 17ms | 3.60
| getChannelsForTeamForUser | p99 | 908ms | 939ms | 31ms | 3.41
| getFilePreview | p99 | 809ms | 836ms | 27ms | 3.34
| uploadFileStream | p99 | 2.172s | 2.244s | 72ms | 3.32
| getChannelStats | p99 | 862ms | 886ms | 24ms | 2.79
| getChannelMembersForTeamForUser | p99 | 903ms | 928ms | 25ms | 2.77
| getFileThumbnail | p99 | 860ms | 881ms | 21ms | 2.44
| searchGroupChannels | p99 | 899ms | 918ms | 19ms | 2.11
| getTeamsUnreadForUser | p99 | 1.689s | 1.715s | 26ms | 1.54
| getAnalytics | p99 | 2.426s | 2.456s | 30ms | 1.24
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | avg | 46ms | 0s | -46ms | -100.35
| getProductNotices | avg | 40ms | 0s | -40ms | -99.17
| channelMemberCountsByGroup | avg | 13ms | 0s | -13ms | -99.06
| createEmoji | avg | 5ms | 0s | -5ms | -96.23
| getRolesByNames | avg | 8ms | 1ms | -7ms | -91.59
| createCategoryForTeamForUser | avg | 202ms | 75ms | -127ms | -62.94
| updateReadStateAllThreadsByUser | avg | 23ms | 9ms | -14ms | -60.38
| getPrevTrialLicense | avg | 3ms | 1ms | -2ms | -57.40
| createSchedulePost | avg | 66ms | 48ms | -18ms | -27.36
| deleteChannelBookmark | avg | 226ms | 178ms | -48ms | -21.27
| createChannelBookmark | avg | 91ms | 75ms | -16ms | -17.49
| followThreadByUser | avg | 224ms | 199ms | -25ms | -11.14
| getProfileImage | avg | 75ms | 71ms | -4ms | -5.31
| getTeamStats | avg | 366ms | 348ms | -18ms | -4.92
| createChannel | avg | 1.318s | 1.265s | -53ms | -4.02
| addChannelMember | avg | 1.277s | 1.23s | -47ms | -3.68
| patchPost | avg | 468ms | 454ms | -14ms | -2.99
| unfollowThreadByUser | avg | 248ms | 243ms | -5ms | -2.02
| searchPostsInTeam | avg | 259ms | 254ms | -5ms | -1.93
| autocompleteUsers | avg | 397ms | 393ms | -4ms | -1.01
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| getProductNotices | p99 | 50ms | 0s | -50ms | -100.49
| channelMemberCountsByGroup | p99 | 180ms | 0s | -180ms | -100.27
| getUsersByGroupChannelIds | p99 | 99ms | 0s | -99ms | -99.97
| getRolesByNames | p99 | 96ms | 5ms | -91ms | -94.76
| updateReadStateAllThreadsByUser | p99 | 238ms | 25ms | -213ms | -89.50
| createCategoryForTeamForUser | p99 | 968ms | 243ms | -725ms | -74.94
| createSchedulePost | p99 | 2.55s | 688ms | -1.862s | -73.03
| getPrevTrialLicense | p99 | 10ms | 5ms | -5ms | -51.00
| unfollowThreadByUser | p99 | 3.65s | 2.358s | -1.292s | -35.40
| createDirectChannel | p99 | 6.817s | 4.721s | -2.096s | -30.75
| updateCategoriesForTeamForUser | p99 | 5.45s | 3.967s | -1.483s | -27.21
| getUser | p99 | 1.686s | 1.306s | -380ms | -22.54
| patchPost | p99 | 4.482s | 3.642s | -840ms | -18.74
| addChannelMember | p99 | 10s | 8.913s | -1.087s | -10.87
| searchPostsInTeam | p99 | 3.958s | 3.556s | -402ms | -10.16
| getChannel | p99 | 2.033s | 1.91s | -123ms | -6.05
| followThreadByUser | p99 | 2.311s | 2.19s | -121ms | -5.24
| createGroupChannel | p99 | 10s | 9.555s | -445ms | -4.45
| viewChannel | p99 | 3.662s | 3.509s | -153ms | -4.18
| createChannelBookmark | p99 | 835ms | 805ms | -30ms | -3.59
| autocompleteUsers | p99 | 2.329s | 2.267s | -62ms | -2.66
| autocompleteChannelsForTeamForSearch | p99 | 2.404s | 2.36s | -44ms | -1.83
| updateReadStateThreadByUser | p99 | 6.55s | 6.438s | -112ms | -1.71
| updateChannelBookmark | p99 | 940ms | 926ms | -14ms | -1.49
| getTeamStats | p99 | 2.238s | 2.208s | -30ms | -1.34
| getPostThread | p99 | 4.44s | 4.384s | -56ms | -1.26
| searchAllChannels | p99 | 4.96s | 4.899s | -61ms | -1.23
| deleteDraft | p99 | 994ms | 982ms | -12ms | -1.21
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 81ms| 88ms | 7ms | 8.652
| BotStore.Get |  Avg| 67ms| 116ms | 49ms | 72.710
| |  P99| 478ms| 2.132s | 1.654s | 346.025
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -97.633
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 27ms| 16ms | -11ms | -41.154
| |  P99| 232ms| 96ms | -136ms | -58.620
| ChannelBookmarkStore.Get |  Avg| 81ms| 58ms | -23ms | -28.229
| |  P99| 825ms| 796ms | -29ms | -3.515
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 29ms| 31ms | 2ms | 6.973
| |  P99| 440ms| 476ms | 36ms | 8.186
| ChannelBookmarkStore.Save |  Avg| 69ms| 40ms | -29ms | -42.300
| |  P99| 780ms| 373ms | -407ms | -52.181
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 59ms| 139ms | 80ms | 134.969
| |  P99| 245ms| 493ms | 248ms | 101.173
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 8ms | 1ms | 13.990
| |  P99| 74ms| 78ms | 4ms | 5.416
| ChannelStore.AnalyticsCountAll |  Avg| 130ms| 311ms | 181ms | 139.389
| |  P99| 248ms| 980ms | 732ms | 295.087
| ChannelStore.Autocomplete |  Avg| 1.588s| 1.613s | 25ms | 1.575
| |  P99| 4.96s| 4.899s | -61ms | -1.230
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 325ms| 327ms | 2ms | 0.615
| |  P99| 2.404s| 2.36s | -44ms | -1.830
| ChannelStore.CreateDirectChannel |  Avg| 221ms| 238ms | 17ms | 7.701
| |  P99| 2.272s| 2.391s | 119ms | 5.237
| ChannelStore.CreateInitialSidebarCategories |  Avg| 70ms| 79ms | 9ms | 12.863
| |  P99| 707ms| 833ms | 126ms | 17.823
| ChannelStore.CreateSidebarCategory |  Avg| 131ms| 44ms | -87ms | -66.547
| |  P99| 489ms| 237ms | -252ms | -51.516
| ChannelStore.Get |  Avg| 121ms| 128ms | 7ms | 5.791
| |  P99| 1.39s| 1.211s | -179ms | -12.874
| ChannelStore.GetAllChannelMembersForUser |  Avg| 42ms| 46ms | 4ms | 9.490
| |  P99| 556ms| 678ms | 122ms | 21.948
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 96ms| 93ms | -3ms | -3.138
| |  P99| 1.517s| 994ms | -523ms | -34.474
| ChannelStore.GetByName |  Avg| 45ms| 51ms | 6ms | 13.326
| |  P99| 657ms| 765ms | 108ms | 16.450
| ChannelStore.GetByNameIncludeDeleted |  Avg| 6ms| 0s | -6ms | -102.952
| |  P99| 25ms| 0s | -25ms | -101.833
| ChannelStore.GetChannelUnread |  Avg| 48ms| 50ms | 2ms | 4.158
| |  P99| 487ms| 650ms | 163ms | 33.456
| ChannelStore.GetChannels |  Avg| 71ms| 78ms | 7ms | 9.879
| |  P99| 905ms| 934ms | 29ms | 3.205
| ChannelStore.GetChannelsByIds |  Avg| 237ms| 0s | -237ms | -99.824
| |  P99| 975ms| 0s | -975ms | -100.000
| ChannelStore.GetChannelsByUser |  Avg| 55ms| 63ms | 8ms | 14.546
| |  P99| 695ms| 803ms | 108ms | 15.534
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 54ms| 59ms | 5ms | 9.320
| |  P99| 781ms| 845ms | 64ms | 8.191
| ChannelStore.GetFileCount |  Avg| 43ms| 44ms | 1ms | 2.317
| |  P99| 491ms| 548ms | 57ms | 11.604
| ChannelStore.GetGuestCount |  Avg| 65ms| 73ms | 8ms | 12.237
| |  P99| 893ms| 927ms | 34ms | 3.807
| ChannelStore.GetMember |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 173ms| 192ms | 19ms | 11.011
| ChannelStore.GetMemberCount |  Avg| 242ms| 252ms | 10ms | 4.136
| |  P99| 1.756s| 1.557s | -199ms | -11.329
| ChannelStore.GetMemberCountsByGroup |  Avg| 8ms| 0s | -8ms | -98.112
| |  P99| 88ms| 0s | -88ms | -99.715
| ChannelStore.GetMemberForPost |  Avg| 88ms| 93ms | 5ms | 5.701
| |  P99| 980ms| 981ms | 1ms | 0.102
| ChannelStore.GetMemberLastViewedAt |  Avg| 32ms| 39ms | 7ms | 21.684
| |  P99| 465ms| 618ms | 153ms | 32.914
| ChannelStore.GetMembers |  Avg| 36ms| 40ms | 4ms | 11.206
| |  P99| 243ms| 483ms | 240ms | 98.969
| ChannelStore.GetMembersForUser |  Avg| 68ms| 76ms | 8ms | 11.692
| |  P99| 901ms| 925ms | 24ms | 2.665
| ChannelStore.GetMembersForUserWithPagination |  Avg| 55ms| 322ms | 267ms | 486.427
| |  P99| 455ms| 970ms | 515ms | 113.185
| ChannelStore.GetPinnedPostCount |  Avg| 73ms| 75ms | 2ms | 2.756
| |  P99| 974ms| 942ms | -32ms | -3.287
| ChannelStore.GetPublicChannelsForTeam |  Avg| 87ms| 101ms | 14ms | 16.113
| |  P99| 890ms| 1.178s | 288ms | 32.359
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 98ms| 122ms | 24ms | 24.561
| |  P99| 1.557s| 1.951s | 394ms | 25.311
| ChannelStore.GetSidebarCategory |  Avg| 68ms| 86ms | 18ms | 26.518
| |  P99| 778ms| 942ms | 164ms | 21.093
| ChannelStore.GetTeamChannels |  Avg| 213ms| 120ms | -93ms | -43.570
| |  P99| 2.32s| 897ms | -1.423s | -61.336
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 93ms | 6ms | 6.913
| ChannelStore.IsReadOnlyChannel |  Avg| 33ms| 37ms | 4ms | 11.949
| |  P99| 490ms| 595ms | 105ms | 21.424
| ChannelStore.Save |  Avg| 112ms| 109ms | -3ms | -2.688
| |  P99| 1.62s| 993ms | -627ms | -38.703
| ChannelStore.SaveMember |  Avg| 192ms| 216ms | 24ms | 12.507
| |  P99| 2.385s| 2.423s | 38ms | 1.593
| ChannelStore.SearchGroupChannels |  Avg| 73ms| 81ms | 8ms | 10.938
| |  P99| 899ms| 918ms | 19ms | 2.113
| ChannelStore.UpdateLastViewedAt |  Avg| 15ms| 16ms | 1ms | 6.779
| |  P99| 169ms| 186ms | 17ms | 10.079
| ChannelStore.UpdateSidebarCategories |  Avg| 273ms| 225ms | -48ms | -17.606
| |  P99| 5.45s| 2.19s | -3.26s | -59.811
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 7ms | 1ms | 16.470
| |  P99| 77ms| 87ms | 10ms | 13.040
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 11ms| 14ms | 3ms | 27.789
| |  P99| 96ms| 101ms | 5ms | 5.220
| CommandWebhookStore.Cleanup |  Avg| 2ms| 18ms | 16ms | 756.700
| |  P99| 5ms| 96ms | 91ms | 1838.020
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 10ms| 11ms | 1ms | 9.826
| |  P99| 95ms| 96ms | 1ms | 1.052
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 43ms| 57ms | 14ms | 32.345
| |  P99| 181ms| 234ms | 53ms | 29.280
| DraftStore.Get |  Avg| 89ms| 94ms | 5ms | 5.649
| |  P99| 993ms| 982ms | -11ms | -1.107
| DraftStore.GetDraftsForUser |  Avg| 83ms| 86ms | 3ms | 3.630
| |  P99| 957ms| 946ms | -11ms | -1.149
| DraftStore.Upsert |  Avg| 11ms| 12ms | 1ms | 9.189
| |  P99| 99ms| 127ms | 28ms | 28.180
| EmojiStore.GetByName |  Avg| 70ms| 74ms | 4ms | 5.686
| |  P99| 945ms| 925ms | -20ms | -2.116
| EmojiStore.GetMultipleByName |  Avg| 47ms| 159ms | 112ms | 235.984
| |  P99| 240ms| 805ms | 565ms | 235.418
| FileInfoStore.AttachToPost |  Avg| 12ms| 13ms | 1ms | 8.146
| |  P99| 110ms| 134ms | 24ms | 21.857
| FileInfoStore.Get |  Avg| 43ms| 45ms | 2ms | 4.606
| |  P99| 550ms| 621ms | 71ms | 12.916
| FileInfoStore.GetByIds |  Avg| 78ms| 82ms | 4ms | 5.096
| |  P99| 1.039s| 898ms | -141ms | -13.567
| FileInfoStore.GetForPost |  Avg| 82ms| 88ms | 6ms | 7.343
| |  P99| 997ms| 994ms | -3ms | -0.301
| FileInfoStore.Save |  Avg| 12ms| 13ms | 1ms | 8.362
| |  P99| 128ms| 148ms | 20ms | 15.573
| FileInfoStore.SetContent |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 198ms| 204ms | 6ms | 3.024
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 40ms| 51ms | 11ms | 27.218
| |  P99| 600ms| 788ms | 188ms | 31.355
| GroupStore.GetByName |  Avg| 28ms| 32ms | 4ms | 14.105
| |  P99| 427ms| 460ms | 33ms | 7.732
| GroupStore.GetGroups |  Avg| 68ms| 75ms | 7ms | 10.220
| |  P99| 919ms| 937ms | 18ms | 1.958
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 19ms| 1.243s | 1.224s | 6492.192
| |  P99| 50ms| 2.485s | 2.435s | 4917.645
| JobStore.GetAllByStatus |  Avg| 73ms| 76ms | 3ms | 4.120
| |  P99| 863ms| 889ms | 26ms | 3.013
| JobStore.GetAllByTypePage |  Avg| 71ms| 100ms | 29ms | 40.983
| |  P99| 472ms| 1.158s | 686ms | 145.186
| JobStore.GetCountByStatusAndType |  Avg| 54ms| 63ms | 9ms | 16.755
| |  P99| 685ms| 488ms | -197ms | -28.759
| JobStore.GetNewestJobByStatusesAndType |  Avg| 59ms| 58ms | -1ms | -1.683
| |  P99| 949ms| 708ms | -241ms | -25.402
| JobStore.Save |  Avg| 10ms| 9ms | -1ms | -10.179
| |  P99| 92ms| 77ms | -15ms | -16.317
| JobStore.UpdateOptimistically |  Avg| 10ms| 8ms | -2ms | -20.872
| |  P99| 89ms| 73ms | -16ms | -18.079
| JobStore.UpdateStatus |  Avg| 8ms| 9ms | 1ms | 13.211
| |  P99| 72ms| 66ms | -6ms | -8.332
| JobStore.UpdateStatusOptimistically |  Avg| 18ms| 22ms | 4ms | 22.296
| |  P99| 99ms| 199ms | 100ms | 100.706
| LicenseStore.GetAll |  Avg| 3ms| 48ms | 45ms | 1648.599
| |  P99| 10ms| 244ms | 234ms | 2398.093
| LinkMetadataStore.Get |  Avg| 63ms| 69ms | 6ms | 9.582
| |  P99| 872ms| 912ms | 40ms | 4.588
| LinkMetadataStore.Save |  Avg| 7ms| 10ms | 3ms | 42.644
| |  P99| 90ms| 90ms | 0s | 0.000
| PluginStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 50ms | 6ms | 13.597
| PluginStore.Get |  Avg| 53ms| 130ms | 77ms | 145.593
| |  P99| 463ms| 248ms | -215ms | -46.486
| PluginStore.List |  Avg| 34ms| 80ms | 46ms | 133.384
| |  P99| 285ms| 1.03s | 745ms | 261.366
| PluginStore.SetWithOptions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 106ms | 11ms | 11.569
| PostAcknowledgementStore.GetForPost |  Avg| 58ms| 60ms | 2ms | 3.424
| |  P99| 1.12s| 1.082s | -38ms | -3.392
| PostAcknowledgementStore.GetForPosts |  Avg| 95ms| 107ms | 12ms | 12.676
| |  P99| 1.784s| 1.944s | 160ms | 8.968
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 5ms | 1ms | 28.240
| |  P99| 23ms| 60ms | 37ms | 158.966
| PostPersistentNotificationStore.Get |  Avg| 5ms| 6ms | 1ms | 20.069
| |  P99| 44ms| 60ms | 16ms | 36.571
| PostPersistentNotificationStore.GetSingle |  Avg| 72ms| 79ms | 7ms | 9.784
| |  P99| 922ms| 952ms | 30ms | 3.253
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 15ms| 0s | -15ms | -100.351
| |  P99| 49ms| 0s | -49ms | -100.000
| PostPriorityStore.GetForPost |  Avg| 54ms| 62ms | 8ms | 14.693
| |  P99| 750ms| 869ms | 119ms | 15.866
| PostPriorityStore.GetForPosts |  Avg| 98ms| 111ms | 13ms | 13.202
| |  P99| 1.827s| 1.965s | 138ms | 7.554
| PostStore.AnalyticsPostCount |  Avg| 940ms| 1.55s | 610ms | 64.920
| |  P99| 2.478s| 2.481s | 3ms | 0.121
| PostStore.AnalyticsPostCountByTeam |  Avg| 807ms| 1.303s | 496ms | 61.485
| |  P99| 995ms| 2.478s | 1.483s | 149.022
| PostStore.Delete |  Avg| 54ms| 127ms | 73ms | 134.425
| |  P99| 443ms| 868ms | 425ms | 96.045
| PostStore.Get |  Avg| 130ms| 138ms | 8ms | 6.144
| |  P99| 1.859s| 1.852s | -7ms | -0.377
| PostStore.GetEtag |  Avg| 66ms| 71ms | 5ms | 7.525
| |  P99| 862ms| 888ms | 26ms | 3.015
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 6ms | 1ms | 19.239
| |  P99| 69ms| 80ms | 11ms | 15.877
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 9ms | 1ms | 12.610
| |  P99| 89ms| 94ms | 5ms | 5.602
| PostStore.GetPostReminderMetadata |  Avg| 83ms| 97ms | 14ms | 16.925
| |  P99| 1.585s| 1.51s | -75ms | -4.731
| PostStore.GetPostReminders |  Avg| 17ms| 26ms | 9ms | 52.540
| |  P99| 218ms| 380ms | 162ms | 74.397
| PostStore.GetPosts |  Avg| 30ms| 37ms | 7ms | 23.308
| |  P99| 436ms| 499ms | 63ms | 14.433
| PostStore.GetPostsAfter |  Avg| 65ms| 70ms | 5ms | 7.680
| |  P99| 929ms| 882ms | -47ms | -5.057
| PostStore.GetPostsBefore |  Avg| 62ms| 67ms | 5ms | 8.125
| |  P99| 815ms| 868ms | 53ms | 6.501
| PostStore.GetPostsByIds |  Avg| 375ms| 0s | -375ms | -99.922
| |  P99| 2.44s| 0s | -2.44s | -100.000
| PostStore.GetPostsByThread |  Avg| 73ms| 77ms | 4ms | 5.458
| |  P99| 967ms| 944ms | -23ms | -2.379
| PostStore.GetPostsSince |  Avg| 92ms| 99ms | 7ms | 7.610
| |  P99| 934ms| 954ms | 20ms | 2.142
| PostStore.GetSingle |  Avg| 61ms| 68ms | 7ms | 11.521
| |  P99| 863ms| 907ms | 44ms | 5.097
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 29ms| 32ms | 3ms | 10.290
| |  P99| 241ms| 248ms | 7ms | 2.907
| PostStore.SearchPostsForUser |  Avg| 129ms| 122ms | -7ms | -5.420
| |  P99| 1.043s| 1.347s | 304ms | 29.141
| PostStore.SetPostReminder |  Avg| 25ms| 31ms | 6ms | 24.170
| |  P99| 227ms| 330ms | 103ms | 45.349
| PostStore.Update |  Avg| 29ms| 30ms | 1ms | 3.450
| |  P99| 214ms| 212ms | -2ms | -0.936
| PreferenceStore.DeleteCategoryAndName |  Avg| 19ms| 17ms | -2ms | -10.576
| |  P99| 385ms| 224ms | -161ms | -41.819
| PreferenceStore.Get |  Avg| 59ms| 65ms | 6ms | 10.143
| |  P99| 828ms| 876ms | 48ms | 5.795
| PreferenceStore.GetAll |  Avg| 62ms| 69ms | 7ms | 11.292
| |  P99| 852ms| 883ms | 31ms | 3.638
| PreferenceStore.Save |  Avg| 23ms| 26ms | 3ms | 13.052
| |  P99| 228ms| 238ms | 10ms | 4.390
| ProductNoticesStore.ClearOldNotices |  Avg| 5ms| 2ms | -3ms | -64.839
| |  P99| 10ms| 5ms | -5ms | -50.505
| ProductNoticesStore.GetViews |  Avg| 20ms| 78ms | 58ms | 283.182
| |  P99| 50ms| 100ms | 50ms | 100.978
| ProductNoticesStore.View |  Avg| 61ms| 65ms | 4ms | 6.517
| |  P99| 436ms| 471ms | 35ms | 8.019
| ReactionStore.GetForPost |  Avg| 60ms| 73ms | 13ms | 21.728
| |  P99| 902ms| 909ms | 7ms | 0.776
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -115.631
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 98ms| 144ms | 46ms | 46.968
| |  P99| 683ms| 1.675s | 992ms | 145.227
| RoleStore.GetByNames |  Avg| 108ms| 182ms | 74ms | 68.407
| |  P99| 490ms| 1.313s | 823ms | 167.865
| ScheduledPostStore.CreateScheduledPost |  Avg| 12ms| 13ms | 1ms | 8.441
| |  P99| 88ms| 156ms | 68ms | 77.493
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 91ms| 128ms | 37ms | 40.808
| |  P99| 893ms| 2.14s | 1.247s | 139.720
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 32ms| 39ms | 7ms | 21.674
| |  P99| 463ms| 543ms | 80ms | 17.287
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 9ms| 5ms | -4ms | -46.110
| |  P99| 186ms| 76ms | -110ms | -59.299
| SessionStore.Get |  Avg| 48ms| 54ms | 6ms | 12.543
| |  P99| 613ms| 743ms | 130ms | 21.216
| SessionStore.GetLRUSessions |  Avg| 30ms| 32ms | 2ms | 6.756
| |  P99| 445ms| 469ms | 24ms | 5.394
| SessionStore.GetSessionsExpired |  Avg| 103ms| 93ms | -10ms | -9.680
| |  P99| 915ms| 895ms | -20ms | -2.186
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 54ms| 61ms | 7ms | 12.937
| |  P99| 825ms| 872ms | 47ms | 5.695
| SessionStore.Remove |  Avg| 6ms| 9ms | 3ms | 46.701
| |  P99| 24ms| 83ms | 59ms | 244.813
| SessionStore.Save |  Avg| 35ms| 38ms | 3ms | 8.565
| |  P99| 439ms| 467ms | 28ms | 6.381
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 10ms | 1ms | 11.127
| |  P99| 87ms| 90ms | 3ms | 3.448
| SharedChannelStore.HasChannel |  Avg| 37ms| 40ms | 3ms | 8.094
| |  P99| 494ms| 608ms | 114ms | 23.060
| StatusStore.Get |  Avg| 50ms| 57ms | 7ms | 13.900
| |  P99| 793ms| 808ms | 15ms | 1.892
| StatusStore.GetByIds |  Avg| 93ms| 99ms | 6ms | 6.485
| |  P99| 1.094s| 994ms | -100ms | -9.139
| StatusStore.SaveOrUpdate |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 219ms| 223ms | 4ms | 1.823
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 15ms| 21ms | 6ms | 40.364
| |  P99| 196ms| 230ms | 34ms | 17.391
| StatusStore.UpdateLastActivityAt |  Avg| 9ms| 10ms | 1ms | 10.838
| |  P99| 94ms| 96ms | 2ms | 2.130
| SystemStore.GetByName |  Avg| 5ms| 6ms | 1ms | 18.909
| |  P99| 74ms| 82ms | 8ms | 10.741
| SystemStore.PermanentDeleteByName |  Avg| 6ms| 4ms | -2ms | -31.408
| |  P99| 10ms| 5ms | -5ms | -50.251
| SystemStore.SaveOrUpdate |  Avg| 5ms| 4ms | -1ms | -21.144
| |  P99| 10ms| 5ms | -5ms | -50.505
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 61ms | 59ms | 3396.443
| |  P99| 5ms| 244ms | 239ms | 4826.764
| TeamStore.Get |  Avg| 59ms| 66ms | 7ms | 11.927
| |  P99| 852ms| 900ms | 48ms | 5.634
| TeamStore.GetActiveMemberCount |  Avg| 328ms| 305ms | -23ms | -7.013
| |  P99| 971ms| 1.915s | 944ms | 97.236
| TeamStore.GetAllPage |  Avg| 43ms| 50ms | 7ms | 16.425
| |  P99| 596ms| 743ms | 147ms | 24.646
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 49ms| 56ms | 7ms | 14.317
| |  P99| 691ms| 812ms | 121ms | 17.499
| TeamStore.GetMany |  Avg| 165ms| 0s | -165ms | -100.178
| |  P99| 975ms| 0s | -975ms | -100.000
| TeamStore.GetMember |  Avg| 17ms| 20ms | 3ms | 18.127
| |  P99| 259ms| 405ms | 146ms | 56.439
| TeamStore.GetTeamsByUserId |  Avg| 47ms| 55ms | 8ms | 17.145
| |  P99| 683ms| 800ms | 117ms | 17.124
| TeamStore.GetTeamsForUser |  Avg| 33ms| 37ms | 4ms | 12.119
| |  P99| 442ms| 483ms | 41ms | 9.266
| TeamStore.GetTotalMemberCount |  Avg| 300ms| 276ms | -24ms | -7.989
| |  P99| 2.238s| 1.915s | -323ms | -14.436
| TeamStore.SaveMember |  Avg| 131ms| 140ms | 9ms | 6.878
| |  P99| 811ms| 879ms | 68ms | 8.381
| ThreadStore.Get |  Avg| 93ms| 92ms | -1ms | -1.080
| |  P99| 919ms| 968ms | 49ms | 5.332
| ThreadStore.GetMembershipForUser |  Avg| 70ms| 77ms | 7ms | 9.995
| |  P99| 931ms| 942ms | 11ms | 1.181
| ThreadStore.GetTeamsUnreadForUser |  Avg| 76ms| 77ms | 1ms | 1.319
| |  P99| 1.29s| 993ms | -297ms | -23.016
| ThreadStore.GetThreadFollowers |  Avg| 69ms| 75ms | 6ms | 8.663
| |  P99| 952ms| 923ms | -29ms | -3.046
| ThreadStore.GetThreadForUser |  Avg| 93ms| 104ms | 11ms | 11.889
| |  P99| 1.405s| 1.615s | 210ms | 14.950
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 78ms| 81ms | 3ms | 3.847
| |  P99| 980ms| 970ms | -10ms | -1.021
| ThreadStore.GetThreadsForUser |  Avg| 78ms| 84ms | 6ms | 7.664
| |  P99| 942ms| 959ms | 17ms | 1.804
| ThreadStore.GetTotalThreads |  Avg| 45ms| 52ms | 7ms | 15.577
| |  P99| 653ms| 765ms | 112ms | 17.160
| ThreadStore.GetTotalUnreadMentions |  Avg| 49ms| 57ms | 8ms | 16.174
| |  P99| 726ms| 834ms | 108ms | 14.866
| ThreadStore.GetTotalUnreadThreads |  Avg| 43ms| 51ms | 8ms | 18.393
| |  P99| 602ms| 759ms | 157ms | 26.095
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 45ms| 52ms | 7ms | 15.568
| |  P99| 621ms| 779ms | 158ms | 25.430
| ThreadStore.MaintainMembership |  Avg| 17ms| 19ms | 2ms | 11.567
| |  P99| 202ms| 217ms | 15ms | 7.418
| ThreadStore.MarkAllAsReadByChannels |  Avg| 8ms| 9ms | 1ms | 13.185
| |  P99| 93ms| 96ms | 3ms | 3.231
| ThreadStore.MarkAllAsReadByTeam |  Avg| 23ms| 8ms | -15ms | -64.983
| |  P99| 238ms| 25ms | -213ms | -89.495
| ThreadStore.MarkAsRead |  Avg| 9ms| 10ms | 1ms | 10.631
| |  P99| 87ms| 92ms | 5ms | 5.726
| ThreadStore.UpdateMembership |  Avg| 10ms| 11ms | 1ms | 9.971
| |  P99| 93ms| 99ms | 6ms | 6.432
| TokenStore.Cleanup |  Avg| 2ms| 23ms | 21ms | 1036.599
| |  P99| 5ms| 98ms | 93ms | 1878.416
| UserAccessTokenStore.GetByToken |  Avg| 43ms| 45ms | 2ms | 4.657
| |  P99| 1.42s| 464ms | -956ms | -67.319
| UserStore.AnalyticsActiveCount |  Avg| 400ms| 403ms | 3ms | 0.751
| |  P99| 2.35s| 987ms | -1.363s | -57.999
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 196ms | 195ms | 13670.348
| |  P99| 5ms| 985ms | 980ms | 19791.753
| UserStore.AutocompleteUsersInChannel |  Avg| 437ms| 433ms | -4ms | -0.914
| |  P99| 2.289s| 2.216s | -73ms | -3.189
| UserStore.Count |  Avg| 208ms| 238ms | 30ms | 14.429
| |  P99| 1.915s| 954ms | -961ms | -50.185
| UserStore.Get |  Avg| 41ms| 46ms | 5ms | 12.172
| |  P99| 624ms| 752ms | 128ms | 20.508
| UserStore.GetAllProfiles |  Avg| 35ms| 41ms | 6ms | 17.244
| |  P99| 490ms| 700ms | 210ms | 42.815
| UserStore.GetAllProfilesInChannel |  Avg| 758ms| 754ms | -4ms | -0.528
| |  P99| 2.653s| 2.463s | -190ms | -7.162
| UserStore.GetByUsername |  Avg| 69ms| 77ms | 8ms | 11.550
| |  P99| 905ms| 905ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 30ms| 33ms | 3ms | 9.950
| |  P99| 441ms| 466ms | 25ms | 5.667
| UserStore.GetMany |  Avg| 69ms| 52ms | -17ms | -24.561
| |  P99| 990ms| 486ms | -504ms | -50.907
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 45ms| 532ms | 487ms | 1073.312
| |  P99| 99ms| 995ms | 896ms | 904.766
| UserStore.GetProfileByIds |  Avg| 54ms| 59ms | 5ms | 9.318
| |  P99| 787ms| 843ms | 56ms | 7.116
| UserStore.GetProfilesByUsernames |  Avg| 44ms| 48ms | 4ms | 8.993
| |  P99| 544ms| 660ms | 116ms | 21.316
| UserStore.GetProfilesInChannel |  Avg| 55ms| 78ms | 23ms | 41.739
| |  P99| 795ms| 1.795s | 1s | 125.781
| UserStore.GetProfilesNotInChannel |  Avg| 68ms| 77ms | 9ms | 13.145
| |  P99| 825ms| 935ms | 110ms | 13.333
| UserStore.GetUnreadCount |  Avg| 57ms| 63ms | 6ms | 10.563
| |  P99| 833ms| 885ms | 52ms | 6.241
| UserStore.IsEmpty |  Avg| 18ms| 22ms | 4ms | 21.831
| |  P99| 320ms| 402ms | 82ms | 25.585
| UserStore.Save |  Avg| 84ms| 84ms | 0s | 0.000
| |  P99| 274ms| 337ms | 63ms | 22.951
| UserStore.Search |  Avg| 205ms| 209ms | 4ms | 1.947
| |  P99| 1.318s| 1.377s | 59ms | 4.476
| UserStore.Update |  Avg| 20ms| 23ms | 3ms | 14.770
| |  P99| 216ms| 225ms | 9ms | 4.172
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 9ms | 1ms | 12.473
| |  P99| 84ms| 87ms | 3ms | 3.586
| UserStore.UpdateLastLogin |  Avg| 7ms| 8ms | 1ms | 14.052
| |  P99| 70ms| 75ms | 5ms | 7.169
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 84ms | 7ms | 9.093
| UserTermsOfServiceStore.GetByUser |  Avg| 44ms| 48ms | 4ms | 9.055
| |  P99| 655ms| 717ms | 62ms | 9.467
| WebhookStore.GetOutgoingByTeam |  Avg| 75ms| 80ms | 5ms | 6.661
| |  P99| 940ms| 934ms | -6ms | -0.638
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.277s| 1.23s | -47ms | -3.681
| | P99| 10s| 8.913s | -1.087s | -10.870
| addTeamMember | Avg| 2.197s| 2.326s | 129ms | 5.872
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 325ms| 327ms | 2ms | 0.615
| | P99| 2.404s| 2.36s | -44ms | -1.830
| autocompleteUsers | Avg| 397ms| 393ms | -4ms | -1.007
| | P99| 2.329s| 2.267s | -62ms | -2.662
| channelMemberCountsByGroup | Avg| 13ms| 0s | -13ms | -99.058
| | P99| 180ms| 0s | -180ms | -100.273
| createCategoryForTeamForUser | Avg| 202ms| 75ms | -127ms | -62.937
| | P99| 968ms| 243ms | -725ms | -74.935
| createChannel | Avg| 1.318s| 1.265s | -53ms | -4.021
| | P99| 8.2s| 9s | 800ms | 9.756
| createChannelBookmark | Avg| 91ms| 75ms | -16ms | -17.492
| | P99| 835ms| 805ms | -30ms | -3.593
| createDirectChannel | Avg| 739ms| 793ms | 54ms | 7.309
| | P99| 6.817s| 4.721s | -2.096s | -30.747
| createEmoji | Avg| 5ms| 0s | -5ms | -96.227
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 1.504s| 1.57s | 66ms | 4.389
| | P99| 10s| 9.555s | -445ms | -4.450
| createPost | Avg| 1.229s| 1.275s | 46ms | 3.742
| | P99| 9.554s| 9.595s | 41ms | 0.429
| createSchedulePost | Avg| 66ms| 48ms | -18ms | -27.362
| | P99| 2.55s| 688ms | -1.862s | -73.025
| createUser | Avg| 284ms| 300ms | 16ms | 5.627
| | P99| 2.233s| 2.24s | 7ms | 0.313
| deleteChannelBookmark | Avg| 226ms| 178ms | -48ms | -21.274
| | P99| 975ms| 970ms | -5ms | -0.513
| deleteDraft | Avg| 89ms| 95ms | 6ms | 6.732
| | P99| 994ms| 982ms | -12ms | -1.207
| deletePost | Avg| 168ms| 337ms | 169ms | 100.543
| | P99| 1.81s| 2.401s | 591ms | 32.653
| followThreadByUser | Avg| 224ms| 199ms | -25ms | -11.142
| | P99| 2.311s| 2.19s | -121ms | -5.236
| getAllTeams | Avg| 46ms| 53ms | 7ms | 15.167
| | P99| 666ms| 783ms | 117ms | 17.561
| getAnalytics | Avg| 479ms| 794ms | 315ms | 65.813
| | P99| 2.426s| 2.456s | 30ms | 1.237
| getCategoriesForTeamForUser | Avg| 98ms| 123ms | 25ms | 25.449
| | P99| 1.564s| 1.958s | 394ms | 25.197
| getChannel | Avg| 133ms| 143ms | 10ms | 7.515
| | P99| 2.033s| 1.91s | -123ms | -6.052
| getChannelMember | Avg| 74ms| 79ms | 5ms | 6.784
| | P99| 1.134s| 1.309s | 175ms | 15.432
| getChannelMembers | Avg| 36ms| 43ms | 7ms | 19.355
| | P99| 243ms| 483ms | 240ms | 98.969
| getChannelMembersForTeamForUser | Avg| 69ms| 76ms | 7ms | 10.161
| | P99| 903ms| 928ms | 25ms | 2.767
| getChannelMembersForUser | Avg| 112ms| 534ms | 422ms | 378.325
| | P99| 485ms| 992ms | 507ms | 104.536
| getChannelStats | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 862ms| 886ms | 24ms | 2.785
| getChannelUnread | Avg| 52ms| 54ms | 2ms | 3.878
| | P99| 607ms| 720ms | 113ms | 18.625
| getChannelsForTeamForUser | Avg| 71ms| 79ms | 8ms | 11.191
| | P99| 908ms| 939ms | 31ms | 3.412
| getChannelsForUser | Avg| 55ms| 63ms | 8ms | 14.458
| | P99| 703ms| 805ms | 102ms | 14.505
| getClientConfig | Avg| 21ms| 23ms | 2ms | 9.356
| | P99| 246ms| 291ms | 45ms | 18.287
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 87ms| 93ms | 6ms | 6.876
| | P99| 980ms| 989ms | 9ms | 0.918
| getFilePreview | Avg| 95ms| 97ms | 2ms | 2.102
| | P99| 809ms| 836ms | 27ms | 3.339
| getFileThumbnail | Avg| 93ms| 95ms | 2ms | 2.158
| | P99| 860ms| 881ms | 21ms | 2.442
| getFilteredUsersStats | Avg| 133ms| 234ms | 101ms | 76.072
| | P99| 247ms| 249ms | 2ms | 0.810
| getGroups | Avg| 39ms| 859ms | 820ms | 2129.147
| | P99| 99ms| 995ms | 896ms | 904.980
| getGroupsAssociatedToChannelsByTeam | Avg| 37ms| 1.243s | 1.206s | 3278.362
| | P99| 50ms| 2.485s | 2.435s | 4893.706
| getJobsByType | Avg| 71ms| 100ms | 29ms | 40.654
| | P99| 472ms| 1.158s | 686ms | 145.186
| getPostThread | Avg| 410ms| 437ms | 27ms | 6.580
| | P99| 4.44s| 4.384s | -56ms | -1.261
| getPostsForChannel | Avg| 656ms| 770ms | 114ms | 17.374
| | P99| 9.599s| 10s | 401ms | 4.178
| getPostsForChannelAroundLastUnread | Avg| 184ms| 222ms | 38ms | 20.663
| | P99| 2.566s| 3.313s | 747ms | 29.113
| getPreferences | Avg| 63ms| 70ms | 7ms | 11.044
| | P99| 865ms| 898ms | 33ms | 3.816
| getPrevTrialLicense | Avg| 3ms| 1ms | -2ms | -57.399
| | P99| 10ms| 5ms | -5ms | -50.996
| getProductNotices | Avg| 40ms| 0s | -40ms | -99.172
| | P99| 50ms| 0s | -50ms | -100.487
| getProfileImage | Avg| 75ms| 71ms | -4ms | -5.310
| | P99| 461ms| 485ms | 24ms | 5.206
| getPublicChannelsForTeam | Avg| 88ms| 102ms | 14ms | 15.896
| | P99| 890ms| 1.178s | 288ms | 32.359
| getRolesByNames | Avg| 8ms| 1ms | -7ms | -91.586
| | P99| 96ms| 5ms | -91ms | -94.761
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 12ms| 14ms | 2ms | 17.155
| | P99| 199ms| 232ms | 33ms | 16.566
| getTeamMembersForUser | Avg| 37ms| 41ms | 4ms | 10.890
| | P99| 472ms| 510ms | 38ms | 8.059
| getTeamScheduledPosts | Avg| 65ms| 78ms | 13ms | 20.071
| | P99| 916ms| 984ms | 68ms | 7.426
| getTeamStats | Avg| 366ms| 348ms | -18ms | -4.920
| | P99| 2.238s| 2.208s | -30ms | -1.341
| getTeamsForUser | Avg| 47ms| 55ms | 8ms | 17.082
| | P99| 686ms| 802ms | 116ms | 16.922
| getTeamsUnreadForUser | Avg| 93ms| 102ms | 9ms | 9.659
| | P99| 1.689s| 1.715s | 26ms | 1.539
| getThreadsForUser | Avg| 80ms| 85ms | 5ms | 6.232
| | P99| 985ms| 983ms | -2ms | -0.203
| getUser | Avg| 90ms| 90ms | 0s | 0.000
| | P99| 1.686s| 1.306s | -380ms | -22.538
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 34ms| 41ms | 7ms | 20.591
| getUsers | Avg| 51ms| 55ms | 4ms | 7.867
| | P99| 896ms| 944ms | 48ms | 5.360
| getUsersByGroupChannelIds | Avg| 46ms| 0s | -46ms | -100.351
| | P99| 99ms| 0s | -99ms | -99.969
| getUsersByIds | Avg| 6ms| 7ms | 1ms | 15.673
| | P99| 156ms| 185ms | 29ms | 18.586
| getUsersByNames | Avg| 45ms| 49ms | 4ms | 8.825
| | P99| 566ms| 676ms | 110ms | 19.438
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 34ms| 37ms | 3ms | 8.763
| | P99| 499ms| 623ms | 124ms | 24.848
| login | Avg| 163ms| 175ms | 12ms | 7.369
| | P99| 1.845s| 1.932s | 87ms | 4.716
| logout | Avg| 120ms| 210ms | 90ms | 75.004
| | P99| 900ms| 1.99s | 1.09s | 121.111
| patchPost | Avg| 468ms| 454ms | -14ms | -2.992
| | P99| 4.482s| 3.642s | -840ms | -18.741
| removeUserCustomStatus | Avg| 279ms| 338ms | 59ms | 21.124
| | P99| 1.03s| 2.129s | 1.099s | 106.691
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 222ms| 242ms | 20ms | 9.019
| | P99| 2.411s| 2.388s | -23ms | -0.954
| searchAllChannels | Avg| 1.591s| 1.615s | 24ms | 1.509
| | P99| 4.96s| 4.899s | -61ms | -1.230
| searchGroupChannels | Avg| 73ms| 81ms | 8ms | 10.921
| | P99| 899ms| 918ms | 19ms | 2.113
| searchPostsInTeam | Avg| 259ms| 254ms | -5ms | -1.934
| | P99| 3.958s| 3.556s | -402ms | -10.158
| searchUsers | Avg| 207ms| 210ms | 3ms | 1.451
| | P99| 1.344s| 1.393s | 49ms | 3.646
| setPostReminder | Avg| 300ms| 487ms | 187ms | 62.254
| | P99| 3.475s| 6.6s | 3.125s | 89.924
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 248ms| 243ms | -5ms | -2.019
| | P99| 3.65s| 2.358s | -1.292s | -35.395
| updateCategoriesForTeamForUser | Avg| 457ms| 464ms | 7ms | 1.530
| | P99| 5.45s| 3.967s | -1.483s | -27.209
| updateChannelBookmark | Avg| 101ms| 137ms | 36ms | 35.575
| | P99| 940ms| 926ms | -14ms | -1.489
| updateChannelBookmarkSortOrder | Avg| 96ms| 104ms | 8ms | 8.334
| | P99| 473ms| 490ms | 17ms | 3.598
| updatePreferences | Avg| 33ms| 37ms | 4ms | 12.167
| | P99| 287ms| 349ms | 62ms | 21.620
| updateReadStateAllThreadsByUser | Avg| 23ms| 9ms | -14ms | -60.379
| | P99| 238ms| 25ms | -213ms | -89.495
| updateReadStateThreadByUser | Avg| 638ms| 681ms | 43ms | 6.738
| | P99| 6.55s| 6.438s | -112ms | -1.710
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 521ms| 532ms | 11ms | 2.112
| | P99| 2.172s| 2.244s | 72ms | 3.315
| upsertDraft | Avg| 41ms| 43ms | 2ms | 4.901
| | P99| 656ms| 742ms | 86ms | 13.103
| viewChannel | Avg| 224ms| 240ms | 16ms | 7.155
| | P99| 3.662s| 3.509s | -153ms | -4.178

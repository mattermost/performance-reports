### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 4ms | 1.256s | 1.252s | 29299.52
| ProductNoticesStore.GetViews | avg | 2ms | 91ms | 89ms | 3608.08
| ProductNoticesStore.ClearOldNotices | avg | 1ms | 6ms | 5ms | 533.51
| ChannelStore.GetChannelsByIds | avg | 54ms | 173ms | 119ms | 219.10
| StatusStore.SaveOrUpdate | avg | 17ms | 42ms | 25ms | 148.75
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 4ms | 9ms | 5ms | 128.78
| ChannelStore.GetMembers | avg | 32ms | 57ms | 25ms | 77.78
| PostStore.GetPostsByIds | avg | 66ms | 117ms | 51ms | 76.98
| JobStore.GetAllByTypePage | avg | 48ms | 83ms | 35ms | 73.18
| LinkMetadataStore.Save | avg | 5ms | 8ms | 3ms | 62.57
| JobStore.Save | avg | 5ms | 8ms | 3ms | 62.16
| JobStore.UpdateStatusOptimistically | avg | 11ms | 15ms | 4ms | 36.42
| PostStore.GetPostReminderMetadata | avg | 83ms | 112ms | 29ms | 34.79
| ChannelBookmarkStore.Delete | avg | 9ms | 12ms | 3ms | 31.91
| JobStore.GetCountByStatusAndType | avg | 86ms | 113ms | 27ms | 31.38
| PostAcknowledgementStore.GetForPost | avg | 59ms | 75ms | 16ms | 27.13
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 46ms | 57ms | 11ms | 24.15
| PreferenceStore.DeleteCategoryAndName | avg | 10ms | 12ms | 2ms | 19.85
| PostStore.GetPostReminders | avg | 17ms | 20ms | 3ms | 17.96
| FileInfoStore.SetContent | avg | 12ms | 14ms | 2ms | 17.17
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 144ms | 164ms | 20ms | 13.91
| PostStore.AnalyticsPostCount | avg | 1.308s | 1.482s | 174ms | 13.31
| EmojiStore.GetMultipleByName | avg | 119ms | 128ms | 9ms | 7.54
| JobStore.GetNewestJobByStatusesAndType | avg | 77ms | 82ms | 5ms | 6.45
| ChannelStore.GetChannelUnread | avg | 58ms | 60ms | 2ms | 3.47
| ChannelStore.GetPublicChannelsForTeam | avg | 109ms | 112ms | 3ms | 2.76
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 5ms | 4.875s | 4.87s | 98356.48
| ProductNoticesStore.GetViews | p99 | 5ms | 247ms | 242ms | 4887.62
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 24ms | 19ms | 383.84
| SessionStore.GetSessionsExpired | p99 | 490ms | 2.17s | 1.68s | 342.86
| StatusStore.SaveOrUpdate | p99 | 295ms | 951ms | 656ms | 222.72
| JobStore.GetCountByStatusAndType | p99 | 765ms | 1.87s | 1.105s | 144.44
| UserStore.Update | p99 | 100ms | 209ms | 109ms | 109.45
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 44ms | 92ms | 48ms | 108.78
| LinkMetadataStore.Save | p99 | 49ms | 100ms | 51ms | 104.08
| ChannelStore.GetMembers | p99 | 238ms | 485ms | 247ms | 103.73
| ChannelStore.GetPublicChannelsForTeam | p99 | 947ms | 1.913s | 966ms | 101.97
| PostStore.GetPostReminderMetadata | p99 | 930ms | 1.875s | 945ms | 101.61
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 249ms | 492ms | 243ms | 97.79
| JobStore.Save | p99 | 44ms | 86ms | 42ms | 96.33
| JobStore.UpdateStatusOptimistically | p99 | 98ms | 180ms | 82ms | 83.89
| JobStore.GetAllByTypePage | p99 | 470ms | 810ms | 340ms | 72.33
| UserStore.Count | p99 | 493ms | 800ms | 307ms | 62.22
| PostAcknowledgementStore.GetForPost | p99 | 729ms | 981ms | 252ms | 34.59
| PostPersistentNotificationStore.Get | p99 | 59ms | 79ms | 20ms | 33.90
| FileInfoStore.SetContent | p99 | 153ms | 201ms | 48ms | 31.48
| PostStore.GetPostReminders | p99 | 179ms | 231ms | 52ms | 28.97
| PluginStore.Delete | p99 | 33ms | 38ms | 5ms | 15.03
| JobStore.GetNewestJobByStatusesAndType | p99 | 849ms | 929ms | 80ms | 9.42
| ChannelStore.GetChannelUnread | p99 | 719ms | 785ms | 66ms | 9.18
| UserStore.UpdateLastLogin | p99 | 59ms | 64ms | 5ms | 8.47
| StatusStore.UpdateExpiredDNDStatuses | p99 | 215ms | 232ms | 17ms | 7.92
| ChannelStore.UpdateSidebarCategories | p99 | 2.24s | 2.414s | 174ms | 7.77
| ScheduledPostStore.CreateScheduledPost | p99 | 92ms | 97ms | 5ms | 5.45
| PostPriorityStore.GetForPost | p99 | 936ms | 986ms | 50ms | 5.34
| EmojiStore.GetMultipleByName | p99 | 810ms | 850ms | 40ms | 4.94
| ChannelStore.UpdateLastViewedAt | p99 | 152ms | 159ms | 7ms | 4.62
| PostStore.GetPostIdAfterTime | p99 | 67ms | 70ms | 3ms | 4.49
| UserStore.UpdateUpdateAt | p99 | 71ms | 74ms | 3ms | 4.21
| ChannelStore.GetMember | p99 | 169ms | 176ms | 7ms | 4.14
| ThreadStore.MaintainMembership | p99 | 194ms | 200ms | 6ms | 3.09
| ProductNoticesStore.View | p99 | 363ms | 374ms | 11ms | 3.03
| ChannelStore.GetChannelsByIds | p99 | 242ms | 249ms | 7ms | 2.89
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 72ms | 74ms | 2ms | 2.77
| AuditStore.Save | p99 | 74ms | 76ms | 2ms | 2.70
| ChannelStore.CreateSidebarCategory | p99 | 468ms | 480ms | 12ms | 2.57
| PostStore.Update | p99 | 206ms | 211ms | 5ms | 2.43
| PluginStore.SetWithOptions | p99 | 85ms | 87ms | 2ms | 2.36
| PreferenceStore.Save | p99 | 219ms | 224ms | 5ms | 2.28
| ThreadStore.MarkAllAsReadByChannels | p99 | 88ms | 90ms | 2ms | 2.26
| ChannelStore.GetMembersForUserWithPagination | p99 | 477ms | 485ms | 8ms | 1.68
| PostStore.Save | p99 | 230ms | 233ms | 3ms | 1.31
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 232ms | 235ms | 3ms | 1.29
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | avg | 3ms | 0s | -3ms | -101.86
| RetentionPolicyStore.GetAll | avg | 107ms | 0s | -107ms | -100.40
| BotStore.GetAll | avg | 161ms | 0s | -161ms | -100.15
| RetentionPolicyStore.GetCount | avg | 77ms | 0s | -77ms | -99.93
| EmojiStore.Search | avg | 2ms | 0s | -2ms | -97.82
| LicenseStore.GetAll | avg | 126ms | 8ms | -118ms | -93.32
| SchemeStore.GetAllPage | avg | 41ms | 3ms | -38ms | -92.50
| TeamStore.AnalyticsTeamCount | avg | 523ms | 69ms | -454ms | -86.79
| CommandWebhookStore.Cleanup | avg | 32ms | 9ms | -23ms | -71.54
| ChannelBookmarkStore.UpdateSortOrder | avg | 413ms | 145ms | -268ms | -64.95
| RoleStore.ChannelHigherScopedPermissions | avg | 140ms | 52ms | -88ms | -62.93
| PostStore.SetPostReminder | avg | 22ms | 9ms | -13ms | -59.33
| UserStore.AnalyticsGetInactiveUsersCount | avg | 61ms | 25ms | -36ms | -58.89
| TokenStore.Cleanup | avg | 30ms | 13ms | -17ms | -56.80
| ChannelStore.GetTeamChannels | avg | 198ms | 105ms | -93ms | -46.89
| RoleStore.GetByNames | avg | 140ms | 79ms | -61ms | -43.57
| ChannelStore.AnalyticsCountAll | avg | 532ms | 313ms | -219ms | -41.19
| UserAccessTokenStore.GetByToken | avg | 79ms | 48ms | -31ms | -39.43
| ChannelBookmarkStore.Save | avg | 70ms | 43ms | -27ms | -38.32
| UserStore.GetMany | avg | 81ms | 51ms | -30ms | -37.07
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 150ms | 100ms | -50ms | -33.24
| ChannelStore.GetSidebarCategory | avg | 136ms | 91ms | -45ms | -33.18
| PluginStore.Get | avg | 31ms | 21ms | -10ms | -32.31
| ChannelBookmarkStore.Get | avg | 90ms | 61ms | -29ms | -32.14
| PluginStore.List | avg | 84ms | 58ms | -26ms | -30.77
| ReactionStore.GetForPost | avg | 102ms | 71ms | -31ms | -30.50
| UserStore.GetProfilesInChannel | avg | 87ms | 63ms | -24ms | -27.60
| ChannelStore.Save | avg | 124ms | 92ms | -32ms | -25.73
| BotStore.Get | avg | 72ms | 55ms | -17ms | -23.69
| ScheduledPostStore.GetPendingScheduledPosts | avg | 81ms | 62ms | -19ms | -23.46
| UserStore.AnalyticsActiveCount | avg | 684ms | 525ms | -159ms | -23.23
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 72ms | 56ms | -16ms | -22.18
| ScheduledPostStore.CreateScheduledPost | avg | 10ms | 8ms | -2ms | -20.47
| JobStore.GetAllByStatus | avg | 90ms | 72ms | -18ms | -19.89
| ClusterDiscoveryStore.SetLastPingAt | avg | 10ms | 8ms | -2ms | -19.25
| ChannelStore.GetPinnedPostCount | avg | 92ms | 75ms | -17ms | -18.53
| UserStore.GetUnreadCount | avg | 71ms | 58ms | -13ms | -18.36
| PostPriorityStore.GetForPosts | avg | 127ms | 104ms | -23ms | -18.14
| PostAcknowledgementStore.GetForPosts | avg | 122ms | 100ms | -22ms | -17.97
| ThreadStore.GetThreadUnreadReplyCount | avg | 95ms | 78ms | -17ms | -17.88
| PostPersistentNotificationStore.GetSingle | avg | 90ms | 74ms | -16ms | -17.81
| StatusStore.UpdateExpiredDNDStatuses | avg | 23ms | 19ms | -4ms | -17.22
| ThreadStore.GetThreadForUser | avg | 117ms | 97ms | -20ms | -17.15
| ChannelStore.SearchGroupChannels | avg | 94ms | 78ms | -16ms | -17.09
| EmojiStore.GetByName | avg | 88ms | 73ms | -15ms | -17.03
| TeamStore.Get | avg | 77ms | 64ms | -13ms | -16.92
| FileInfoStore.GetByIds | avg | 101ms | 84ms | -17ms | -16.91
| PostStore.Get | avg | 161ms | 134ms | -27ms | -16.77
| FileInfoStore.GetForPost | avg | 109ms | 91ms | -18ms | -16.49
| PostStore.GetSingle | avg | 79ms | 66ms | -13ms | -16.41
| WebhookStore.GetOutgoingByTeam | avg | 92ms | 77ms | -15ms | -16.39
| ChannelStore.GetMemberForPost | avg | 106ms | 89ms | -17ms | -16.04
| LinkMetadataStore.Get | avg | 81ms | 68ms | -13ms | -16.04
| TeamStore.GetTotalMemberCount | avg | 282ms | 237ms | -45ms | -15.96
| ChannelStore.GetChannels | avg | 89ms | 75ms | -14ms | -15.66
| ThreadStore.GetThreadsForUser | avg | 97ms | 82ms | -15ms | -15.44
| GroupStore.GetGroups | avg | 86ms | 73ms | -13ms | -15.14
| ChannelStore.GetMembersForUser | avg | 86ms | 73ms | -13ms | -15.13
| ThreadStore.GetThreadFollowers | avg | 86ms | 73ms | -13ms | -15.04
| PreferenceStore.Get | avg | 74ms | 63ms | -11ms | -14.92
| StatusStore.Get | avg | 67ms | 57ms | -10ms | -14.91
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 67ms | 57ms | -10ms | -14.91
| DraftStore.Get | avg | 109ms | 93ms | -16ms | -14.72
| TeamStore.GetMany | avg | 118ms | 101ms | -17ms | -14.45
| ThreadStore.GetTotalThreads | avg | 56ms | 48ms | -8ms | -14.41
| SessionStore.GetSessionsExpired | avg | 141ms | 121ms | -20ms | -14.17
| ThreadStore.GetTotalUnreadMentions | avg | 64ms | 55ms | -9ms | -14.10
| ThreadStore.GetMembershipForUser | avg | 85ms | 73ms | -12ms | -14.06
| PostStore.GetEtag | avg | 80ms | 69ms | -11ms | -13.72
| ThreadStore.GetTeamsUnreadForUser | avg | 96ms | 83ms | -13ms | -13.60
| PostStore.GetPostsByThread | avg | 89ms | 77ms | -12ms | -13.56
| UserStore.GetProfilesNotInChannel | avg | 96ms | 83ms | -13ms | -13.53
| ThreadStore.Get | avg | 96ms | 83ms | -13ms | -13.51
| PostStore.GetPostsBefore | avg | 75ms | 65ms | -10ms | -13.35
| StatusStore.GetByIds | avg | 114ms | 99ms | -15ms | -13.17
| ChannelStore.CreateSidebarCategory | avg | 55ms | 48ms | -7ms | -12.84
| ChannelStore.GetGuestCount | avg | 78ms | 68ms | -10ms | -12.84
| DraftStore.GetDraftsForUser | avg | 94ms | 82ms | -12ms | -12.80
| PostStore.GetPostsSince | avg | 110ms | 96ms | -14ms | -12.74
| ChannelStore.Get | avg | 137ms | 120ms | -17ms | -12.39
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 57ms | 50ms | -7ms | -12.25
| PostStore.Update | avg | 25ms | 22ms | -3ms | -12.24
| TeamStore.GetActiveMemberCount | avg | 303ms | 266ms | -37ms | -12.21
| ChannelStore.IsReadOnlyChannel | avg | 41ms | 36ms | -5ms | -12.21
| ChannelStore.GetAllChannelMembersForUser | avg | 49ms | 43ms | -6ms | -12.15
| ChannelStore.GetMemberLastViewedAt | avg | 42ms | 37ms | -5ms | -12.04
| ChannelStore.AutocompleteInTeamForSearch | avg | 367ms | 323ms | -44ms | -11.99
| UserStore.Get | avg | 51ms | 45ms | -6ms | -11.72
| PostStore.SearchPostsForUser | avg | 128ms | 113ms | -15ms | -11.69
| ChannelStore.CreateDirectChannel | avg | 253ms | 224ms | -29ms | -11.45
| UserStore.GetProfileByIds | avg | 63ms | 56ms | -7ms | -11.11
| ChannelStore.SaveMember | avg | 226ms | 201ms | -25ms | -11.07
| UserTermsOfServiceStore.GetByUser | avg | 55ms | 49ms | -6ms | -10.99
| TeamStore.GetMember | avg | 19ms | 17ms | -2ms | -10.73
| UserStore.GetByUsername | avg | 87ms | 78ms | -9ms | -10.30
| ChannelStore.CreateInitialSidebarCategories | avg | 68ms | 61ms | -7ms | -10.30
| PostStore.GetPosts | avg | 39ms | 35ms | -4ms | -10.24
| FileInfoStore.Get | avg | 49ms | 44ms | -5ms | -10.21
| PostStore.AnalyticsPostCountByTeam | avg | 1.371s | 1.231s | -140ms | -10.21
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 51ms | 46ms | -5ms | -9.84
| UserStore.GetProfilesByUsernames | avg | 52ms | 47ms | -5ms | -9.60
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 94ms | 85ms | -9ms | -9.54
| SessionStore.Get | avg | 55ms | 50ms | -5ms | -9.02
| SharedChannelStore.HasChannel | avg | 45ms | 41ms | -4ms | -8.89
| PostStore.Delete | avg | 103ms | 94ms | -9ms | -8.74
| UserStore.GetAllProfiles | avg | 46ms | 42ms | -4ms | -8.71
| GroupStore.GetByName | avg | 35ms | 32ms | -3ms | -8.66
| UserStore.IsEmpty | avg | 24ms | 22ms | -2ms | -8.30
| ChannelStore.GetMemberCount | avg | 270ms | 248ms | -22ms | -8.15
| UserStore.GetForLogin | avg | 39ms | 36ms | -3ms | -7.70
| TeamStore.GetAllPage | avg | 53ms | 49ms | -4ms | -7.49
| ThreadStore.GetTotalUnreadThreads | avg | 55ms | 51ms | -4ms | -7.23
| PreferenceStore.GetAll | avg | 72ms | 67ms | -5ms | -6.91
| TeamStore.GetChannelUnreadsForAllTeams | avg | 59ms | 55ms | -4ms | -6.72
| UserStore.AutocompleteUsersInChannel | avg | 468ms | 438ms | -30ms | -6.41
| UserStore.Search | avg | 222ms | 208ms | -14ms | -6.30
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 34ms | 32ms | -2ms | -5.90
| ChannelStore.GetByName | avg | 53ms | 50ms | -3ms | -5.68
| ChannelStore.Autocomplete | avg | 1.626s | 1.539s | -87ms | -5.35
| TeamStore.GetTeamsByUserId | avg | 56ms | 53ms | -3ms | -5.33
| TeamStore.SaveMember | avg | 135ms | 128ms | -7ms | -5.20
| SessionStore.GetLRUSessions | avg | 39ms | 37ms | -2ms | -5.16
| SessionStore.Save | avg | 41ms | 39ms | -2ms | -4.93
| UserStore.GetAllProfilesInChannel | avg | 787ms | 749ms | -38ms | -4.83
| TeamStore.GetTeamsForUser | avg | 42ms | 40ms | -2ms | -4.81
| UserStore.Count | avg | 215ms | 206ms | -9ms | -4.19
| ChannelStore.GetFileCount | avg | 49ms | 47ms | -2ms | -4.08
| PostStore.GetPostsAfter | avg | 75ms | 72ms | -3ms | -4.01
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 122ms | 118ms | -4ms | -3.28
| ChannelStore.GetChannelsByUser | avg | 67ms | 65ms | -2ms | -3.00
| PostPriorityStore.GetForPost | avg | 76ms | 74ms | -2ms | -2.63
| UserStore.Save | avg | 77ms | 75ms | -2ms | -2.59
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -100.98
| RetentionPolicyStore.GetCount | p99 | 100ms | 0s | -100ms | -100.50
| RetentionPolicyStore.GetAll | p99 | 249ms | 0s | -249ms | -100.20
| BotStore.GetAll | p99 | 970ms | 0s | -970ms | -100.00
| LicenseStore.GetAll | p99 | 487ms | 25ms | -462ms | -94.77
| SchemeStore.GetAllPage | p99 | 50ms | 5ms | -45ms | -90.45
| CommandWebhookStore.Cleanup | p99 | 241ms | 48ms | -193ms | -80.08
| ChannelBookmarkStore.Save | p99 | 1.75s | 375ms | -1.375s | -78.57
| TeamStore.AnalyticsTeamCount | p99 | 990ms | 245ms | -745ms | -75.25
| RoleStore.ChannelHigherScopedPermissions | p99 | 1.941s | 492ms | -1.449s | -74.66
| ChannelStore.GetSidebarCategory | p99 | 3.283s | 963ms | -2.32s | -70.66
| UserStore.GetMany | p99 | 1.585s | 484ms | -1.101s | -69.46
| ChannelStore.GetTeamChannels | p99 | 2.11s | 770ms | -1.34s | -63.51
| TokenStore.Cleanup | p99 | 241ms | 96ms | -145ms | -60.17
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 247ms | 99ms | -148ms | -59.92
| UserAccessTokenStore.GetByToken | p99 | 1.12s | 450ms | -670ms | -59.82
| UserStore.AnalyticsActiveCount | p99 | 2.44s | 993ms | -1.447s | -59.30
| BotStore.Get | p99 | 1.78s | 745ms | -1.035s | -58.15
| ChannelStore.Save | p99 | 2.058s | 875ms | -1.183s | -57.50
| TeamStore.GetTotalMemberCount | p99 | 2.155s | 925ms | -1.23s | -57.08
| PostPersistentNotificationStore.DeleteExpired | p99 | 62ms | 29ms | -33ms | -53.22
| SessionStore.Remove | p99 | 65ms | 31ms | -34ms | -51.91
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 10ms | 5ms | -5ms | -51.02
| ClusterDiscoveryStore.SetLastPingAt | p99 | 171ms | 85ms | -86ms | -50.19
| ChannelStore.AnalyticsCountAll | p99 | 990ms | 498ms | -492ms | -49.70
| TeamStore.GetMany | p99 | 487ms | 247ms | -240ms | -49.23
| ReactionStore.GetForPost | p99 | 1.612s | 891ms | -721ms | -44.73
| ThreadStore.GetThreadUnreadReplyCount | p99 | 1.392s | 946ms | -446ms | -32.05
| PostStore.SearchPostsForUser | p99 | 1.432s | 976ms | -456ms | -31.84
| PostStore.SetPostReminder | p99 | 226ms | 156ms | -70ms | -31.02
| DraftStore.Get | p99 | 1.422s | 996ms | -426ms | -29.96
| ChannelStore.GetMemberForPost | p99 | 1.392s | 989ms | -403ms | -28.95
| FileInfoStore.GetForPost | p99 | 1.456s | 1.042s | -414ms | -28.43
| PostStore.GetPostsAfter | p99 | 1.229s | 921ms | -308ms | -25.06
| ChannelStore.GetMemberCount | p99 | 1.781s | 1.351s | -430ms | -24.14
| ChannelStore.GetAllChannelMembersForUser | p99 | 717ms | 544ms | -173ms | -24.13
| ChannelStore.IsReadOnlyChannel | p99 | 657ms | 500ms | -157ms | -23.90
| PluginStore.List | p99 | 1.09s | 830ms | -260ms | -23.85
| UserStore.Search | p99 | 1.576s | 1.205s | -371ms | -23.54
| UserStore.GetProfilesInChannel | p99 | 925ms | 710ms | -215ms | -23.24
| ChannelStore.Get | p99 | 1.625s | 1.248s | -377ms | -23.20
| FileInfoStore.Get | p99 | 661ms | 511ms | -150ms | -22.70
| ThreadStore.GetThreadsForUser | p99 | 1.22s | 948ms | -272ms | -22.29
| SharedChannelStore.HasChannel | p99 | 657ms | 511ms | -146ms | -22.21
| UserStore.GetAllProfiles | p99 | 766ms | 599ms | -167ms | -21.81
| ThreadStore.GetTotalThreads | p99 | 795ms | 628ms | -167ms | -21.02
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 806ms | 644ms | -162ms | -20.11
| ThreadStore.GetTeamsUnreadForUser | p99 | 1.69s | 1.351s | -339ms | -20.06
| ChannelStore.GetPinnedPostCount | p99 | 1.199s | 959ms | -240ms | -20.02
| UserStore.GetProfilesByUsernames | p99 | 698ms | 569ms | -129ms | -18.47
| UserStore.GetByUsername | p99 | 1.082s | 887ms | -195ms | -18.01
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 967ms | 794ms | -173ms | -17.89
| ChannelStore.GetMemberLastViewedAt | p99 | 595ms | 490ms | -105ms | -17.66
| ThreadStore.GetThreadForUser | p99 | 1.777s | 1.466s | -311ms | -17.50
| StatusStore.GetByIds | p99 | 1.454s | 1.208s | -246ms | -16.92
| UserTermsOfServiceStore.GetByUser | p99 | 802ms | 669ms | -133ms | -16.58
| SessionStore.Get | p99 | 760ms | 636ms | -124ms | -16.32
| TeamStore.GetAllPage | p99 | 775ms | 651ms | -124ms | -16.00
| UserStore.IsEmpty | p99 | 404ms | 343ms | -61ms | -15.12
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 883ms | 750ms | -133ms | -15.07
| ChannelBookmarkStore.Get | p99 | 888ms | 755ms | -133ms | -14.99
| ThreadStore.GetTotalUnreadMentions | p99 | 877ms | 746ms | -131ms | -14.93
| PostAcknowledgementStore.GetForPosts | p99 | 2.074s | 1.768s | -306ms | -14.75
| StatusStore.Get | p99 | 912ms | 778ms | -134ms | -14.69
| ChannelStore.CreateInitialSidebarCategories | p99 | 803ms | 690ms | -113ms | -14.08
| EmojiStore.GetByName | p99 | 1.065s | 917ms | -148ms | -13.90
| PostStore.Get | p99 | 2.102s | 1.812s | -290ms | -13.79
| JobStore.UpdateStatus | p99 | 44ms | 38ms | -6ms | -13.75
| UserStore.Get | p99 | 782ms | 677ms | -105ms | -13.43
| PostPriorityStore.GetForPosts | p99 | 2.104s | 1.822s | -282ms | -13.40
| GroupStore.GetGroups | p99 | 1.064s | 926ms | -138ms | -12.97
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 799ms | 696ms | -103ms | -12.90
| UserStore.GetUnreadCount | p99 | 928ms | 812ms | -116ms | -12.50
| TeamStore.GetMember | p99 | 364ms | 319ms | -45ms | -12.36
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 1.856s | 1.63s | -226ms | -12.18
| PostStore.GetPostsByThread | p99 | 1.1s | 967ms | -133ms | -12.09
| PostPersistentNotificationStore.GetSingle | p99 | 1.057s | 931ms | -126ms | -11.92
| UserStore.GetProfileByIds | p99 | 878ms | 774ms | -104ms | -11.85
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 904ms | 800ms | -104ms | -11.51
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 967ms | 856ms | -111ms | -11.48
| ChannelStore.GetGuestCount | p99 | 960ms | 850ms | -110ms | -11.46
| RoleStore.GetByNames | p99 | 1.185s | 1.05s | -135ms | -11.39
| TeamStore.GetTeamsByUserId | p99 | 781ms | 693ms | -88ms | -11.27
| ThreadStore.GetThreadFollowers | p99 | 1.067s | 948ms | -119ms | -11.15
| PostStore.GetEtag | p99 | 955ms | 849ms | -106ms | -11.10
| PostStore.GetPostsBefore | p99 | 922ms | 823ms | -99ms | -10.74
| JobStore.GetAllByStatus | p99 | 982ms | 879ms | -103ms | -10.49
| PreferenceStore.Get | p99 | 937ms | 841ms | -96ms | -10.25
| PostStore.GetPostsSince | p99 | 1.043s | 937ms | -106ms | -10.17
| PostStore.GetSingle | p99 | 983ms | 885ms | -98ms | -9.97
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 823ms | 741ms | -82ms | -9.97
| ChannelStore.GetMembersForUser | p99 | 991ms | 894ms | -97ms | -9.79
| TeamStore.Get | p99 | 972ms | 877ms | -95ms | -9.77
| ChannelStore.GetChannels | p99 | 1s | 903ms | -97ms | -9.70
| ThreadStore.GetTotalUnreadThreads | p99 | 778ms | 705ms | -73ms | -9.38
| LinkMetadataStore.Get | p99 | 985ms | 893ms | -92ms | -9.34
| UserStore.GetForLogin | p99 | 517ms | 469ms | -48ms | -9.29
| WebhookStore.GetOutgoingByTeam | p99 | 1.013s | 919ms | -94ms | -9.28
| GroupStore.GetByName | p99 | 471ms | 435ms | -36ms | -7.64
| DraftStore.GetDraftsForUser | p99 | 987ms | 912ms | -75ms | -7.60
| ChannelStore.GetFileCount | p99 | 547ms | 508ms | -39ms | -7.13
| ThreadStore.GetMembershipForUser | p99 | 989ms | 920ms | -69ms | -6.98
| TeamStore.SaveMember | p99 | 862ms | 802ms | -60ms | -6.96
| PreferenceStore.GetAll | p99 | 920ms | 857ms | -63ms | -6.84
| FileInfoStore.AttachToPost | p99 | 92ms | 86ms | -6ms | -6.51
| PostStore.GetPosts | p99 | 495ms | 463ms | -32ms | -6.47
| ChannelStore.SearchGroupChannels | p99 | 980ms | 917ms | -63ms | -6.43
| ChannelStore.GetByName | p99 | 751ms | 703ms | -48ms | -6.39
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 525ms | 492ms | -33ms | -6.29
| ChannelStore.GetChannelsByUser | p99 | 843ms | 790ms | -53ms | -6.29
| FileInfoStore.GetByIds | p99 | 996ms | 935ms | -61ms | -6.13
| ChannelStore.SaveMember | p99 | 2.493s | 2.357s | -136ms | -5.45
| DraftStore.Delete | p99 | 93ms | 88ms | -5ms | -5.38
| SessionStore.GetLRUSessions | p99 | 509ms | 482ms | -27ms | -5.30
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 480ms | 456ms | -24ms | -5.00
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.48s | 2.371s | -109ms | -4.39
| UserStore.AutocompleteUsersInChannel | p99 | 2.352s | 2.253s | -99ms | -4.21
| ChannelBookmarkStore.UpdateSortOrder | p99 | 2.41s | 2.32s | -90ms | -3.73
| SessionStore.Save | p99 | 496ms | 478ms | -18ms | -3.63
| FileInfoStore.Save | p99 | 100ms | 97ms | -3ms | -3.00
| TeamStore.GetTeamsForUser | p99 | 500ms | 485ms | -15ms | -3.00
| TeamStore.GetActiveMemberCount | p99 | 971ms | 944ms | -27ms | -2.78
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 249ms | 246ms | -3ms | -1.21
| PreferenceStore.DeleteCategoryAndName | p99 | 178ms | 176ms | -2ms | -1.12
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 122ms | 328ms | 206ms | 169.39
| getChannelMembers | avg | 40ms | 76ms | 36ms | 90.87
| getJobsByType | avg | 48ms | 85ms | 37ms | 77.17
| deleteChannelBookmark | avg | 96ms | 132ms | 36ms | 37.55
| logout | avg | 315ms | 346ms | 31ms | 9.83
| removeUserCustomStatus | avg | 374ms | 397ms | 23ms | 6.16
| addChannelMember | avg | 1.246s | 1.307s | 61ms | 4.89
| uploadFileStream | avg | 482ms | 497ms | 15ms | 3.11
| getPublicChannelsForTeam | avg | 110ms | 113ms | 3ms | 2.73
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 484ms | 2.38s | 1.896s | 391.94
| getPublicChannelsForTeam | p99 | 947ms | 1.913s | 966ms | 101.97
| logout | p99 | 4.138s | 8.1s | 3.962s | 95.76
| getJobsByType | p99 | 470ms | 810ms | 340ms | 72.33
| getUserStatusesByIds | p99 | 29ms | 32ms | 3ms | 10.22
| getChannelMembers | p99 | 460ms | 485ms | 25ms | 5.43
| patchPost | p99 | 4.766s | 4.994s | 228ms | 4.78
| createChannel | p99 | 9.567s | 10s | 433ms | 4.53
| updateChannelBookmark | p99 | 925ms | 953ms | 28ms | 3.03
| getClientConfig | p99 | 248ms | 252ms | 4ms | 1.61
| updatePreferences | p99 | 248ms | 252ms | 4ms | 1.61
| getChannelUnread | p99 | 826ms | 839ms | 13ms | 1.57
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | avg | 2ms | 0s | -2ms | -95.71
| getPrevTrialLicense | avg | 158ms | 8ms | -150ms | -94.93
| updateChannelBookmarkSortOrder | avg | 513ms | 137ms | -376ms | -73.22
| getRolesByNames | avg | 84ms | 23ms | -61ms | -72.81
| getChannelMembersForUser | avg | 178ms | 52ms | -126ms | -70.73
| getFilteredUsersStats | avg | 308ms | 102ms | -206ms | -66.90
| getGroups | avg | 148ms | 73ms | -75ms | -50.76
| createChannel | avg | 1.939s | 1.112s | -827ms | -42.65
| createSchedulePost | avg | 59ms | 39ms | -20ms | -33.85
| getTeamMember | avg | 15ms | 11ms | -4ms | -27.38
| createChannelBookmark | avg | 86ms | 69ms | -17ms | -19.74
| getChannelStats | avg | 44ms | 36ms | -8ms | -17.98
| getChannelMember | avg | 84ms | 69ms | -15ms | -17.77
| getUsers | avg | 63ms | 52ms | -11ms | -17.43
| searchPostsInTeam | avg | 295ms | 244ms | -51ms | -17.30
| getUser | avg | 105ms | 87ms | -18ms | -17.13
| searchGroupChannels | avg | 94ms | 78ms | -16ms | -17.06
| getPostThread | avg | 514ms | 427ms | -87ms | -16.92
| saveReaction | avg | 280ms | 233ms | -47ms | -16.81
| getTeamStats | avg | 343ms | 286ms | -57ms | -16.60
| getPostsForChannel | avg | 875ms | 733ms | -142ms | -16.23
| getThreadsForUser | avg | 100ms | 84ms | -16ms | -16.00
| getChannelsForTeamForUser | avg | 90ms | 76ms | -14ms | -15.62
| upsertDraft | avg | 45ms | 38ms | -7ms | -15.58
| viewChannel | avg | 269ms | 228ms | -41ms | -15.25
| updateCategoriesForTeamForUser | avg | 586ms | 497ms | -89ms | -15.19
| updateReadStateThreadByUser | avg | 765ms | 650ms | -115ms | -15.04
| deleteDraft | avg | 109ms | 93ms | -16ms | -14.66
| deletePost | avg | 288ms | 246ms | -42ms | -14.56
| getChannel | avg | 159ms | 136ms | -23ms | -14.45
| unfollowThreadByUser | avg | 234ms | 201ms | -33ms | -14.09
| getChannelMembersForTeamForUser | avg | 86ms | 74ms | -12ms | -13.92
| getDrafts | avg | 102ms | 89ms | -13ms | -12.76
| createGroupChannel | avg | 1.656s | 1.45s | -206ms | -12.44
| autocompleteChannelsForTeamForSearch | avg | 367ms | 323ms | -44ms | -11.99
| createPost | avg | 1.356s | 1.202s | -154ms | -11.35
| getTeamsUnreadForUser | avg | 115ms | 104ms | -11ms | -9.60
| patchPost | avg | 604ms | 547ms | -57ms | -9.44
| getUsersByNames | avg | 53ms | 48ms | -5ms | -9.43
| getAllTeams | avg | 57ms | 52ms | -5ms | -8.75
| updateChannelBookmark | avg | 131ms | 120ms | -11ms | -8.40
| getPreferences | avg | 74ms | 68ms | -6ms | -8.09
| getPostsForChannelAroundLastUnread | avg | 223ms | 205ms | -18ms | -8.06
| searchUsers | avg | 225ms | 208ms | -17ms | -7.56
| addTeamMember | avg | 2.327s | 2.152s | -175ms | -7.52
| createDirectChannel | avg | 777ms | 724ms | -53ms | -6.82
| setPostReminder | avg | 450ms | 422ms | -28ms | -6.22
| getFileThumbnail | avg | 99ms | 93ms | -6ms | -6.04
| autocompleteUsers | avg | 422ms | 398ms | -24ms | -5.69
| getProfileImage | avg | 72ms | 68ms | -4ms | -5.56
| searchAllChannels | avg | 1.63s | 1.542s | -88ms | -5.40
| getTeamsForUser | avg | 56ms | 53ms | -3ms | -5.31
| listChannelBookmarksForChannel | avg | 40ms | 38ms | -2ms | -4.95
| getTeamMembersForUser | avg | 46ms | 44ms | -2ms | -4.39
| getFilePreview | avg | 101ms | 97ms | -4ms | -3.96
| getCategoriesForTeamForUser | avg | 123ms | 119ms | -4ms | -3.26
| getChannelsForUser | avg | 67ms | 65ms | -2ms | -2.98
| createUser | avg | 275ms | 267ms | -8ms | -2.91
| login | avg | 171ms | 168ms | -3ms | -1.75
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -100.98
| getPrevTrialLicense | p99 | 490ms | 25ms | -465ms | -94.90
| createChannelBookmark | p99 | 1.9s | 400ms | -1.5s | -78.95
| updateChannelBookmarkSortOrder | p99 | 2.425s | 946ms | -1.479s | -60.99
| getTeamStats | p99 | 2.155s | 944ms | -1.211s | -56.19
| getRolesByNames | p99 | 489ms | 238ms | -251ms | -51.36
| createSchedulePost | p99 | 920ms | 450ms | -470ms | -51.09
| getChannelMembersForUser | p99 | 492ms | 241ms | -251ms | -50.96
| getFilteredUsersStats | p99 | 496ms | 246ms | -250ms | -50.38
| followThreadByUser | p99 | 1.69s | 942ms | -748ms | -44.26
| getChannelMember | p99 | 1.553s | 987ms | -566ms | -36.44
| getUsers | p99 | 1.372s | 877ms | -495ms | -36.08
| setPostReminder | p99 | 6.75s | 4.475s | -2.275s | -33.70
| getThreadsForUser | p99 | 1.45s | 986ms | -464ms | -32.00
| deleteDraft | p99 | 1.424s | 996ms | -428ms | -30.05
| getUser | p99 | 1.888s | 1.354s | -534ms | -28.28
| searchUsers | p99 | 1.598s | 1.165s | -433ms | -27.10
| searchPostsInTeam | p99 | 4.422s | 3.327s | -1.095s | -24.76
| getPostsForChannelAroundLastUnread | p99 | 3.182s | 2.489s | -693ms | -21.78
| createDirectChannel | p99 | 6.133s | 4.839s | -1.294s | -21.10
| upsertDraft | p99 | 773ms | 617ms | -156ms | -20.17
| updateReadStateThreadByUser | p99 | 7.259s | 5.889s | -1.37s | -18.87
| viewChannel | p99 | 4.249s | 3.473s | -776ms | -18.26
| getUsersByNames | p99 | 713ms | 590ms | -123ms | -17.25
| saveReaction | p99 | 2.849s | 2.42s | -429ms | -15.06
| listChannelBookmarksForChannel | p99 | 652ms | 556ms | -96ms | -14.72
| getAllTeams | p99 | 824ms | 713ms | -111ms | -13.47
| getDrafts | p99 | 1.12s | 972ms | -148ms | -13.22
| getTeamMembersForUser | p99 | 614ms | 533ms | -81ms | -13.19
| getTeamMember | p99 | 238ms | 207ms | -31ms | -13.00
| getCategoriesForTeamForUser | p99 | 1.858s | 1.638s | -220ms | -11.84
| getChannel | p99 | 2.206s | 1.945s | -261ms | -11.83
| getTeamsForUser | p99 | 781ms | 694ms | -87ms | -11.13
| getTeamsUnreadForUser | p99 | 1.941s | 1.729s | -212ms | -10.92
| getUsersByIds | p99 | 187ms | 169ms | -18ms | -9.63
| getChannelMembersForTeamForUser | p99 | 991ms | 896ms | -95ms | -9.58
| deletePost | p99 | 2.356s | 2.133s | -223ms | -9.47
| getChannelsForTeamForUser | p99 | 1s | 906ms | -94ms | -9.40
| getChannelStats | p99 | 923ms | 840ms | -83ms | -8.99
| getPostThread | p99 | 4.726s | 4.311s | -415ms | -8.78
| updateCategoriesForTeamForUser | p99 | 4.629s | 4.231s | -398ms | -8.60
| getFilePreview | p99 | 862ms | 790ms | -72ms | -8.35
| getFileThumbnail | p99 | 911ms | 835ms | -76ms | -8.34
| getPreferences | p99 | 939ms | 876ms | -63ms | -6.71
| searchGroupChannels | p99 | 980ms | 917ms | -63ms | -6.43
| getChannelsForUser | p99 | 844ms | 791ms | -53ms | -6.28
| createPost | p99 | 9.975s | 9.414s | -561ms | -5.62
| login | p99 | 2.081s | 1.986s | -95ms | -4.56
| autocompleteChannelsForTeamForSearch | p99 | 2.48s | 2.371s | -109ms | -4.39
| autocompleteUsers | p99 | 2.377s | 2.3s | -77ms | -3.24
| createGroupChannel | p99 | 10s | 9.759s | -241ms | -2.41
| getTeamScheduledPosts | p99 | 995ms | 974ms | -21ms | -2.11
| getGroups | p99 | 249ms | 244ms | -5ms | -2.01
| getProfileImage | p99 | 464ms | 456ms | -8ms | -1.72
| getPostsForChannel | p99 | 10s | 9.862s | -138ms | -1.38
| unfollowThreadByUser | p99 | 2.19s | 2.164s | -26ms | -1.19
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 74ms| 76ms | 2ms | 2.703
| BotStore.Get |  Avg| 72ms| 55ms | -17ms | -23.692
| |  P99| 1.78s| 745ms | -1.035s | -58.146
| BotStore.GetAll |  Avg| 161ms| 0s | -161ms | -100.146
| |  P99| 970ms| 0s | -970ms | -100.000
| ChannelBookmarkStore.Delete |  Avg| 9ms| 12ms | 3ms | 31.910
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 90ms| 61ms | -29ms | -32.138
| |  P99| 888ms| 755ms | -133ms | -14.986
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 34ms| 32ms | -2ms | -5.895
| |  P99| 480ms| 456ms | -24ms | -5.001
| ChannelBookmarkStore.Save |  Avg| 70ms| 43ms | -27ms | -38.319
| |  P99| 1.75s| 375ms | -1.375s | -78.569
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 413ms| 145ms | -268ms | -64.951
| |  P99| 2.41s| 2.32s | -90ms | -3.734
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 69ms| 69ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 532ms| 313ms | -219ms | -41.191
| |  P99| 990ms| 498ms | -492ms | -49.697
| ChannelStore.Autocomplete |  Avg| 1.626s| 1.539s | -87ms | -5.352
| |  P99| 4.934s| 4.891s | -43ms | -0.871
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 367ms| 323ms | -44ms | -11.993
| |  P99| 2.48s| 2.371s | -109ms | -4.395
| ChannelStore.CreateDirectChannel |  Avg| 253ms| 224ms | -29ms | -11.455
| |  P99| 2.427s| 2.405s | -22ms | -0.906
| ChannelStore.CreateInitialSidebarCategories |  Avg| 68ms| 61ms | -7ms | -10.296
| |  P99| 803ms| 690ms | -113ms | -14.080
| ChannelStore.CreateSidebarCategory |  Avg| 55ms| 48ms | -7ms | -12.838
| |  P99| 468ms| 480ms | 12ms | 2.567
| ChannelStore.Get |  Avg| 137ms| 120ms | -17ms | -12.394
| |  P99| 1.625s| 1.248s | -377ms | -23.204
| ChannelStore.GetAllChannelMembersForUser |  Avg| 49ms| 43ms | -6ms | -12.148
| |  P99| 717ms| 544ms | -173ms | -24.131
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 94ms| 85ms | -9ms | -9.541
| |  P99| 967ms| 856ms | -111ms | -11.478
| ChannelStore.GetByName |  Avg| 53ms| 50ms | -3ms | -5.685
| |  P99| 751ms| 703ms | -48ms | -6.389
| ChannelStore.GetByNameIncludeDeleted |  Avg| 3ms| 0s | -3ms | -101.860
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 58ms| 60ms | 2ms | 3.466
| |  P99| 719ms| 785ms | 66ms | 9.180
| ChannelStore.GetChannels |  Avg| 89ms| 75ms | -14ms | -15.660
| |  P99| 1s| 903ms | -97ms | -9.703
| ChannelStore.GetChannelsByIds |  Avg| 54ms| 173ms | 119ms | 219.099
| |  P99| 242ms| 249ms | 7ms | 2.887
| ChannelStore.GetChannelsByUser |  Avg| 67ms| 65ms | -2ms | -2.996
| |  P99| 843ms| 790ms | -53ms | -6.286
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 67ms| 57ms | -10ms | -14.907
| |  P99| 904ms| 800ms | -104ms | -11.505
| ChannelStore.GetFileCount |  Avg| 49ms| 47ms | -2ms | -4.076
| |  P99| 547ms| 508ms | -39ms | -7.129
| ChannelStore.GetGuestCount |  Avg| 78ms| 68ms | -10ms | -12.837
| |  P99| 960ms| 850ms | -110ms | -11.458
| ChannelStore.GetMember |  Avg| 9ms| 10ms | 1ms | 10.720
| |  P99| 169ms| 176ms | 7ms | 4.135
| ChannelStore.GetMemberCount |  Avg| 270ms| 248ms | -22ms | -8.155
| |  P99| 1.781s| 1.351s | -430ms | -24.141
| ChannelStore.GetMemberCountsByGroup |  Avg| 1ms| 0s | -1ms | -110.916
| |  P99| 5ms| 0s | -5ms | -100.984
| ChannelStore.GetMemberForPost |  Avg| 106ms| 89ms | -17ms | -16.041
| |  P99| 1.392s| 989ms | -403ms | -28.953
| ChannelStore.GetMemberLastViewedAt |  Avg| 42ms| 37ms | -5ms | -12.038
| |  P99| 595ms| 490ms | -105ms | -17.662
| ChannelStore.GetMembers |  Avg| 32ms| 57ms | 25ms | 77.780
| |  P99| 238ms| 485ms | 247ms | 103.734
| ChannelStore.GetMembersForUser |  Avg| 86ms| 73ms | -13ms | -15.132
| |  P99| 991ms| 894ms | -97ms | -9.789
| ChannelStore.GetMembersForUserWithPagination |  Avg| 103ms| 103ms | 0s | 0.000
| |  P99| 477ms| 485ms | 8ms | 1.675
| ChannelStore.GetPinnedPostCount |  Avg| 92ms| 75ms | -17ms | -18.533
| |  P99| 1.199s| 959ms | -240ms | -20.020
| ChannelStore.GetPublicChannelsForTeam |  Avg| 109ms| 112ms | 3ms | 2.762
| |  P99| 947ms| 1.913s | 966ms | 101.968
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 122ms| 118ms | -4ms | -3.275
| |  P99| 1.856s| 1.63s | -226ms | -12.176
| ChannelStore.GetSidebarCategory |  Avg| 136ms| 91ms | -45ms | -33.182
| |  P99| 3.283s| 963ms | -2.32s | -70.659
| ChannelStore.GetTeamChannels |  Avg| 198ms| 105ms | -93ms | -46.892
| |  P99| 2.11s| 770ms | -1.34s | -63.507
| ChannelStore.IncrementMentionCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 83ms| 84ms | 1ms | 1.209
| ChannelStore.IsReadOnlyChannel |  Avg| 41ms| 36ms | -5ms | -12.208
| |  P99| 657ms| 500ms | -157ms | -23.899
| ChannelStore.Save |  Avg| 124ms| 92ms | -32ms | -25.733
| |  P99| 2.058s| 875ms | -1.183s | -57.497
| ChannelStore.SaveMember |  Avg| 226ms| 201ms | -25ms | -11.074
| |  P99| 2.493s| 2.357s | -136ms | -5.455
| ChannelStore.SearchGroupChannels |  Avg| 94ms| 78ms | -16ms | -17.087
| |  P99| 980ms| 917ms | -63ms | -6.431
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 11ms | 1ms | 9.577
| |  P99| 152ms| 159ms | 7ms | 4.619
| ChannelStore.UpdateSidebarCategories |  Avg| 229ms| 227ms | -2ms | -0.873
| |  P99| 2.24s| 2.414s | 174ms | 7.768
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 72ms| 74ms | 2ms | 2.767
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 8ms | -2ms | -19.246
| |  P99| 171ms| 85ms | -86ms | -50.195
| CommandWebhookStore.Cleanup |  Avg| 32ms| 9ms | -23ms | -71.543
| |  P99| 241ms| 48ms | -193ms | -80.083
| ComplianceStore.MessageExport |  Avg| 4ms| 1.256s | 1.252s | 29299.524
| |  P99| 5ms| 4.875s | 4.87s | 98356.481
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 8ms| 7ms | -1ms | -13.046
| |  P99| 93ms| 88ms | -5ms | -5.383
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 46ms| 57ms | 11ms | 24.152
| |  P99| 232ms| 235ms | 3ms | 1.293
| DraftStore.Get |  Avg| 109ms| 93ms | -16ms | -14.722
| |  P99| 1.422s| 996ms | -426ms | -29.963
| DraftStore.GetDraftsForUser |  Avg| 94ms| 82ms | -12ms | -12.800
| |  P99| 987ms| 912ms | -75ms | -7.602
| DraftStore.Upsert |  Avg| 8ms| 9ms | 1ms | 12.180
| |  P99| 96ms| 97ms | 1ms | 1.044
| EmojiStore.GetByName |  Avg| 88ms| 73ms | -15ms | -17.026
| |  P99| 1.065s| 917ms | -148ms | -13.898
| EmojiStore.GetMultipleByName |  Avg| 119ms| 128ms | 9ms | 7.541
| |  P99| 810ms| 850ms | 40ms | 4.938
| EmojiStore.Search |  Avg| 2ms| 0s | -2ms | -97.819
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 86ms | -6ms | -6.511
| FileInfoStore.Get |  Avg| 49ms| 44ms | -5ms | -10.212
| |  P99| 661ms| 511ms | -150ms | -22.695
| FileInfoStore.GetByIds |  Avg| 101ms| 84ms | -17ms | -16.910
| |  P99| 996ms| 935ms | -61ms | -6.126
| FileInfoStore.GetForPost |  Avg| 109ms| 91ms | -18ms | -16.491
| |  P99| 1.456s| 1.042s | -414ms | -28.433
| FileInfoStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 100ms| 97ms | -3ms | -3.003
| FileInfoStore.SetContent |  Avg| 12ms| 14ms | 2ms | 17.174
| |  P99| 153ms| 201ms | 48ms | 31.475
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 51ms| 46ms | -5ms | -9.841
| |  P99| 799ms| 696ms | -103ms | -12.898
| GroupStore.GetByName |  Avg| 35ms| 32ms | -3ms | -8.665
| |  P99| 471ms| 435ms | -36ms | -7.638
| GroupStore.GetGroups |  Avg| 86ms| 73ms | -13ms | -15.139
| |  P99| 1.064s| 926ms | -138ms | -12.970
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 150ms| 100ms | -50ms | -33.239
| |  P99| 249ms| 246ms | -3ms | -1.207
| JobStore.GetAllByStatus |  Avg| 90ms| 72ms | -18ms | -19.894
| |  P99| 982ms| 879ms | -103ms | -10.494
| JobStore.GetAllByTypePage |  Avg| 48ms| 83ms | 35ms | 73.183
| |  P99| 470ms| 810ms | 340ms | 72.333
| JobStore.GetCountByStatusAndType |  Avg| 86ms| 113ms | 27ms | 31.379
| |  P99| 765ms| 1.87s | 1.105s | 144.444
| JobStore.GetNewestJobByStatusesAndType |  Avg| 77ms| 82ms | 5ms | 6.454
| |  P99| 849ms| 929ms | 80ms | 9.418
| JobStore.Save |  Avg| 5ms| 8ms | 3ms | 62.156
| |  P99| 44ms| 86ms | 42ms | 96.330
| JobStore.UpdateOptimistically |  Avg| 5ms| 6ms | 1ms | 19.359
| |  P99| 67ms| 67ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -21.367
| |  P99| 44ms| 38ms | -6ms | -13.746
| JobStore.UpdateStatusOptimistically |  Avg| 11ms| 15ms | 4ms | 36.417
| |  P99| 98ms| 180ms | 82ms | 83.887
| LicenseStore.GetAll |  Avg| 126ms| 8ms | -118ms | -93.316
| |  P99| 487ms| 25ms | -462ms | -94.769
| LinkMetadataStore.Get |  Avg| 81ms| 68ms | -13ms | -16.040
| |  P99| 985ms| 893ms | -92ms | -9.343
| LinkMetadataStore.Save |  Avg| 5ms| 8ms | 3ms | 62.575
| |  P99| 49ms| 100ms | 51ms | 104.082
| PluginStore.Delete |  Avg| 2ms| 3ms | 1ms | 42.010
| |  P99| 33ms| 38ms | 5ms | 15.028
| PluginStore.Get |  Avg| 31ms| 21ms | -10ms | -32.312
| |  P99| 232ms| 232ms | 0s | 0.000
| PluginStore.List |  Avg| 84ms| 58ms | -26ms | -30.773
| |  P99| 1.09s| 830ms | -260ms | -23.853
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 85ms| 87ms | 2ms | 2.356
| PostAcknowledgementStore.GetForPost |  Avg| 59ms| 75ms | 16ms | 27.128
| |  P99| 729ms| 981ms | 252ms | 34.592
| PostAcknowledgementStore.GetForPosts |  Avg| 122ms| 100ms | -22ms | -17.969
| |  P99| 2.074s| 1.768s | -306ms | -14.754
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 2ms | -1ms | -39.378
| |  P99| 62ms| 29ms | -33ms | -53.222
| PostPersistentNotificationStore.Get |  Avg| 3ms| 4ms | 1ms | 33.622
| |  P99| 59ms| 79ms | 20ms | 33.896
| PostPersistentNotificationStore.GetSingle |  Avg| 90ms| 74ms | -16ms | -17.808
| |  P99| 1.057s| 931ms | -126ms | -11.919
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 2ms | -1ms | -28.611
| |  P99| 10ms| 5ms | -5ms | -51.020
| PostPriorityStore.GetForPost |  Avg| 76ms| 74ms | -2ms | -2.631
| |  P99| 936ms| 986ms | 50ms | 5.342
| PostPriorityStore.GetForPosts |  Avg| 127ms| 104ms | -23ms | -18.142
| |  P99| 2.104s| 1.822s | -282ms | -13.401
| PostStore.AnalyticsPostCount |  Avg| 1.308s| 1.482s | 174ms | 13.306
| |  P99| 2.48s| 2.482s | 2ms | 0.081
| PostStore.AnalyticsPostCountByTeam |  Avg| 1.371s| 1.231s | -140ms | -10.209
| |  P99| 2.485s| 2.478s | -7ms | -0.282
| PostStore.Delete |  Avg| 103ms| 94ms | -9ms | -8.737
| |  P99| 1.78s| 1.765s | -15ms | -0.843
| PostStore.Get |  Avg| 161ms| 134ms | -27ms | -16.767
| |  P99| 2.102s| 1.812s | -290ms | -13.793
| PostStore.GetEtag |  Avg| 80ms| 69ms | -11ms | -13.724
| |  P99| 955ms| 849ms | -106ms | -11.103
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 67ms| 70ms | 3ms | 4.486
| PostStore.GetPostIdBeforeTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 86ms| 87ms | 1ms | 1.168
| PostStore.GetPostReminderMetadata |  Avg| 83ms| 112ms | 29ms | 34.787
| |  P99| 930ms| 1.875s | 945ms | 101.612
| PostStore.GetPostReminders |  Avg| 17ms| 20ms | 3ms | 17.961
| |  P99| 179ms| 231ms | 52ms | 28.969
| PostStore.GetPosts |  Avg| 39ms| 35ms | -4ms | -10.245
| |  P99| 495ms| 463ms | -32ms | -6.465
| PostStore.GetPostsAfter |  Avg| 75ms| 72ms | -3ms | -4.006
| |  P99| 1.229s| 921ms | -308ms | -25.059
| PostStore.GetPostsBefore |  Avg| 75ms| 65ms | -10ms | -13.348
| |  P99| 922ms| 823ms | -99ms | -10.739
| PostStore.GetPostsByIds |  Avg| 66ms| 117ms | 51ms | 76.976
| |  P99| 247ms| 248ms | 1ms | 0.405
| PostStore.GetPostsByThread |  Avg| 89ms| 77ms | -12ms | -13.559
| |  P99| 1.1s| 967ms | -133ms | -12.088
| PostStore.GetPostsSince |  Avg| 110ms| 96ms | -14ms | -12.738
| |  P99| 1.043s| 937ms | -106ms | -10.167
| PostStore.GetSingle |  Avg| 79ms| 66ms | -13ms | -16.410
| |  P99| 983ms| 885ms | -98ms | -9.971
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 20ms| 21ms | 1ms | 4.908
| |  P99| 230ms| 233ms | 3ms | 1.306
| PostStore.SearchPostsForUser |  Avg| 128ms| 113ms | -15ms | -11.688
| |  P99| 1.432s| 976ms | -456ms | -31.839
| PostStore.SetPostReminder |  Avg| 22ms| 9ms | -13ms | -59.329
| |  P99| 226ms| 156ms | -70ms | -31.025
| PostStore.Update |  Avg| 25ms| 22ms | -3ms | -12.240
| |  P99| 206ms| 211ms | 5ms | 2.432
| PreferenceStore.DeleteCategoryAndName |  Avg| 10ms| 12ms | 2ms | 19.847
| |  P99| 178ms| 176ms | -2ms | -1.124
| PreferenceStore.Get |  Avg| 74ms| 63ms | -11ms | -14.919
| |  P99| 937ms| 841ms | -96ms | -10.247
| PreferenceStore.GetAll |  Avg| 72ms| 67ms | -5ms | -6.908
| |  P99| 920ms| 857ms | -63ms | -6.845
| PreferenceStore.Save |  Avg| 16ms| 17ms | 1ms | 6.237
| |  P99| 219ms| 224ms | 5ms | 2.285
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 6ms | 5ms | 533.511
| |  P99| 5ms| 24ms | 19ms | 383.838
| ProductNoticesStore.GetViews |  Avg| 2ms| 91ms | 89ms | 3608.078
| |  P99| 5ms| 247ms | 242ms | 4887.618
| ProductNoticesStore.View |  Avg| 39ms| 39ms | 0s | 0.000
| |  P99| 363ms| 374ms | 11ms | 3.031
| ReactionStore.GetForPost |  Avg| 102ms| 71ms | -31ms | -30.504
| |  P99| 1.612s| 891ms | -721ms | -44.729
| RetentionPolicyStore.GetAll |  Avg| 107ms| 0s | -107ms | -100.404
| |  P99| 249ms| 0s | -249ms | -100.201
| RetentionPolicyStore.GetCount |  Avg| 77ms| 0s | -77ms | -99.930
| |  P99| 100ms| 0s | -100ms | -100.503
| RoleStore.ChannelHigherScopedPermissions |  Avg| 140ms| 52ms | -88ms | -62.928
| |  P99| 1.941s| 492ms | -1.449s | -74.663
| RoleStore.GetByNames |  Avg| 140ms| 79ms | -61ms | -43.572
| |  P99| 1.185s| 1.05s | -135ms | -11.392
| ScheduledPostStore.CreateScheduledPost |  Avg| 10ms| 8ms | -2ms | -20.473
| |  P99| 92ms| 97ms | 5ms | 5.452
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 81ms| 62ms | -19ms | -23.457
| |  P99| 883ms| 750ms | -133ms | -15.071
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 41ms| 40ms | -1ms | -2.460
| |  P99| 525ms| 492ms | -33ms | -6.289
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 4ms| 9ms | 5ms | 128.782
| |  P99| 44ms| 92ms | 48ms | 108.782
| SchemeStore.GetAllPage |  Avg| 41ms| 3ms | -38ms | -92.498
| |  P99| 50ms| 5ms | -45ms | -90.452
| SessionStore.Get |  Avg| 55ms| 50ms | -5ms | -9.018
| |  P99| 760ms| 636ms | -124ms | -16.322
| SessionStore.GetLRUSessions |  Avg| 39ms| 37ms | -2ms | -5.164
| |  P99| 509ms| 482ms | -27ms | -5.300
| SessionStore.GetSessionsExpired |  Avg| 141ms| 121ms | -20ms | -14.173
| |  P99| 490ms| 2.17s | 1.68s | 342.857
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 72ms| 56ms | -16ms | -22.181
| |  P99| 967ms| 794ms | -173ms | -17.889
| SessionStore.Remove |  Avg| 6ms| 5ms | -1ms | -15.398
| |  P99| 65ms| 31ms | -34ms | -51.910
| SessionStore.Save |  Avg| 41ms| 39ms | -2ms | -4.927
| |  P99| 496ms| 478ms | -18ms | -3.626
| SessionStore.UpdateLastActivityAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 80ms| 80ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 45ms| 41ms | -4ms | -8.886
| |  P99| 657ms| 511ms | -146ms | -22.209
| StatusStore.Get |  Avg| 67ms| 57ms | -10ms | -14.912
| |  P99| 912ms| 778ms | -134ms | -14.692
| StatusStore.GetByIds |  Avg| 114ms| 99ms | -15ms | -13.172
| |  P99| 1.454s| 1.208s | -246ms | -16.924
| StatusStore.SaveOrUpdate |  Avg| 17ms| 42ms | 25ms | 148.748
| |  P99| 295ms| 951ms | 656ms | 222.721
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 23ms| 19ms | -4ms | -17.222
| |  P99| 215ms| 232ms | 17ms | 7.916
| StatusStore.UpdateLastActivityAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.122
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 67ms| 68ms | 1ms | 1.492
| TeamStore.AnalyticsTeamCount |  Avg| 523ms| 69ms | -454ms | -86.788
| |  P99| 990ms| 245ms | -745ms | -75.253
| TeamStore.Get |  Avg| 77ms| 64ms | -13ms | -16.919
| |  P99| 972ms| 877ms | -95ms | -9.769
| TeamStore.GetActiveMemberCount |  Avg| 303ms| 266ms | -37ms | -12.210
| |  P99| 971ms| 944ms | -27ms | -2.780
| TeamStore.GetAllPage |  Avg| 53ms| 49ms | -4ms | -7.491
| |  P99| 775ms| 651ms | -124ms | -15.996
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 59ms| 55ms | -4ms | -6.723
| |  P99| 823ms| 741ms | -82ms | -9.966
| TeamStore.GetMany |  Avg| 118ms| 101ms | -17ms | -14.450
| |  P99| 487ms| 247ms | -240ms | -49.231
| TeamStore.GetMember |  Avg| 19ms| 17ms | -2ms | -10.731
| |  P99| 364ms| 319ms | -45ms | -12.360
| TeamStore.GetTeamsByUserId |  Avg| 56ms| 53ms | -3ms | -5.325
| |  P99| 781ms| 693ms | -88ms | -11.271
| TeamStore.GetTeamsForUser |  Avg| 42ms| 40ms | -2ms | -4.815
| |  P99| 500ms| 485ms | -15ms | -3.002
| TeamStore.GetTotalMemberCount |  Avg| 282ms| 237ms | -45ms | -15.964
| |  P99| 2.155s| 925ms | -1.23s | -57.076
| TeamStore.SaveMember |  Avg| 135ms| 128ms | -7ms | -5.202
| |  P99| 862ms| 802ms | -60ms | -6.958
| ThreadStore.Get |  Avg| 96ms| 83ms | -13ms | -13.509
| |  P99| 984ms| 991ms | 7ms | 0.711
| ThreadStore.GetMembershipForUser |  Avg| 85ms| 73ms | -12ms | -14.063
| |  P99| 989ms| 920ms | -69ms | -6.976
| ThreadStore.GetTeamsUnreadForUser |  Avg| 96ms| 83ms | -13ms | -13.598
| |  P99| 1.69s| 1.351s | -339ms | -20.065
| ThreadStore.GetThreadFollowers |  Avg| 86ms| 73ms | -13ms | -15.038
| |  P99| 1.067s| 948ms | -119ms | -11.153
| ThreadStore.GetThreadForUser |  Avg| 117ms| 97ms | -20ms | -17.155
| |  P99| 1.777s| 1.466s | -311ms | -17.500
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 95ms| 78ms | -17ms | -17.879
| |  P99| 1.392s| 946ms | -446ms | -32.049
| ThreadStore.GetThreadsForUser |  Avg| 97ms| 82ms | -15ms | -15.437
| |  P99| 1.22s| 948ms | -272ms | -22.295
| ThreadStore.GetTotalThreads |  Avg| 56ms| 48ms | -8ms | -14.411
| |  P99| 795ms| 628ms | -167ms | -21.019
| ThreadStore.GetTotalUnreadMentions |  Avg| 64ms| 55ms | -9ms | -14.100
| |  P99| 877ms| 746ms | -131ms | -14.931
| ThreadStore.GetTotalUnreadThreads |  Avg| 55ms| 51ms | -4ms | -7.234
| |  P99| 778ms| 705ms | -73ms | -9.385
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 57ms| 50ms | -7ms | -12.251
| |  P99| 806ms| 644ms | -162ms | -20.109
| ThreadStore.MaintainMembership |  Avg| 12ms| 13ms | 1ms | 8.211
| |  P99| 194ms| 200ms | 6ms | 3.092
| ThreadStore.MarkAllAsReadByChannels |  Avg| 6ms| 7ms | 1ms | 16.651
| |  P99| 88ms| 90ms | 2ms | 2.264
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 81ms | -1ms | -1.216
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 92ms | 1ms | 1.098
| TokenStore.Cleanup |  Avg| 30ms| 13ms | -17ms | -56.796
| |  P99| 241ms| 96ms | -145ms | -60.166
| UserAccessTokenStore.GetByToken |  Avg| 79ms| 48ms | -31ms | -39.433
| |  P99| 1.12s| 450ms | -670ms | -59.821
| UserStore.AnalyticsActiveCount |  Avg| 684ms| 525ms | -159ms | -23.231
| |  P99| 2.44s| 993ms | -1.447s | -59.303
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 61ms| 25ms | -36ms | -58.886
| |  P99| 247ms| 99ms | -148ms | -59.919
| UserStore.AutocompleteUsersInChannel |  Avg| 468ms| 438ms | -30ms | -6.413
| |  P99| 2.352s| 2.253s | -99ms | -4.209
| UserStore.Count |  Avg| 215ms| 206ms | -9ms | -4.189
| |  P99| 493ms| 800ms | 307ms | 62.222
| UserStore.Get |  Avg| 51ms| 45ms | -6ms | -11.725
| |  P99| 782ms| 677ms | -105ms | -13.432
| UserStore.GetAllProfiles |  Avg| 46ms| 42ms | -4ms | -8.711
| |  P99| 766ms| 599ms | -167ms | -21.814
| UserStore.GetAllProfilesInChannel |  Avg| 787ms| 749ms | -38ms | -4.829
| |  P99| 2.484s| 2.469s | -15ms | -0.604
| UserStore.GetByUsername |  Avg| 87ms| 78ms | -9ms | -10.302
| |  P99| 1.082s| 887ms | -195ms | -18.014
| UserStore.GetForLogin |  Avg| 39ms| 36ms | -3ms | -7.702
| |  P99| 517ms| 469ms | -48ms | -9.287
| UserStore.GetMany |  Avg| 81ms| 51ms | -30ms | -37.073
| |  P99| 1.585s| 484ms | -1.101s | -69.464
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 144ms| 164ms | 20ms | 13.906
| |  P99| 249ms| 492ms | 243ms | 97.787
| UserStore.GetProfileByIds |  Avg| 63ms| 56ms | -7ms | -11.110
| |  P99| 878ms| 774ms | -104ms | -11.845
| UserStore.GetProfilesByUsernames |  Avg| 52ms| 47ms | -5ms | -9.597
| |  P99| 698ms| 569ms | -129ms | -18.469
| UserStore.GetProfilesInChannel |  Avg| 87ms| 63ms | -24ms | -27.596
| |  P99| 925ms| 710ms | -215ms | -23.243
| UserStore.GetProfilesNotInChannel |  Avg| 96ms| 83ms | -13ms | -13.531
| |  P99| 885ms| 888ms | 3ms | 0.339
| UserStore.GetUnreadCount |  Avg| 71ms| 58ms | -13ms | -18.363
| |  P99| 928ms| 812ms | -116ms | -12.504
| UserStore.IsEmpty |  Avg| 24ms| 22ms | -2ms | -8.301
| |  P99| 404ms| 343ms | -61ms | -15.118
| UserStore.Save |  Avg| 77ms| 75ms | -2ms | -2.593
| |  P99| 247ms| 246ms | -1ms | -0.405
| UserStore.Search |  Avg| 222ms| 208ms | -14ms | -6.299
| |  P99| 1.576s| 1.205s | -371ms | -23.544
| UserStore.Update |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 100ms| 209ms | 109ms | 109.448
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 79ms| 79ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 59ms| 64ms | 5ms | 8.469
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 71ms| 74ms | 3ms | 4.206
| UserTermsOfServiceStore.GetByUser |  Avg| 55ms| 49ms | -6ms | -10.987
| |  P99| 802ms| 669ms | -133ms | -16.578
| WebhookStore.GetOutgoingByTeam |  Avg| 92ms| 77ms | -15ms | -16.388
| |  P99| 1.013s| 919ms | -94ms | -9.278
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.246s| 1.307s | 61ms | 4.895
| | P99| 9.958s| 10s | 42ms | 0.422
| addTeamMember | Avg| 2.327s| 2.152s | -175ms | -7.520
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 367ms| 323ms | -44ms | -11.990
| | P99| 2.48s| 2.371s | -109ms | -4.395
| autocompleteEmojis | Avg| 2ms| 0s | -2ms | -95.712
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 422ms| 398ms | -24ms | -5.689
| | P99| 2.377s| 2.3s | -77ms | -3.239
| channelMemberCountsByGroup | Avg| 1ms| 0s | -1ms | -100.470
| | P99| 5ms| 0s | -5ms | -100.984
| createCategoryForTeamForUser | Avg| 122ms| 328ms | 206ms | 169.387
| | P99| 484ms| 2.38s | 1.896s | 391.935
| createChannel | Avg| 1.939s| 1.112s | -827ms | -42.653
| | P99| 9.567s| 10s | 433ms | 4.526
| createChannelBookmark | Avg| 86ms| 69ms | -17ms | -19.740
| | P99| 1.9s| 400ms | -1.5s | -78.946
| createDirectChannel | Avg| 777ms| 724ms | -53ms | -6.824
| | P99| 6.133s| 4.839s | -1.294s | -21.098
| createGroupChannel | Avg| 1.656s| 1.45s | -206ms | -12.440
| | P99| 10s| 9.759s | -241ms | -2.410
| createPost | Avg| 1.356s| 1.202s | -154ms | -11.354
| | P99| 9.975s| 9.414s | -561ms | -5.624
| createSchedulePost | Avg| 59ms| 39ms | -20ms | -33.849
| | P99| 920ms| 450ms | -470ms | -51.088
| createUser | Avg| 275ms| 267ms | -8ms | -2.907
| | P99| 2.192s| 2.185s | -7ms | -0.319
| deleteChannelBookmark | Avg| 96ms| 132ms | 36ms | 37.554
| | P99| 489ms| 489ms | 0s | 0.000
| deleteDraft | Avg| 109ms| 93ms | -16ms | -14.658
| | P99| 1.424s| 996ms | -428ms | -30.050
| deletePost | Avg| 288ms| 246ms | -42ms | -14.562
| | P99| 2.356s| 2.133s | -223ms | -9.465
| followThreadByUser | Avg| 151ms| 150ms | -1ms | -0.661
| | P99| 1.69s| 942ms | -748ms | -44.261
| getAllTeams | Avg| 57ms| 52ms | -5ms | -8.745
| | P99| 824ms| 713ms | -111ms | -13.469
| getCategoriesForTeamForUser | Avg| 123ms| 119ms | -4ms | -3.262
| | P99| 1.858s| 1.638s | -220ms | -11.843
| getChannel | Avg| 159ms| 136ms | -23ms | -14.451
| | P99| 2.206s| 1.945s | -261ms | -11.833
| getChannelMember | Avg| 84ms| 69ms | -15ms | -17.767
| | P99| 1.553s| 987ms | -566ms | -36.440
| getChannelMembers | Avg| 40ms| 76ms | 36ms | 90.870
| | P99| 460ms| 485ms | 25ms | 5.431
| getChannelMembersForTeamForUser | Avg| 86ms| 74ms | -12ms | -13.922
| | P99| 991ms| 896ms | -95ms | -9.582
| getChannelMembersForUser | Avg| 178ms| 52ms | -126ms | -70.725
| | P99| 492ms| 241ms | -251ms | -50.964
| getChannelStats | Avg| 44ms| 36ms | -8ms | -17.983
| | P99| 923ms| 840ms | -83ms | -8.995
| getChannelUnread | Avg| 66ms| 65ms | -1ms | -1.513
| | P99| 826ms| 839ms | 13ms | 1.573
| getChannelsForTeamForUser | Avg| 90ms| 76ms | -14ms | -15.624
| | P99| 1s| 906ms | -94ms | -9.402
| getChannelsForUser | Avg| 67ms| 65ms | -2ms | -2.984
| | P99| 844ms| 791ms | -53ms | -6.281
| getClientConfig | Avg| 17ms| 18ms | 1ms | 5.757
| | P99| 248ms| 252ms | 4ms | 1.614
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 102ms| 89ms | -13ms | -12.757
| | P99| 1.12s| 972ms | -148ms | -13.218
| getFilePreview | Avg| 101ms| 97ms | -4ms | -3.957
| | P99| 862ms| 790ms | -72ms | -8.354
| getFileThumbnail | Avg| 99ms| 93ms | -6ms | -6.035
| | P99| 911ms| 835ms | -76ms | -8.341
| getFilteredUsersStats | Avg| 308ms| 102ms | -206ms | -66.903
| | P99| 496ms| 246ms | -250ms | -50.378
| getGroups | Avg| 148ms| 73ms | -75ms | -50.762
| | P99| 249ms| 244ms | -5ms | -2.012
| getJobsByType | Avg| 48ms| 85ms | 37ms | 77.173
| | P99| 470ms| 810ms | 340ms | 72.333
| getPostThread | Avg| 514ms| 427ms | -87ms | -16.918
| | P99| 4.726s| 4.311s | -415ms | -8.781
| getPostsForChannel | Avg| 875ms| 733ms | -142ms | -16.232
| | P99| 10s| 9.862s | -138ms | -1.380
| getPostsForChannelAroundLastUnread | Avg| 223ms| 205ms | -18ms | -8.059
| | P99| 3.182s| 2.489s | -693ms | -21.781
| getPreferences | Avg| 74ms| 68ms | -6ms | -8.090
| | P99| 939ms| 876ms | -63ms | -6.712
| getPrevTrialLicense | Avg| 158ms| 8ms | -150ms | -94.931
| | P99| 490ms| 25ms | -465ms | -94.898
| getProfileImage | Avg| 72ms| 68ms | -4ms | -5.556
| | P99| 464ms| 456ms | -8ms | -1.723
| getPublicChannelsForTeam | Avg| 110ms| 113ms | 3ms | 2.734
| | P99| 947ms| 1.913s | 966ms | 101.968
| getRolesByNames | Avg| 84ms| 23ms | -61ms | -72.807
| | P99| 489ms| 238ms | -251ms | -51.355
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 15ms| 11ms | -4ms | -27.383
| | P99| 238ms| 207ms | -31ms | -13.003
| getTeamMembersForUser | Avg| 46ms| 44ms | -2ms | -4.392
| | P99| 614ms| 533ms | -81ms | -13.189
| getTeamScheduledPosts | Avg| 81ms| 81ms | 0s | 0.000
| | P99| 995ms| 974ms | -21ms | -2.111
| getTeamStats | Avg| 343ms| 286ms | -57ms | -16.601
| | P99| 2.155s| 944ms | -1.211s | -56.195
| getTeamsForUser | Avg| 56ms| 53ms | -3ms | -5.313
| | P99| 781ms| 694ms | -87ms | -11.133
| getTeamsUnreadForUser | Avg| 115ms| 104ms | -11ms | -9.596
| | P99| 1.941s| 1.729s | -212ms | -10.924
| getThreadsForUser | Avg| 100ms| 84ms | -16ms | -15.999
| | P99| 1.45s| 986ms | -464ms | -31.995
| getUser | Avg| 105ms| 87ms | -18ms | -17.125
| | P99| 1.888s| 1.354s | -534ms | -28.279
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 29ms| 32ms | 3ms | 10.219
| getUsers | Avg| 63ms| 52ms | -11ms | -17.427
| | P99| 1.372s| 877ms | -495ms | -36.083
| getUsersByIds | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 187ms| 169ms | -18ms | -9.633
| getUsersByNames | Avg| 53ms| 48ms | -5ms | -9.433
| | P99| 713ms| 590ms | -123ms | -17.246
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 40ms| 38ms | -2ms | -4.948
| | P99| 652ms| 556ms | -96ms | -14.721
| login | Avg| 171ms| 168ms | -3ms | -1.751
| | P99| 2.081s| 1.986s | -95ms | -4.564
| logout | Avg| 315ms| 346ms | 31ms | 9.830
| | P99| 4.138s| 8.1s | 3.962s | 95.758
| patchPost | Avg| 604ms| 547ms | -57ms | -9.443
| | P99| 4.766s| 4.994s | 228ms | 4.784
| removeUserCustomStatus | Avg| 374ms| 397ms | 23ms | 6.156
| | P99| 4.788s| 4.813s | 25ms | 0.522
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 280ms| 233ms | -47ms | -16.811
| | P99| 2.849s| 2.42s | -429ms | -15.059
| searchAllChannels | Avg| 1.63s| 1.542s | -88ms | -5.398
| | P99| 4.937s| 4.891s | -46ms | -0.932
| searchGroupChannels | Avg| 94ms| 78ms | -16ms | -17.065
| | P99| 980ms| 917ms | -63ms | -6.431
| searchPostsInTeam | Avg| 295ms| 244ms | -51ms | -17.296
| | P99| 4.422s| 3.327s | -1.095s | -24.760
| searchUsers | Avg| 225ms| 208ms | -17ms | -7.564
| | P99| 1.598s| 1.165s | -433ms | -27.103
| setPostReminder | Avg| 450ms| 422ms | -28ms | -6.223
| | P99| 6.75s| 4.475s | -2.275s | -33.704
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 234ms| 201ms | -33ms | -14.093
| | P99| 2.19s| 2.164s | -26ms | -1.187
| updateCategoriesForTeamForUser | Avg| 586ms| 497ms | -89ms | -15.186
| | P99| 4.629s| 4.231s | -398ms | -8.599
| updateChannelBookmark | Avg| 131ms| 120ms | -11ms | -8.397
| | P99| 925ms| 953ms | 28ms | 3.027
| updateChannelBookmarkSortOrder | Avg| 513ms| 137ms | -376ms | -73.224
| | P99| 2.425s| 946ms | -1.479s | -60.990
| updatePreferences | Avg| 25ms| 26ms | 1ms | 4.013
| | P99| 248ms| 252ms | 4ms | 1.610
| updateReadStateAllThreadsByUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 47ms| 47ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 765ms| 650ms | -115ms | -15.042
| | P99| 7.259s| 5.889s | -1.37s | -18.872
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 482ms| 497ms | 15ms | 3.115
| | P99| 2.11s| 2.089s | -21ms | -0.995
| upsertDraft | Avg| 45ms| 38ms | -7ms | -15.584
| | P99| 773ms| 617ms | -156ms | -20.171
| viewChannel | Avg| 269ms| 228ms | -41ms | -15.251
| | P99| 4.249s| 3.473s | -776ms | -18.262

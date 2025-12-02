### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 6ms | 344ms | 338ms | 5948.68
| ProductNoticesStore.GetViews | avg | 1ms | 45ms | 44ms | 3728.89
| PostStore.GetPostsByIds | avg | 1ms | 11ms | 10ms | 1076.81
| TeamStore.AnalyticsTeamCount | avg | 6ms | 22ms | 16ms | 247.36
| ChannelStore.GetChannelsByIds | avg | 1ms | 4ms | 3ms | 238.76
| PostStore.AnalyticsPostCountByTeam | avg | 3ms | 8ms | 5ms | 152.79
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 4ms | 9ms | 5ms | 125.93
| ScheduledPostStore.GetPendingScheduledPosts | avg | 8ms | 14ms | 6ms | 75.24
| UserStore.AnalyticsGetInactiveUsersCount | avg | 18ms | 30ms | 12ms | 67.27
| ChannelStore.CreateSidebarCategory | avg | 68ms | 111ms | 43ms | 62.82
| ChannelBookmarkStore.UpdateSortOrder | avg | 5ms | 7ms | 2ms | 41.36
| JobStore.GetCountByStatusAndType | avg | 7ms | 10ms | 3ms | 40.34
| LinkMetadataStore.Save | avg | 10ms | 14ms | 4ms | 40.03
| BotStore.Get | avg | 6ms | 8ms | 2ms | 31.72
| UserStore.GetProfilesInChannel | avg | 15ms | 19ms | 4ms | 25.92
| PostStore.GetPostReminderMetadata | avg | 8ms | 10ms | 2ms | 24.34
| ChannelStore.GetSidebarCategory | avg | 18ms | 22ms | 4ms | 21.68
| ClusterDiscoveryStore.SetLastPingAt | avg | 14ms | 17ms | 3ms | 21.52
| ChannelStore.AutocompleteInTeamForSearch | avg | 45ms | 53ms | 8ms | 17.62
| ChannelStore.UpdateSidebarCategories | avg | 93ms | 107ms | 14ms | 15.03
| ChannelStore.GetTeamChannels | avg | 33ms | 37ms | 4ms | 12.07
| ChannelStore.Save | avg | 36ms | 40ms | 4ms | 11.06
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 10ms | 985ms | 975ms | 9796.97
| ProductNoticesStore.GetViews | p99 | 5ms | 50ms | 45ms | 908.95
| PostStore.GetPostsByIds | p99 | 5ms | 49ms | 44ms | 888.89
| ChannelStore.GetChannelsByIds | p99 | 5ms | 24ms | 19ms | 382.90
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 23ms | 84ms | 61ms | 262.93
| ChannelStore.GetTeamChannels | p99 | 98ms | 236ms | 138ms | 141.42
| UserStore.GetProfilesNotInChannel | p99 | 95ms | 209ms | 114ms | 119.79
| ChannelStore.Save | p99 | 249ms | 365ms | 116ms | 46.65
| PostStore.GetPostReminderMetadata | p99 | 99ms | 142ms | 43ms | 43.36
| ChannelStore.GetSidebarCategory | p99 | 179ms | 237ms | 58ms | 32.45
| ClusterDiscoveryStore.SetLastPingAt | p99 | 160ms | 202ms | 42ms | 26.33
| JobStore.GetCountByStatusAndType | p99 | 98ms | 121ms | 23ms | 23.59
| UserStore.GetProfilesInChannel | p99 | 202ms | 224ms | 22ms | 10.89
| LinkMetadataStore.Save | p99 | 166ms | 180ms | 14ms | 8.43
| FileInfoStore.Save | p99 | 160ms | 172ms | 12ms | 7.52
| JobStore.GetNewestJobByStatusesAndType | p99 | 74ms | 79ms | 5ms | 6.75
| UserStore.GetMany | p99 | 93ms | 99ms | 6ms | 6.46
| JobStore.GetAllByTypePage | p99 | 206ms | 215ms | 9ms | 4.37
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 196ms | 203ms | 7ms | 3.57
| BotStore.Get | p99 | 83ms | 85ms | 2ms | 2.42
| ChannelStore.CreateSidebarCategory | p99 | 480ms | 489ms | 9ms | 1.87
| FileInfoStore.GetByIds | p99 | 176ms | 178ms | 2ms | 1.14
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 8ms | 0s | -8ms | -105.65
| DesktopTokensStore.DeleteOlderThan | avg | 7ms | 0s | -7ms | -103.34
| ChannelStore.GetMemberCountsByGroup | avg | 12ms | 0s | -12ms | -99.56
| RetentionPolicyStore.GetAll | avg | 8ms | 0s | -8ms | -99.14
| FileInfoStore.Search | avg | 4ms | 0s | -4ms | -94.44
| LicenseStore.GetAll | avg | 17ms | 1ms | -16ms | -93.07
| EmojiStore.GetMultipleByName | avg | 11ms | 2ms | -9ms | -83.62
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 16ms | 3ms | -13ms | -79.25
| ThreadStore.MarkAllAsReadByTeam | avg | 14ms | 3ms | -11ms | -78.37
| SchemeStore.GetAllPage | avg | 57ms | 18ms | -39ms | -68.15
| RoleStore.GetByNames | avg | 44ms | 17ms | -27ms | -61.12
| ChannelStore.GetMembers | avg | 21ms | 8ms | -13ms | -60.88
| CommandWebhookStore.Cleanup | avg | 21ms | 9ms | -12ms | -57.51
| ChannelBookmarkStore.Save | avg | 45ms | 20ms | -25ms | -55.35
| TokenStore.Cleanup | avg | 11ms | 5ms | -6ms | -54.54
| PostPersistentNotificationStore.DeleteExpired | avg | 8ms | 4ms | -4ms | -53.18
| ChannelBookmarkStore.Delete | avg | 18ms | 9ms | -9ms | -49.56
| ProductNoticesStore.ClearOldNotices | avg | 71ms | 39ms | -32ms | -45.21
| UserStore.GetProfilesNotInChannel | avg | 19ms | 11ms | -8ms | -42.45
| JobStore.GetAllByTypePage | avg | 22ms | 13ms | -9ms | -41.42
| PostPersistentNotificationStore.Get | avg | 10ms | 6ms | -4ms | -40.80
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 7ms | 4ms | -3ms | -40.68
| UserAccessTokenStore.GetByToken | avg | 8ms | 5ms | -3ms | -38.27
| UserStore.GetMany | avg | 14ms | 9ms | -5ms | -35.29
| JobStore.UpdateStatusOptimistically | avg | 12ms | 8ms | -4ms | -33.90
| ChannelBookmarkStore.Get | avg | 6ms | 4ms | -2ms | -32.70
| PostStore.SetPostReminder | avg | 25ms | 17ms | -8ms | -32.17
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 23ms | 16ms | -7ms | -30.71
| PreferenceStore.DeleteCategoryAndName | avg | 17ms | 12ms | -5ms | -28.60
| ThreadStore.Get | avg | 9ms | 7ms | -2ms | -23.03
| ScheduledPostStore.CreateScheduledPost | avg | 14ms | 11ms | -3ms | -21.71
| PostStore.Delete | avg | 85ms | 67ms | -18ms | -21.30
| RoleStore.ChannelHigherScopedPermissions | avg | 14ms | 11ms | -3ms | -21.18
| JobStore.UpdateStatus | avg | 9ms | 7ms | -2ms | -21.12
| StatusStore.Get | avg | 10ms | 8ms | -2ms | -20.63
| PostStore.GetPostsAfter | avg | 10ms | 8ms | -2ms | -20.41
| FileInfoStore.GetForPost | avg | 11ms | 9ms | -2ms | -18.86
| StatusStore.GetByIds | avg | 17ms | 14ms | -3ms | -17.90
| ChannelStore.CreateDirectChannel | avg | 74ms | 61ms | -13ms | -17.45
| StatusStore.SaveOrUpdateMany | avg | 19ms | 16ms | -3ms | -15.85
| UserStore.GetProfileByIds | avg | 13ms | 11ms | -2ms | -15.70
| ChannelStore.GetMembersForUser | avg | 13ms | 11ms | -2ms | -15.46
| PostPriorityStore.GetForPosts | avg | 13ms | 11ms | -2ms | -15.39
| ChannelStore.Get | avg | 20ms | 17ms | -3ms | -15.23
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 14ms | 12ms | -2ms | -14.45
| WebhookStore.GetOutgoingByTeam | avg | 15ms | 13ms | -2ms | -13.77
| DraftStore.Get | avg | 15ms | 13ms | -2ms | -13.72
| TeamStore.GetActiveMemberCount | avg | 73ms | 63ms | -10ms | -13.71
| ChannelStore.SearchGroupChannels | avg | 16ms | 14ms | -2ms | -12.36
| SessionStore.Get | avg | 18ms | 16ms | -2ms | -11.10
| PostStore.Update | avg | 38ms | 34ms | -4ms | -10.54
| ChannelStore.CreateInitialSidebarCategories | avg | 40ms | 36ms | -4ms | -10.01
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 22ms | 20ms | -2ms | -9.19
| TeamStore.GetTotalMemberCount | avg | 69ms | 63ms | -6ms | -8.70
| ChannelStore.AnalyticsCountAll | avg | 23ms | 21ms | -2ms | -8.60
| ChannelStore.SaveMember | avg | 59ms | 54ms | -5ms | -8.42
| PostStore.GetPostsSince | avg | 26ms | 24ms | -2ms | -7.79
| PostStore.Save | avg | 39ms | 36ms | -3ms | -7.76
| PostStore.Get | avg | 27ms | 25ms | -2ms | -7.28
| PreferenceStore.Save | avg | 30ms | 28ms | -2ms | -6.62
| UserStore.Update | avg | 31ms | 29ms | -2ms | -6.53
| ChannelStore.GetMemberCount | avg | 33ms | 31ms | -2ms | -6.06
| UserStore.AutocompleteUsersInChannel | avg | 71ms | 67ms | -4ms | -5.66
| TeamStore.SaveMember | avg | 38ms | 36ms | -2ms | -5.29
| UserStore.GetAllProfilesInChannel | avg | 334ms | 318ms | -16ms | -4.78
| ProductNoticesStore.View | avg | 107ms | 102ms | -5ms | -4.67
| UserStore.Save | avg | 166ms | 160ms | -6ms | -3.62
| PostStore.SearchPostsForUser | avg | 173ms | 168ms | -5ms | -2.88
| PostStore.AnalyticsPostCount | avg | 200ms | 195ms | -5ms | -2.50
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 10ms | 0s | -10ms | -100.50
| RetentionPolicyStore.GetCount | p99 | 10ms | 0s | -10ms | -100.50
| DesktopTokensStore.DeleteOlderThan | p99 | 10ms | 0s | -10ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 93ms | 0s | -93ms | -99.73
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 216ms | 5ms | -211ms | -97.57
| LicenseStore.GetAll | p99 | 95ms | 5ms | -90ms | -94.24
| ThreadStore.MarkAllAsReadByTeam | p99 | 49ms | 5ms | -44ms | -89.80
| CommandWebhookStore.Cleanup | p99 | 241ms | 25ms | -216ms | -89.63
| TokenStore.Cleanup | p99 | 48ms | 10ms | -38ms | -78.35
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 24ms | 5ms | -19ms | -78.35
| SchemeStore.GetAllPage | p99 | 100ms | 25ms | -75ms | -75.38
| ChannelBookmarkStore.Delete | p99 | 95ms | 24ms | -71ms | -75.13
| UserAccessTokenStore.GetByToken | p99 | 170ms | 46ms | -124ms | -72.73
| SessionStore.GetSessionsExpired | p99 | 23ms | 9ms | -14ms | -61.14
| RoleStore.GetByNames | p99 | 242ms | 99ms | -143ms | -59.20
| SessionStore.Remove | p99 | 211ms | 92ms | -119ms | -56.40
| PreferenceStore.DeleteCategoryAndName | p99 | 202ms | 93ms | -109ms | -53.96
| RoleStore.ChannelHigherScopedPermissions | p99 | 177ms | 82ms | -95ms | -53.67
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 202ms | 95ms | -107ms | -52.97
| EmojiStore.GetMultipleByName | p99 | 49ms | 24ms | -25ms | -51.41
| PostStore.GetPostReminders | p99 | 196ms | 96ms | -100ms | -51.02
| ChannelStore.GetMembers | p99 | 98ms | 48ms | -50ms | -50.89
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 10ms | 5ms | -5ms | -50.74
| ChannelBookmarkStore.Save | p99 | 437ms | 217ms | -220ms | -50.29
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 50ms | -49ms | -49.49
| TeamStore.AnalyticsTeamCount | p99 | 49ms | 25ms | -24ms | -49.48
| ChannelStore.AnalyticsCountAll | p99 | 49ms | 25ms | -24ms | -49.45
| UserStore.AnalyticsActiveCount | p99 | 97ms | 50ms | -47ms | -48.58
| PostPersistentNotificationStore.DeleteExpired | p99 | 71ms | 37ms | -34ms | -47.89
| ChannelBookmarkStore.Get | p99 | 86ms | 45ms | -41ms | -47.67
| PostStore.SetPostReminder | p99 | 169ms | 91ms | -78ms | -46.16
| JobStore.UpdateStatus | p99 | 107ms | 58ms | -49ms | -45.59
| PostStore.Delete | p99 | 840ms | 466ms | -374ms | -44.52
| TeamStore.GetTotalMemberCount | p99 | 427ms | 240ms | -187ms | -43.74
| ChannelStore.UpdateSidebarCategories | p99 | 1.06s | 615ms | -445ms | -41.98
| JobStore.Save | p99 | 76ms | 47ms | -29ms | -38.16
| PostAcknowledgementStore.GetForPost | p99 | 112ms | 70ms | -42ms | -37.34
| PostStore.GetPostsAfter | p99 | 145ms | 93ms | -52ms | -35.84
| ChannelStore.AutocompleteInTeamForSearch | p99 | 391ms | 262ms | -129ms | -33.02
| ChannelStore.GetGuestCount | p99 | 145ms | 99ms | -46ms | -31.75
| PreferenceStore.GetAll | p99 | 139ms | 96ms | -43ms | -31.04
| StatusStore.Get | p99 | 154ms | 110ms | -44ms | -28.56
| EmojiStore.GetByName | p99 | 130ms | 95ms | -35ms | -26.95
| FileInfoStore.GetForPost | p99 | 182ms | 133ms | -49ms | -26.87
| JobStore.UpdateStatusOptimistically | p99 | 107ms | 79ms | -28ms | -26.05
| UserStore.GetByUsername | p99 | 127ms | 94ms | -33ms | -25.99
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 146ms | 109ms | -37ms | -25.37
| ChannelStore.GetPinnedPostCount | p99 | 137ms | 103ms | -34ms | -24.83
| ChannelStore.CreateDirectChannel | p99 | 623ms | 471ms | -152ms | -24.40
| DraftStore.Delete | p99 | 147ms | 112ms | -35ms | -23.82
| UserStore.GetUnreadCount | p99 | 128ms | 98ms | -30ms | -23.46
| PostStore.GetPostsByThread | p99 | 140ms | 108ms | -32ms | -22.78
| UserStore.Update | p99 | 305ms | 236ms | -69ms | -22.62
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 129ms | 100ms | -29ms | -22.42
| ChannelStore.GetByName | p99 | 124ms | 97ms | -27ms | -21.78
| LinkMetadataStore.Get | p99 | 122ms | 96ms | -26ms | -21.34
| PostPersistentNotificationStore.Get | p99 | 90ms | 71ms | -19ms | -21.11
| GroupStore.GetGroups | p99 | 121ms | 96ms | -25ms | -20.71
| ChannelStore.GetFileCount | p99 | 137ms | 110ms | -27ms | -19.74
| ChannelStore.SearchGroupChannels | p99 | 207ms | 167ms | -40ms | -19.29
| UserStore.Get | p99 | 147ms | 119ms | -28ms | -19.03
| StatusStore.UpdateExpiredDNDStatuses | p99 | 160ms | 130ms | -30ms | -18.81
| ThreadStore.GetMembershipForUser | p99 | 148ms | 121ms | -27ms | -18.30
| ThreadStore.GetTeamsUnreadForUser | p99 | 173ms | 143ms | -30ms | -17.36
| PostStore.GetEtag | p99 | 182ms | 151ms | -31ms | -17.07
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 88ms | 74ms | -14ms | -15.93
| PropertyValueStore.SearchPropertyValues | p99 | 174ms | 147ms | -27ms | -15.48
| ScheduledPostStore.CreateScheduledPost | p99 | 99ms | 84ms | -15ms | -15.16
| ChannelStore.CreateInitialSidebarCategories | p99 | 376ms | 319ms | -57ms | -15.16
| ChannelStore.GetMembersForUser | p99 | 179ms | 152ms | -27ms | -15.07
| FileInfoStore.Get | p99 | 176ms | 150ms | -26ms | -14.80
| ChannelStore.GetAllChannelMembersForUser | p99 | 157ms | 134ms | -23ms | -14.66
| UserStore.GetProfileByIds | p99 | 180ms | 154ms | -26ms | -14.45
| ChannelStore.GetChannels | p99 | 191ms | 164ms | -27ms | -14.13
| PostStore.GetSingle | p99 | 108ms | 93ms | -15ms | -13.83
| PostPriorityStore.GetForPost | p99 | 95ms | 82ms | -13ms | -13.64
| PreferenceStore.Get | p99 | 174ms | 151ms | -23ms | -13.19
| UserStore.GetAllProfiles | p99 | 86ms | 75ms | -11ms | -12.75
| UserStore.AutocompleteUsersInChannel | p99 | 338ms | 295ms | -43ms | -12.73
| JobStore.UpdateOptimistically | p99 | 104ms | 91ms | -13ms | -12.44
| UserStore.GetProfilesByUsernames | p99 | 183ms | 161ms | -22ms | -12.03
| ThreadStore.Get | p99 | 97ms | 86ms | -11ms | -11.30
| DraftStore.Get | p99 | 204ms | 181ms | -23ms | -11.29
| PostStore.GetPostsBefore | p99 | 183ms | 163ms | -20ms | -10.94
| ThreadStore.GetThreadsForUser | p99 | 192ms | 171ms | -21ms | -10.93
| SessionStore.Save | p99 | 174ms | 155ms | -19ms | -10.92
| DraftStore.Upsert | p99 | 165ms | 147ms | -18ms | -10.88
| PostAcknowledgementStore.GetForPosts | p99 | 206ms | 184ms | -22ms | -10.68
| PostPriorityStore.GetForPosts | p99 | 211ms | 189ms | -22ms | -10.44
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 201ms | 180ms | -21ms | -10.42
| StatusStore.SaveOrUpdate | p99 | 135ms | 121ms | -14ms | -10.38
| UserStore.UpdateLastLogin | p99 | 79ms | 71ms | -8ms | -10.08
| ChannelStore.Get | p99 | 231ms | 208ms | -23ms | -9.97
| PostStore.Save | p99 | 366ms | 331ms | -35ms | -9.57
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 105ms | 95ms | -10ms | -9.52
| UserStore.GetAllProfilesInChannel | p99 | 1.931s | 1.749s | -182ms | -9.43
| PostStore.GetPostIdAfterTime | p99 | 75ms | 68ms | -7ms | -9.32
| TeamStore.Get | p99 | 99ms | 90ms | -9ms | -9.13
| TeamStore.GetTeamsForUser | p99 | 100ms | 91ms | -9ms | -9.01
| UserStore.UpdateUpdateAt | p99 | 80ms | 73ms | -7ms | -8.73
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 95ms | 87ms | -8ms | -8.46
| PostPersistentNotificationStore.GetSingle | p99 | 96ms | 88ms | -8ms | -8.34
| TeamStore.GetMember | p99 | 86ms | 79ms | -7ms | -8.11
| WebhookStore.GetOutgoingByTeam | p99 | 201ms | 185ms | -16ms | -7.96
| StatusStore.SaveOrUpdateMany | p99 | 214ms | 197ms | -17ms | -7.94
| ThreadStore.GetThreadUnreadReplyCount | p99 | 172ms | 159ms | -13ms | -7.56
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 106ms | 98ms | -8ms | -7.52
| ChannelStore.SaveMember | p99 | 484ms | 448ms | -36ms | -7.44
| UserStore.GetForLogin | p99 | 98ms | 91ms | -7ms | -7.15
| ThreadStore.GetTotalUnreadThreads | p99 | 98ms | 91ms | -7ms | -7.14
| PostStore.GetPosts | p99 | 85ms | 79ms | -6ms | -7.10
| StatusStore.GetByIds | p99 | 211ms | 196ms | -15ms | -7.10
| FileInfoStore.AttachToPost | p99 | 202ms | 189ms | -13ms | -6.43
| ReactionStore.GetForPost | p99 | 95ms | 89ms | -6ms | -6.34
| UserStore.IsEmpty | p99 | 48ms | 45ms | -3ms | -6.31
| ThreadStore.GetThreadFollowers | p99 | 97ms | 91ms | -6ms | -6.22
| TeamStore.GetTeamsByUserId | p99 | 99ms | 93ms | -6ms | -6.06
| ChannelStore.GetMember | p99 | 99ms | 93ms | -6ms | -6.06
| SessionStore.GetLRUSessions | p99 | 87ms | 82ms | -5ms | -5.78
| ThreadStore.UpdateMembership | p99 | 92ms | 87ms | -5ms | -5.42
| SessionStore.UpdateLastActivityAt | p99 | 93ms | 88ms | -5ms | -5.36
| UserStore.UpdateFailedPasswordAttempts | p99 | 95ms | 90ms | -5ms | -5.29
| ChannelStore.GetChannelsByUser | p99 | 95ms | 90ms | -5ms | -5.25
| UserTermsOfServiceStore.GetByUser | p99 | 96ms | 91ms | -5ms | -5.19
| ChannelStore.GetMembersForUserWithPagination | p99 | 97ms | 92ms | -5ms | -5.15
| ThreadStore.GetTotalThreads | p99 | 97ms | 92ms | -5ms | -5.13
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 98ms | 93ms | -5ms | -5.08
| ThreadStore.GetTotalUnreadMentions | p99 | 99ms | 94ms | -5ms | -5.04
| ChannelStore.GetMemberCount | p99 | 219ms | 208ms | -11ms | -5.01
| SessionStore.Get | p99 | 220ms | 209ms | -11ms | -5.00
| ChannelStore.GetChannelUnread | p99 | 160ms | 152ms | -8ms | -4.99
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 249ms | 237ms | -12ms | -4.82
| PostStore.GetPostsSince | p99 | 221ms | 211ms | -10ms | -4.53
| ChannelStore.GetMemberLastViewedAt | p99 | 89ms | 85ms | -4ms | -4.48
| ChannelStore.GetMemberForPost | p99 | 201ms | 192ms | -9ms | -4.47
| PostStore.SearchPostsForUser | p99 | 2.427s | 2.32s | -107ms | -4.41
| ProductNoticesStore.View | p99 | 867ms | 829ms | -38ms | -4.38
| SystemStore.GetByName | p99 | 92ms | 88ms | -4ms | -4.37
| ThreadStore.MarkAsRead | p99 | 92ms | 88ms | -4ms | -4.35
| GroupStore.GetByName | p99 | 93ms | 89ms | -4ms | -4.30
| AuditStore.Save | p99 | 94ms | 90ms | -4ms | -4.27
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 95ms | 91ms | -4ms | -4.21
| PostStore.Update | p99 | 246ms | 236ms | -10ms | -4.07
| ThreadStore.MarkAllAsReadByChannels | p99 | 99ms | 95ms | -4ms | -4.05
| TeamStore.GetAllPage | p99 | 99ms | 95ms | -4ms | -4.04
| PostStore.Get | p99 | 248ms | 238ms | -10ms | -4.03
| DraftStore.GetDraftsForUser | p99 | 184ms | 177ms | -7ms | -3.80
| ThreadStore.GetThreadForUser | p99 | 216ms | 209ms | -7ms | -3.23
| StatusStore.UpdateLastActivityAt | p99 | 93ms | 90ms | -3ms | -3.23
| FileInfoStore.SetContent | p99 | 226ms | 219ms | -7ms | -3.09
| ChannelStore.UpdateLastViewedAt | p99 | 97ms | 94ms | -3ms | -3.08
| PropertyFieldStore.SearchPropertyFields | p99 | 98ms | 95ms | -3ms | -3.08
| ChannelStore.IncrementMentionCount | p99 | 99ms | 96ms | -3ms | -3.04
| TeamStore.SaveMember | p99 | 234ms | 227ms | -7ms | -2.99
| ChannelStore.Autocomplete | p99 | 241ms | 234ms | -7ms | -2.91
| ChannelStore.GetPublicChannelsForTeam | p99 | 173ms | 168ms | -5ms | -2.88
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 70ms | 68ms | -2ms | -2.85
| UserStore.Count | p99 | 180ms | 175ms | -5ms | -2.78
| ThreadStore.MaintainMembership | p99 | 228ms | 222ms | -6ms | -2.63
| PostStore.GetPostIdBeforeTime | p99 | 98ms | 96ms | -2ms | -2.03
| UserStore.Search | p99 | 237ms | 233ms | -4ms | -1.69
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 0s | 5ms | 5ms | 5325.85
| updateChannelBookmarkSortOrder | avg | 7ms | 51ms | 44ms | 638.47
| updateChannelBookmark | avg | 24ms | 49ms | 25ms | 106.22
| createCategoryForTeamForUser | avg | 77ms | 147ms | 70ms | 91.03
| getServerLimits | avg | 32ms | 40ms | 8ms | 25.28
| autocompleteChannelsForTeamForSearch | avg | 46ms | 53ms | 7ms | 15.32
| updateCategoriesForTeamForUser | avg | 136ms | 155ms | 19ms | 13.99
| createChannel | avg | 413ms | 467ms | 54ms | 13.07
| createGroupChannel | avg | 716ms | 778ms | 62ms | 8.65
| followThreadByUser | avg | 46ms | 49ms | 3ms | 6.55
| unfollowThreadByUser | avg | 54ms | 57ms | 3ms | 5.55
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmarkSortOrder | p99 | 24ms | 246ms | 222ms | 931.46
| updateChannelBookmark | p99 | 50ms | 241ms | 191ms | 385.50
| createCategoryForTeamForUser | p99 | 480ms | 955ms | 475ms | 98.96
| createSchedulePost | p99 | 165ms | 203ms | 38ms | 23.00
| setPostReminder | p99 | 365ms | 407ms | 42ms | 11.51
| createChannel | p99 | 2.065s | 2.29s | 225ms | 10.90
| followThreadByUser | p99 | 367ms | 403ms | 36ms | 9.80
| getTeamMember | p99 | 140ms | 152ms | 12ms | 8.58
| getChannel | p99 | 242ms | 259ms | 17ms | 7.02
| getPublicChannelsForTeam | p99 | 173ms | 185ms | 12ms | 6.92
| getJobsByType | p99 | 206ms | 215ms | 9ms | 4.37
| getChannelUnread | p99 | 182ms | 187ms | 5ms | 2.74
| unfollowThreadByUser | p99 | 456ms | 466ms | 10ms | 2.19
| logout | p99 | 740ms | 755ms | 15ms | 2.03
| createGroupChannel | p99 | 3.433s | 3.5s | 67ms | 1.95
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 2ms | 0s | -2ms | -125.62
| searchFilesInTeam | avg | 7ms | 0s | -7ms | -105.31
| getUsersByGroupChannelIds | avg | 3ms | 0s | -3ms | -101.49
| getPrevTrialLicense | avg | 20ms | 0s | -20ms | -100.03
| getGroupsAssociatedToChannelsByTeam | avg | 9ms | 0s | -9ms | -99.94
| getAnalytics | avg | 113ms | 0s | -113ms | -99.62
| channelMemberCountsByGroup | avg | 16ms | 0s | -16ms | -99.47
| createEmoji | avg | 6ms | 0s | -6ms | -97.26
| getGroups | avg | 5ms | 0s | -5ms | -92.61
| updateReadStateAllThreadsByUser | avg | 14ms | 3ms | -11ms | -77.90
| getChannelMembers | avg | 26ms | 8ms | -18ms | -68.90
| getFilteredUsersStats | avg | 68ms | 24ms | -44ms | -64.46
| createChannelBookmark | avg | 61ms | 24ms | -37ms | -60.53
| getJobsByType | avg | 23ms | 13ms | -10ms | -44.30
| createDirectChannel | avg | 532ms | 408ms | -124ms | -23.29
| getPreferences | avg | 10ms | 8ms | -2ms | -20.82
| listCPAValues | avg | 14ms | 12ms | -2ms | -14.77
| getUsersByNames | avg | 14ms | 12ms | -2ms | -14.55
| getChannelsForTeamForUser | avg | 14ms | 12ms | -2ms | -14.51
| getTeamScheduledPosts | avg | 14ms | 12ms | -2ms | -14.06
| addChannelMember | avg | 473ms | 409ms | -64ms | -13.54
| setPostReminder | avg | 59ms | 51ms | -8ms | -13.50
| getCategoriesForTeamForUser | avg | 15ms | 13ms | -2ms | -13.49
| deletePost | avg | 127ms | 110ms | -17ms | -13.37
| getUser | avg | 15ms | 13ms | -2ms | -13.32
| deleteDraft | avg | 16ms | 14ms | -2ms | -12.84
| getTeamsUnreadForUser | avg | 16ms | 14ms | -2ms | -12.52
| removeUserCustomStatus | avg | 349ms | 306ms | -43ms | -12.32
| searchGroupChannels | avg | 16ms | 14ms | -2ms | -12.16
| getPostThread | avg | 62ms | 55ms | -7ms | -11.27
| viewChannel | avg | 47ms | 42ms | -5ms | -10.69
| deleteChannelBookmark | avg | 47ms | 42ms | -5ms | -10.61
| login | avg | 190ms | 171ms | -19ms | -10.02
| getChannelMember | avg | 20ms | 18ms | -2ms | -9.95
| getTeamStats | avg | 82ms | 74ms | -8ms | -9.74
| getPostsForChannelAroundLastUnread | avg | 43ms | 39ms | -4ms | -9.41
| getClientConfig | avg | 23ms | 21ms | -2ms | -8.74
| getPostsForChannel | avg | 103ms | 94ms | -9ms | -8.70
| getChannel | avg | 24ms | 22ms | -2ms | -8.41
| saveReaction | avg | 37ms | 34ms | -3ms | -8.15
| addTeamMember | avg | 1.252s | 1.158s | -94ms | -7.51
| updatePreferences | avg | 41ms | 38ms | -3ms | -7.27
| updateReadStateThreadByUser | avg | 131ms | 123ms | -8ms | -6.13
| createUser | avg | 380ms | 360ms | -20ms | -5.26
| getFileThumbnail | avg | 58ms | 55ms | -3ms | -5.18
| autocompleteUsers | avg | 65ms | 62ms | -3ms | -4.59
| getFilePreview | avg | 67ms | 64ms | -3ms | -4.49
| logout | avg | 119ms | 114ms | -5ms | -4.21
| searchPostsInTeam | avg | 196ms | 188ms | -8ms | -4.08
| createPost | avg | 636ms | 612ms | -24ms | -3.77
| handleCheckCWSConnection | avg | 71ms | 69ms | -2ms | -2.84
| getProfileImage | avg | 71ms | 69ms | -2ms | -2.80
| uploadFileStream | avg | 518ms | 508ms | -10ms | -1.93
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -101.01
| getGroups | p99 | 24ms | 0s | -24ms | -100.84
| searchFilesInTeam | p99 | 10ms | 0s | -10ms | -100.50
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| getPrevTrialLicense | p99 | 97ms | 0s | -97ms | -100.00
| getAnalytics | p99 | 247ms | 0s | -247ms | -100.00
| channelMemberCountsByGroup | p99 | 170ms | 0s | -170ms | -99.71
| getGroupsAssociatedToChannelsByTeam | p99 | 24ms | 0s | -24ms | -98.36
| createChannelBookmark | p99 | 795ms | 50ms | -745ms | -93.71
| updateReadStateAllThreadsByUser | p99 | 49ms | 5ms | -44ms | -89.80
| getFilteredUsersStats | p99 | 245ms | 50ms | -195ms | -79.43
| getServerLimits | p99 | 235ms | 50ms | -185ms | -78.72
| getChannelMembers | p99 | 98ms | 48ms | -50ms | -50.89
| deleteChannelBookmark | p99 | 99ms | 50ms | -49ms | -49.48
| getPreferences | p99 | 150ms | 99ms | -51ms | -34.00
| getTeamMembersForUser | p99 | 148ms | 99ms | -49ms | -33.09
| autocompleteChannelsForTeamForSearch | p99 | 391ms | 262ms | -129ms | -33.02
| getPostThread | p99 | 651ms | 479ms | -172ms | -26.42
| getPostsForChannel | p99 | 1.313s | 987ms | -326ms | -24.84
| login | p99 | 1.664s | 1.343s | -321ms | -19.29
| updateCategoriesForTeamForUser | p99 | 1.06s | 872ms | -188ms | -17.74
| getUserStatusesByIds | p99 | 83ms | 69ms | -14ms | -16.96
| saveReaction | p99 | 405ms | 341ms | -64ms | -15.81
| searchGroupChannels | p99 | 210ms | 177ms | -33ms | -15.71
| listChannelBookmarksForChannel | p99 | 165ms | 140ms | -25ms | -15.19
| addTeamMember | p99 | 8.082s | 6.968s | -1.114s | -13.78
| getFileThumbnail | p99 | 365ms | 316ms | -49ms | -13.43
| listCPAValues | p99 | 195ms | 169ms | -26ms | -13.33
| getChannelMembersForTeamForUser | p99 | 184ms | 160ms | -24ms | -13.02
| getChannelsForTeamForUser | p99 | 196ms | 172ms | -24ms | -12.26
| autocompleteUsers | p99 | 348ms | 307ms | -41ms | -11.78
| createDirectChannel | p99 | 2.454s | 2.171s | -283ms | -11.53
| getAllTeams | p99 | 150ms | 134ms | -16ms | -10.68
| getChannelStats | p99 | 133ms | 119ms | -14ms | -10.56
| getUsersByNames | p99 | 191ms | 172ms | -19ms | -9.95
| getTeamScheduledPosts | p99 | 213ms | 192ms | -21ms | -9.87
| getThreadsForUser | p99 | 202ms | 183ms | -19ms | -9.39
| getCategoriesForTeamForUser | p99 | 210ms | 192ms | -18ms | -8.57
| deleteDraft | p99 | 212ms | 194ms | -18ms | -8.48
| getFilePreview | p99 | 401ms | 368ms | -33ms | -8.23
| getUsers | p99 | 232ms | 213ms | -19ms | -8.19
| listCPAFields | p99 | 137ms | 126ms | -11ms | -8.01
| getTeamsForUser | p99 | 103ms | 95ms | -8ms | -7.78
| getChannelMember | p99 | 238ms | 220ms | -18ms | -7.57
| viewChannel | p99 | 475ms | 443ms | -32ms | -6.74
| getTeamsUnreadForUser | p99 | 225ms | 210ms | -15ms | -6.68
| createPost | p99 | 4.277s | 3.993s | -284ms | -6.64
| getUsersByIds | p99 | 48ms | 45ms | -3ms | -6.28
| deletePost | p99 | 920ms | 865ms | -55ms | -5.98
| updateReadStateThreadByUser | p99 | 953ms | 897ms | -56ms | -5.88
| getPostsForChannelAroundLastUnread | p99 | 450ms | 426ms | -24ms | -5.33
| getChannelsForUser | p99 | 97ms | 92ms | -5ms | -5.17
| getChannelMembersForUser | p99 | 99ms | 94ms | -5ms | -5.05
| upsertDraft | p99 | 215ms | 205ms | -10ms | -4.66
| getUser | p99 | 237ms | 226ms | -11ms | -4.64
| addChannelMember | p99 | 2.473s | 2.362s | -111ms | -4.49
| removeUserCustomStatus | p99 | 2.001s | 1.915s | -86ms | -4.30
| searchPostsInTeam | p99 | 2.431s | 2.341s | -90ms | -3.70
| createUser | p99 | 2.197s | 2.135s | -62ms | -2.82
| getClientConfig | p99 | 237ms | 231ms | -6ms | -2.53
| searchAllChannels | p99 | 243ms | 238ms | -5ms | -2.06
| searchUsers | p99 | 240ms | 236ms | -4ms | -1.67
| patchPost | p99 | 888ms | 874ms | -14ms | -1.58
| getProfileImage | p99 | 466ms | 459ms | -7ms | -1.50
| uploadFileStream | p99 | 2.155s | 2.126s | -29ms | -1.35
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 10ms| 9ms | -1ms | -10.064
| |  P99| 94ms| 90ms | -4ms | -4.274
| BotStore.Get |  Avg| 6ms| 8ms | 2ms | 31.720
| |  P99| 83ms| 85ms | 2ms | 2.424
| ChannelBookmarkStore.Delete |  Avg| 18ms| 9ms | -9ms | -49.561
| |  P99| 95ms| 24ms | -71ms | -75.132
| ChannelBookmarkStore.Get |  Avg| 6ms| 4ms | -2ms | -32.698
| |  P99| 86ms| 45ms | -41ms | -47.674
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 9ms| 8ms | -1ms | -11.091
| |  P99| 129ms| 100ms | -29ms | -22.423
| ChannelBookmarkStore.Save |  Avg| 45ms| 20ms | -25ms | -55.347
| |  P99| 437ms| 217ms | -220ms | -50.286
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 5ms| 7ms | 2ms | 41.361
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 70ms| 68ms | -2ms | -2.854
| ChannelStore.AnalyticsCountAll |  Avg| 23ms| 21ms | -2ms | -8.604
| |  P99| 49ms| 25ms | -24ms | -49.454
| ChannelStore.Autocomplete |  Avg| 48ms| 47ms | -1ms | -2.076
| |  P99| 241ms| 234ms | -7ms | -2.910
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 45ms| 53ms | 8ms | 17.623
| |  P99| 391ms| 262ms | -129ms | -33.020
| ChannelStore.CreateDirectChannel |  Avg| 74ms| 61ms | -13ms | -17.450
| |  P99| 623ms| 471ms | -152ms | -24.399
| ChannelStore.CreateInitialSidebarCategories |  Avg| 40ms| 36ms | -4ms | -10.005
| |  P99| 376ms| 319ms | -57ms | -15.162
| ChannelStore.CreateSidebarCategory |  Avg| 68ms| 111ms | 43ms | 62.822
| |  P99| 480ms| 489ms | 9ms | 1.875
| ChannelStore.Get |  Avg| 20ms| 17ms | -3ms | -15.232
| |  P99| 231ms| 208ms | -23ms | -9.968
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 12ms | -1ms | -7.926
| |  P99| 157ms| 134ms | -23ms | -14.664
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 22ms| 20ms | -2ms | -9.194
| |  P99| 249ms| 237ms | -12ms | -4.824
| ChannelStore.GetByName |  Avg| 11ms| 10ms | -1ms | -9.180
| |  P99| 124ms| 97ms | -27ms | -21.778
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 0s | -1ms | -88.440
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 160ms| 152ms | -8ms | -4.991
| ChannelStore.GetChannels |  Avg| 13ms| 12ms | -1ms | -7.450
| |  P99| 191ms| 164ms | -27ms | -14.131
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 4ms | 3ms | 238.755
| |  P99| 5ms| 24ms | 19ms | 382.901
| ChannelStore.GetChannelsByUser |  Avg| 8ms| 7ms | -1ms | -13.146
| |  P99| 95ms| 90ms | -5ms | -5.248
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 9ms | -1ms | -10.026
| |  P99| 146ms| 109ms | -37ms | -25.368
| ChannelStore.GetFileCount |  Avg| 12ms| 11ms | -1ms | -8.652
| |  P99| 137ms| 110ms | -27ms | -19.739
| ChannelStore.GetGuestCount |  Avg| 10ms| 9ms | -1ms | -9.656
| |  P99| 145ms| 99ms | -46ms | -31.747
| ChannelStore.GetMember |  Avg| 10ms| 9ms | -1ms | -10.288
| |  P99| 99ms| 93ms | -6ms | -6.061
| ChannelStore.GetMemberCount |  Avg| 33ms| 31ms | -2ms | -6.062
| |  P99| 219ms| 208ms | -11ms | -5.014
| ChannelStore.GetMemberCountsByGroup |  Avg| 12ms| 0s | -12ms | -99.556
| |  P99| 93ms| 0s | -93ms | -99.732
| ChannelStore.GetMemberForPost |  Avg| 17ms| 16ms | -1ms | -6.004
| |  P99| 201ms| 192ms | -9ms | -4.472
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 89ms| 85ms | -4ms | -4.480
| ChannelStore.GetMembers |  Avg| 21ms| 8ms | -13ms | -60.883
| |  P99| 98ms| 48ms | -50ms | -50.890
| ChannelStore.GetMembersForUser |  Avg| 13ms| 11ms | -2ms | -15.462
| |  P99| 179ms| 152ms | -27ms | -15.068
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 16ms| 3ms | -13ms | -79.251
| |  P99| 216ms| 5ms | -211ms | -97.574
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 8ms | -1ms | -11.760
| |  P99| 97ms| 92ms | -5ms | -5.149
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 137ms| 103ms | -34ms | -24.834
| ChannelStore.GetPublicChannelsForTeam |  Avg| 26ms| 25ms | -1ms | -3.882
| |  P99| 173ms| 168ms | -5ms | -2.884
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 14ms| 12ms | -2ms | -14.447
| |  P99| 201ms| 180ms | -21ms | -10.423
| ChannelStore.GetSidebarCategory |  Avg| 18ms| 22ms | 4ms | 21.682
| |  P99| 179ms| 237ms | 58ms | 32.447
| ChannelStore.GetTeamChannels |  Avg| 33ms| 37ms | 4ms | 12.074
| |  P99| 98ms| 236ms | 138ms | 141.418
| ChannelStore.IncrementMentionCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 96ms | -3ms | -3.041
| ChannelStore.Save |  Avg| 36ms| 40ms | 4ms | 11.062
| |  P99| 249ms| 365ms | 116ms | 46.653
| ChannelStore.SaveMember |  Avg| 59ms| 54ms | -5ms | -8.417
| |  P99| 484ms| 448ms | -36ms | -7.442
| ChannelStore.SearchGroupChannels |  Avg| 16ms| 14ms | -2ms | -12.360
| |  P99| 207ms| 167ms | -40ms | -19.287
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 97ms| 94ms | -3ms | -3.080
| ChannelStore.UpdateSidebarCategories |  Avg| 93ms| 107ms | 14ms | 15.035
| |  P99| 1.06s| 615ms | -445ms | -41.984
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 91ms | -4ms | -4.214
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 14ms| 17ms | 3ms | 21.522
| |  P99| 160ms| 202ms | 42ms | 26.332
| CommandWebhookStore.Cleanup |  Avg| 21ms| 9ms | -12ms | -57.512
| |  P99| 241ms| 25ms | -216ms | -89.627
| ComplianceStore.MessageExport |  Avg| 6ms| 344ms | 338ms | 5948.679
| |  P99| 10ms| 985ms | 975ms | 9796.971
| DesktopTokensStore.DeleteOlderThan |  Avg| 7ms| 0s | -7ms | -103.335
| |  P99| 10ms| 0s | -10ms | -100.503
| DraftStore.Delete |  Avg| 13ms| 12ms | -1ms | -7.761
| |  P99| 147ms| 112ms | -35ms | -23.822
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 23ms| 16ms | -7ms | -30.709
| |  P99| 202ms| 95ms | -107ms | -52.972
| DraftStore.Get |  Avg| 15ms| 13ms | -2ms | -13.718
| |  P99| 204ms| 181ms | -23ms | -11.290
| DraftStore.GetDraftsForUser |  Avg| 14ms| 13ms | -1ms | -7.049
| |  P99| 184ms| 177ms | -7ms | -3.796
| DraftStore.Upsert |  Avg| 15ms| 14ms | -1ms | -6.868
| |  P99| 165ms| 147ms | -18ms | -10.876
| EmojiStore.GetByName |  Avg| 9ms| 8ms | -1ms | -11.122
| |  P99| 130ms| 95ms | -35ms | -26.949
| EmojiStore.GetMultipleByName |  Avg| 11ms| 2ms | -9ms | -83.620
| |  P99| 49ms| 24ms | -25ms | -51.414
| FileInfoStore.AttachToPost |  Avg| 19ms| 18ms | -1ms | -5.230
| |  P99| 202ms| 189ms | -13ms | -6.434
| FileInfoStore.Get |  Avg| 11ms| 10ms | -1ms | -8.744
| |  P99| 176ms| 150ms | -26ms | -14.804
| FileInfoStore.GetByIds |  Avg| 11ms| 10ms | -1ms | -9.212
| |  P99| 176ms| 178ms | 2ms | 1.139
| FileInfoStore.GetForPost |  Avg| 11ms| 9ms | -2ms | -18.861
| |  P99| 182ms| 133ms | -49ms | -26.867
| FileInfoStore.Save |  Avg| 16ms| 15ms | -1ms | -6.443
| |  P99| 160ms| 172ms | 12ms | 7.517
| FileInfoStore.Search |  Avg| 4ms| 0s | -4ms | -94.438
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.SetContent |  Avg| 24ms| 23ms | -1ms | -4.209
| |  P99| 226ms| 219ms | -7ms | -3.094
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 5ms | -1ms | -17.647
| |  P99| 88ms| 74ms | -14ms | -15.926
| GroupStore.GetByName |  Avg| 7ms| 6ms | -1ms | -14.216
| |  P99| 93ms| 89ms | -4ms | -4.297
| GroupStore.GetGroups |  Avg| 9ms| 8ms | -1ms | -10.734
| |  P99| 121ms| 96ms | -25ms | -20.705
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 7ms| 4ms | -3ms | -40.684
| |  P99| 24ms| 5ms | -19ms | -78.350
| JobStore.GetAllByStatus |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 203ms| 203ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 22ms| 13ms | -9ms | -41.420
| |  P99| 206ms| 215ms | 9ms | 4.374
| JobStore.GetCountByStatusAndType |  Avg| 7ms| 10ms | 3ms | 40.337
| |  P99| 98ms| 121ms | 23ms | 23.590
| JobStore.GetNewestJobByStatusesAndType |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 74ms| 79ms | 5ms | 6.745
| JobStore.Save |  Avg| 9ms| 8ms | -1ms | -11.710
| |  P99| 76ms| 47ms | -29ms | -38.158
| JobStore.UpdateOptimistically |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 104ms| 91ms | -13ms | -12.441
| JobStore.UpdateStatus |  Avg| 9ms| 7ms | -2ms | -21.117
| |  P99| 107ms| 58ms | -49ms | -45.585
| JobStore.UpdateStatusOptimistically |  Avg| 12ms| 8ms | -4ms | -33.898
| |  P99| 107ms| 79ms | -28ms | -26.049
| LicenseStore.GetAll |  Avg| 17ms| 1ms | -16ms | -93.065
| |  P99| 95ms| 5ms | -90ms | -94.241
| LinkMetadataStore.Get |  Avg| 8ms| 7ms | -1ms | -12.211
| |  P99| 122ms| 96ms | -26ms | -21.338
| LinkMetadataStore.Save |  Avg| 10ms| 14ms | 4ms | 40.035
| |  P99| 166ms| 180ms | 14ms | 8.434
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 6ms | -1ms | -14.664
| |  P99| 112ms| 70ms | -42ms | -37.335
| PostAcknowledgementStore.GetForPosts |  Avg| 12ms| 11ms | -1ms | -8.228
| |  P99| 206ms| 184ms | -22ms | -10.685
| PostPersistentNotificationStore.DeleteExpired |  Avg| 8ms| 4ms | -4ms | -53.182
| |  P99| 71ms| 37ms | -34ms | -47.894
| PostPersistentNotificationStore.Get |  Avg| 10ms| 6ms | -4ms | -40.799
| |  P99| 90ms| 71ms | -19ms | -21.112
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 6ms | -1ms | -14.992
| |  P99| 96ms| 88ms | -8ms | -8.343
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 3ms | -1ms | -28.428
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 7ms| 6ms | -1ms | -14.332
| |  P99| 95ms| 82ms | -13ms | -13.635
| PostPriorityStore.GetForPosts |  Avg| 13ms| 11ms | -2ms | -15.389
| |  P99| 211ms| 189ms | -22ms | -10.436
| PostStore.AnalyticsPostCount |  Avg| 200ms| 195ms | -5ms | -2.500
| |  P99| 496ms| 496ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 3ms| 8ms | 5ms | 152.793
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Delete |  Avg| 85ms| 67ms | -18ms | -21.301
| |  P99| 840ms| 466ms | -374ms | -44.525
| PostStore.Get |  Avg| 27ms| 25ms | -2ms | -7.278
| |  P99| 248ms| 238ms | -10ms | -4.032
| PostStore.GetEtag |  Avg| 12ms| 11ms | -1ms | -8.195
| |  P99| 182ms| 151ms | -31ms | -17.069
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 68ms | -7ms | -9.320
| PostStore.GetPostIdBeforeTime |  Avg| 10ms| 9ms | -1ms | -10.298
| |  P99| 98ms| 96ms | -2ms | -2.032
| PostStore.GetPostReminderMetadata |  Avg| 8ms| 10ms | 2ms | 24.343
| |  P99| 99ms| 142ms | 43ms | 43.361
| PostStore.GetPostReminders |  Avg| 19ms| 20ms | 1ms | 5.306
| |  P99| 196ms| 96ms | -100ms | -51.020
| PostStore.GetPosts |  Avg| 7ms| 6ms | -1ms | -14.525
| |  P99| 85ms| 79ms | -6ms | -7.097
| PostStore.GetPostsAfter |  Avg| 10ms| 8ms | -2ms | -20.405
| |  P99| 145ms| 93ms | -52ms | -35.839
| PostStore.GetPostsBefore |  Avg| 14ms| 13ms | -1ms | -7.300
| |  P99| 183ms| 163ms | -20ms | -10.940
| PostStore.GetPostsByIds |  Avg| 1ms| 11ms | 10ms | 1076.806
| |  P99| 5ms| 49ms | 44ms | 888.889
| PostStore.GetPostsByThread |  Avg| 16ms| 15ms | -1ms | -6.319
| |  P99| 140ms| 108ms | -32ms | -22.780
| PostStore.GetPostsSince |  Avg| 26ms| 24ms | -2ms | -7.786
| |  P99| 221ms| 211ms | -10ms | -4.533
| PostStore.GetSingle |  Avg| 8ms| 7ms | -1ms | -12.769
| |  P99| 108ms| 93ms | -15ms | -13.833
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 39ms| 36ms | -3ms | -7.756
| |  P99| 366ms| 331ms | -35ms | -9.566
| PostStore.SearchPostsForUser |  Avg| 173ms| 168ms | -5ms | -2.883
| |  P99| 2.427s| 2.32s | -107ms | -4.408
| PostStore.SetPostReminder |  Avg| 25ms| 17ms | -8ms | -32.172
| |  P99| 169ms| 91ms | -78ms | -46.155
| PostStore.Update |  Avg| 38ms| 34ms | -4ms | -10.542
| |  P99| 246ms| 236ms | -10ms | -4.067
| PreferenceStore.DeleteCategoryAndName |  Avg| 17ms| 12ms | -5ms | -28.605
| |  P99| 202ms| 93ms | -109ms | -53.962
| PreferenceStore.Get |  Avg| 12ms| 11ms | -1ms | -8.466
| |  P99| 174ms| 151ms | -23ms | -13.187
| PreferenceStore.GetAll |  Avg| 9ms| 8ms | -1ms | -10.875
| |  P99| 139ms| 96ms | -43ms | -31.043
| PreferenceStore.Save |  Avg| 30ms| 28ms | -2ms | -6.624
| |  P99| 248ms| 248ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 71ms| 39ms | -32ms | -45.210
| |  P99| 99ms| 50ms | -49ms | -49.495
| ProductNoticesStore.GetViews |  Avg| 1ms| 45ms | 44ms | 3728.894
| |  P99| 5ms| 50ms | 45ms | 908.953
| ProductNoticesStore.View |  Avg| 107ms| 102ms | -5ms | -4.673
| |  P99| 867ms| 829ms | -38ms | -4.384
| PropertyFieldStore.SearchPropertyFields |  Avg| 8ms| 7ms | -1ms | -13.022
| |  P99| 98ms| 95ms | -3ms | -3.077
| PropertyValueStore.SearchPropertyValues |  Avg| 12ms| 11ms | -1ms | -8.275
| |  P99| 174ms| 147ms | -27ms | -15.483
| ReactionStore.GetForPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 89ms | -6ms | -6.338
| RetentionPolicyStore.GetAll |  Avg| 8ms| 0s | -8ms | -99.136
| |  P99| 10ms| 0s | -10ms | -100.503
| RetentionPolicyStore.GetCount |  Avg| 8ms| 0s | -8ms | -105.647
| |  P99| 10ms| 0s | -10ms | -100.503
| RoleStore.ChannelHigherScopedPermissions |  Avg| 14ms| 11ms | -3ms | -21.176
| |  P99| 177ms| 82ms | -95ms | -53.672
| RoleStore.GetByNames |  Avg| 44ms| 17ms | -27ms | -61.123
| |  P99| 242ms| 99ms | -143ms | -59.197
| ScheduledPostStore.CreateScheduledPost |  Avg| 14ms| 11ms | -3ms | -21.715
| |  P99| 99ms| 84ms | -15ms | -15.164
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 8ms| 14ms | 6ms | 75.238
| |  P99| 196ms| 203ms | 7ms | 3.571
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 7ms| 6ms | -1ms | -14.536
| |  P99| 95ms| 87ms | -8ms | -8.457
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 4ms| 9ms | 5ms | 125.929
| |  P99| 23ms| 84ms | 61ms | 262.931
| SchemeStore.GetAllPage |  Avg| 57ms| 18ms | -39ms | -68.154
| |  P99| 100ms| 25ms | -75ms | -75.377
| SessionStore.Get |  Avg| 18ms| 16ms | -2ms | -11.102
| |  P99| 220ms| 209ms | -11ms | -5.004
| SessionStore.GetLRUSessions |  Avg| 6ms| 5ms | -1ms | -16.191
| |  P99| 87ms| 82ms | -5ms | -5.779
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 9ms | -14ms | -61.137
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 7ms | -1ms | -13.233
| |  P99| 106ms| 98ms | -8ms | -7.520
| SessionStore.Remove |  Avg| 13ms| 12ms | -1ms | -7.553
| |  P99| 211ms| 92ms | -119ms | -56.398
| SessionStore.Save |  Avg| 14ms| 13ms | -1ms | -6.962
| |  P99| 174ms| 155ms | -19ms | -10.922
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 88ms | -5ms | -5.358
| StatusStore.Get |  Avg| 10ms| 8ms | -2ms | -20.626
| |  P99| 154ms| 110ms | -44ms | -28.561
| StatusStore.GetByIds |  Avg| 17ms| 14ms | -3ms | -17.900
| |  P99| 211ms| 196ms | -15ms | -7.097
| StatusStore.SaveOrUpdate |  Avg| 13ms| 12ms | -1ms | -7.827
| |  P99| 135ms| 121ms | -14ms | -10.379
| StatusStore.SaveOrUpdateMany |  Avg| 19ms| 16ms | -3ms | -15.855
| |  P99| 214ms| 197ms | -17ms | -7.940
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 160ms| 130ms | -30ms | -18.809
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 9ms | -1ms | -10.266
| |  P99| 93ms| 90ms | -3ms | -3.228
| SystemStore.GetByName |  Avg| 8ms| 7ms | -1ms | -12.869
| |  P99| 92ms| 88ms | -4ms | -4.367
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 22ms | 16ms | 247.361
| |  P99| 49ms| 25ms | -24ms | -49.483
| TeamStore.Get |  Avg| 7ms| 6ms | -1ms | -13.845
| |  P99| 99ms| 90ms | -9ms | -9.126
| TeamStore.GetActiveMemberCount |  Avg| 73ms| 63ms | -10ms | -13.711
| |  P99| 241ms| 240ms | -1ms | -0.414
| TeamStore.GetAllPage |  Avg| 8ms| 7ms | -1ms | -12.760
| |  P99| 99ms| 95ms | -4ms | -4.040
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 7ms | -1ms | -12.135
| |  P99| 105ms| 95ms | -10ms | -9.519
| TeamStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 7ms| 6ms | -1ms | -14.434
| |  P99| 86ms| 79ms | -7ms | -8.109
| TeamStore.GetTeamsByUserId |  Avg| 8ms| 7ms | -1ms | -13.129
| |  P99| 99ms| 93ms | -6ms | -6.062
| TeamStore.GetTeamsForUser |  Avg| 8ms| 7ms | -1ms | -12.691
| |  P99| 100ms| 91ms | -9ms | -9.010
| TeamStore.GetTotalMemberCount |  Avg| 69ms| 63ms | -6ms | -8.699
| |  P99| 427ms| 240ms | -187ms | -43.743
| TeamStore.SaveMember |  Avg| 38ms| 36ms | -2ms | -5.285
| |  P99| 234ms| 227ms | -7ms | -2.987
| ThreadStore.Get |  Avg| 9ms| 7ms | -2ms | -23.031
| |  P99| 97ms| 86ms | -11ms | -11.304
| ThreadStore.GetMembershipForUser |  Avg| 10ms| 9ms | -1ms | -10.465
| |  P99| 148ms| 121ms | -27ms | -18.295
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 10ms | -1ms | -8.975
| |  P99| 173ms| 143ms | -30ms | -17.364
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 7ms | -1ms | -13.195
| |  P99| 97ms| 91ms | -6ms | -6.217
| ThreadStore.GetThreadForUser |  Avg| 17ms| 16ms | -1ms | -5.819
| |  P99| 216ms| 209ms | -7ms | -3.234
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 19ms| 18ms | -1ms | -5.271
| |  P99| 172ms| 159ms | -13ms | -7.560
| ThreadStore.GetThreadsForUser |  Avg| 15ms| 14ms | -1ms | -6.685
| |  P99| 192ms| 171ms | -21ms | -10.932
| ThreadStore.GetTotalThreads |  Avg| 8ms| 7ms | -1ms | -12.530
| |  P99| 97ms| 92ms | -5ms | -5.129
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 7ms | -1ms | -12.651
| |  P99| 99ms| 94ms | -5ms | -5.045
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 7ms | -1ms | -12.637
| |  P99| 98ms| 91ms | -7ms | -7.144
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 7ms | -1ms | -12.063
| |  P99| 98ms| 93ms | -5ms | -5.083
| ThreadStore.MaintainMembership |  Avg| 21ms| 20ms | -1ms | -4.769
| |  P99| 228ms| 222ms | -6ms | -2.627
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 95ms | -4ms | -4.047
| ThreadStore.MarkAllAsReadByTeam |  Avg| 14ms| 3ms | -11ms | -78.366
| |  P99| 49ms| 5ms | -44ms | -89.796
| ThreadStore.MarkAsRead |  Avg| 10ms| 9ms | -1ms | -10.150
| |  P99| 92ms| 88ms | -4ms | -4.352
| ThreadStore.UpdateMembership |  Avg| 10ms| 9ms | -1ms | -10.386
| |  P99| 92ms| 87ms | -5ms | -5.417
| TokenStore.Cleanup |  Avg| 11ms| 5ms | -6ms | -54.543
| |  P99| 48ms| 10ms | -38ms | -78.351
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 5ms | -3ms | -38.275
| |  P99| 170ms| 46ms | -124ms | -72.729
| UserStore.AnalyticsActiveCount |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 97ms| 50ms | -47ms | -48.579
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 18ms| 30ms | 12ms | 67.273
| |  P99| 49ms| 50ms | 1ms | 2.030
| UserStore.AutocompleteUsersInChannel |  Avg| 71ms| 67ms | -4ms | -5.664
| |  P99| 338ms| 295ms | -43ms | -12.732
| UserStore.Count |  Avg| 23ms| 22ms | -1ms | -4.428
| |  P99| 180ms| 175ms | -5ms | -2.777
| UserStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 147ms| 119ms | -28ms | -19.030
| UserStore.GetAllProfiles |  Avg| 7ms| 6ms | -1ms | -14.217
| |  P99| 86ms| 75ms | -11ms | -12.746
| UserStore.GetAllProfilesInChannel |  Avg| 334ms| 318ms | -16ms | -4.784
| |  P99| 1.931s| 1.749s | -182ms | -9.426
| UserStore.GetByUsername |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 127ms| 94ms | -33ms | -25.985
| UserStore.GetForLogin |  Avg| 8ms| 7ms | -1ms | -12.960
| |  P99| 98ms| 91ms | -7ms | -7.150
| UserStore.GetMany |  Avg| 14ms| 9ms | -5ms | -35.293
| |  P99| 93ms| 99ms | 6ms | 6.463
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 5ms| 4ms | -1ms | -21.410
| |  P99| 10ms| 5ms | -5ms | -50.742
| UserStore.GetProfileByIds |  Avg| 13ms| 11ms | -2ms | -15.705
| |  P99| 180ms| 154ms | -26ms | -14.453
| UserStore.GetProfilesByUsernames |  Avg| 13ms| 12ms | -1ms | -7.607
| |  P99| 183ms| 161ms | -22ms | -12.030
| UserStore.GetProfilesInChannel |  Avg| 15ms| 19ms | 4ms | 25.923
| |  P99| 202ms| 224ms | 22ms | 10.891
| UserStore.GetProfilesNotInChannel |  Avg| 19ms| 11ms | -8ms | -42.451
| |  P99| 95ms| 209ms | 114ms | 119.790
| UserStore.GetUnreadCount |  Avg| 8ms| 7ms | -1ms | -12.425
| |  P99| 128ms| 98ms | -30ms | -23.456
| UserStore.IsEmpty |  Avg| 4ms| 3ms | -1ms | -28.444
| |  P99| 48ms| 45ms | -3ms | -6.314
| UserStore.Save |  Avg| 166ms| 160ms | -6ms | -3.619
| |  P99| 500ms| 499ms | -1ms | -0.200
| UserStore.Search |  Avg| 47ms| 46ms | -1ms | -2.121
| |  P99| 237ms| 233ms | -4ms | -1.685
| UserStore.Update |  Avg| 31ms| 29ms | -2ms | -6.534
| |  P99| 305ms| 236ms | -69ms | -22.624
| UserStore.UpdateFailedPasswordAttempts |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 95ms| 90ms | -5ms | -5.290
| UserStore.UpdateLastLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 79ms| 71ms | -8ms | -10.079
| UserStore.UpdateUpdateAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 80ms| 73ms | -7ms | -8.732
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 6ms | -1ms | -14.195
| |  P99| 96ms| 91ms | -5ms | -5.187
| WebhookStore.GetOutgoingByTeam |  Avg| 15ms| 13ms | -2ms | -13.770
| |  P99| 201ms| 185ms | -16ms | -7.961
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 473ms| 409ms | -64ms | -13.543
| | P99| 2.473s| 2.362s | -111ms | -4.489
| addTeamMember | Avg| 1.252s| 1.158s | -94ms | -7.506
| | P99| 8.082s| 6.968s | -1.114s | -13.785
| autocompleteChannelsForTeamForSearch | Avg| 46ms| 53ms | 7ms | 15.322
| | P99| 391ms| 262ms | -129ms | -33.020
| autocompleteUsers | Avg| 65ms| 62ms | -3ms | -4.585
| | P99| 348ms| 307ms | -41ms | -11.778
| channelMemberCountsByGroup | Avg| 16ms| 0s | -16ms | -99.472
| | P99| 170ms| 0s | -170ms | -99.710
| createCategoryForTeamForUser | Avg| 77ms| 147ms | 70ms | 91.027
| | P99| 480ms| 955ms | 475ms | 98.958
| createChannel | Avg| 413ms| 467ms | 54ms | 13.065
| | P99| 2.065s| 2.29s | 225ms | 10.896
| createChannelBookmark | Avg| 61ms| 24ms | -37ms | -60.532
| | P99| 795ms| 50ms | -745ms | -93.714
| createDirectChannel | Avg| 532ms| 408ms | -124ms | -23.288
| | P99| 2.454s| 2.171s | -283ms | -11.533
| createEmoji | Avg| 6ms| 0s | -6ms | -97.262
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 716ms| 778ms | 62ms | 8.654
| | P99| 3.433s| 3.5s | 67ms | 1.952
| createPost | Avg| 636ms| 612ms | -24ms | -3.773
| | P99| 4.277s| 3.993s | -284ms | -6.640
| createSchedulePost | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 165ms| 203ms | 38ms | 22.996
| createUser | Avg| 380ms| 360ms | -20ms | -5.260
| | P99| 2.197s| 2.135s | -62ms | -2.822
| deleteChannelBookmark | Avg| 47ms| 42ms | -5ms | -10.609
| | P99| 99ms| 50ms | -49ms | -49.480
| deleteDraft | Avg| 16ms| 14ms | -2ms | -12.843
| | P99| 212ms| 194ms | -18ms | -8.480
| deletePost | Avg| 127ms| 110ms | -17ms | -13.374
| | P99| 920ms| 865ms | -55ms | -5.978
| followThreadByUser | Avg| 46ms| 49ms | 3ms | 6.550
| | P99| 367ms| 403ms | 36ms | 9.796
| getAllTeams | Avg| 9ms| 8ms | -1ms | -10.552
| | P99| 150ms| 134ms | -16ms | -10.681
| getAnalytics | Avg| 113ms| 0s | -113ms | -99.616
| | P99| 247ms| 0s | -247ms | -100.000
| getCategoriesForTeamForUser | Avg| 15ms| 13ms | -2ms | -13.488
| | P99| 210ms| 192ms | -18ms | -8.566
| getChannel | Avg| 24ms| 22ms | -2ms | -8.411
| | P99| 242ms| 259ms | 17ms | 7.019
| getChannelMember | Avg| 20ms| 18ms | -2ms | -9.948
| | P99| 238ms| 220ms | -18ms | -7.568
| getChannelMembers | Avg| 26ms| 8ms | -18ms | -68.895
| | P99| 98ms| 48ms | -50ms | -50.890
| getChannelMembersForTeamForUser | Avg| 13ms| 12ms | -1ms | -7.549
| | P99| 184ms| 160ms | -24ms | -13.024
| getChannelMembersForUser | Avg| 9ms| 8ms | -1ms | -11.378
| | P99| 99ms| 94ms | -5ms | -5.047
| getChannelStats | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 133ms| 119ms | -14ms | -10.565
| getChannelUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 182ms| 187ms | 5ms | 2.741
| getChannelsForTeamForUser | Avg| 14ms| 12ms | -2ms | -14.507
| | P99| 196ms| 172ms | -24ms | -12.258
| getChannelsForUser | Avg| 8ms| 7ms | -1ms | -12.710
| | P99| 97ms| 92ms | -5ms | -5.174
| getClientConfig | Avg| 23ms| 21ms | -2ms | -8.737
| | P99| 237ms| 231ms | -6ms | -2.535
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 15ms| 14ms | -1ms | -6.603
| | P99| 194ms| 193ms | -1ms | -0.514
| getFilePreview | Avg| 67ms| 64ms | -3ms | -4.493
| | P99| 401ms| 368ms | -33ms | -8.232
| getFileThumbnail | Avg| 58ms| 55ms | -3ms | -5.184
| | P99| 365ms| 316ms | -49ms | -13.431
| getFilteredUsersStats | Avg| 68ms| 24ms | -44ms | -64.458
| | P99| 245ms| 50ms | -195ms | -79.430
| getGroups | Avg| 5ms| 0s | -5ms | -92.610
| | P99| 24ms| 0s | -24ms | -100.840
| getGroupsAssociatedToChannelsByTeam | Avg| 9ms| 0s | -9ms | -99.938
| | P99| 24ms| 0s | -24ms | -98.361
| getJobsByType | Avg| 23ms| 13ms | -10ms | -44.297
| | P99| 206ms| 215ms | 9ms | 4.374
| getPostThread | Avg| 62ms| 55ms | -7ms | -11.267
| | P99| 651ms| 479ms | -172ms | -26.420
| getPostsForChannel | Avg| 103ms| 94ms | -9ms | -8.702
| | P99| 1.313s| 987ms | -326ms | -24.838
| getPostsForChannelAroundLastUnread | Avg| 43ms| 39ms | -4ms | -9.409
| | P99| 450ms| 426ms | -24ms | -5.334
| getPreferences | Avg| 10ms| 8ms | -2ms | -20.821
| | P99| 150ms| 99ms | -51ms | -33.997
| getPrevTrialLicense | Avg| 20ms| 0s | -20ms | -100.030
| | P99| 97ms| 0s | -97ms | -100.000
| getProductNotices | Avg| 2ms| 0s | -2ms | -125.624
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 71ms| 69ms | -2ms | -2.801
| | P99| 466ms| 459ms | -7ms | -1.502
| getPublicChannelsForTeam | Avg| 27ms| 26ms | -1ms | -3.691
| | P99| 173ms| 185ms | 12ms | 6.922
| getRolesByNames | Avg| 0s| 5ms | 5ms | 5325.854
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 32ms| 40ms | 8ms | 25.278
| | P99| 235ms| 50ms | -185ms | -78.724
| getTeamMember | Avg| 12ms| 11ms | -1ms | -8.174
| | P99| 140ms| 152ms | 12ms | 8.575
| getTeamMembersForUser | Avg| 9ms| 8ms | -1ms | -10.927
| | P99| 148ms| 99ms | -49ms | -33.091
| getTeamScheduledPosts | Avg| 14ms| 12ms | -2ms | -14.055
| | P99| 213ms| 192ms | -21ms | -9.868
| getTeamStats | Avg| 82ms| 74ms | -8ms | -9.740
| | P99| 427ms| 430ms | 3ms | 0.702
| getTeamsForUser | Avg| 8ms| 7ms | -1ms | -12.778
| | P99| 103ms| 95ms | -8ms | -7.777
| getTeamsUnreadForUser | Avg| 16ms| 14ms | -2ms | -12.519
| | P99| 225ms| 210ms | -15ms | -6.675
| getThreadsForUser | Avg| 15ms| 14ms | -1ms | -6.595
| | P99| 202ms| 183ms | -19ms | -9.394
| getUser | Avg| 15ms| 13ms | -2ms | -13.316
| | P99| 237ms| 226ms | -11ms | -4.641
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 83ms| 69ms | -14ms | -16.957
| getUsers | Avg| 14ms| 13ms | -1ms | -6.948
| | P99| 232ms| 213ms | -19ms | -8.190
| getUsersByGroupChannelIds | Avg| 3ms| 0s | -3ms | -101.493
| | P99| 5ms| 0s | -5ms | -101.010
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 48ms| 45ms | -3ms | -6.282
| getUsersByNames | Avg| 14ms| 12ms | -2ms | -14.546
| | P99| 191ms| 172ms | -19ms | -9.950
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 71ms| 69ms | -2ms | -2.835
| | P99| 99ms| 100ms | 1ms | 1.005
| listCPAFields | Avg| 9ms| 8ms | -1ms | -11.058
| | P99| 137ms| 126ms | -11ms | -8.012
| listCPAValues | Avg| 14ms| 12ms | -2ms | -14.772
| | P99| 195ms| 169ms | -26ms | -13.332
| listChannelBookmarksForChannel | Avg| 10ms| 9ms | -1ms | -9.768
| | P99| 165ms| 140ms | -25ms | -15.191
| login | Avg| 190ms| 171ms | -19ms | -10.022
| | P99| 1.664s| 1.343s | -321ms | -19.289
| logout | Avg| 119ms| 114ms | -5ms | -4.206
| | P99| 740ms| 755ms | 15ms | 2.027
| patchPost | Avg| 102ms| 101ms | -1ms | -0.982
| | P99| 888ms| 874ms | -14ms | -1.577
| removeUserCustomStatus | Avg| 349ms| 306ms | -43ms | -12.324
| | P99| 2.001s| 1.915s | -86ms | -4.299
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 37ms| 34ms | -3ms | -8.148
| | P99| 405ms| 341ms | -64ms | -15.814
| searchAllChannels | Avg| 49ms| 48ms | -1ms | -2.035
| | P99| 243ms| 238ms | -5ms | -2.059
| searchFilesInTeam | Avg| 7ms| 0s | -7ms | -105.314
| | P99| 10ms| 0s | -10ms | -100.503
| searchGroupChannels | Avg| 16ms| 14ms | -2ms | -12.158
| | P99| 210ms| 177ms | -33ms | -15.714
| searchPostsInTeam | Avg| 196ms| 188ms | -8ms | -4.084
| | P99| 2.431s| 2.341s | -90ms | -3.703
| searchUsers | Avg| 49ms| 48ms | -1ms | -2.034
| | P99| 240ms| 236ms | -4ms | -1.668
| setPostReminder | Avg| 59ms| 51ms | -8ms | -13.504
| | P99| 365ms| 407ms | 42ms | 11.507
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 54ms| 57ms | 3ms | 5.550
| | P99| 456ms| 466ms | 10ms | 2.193
| updateCategoriesForTeamForUser | Avg| 136ms| 155ms | 19ms | 13.989
| | P99| 1.06s| 872ms | -188ms | -17.737
| updateChannelBookmark | Avg| 24ms| 49ms | 25ms | 106.222
| | P99| 50ms| 241ms | 191ms | 385.499
| updateChannelBookmarkSortOrder | Avg| 7ms| 51ms | 44ms | 638.467
| | P99| 24ms| 246ms | 222ms | 931.462
| updatePreferences | Avg| 41ms| 38ms | -3ms | -7.269
| | P99| 388ms| 385ms | -3ms | -0.773
| updateReadStateAllThreadsByUser | Avg| 14ms| 3ms | -11ms | -77.898
| | P99| 49ms| 5ms | -44ms | -89.796
| updateReadStateThreadByUser | Avg| 131ms| 123ms | -8ms | -6.127
| | P99| 953ms| 897ms | -56ms | -5.876
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -118.262
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 518ms| 508ms | -10ms | -1.930
| | P99| 2.155s| 2.126s | -29ms | -1.346
| upsertDraft | Avg| 18ms| 17ms | -1ms | -5.406
| | P99| 215ms| 205ms | -10ms | -4.656
| viewChannel | Avg| 47ms| 42ms | -5ms | -10.689
| | P99| 475ms| 443ms | -32ms | -6.743

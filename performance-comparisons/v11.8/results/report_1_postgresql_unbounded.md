### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 6ms | 530ms | 524ms | 8343.53
| PostStore.AnalyticsPostCountByTeam | avg | 2ms | 7ms | 5ms | 313.11
| PostStore.SearchPostsForUser | avg | 72ms | 253ms | 181ms | 253.11
| TeamStore.AnalyticsTeamCount | avg | 2ms | 8ms | 6ms | 252.57
| LicenseStore.GetAll | avg | 4ms | 14ms | 10ms | 251.00
| ChannelStore.GetMemberForPost | avg | 16ms | 35ms | 19ms | 115.97
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 11ms | 18ms | 7ms | 64.74
| TemporaryPostStore.GetExpiredPosts | avg | 5ms | 8ms | 3ms | 63.31
| ChannelStore.AnalyticsCountAll | avg | 23ms | 37ms | 14ms | 61.34
| RoleStore.GetByNames | avg | 17ms | 27ms | 10ms | 57.38
| JobStore.GetAllByTypePage | avg | 13ms | 20ms | 7ms | 52.35
| UserStore.AnalyticsActiveCount | avg | 25ms | 38ms | 13ms | 52.01
| PostStore.AnalyticsPostCount | avg | 171ms | 259ms | 88ms | 51.42
| TeamStore.GetActiveMemberCount | avg | 55ms | 80ms | 25ms | 45.21
| TeamStore.GetTotalMemberCount | avg | 61ms | 87ms | 26ms | 42.78
| ChannelBookmarkStore.Get | avg | 10ms | 14ms | 4ms | 39.78
| ChannelStore.AutocompleteInTeamForSearch | avg | 74ms | 102ms | 28ms | 37.87
| ChannelStore.GetTeamChannels | avg | 30ms | 41ms | 11ms | 37.17
| ChannelBookmarkStore.Delete | avg | 27ms | 37ms | 10ms | 36.37
| ChannelStore.GetMany | avg | 17ms | 22ms | 5ms | 29.91
| UserStore.GetProfilesInChannel | avg | 7ms | 9ms | 2ms | 29.11
| ProductNoticesStore.ClearOldNotices | avg | 33ms | 41ms | 8ms | 24.45
| StatusStore.UpdateExpiredDNDStatuses | avg | 9ms | 11ms | 2ms | 21.62
| PreferenceStore.DeleteCategoryAndName | avg | 9ms | 11ms | 2ms | 21.29
| UserStore.GetProfilesNotInChannel | avg | 13ms | 15ms | 2ms | 15.17
| FileInfoStore.SetContent | avg | 17ms | 19ms | 2ms | 11.99
| ChannelStore.Save | avg | 35ms | 39ms | 4ms | 11.57
| ProductNoticesStore.View | avg | 70ms | 78ms | 8ms | 11.48
| ChannelStore.CreateInitialSidebarCategories | avg | 26ms | 29ms | 3ms | 11.41
| UserStore.GetAllProfilesInChannel | avg | 297ms | 330ms | 33ms | 11.12
| ChannelStore.SaveMember | avg | 54ms | 58ms | 4ms | 7.40
| UserStore.Save | avg | 150ms | 152ms | 2ms | 1.33
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 10ms | 993ms | 983ms | 9875.12
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 49ms | 44ms | 888.21
| PostStore.AnalyticsPostCountByTeam | p99 | 5ms | 25ms | 20ms | 403.73
| ChannelStore.AutocompleteInTeamForSearch | p99 | 347ms | 1.634s | 1.287s | 370.37
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 47ms | 203ms | 156ms | 331.04
| TeamStore.GetActiveMemberCount | p99 | 99ms | 243ms | 144ms | 145.21
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 10ms | 24ms | 14ms | 143.59
| ChannelStore.CreateSidebarCategory | p99 | 99ms | 232ms | 133ms | 134.34
| ChannelStore.GetTeamChannels | p99 | 97ms | 223ms | 126ms | 130.34
| JobStore.GetAllByTypePage | p99 | 96ms | 206ms | 110ms | 114.73
| LicenseStore.GetAll | p99 | 24ms | 49ms | 25ms | 102.46
| UserStore.GetProfilesInChannel | p99 | 45ms | 90ms | 45ms | 100.00
| ChannelBookmarkStore.Get | p99 | 47ms | 93ms | 46ms | 97.87
| UserStore.AnalyticsActiveCount | p99 | 50ms | 97ms | 47ms | 94.95
| SessionStore.GetSessionsExpired | p99 | 24ms | 47ms | 23ms | 94.55
| ChannelStore.UpdateSidebarCategories | p99 | 470ms | 660ms | 190ms | 40.42
| ThreadStore.Get | p99 | 58ms | 80ms | 22ms | 37.93
| PostStore.SearchPostsForUser | p99 | 1.86s | 2.422s | 562ms | 30.21
| FileInfoStore.SetContent | p99 | 151ms | 184ms | 33ms | 21.85
| UserStore.GetAllProfilesInChannel | p99 | 1.346s | 1.602s | 256ms | 19.03
| ChannelStore.Save | p99 | 241ms | 278ms | 37ms | 15.34
| ProductNoticesStore.View | p99 | 580ms | 664ms | 84ms | 14.48
| UserStore.UpdateUpdateAt | p99 | 53ms | 59ms | 6ms | 11.35
| TeamStore.GetTotalMemberCount | p99 | 220ms | 243ms | 23ms | 10.45
| UserAccessTokenStore.GetByToken | p99 | 43ms | 47ms | 4ms | 9.20
| UserStore.UpdateLastLogin | p99 | 53ms | 57ms | 4ms | 7.51
| PostStore.Update | p99 | 214ms | 224ms | 10ms | 4.68
| ChannelStore.SaveMember | p99 | 396ms | 413ms | 17ms | 4.30
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 48ms | 50ms | 2ms | 4.19
| ChannelStore.GetMemberForPost | p99 | 179ms | 186ms | 7ms | 3.91
| TeamStore.SaveMember | p99 | 228ms | 232ms | 4ms | 1.75
| ChannelStore.CreateInitialSidebarCategories | p99 | 241ms | 244ms | 3ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -114.99
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -103.25
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 21ms | 0s | -21ms | -101.72
| EmojiStore.Search | avg | 10ms | 0s | -10ms | -99.52
| ChannelStore.GetMemberCountsByGroup | avg | 29ms | 0s | -29ms | -98.55
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 9ms | 0s | -9ms | -96.23
| ThreadStore.MarkAllAsReadByTeam | avg | 45ms | 6ms | -39ms | -86.67
| TokenStore.Cleanup | avg | 10ms | 2ms | -8ms | -80.54
| TeamStore.GetMany | avg | 28ms | 6ms | -22ms | -77.47
| ChannelStore.GetMembers | avg | 9ms | 3ms | -6ms | -66.14
| ChannelStore.GetChannelsByIds | avg | 25ms | 9ms | -16ms | -65.13
| CommandWebhookStore.Cleanup | avg | 10ms | 4ms | -6ms | -61.08
| JobStore.GetCountByStatusAndType | avg | 20ms | 9ms | -11ms | -54.11
| ScheduledPostStore.GetPendingScheduledPosts | avg | 24ms | 11ms | -13ms | -53.52
| UserStore.AnalyticsGetInactiveUsersCount | avg | 6ms | 3ms | -3ms | -53.39
| LinkMetadataStore.Save | avg | 9ms | 5ms | -4ms | -43.75
| SessionStore.Remove | avg | 10ms | 6ms | -4ms | -39.13
| PostStore.GetPostsByIds | avg | 10ms | 6ms | -4ms | -38.80
| ChannelStore.GetSidebarCategory | avg | 31ms | 20ms | -11ms | -35.98
| ChannelStore.CreateSidebarCategory | avg | 40ms | 26ms | -14ms | -35.35
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 14ms | 9ms | -5ms | -35.18
| PostPersistentNotificationStore.DeleteExpired | avg | 9ms | 6ms | -3ms | -34.87
| UserStore.GetMany | avg | 12ms | 8ms | -4ms | -33.82
| EmojiStore.GetMultipleByName | avg | 13ms | 9ms | -4ms | -30.87
| JobStore.UpdateStatusOptimistically | avg | 10ms | 7ms | -3ms | -30.31
| PostStore.GetPostReminderMetadata | avg | 17ms | 12ms | -5ms | -29.45
| JobStore.Save | avg | 11ms | 8ms | -3ms | -27.78
| PostPersistentNotificationStore.Get | avg | 7ms | 5ms | -2ms | -27.78
| JobStore.GetNewestJobByStatusesAndType | avg | 11ms | 8ms | -3ms | -27.42
| FileInfoStore.GetForPost | avg | 7ms | 5ms | -2ms | -26.75
| PreferenceStore.Get | avg | 12ms | 9ms | -3ms | -25.77
| JobStore.UpdateStatus | avg | 8ms | 6ms | -2ms | -24.91
| ThreadStore.GetThreadUnreadReplyCount | avg | 21ms | 16ms | -5ms | -23.38
| RoleStore.ChannelHigherScopedPermissions | avg | 9ms | 7ms | -2ms | -23.23
| PostStore.GetPostsByThread | avg | 18ms | 14ms | -4ms | -22.47
| UserStore.GetByUsername | avg | 14ms | 11ms | -3ms | -22.16
| ClusterDiscoveryStore.SetLastPingAt | avg | 14ms | 11ms | -3ms | -21.86
| BotStore.Get | avg | 15ms | 12ms | -3ms | -19.91
| StatusStore.GetByIds | avg | 15ms | 12ms | -3ms | -19.53
| FileInfoStore.GetByIds | avg | 10ms | 8ms | -2ms | -19.52
| PropertyValueStore.SearchPropertyValues | avg | 11ms | 9ms | -2ms | -18.78
| ChannelStore.Get | avg | 17ms | 14ms | -3ms | -18.16
| ChannelStore.CreateDirectChannel | avg | 83ms | 68ms | -15ms | -17.97
| PostStore.Delete | avg | 61ms | 51ms | -10ms | -16.26
| ChannelStore.GetChannels | avg | 13ms | 11ms | -2ms | -15.95
| StatusStore.SaveOrUpdateMany | avg | 19ms | 16ms | -3ms | -15.71
| PostStore.Get | avg | 26ms | 22ms | -4ms | -15.43
| UserStore.GetProfilesByUsernames | avg | 13ms | 11ms | -2ms | -15.25
| JobStore.GetAllByStatus | avg | 14ms | 12ms | -2ms | -14.76
| DraftStore.Get | avg | 14ms | 12ms | -2ms | -14.21
| UserStore.Update | avg | 21ms | 18ms | -3ms | -14.07
| DraftStore.GetDraftsForUser | avg | 14ms | 12ms | -2ms | -13.91
| ChannelStore.SearchGroupChannels | avg | 15ms | 13ms | -2ms | -13.67
| ThreadStore.GetThreadsForUser | avg | 15ms | 13ms | -2ms | -13.58
| ThreadStore.GetThreadForUser | avg | 18ms | 16ms | -2ms | -11.17
| ChannelStore.GetPublicChannelsForTeam | avg | 26ms | 24ms | -2ms | -7.58
| PostStore.Update | avg | 27ms | 25ms | -2ms | -7.31
| ChannelStore.Autocomplete | avg | 51ms | 49ms | -2ms | -3.96
| ChannelStore.UpdateSidebarCategories | avg | 99ms | 96ms | -3ms | -3.02
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 50ms | 0s | -50ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.00
| EmojiStore.Search | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.GetMemberCountsByGroup | p99 | 221ms | 0s | -221ms | -100.11
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 24ms | 0s | -24ms | -98.97
| ThreadStore.MarkAllAsReadByTeam | p99 | 244ms | 24ms | -220ms | -90.16
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 435ms | 48ms | -387ms | -88.97
| TokenStore.Cleanup | p99 | 49ms | 10ms | -39ms | -79.59
| CommandWebhookStore.Cleanup | p99 | 49ms | 10ms | -39ms | -79.59
| JobStore.GetCountByStatusAndType | p99 | 421ms | 90ms | -331ms | -78.65
| ChannelStore.GetMembers | p99 | 24ms | 5ms | -19ms | -77.81
| PostStore.GetPostReminderMetadata | p99 | 337ms | 79ms | -258ms | -76.45
| TeamStore.GetMany | p99 | 99ms | 24ms | -75ms | -76.14
| EmojiStore.GetMultipleByName | p99 | 96ms | 24ms | -72ms | -74.61
| ChannelStore.GetChannelsByIds | p99 | 97ms | 25ms | -72ms | -74.23
| LinkMetadataStore.Save | p99 | 94ms | 37ms | -57ms | -60.64
| BotStore.Get | p99 | 212ms | 85ms | -127ms | -59.76
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 211ms | 85ms | -126ms | -59.72
| PostPersistentNotificationStore.Get | p99 | 178ms | 72ms | -106ms | -59.55
| UserStore.GetProfilesNotInChannel | p99 | 222ms | 91ms | -131ms | -59.14
| ChannelStore.GetSidebarCategory | p99 | 227ms | 99ms | -128ms | -56.51
| PostPersistentNotificationStore.DeleteExpired | p99 | 187ms | 87ms | -100ms | -53.48
| SessionStore.Remove | p99 | 96ms | 45ms | -51ms | -53.40
| PostStore.Delete | p99 | 885ms | 423ms | -462ms | -52.20
| PostStore.GetPostsByIds | p99 | 49ms | 24ms | -25ms | -51.28
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 10ms | 5ms | -5ms | -50.50
| UserStore.GetByUsername | p99 | 183ms | 94ms | -89ms | -48.53
| JobStore.UpdateStatus | p99 | 87ms | 45ms | -42ms | -48.18
| DraftStore.Get | p99 | 189ms | 99ms | -90ms | -47.69
| DraftStore.GetDraftsForUser | p99 | 185ms | 98ms | -87ms | -46.90
| StatusStore.GetByIds | p99 | 200ms | 107ms | -93ms | -46.59
| PreferenceStore.DeleteCategoryAndName | p99 | 88ms | 48ms | -40ms | -45.20
| JobStore.UpdateOptimistically | p99 | 128ms | 70ms | -58ms | -45.14
| PostStore.GetPostReminders | p99 | 87ms | 48ms | -39ms | -44.83
| ThreadStore.GetThreadsForUser | p99 | 178ms | 98ms | -80ms | -44.83
| ChannelStore.GetForPost | p99 | 187ms | 105ms | -82ms | -43.84
| ThreadStore.GetThreadUnreadReplyCount | p99 | 173ms | 98ms | -75ms | -43.48
| UserStore.GetProfilesByUsernames | p99 | 164ms | 97ms | -67ms | -40.88
| ChannelStore.GetChannels | p99 | 161ms | 96ms | -65ms | -40.45
| PreferenceStore.Get | p99 | 149ms | 89ms | -60ms | -40.30
| ChannelStore.GetChannelUnread | p99 | 155ms | 93ms | -62ms | -40.00
| ScheduledPostStore.CreateScheduledPost | p99 | 152ms | 92ms | -60ms | -39.35
| PostStore.GetPostsBefore | p99 | 159ms | 97ms | -62ms | -39.08
| FileInfoStore.Save | p99 | 152ms | 93ms | -59ms | -38.78
| FileInfoStore.Get | p99 | 155ms | 95ms | -60ms | -38.76
| ChannelStore.GetMembersForUser | p99 | 154ms | 95ms | -59ms | -38.41
| JobStore.GetAllByStatus | p99 | 203ms | 126ms | -77ms | -37.99
| JobStore.UpdateStatusOptimistically | p99 | 134ms | 84ms | -50ms | -37.18
| ChannelStore.Get | p99 | 209ms | 132ms | -77ms | -36.93
| WebhookStore.GetOutgoingByTeam | p99 | 180ms | 114ms | -66ms | -36.74
| ChannelStore.SearchGroupChannels | p99 | 178ms | 113ms | -65ms | -36.60
| ChannelStore.CreateDirectChannel | p99 | 762ms | 491ms | -271ms | -35.54
| DraftStore.Upsert | p99 | 143ms | 93ms | -50ms | -34.97
| PostStore.GetEtag | p99 | 146ms | 96ms | -50ms | -34.14
| PostStore.GetPostsAfter | p99 | 125ms | 83ms | -42ms | -33.60
| FileInfoStore.GetForPost | p99 | 85ms | 57ms | -28ms | -33.04
| UserStore.GetProfileByIds | p99 | 143ms | 96ms | -47ms | -32.77
| PropertyValueStore.SearchPropertyValues | p99 | 127ms | 89ms | -38ms | -29.97
| ChannelStore.GetPublicChannelsForTeam | p99 | 183ms | 129ms | -54ms | -29.51
| PostStore.GetPostsByThread | p99 | 128ms | 93ms | -35ms | -27.38
| StatusStore.SaveOrUpdateMany | p99 | 222ms | 163ms | -59ms | -26.55
| RoleStore.ChannelHigherScopedPermissions | p99 | 72ms | 53ms | -19ms | -26.39
| ThreadStore.GetMembershipForUser | p99 | 120ms | 90ms | -30ms | -24.98
| RoleStore.GetByNames | p99 | 234ms | 177ms | -57ms | -24.33
| UserStore.AutocompleteUsersInChannel | p99 | 336ms | 256ms | -80ms | -23.79
| ChannelStore.GetAllChannelMembersForUser | p99 | 122ms | 93ms | -29ms | -23.70
| ClusterDiscoveryStore.SetLastPingAt | p99 | 117ms | 93ms | -24ms | -20.51
| ThreadStore.GetTeamsUnreadForUser | p99 | 122ms | 98ms | -24ms | -19.64
| UserStore.GetAllProfiles | p99 | 62ms | 50ms | -12ms | -19.32
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 174ms | 141ms | -33ms | -19.01
| ThreadStore.GetThreadForUser | p99 | 202ms | 164ms | -38ms | -18.82
| UserStore.GetMany | p99 | 91ms | 74ms | -17ms | -18.66
| UserStore.Update | p99 | 226ms | 185ms | -41ms | -18.14
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 102ms | 86ms | -16ms | -15.66
| FileInfoStore.GetByIds | p99 | 104ms | 88ms | -16ms | -15.42
| JobStore.GetNewestJobByStatusesAndType | p99 | 119ms | 101ms | -18ms | -15.16
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 99ms | 85ms | -14ms | -14.17
| StatusStore.SaveOrUpdate | p99 | 104ms | 90ms | -14ms | -13.50
| ChannelStore.UpdateLastViewedAt | p99 | 91ms | 79ms | -12ms | -13.23
| PostPriorityStore.GetForPostWithContext | p99 | 91ms | 79ms | -12ms | -13.22
| ThreadStore.GetTotalUnreadMentions | p99 | 95ms | 83ms | -12ms | -12.68
| ChannelStore.GetPinnedPostCount | p99 | 110ms | 96ms | -14ms | -12.67
| PostPersistentNotificationStore.GetSingle | p99 | 88ms | 77ms | -11ms | -12.52
| LinkMetadataStore.Get | p99 | 97ms | 85ms | -12ms | -12.38
| PostAcknowledgementStore.GetForPost | p99 | 89ms | 78ms | -11ms | -12.31
| UserStore.GetUnreadCount | p99 | 98ms | 86ms | -12ms | -12.24
| ChannelStore.IncrementMentionCount | p99 | 90ms | 79ms | -11ms | -12.23
| ThreadStore.GetThreadFollowers | p99 | 91ms | 80ms | -11ms | -12.14
| DraftStore.Delete | p99 | 99ms | 87ms | -12ms | -12.11
| UserStore.UpdateFailedPasswordAttempts | p99 | 84ms | 74ms | -10ms | -11.94
| PostStore.GetSingle | p99 | 94ms | 83ms | -11ms | -11.68
| PostStore.Save | p99 | 277ms | 246ms | -31ms | -11.21
| TeamStore.GetTeamsByUserId | p99 | 90ms | 80ms | -10ms | -11.17
| UserStore.Count | p99 | 136ms | 121ms | -15ms | -11.05
| TeamStore.Get | p99 | 90ms | 80ms | -10ms | -11.05
| UserStore.Get | p99 | 100ms | 89ms | -11ms | -11.04
| ChannelStore.GetMemberLastViewedAt | p99 | 83ms | 74ms | -9ms | -10.83
| ThreadStore.MarkAsRead | p99 | 87ms | 78ms | -9ms | -10.38
| SessionStore.Get | p99 | 185ms | 166ms | -19ms | -10.28
| PostStore.GetPosts | p99 | 78ms | 70ms | -8ms | -10.24
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 99ms | 89ms | -10ms | -10.15
| ChannelStore.GetChannelsByUser | p99 | 89ms | 80ms | -9ms | -10.13
| EmojiStore.GetByName | p99 | 99ms | 89ms | -10ms | -10.07
| PostStore.GetPostsSince | p99 | 211ms | 190ms | -21ms | -9.95
| ThreadStore.GetTotalThreads | p99 | 91ms | 82ms | -9ms | -9.92
| ThreadStore.MaintainMembership | p99 | 212ms | 191ms | -21ms | -9.92
| ThreadStore.MarkAllAsReadByChannels | p99 | 92ms | 83ms | -9ms | -9.79
| PreferenceStore.GetAll | p99 | 95ms | 86ms | -9ms | -9.45
| ReactionStore.GetForPost | p99 | 98ms | 89ms | -9ms | -9.21
| PostStore.Get | p99 | 239ms | 217ms | -22ms | -9.21
| ChannelStore.GetFileCount | p99 | 98ms | 89ms | -9ms | -9.18
| PostPriorityStore.GetForPosts | p99 | 188ms | 171ms | -17ms | -9.06
| FileInfoStore.AttachToPost | p99 | 177ms | 161ms | -16ms | -9.03
| ChannelStore.GetMember | p99 | 89ms | 81ms | -8ms | -9.00
| ThreadStore.GetTotalUnreadThreads | p99 | 90ms | 82ms | -8ms | -8.90
| ChannelStore.GetMembersForUserWithPagination | p99 | 90ms | 82ms | -8ms | -8.87
| TeamStore.GetMember | p99 | 68ms | 62ms | -6ms | -8.86
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 91ms | 83ms | -8ms | -8.79
| PropertyGroupStore.Get | p99 | 91ms | 83ms | -8ms | -8.75
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 92ms | 84ms | -8ms | -8.69
| AuditStore.Save | p99 | 81ms | 74ms | -7ms | -8.66
| ChannelStore.GetMemberCount | p99 | 198ms | 181ms | -17ms | -8.57
| SessionStore.UpdateLastActivityAt | p99 | 83ms | 76ms | -7ms | -8.38
| PostAcknowledgementStore.GetForPosts | p99 | 180ms | 165ms | -15ms | -8.34
| ThreadStore.UpdateMembership | p99 | 84ms | 77ms | -7ms | -8.32
| TeamStore.GetTeamsForUser | p99 | 88ms | 81ms | -7ms | -7.99
| SystemStore.GetByName | p99 | 77ms | 71ms | -6ms | -7.78
| PostStore.GetPostIdBeforeTime | p99 | 80ms | 74ms | -6ms | -7.47
| GroupStore.GetGroups | p99 | 95ms | 88ms | -7ms | -7.38
| StatusStore.Get | p99 | 95ms | 88ms | -7ms | -7.36
| UserTermsOfServiceStore.GetByUser | p99 | 83ms | 77ms | -6ms | -7.19
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 85ms | 79ms | -6ms | -7.03
| PropertyFieldStore.SearchPropertyFields | p99 | 79ms | 74ms | -5ms | -6.34
| ChannelStore.Autocomplete | p99 | 250ms | 235ms | -15ms | -6.00
| TeamStore.GetAllPage | p99 | 88ms | 83ms | -5ms | -5.70
| ChannelStore.GetByName | p99 | 93ms | 88ms | -5ms | -5.39
| JobStore.Save | p99 | 80ms | 76ms | -4ms | -4.98
| UserStore.Search | p99 | 234ms | 223ms | -11ms | -4.71
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 235ms | 224ms | -11ms | -4.68
| PostStore.GetPostIdAfterTime | p99 | 51ms | 49ms | -2ms | -3.91
| UserStore.GetForLogin | p99 | 84ms | 81ms | -3ms | -3.58
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 85ms | 82ms | -3ms | -3.52
| ChannelBookmarkStore.Delete | p99 | 241ms | 233ms | -8ms | -3.32
| ChannelStore.GetGuestCount | p99 | 94ms | 91ms | -3ms | -3.19
| PostStore.SetPostReminder | p99 | 225ms | 219ms | -6ms | -2.67
| StatusStore.UpdateLastActivityAt | p99 | 83ms | 81ms | -2ms | -2.42
| PreferenceStore.Save | p99 | 228ms | 224ms | -4ms | -1.76
| ChannelStore.GetMany | p99 | 375ms | 370ms | -5ms | -1.33
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 5ms | 29ms | 24ms | 495.92
| searchPostsInTeam | avg | 98ms | 278ms | 180ms | 184.08
| deleteChannelBookmark | avg | 40ms | 91ms | 51ms | 127.45
| getServerLimits | avg | 14ms | 23ms | 9ms | 66.24
| updateChannelBookmarkSortOrder | avg | 9ms | 14ms | 5ms | 58.57
| getFilteredUsersStats | avg | 13ms | 20ms | 7ms | 53.22
| getJobsByType | avg | 14ms | 21ms | 7ms | 50.48
| getAnalytics | avg | 57ms | 84ms | 27ms | 47.63
| saveReaction | avg | 38ms | 55ms | 17ms | 45.26
| getTeamStats | avg | 69ms | 95ms | 26ms | 37.95
| autocompleteChannelsForTeamForSearch | avg | 74ms | 102ms | 28ms | 37.83
| setPostReminder | avg | 71ms | 95ms | 24ms | 33.76
| viewChannel | avg | 42ms | 51ms | 9ms | 21.46
| addChannelMember | avg | 376ms | 427ms | 51ms | 13.58
| createGroupChannel | avg | 692ms | 775ms | 83ms | 12.00
| followThreadByUser | avg | 47ms | 52ms | 5ms | 10.53
| addTeamMember | avg | 1.07s | 1.163s | 93ms | 8.69
| createDirectChannel | avg | 416ms | 447ms | 31ms | 7.46
| createUser | avg | 318ms | 341ms | 23ms | 7.23
| removeUserCustomStatus | avg | 248ms | 265ms | 17ms | 6.86
| getPostsForChannelAroundLastUnread | avg | 43ms | 45ms | 2ms | 4.64
| getPostsForChannel | avg | 116ms | 120ms | 4ms | 3.45
| createPost | avg | 590ms | 601ms | 11ms | 1.86
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | p99 | 5ms | 50ms | 45ms | 909.09
| deleteChannelBookmark | p99 | 50ms | 247ms | 197ms | 395.87
| autocompleteChannelsForTeamForSearch | p99 | 347ms | 1.634s | 1.287s | 370.37
| setPostReminder | p99 | 472ms | 1.87s | 1.398s | 296.39
| getAnalytics | p99 | 100ms | 246ms | 146ms | 146.68
| createCategoryForTeamForUser | p99 | 99ms | 232ms | 133ms | 134.34
| getJobsByType | p99 | 96ms | 206ms | 110ms | 114.73
| getServerLimits | p99 | 25ms | 50ms | 25ms | 100.60
| logout | p99 | 483ms | 795ms | 312ms | 64.58
| searchPostsInTeam | p99 | 1.895s | 2.447s | 552ms | 29.13
| addChannelMember | p99 | 1.958s | 2.297s | 339ms | 17.31
| createUser | p99 | 1.723s | 1.887s | 164ms | 9.52
| addTeamMember | p99 | 4.804s | 5.219s | 415ms | 8.64
| getPostsForChannel | p99 | 1.149s | 1.205s | 56ms | 4.87
| getUsers | p99 | 186ms | 195ms | 9ms | 4.83
| getTeamStats | p99 | 235ms | 245ms | 10ms | 4.26
| viewChannel | p99 | 437ms | 449ms | 12ms | 2.75
| getPostsForChannelAroundLastUnread | p99 | 391ms | 401ms | 10ms | 2.56
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateUserCustomStatus | avg | 2ms | 0s | -2ms | -122.14
| channelMemberCountsByGroup | avg | 40ms | 0s | -40ms | -99.27
| autocompleteEmojis | avg | 10ms | 0s | -10ms | -99.12
| getUsersByGroupChannelIds | avg | 37ms | 0s | -37ms | -98.80
| updateReadStateAllThreadsByUser | avg | 45ms | 6ms | -39ms | -86.40
| getChannelMembers | avg | 13ms | 4ms | -9ms | -68.64
| updateChannelBookmark | avg | 214ms | 86ms | -128ms | -59.69
| deletePost | avg | 127ms | 83ms | -44ms | -34.70
| handleCheckCWSConnection | avg | 55ms | 37ms | -18ms | -32.89
| root | avg | 10ms | 7ms | -3ms | -30.62
| createSchedulePost | avg | 23ms | 16ms | -7ms | -29.93
| logout | avg | 142ms | 102ms | -40ms | -28.27
| createChannelBookmark | avg | 71ms | 53ms | -18ms | -25.35
| createCategoryForTeamForUser | avg | 43ms | 33ms | -10ms | -23.01
| deleteDraft | avg | 15ms | 12ms | -3ms | -20.18
| getDrafts | avg | 15ms | 12ms | -3ms | -20.01
| getChannelMembersForTeamForUser | avg | 13ms | 11ms | -2ms | -15.86
| getChannelsForTeamForUser | avg | 13ms | 11ms | -2ms | -15.62
| getUsersByNames | avg | 14ms | 12ms | -2ms | -14.66
| getThreadsForUser | avg | 15ms | 13ms | -2ms | -13.70
| getProfileImage | avg | 91ms | 79ms | -12ms | -13.18
| updateReadStateThreadByUser | avg | 133ms | 116ms | -17ms | -12.81
| upsertDraft | avg | 16ms | 14ms | -2ms | -12.54
| listCPAValues | avg | 24ms | 21ms | -3ms | -12.46
| updateCategoriesForTeamForUser | avg | 170ms | 149ms | -21ms | -12.33
| getPublicChannelsForTeam | avg | 28ms | 25ms | -3ms | -10.56
| patchPost | avg | 93ms | 84ms | -9ms | -9.64
| getPostThread | avg | 60ms | 55ms | -5ms | -8.36
| createChannel | avg | 448ms | 419ms | -29ms | -6.47
| updatePreferences | avg | 33ms | 31ms | -2ms | -6.02
| getFileThumbnail | avg | 67ms | 65ms | -2ms | -3.00
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 25ms | 0s | -25ms | -100.60
| getUsersByGroupChannelIds | p99 | 50ms | 0s | -50ms | -100.50
| channelMemberCountsByGroup | p99 | 238ms | 0s | -238ms | -99.87
| updateReadStateAllThreadsByUser | p99 | 244ms | 24ms | -220ms | -90.16
| getChannelMembers | p99 | 47ms | 5ms | -42ms | -89.34
| createSchedulePost | p99 | 675ms | 94ms | -581ms | -86.08
| getPrevTrialLicense | p99 | 25ms | 5ms | -20ms | -81.47
| createChannel | p99 | 2.2s | 978ms | -1.222s | -55.54
| updateChannelBookmark | p99 | 985ms | 475ms | -510ms | -51.78
| handleCheckCWSConnection | p99 | 100ms | 50ms | -50ms | -50.25
| createChannelBookmark | p99 | 473ms | 244ms | -229ms | -48.46
| getDrafts | p99 | 193ms | 100ms | -93ms | -48.09
| getChannelUnread | p99 | 182ms | 98ms | -84ms | -46.09
| unfollowThreadByUser | p99 | 615ms | 335ms | -280ms | -45.53
| getUsersByNames | p99 | 173ms | 99ms | -74ms | -42.79
| getChannelsForTeamForUser | p99 | 167ms | 98ms | -69ms | -41.35
| getChannelMembersForTeamForUser | p99 | 159ms | 96ms | -63ms | -39.54
| deleteDraft | p99 | 199ms | 122ms | -77ms | -38.66
| updatePreferences | p99 | 389ms | 250ms | -139ms | -35.73
| getPublicChannelsForTeam | p99 | 197ms | 129ms | -68ms | -34.57
| getThreadsForUser | p99 | 184ms | 123ms | -61ms | -33.14
| searchGroupChannels | p99 | 182ms | 125ms | -57ms | -31.40
| root | p99 | 171ms | 121ms | -50ms | -29.31
| listChannelBookmarksForChannel | p99 | 132ms | 96ms | -36ms | -27.25
| getFileThumbnail | p99 | 340ms | 248ms | -92ms | -27.04
| getTeamMember | p99 | 130ms | 95ms | -35ms | -26.84
| upsertDraft | p99 | 203ms | 149ms | -54ms | -26.59
| patchPost | p99 | 827ms | 622ms | -205ms | -24.78
| saveReaction | p99 | 322ms | 247ms | -75ms | -23.31
| autocompleteUsers | p99 | 325ms | 251ms | -74ms | -22.79
| updateReadStateThreadByUser | p99 | 903ms | 734ms | -169ms | -18.72
| getFilePreview | p99 | 386ms | 314ms | -72ms | -18.66
| removeUserCustomStatus | p99 | 1.157s | 963ms | -194ms | -16.76
| getChannelStats | p99 | 118ms | 99ms | -19ms | -16.12
| getCategoriesForTeamForUser | p99 | 187ms | 165ms | -22ms | -11.74
| getTeamScheduledPosts | p99 | 184ms | 165ms | -19ms | -10.35
| deletePost | p99 | 942ms | 845ms | -97ms | -10.29
| listCPAValues | p99 | 239ms | 215ms | -24ms | -10.02
| getTeamsForUser | p99 | 91ms | 82ms | -9ms | -9.90
| getPostThread | p99 | 477ms | 431ms | -46ms | -9.64
| createPost | p99 | 3.761s | 3.412s | -349ms | -9.28
| getPreferences | p99 | 97ms | 88ms | -9ms | -9.27
| getChannelsForUser | p99 | 91ms | 83ms | -8ms | -8.83
| followThreadByUser | p99 | 430ms | 395ms | -35ms | -8.14
| getUserStatusesByIds | p99 | 62ms | 57ms | -5ms | -8.08
| listCPAFields | p99 | 194ms | 179ms | -15ms | -7.75
| getUsersByIds | p99 | 44ms | 41ms | -3ms | -6.87
| getChannelMembersForUser | p99 | 91ms | 85ms | -6ms | -6.56
| createDirectChannel | p99 | 2.327s | 2.183s | -144ms | -6.19
| createGroupChannel | p99 | 4.481s | 4.228s | -253ms | -5.65
| getTeamsUnreadForUser | p99 | 200ms | 189ms | -11ms | -5.51
| getTeamMembersForUser | p99 | 95ms | 90ms | -5ms | -5.25
| getChannel | p99 | 236ms | 224ms | -12ms | -5.09
| getChannelMember | p99 | 208ms | 198ms | -10ms | -4.80
| searchAllChannels | p99 | 250ms | 238ms | -12ms | -4.80
| getAllTeams | p99 | 98ms | 94ms | -4ms | -4.10
| searchUsers | p99 | 236ms | 227ms | -9ms | -3.81
| getClientConfig | p99 | 213ms | 205ms | -8ms | -3.75
| getUser | p99 | 207ms | 200ms | -7ms | -3.39
| updateCategoriesForTeamForUser | p99 | 940ms | 915ms | -25ms | -2.66
| login | p99 | 958ms | 942ms | -16ms | -1.67
| getProfileImage | p99 | 489ms | 481ms | -8ms | -1.64
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 74ms | -7ms | -8.659
| BotStore.Get |  Avg| 15ms| 12ms | -3ms | -19.909
| |  P99| 212ms| 85ms | -127ms | -59.765
| ChannelBookmarkStore.Delete |  Avg| 27ms| 37ms | 10ms | 36.369
| |  P99| 241ms| 233ms | -8ms | -3.320
| ChannelBookmarkStore.Get |  Avg| 10ms| 14ms | 4ms | 39.782
| |  P99| 47ms| 93ms | 46ms | 97.867
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 89ms | -10ms | -10.151
| ChannelBookmarkStore.Save |  Avg| 43ms| 42ms | -1ms | -2.300
| |  P99| 242ms| 242ms | 0s | 0.000
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 6ms | 1ms | 18.524
| |  P99| 48ms| 50ms | 2ms | 4.186
| ChannelStore.AnalyticsCountAll |  Avg| 23ms| 37ms | 14ms | 61.337
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 51ms| 49ms | -2ms | -3.957
| |  P99| 250ms| 235ms | -15ms | -6.004
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 74ms| 102ms | 28ms | 37.870
| |  P99| 347ms| 1.634s | 1.287s | 370.366
| ChannelStore.CreateDirectChannel |  Avg| 83ms| 68ms | -15ms | -17.974
| |  P99| 762ms| 491ms | -271ms | -35.542
| ChannelStore.CreateInitialSidebarCategories |  Avg| 26ms| 29ms | 3ms | 11.413
| |  P99| 241ms| 244ms | 3ms | 1.243
| ChannelStore.CreateSidebarCategory |  Avg| 40ms| 26ms | -14ms | -35.348
| |  P99| 99ms| 232ms | 133ms | 134.343
| ChannelStore.Get |  Avg| 17ms| 14ms | -3ms | -18.159
| |  P99| 209ms| 132ms | -77ms | -36.930
| ChannelStore.GetAllChannelMembersForUser |  Avg| 12ms| 11ms | -1ms | -8.421
| |  P99| 122ms| 93ms | -29ms | -23.703
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 23ms| 22ms | -1ms | -4.263
| |  P99| 235ms| 224ms | -11ms | -4.682
| ChannelStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 93ms| 88ms | -5ms | -5.386
| ChannelStore.GetChannelUnread |  Avg| 12ms| 11ms | -1ms | -8.259
| |  P99| 155ms| 93ms | -62ms | -39.997
| ChannelStore.GetChannels |  Avg| 13ms| 11ms | -2ms | -15.948
| |  P99| 161ms| 96ms | -65ms | -40.454
| ChannelStore.GetChannelsByIds |  Avg| 25ms| 9ms | -16ms | -65.127
| |  P99| 97ms| 25ms | -72ms | -74.227
| ChannelStore.GetChannelsByUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 80ms | -9ms | -10.132
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 9ms | -1ms | -10.014
| |  P99| 102ms| 86ms | -16ms | -15.657
| ChannelStore.GetFileCount |  Avg| 11ms| 10ms | -1ms | -9.346
| |  P99| 98ms| 89ms | -9ms | -9.179
| ChannelStore.GetForPost |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 187ms| 105ms | -82ms | -43.837
| ChannelStore.GetGuestCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 94ms| 91ms | -3ms | -3.193
| ChannelStore.GetMany |  Avg| 17ms| 22ms | 5ms | 29.911
| |  P99| 375ms| 370ms | -5ms | -1.333
| ChannelStore.GetMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 81ms | -8ms | -8.999
| ChannelStore.GetMemberCount |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 198ms| 181ms | -17ms | -8.567
| ChannelStore.GetMemberCountsByGroup |  Avg| 29ms| 0s | -29ms | -98.551
| |  P99| 221ms| 0s | -221ms | -100.110
| ChannelStore.GetMemberForPost |  Avg| 16ms| 35ms | 19ms | 115.966
| |  P99| 179ms| 186ms | 7ms | 3.906
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 74ms | -9ms | -10.829
| ChannelStore.GetMembers |  Avg| 9ms| 3ms | -6ms | -66.142
| |  P99| 24ms| 5ms | -19ms | -77.812
| ChannelStore.GetMembersForUser |  Avg| 12ms| 11ms | -1ms | -8.095
| |  P99| 154ms| 95ms | -59ms | -38.412
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 9ms| 0s | -9ms | -96.225
| |  P99| 24ms| 0s | -24ms | -98.969
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 82ms | -8ms | -8.874
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 110ms| 96ms | -14ms | -12.671
| ChannelStore.GetPublicChannelsForTeam |  Avg| 26ms| 24ms | -2ms | -7.577
| |  P99| 183ms| 129ms | -54ms | -29.514
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 174ms| 141ms | -33ms | -19.007
| ChannelStore.GetSidebarCategory |  Avg| 31ms| 20ms | -11ms | -35.979
| |  P99| 227ms| 99ms | -128ms | -56.512
| ChannelStore.GetTeamChannels |  Avg| 30ms| 41ms | 11ms | 37.168
| |  P99| 97ms| 223ms | 126ms | 130.345
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 90ms| 79ms | -11ms | -12.229
| ChannelStore.Save |  Avg| 35ms| 39ms | 4ms | 11.570
| |  P99| 241ms| 278ms | 37ms | 15.337
| ChannelStore.SaveMember |  Avg| 54ms| 58ms | 4ms | 7.396
| |  P99| 396ms| 413ms | 17ms | 4.296
| ChannelStore.SearchGroupChannels |  Avg| 15ms| 13ms | -2ms | -13.674
| |  P99| 178ms| 113ms | -65ms | -36.601
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 79ms | -12ms | -13.229
| ChannelStore.UpdateSidebarCategories |  Avg| 99ms| 96ms | -3ms | -3.019
| |  P99| 470ms| 660ms | 190ms | 40.425
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 85ms| 82ms | -3ms | -3.521
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 14ms| 11ms | -3ms | -21.858
| |  P99| 117ms| 93ms | -24ms | -20.509
| CommandWebhookStore.Cleanup |  Avg| 10ms| 4ms | -6ms | -61.078
| |  P99| 49ms| 10ms | -39ms | -79.591
| ComplianceStore.MessageExport |  Avg| 6ms| 530ms | 524ms | 8343.532
| |  P99| 10ms| 993ms | 983ms | 9875.119
| DraftStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 87ms | -12ms | -12.113
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 11ms| 18ms | 7ms | 64.737
| |  P99| 47ms| 203ms | 156ms | 331.038
| DraftStore.Get |  Avg| 14ms| 12ms | -2ms | -14.211
| |  P99| 189ms| 99ms | -90ms | -47.692
| DraftStore.GetDraftsForUser |  Avg| 14ms| 12ms | -2ms | -13.913
| |  P99| 185ms| 98ms | -87ms | -46.902
| DraftStore.Upsert |  Avg| 12ms| 11ms | -1ms | -8.286
| |  P99| 143ms| 93ms | -50ms | -34.971
| EmojiStore.GetByName |  Avg| 10ms| 9ms | -1ms | -10.434
| |  P99| 99ms| 89ms | -10ms | -10.067
| EmojiStore.GetMultipleByName |  Avg| 13ms| 9ms | -4ms | -30.866
| |  P99| 96ms| 24ms | -72ms | -74.612
| EmojiStore.Search |  Avg| 10ms| 0s | -10ms | -99.520
| |  P99| 25ms| 0s | -25ms | -100.604
| FileInfoStore.AttachToPost |  Avg| 14ms| 15ms | 1ms | 6.982
| |  P99| 177ms| 161ms | -16ms | -9.026
| FileInfoStore.Get |  Avg| 11ms| 10ms | -1ms | -8.827
| |  P99| 155ms| 95ms | -60ms | -38.764
| FileInfoStore.GetByIds |  Avg| 10ms| 8ms | -2ms | -19.516
| |  P99| 104ms| 88ms | -16ms | -15.424
| FileInfoStore.GetForPost |  Avg| 7ms| 5ms | -2ms | -26.750
| |  P99| 85ms| 57ms | -28ms | -33.037
| FileInfoStore.Save |  Avg| 13ms| 12ms | -1ms | -7.645
| |  P99| 152ms| 93ms | -59ms | -38.784
| FileInfoStore.SetContent |  Avg| 17ms| 19ms | 2ms | 11.993
| |  P99| 151ms| 184ms | 33ms | 21.854
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 63ms| 64ms | 1ms | 1.594
| GroupStore.GetByName |  Avg| 7ms| 8ms | 1ms | 14.180
| |  P99| 79ms| 80ms | 1ms | 1.260
| GroupStore.GetGroups |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 88ms | -7ms | -7.384
| JobStore.GetAllByStatus |  Avg| 14ms| 12ms | -2ms | -14.763
| |  P99| 203ms| 126ms | -77ms | -37.995
| JobStore.GetAllByTypePage |  Avg| 13ms| 20ms | 7ms | 52.347
| |  P99| 96ms| 206ms | 110ms | 114.734
| JobStore.GetCountByStatusAndType |  Avg| 20ms| 9ms | -11ms | -54.106
| |  P99| 421ms| 90ms | -331ms | -78.653
| JobStore.GetNewestJobByStatusesAndType |  Avg| 11ms| 8ms | -3ms | -27.425
| |  P99| 119ms| 101ms | -18ms | -15.158
| JobStore.Save |  Avg| 11ms| 8ms | -3ms | -27.783
| |  P99| 80ms| 76ms | -4ms | -4.984
| JobStore.UpdateOptimistically |  Avg| 7ms| 6ms | -1ms | -13.353
| |  P99| 128ms| 70ms | -58ms | -45.138
| JobStore.UpdateStatus |  Avg| 8ms| 6ms | -2ms | -24.909
| |  P99| 87ms| 45ms | -42ms | -48.184
| JobStore.UpdateStatusOptimistically |  Avg| 10ms| 7ms | -3ms | -30.311
| |  P99| 134ms| 84ms | -50ms | -37.176
| LicenseStore.GetAll |  Avg| 4ms| 14ms | 10ms | 250.995
| |  P99| 24ms| 49ms | 25ms | 102.459
| LinkMetadataStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 97ms| 85ms | -12ms | -12.381
| LinkMetadataStore.Save |  Avg| 9ms| 5ms | -4ms | -43.754
| |  P99| 94ms| 37ms | -57ms | -60.638
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 78ms | -11ms | -12.308
| PostAcknowledgementStore.GetForPosts |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 180ms| 165ms | -15ms | -8.341
| PostPersistentNotificationStore.DeleteExpired |  Avg| 9ms| 6ms | -3ms | -34.867
| |  P99| 187ms| 87ms | -100ms | -53.477
| PostPersistentNotificationStore.Get |  Avg| 7ms| 5ms | -2ms | -27.780
| |  P99| 178ms| 72ms | -106ms | -59.552
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 77ms | -11ms | -12.524
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 5ms | 1ms | 24.131
| |  P99| 10ms| 24ms | 14ms | 143.590
| PostPriorityStore.GetForPostWithContext |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 91ms| 79ms | -12ms | -13.217
| PostPriorityStore.GetForPosts |  Avg| 14ms| 13ms | -1ms | -7.256
| |  P99| 188ms| 171ms | -17ms | -9.065
| PostStore.AnalyticsPostCount |  Avg| 171ms| 259ms | 88ms | 51.421
| |  P99| 495ms| 496ms | 1ms | 0.202
| PostStore.AnalyticsPostCountByTeam |  Avg| 2ms| 7ms | 5ms | 313.106
| |  P99| 5ms| 25ms | 20ms | 403.734
| PostStore.Delete |  Avg| 61ms| 51ms | -10ms | -16.262
| |  P99| 885ms| 423ms | -462ms | -52.205
| PostStore.Get |  Avg| 26ms| 22ms | -4ms | -15.426
| |  P99| 239ms| 217ms | -22ms | -9.208
| PostStore.GetEtag |  Avg| 11ms| 10ms | -1ms | -8.726
| |  P99| 146ms| 96ms | -50ms | -34.144
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 51ms| 49ms | -2ms | -3.909
| PostStore.GetPostIdBeforeTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 80ms| 74ms | -6ms | -7.468
| PostStore.GetPostReminderMetadata |  Avg| 17ms| 12ms | -5ms | -29.451
| |  P99| 337ms| 79ms | -258ms | -76.450
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 48ms | -39ms | -44.828
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 78ms| 70ms | -8ms | -10.239
| PostStore.GetPostsAfter |  Avg| 10ms| 9ms | -1ms | -9.619
| |  P99| 125ms| 83ms | -42ms | -33.604
| PostStore.GetPostsBefore |  Avg| 13ms| 12ms | -1ms | -7.452
| |  P99| 159ms| 97ms | -62ms | -39.079
| PostStore.GetPostsByIds |  Avg| 10ms| 6ms | -4ms | -38.801
| |  P99| 49ms| 24ms | -25ms | -51.282
| PostStore.GetPostsByThread |  Avg| 18ms| 14ms | -4ms | -22.467
| |  P99| 128ms| 93ms | -35ms | -27.383
| PostStore.GetPostsSince |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 211ms| 190ms | -21ms | -9.949
| PostStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 94ms| 83ms | -11ms | -11.680
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 277ms| 246ms | -31ms | -11.206
| PostStore.SearchPostsForUser |  Avg| 72ms| 253ms | 181ms | 253.105
| |  P99| 1.86s| 2.422s | 562ms | 30.213
| PostStore.SetPostReminder |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 225ms| 219ms | -6ms | -2.673
| PostStore.Update |  Avg| 27ms| 25ms | -2ms | -7.307
| |  P99| 214ms| 224ms | 10ms | 4.682
| PreferenceStore.DeleteCategoryAndName |  Avg| 9ms| 11ms | 2ms | 21.287
| |  P99| 88ms| 48ms | -40ms | -45.199
| PreferenceStore.Get |  Avg| 12ms| 9ms | -3ms | -25.770
| |  P99| 149ms| 89ms | -60ms | -40.297
| PreferenceStore.GetAll |  Avg| 9ms| 8ms | -1ms | -11.446
| |  P99| 95ms| 86ms | -9ms | -9.447
| PreferenceStore.Save |  Avg| 21ms| 22ms | 1ms | 4.727
| |  P99| 228ms| 224ms | -4ms | -1.757
| ProductNoticesStore.ClearOldNotices |  Avg| 33ms| 41ms | 8ms | 24.447
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 70ms| 78ms | 8ms | 11.477
| |  P99| 580ms| 664ms | 84ms | 14.482
| PropertyFieldStore.SearchPropertyFields |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 74ms | -5ms | -6.345
| PropertyGroupStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 83ms | -8ms | -8.754
| PropertyValueStore.SearchPropertyValues |  Avg| 11ms| 9ms | -2ms | -18.777
| |  P99| 127ms| 89ms | -38ms | -29.969
| ReactionStore.GetForPost |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 89ms | -9ms | -9.214
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -114.995
| |  P99| 5ms| 0s | -5ms | -100.998
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 9ms| 7ms | -2ms | -23.227
| |  P99| 72ms| 53ms | -19ms | -26.392
| RoleStore.GetByNames |  Avg| 17ms| 27ms | 10ms | 57.378
| |  P99| 234ms| 177ms | -57ms | -24.334
| ScheduledPostStore.CreateScheduledPost |  Avg| 13ms| 12ms | -1ms | -7.694
| |  P99| 152ms| 92ms | -60ms | -39.349
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 24ms| 11ms | -13ms | -53.520
| |  P99| 435ms| 48ms | -387ms | -88.966
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 85ms| 79ms | -6ms | -7.029
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 14ms| 9ms | -5ms | -35.176
| |  P99| 211ms| 85ms | -126ms | -59.716
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -103.247
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 185ms| 166ms | -19ms | -10.276
| SessionStore.GetLRUSessions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 68ms| 67ms | -1ms | -1.480
| SessionStore.GetSessionsExpired |  Avg| 5ms| 6ms | 1ms | 19.464
| |  P99| 24ms| 47ms | 23ms | 94.553
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 85ms | -14ms | -14.169
| SessionStore.Remove |  Avg| 10ms| 6ms | -4ms | -39.125
| |  P99| 96ms| 45ms | -51ms | -53.403
| SessionStore.Save |  Avg| 12ms| 13ms | 1ms | 8.335
| |  P99| 97ms| 98ms | 1ms | 1.029
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 76ms | -7ms | -8.384
| StatusStore.Get |  Avg| 9ms| 8ms | -1ms | -11.513
| |  P99| 95ms| 88ms | -7ms | -7.357
| StatusStore.GetByIds |  Avg| 15ms| 12ms | -3ms | -19.533
| |  P99| 200ms| 107ms | -93ms | -46.586
| StatusStore.SaveOrUpdate |  Avg| 10ms| 9ms | -1ms | -9.690
| |  P99| 104ms| 90ms | -14ms | -13.503
| StatusStore.SaveOrUpdateMany |  Avg| 19ms| 16ms | -3ms | -15.710
| |  P99| 222ms| 163ms | -59ms | -26.547
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 11ms | 2ms | 21.620
| |  P99| 89ms| 90ms | 1ms | 1.125
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 81ms | -2ms | -2.416
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 77ms| 71ms | -6ms | -7.777
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 8ms | 6ms | 252.568
| |  P99| 5ms| 49ms | 44ms | 888.214
| TeamStore.Get |  Avg| 8ms| 7ms | -1ms | -13.231
| |  P99| 90ms| 80ms | -10ms | -11.054
| TeamStore.GetActiveMemberCount |  Avg| 55ms| 80ms | 25ms | 45.206
| |  P99| 99ms| 243ms | 144ms | 145.210
| TeamStore.GetAllPage |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 83ms | -5ms | -5.697
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 84ms | -8ms | -8.686
| TeamStore.GetMany |  Avg| 28ms| 6ms | -22ms | -77.470
| |  P99| 99ms| 24ms | -75ms | -76.142
| TeamStore.GetMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 68ms| 62ms | -6ms | -8.863
| TeamStore.GetTeamsByUserId |  Avg| 8ms| 7ms | -1ms | -12.914
| |  P99| 90ms| 80ms | -10ms | -11.169
| TeamStore.GetTeamsForUser |  Avg| 8ms| 7ms | -1ms | -13.079
| |  P99| 88ms| 81ms | -7ms | -7.985
| TeamStore.GetTotalMemberCount |  Avg| 61ms| 87ms | 26ms | 42.777
| |  P99| 220ms| 243ms | 23ms | 10.454
| TeamStore.SaveMember |  Avg| 36ms| 37ms | 1ms | 2.805
| |  P99| 228ms| 232ms | 4ms | 1.752
| TemporaryPostStore.GetExpiredPosts |  Avg| 5ms| 8ms | 3ms | 63.308
| |  P99| 48ms| 49ms | 1ms | 2.094
| ThreadStore.Get |  Avg| 8ms| 9ms | 1ms | 12.708
| |  P99| 58ms| 80ms | 22ms | 37.933
| ThreadStore.GetMembershipForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 120ms| 90ms | -30ms | -24.983
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 122ms| 98ms | -24ms | -19.636
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 80ms | -11ms | -12.138
| ThreadStore.GetThreadForUser |  Avg| 18ms| 16ms | -2ms | -11.170
| |  P99| 202ms| 164ms | -38ms | -18.818
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 21ms| 16ms | -5ms | -23.380
| |  P99| 173ms| 98ms | -75ms | -43.477
| ThreadStore.GetThreadsForUser |  Avg| 15ms| 13ms | -2ms | -13.575
| |  P99| 178ms| 98ms | -80ms | -44.825
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 82ms | -9ms | -9.921
| ThreadStore.GetTotalUnreadMentions |  Avg| 9ms| 8ms | -1ms | -11.553
| |  P99| 95ms| 83ms | -12ms | -12.675
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 82ms | -8ms | -8.900
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 83ms | -8ms | -8.793
| ThreadStore.MaintainMembership |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 212ms| 191ms | -21ms | -9.920
| ThreadStore.MarkAllAsReadByChannels |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 83ms | -9ms | -9.785
| ThreadStore.MarkAllAsReadByTeam |  Avg| 45ms| 6ms | -39ms | -86.668
| |  P99| 244ms| 24ms | -220ms | -90.164
| ThreadStore.MarkAsRead |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 78ms | -9ms | -10.381
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 77ms | -7ms | -8.319
| TokenStore.Cleanup |  Avg| 10ms| 2ms | -8ms | -80.538
| |  P99| 49ms| 10ms | -39ms | -79.591
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 9ms | 1ms | 12.289
| |  P99| 43ms| 47ms | 4ms | 9.196
| UserStore.AnalyticsActiveCount |  Avg| 25ms| 38ms | 13ms | 52.009
| |  P99| 50ms| 97ms | 47ms | 94.949
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 6ms| 3ms | -3ms | -53.393
| |  P99| 10ms| 5ms | -5ms | -50.505
| UserStore.AutocompleteUsersInChannel |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 336ms| 256ms | -80ms | -23.790
| UserStore.Count |  Avg| 22ms| 23ms | 1ms | 4.546
| |  P99| 136ms| 121ms | -15ms | -11.054
| UserStore.Get |  Avg| 9ms| 8ms | -1ms | -11.043
| |  P99| 100ms| 89ms | -11ms | -11.038
| UserStore.GetAllProfiles |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 50ms | -12ms | -19.316
| UserStore.GetAllProfilesInChannel |  Avg| 297ms| 330ms | 33ms | 11.119
| |  P99| 1.346s| 1.602s | 256ms | 19.026
| UserStore.GetByUsername |  Avg| 14ms| 11ms | -3ms | -22.155
| |  P99| 183ms| 94ms | -89ms | -48.528
| UserStore.GetForLogin |  Avg| 7ms| 8ms | 1ms | 13.444
| |  P99| 84ms| 81ms | -3ms | -3.576
| UserStore.GetMany |  Avg| 12ms| 8ms | -4ms | -33.820
| |  P99| 91ms| 74ms | -17ms | -18.656
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 21ms| 0s | -21ms | -101.717
| |  P99| 50ms| 0s | -50ms | -101.010
| UserStore.GetProfileByIds |  Avg| 11ms| 10ms | -1ms | -8.973
| |  P99| 143ms| 96ms | -47ms | -32.772
| UserStore.GetProfilesByUsernames |  Avg| 13ms| 11ms | -2ms | -15.249
| |  P99| 164ms| 97ms | -67ms | -40.880
| UserStore.GetProfilesInChannel |  Avg| 7ms| 9ms | 2ms | 29.114
| |  P99| 45ms| 90ms | 45ms | 100.002
| UserStore.GetProfilesNotInChannel |  Avg| 13ms| 15ms | 2ms | 15.174
| |  P99| 222ms| 91ms | -131ms | -59.140
| UserStore.GetUnreadCount |  Avg| 9ms| 8ms | -1ms | -10.934
| |  P99| 98ms| 86ms | -12ms | -12.240
| UserStore.IsEmpty |  Avg| 3ms| 4ms | 1ms | 29.578
| |  P99| 40ms| 40ms | 0s | 0.000
| UserStore.Save |  Avg| 150ms| 152ms | 2ms | 1.332
| |  P99| 478ms| 477ms | -1ms | -0.209
| UserStore.Search |  Avg| 46ms| 45ms | -1ms | -2.190
| |  P99| 234ms| 223ms | -11ms | -4.705
| UserStore.Update |  Avg| 21ms| 18ms | -3ms | -14.075
| |  P99| 226ms| 185ms | -41ms | -18.142
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 74ms | -10ms | -11.942
| UserStore.UpdateLastLogin |  Avg| 7ms| 8ms | 1ms | 13.717
| |  P99| 53ms| 57ms | 4ms | 7.515
| UserStore.UpdateUpdateAt |  Avg| 7ms| 8ms | 1ms | 14.063
| |  P99| 53ms| 59ms | 6ms | 11.351
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 77ms | -6ms | -7.191
| WebhookStore.GetOutgoingByTeam |  Avg| 14ms| 13ms | -1ms | -7.119
| |  P99| 180ms| 114ms | -66ms | -36.744
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 376ms| 427ms | 51ms | 13.577
| | P99| 1.958s| 2.297s | 339ms | 17.310
| addTeamMember | Avg| 1.07s| 1.163s | 93ms | 8.695
| | P99| 4.804s| 5.219s | 415ms | 8.639
| autocompleteChannelsForTeamForSearch | Avg| 74ms| 102ms | 28ms | 37.826
| | P99| 347ms| 1.634s | 1.287s | 370.366
| autocompleteEmojis | Avg| 10ms| 0s | -10ms | -99.117
| | P99| 25ms| 0s | -25ms | -100.604
| autocompleteUsers | Avg| 61ms| 62ms | 1ms | 1.629
| | P99| 325ms| 251ms | -74ms | -22.787
| channelMemberCountsByGroup | Avg| 40ms| 0s | -40ms | -99.271
| | P99| 238ms| 0s | -238ms | -99.873
| createCategoryForTeamForUser | Avg| 43ms| 33ms | -10ms | -23.008
| | P99| 99ms| 232ms | 133ms | 134.343
| createChannel | Avg| 448ms| 419ms | -29ms | -6.467
| | P99| 2.2s| 978ms | -1.222s | -55.544
| createChannelBookmark | Avg| 71ms| 53ms | -18ms | -25.349
| | P99| 473ms| 244ms | -229ms | -48.465
| createDirectChannel | Avg| 416ms| 447ms | 31ms | 7.455
| | P99| 2.327s| 2.183s | -144ms | -6.189
| createGroupChannel | Avg| 692ms| 775ms | 83ms | 11.997
| | P99| 4.481s| 4.228s | -253ms | -5.646
| createPost | Avg| 590ms| 601ms | 11ms | 1.864
| | P99| 3.761s| 3.412s | -349ms | -9.279
| createSchedulePost | Avg| 23ms| 16ms | -7ms | -29.932
| | P99| 675ms| 94ms | -581ms | -86.082
| createUser | Avg| 318ms| 341ms | 23ms | 7.228
| | P99| 1.723s| 1.887s | 164ms | 9.521
| deleteChannelBookmark | Avg| 40ms| 91ms | 51ms | 127.448
| | P99| 50ms| 247ms | 197ms | 395.870
| deleteDraft | Avg| 15ms| 12ms | -3ms | -20.177
| | P99| 199ms| 122ms | -77ms | -38.662
| deletePost | Avg| 127ms| 83ms | -44ms | -34.698
| | P99| 942ms| 845ms | -97ms | -10.292
| followThreadByUser | Avg| 47ms| 52ms | 5ms | 10.530
| | P99| 430ms| 395ms | -35ms | -8.139
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 98ms| 94ms | -4ms | -4.099
| getAnalytics | Avg| 57ms| 84ms | 27ms | 47.627
| | P99| 100ms| 246ms | 146ms | 146.678
| getCategoriesForTeamForUser | Avg| 15ms| 16ms | 1ms | 6.473
| | P99| 187ms| 165ms | -22ms | -11.741
| getChannel | Avg| 23ms| 22ms | -1ms | -4.283
| | P99| 236ms| 224ms | -12ms | -5.094
| getChannelMember | Avg| 17ms| 16ms | -1ms | -6.060
| | P99| 208ms| 198ms | -10ms | -4.804
| getChannelMembers | Avg| 13ms| 4ms | -9ms | -68.645
| | P99| 47ms| 5ms | -42ms | -89.342
| getChannelMembersForTeamForUser | Avg| 13ms| 11ms | -2ms | -15.857
| | P99| 159ms| 96ms | -63ms | -39.540
| getChannelMembersForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 91ms| 85ms | -6ms | -6.559
| getChannelStats | Avg| 7ms| 6ms | -1ms | -13.795
| | P99| 118ms| 99ms | -19ms | -16.122
| getChannelUnread | Avg| 13ms| 12ms | -1ms | -7.494
| | P99| 182ms| 98ms | -84ms | -46.087
| getChannelsForTeamForUser | Avg| 13ms| 11ms | -2ms | -15.618
| | P99| 167ms| 98ms | -69ms | -41.348
| getChannelsForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 91ms| 83ms | -8ms | -8.826
| getClientConfig | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 213ms| 205ms | -8ms | -3.752
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 15ms| 12ms | -3ms | -20.006
| | P99| 193ms| 100ms | -93ms | -48.087
| getFilePreview | Avg| 71ms| 70ms | -1ms | -1.399
| | P99| 386ms| 314ms | -72ms | -18.664
| getFileThumbnail | Avg| 67ms| 65ms | -2ms | -3.004
| | P99| 340ms| 248ms | -92ms | -27.045
| getFilteredUsersStats | Avg| 13ms| 20ms | 7ms | 53.217
| | P99| 25ms| 25ms | 0s | 0.000
| getJobsByType | Avg| 14ms| 21ms | 7ms | 50.478
| | P99| 96ms| 206ms | 110ms | 114.734
| getPostThread | Avg| 60ms| 55ms | -5ms | -8.358
| | P99| 477ms| 431ms | -46ms | -9.636
| getPostsForChannel | Avg| 116ms| 120ms | 4ms | 3.451
| | P99| 1.149s| 1.205s | 56ms | 4.873
| getPostsForChannelAroundLastUnread | Avg| 43ms| 45ms | 2ms | 4.642
| | P99| 391ms| 401ms | 10ms | 2.556
| getPreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 97ms| 88ms | -9ms | -9.269
| getPrevTrialLicense | Avg| 5ms| 4ms | -1ms | -19.834
| | P99| 25ms| 5ms | -20ms | -81.466
| getProfileImage | Avg| 91ms| 79ms | -12ms | -13.179
| | P99| 489ms| 481ms | -8ms | -1.636
| getPublicChannelsForTeam | Avg| 28ms| 25ms | -3ms | -10.560
| | P99| 197ms| 129ms | -68ms | -34.574
| getRolesByNames | Avg| 5ms| 29ms | 24ms | 495.921
| | P99| 5ms| 50ms | 45ms | 909.091
| getServerLimits | Avg| 14ms| 23ms | 9ms | 66.244
| | P99| 25ms| 50ms | 25ms | 100.604
| getTeamMember | Avg| 10ms| 9ms | -1ms | -10.318
| | P99| 130ms| 95ms | -35ms | -26.844
| getTeamMembersForUser | Avg| 9ms| 8ms | -1ms | -11.707
| | P99| 95ms| 90ms | -5ms | -5.252
| getTeamScheduledPosts | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 184ms| 165ms | -19ms | -10.347
| getTeamStats | Avg| 69ms| 95ms | 26ms | 37.950
| | P99| 235ms| 245ms | 10ms | 4.255
| getTeamsForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 91ms| 82ms | -9ms | -9.899
| getTeamsUnreadForUser | Avg| 15ms| 16ms | 1ms | 6.458
| | P99| 200ms| 189ms | -11ms | -5.507
| getThreadsForUser | Avg| 15ms| 13ms | -2ms | -13.697
| | P99| 184ms| 123ms | -61ms | -33.137
| getUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 207ms| 200ms | -7ms | -3.385
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 62ms| 57ms | -5ms | -8.077
| getUsers | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 186ms| 195ms | 9ms | 4.833
| getUsersByGroupChannelIds | Avg| 37ms| 0s | -37ms | -98.796
| | P99| 50ms| 0s | -50ms | -100.503
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 44ms| 41ms | -3ms | -6.875
| getUsersByNames | Avg| 14ms| 12ms | -2ms | -14.657
| | P99| 173ms| 99ms | -74ms | -42.785
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 55ms| 37ms | -18ms | -32.892
| | P99| 100ms| 50ms | -50ms | -50.251
| listCPAFields | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 194ms| 179ms | -15ms | -7.749
| listCPAValues | Avg| 24ms| 21ms | -3ms | -12.463
| | P99| 239ms| 215ms | -24ms | -10.024
| listChannelBookmarksForChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 132ms| 96ms | -36ms | -27.252
| login | Avg| 153ms| 152ms | -1ms | -0.654
| | P99| 958ms| 942ms | -16ms | -1.670
| logout | Avg| 142ms| 102ms | -40ms | -28.266
| | P99| 483ms| 795ms | 312ms | 64.580
| patchPost | Avg| 93ms| 84ms | -9ms | -9.639
| | P99| 827ms| 622ms | -205ms | -24.776
| removeUserCustomStatus | Avg| 248ms| 265ms | 17ms | 6.861
| | P99| 1.157s| 963ms | -194ms | -16.764
| root | Avg| 10ms| 7ms | -3ms | -30.617
| | P99| 171ms| 121ms | -50ms | -29.315
| saveReaction | Avg| 38ms| 55ms | 17ms | 45.260
| | P99| 322ms| 247ms | -75ms | -23.309
| searchAllChannels | Avg| 51ms| 50ms | -1ms | -1.951
| | P99| 250ms| 238ms | -12ms | -4.803
| searchGroupChannels | Avg| 15ms| 14ms | -1ms | -6.720
| | P99| 182ms| 125ms | -57ms | -31.398
| searchPostsInTeam | Avg| 98ms| 278ms | 180ms | 184.080
| | P99| 1.895s| 2.447s | 552ms | 29.134
| searchUsers | Avg| 48ms| 47ms | -1ms | -2.100
| | P99| 236ms| 227ms | -9ms | -3.807
| setPostReminder | Avg| 71ms| 95ms | 24ms | 33.760
| | P99| 472ms| 1.87s | 1.398s | 296.394
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 49ms| 49ms | 0s | 0.000
| | P99| 615ms| 335ms | -280ms | -45.529
| updateCategoriesForTeamForUser | Avg| 170ms| 149ms | -21ms | -12.331
| | P99| 940ms| 915ms | -25ms | -2.660
| updateChannelBookmark | Avg| 214ms| 86ms | -128ms | -59.686
| | P99| 985ms| 475ms | -510ms | -51.777
| updateChannelBookmarkSortOrder | Avg| 9ms| 14ms | 5ms | 58.574
| | P99| 25ms| 25ms | 0s | 0.000
| updatePreferences | Avg| 33ms| 31ms | -2ms | -6.015
| | P99| 389ms| 250ms | -139ms | -35.731
| updateReadStateAllThreadsByUser | Avg| 45ms| 6ms | -39ms | -86.403
| | P99| 244ms| 24ms | -220ms | -90.164
| updateReadStateThreadByUser | Avg| 133ms| 116ms | -17ms | -12.811
| | P99| 903ms| 734ms | -169ms | -18.723
| updateUserCustomStatus | Avg| 2ms| 0s | -2ms | -122.145
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 534ms| 534ms | 0s | 0.000
| | P99| 2.12s| 2.127s | 7ms | 0.330
| upsertDraft | Avg| 16ms| 14ms | -2ms | -12.539
| | P99| 203ms| 149ms | -54ms | -26.593
| viewChannel | Avg| 42ms| 51ms | 9ms | 21.464
| | P99| 437ms| 449ms | 12ms | 2.746

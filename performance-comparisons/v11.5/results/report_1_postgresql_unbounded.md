### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 3ms | 418ms | 415ms | 12423.94
| DesktopTokensStore.DeleteOlderThan | avg | 9ms | 48ms | 39ms | 444.41
| EmojiStore.GetMultipleByName | avg | 7ms | 33ms | 26ms | 361.91
| RoleStore.GetByNames | avg | 35ms | 93ms | 58ms | 167.28
| SystemStore.SaveOrUpdate | avg | 11ms | 30ms | 19ms | 166.89
| RoleStore.ChannelHigherScopedPermissions | avg | 10ms | 21ms | 11ms | 109.81
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 12ms | 24ms | 12ms | 97.79
| PostStore.AnalyticsPostCountByTeam | avg | 4ms | 8ms | 4ms | 93.53
| UserStore.GetProfilesInChannel | avg | 8ms | 15ms | 7ms | 83.69
| JobStore.GetAllByTypePage | avg | 11ms | 19ms | 8ms | 72.72
| PostPersistentNotificationStore.UpdateLastActivity | avg | 8ms | 13ms | 5ms | 63.06
| ChannelStore.UpdateSidebarCategories | avg | 76ms | 119ms | 43ms | 56.45
| BotStore.Get | avg | 13ms | 20ms | 7ms | 53.81
| PostAcknowledgementStore.GetForPost | avg | 7ms | 10ms | 3ms | 45.94
| ProductNoticesStore.ClearOldNotices | avg | 42ms | 61ms | 19ms | 45.64
| TeamStore.GetTotalMemberCount | avg | 55ms | 78ms | 23ms | 41.44
| UserStore.GetProfilesNotInChannel | avg | 8ms | 11ms | 3ms | 36.43
| PostStore.AnalyticsPostCount | avg | 201ms | 272ms | 71ms | 35.25
| TeamStore.GetActiveMemberCount | avg | 65ms | 87ms | 22ms | 33.87
| UserStore.GetByUsername | avg | 12ms | 16ms | 4ms | 32.98
| ThreadStore.MarkAllAsReadByTeam | avg | 10ms | 13ms | 3ms | 30.51
| ScheduledPostStore.CreateScheduledPost | avg | 13ms | 17ms | 4ms | 29.81
| ChannelStore.GetSidebarCategory | avg | 23ms | 29ms | 6ms | 26.03
| ChannelBookmarkStore.Save | avg | 24ms | 30ms | 6ms | 24.84
| ChannelStore.CreateSidebarCategory | avg | 49ms | 61ms | 12ms | 24.65
| ChannelStore.GetMany | avg | 12ms | 15ms | 3ms | 24.05
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 13ms | 16ms | 3ms | 23.81
| PreferenceStore.DeleteCategoryAndName | avg | 9ms | 11ms | 2ms | 22.72
| PreferenceStore.GetAll | avg | 10ms | 12ms | 2ms | 19.27
| ChannelStore.CreateInitialSidebarCategories | avg | 33ms | 39ms | 6ms | 18.16
| FileInfoStore.AttachToPost | avg | 17ms | 20ms | 3ms | 17.27
| ChannelStore.Get | avg | 19ms | 22ms | 3ms | 15.53
| UserStore.GetProfileByIds | avg | 13ms | 15ms | 2ms | 15.08
| PostStore.GetEtag | avg | 13ms | 15ms | 2ms | 14.97
| PostStore.Save | avg | 34ms | 39ms | 5ms | 14.64
| ChannelStore.GetPublicChannelsForTeam | avg | 29ms | 33ms | 4ms | 13.98
| ChannelStore.Save | avg | 43ms | 49ms | 6ms | 13.88
| SessionStore.Save | avg | 14ms | 16ms | 2ms | 13.87
| ChannelStore.GetChannels | avg | 14ms | 16ms | 2ms | 13.86
| FileInfoStore.Save | avg | 14ms | 16ms | 2ms | 13.81
| DraftStore.GetDraftsForUser | avg | 15ms | 17ms | 2ms | 13.50
| ChannelStore.SaveMember | avg | 60ms | 68ms | 8ms | 13.29
| StatusStore.UpdateExpiredDNDStatuses | avg | 16ms | 18ms | 2ms | 12.40
| ThreadStore.GetThreadsForUser | avg | 16ms | 18ms | 2ms | 12.32
| StatusStore.SaveOrUpdateMany | avg | 16ms | 18ms | 2ms | 12.28
| ProductNoticesStore.View | avg | 91ms | 102ms | 11ms | 12.13
| ChannelStore.GetMembers | avg | 17ms | 19ms | 2ms | 11.87
| ChannelStore.SearchGroupChannels | avg | 17ms | 19ms | 2ms | 11.78
| PreferenceStore.Save | avg | 27ms | 30ms | 3ms | 11.20
| SessionStore.Get | avg | 18ms | 20ms | 2ms | 11.10
| ThreadStore.MaintainMembership | avg | 18ms | 20ms | 2ms | 10.97
| ScheduledPostStore.GetPendingScheduledPosts | avg | 29ms | 32ms | 3ms | 10.49
| UserStore.GetAllProfilesInChannel | avg | 316ms | 349ms | 33ms | 10.44
| PostStore.SetPostReminder | avg | 22ms | 24ms | 2ms | 9.21
| ChannelStore.CreateDirectChannel | avg | 83ms | 90ms | 7ms | 8.45
| PostStore.GetPostsSince | avg | 27ms | 29ms | 2ms | 7.37
| PostStore.Get | avg | 29ms | 31ms | 2ms | 6.90
| UserStore.AutocompleteUsersInChannel | avg | 71ms | 75ms | 4ms | 5.63
| TeamStore.SaveMember | avg | 36ms | 38ms | 2ms | 5.62
| UserStore.Search | avg | 48ms | 50ms | 2ms | 4.20
| UserStore.Save | avg | 158ms | 164ms | 6ms | 3.80
| PostStore.Delete | avg | 62ms | 64ms | 2ms | 3.20
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 5ms | 988ms | 983ms | 19847.01
| DesktopTokensStore.DeleteOlderThan | p99 | 10ms | 99ms | 89ms | 894.47
| EmojiStore.GetMultipleByName | p99 | 24ms | 231ms | 207ms | 853.61
| RoleStore.ChannelHigherScopedPermissions | p99 | 49ms | 226ms | 177ms | 358.06
| ChannelStore.UpdateSidebarCategories | p99 | 457ms | 1.773s | 1.316s | 288.04
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 84ms | 220ms | 136ms | 160.95
| PostStore.AnalyticsPostCountByTeam | p99 | 10ms | 25ms | 15ms | 152.28
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 245ms | 146ms | 147.47
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 83ms | 204ms | 121ms | 146.66
| CommandWebhookStore.Cleanup | p99 | 10ms | 24ms | 14ms | 141.39
| ChannelBookmarkStore.Delete | p99 | 98ms | 224ms | 126ms | 129.23
| PostAcknowledgementStore.GetForPost | p99 | 73ms | 161ms | 88ms | 120.95
| ScheduledPostStore.CreateScheduledPost | p99 | 95ms | 205ms | 110ms | 115.38
| SystemStore.SaveOrUpdate | p99 | 25ms | 50ms | 25ms | 101.21
| BotStore.Get | p99 | 95ms | 191ms | 96ms | 101.05
| UserStore.GetProfilesNotInChannel | p99 | 24ms | 48ms | 24ms | 98.10
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 25ms | 49ms | 24ms | 97.76
| LicenseStore.GetAll | p99 | 25ms | 49ms | 24ms | 97.70
| PreferenceStore.DeleteCategoryAndName | p99 | 47ms | 92ms | 45ms | 95.57
| UserStore.GetProfilesInChannel | p99 | 48ms | 90ms | 42ms | 88.06
| RoleStore.GetByNames | p99 | 238ms | 440ms | 202ms | 85.03
| ChannelBookmarkStore.Save | p99 | 219ms | 398ms | 179ms | 81.92
| PostPriorityStore.GetForPost | p99 | 81ms | 144ms | 63ms | 77.96
| ChannelStore.GetSidebarCategory | p99 | 196ms | 338ms | 142ms | 72.44
| ChannelStore.GetMany | p99 | 120ms | 200ms | 80ms | 66.93
| PostStore.GetPostReminderMetadata | p99 | 118ms | 190ms | 72ms | 61.01
| ThreadStore.MarkAllAsReadByChannels | p99 | 97ms | 140ms | 43ms | 44.49
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 103ms | 147ms | 44ms | 42.85
| ChannelStore.CreateDirectChannel | p99 | 515ms | 728ms | 213ms | 41.35
| ChannelStore.GetMembersForUserWithPagination | p99 | 98ms | 137ms | 39ms | 39.72
| PostStore.SearchPostsForUser | p99 | 2.288s | 3.139s | 851ms | 37.20
| TeamStore.GetTeamsForUser | p99 | 99ms | 132ms | 33ms | 33.26
| ChannelStore.GetChannelsByUser | p99 | 95ms | 126ms | 31ms | 32.49
| DraftStore.Delete | p99 | 114ms | 150ms | 36ms | 31.57
| TeamStore.GetTeamsByUserId | p99 | 99ms | 130ms | 31ms | 31.27
| PreferenceStore.GetAll | p99 | 119ms | 156ms | 37ms | 31.19
| ChannelStore.GetMember | p99 | 95ms | 124ms | 29ms | 30.46
| ThreadStore.GetTotalUnreadMentions | p99 | 99ms | 129ms | 30ms | 30.18
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 100ms | 126ms | 26ms | 26.12
| ChannelStore.CreateInitialSidebarCategories | p99 | 332ms | 418ms | 86ms | 25.93
| TeamStore.GetAllPage | p99 | 108ms | 134ms | 26ms | 24.13
| ChannelStore.IncrementMentionCount | p99 | 97ms | 120ms | 23ms | 23.69
| ThreadStore.GetTotalThreads | p99 | 97ms | 119ms | 22ms | 22.60
| ChannelStore.GetPinnedPostCount | p99 | 136ms | 166ms | 30ms | 22.06
| GroupStore.GetGroups | p99 | 112ms | 136ms | 24ms | 21.37
| UserStore.UpdateUpdateAt | p99 | 71ms | 86ms | 15ms | 21.24
| ThreadStore.GetTotalUnreadThreads | p99 | 97ms | 117ms | 20ms | 20.57
| UserStore.GetUnreadCount | p99 | 118ms | 142ms | 24ms | 20.42
| UserStore.GetForLogin | p99 | 97ms | 116ms | 19ms | 19.62
| UserStore.GetAllProfilesInChannel | p99 | 1.707s | 2.037s | 330ms | 19.33
| PreferenceStore.Save | p99 | 248ms | 295ms | 47ms | 18.95
| UserTermsOfServiceStore.GetByUser | p99 | 96ms | 114ms | 18ms | 18.80
| SessionStore.Save | p99 | 160ms | 190ms | 30ms | 18.71
| StatusStore.SaveOrUpdate | p99 | 139ms | 165ms | 26ms | 18.67
| PropertyFieldStore.SearchPropertyFields | p99 | 98ms | 116ms | 18ms | 18.33
| FileInfoStore.GetForPost | p99 | 120ms | 142ms | 22ms | 18.28
| StatusStore.Get | p99 | 142ms | 167ms | 25ms | 17.65
| UserStore.GetMany | p99 | 121ms | 142ms | 21ms | 17.35
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 134ms | 157ms | 23ms | 17.22
| ChannelStore.GetGuestCount | p99 | 139ms | 162ms | 23ms | 16.52
| ChannelStore.GetFileCount | p99 | 145ms | 169ms | 24ms | 16.52
| PostStore.Save | p99 | 345ms | 401ms | 56ms | 16.24
| ChannelStore.GetByName | p99 | 124ms | 143ms | 19ms | 15.26
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 122ms | 140ms | 18ms | 14.81
| ThreadStore.GetTeamsUnreadForUser | p99 | 173ms | 198ms | 25ms | 14.48
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 142ms | 162ms | 20ms | 14.07
| PostStore.GetSingle | p99 | 107ms | 122ms | 15ms | 14.01
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 74ms | 84ms | 10ms | 13.60
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 81ms | 92ms | 11ms | 13.54
| FileInfoStore.Save | p99 | 161ms | 182ms | 21ms | 13.06
| DraftStore.Upsert | p99 | 161ms | 181ms | 20ms | 12.45
| TeamStore.GetMember | p99 | 82ms | 92ms | 10ms | 12.15
| UserStore.Get | p99 | 152ms | 170ms | 18ms | 11.84
| ChannelStore.GetAllChannelMembersForUser | p99 | 153ms | 171ms | 18ms | 11.76
| FileInfoStore.AttachToPost | p99 | 198ms | 221ms | 23ms | 11.64
| LinkMetadataStore.Get | p99 | 121ms | 135ms | 14ms | 11.61
| UserStore.Save | p99 | 494ms | 551ms | 57ms | 11.54
| EmojiStore.GetByName | p99 | 132ms | 147ms | 15ms | 11.40
| PostStore.GetPostIdAfterTime | p99 | 71ms | 79ms | 8ms | 11.29
| SessionStore.GetLRUSessions | p99 | 85ms | 94ms | 9ms | 10.61
| PostStore.GetEtag | p99 | 175ms | 193ms | 18ms | 10.29
| ThreadStore.GetThreadFollowers | p99 | 109ms | 120ms | 11ms | 10.08
| UserStore.GetAllProfiles | p99 | 83ms | 91ms | 8ms | 9.69
| FileInfoStore.Get | p99 | 173ms | 189ms | 16ms | 9.24
| DraftStore.GetDraftsForUser | p99 | 186ms | 203ms | 17ms | 9.15
| TeamStore.Get | p99 | 99ms | 108ms | 9ms | 9.11
| UserStore.GetByUsername | p99 | 156ms | 170ms | 14ms | 8.97
| UserStore.UpdateLastLogin | p99 | 79ms | 86ms | 7ms | 8.91
| ChannelStore.Save | p99 | 394ms | 428ms | 34ms | 8.64
| ProductNoticesStore.View | p99 | 836ms | 906ms | 70ms | 8.37
| ChannelStore.SaveMember | p99 | 461ms | 499ms | 38ms | 8.25
| UserStore.AutocompleteUsersInChannel | p99 | 343ms | 371ms | 28ms | 8.17
| ThreadStore.MarkAsRead | p99 | 88ms | 95ms | 7ms | 7.91
| ChannelStore.GetMembersForUser | p99 | 178ms | 192ms | 14ms | 7.85
| SystemStore.GetByName | p99 | 90ms | 97ms | 7ms | 7.76
| StatusStore.SaveOrUpdateMany | p99 | 194ms | 209ms | 15ms | 7.75
| UserStore.UpdateFailedPasswordAttempts | p99 | 91ms | 98ms | 7ms | 7.68
| UserStore.GetProfileByIds | p99 | 183ms | 197ms | 14ms | 7.66
| PostStore.GetPostsByThread | p99 | 144ms | 155ms | 11ms | 7.63
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 202ms | 217ms | 15ms | 7.44
| PreferenceStore.Get | p99 | 175ms | 188ms | 13ms | 7.43
| UserStore.Count | p99 | 177ms | 190ms | 13ms | 7.34
| PostStore.GetPostsBefore | p99 | 182ms | 195ms | 13ms | 7.15
| ChannelStore.GetChannels | p99 | 187ms | 200ms | 13ms | 6.93
| ChannelStore.SearchGroupChannels | p99 | 199ms | 212ms | 13ms | 6.55
| AuditStore.Save | p99 | 92ms | 98ms | 6ms | 6.49
| TeamStore.SaveMember | p99 | 229ms | 243ms | 14ms | 6.11
| PostStore.GetPostIdBeforeTime | p99 | 88ms | 93ms | 5ms | 5.69
| PostAcknowledgementStore.GetForPosts | p99 | 212ms | 224ms | 12ms | 5.65
| ChannelStore.GetTeamChannels | p99 | 212ms | 224ms | 12ms | 5.65
| PostPriorityStore.GetForPosts | p99 | 215ms | 227ms | 12ms | 5.57
| GroupStore.GetByName | p99 | 93ms | 98ms | 5ms | 5.39
| UserStore.GetProfilesByUsernames | p99 | 188ms | 198ms | 10ms | 5.33
| ChannelStore.AutocompleteInTeamForSearch | p99 | 404ms | 425ms | 21ms | 5.19
| ThreadStore.GetThreadsForUser | p99 | 194ms | 204ms | 10ms | 5.15
| SessionStore.Get | p99 | 215ms | 226ms | 11ms | 5.12
| ChannelStore.GetMemberCount | p99 | 216ms | 227ms | 11ms | 5.09
| FileInfoStore.SetContent | p99 | 221ms | 232ms | 11ms | 4.97
| ThreadStore.MaintainMembership | p99 | 223ms | 234ms | 11ms | 4.94
| ChannelStore.CreateSidebarCategory | p99 | 234ms | 245ms | 11ms | 4.71
| UserStore.Update | p99 | 237ms | 248ms | 11ms | 4.64
| PostStore.GetPosts | p99 | 89ms | 93ms | 4ms | 4.51
| StatusStore.UpdateLastActivityAt | p99 | 90ms | 94ms | 4ms | 4.45
| ThreadStore.UpdateMembership | p99 | 90ms | 94ms | 4ms | 4.44
| SessionStore.UpdateLastActivityAt | p99 | 91ms | 95ms | 4ms | 4.41
| ChannelStore.GetMemberLastViewedAt | p99 | 93ms | 97ms | 4ms | 4.32
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 95ms | 99ms | 4ms | 4.21
| WebhookStore.GetOutgoingByTeam | p99 | 195ms | 203ms | 8ms | 4.10
| PostStore.Get | p99 | 246ms | 256ms | 10ms | 4.06
| PostPersistentNotificationStore.GetSingle | p99 | 93ms | 96ms | 3ms | 3.24
| ChannelStore.UpdateLastViewedAt | p99 | 96ms | 99ms | 3ms | 3.14
| PostStore.GetPostsSince | p99 | 220ms | 226ms | 6ms | 2.73
| TeamStore.GetActiveMemberCount | p99 | 238ms | 244ms | 6ms | 2.53
| TeamStore.GetTotalMemberCount | p99 | 238ms | 244ms | 6ms | 2.53
| DraftStore.Get | p99 | 203ms | 208ms | 5ms | 2.46
| SessionStore.Remove | p99 | 84ms | 86ms | 2ms | 2.38
| ChannelStore.GetPublicChannelsForTeam | p99 | 215ms | 220ms | 5ms | 2.33
| ThreadStore.GetThreadForUser | p99 | 215ms | 220ms | 5ms | 2.33
| ChannelStore.Get | p99 | 222ms | 227ms | 5ms | 2.25
| ThreadStore.GetMembershipForUser | p99 | 157ms | 160ms | 3ms | 1.91
| ThreadStore.GetThreadUnreadReplyCount | p99 | 185ms | 188ms | 3ms | 1.62
| StatusStore.UpdateExpiredDNDStatuses | p99 | 202ms | 205ms | 3ms | 1.49
| PostStore.SetPostReminder | p99 | 216ms | 219ms | 3ms | 1.39
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -105.44
| ChannelStore.GetMemberCountsByGroup | avg | 21ms | 0s | -21ms | -100.49
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -98.91
| ChannelStore.GetChannelsByIds | avg | 32ms | 3ms | -29ms | -89.87
| ChannelBookmarkStore.UpdateSortOrder | avg | 77ms | 17ms | -60ms | -77.49
| TokenStore.Cleanup | avg | 26ms | 6ms | -20ms | -76.03
| SessionStore.GetSessionsExpired | avg | 19ms | 5ms | -14ms | -73.67
| UserStore.AnalyticsGetInactiveUsersCount | avg | 22ms | 6ms | -16ms | -72.30
| TeamStore.AnalyticsTeamCount | avg | 8ms | 2ms | -6ms | -72.11
| TeamStore.GetMany | avg | 13ms | 4ms | -9ms | -70.93
| PostStore.GetPostsByIds | avg | 17ms | 6ms | -11ms | -63.18
| RetentionPolicyStore.GetCount | avg | 5ms | 2ms | -3ms | -61.12
| JobStore.UpdateStatus | avg | 16ms | 6ms | -10ms | -60.90
| PostStore.GetPostReminders | avg | 36ms | 15ms | -21ms | -58.79
| PostPersistentNotificationStore.DeleteExpired | avg | 16ms | 7ms | -9ms | -57.42
| JobStore.UpdateOptimistically | avg | 17ms | 8ms | -9ms | -54.25
| TemporaryPostStore.GetExpiredPosts | avg | 29ms | 14ms | -15ms | -52.46
| PostPersistentNotificationStore.Get | avg | 17ms | 8ms | -9ms | -51.77
| JobStore.GetCountByStatusAndType | avg | 25ms | 15ms | -10ms | -39.64
| JobStore.UpdateStatusOptimistically | avg | 23ms | 14ms | -9ms | -39.61
| PostStore.SearchPostsForUser | avg | 153ms | 95ms | -58ms | -37.89
| ChannelStore.AnalyticsCountAll | avg | 25ms | 16ms | -9ms | -35.78
| JobStore.GetNewestJobByStatusesAndType | avg | 16ms | 11ms | -5ms | -30.39
| LinkMetadataStore.Save | avg | 13ms | 9ms | -4ms | -29.75
| LicenseStore.GetAll | avg | 11ms | 8ms | -3ms | -28.36
| UserStore.AnalyticsActiveCount | avg | 32ms | 23ms | -9ms | -28.02
| JobStore.Save | avg | 14ms | 11ms | -3ms | -21.52
| ChannelStore.GetChannelUnread | avg | 16ms | 14ms | -2ms | -12.42
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 23ms | 21ms | -2ms | -8.89
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 206ms | 0s | -206ms | -99.99
| ChannelStore.GetChannelsByIds | p99 | 239ms | 5ms | -234ms | -97.70
| TeamStore.AnalyticsTeamCount | p99 | 25ms | 5ms | -20ms | -81.47
| SessionStore.GetSessionsExpired | p99 | 231ms | 46ms | -185ms | -80.26
| TeamStore.GetMany | p99 | 48ms | 10ms | -38ms | -78.76
| TokenStore.Cleanup | p99 | 98ms | 24ms | -74ms | -75.51
| PostStore.GetPostsByIds | p99 | 97ms | 24ms | -73ms | -75.26
| UserStore.AnalyticsActiveCount | p99 | 97ms | 25ms | -72ms | -74.23
| JobStore.UpdateStatus | p99 | 201ms | 67ms | -134ms | -66.83
| PostPersistentNotificationStore.DeleteExpired | p99 | 225ms | 89ms | -136ms | -60.58
| ChannelBookmarkStore.Get | p99 | 211ms | 89ms | -122ms | -57.82
| JobStore.GetNewestJobByStatusesAndType | p99 | 228ms | 97ms | -131ms | -57.44
| JobStore.UpdateOptimistically | p99 | 219ms | 104ms | -115ms | -52.56
| ChannelBookmarkStore.UpdateSortOrder | p99 | 478ms | 232ms | -246ms | -51.52
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 50ms | 25ms | -25ms | -50.51
| RetentionPolicyStore.GetCount | p99 | 10ms | 5ms | -5ms | -50.50
| ChannelStore.AnalyticsCountAll | p99 | 50ms | 25ms | -25ms | -50.38
| LinkMetadataStore.Save | p99 | 181ms | 90ms | -91ms | -50.28
| JobStore.Save | p99 | 175ms | 97ms | -78ms | -44.57
| PostPersistentNotificationStore.Get | p99 | 221ms | 141ms | -80ms | -36.20
| JobStore.UpdateStatusOptimistically | p99 | 231ms | 152ms | -79ms | -34.13
| JobStore.GetAllByTypePage | p99 | 136ms | 97ms | -39ms | -28.67
| PostStore.GetPostsAfter | p99 | 137ms | 101ms | -36ms | -26.24
| PostStore.GetPostReminders | p99 | 238ms | 190ms | -48ms | -20.14
| ReactionStore.GetForPost | p99 | 114ms | 94ms | -20ms | -17.60
| ThreadStore.Get | p99 | 124ms | 106ms | -18ms | -14.57
| ChannelStore.GetChannelUnread | p99 | 209ms | 186ms | -23ms | -11.01
| JobStore.GetCountByStatusAndType | p99 | 221ms | 200ms | -21ms | -9.50
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 240ms | 221ms | -19ms | -7.90
| PostStore.Delete | p99 | 456ms | 422ms | -34ms | -7.45
| TemporaryPostStore.GetExpiredPosts | p99 | 241ms | 224ms | -17ms | -7.05
| UserAccessTokenStore.GetByToken | p99 | 201ms | 187ms | -14ms | -6.96
| PropertyValueStore.SearchPropertyValues | p99 | 201ms | 191ms | -10ms | -4.99
| FileInfoStore.GetByIds | p99 | 174ms | 166ms | -8ms | -4.61
| ClusterDiscoveryStore.SetLastPingAt | p99 | 202ms | 194ms | -8ms | -3.95
| JobStore.GetAllByStatus | p99 | 217ms | 209ms | -8ms | -3.69
| PostStore.Update | p99 | 248ms | 240ms | -8ms | -3.22
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | avg | 11ms | 20ms | 9ms | 80.44
| createChannelBookmark | avg | 35ms | 59ms | 24ms | 69.56
| getTeamStats | avg | 66ms | 94ms | 28ms | 42.49
| updateCategoriesForTeamForUser | avg | 134ms | 189ms | 55ms | 40.92
| updateReadStateAllThreadsByUser | avg | 10ms | 13ms | 3ms | 30.25
| createDirectChannel | avg | 443ms | 552ms | 109ms | 24.58
| addChannelMember | avg | 434ms | 532ms | 98ms | 22.61
| createCategoryForTeamForUser | avg | 62ms | 76ms | 14ms | 22.47
| getChannelsForUser | avg | 9ms | 11ms | 2ms | 21.18
| getChannelMembersForUser | avg | 10ms | 12ms | 2ms | 19.22
| getDrafts | avg | 16ms | 19ms | 3ms | 19.00
| getUser | avg | 16ms | 19ms | 3ms | 18.97
| getTeamMember | avg | 11ms | 13ms | 2ms | 18.31
| root | avg | 11ms | 13ms | 2ms | 18.20
| createGroupChannel | avg | 710ms | 829ms | 119ms | 16.76
| getTeamsUnreadForUser | avg | 18ms | 21ms | 3ms | 16.45
| getChannel | avg | 24ms | 28ms | 4ms | 16.36
| patchPost | avg | 100ms | 115ms | 15ms | 14.98
| getClientConfig | avg | 21ms | 24ms | 3ms | 14.54
| getUsers | avg | 14ms | 16ms | 2ms | 14.26
| getAnalytics | avg | 91ms | 104ms | 13ms | 14.21
| getChannelMembersForTeamForUser | avg | 14ms | 16ms | 2ms | 13.93
| removeUserCustomStatus | avg | 281ms | 320ms | 39ms | 13.88
| createChannel | avg | 393ms | 446ms | 53ms | 13.50
| getPublicChannelsForTeam | avg | 30ms | 34ms | 4ms | 13.17
| getUsersByNames | avg | 15ms | 17ms | 2ms | 12.94
| addTeamMember | avg | 1.211s | 1.365s | 154ms | 12.71
| saveReaction | avg | 40ms | 45ms | 5ms | 12.47
| getTeamScheduledPosts | avg | 17ms | 19ms | 2ms | 11.61
| searchGroupChannels | avg | 17ms | 19ms | 2ms | 11.54
| upsertDraft | avg | 18ms | 20ms | 2ms | 11.18
| createUser | avg | 354ms | 392ms | 38ms | 10.75
| viewChannel | avg | 48ms | 53ms | 5ms | 10.47
| updatePreferences | avg | 39ms | 43ms | 4ms | 10.21
| getChannelMember | avg | 20ms | 22ms | 2ms | 9.95
| login | avg | 184ms | 200ms | 16ms | 8.70
| deletePost | avg | 122ms | 132ms | 10ms | 8.18
| getPostsForChannelAroundLastUnread | avg | 50ms | 54ms | 4ms | 8.03
| createPost | avg | 622ms | 671ms | 49ms | 7.88
| autocompleteUsers | avg | 66ms | 71ms | 5ms | 7.59
| getPostsForChannel | avg | 120ms | 128ms | 8ms | 6.68
| getPostThread | avg | 69ms | 73ms | 4ms | 5.81
| getFileThumbnail | avg | 66ms | 69ms | 3ms | 4.55
| getFilePreview | avg | 71ms | 74ms | 3ms | 4.24
| searchUsers | avg | 50ms | 52ms | 2ms | 4.04
| updateReadStateThreadByUser | avg | 144ms | 146ms | 2ms | 1.39
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | p99 | 99ms | 435ms | 336ms | 341.12
| updateCategoriesForTeamForUser | p99 | 914ms | 2.136s | 1.222s | 133.73
| followThreadByUser | p99 | 243ms | 428ms | 185ms | 76.05
| getChannelMembersForUser | p99 | 99ms | 146ms | 47ms | 47.26
| getChannelsForUser | p99 | 97ms | 134ms | 37ms | 38.26
| getTeamsForUser | p99 | 103ms | 142ms | 39ms | 37.70
| addChannelMember | p99 | 2.387s | 3.281s | 894ms | 37.45
| patchPost | p99 | 730ms | 995ms | 265ms | 36.30
| searchPostsInTeam | p99 | 2.306s | 3.137s | 831ms | 36.03
| removeUserCustomStatus | p99 | 1.395s | 1.81s | 415ms | 29.75
| getPreferences | p99 | 135ms | 168ms | 33ms | 24.51
| addTeamMember | p99 | 7.113s | 8.787s | 1.674s | 23.54
| getTeamMember | p99 | 160ms | 194ms | 34ms | 21.25
| getTeamMembersForUser | p99 | 137ms | 164ms | 27ms | 19.77
| listCPAFields | p99 | 146ms | 173ms | 27ms | 18.53
| getUsersByIds | p99 | 49ms | 58ms | 9ms | 18.44
| getPostsForChannel | p99 | 1.364s | 1.588s | 224ms | 16.43
| getUserStatusesByIds | p99 | 82ms | 95ms | 13ms | 15.81
| deletePost | p99 | 825ms | 948ms | 123ms | 14.91
| getAllTeams | p99 | 162ms | 182ms | 20ms | 12.31
| createGroupChannel | p99 | 3.871s | 4.338s | 467ms | 12.06
| listChannelBookmarksForChannel | p99 | 168ms | 186ms | 18ms | 10.73
| root | p99 | 198ms | 218ms | 20ms | 10.08
| getChannel | p99 | 238ms | 261ms | 23ms | 9.67
| saveReaction | p99 | 385ms | 420ms | 35ms | 9.08
| autocompleteUsers | p99 | 353ms | 385ms | 32ms | 9.06
| getFileThumbnail | p99 | 370ms | 403ms | 33ms | 8.91
| getPostsForChannelAroundLastUnread | p99 | 454ms | 493ms | 39ms | 8.59
| getUser | p99 | 233ms | 253ms | 20ms | 8.59
| getDrafts | p99 | 199ms | 216ms | 17ms | 8.54
| getUsers | p99 | 224ms | 243ms | 19ms | 8.48
| login | p99 | 1.877s | 2.024s | 147ms | 7.83
| getChannelMembersForTeamForUser | p99 | 184ms | 198ms | 14ms | 7.61
| createPost | p99 | 4.142s | 4.444s | 302ms | 7.29
| createUser | p99 | 2.088s | 2.236s | 148ms | 7.09
| getTeamScheduledPosts | p99 | 211ms | 225ms | 14ms | 6.63
| searchGroupChannels | p99 | 204ms | 217ms | 13ms | 6.36
| getChannelsForTeamForUser | p99 | 193ms | 205ms | 12ms | 6.23
| getCategoriesForTeamForUser | p99 | 212ms | 225ms | 13ms | 6.15
| getFilePreview | p99 | 407ms | 431ms | 24ms | 5.89
| getTeamsUnreadForUser | p99 | 225ms | 238ms | 13ms | 5.79
| updatePreferences | p99 | 399ms | 422ms | 23ms | 5.76
| getChannelStats | p99 | 147ms | 155ms | 8ms | 5.46
| getChannelMember | p99 | 231ms | 243ms | 12ms | 5.19
| upsertDraft | p99 | 214ms | 225ms | 11ms | 5.15
| getUsersByNames | p99 | 195ms | 205ms | 10ms | 5.13
| getThreadsForUser | p99 | 204ms | 214ms | 10ms | 4.91
| getClientConfig | p99 | 236ms | 247ms | 11ms | 4.67
| createDirectChannel | p99 | 2.345s | 2.443s | 98ms | 4.18
| viewChannel | p99 | 469ms | 485ms | 16ms | 3.41
| autocompleteChannelsForTeamForSearch | p99 | 411ms | 425ms | 14ms | 3.41
| createSchedulePost | p99 | 208ms | 214ms | 6ms | 2.88
| deleteDraft | p99 | 212ms | 217ms | 5ms | 2.36
| getPublicChannelsForTeam | p99 | 217ms | 221ms | 4ms | 1.84
| getTeamStats | p99 | 241ms | 245ms | 4ms | 1.66
| getAnalytics | p99 | 243ms | 247ms | 4ms | 1.65
| searchUsers | p99 | 239ms | 242ms | 3ms | 1.25
| createCategoryForTeamForUser | p99 | 242ms | 245ms | 3ms | 1.24
| setPostReminder | p99 | 444ms | 449ms | 5ms | 1.13
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 28ms | 0s | -28ms | -101.81
| getRolesByNames | avg | 41ms | 0s | -41ms | -98.91
| getPrevTrialLicense | avg | 14ms | 1ms | -13ms | -92.35
| updateChannelBookmarkSortOrder | avg | 86ms | 25ms | -61ms | -71.16
| getServerLimits | avg | 38ms | 17ms | -21ms | -55.48
| searchPostsInTeam | avg | 179ms | 125ms | -54ms | -30.10
| updateChannelBookmark | avg | 74ms | 57ms | -17ms | -22.89
| getFilteredUsersStats | avg | 19ms | 15ms | -4ms | -21.06
| getChannelUnread | avg | 18ms | 15ms | -3ms | -16.35
| logout | avg | 127ms | 110ms | -17ms | -13.39
| followThreadByUser | avg | 60ms | 53ms | -7ms | -11.59
| getProfileImage | avg | 81ms | 72ms | -9ms | -11.06
| setPostReminder | avg | 64ms | 57ms | -7ms | -10.91
| unfollowThreadByUser | avg | 63ms | 59ms | -4ms | -6.32
| deleteChannelBookmark | avg | 79ms | 75ms | -4ms | -5.05
| uploadFileStream | avg | 552ms | 538ms | -14ms | -2.54
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | p99 | 429ms | 0s | -429ms | -99.96
| getRolesByNames | p99 | 99ms | 5ms | -94ms | -94.95
| getPrevTrialLicense | p99 | 25ms | 5ms | -20ms | -80.92
| getServerLimits | p99 | 98ms | 25ms | -73ms | -74.11
| updateUserCustomStatus | p99 | 19ms | 5ms | -14ms | -73.09
| logout | p99 | 1.54s | 477ms | -1.063s | -69.02
| updateChannelBookmarkSortOrder | p99 | 480ms | 235ms | -245ms | -51.04
| getJobsByType | p99 | 136ms | 97ms | -39ms | -28.67
| getChannelUnread | p99 | 231ms | 200ms | -31ms | -13.40
| updateChannelBookmark | p99 | 482ms | 457ms | -25ms | -5.18
| getPostThread | p99 | 617ms | 598ms | -19ms | -3.08
| unfollowThreadByUser | p99 | 469ms | 457ms | -12ms | -2.56
| listCPAValues | p99 | 208ms | 204ms | -4ms | -1.92
| updateReadStateThreadByUser | p99 | 963ms | 951ms | -12ms | -1.25
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 10ms | 1ms | 11.200
| |  P99| 92ms| 98ms | 6ms | 6.490
| BotStore.Get |  Avg| 13ms| 20ms | 7ms | 53.814
| |  P99| 95ms| 191ms | 96ms | 101.053
| ChannelBookmarkStore.Delete |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 98ms| 224ms | 126ms | 129.230
| ChannelBookmarkStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 211ms| 89ms | -122ms | -57.819
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 10ms| 11ms | 1ms | 9.570
| |  P99| 134ms| 157ms | 23ms | 17.216
| ChannelBookmarkStore.Save |  Avg| 24ms| 30ms | 6ms | 24.844
| |  P99| 219ms| 398ms | 179ms | 81.920
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 77ms| 17ms | -60ms | -77.485
| |  P99| 478ms| 232ms | -246ms | -51.517
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 8ms | 1ms | 15.040
| |  P99| 74ms| 84ms | 10ms | 13.600
| ChannelStore.AnalyticsCountAll |  Avg| 25ms| 16ms | -9ms | -35.778
| |  P99| 50ms| 25ms | -25ms | -50.378
| ChannelStore.Autocomplete |  Avg| 51ms| 51ms | 0s | 0.000
| |  P99| 245ms| 244ms | -1ms | -0.408
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 404ms| 425ms | 21ms | 5.195
| ChannelStore.CreateDirectChannel |  Avg| 83ms| 90ms | 7ms | 8.454
| |  P99| 515ms| 728ms | 213ms | 41.354
| ChannelStore.CreateInitialSidebarCategories |  Avg| 33ms| 39ms | 6ms | 18.164
| |  P99| 332ms| 418ms | 86ms | 25.934
| ChannelStore.CreateSidebarCategory |  Avg| 49ms| 61ms | 12ms | 24.653
| |  P99| 234ms| 245ms | 11ms | 4.711
| ChannelStore.Get |  Avg| 19ms| 22ms | 3ms | 15.529
| |  P99| 222ms| 227ms | 5ms | 2.255
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 14ms | 1ms | 7.586
| |  P99| 153ms| 171ms | 18ms | 11.756
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 23ms| 21ms | -2ms | -8.887
| |  P99| 240ms| 221ms | -19ms | -7.902
| ChannelStore.GetByName |  Avg| 13ms| 14ms | 1ms | 7.940
| |  P99| 124ms| 143ms | 19ms | 15.263
| ChannelStore.GetChannelUnread |  Avg| 16ms| 14ms | -2ms | -12.417
| |  P99| 209ms| 186ms | -23ms | -11.013
| ChannelStore.GetChannels |  Avg| 14ms| 16ms | 2ms | 13.860
| |  P99| 187ms| 200ms | 13ms | 6.935
| ChannelStore.GetChannelsByIds |  Avg| 32ms| 3ms | -29ms | -89.873
| |  P99| 239ms| 5ms | -234ms | -97.704
| ChannelStore.GetChannelsByUser |  Avg| 9ms| 10ms | 1ms | 10.839
| |  P99| 95ms| 126ms | 31ms | 32.488
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 11ms| 12ms | 1ms | 8.898
| |  P99| 142ms| 162ms | 20ms | 14.066
| ChannelStore.GetFileCount |  Avg| 13ms| 14ms | 1ms | 7.699
| |  P99| 145ms| 169ms | 24ms | 16.517
| ChannelStore.GetGuestCount |  Avg| 12ms| 13ms | 1ms | 8.625
| |  P99| 139ms| 162ms | 23ms | 16.520
| ChannelStore.GetMany |  Avg| 12ms| 15ms | 3ms | 24.052
| |  P99| 120ms| 200ms | 80ms | 66.930
| ChannelStore.GetMember |  Avg| 9ms| 10ms | 1ms | 11.456
| |  P99| 95ms| 124ms | 29ms | 30.463
| ChannelStore.GetMemberCount |  Avg| 35ms| 36ms | 1ms | 2.893
| |  P99| 216ms| 227ms | 11ms | 5.093
| ChannelStore.GetMemberCountsByGroup |  Avg| 21ms| 0s | -21ms | -100.488
| |  P99| 206ms| 0s | -206ms | -99.993
| ChannelStore.GetMemberForPost |  Avg| 18ms| 19ms | 1ms | 5.531
| |  P99| 206ms| 208ms | 2ms | 0.972
| ChannelStore.GetMemberLastViewedAt |  Avg| 8ms| 9ms | 1ms | 12.437
| |  P99| 93ms| 97ms | 4ms | 4.321
| ChannelStore.GetMembers |  Avg| 17ms| 19ms | 2ms | 11.866
| |  P99| 96ms| 97ms | 1ms | 1.042
| ChannelStore.GetMembersForUser |  Avg| 14ms| 15ms | 1ms | 7.142
| |  P99| 178ms| 192ms | 14ms | 7.851
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 11ms | 1ms | 9.835
| |  P99| 98ms| 137ms | 39ms | 39.716
| ChannelStore.GetPinnedPostCount |  Avg| 11ms| 12ms | 1ms | 9.226
| |  P99| 136ms| 166ms | 30ms | 22.062
| ChannelStore.GetPublicChannelsForTeam |  Avg| 29ms| 33ms | 4ms | 13.979
| |  P99| 215ms| 220ms | 5ms | 2.331
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 17ms| 18ms | 1ms | 5.958
| |  P99| 202ms| 217ms | 15ms | 7.437
| ChannelStore.GetSidebarCategory |  Avg| 23ms| 29ms | 6ms | 26.027
| |  P99| 196ms| 338ms | 142ms | 72.440
| ChannelStore.GetTeamChannels |  Avg| 33ms| 34ms | 1ms | 3.031
| |  P99| 212ms| 224ms | 12ms | 5.647
| ChannelStore.IncrementMentionCount |  Avg| 8ms| 9ms | 1ms | 11.992
| |  P99| 97ms| 120ms | 23ms | 23.691
| ChannelStore.Save |  Avg| 43ms| 49ms | 6ms | 13.878
| |  P99| 394ms| 428ms | 34ms | 8.638
| ChannelStore.SaveMember |  Avg| 60ms| 68ms | 8ms | 13.286
| |  P99| 461ms| 499ms | 38ms | 8.251
| ChannelStore.SearchGroupChannels |  Avg| 17ms| 19ms | 2ms | 11.785
| |  P99| 199ms| 212ms | 13ms | 6.546
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 11ms | 1ms | 9.662
| |  P99| 96ms| 99ms | 3ms | 3.138
| ChannelStore.UpdateSidebarCategories |  Avg| 76ms| 119ms | 43ms | 56.450
| |  P99| 457ms| 1.773s | 1.316s | 288.042
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.024
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 17ms| 18ms | 1ms | 5.916
| |  P99| 202ms| 194ms | -8ms | -3.952
| CommandWebhookStore.Cleanup |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 141.390
| ComplianceStore.MessageExport |  Avg| 3ms| 418ms | 415ms | 12423.941
| |  P99| 5ms| 988ms | 983ms | 19847.011
| DesktopTokensStore.DeleteOlderThan |  Avg| 9ms| 48ms | 39ms | 444.415
| |  P99| 10ms| 99ms | 89ms | 894.472
| DraftStore.Delete |  Avg| 11ms| 12ms | 1ms | 8.735
| |  P99| 114ms| 150ms | 36ms | 31.574
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 13ms| 16ms | 3ms | 23.813
| |  P99| 83ms| 204ms | 121ms | 146.657
| DraftStore.Get |  Avg| 16ms| 17ms | 1ms | 6.324
| |  P99| 203ms| 208ms | 5ms | 2.460
| DraftStore.GetDraftsForUser |  Avg| 15ms| 17ms | 2ms | 13.497
| |  P99| 186ms| 203ms | 17ms | 9.152
| DraftStore.Upsert |  Avg| 14ms| 15ms | 1ms | 7.285
| |  P99| 161ms| 181ms | 20ms | 12.447
| EmojiStore.GetByName |  Avg| 10ms| 11ms | 1ms | 9.880
| |  P99| 132ms| 147ms | 15ms | 11.397
| EmojiStore.GetMultipleByName |  Avg| 7ms| 33ms | 26ms | 361.914
| |  P99| 24ms| 231ms | 207ms | 853.609
| FileInfoStore.AttachToPost |  Avg| 17ms| 20ms | 3ms | 17.267
| |  P99| 198ms| 221ms | 23ms | 11.636
| FileInfoStore.Get |  Avg| 13ms| 14ms | 1ms | 7.962
| |  P99| 173ms| 189ms | 16ms | 9.244
| FileInfoStore.GetByIds |  Avg| 12ms| 13ms | 1ms | 8.510
| |  P99| 174ms| 166ms | -8ms | -4.611
| FileInfoStore.GetForPost |  Avg| 10ms| 11ms | 1ms | 9.857
| |  P99| 120ms| 142ms | 22ms | 18.280
| FileInfoStore.Save |  Avg| 14ms| 16ms | 2ms | 13.812
| |  P99| 161ms| 182ms | 21ms | 13.060
| FileInfoStore.SetContent |  Avg| 22ms| 23ms | 1ms | 4.589
| |  P99| 221ms| 232ms | 11ms | 4.968
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 7ms| 8ms | 1ms | 14.339
| |  P99| 81ms| 92ms | 11ms | 13.537
| GroupStore.GetByName |  Avg| 8ms| 9ms | 1ms | 11.877
| |  P99| 93ms| 98ms | 5ms | 5.389
| GroupStore.GetGroups |  Avg| 10ms| 11ms | 1ms | 9.553
| |  P99| 112ms| 136ms | 24ms | 21.367
| JobStore.GetAllByStatus |  Avg| 16ms| 17ms | 1ms | 6.228
| |  P99| 217ms| 209ms | -8ms | -3.689
| JobStore.GetAllByTypePage |  Avg| 11ms| 19ms | 8ms | 72.724
| |  P99| 136ms| 97ms | -39ms | -28.669
| JobStore.GetCountByStatusAndType |  Avg| 25ms| 15ms | -10ms | -39.639
| |  P99| 221ms| 200ms | -21ms | -9.502
| JobStore.GetNewestJobByStatusesAndType |  Avg| 16ms| 11ms | -5ms | -30.391
| |  P99| 228ms| 97ms | -131ms | -57.440
| JobStore.Save |  Avg| 14ms| 11ms | -3ms | -21.520
| |  P99| 175ms| 97ms | -78ms | -44.571
| JobStore.UpdateOptimistically |  Avg| 17ms| 8ms | -9ms | -54.252
| |  P99| 219ms| 104ms | -115ms | -52.559
| JobStore.UpdateStatus |  Avg| 16ms| 6ms | -10ms | -60.896
| |  P99| 201ms| 67ms | -134ms | -66.832
| JobStore.UpdateStatusOptimistically |  Avg| 23ms| 14ms | -9ms | -39.608
| |  P99| 231ms| 152ms | -79ms | -34.134
| LicenseStore.GetAll |  Avg| 11ms| 8ms | -3ms | -28.359
| |  P99| 25ms| 49ms | 24ms | 97.699
| LinkMetadataStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 121ms| 135ms | 14ms | 11.606
| LinkMetadataStore.Save |  Avg| 13ms| 9ms | -4ms | -29.749
| |  P99| 181ms| 90ms | -91ms | -50.279
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 10ms | 3ms | 45.937
| |  P99| 73ms| 161ms | 88ms | 120.952
| PostAcknowledgementStore.GetForPosts |  Avg| 15ms| 16ms | 1ms | 6.627
| |  P99| 212ms| 224ms | 12ms | 5.653
| PostPersistentNotificationStore.DeleteExpired |  Avg| 16ms| 7ms | -9ms | -57.421
| |  P99| 225ms| 89ms | -136ms | -60.579
| PostPersistentNotificationStore.Get |  Avg| 17ms| 8ms | -9ms | -51.767
| |  P99| 221ms| 141ms | -80ms | -36.199
| PostPersistentNotificationStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 96ms | 3ms | 3.238
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 8ms| 13ms | 5ms | 63.055
| |  P99| 25ms| 49ms | 24ms | 97.760
| PostPriorityStore.GetForPost |  Avg| 9ms| 10ms | 1ms | 11.412
| |  P99| 81ms| 144ms | 63ms | 77.958
| PostPriorityStore.GetForPosts |  Avg| 16ms| 17ms | 1ms | 6.286
| |  P99| 215ms| 227ms | 12ms | 5.573
| PostStore.AnalyticsPostCount |  Avg| 201ms| 272ms | 71ms | 35.251
| |  P99| 496ms| 497ms | 1ms | 0.202
| PostStore.AnalyticsPostCountByTeam |  Avg| 4ms| 8ms | 4ms | 93.527
| |  P99| 10ms| 25ms | 15ms | 152.284
| PostStore.Delete |  Avg| 62ms| 64ms | 2ms | 3.204
| |  P99| 456ms| 422ms | -34ms | -7.452
| PostStore.Get |  Avg| 29ms| 31ms | 2ms | 6.897
| |  P99| 246ms| 256ms | 10ms | 4.058
| PostStore.GetEtag |  Avg| 13ms| 15ms | 2ms | 14.969
| |  P99| 175ms| 193ms | 18ms | 10.294
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 71ms| 79ms | 8ms | 11.289
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 8ms | 1ms | 13.821
| |  P99| 88ms| 93ms | 5ms | 5.689
| PostStore.GetPostReminderMetadata |  Avg| 14ms| 15ms | 1ms | 6.980
| |  P99| 118ms| 190ms | 72ms | 61.009
| PostStore.GetPostReminders |  Avg| 36ms| 15ms | -21ms | -58.791
| |  P99| 238ms| 190ms | -48ms | -20.136
| PostStore.GetPosts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 93ms | 4ms | 4.513
| PostStore.GetPostsAfter |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 137ms| 101ms | -36ms | -26.241
| PostStore.GetPostsBefore |  Avg| 15ms| 16ms | 1ms | 6.681
| |  P99| 182ms| 195ms | 13ms | 7.147
| PostStore.GetPostsByIds |  Avg| 17ms| 6ms | -11ms | -63.180
| |  P99| 97ms| 24ms | -73ms | -75.258
| PostStore.GetPostsByThread |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 144ms| 155ms | 11ms | 7.626
| PostStore.GetPostsSince |  Avg| 27ms| 29ms | 2ms | 7.368
| |  P99| 220ms| 226ms | 6ms | 2.728
| PostStore.GetSingle |  Avg| 9ms| 10ms | 1ms | 10.856
| |  P99| 107ms| 122ms | 15ms | 14.006
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 34ms| 39ms | 5ms | 14.635
| |  P99| 345ms| 401ms | 56ms | 16.240
| PostStore.SearchPostsForUser |  Avg| 153ms| 95ms | -58ms | -37.886
| |  P99| 2.288s| 3.139s | 851ms | 37.198
| PostStore.SetPostReminder |  Avg| 22ms| 24ms | 2ms | 9.213
| |  P99| 216ms| 219ms | 3ms | 1.387
| PostStore.Update |  Avg| 29ms| 30ms | 1ms | 3.467
| |  P99| 248ms| 240ms | -8ms | -3.224
| PreferenceStore.DeleteCategoryAndName |  Avg| 9ms| 11ms | 2ms | 22.724
| |  P99| 47ms| 92ms | 45ms | 95.573
| PreferenceStore.Get |  Avg| 13ms| 14ms | 1ms | 7.598
| |  P99| 175ms| 188ms | 13ms | 7.426
| PreferenceStore.GetAll |  Avg| 10ms| 12ms | 2ms | 19.267
| |  P99| 119ms| 156ms | 37ms | 31.190
| PreferenceStore.Save |  Avg| 27ms| 30ms | 3ms | 11.195
| |  P99| 248ms| 295ms | 47ms | 18.953
| ProductNoticesStore.ClearOldNotices |  Avg| 42ms| 61ms | 19ms | 45.637
| |  P99| 99ms| 245ms | 146ms | 147.475
| ProductNoticesStore.View |  Avg| 91ms| 102ms | 11ms | 12.133
| |  P99| 836ms| 906ms | 70ms | 8.374
| PropertyFieldStore.SearchPropertyFields |  Avg| 9ms| 10ms | 1ms | 10.850
| |  P99| 98ms| 116ms | 18ms | 18.330
| PropertyValueStore.SearchPropertyValues |  Avg| 14ms| 15ms | 1ms | 7.168
| |  P99| 201ms| 191ms | -10ms | -4.986
| ReactionStore.GetForPost |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 114ms| 94ms | -20ms | -17.600
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -98.914
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 5ms| 2ms | -3ms | -61.121
| |  P99| 10ms| 5ms | -5ms | -50.505
| RoleStore.ChannelHigherScopedPermissions |  Avg| 10ms| 21ms | 11ms | 109.813
| |  P99| 49ms| 226ms | 177ms | 358.061
| RoleStore.GetByNames |  Avg| 35ms| 93ms | 58ms | 167.283
| |  P99| 238ms| 440ms | 202ms | 85.026
| ScheduledPostStore.CreateScheduledPost |  Avg| 13ms| 17ms | 4ms | 29.811
| |  P99| 95ms| 205ms | 110ms | 115.384
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 29ms| 32ms | 3ms | 10.490
| |  P99| 234ms| 235ms | 1ms | 0.426
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 8ms| 9ms | 1ms | 11.900
| |  P99| 95ms| 99ms | 4ms | 4.210
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 12ms| 24ms | 12ms | 97.788
| |  P99| 84ms| 220ms | 136ms | 160.947
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -105.440
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 18ms| 20ms | 2ms | 11.104
| |  P99| 215ms| 226ms | 11ms | 5.118
| SessionStore.GetLRUSessions |  Avg| 7ms| 8ms | 1ms | 13.881
| |  P99| 85ms| 94ms | 9ms | 10.607
| SessionStore.GetSessionsExpired |  Avg| 19ms| 5ms | -14ms | -73.669
| |  P99| 231ms| 46ms | -185ms | -80.260
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 10ms| 11ms | 1ms | 9.701
| |  P99| 122ms| 140ms | 18ms | 14.811
| SessionStore.Remove |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 86ms | 2ms | 2.381
| SessionStore.Save |  Avg| 14ms| 16ms | 2ms | 13.868
| |  P99| 160ms| 190ms | 30ms | 18.706
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 10ms | 1ms | 10.807
| |  P99| 91ms| 95ms | 4ms | 4.414
| StatusStore.Get |  Avg| 11ms| 12ms | 1ms | 9.490
| |  P99| 142ms| 167ms | 25ms | 17.655
| StatusStore.GetByIds |  Avg| 17ms| 18ms | 1ms | 5.856
| |  P99| 214ms| 213ms | -1ms | -0.467
| StatusStore.SaveOrUpdate |  Avg| 12ms| 13ms | 1ms | 8.408
| |  P99| 139ms| 165ms | 26ms | 18.673
| StatusStore.SaveOrUpdateMany |  Avg| 16ms| 18ms | 2ms | 12.281
| |  P99| 194ms| 209ms | 15ms | 7.750
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 16ms| 18ms | 2ms | 12.397
| |  P99| 202ms| 205ms | 3ms | 1.487
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 9ms | 1ms | 11.828
| |  P99| 90ms| 94ms | 4ms | 4.450
| SystemStore.GetByName |  Avg| 7ms| 8ms | 1ms | 14.464
| |  P99| 90ms| 97ms | 7ms | 7.758
| SystemStore.PermanentDeleteByName |  Avg| 14ms| 13ms | -1ms | -7.235
| |  P99| 25ms| 25ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 11ms| 30ms | 19ms | 166.893
| |  P99| 25ms| 50ms | 25ms | 101.215
| TeamStore.AnalyticsTeamCount |  Avg| 8ms| 2ms | -6ms | -72.113
| |  P99| 25ms| 5ms | -20ms | -81.466
| TeamStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 108ms | 9ms | 9.115
| TeamStore.GetActiveMemberCount |  Avg| 65ms| 87ms | 22ms | 33.873
| |  P99| 238ms| 244ms | 6ms | 2.526
| TeamStore.GetAllPage |  Avg| 9ms| 10ms | 1ms | 10.783
| |  P99| 108ms| 134ms | 26ms | 24.129
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 10ms| 11ms | 1ms | 10.381
| |  P99| 103ms| 147ms | 44ms | 42.850
| TeamStore.GetMany |  Avg| 13ms| 4ms | -9ms | -70.926
| |  P99| 48ms| 10ms | -38ms | -78.756
| TeamStore.GetMember |  Avg| 7ms| 8ms | 1ms | 14.947
| |  P99| 82ms| 92ms | 10ms | 12.153
| TeamStore.GetTeamsByUserId |  Avg| 9ms| 10ms | 1ms | 10.895
| |  P99| 99ms| 130ms | 31ms | 31.273
| TeamStore.GetTeamsForUser |  Avg| 9ms| 10ms | 1ms | 10.983
| |  P99| 99ms| 132ms | 33ms | 33.264
| TeamStore.GetTotalMemberCount |  Avg| 55ms| 78ms | 23ms | 41.442
| |  P99| 238ms| 244ms | 6ms | 2.526
| TeamStore.SaveMember |  Avg| 36ms| 38ms | 2ms | 5.622
| |  P99| 229ms| 243ms | 14ms | 6.107
| TemporaryPostStore.GetExpiredPosts |  Avg| 29ms| 14ms | -15ms | -52.457
| |  P99| 241ms| 224ms | -17ms | -7.054
| ThreadStore.Get |  Avg| 11ms| 10ms | -1ms | -9.304
| |  P99| 124ms| 106ms | -18ms | -14.573
| ThreadStore.GetMembershipForUser |  Avg| 11ms| 12ms | 1ms | 9.197
| |  P99| 157ms| 160ms | 3ms | 1.907
| ThreadStore.GetTeamsUnreadForUser |  Avg| 13ms| 14ms | 1ms | 7.883
| |  P99| 173ms| 198ms | 25ms | 14.476
| ThreadStore.GetThreadFollowers |  Avg| 9ms| 10ms | 1ms | 10.716
| |  P99| 109ms| 120ms | 11ms | 10.084
| ThreadStore.GetThreadForUser |  Avg| 19ms| 20ms | 1ms | 5.180
| |  P99| 215ms| 220ms | 5ms | 2.326
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 22ms| 21ms | -1ms | -4.617
| |  P99| 185ms| 188ms | 3ms | 1.623
| ThreadStore.GetThreadsForUser |  Avg| 16ms| 18ms | 2ms | 12.319
| |  P99| 194ms| 204ms | 10ms | 5.154
| ThreadStore.GetTotalThreads |  Avg| 9ms| 10ms | 1ms | 10.611
| |  P99| 97ms| 119ms | 22ms | 22.601
| ThreadStore.GetTotalUnreadMentions |  Avg| 10ms| 11ms | 1ms | 10.152
| |  P99| 99ms| 129ms | 30ms | 30.176
| ThreadStore.GetTotalUnreadThreads |  Avg| 9ms| 10ms | 1ms | 10.597
| |  P99| 97ms| 117ms | 20ms | 20.569
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 10ms| 11ms | 1ms | 10.044
| |  P99| 100ms| 126ms | 26ms | 26.121
| ThreadStore.MaintainMembership |  Avg| 18ms| 20ms | 2ms | 10.965
| |  P99| 223ms| 234ms | 11ms | 4.942
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 11ms | 1ms | 9.924
| |  P99| 97ms| 140ms | 43ms | 44.492
| ThreadStore.MarkAllAsReadByTeam |  Avg| 10ms| 13ms | 3ms | 30.508
| |  P99| 48ms| 49ms | 1ms | 2.062
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 95ms | 7ms | 7.914
| ThreadStore.UpdateMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 94ms | 4ms | 4.445
| TokenStore.Cleanup |  Avg| 26ms| 6ms | -20ms | -76.033
| |  P99| 98ms| 24ms | -74ms | -75.510
| UserAccessTokenStore.GetByToken |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 201ms| 187ms | -14ms | -6.957
| UserStore.AnalyticsActiveCount |  Avg| 32ms| 23ms | -9ms | -28.025
| |  P99| 97ms| 25ms | -72ms | -74.227
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 22ms| 6ms | -16ms | -72.298
| |  P99| 50ms| 25ms | -25ms | -50.505
| UserStore.AutocompleteUsersInChannel |  Avg| 71ms| 75ms | 4ms | 5.634
| |  P99| 343ms| 371ms | 28ms | 8.169
| UserStore.Count |  Avg| 24ms| 25ms | 1ms | 4.141
| |  P99| 177ms| 190ms | 13ms | 7.343
| UserStore.Get |  Avg| 11ms| 12ms | 1ms | 9.102
| |  P99| 152ms| 170ms | 18ms | 11.839
| UserStore.GetAllProfiles |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 91ms | 8ms | 9.685
| UserStore.GetAllProfilesInChannel |  Avg| 316ms| 349ms | 33ms | 10.436
| |  P99| 1.707s| 2.037s | 330ms | 19.329
| UserStore.GetByUsername |  Avg| 12ms| 16ms | 4ms | 32.982
| |  P99| 156ms| 170ms | 14ms | 8.966
| UserStore.GetForLogin |  Avg| 9ms| 10ms | 1ms | 11.184
| |  P99| 97ms| 116ms | 19ms | 19.624
| UserStore.GetMany |  Avg| 13ms| 12ms | -1ms | -7.957
| |  P99| 121ms| 142ms | 21ms | 17.352
| UserStore.GetProfileByIds |  Avg| 13ms| 15ms | 2ms | 15.076
| |  P99| 183ms| 197ms | 14ms | 7.662
| UserStore.GetProfilesByUsernames |  Avg| 15ms| 16ms | 1ms | 6.750
| |  P99| 188ms| 198ms | 10ms | 5.332
| UserStore.GetProfilesInChannel |  Avg| 8ms| 15ms | 7ms | 83.690
| |  P99| 48ms| 90ms | 42ms | 88.056
| UserStore.GetProfilesNotInChannel |  Avg| 8ms| 11ms | 3ms | 36.427
| |  P99| 24ms| 48ms | 24ms | 98.101
| UserStore.GetUnreadCount |  Avg| 10ms| 11ms | 1ms | 9.905
| |  P99| 118ms| 142ms | 24ms | 20.421
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.103
| UserStore.Save |  Avg| 158ms| 164ms | 6ms | 3.801
| |  P99| 494ms| 551ms | 57ms | 11.543
| UserStore.Search |  Avg| 48ms| 50ms | 2ms | 4.203
| |  P99| 237ms| 239ms | 2ms | 0.844
| UserStore.Update |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 237ms| 248ms | 11ms | 4.643
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 10ms | 1ms | 10.975
| |  P99| 91ms| 98ms | 7ms | 7.680
| UserStore.UpdateLastLogin |  Avg| 8ms| 9ms | 1ms | 11.807
| |  P99| 79ms| 86ms | 7ms | 8.905
| UserStore.UpdateUpdateAt |  Avg| 8ms| 9ms | 1ms | 12.304
| |  P99| 71ms| 86ms | 15ms | 21.240
| UserTermsOfServiceStore.GetByUser |  Avg| 8ms| 9ms | 1ms | 11.849
| |  P99| 96ms| 114ms | 18ms | 18.802
| WebhookStore.GetOutgoingByTeam |  Avg| 15ms| 16ms | 1ms | 6.491
| |  P99| 195ms| 203ms | 8ms | 4.105
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 434ms| 532ms | 98ms | 22.605
| | P99| 2.387s| 3.281s | 894ms | 37.448
| addTeamMember | Avg| 1.211s| 1.365s | 154ms | 12.713
| | P99| 7.113s| 8.787s | 1.674s | 23.536
| autocompleteChannelsForTeamForSearch | Avg| 69ms| 68ms | -1ms | -1.454
| | P99| 411ms| 425ms | 14ms | 3.406
| autocompleteUsers | Avg| 66ms| 71ms | 5ms | 7.588
| | P99| 353ms| 385ms | 32ms | 9.055
| channelMemberCountsByGroup | Avg| 28ms| 0s | -28ms | -101.809
| | P99| 429ms| 0s | -429ms | -99.956
| createCategoryForTeamForUser | Avg| 62ms| 76ms | 14ms | 22.470
| | P99| 242ms| 245ms | 3ms | 1.241
| createChannel | Avg| 393ms| 446ms | 53ms | 13.497
| | P99| 984ms| 987ms | 3ms | 0.305
| createChannelBookmark | Avg| 35ms| 59ms | 24ms | 69.556
| | P99| 99ms| 435ms | 336ms | 341.117
| createDirectChannel | Avg| 443ms| 552ms | 109ms | 24.581
| | P99| 2.345s| 2.443s | 98ms | 4.179
| createGroupChannel | Avg| 710ms| 829ms | 119ms | 16.765
| | P99| 3.871s| 4.338s | 467ms | 12.064
| createPost | Avg| 622ms| 671ms | 49ms | 7.882
| | P99| 4.142s| 4.444s | 302ms | 7.292
| createSchedulePost | Avg| 19ms| 20ms | 1ms | 5.351
| | P99| 208ms| 214ms | 6ms | 2.885
| createUser | Avg| 354ms| 392ms | 38ms | 10.749
| | P99| 2.088s| 2.236s | 148ms | 7.088
| deleteChannelBookmark | Avg| 79ms| 75ms | -4ms | -5.051
| | P99| 244ms| 244ms | 0s | 0.000
| deleteDraft | Avg| 17ms| 18ms | 1ms | 5.975
| | P99| 212ms| 217ms | 5ms | 2.364
| deletePost | Avg| 122ms| 132ms | 10ms | 8.183
| | P99| 825ms| 948ms | 123ms | 14.908
| followThreadByUser | Avg| 60ms| 53ms | -7ms | -11.588
| | P99| 243ms| 428ms | 185ms | 76.053
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 11ms| 12ms | 1ms | 9.084
| | P99| 162ms| 182ms | 20ms | 12.310
| getAnalytics | Avg| 91ms| 104ms | 13ms | 14.211
| | P99| 243ms| 247ms | 4ms | 1.649
| getCategoriesForTeamForUser | Avg| 18ms| 19ms | 1ms | 5.572
| | P99| 212ms| 225ms | 13ms | 6.146
| getChannel | Avg| 24ms| 28ms | 4ms | 16.360
| | P99| 238ms| 261ms | 23ms | 9.670
| getChannelMember | Avg| 20ms| 22ms | 2ms | 9.946
| | P99| 231ms| 243ms | 12ms | 5.193
| getChannelMembers | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 96ms| 97ms | 1ms | 1.042
| getChannelMembersForTeamForUser | Avg| 14ms| 16ms | 2ms | 13.926
| | P99| 184ms| 198ms | 14ms | 7.606
| getChannelMembersForUser | Avg| 10ms| 12ms | 2ms | 19.223
| | P99| 99ms| 146ms | 47ms | 47.260
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 147ms| 155ms | 8ms | 5.457
| getChannelUnread | Avg| 18ms| 15ms | -3ms | -16.354
| | P99| 231ms| 200ms | -31ms | -13.401
| getChannelsForTeamForUser | Avg| 15ms| 16ms | 1ms | 6.760
| | P99| 193ms| 205ms | 12ms | 6.233
| getChannelsForUser | Avg| 9ms| 11ms | 2ms | 21.183
| | P99| 97ms| 134ms | 37ms | 38.255
| getClientConfig | Avg| 21ms| 24ms | 3ms | 14.538
| | P99| 236ms| 247ms | 11ms | 4.667
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 16ms| 19ms | 3ms | 19.003
| | P99| 199ms| 216ms | 17ms | 8.542
| getFilePreview | Avg| 71ms| 74ms | 3ms | 4.244
| | P99| 407ms| 431ms | 24ms | 5.890
| getFileThumbnail | Avg| 66ms| 69ms | 3ms | 4.549
| | P99| 370ms| 403ms | 33ms | 8.915
| getFilteredUsersStats | Avg| 19ms| 15ms | -4ms | -21.061
| | P99| 25ms| 25ms | 0s | 0.000
| getJobsByType | Avg| 11ms| 20ms | 9ms | 80.442
| | P99| 136ms| 97ms | -39ms | -28.669
| getPostThread | Avg| 69ms| 73ms | 4ms | 5.807
| | P99| 617ms| 598ms | -19ms | -3.079
| getPostsForChannel | Avg| 120ms| 128ms | 8ms | 6.683
| | P99| 1.364s| 1.588s | 224ms | 16.427
| getPostsForChannelAroundLastUnread | Avg| 50ms| 54ms | 4ms | 8.026
| | P99| 454ms| 493ms | 39ms | 8.595
| getPreferences | Avg| 11ms| 12ms | 1ms | 9.263
| | P99| 135ms| 168ms | 33ms | 24.515
| getPrevTrialLicense | Avg| 14ms| 1ms | -13ms | -92.345
| | P99| 25ms| 5ms | -20ms | -80.922
| getProfileImage | Avg| 81ms| 72ms | -9ms | -11.056
| | P99| 481ms| 479ms | -2ms | -0.416
| getPublicChannelsForTeam | Avg| 30ms| 34ms | 4ms | 13.171
| | P99| 217ms| 221ms | 4ms | 1.841
| getRolesByNames | Avg| 41ms| 0s | -41ms | -98.911
| | P99| 99ms| 5ms | -94ms | -94.950
| getServerLimits | Avg| 38ms| 17ms | -21ms | -55.479
| | P99| 98ms| 25ms | -73ms | -74.112
| getTeamMember | Avg| 11ms| 13ms | 2ms | 18.308
| | P99| 160ms| 194ms | 34ms | 21.249
| getTeamMembersForUser | Avg| 10ms| 11ms | 1ms | 9.769
| | P99| 137ms| 164ms | 27ms | 19.769
| getTeamScheduledPosts | Avg| 17ms| 19ms | 2ms | 11.607
| | P99| 211ms| 225ms | 14ms | 6.635
| getTeamStats | Avg| 66ms| 94ms | 28ms | 42.485
| | P99| 241ms| 245ms | 4ms | 1.662
| getTeamsForUser | Avg| 9ms| 10ms | 1ms | 10.640
| | P99| 103ms| 142ms | 39ms | 37.704
| getTeamsUnreadForUser | Avg| 18ms| 21ms | 3ms | 16.447
| | P99| 225ms| 238ms | 13ms | 5.789
| getThreadsForUser | Avg| 17ms| 18ms | 1ms | 6.049
| | P99| 204ms| 214ms | 10ms | 4.913
| getUser | Avg| 16ms| 19ms | 3ms | 18.967
| | P99| 233ms| 253ms | 20ms | 8.593
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 3ms| 4ms | 1ms | 30.767
| | P99| 82ms| 95ms | 13ms | 15.813
| getUsers | Avg| 14ms| 16ms | 2ms | 14.260
| | P99| 224ms| 243ms | 19ms | 8.484
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 49ms| 58ms | 9ms | 18.442
| getUsersByNames | Avg| 15ms| 17ms | 2ms | 12.940
| | P99| 195ms| 205ms | 10ms | 5.127
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 11ms| 12ms | 1ms | 9.361
| | P99| 146ms| 173ms | 27ms | 18.530
| listCPAValues | Avg| 15ms| 16ms | 1ms | 6.719
| | P99| 208ms| 204ms | -4ms | -1.923
| listChannelBookmarksForChannel | Avg| 12ms| 13ms | 1ms | 8.478
| | P99| 168ms| 186ms | 18ms | 10.729
| login | Avg| 184ms| 200ms | 16ms | 8.702
| | P99| 1.877s| 2.024s | 147ms | 7.834
| logout | Avg| 127ms| 110ms | -17ms | -13.393
| | P99| 1.54s| 477ms | -1.063s | -69.017
| patchPost | Avg| 100ms| 115ms | 15ms | 14.981
| | P99| 730ms| 995ms | 265ms | 36.297
| removeUserCustomStatus | Avg| 281ms| 320ms | 39ms | 13.883
| | P99| 1.395s| 1.81s | 415ms | 29.745
| root | Avg| 11ms| 13ms | 2ms | 18.197
| | P99| 198ms| 218ms | 20ms | 10.080
| saveReaction | Avg| 40ms| 45ms | 5ms | 12.468
| | P99| 385ms| 420ms | 35ms | 9.082
| searchAllChannels | Avg| 52ms| 52ms | 0s | 0.000
| | P99| 246ms| 245ms | -1ms | -0.406
| searchGroupChannels | Avg| 17ms| 19ms | 2ms | 11.543
| | P99| 204ms| 217ms | 13ms | 6.361
| searchPostsInTeam | Avg| 179ms| 125ms | -54ms | -30.098
| | P99| 2.306s| 3.137s | 831ms | 36.031
| searchUsers | Avg| 50ms| 52ms | 2ms | 4.040
| | P99| 239ms| 242ms | 3ms | 1.253
| setPostReminder | Avg| 64ms| 57ms | -7ms | -10.907
| | P99| 444ms| 449ms | 5ms | 1.127
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 63ms| 59ms | -4ms | -6.315
| | P99| 469ms| 457ms | -12ms | -2.559
| updateCategoriesForTeamForUser | Avg| 134ms| 189ms | 55ms | 40.919
| | P99| 914ms| 2.136s | 1.222s | 133.734
| updateChannelBookmark | Avg| 74ms| 57ms | -17ms | -22.893
| | P99| 482ms| 457ms | -25ms | -5.181
| updateChannelBookmarkSortOrder | Avg| 86ms| 25ms | -61ms | -71.156
| | P99| 480ms| 235ms | -245ms | -51.042
| updatePreferences | Avg| 39ms| 43ms | 4ms | 10.209
| | P99| 399ms| 422ms | 23ms | 5.762
| updateReadStateAllThreadsByUser | Avg| 10ms| 13ms | 3ms | 30.246
| | P99| 48ms| 49ms | 1ms | 2.062
| updateReadStateThreadByUser | Avg| 144ms| 146ms | 2ms | 1.386
| | P99| 963ms| 951ms | -12ms | -1.247
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 19ms| 5ms | -14ms | -73.093
| uploadFileStream | Avg| 552ms| 538ms | -14ms | -2.537
| | P99| 2.23s| 2.232s | 2ms | 0.090
| upsertDraft | Avg| 18ms| 20ms | 2ms | 11.185
| | P99| 214ms| 225ms | 11ms | 5.148
| viewChannel | Avg| 48ms| 53ms | 5ms | 10.473
| | P99| 469ms| 485ms | 16ms | 3.413

### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 4ms | 537ms | 533ms | 13889.11
| TeamStore.AnalyticsTeamCount | avg | 3ms | 13ms | 10ms | 296.36
| DesktopTokensStore.DeleteOlderThan | avg | 12ms | 39ms | 27ms | 221.33
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 20ms | 56ms | 36ms | 178.83
| BotStore.Get | avg | 4ms | 11ms | 7ms | 177.11
| ChannelStore.CreateSidebarCategory | avg | 49ms | 101ms | 52ms | 105.60
| PostStore.AnalyticsPostCount | avg | 257ms | 514ms | 257ms | 99.86
| LinkMetadataStore.Save | avg | 5ms | 10ms | 5ms | 91.59
| EmojiStore.GetMultipleByName | avg | 7ms | 13ms | 6ms | 81.30
| RoleStore.GetByNames | avg | 15ms | 26ms | 11ms | 71.84
| PostPersistentNotificationStore.Get | avg | 7ms | 11ms | 4ms | 57.23
| PostPersistentNotificationStore.DeleteExpired | avg | 7ms | 11ms | 4ms | 56.99
| PostStore.GetPostReminders | avg | 6ms | 9ms | 3ms | 51.05
| PostStore.Delete | avg | 46ms | 67ms | 21ms | 46.10
| ChannelBookmarkStore.UpdateSortOrder | avg | 16ms | 23ms | 7ms | 44.02
| ScheduledPostStore.GetPendingScheduledPosts | avg | 12ms | 17ms | 5ms | 41.20
| RoleStore.ChannelHigherScopedPermissions | avg | 10ms | 14ms | 4ms | 39.81
| UserAccessTokenStore.GetByToken | avg | 11ms | 15ms | 4ms | 36.64
| PostStore.AnalyticsPostCountByTeam | avg | 10ms | 13ms | 3ms | 29.59
| ChannelStore.GetMembers | avg | 18ms | 23ms | 5ms | 28.15
| ScheduledPostStore.CreateScheduledPost | avg | 11ms | 14ms | 3ms | 27.66
| JobStore.GetAllByTypePage | avg | 13ms | 16ms | 3ms | 22.97
| PostStore.GetPostReminderMetadata | avg | 13ms | 16ms | 3ms | 22.63
| ChannelStore.GetPublicChannelsForTeam | avg | 27ms | 33ms | 6ms | 21.91
| ThreadStore.Get | avg | 9ms | 11ms | 2ms | 21.65
| JobStore.UpdateStatusOptimistically | avg | 11ms | 13ms | 2ms | 18.92
| JobStore.GetCountByStatusAndType | avg | 11ms | 13ms | 2ms | 18.21
| ChannelStore.GetPinnedPostCount | avg | 11ms | 13ms | 2ms | 17.74
| JobStore.Save | avg | 11ms | 13ms | 2ms | 17.48
| PreferenceStore.DeleteCategoryAndName | avg | 12ms | 14ms | 2ms | 16.22
| ChannelStore.SearchGroupChannels | avg | 15ms | 17ms | 2ms | 13.14
| ChannelStore.CreateDirectChannel | avg | 86ms | 97ms | 11ms | 12.74
| ChannelStore.AutocompleteInTeamForSearch | avg | 68ms | 76ms | 8ms | 11.74
| ChannelStore.Get | avg | 20ms | 22ms | 2ms | 9.87
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 20ms | 22ms | 2ms | 9.85
| PostStore.SearchPostsForUser | avg | 298ms | 323ms | 25ms | 8.40
| PostStore.Get | avg | 28ms | 30ms | 2ms | 7.22
| PostStore.Save | avg | 41ms | 43ms | 2ms | 4.82
| UserStore.Search | avg | 48ms | 50ms | 2ms | 4.12
| TeamStore.GetActiveMemberCount | avg | 74ms | 77ms | 3ms | 4.06
| UserStore.GetAllProfilesInChannel | avg | 396ms | 412ms | 16ms | 4.04
| TeamStore.GetTotalMemberCount | avg | 68ms | 70ms | 2ms | 2.93
| ChannelStore.SaveMember | avg | 73ms | 75ms | 2ms | 2.74
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 5ms | 992ms | 987ms | 19932.48
| BotStore.Get | p99 | 24ms | 184ms | 160ms | 671.42
| PostStore.GetPostReminders | p99 | 24ms | 77ms | 53ms | 222.69
| LinkMetadataStore.Save | p99 | 23ms | 69ms | 46ms | 199.57
| TeamStore.AnalyticsTeamCount | p99 | 10ms | 25ms | 15ms | 152.98
| LicenseStore.GetAll | p99 | 10ms | 24ms | 14ms | 142.13
| ChannelStore.GetMembers | p99 | 96ms | 232ms | 136ms | 141.67
| JobStore.UpdateStatusOptimistically | p99 | 68ms | 142ms | 74ms | 108.42
| UserAccessTokenStore.GetByToken | p99 | 92ms | 189ms | 97ms | 105.43
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 90ms | 182ms | 92ms | 102.22
| ChannelStore.CreateSidebarCategory | p99 | 237ms | 477ms | 240ms | 101.48
| DesktopTokensStore.DeleteOlderThan | p99 | 25ms | 50ms | 25ms | 100.60
| PostStore.AnalyticsPostCount | p99 | 497ms | 990ms | 493ms | 99.26
| JobStore.GetAllByTypePage | p99 | 95ms | 188ms | 93ms | 98.15
| EmojiStore.GetMultipleByName | p99 | 47ms | 92ms | 45ms | 95.74
| ClusterDiscoveryStore.SetLastPingAt | p99 | 100ms | 184ms | 84ms | 84.18
| RoleStore.ChannelHigherScopedPermissions | p99 | 50ms | 91ms | 41ms | 82.70
| RoleStore.GetByNames | p99 | 91ms | 153ms | 62ms | 67.81
| StatusStore.UpdateExpiredDNDStatuses | p99 | 100ms | 165ms | 65ms | 65.14
| PostPersistentNotificationStore.DeleteExpired | p99 | 89ms | 140ms | 51ms | 57.30
| ThreadStore.Get | p99 | 100ms | 152ms | 52ms | 52.09
| ChannelStore.CreateDirectChannel | p99 | 489ms | 717ms | 228ms | 46.65
| ScheduledPostStore.CreateScheduledPost | p99 | 68ms | 99ms | 31ms | 45.75
| ChannelStore.GetPinnedPostCount | p99 | 119ms | 169ms | 50ms | 41.93
| ChannelStore.GetFileCount | p99 | 98ms | 130ms | 32ms | 32.52
| ChannelStore.Save | p99 | 344ms | 449ms | 105ms | 30.54
| TeamStore.Get | p99 | 99ms | 126ms | 27ms | 27.16
| PostStore.GetSingle | p99 | 105ms | 131ms | 26ms | 24.67
| ChannelStore.SearchGroupChannels | p99 | 155ms | 193ms | 38ms | 24.48
| ChannelStore.GetMany | p99 | 222ms | 273ms | 51ms | 23.02
| PostAcknowledgementStore.GetForPost | p99 | 99ms | 121ms | 22ms | 22.19
| DraftStore.GetDraftsForUser | p99 | 163ms | 199ms | 36ms | 22.06
| UserStore.GetUnreadCount | p99 | 115ms | 140ms | 25ms | 21.71
| LinkMetadataStore.Get | p99 | 111ms | 135ms | 24ms | 21.68
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 111ms | 135ms | 24ms | 21.61
| PostPriorityStore.GetForPostWithContext | p99 | 99ms | 119ms | 20ms | 20.20
| JobStore.GetNewestJobByStatusesAndType | p99 | 89ms | 105ms | 16ms | 17.91
| ThreadStore.GetMembershipForUser | p99 | 129ms | 152ms | 23ms | 17.78
| UserStore.Get | p99 | 117ms | 137ms | 20ms | 17.15
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 99ms | 116ms | 17ms | 17.13
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 100ms | 117ms | 17ms | 17.05
| ThreadStore.GetTotalUnreadMentions | p99 | 99ms | 115ms | 16ms | 16.18
| ChannelStore.GetAllChannelMembersForUser | p99 | 115ms | 132ms | 17ms | 14.80
| JobStore.Save | p99 | 155ms | 177ms | 22ms | 14.22
| PreferenceStore.Get | p99 | 122ms | 138ms | 16ms | 13.14
| PostPersistentNotificationStore.GetSingle | p99 | 99ms | 112ms | 13ms | 13.09
| DraftStore.Upsert | p99 | 102ms | 115ms | 13ms | 12.77
| UserStore.GetByUsername | p99 | 138ms | 155ms | 17ms | 12.29
| GroupStore.GetGroups | p99 | 132ms | 148ms | 16ms | 12.09
| StatusStore.Get | p99 | 128ms | 143ms | 15ms | 11.71
| ChannelStore.GetBoardChannel | p99 | 138ms | 154ms | 16ms | 11.60
| PostStore.SearchPostsForUser | p99 | 3.902s | 4.347s | 445ms | 11.41
| PreferenceStore.GetAll | p99 | 98ms | 109ms | 11ms | 11.20
| ChannelStore.GetPublicChannelsForTeam | p99 | 211ms | 234ms | 23ms | 10.91
| ChannelStore.SaveMember | p99 | 550ms | 609ms | 59ms | 10.73
| PostStore.GetPostReminderMetadata | p99 | 96ms | 106ms | 10ms | 10.38
| ThreadStore.GetThreadFollowers | p99 | 127ms | 140ms | 13ms | 10.21
| ChannelStore.AutocompleteInTeamForSearch | p99 | 369ms | 405ms | 36ms | 9.75
| PostStore.GetPostsBefore | p99 | 158ms | 173ms | 15ms | 9.48
| ChannelStore.GetMembersForUser | p99 | 160ms | 175ms | 15ms | 9.36
| ThreadStore.MarkAllAsReadByChannels | p99 | 89ms | 97ms | 8ms | 9.01
| FileInfoStore.Get | p99 | 145ms | 158ms | 13ms | 8.97
| UserStore.GetProfileByIds | p99 | 161ms | 174ms | 13ms | 8.09
| ChannelStore.GetByName | p99 | 114ms | 123ms | 9ms | 7.88
| ThreadStore.GetTeamsUnreadForUser | p99 | 178ms | 192ms | 14ms | 7.85
| PostStore.GetEtag | p99 | 155ms | 167ms | 12ms | 7.74
| UserStore.GetProfilesByUsernames | p99 | 155ms | 167ms | 12ms | 7.72
| DraftStore.Get | p99 | 181ms | 194ms | 13ms | 7.19
| EmojiStore.GetByName | p99 | 124ms | 132ms | 8ms | 6.43
| WebhookStore.GetOutgoingByTeam | p99 | 187ms | 199ms | 12ms | 6.43
| UserStore.GetAllProfiles | p99 | 80ms | 85ms | 5ms | 6.24
| TeamStore.GetTeamsByUserId | p99 | 98ms | 104ms | 6ms | 6.15
| UserStore.Count | p99 | 157ms | 166ms | 9ms | 5.72
| StatusStore.GetByIds | p99 | 193ms | 204ms | 11ms | 5.70
| ChannelStore.GetTeamChannels | p99 | 225ms | 237ms | 12ms | 5.35
| ChannelStore.GetChannels | p99 | 171ms | 180ms | 9ms | 5.28
| UserStore.Update | p99 | 215ms | 226ms | 11ms | 5.11
| PostStore.GetPostsAfter | p99 | 157ms | 165ms | 8ms | 5.10
| PostStore.GetPostsByThread | p99 | 141ms | 148ms | 7ms | 4.96
| PostPersistentNotificationStore.Get | p99 | 84ms | 88ms | 4ms | 4.79
| ThreadStore.GetThreadForUser | p99 | 218ms | 227ms | 9ms | 4.14
| ThreadStore.GetThreadsForUser | p99 | 176ms | 183ms | 7ms | 3.97
| UserStore.UpdateLastLogin | p99 | 77ms | 80ms | 3ms | 3.87
| PostStore.Save | p99 | 365ms | 379ms | 14ms | 3.84
| PostAcknowledgementStore.GetForPosts | p99 | 223ms | 231ms | 8ms | 3.59
| PostPriorityStore.GetForPosts | p99 | 225ms | 233ms | 8ms | 3.56
| ChannelStore.CreateInitialSidebarCategories | p99 | 375ms | 388ms | 13ms | 3.47
| ChannelStore.GetMember | p99 | 93ms | 96ms | 3ms | 3.23
| ChannelStore.GetForPost | p99 | 188ms | 194ms | 6ms | 3.19
| UserTermsOfServiceStore.GetByUser | p99 | 95ms | 98ms | 3ms | 3.14
| PropertyGroupStore.Get | p99 | 96ms | 99ms | 3ms | 3.11
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 99ms | 102ms | 3ms | 3.02
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 205ms | 210ms | 5ms | 2.44
| SessionStore.Get | p99 | 210ms | 215ms | 5ms | 2.38
| PostStore.GetPostIdBeforeTime | p99 | 86ms | 88ms | 2ms | 2.32
| TeamStore.GetMember | p99 | 86ms | 88ms | 2ms | 2.32
| ChannelStore.GetMemberForPost | p99 | 220ms | 225ms | 5ms | 2.27
| PostStore.GetPostsSince | p99 | 220ms | 225ms | 5ms | 2.27
| ChannelStore.GetMemberLastViewedAt | p99 | 91ms | 93ms | 2ms | 2.20
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 91ms | 93ms | 2ms | 2.19
| UserStore.GetAllProfilesInChannel | p99 | 2.154s | 2.201s | 47ms | 2.18
| UserStore.GetMany | p99 | 92ms | 94ms | 2ms | 2.17
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 93ms | 95ms | 2ms | 2.15
| JobStore.UpdateOptimistically | p99 | 96ms | 98ms | 2ms | 2.08
| TeamStore.GetTeamsForUser | p99 | 97ms | 99ms | 2ms | 2.07
| ChannelStore.Get | p99 | 222ms | 226ms | 4ms | 1.80
| ThreadStore.MaintainMembership | p99 | 222ms | 226ms | 4ms | 1.80
| SessionStore.Save | p99 | 174ms | 177ms | 3ms | 1.72
| ChannelBookmarkStore.Save | p99 | 238ms | 242ms | 4ms | 1.68
| PostStore.Get | p99 | 242ms | 246ms | 4ms | 1.65
| ChannelStore.GetMemberCount | p99 | 218ms | 221ms | 3ms | 1.38
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 221ms | 224ms | 3ms | 1.36
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.Get | avg | 3ms | 0s | -3ms | -103.88
| RetentionPolicyStore.GetAll | avg | 9ms | 0s | -9ms | -103.45
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | avg | 4ms | 0s | -4ms | -101.77
| FileInfoStore.DeleteForPost | avg | 147ms | 0s | -147ms | -100.27
| ChannelStore.GetMemberCountsByGroup | avg | 17ms | 0s | -17ms | -98.13
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 22ms | 3ms | -19ms | -87.23
| SchemeStore.GetAllPage | avg | 6ms | 1ms | -5ms | -79.74
| ThreadStore.MarkAllAsReadByTeam | avg | 18ms | 8ms | -10ms | -55.27
| UserStore.GetProfilesInChannel | avg | 22ms | 10ms | -12ms | -54.42
| SessionStore.GetSessionsExpired | avg | 13ms | 6ms | -7ms | -53.05
| TemporaryPostStore.GetExpiredPosts | avg | 21ms | 11ms | -10ms | -48.53
| ChannelStore.AnalyticsCountAll | avg | 56ms | 30ms | -26ms | -46.52
| UserStore.AnalyticsGetInactiveUsersCount | avg | 32ms | 18ms | -14ms | -44.09
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 13ms | 8ms | -5ms | -39.54
| UserStore.GetProfilesNotInChannel | avg | 16ms | 11ms | -5ms | -31.80
| ProductNoticesStore.ClearOldNotices | avg | 59ms | 42ms | -17ms | -28.65
| CommandWebhookStore.Cleanup | avg | 18ms | 13ms | -5ms | -27.22
| JobStore.UpdateStatus | avg | 13ms | 10ms | -3ms | -23.27
| ChannelBookmarkStore.Delete | avg | 24ms | 19ms | -5ms | -20.96
| ChannelStore.GetMany | avg | 27ms | 22ms | -5ms | -18.80
| FileInfoStore.GetForPost | avg | 11ms | 9ms | -2ms | -18.16
| ChannelStore.GetSidebarCategory | avg | 32ms | 28ms | -4ms | -12.32
| ChannelStore.UpdateSidebarCategories | avg | 133ms | 121ms | -12ms | -9.01
| PostStore.Update | avg | 40ms | 37ms | -3ms | -7.44
| UserStore.AnalyticsActiveCount | avg | 40ms | 38ms | -2ms | -5.02
| UserStore.Save | avg | 178ms | 173ms | -5ms | -2.81
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 10ms | 0s | -10ms | -100.50
| FileInfoStore.DeleteForPost | p99 | 249ms | 0s | -249ms | -100.20
| ChannelStore.GetMemberCountsByGroup | p99 | 171ms | 0s | -171ms | -99.78
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 50ms | 5ms | -45ms | -90.91
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 244ms | 49ms | -195ms | -79.92
| UserStore.GetProfilesInChannel | p99 | 392ms | 79ms | -313ms | -79.75
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 107ms | 25ms | -82ms | -76.29
| ThreadStore.MarkAllAsReadByTeam | p99 | 96ms | 24ms | -72ms | -74.61
| SessionStore.GetSessionsExpired | p99 | 92ms | 45ms | -47ms | -51.09
| SchemeStore.GetAllPage | p99 | 10ms | 5ms | -5ms | -50.25
| ChannelStore.AnalyticsCountAll | p99 | 99ms | 50ms | -49ms | -49.49
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 50ms | -49ms | -49.37
| UserStore.AnalyticsActiveCount | p99 | 98ms | 50ms | -48ms | -48.98
| PostStore.AnalyticsPostCountByTeam | p99 | 49ms | 25ms | -24ms | -48.98
| TemporaryPostStore.GetExpiredPosts | p99 | 96ms | 49ms | -47ms | -48.96
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 94ms | 49ms | -45ms | -47.96
| SessionStore.Remove | p99 | 152ms | 80ms | -72ms | -47.21
| ChannelStore.GetSidebarCategory | p99 | 379ms | 246ms | -133ms | -35.11
| ReactionStore.GetForPost | p99 | 135ms | 97ms | -38ms | -28.07
| JobStore.UpdateStatus | p99 | 97ms | 76ms | -21ms | -21.58
| PostStore.Update | p99 | 301ms | 240ms | -61ms | -20.28
| FileInfoStore.Save | p99 | 124ms | 103ms | -21ms | -16.98
| PreferenceStore.DeleteCategoryAndName | p99 | 94ms | 81ms | -13ms | -13.85
| PostStore.Delete | p99 | 454ms | 405ms | -49ms | -10.80
| FileInfoStore.GetForPost | p99 | 99ms | 90ms | -9ms | -9.06
| FileInfoStore.GetByIds | p99 | 183ms | 169ms | -14ms | -7.65
| JobStore.GetAllByStatus | p99 | 191ms | 179ms | -12ms | -6.29
| UserStore.Save | p99 | 558ms | 523ms | -35ms | -6.28
| ChannelStore.GetMembersForUserWithPagination | p99 | 104ms | 98ms | -6ms | -5.79
| ChannelStore.UpdateSidebarCategories | p99 | 919ms | 875ms | -44ms | -4.79
| FileInfoStore.AttachToPost | p99 | 201ms | 193ms | -8ms | -3.98
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 80ms | 77ms | -3ms | -3.75
| UserStore.GetProfilesNotInChannel | p99 | 94ms | 91ms | -3ms | -3.18
| FileInfoStore.SetContent | p99 | 230ms | 224ms | -6ms | -2.61
| ThreadStore.MarkAsRead | p99 | 91ms | 89ms | -2ms | -2.21
| GroupStore.GetByName | p99 | 91ms | 89ms | -2ms | -2.19
| JobStore.GetCountByStatusAndType | p99 | 97ms | 95ms | -2ms | -2.06
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPropertyFields | avg | 20ms | 43ms | 23ms | 112.61
| createCategoryForTeamForUser | avg | 59ms | 115ms | 56ms | 94.79
| deletePost | avg | 76ms | 129ms | 53ms | 69.99
| getChannelMembers | avg | 19ms | 27ms | 8ms | 43.09
| logout | avg | 131ms | 161ms | 30ms | 22.99
| getJobsByType | avg | 13ms | 16ms | 3ms | 22.72
| getChannel | avg | 23ms | 28ms | 5ms | 21.90
| getServerLimits | avg | 35ms | 42ms | 7ms | 19.98
| createSchedulePost | avg | 16ms | 19ms | 3ms | 18.61
| setPostReminder | avg | 121ms | 143ms | 22ms | 18.21
| getPublicChannelsForTeam | avg | 29ms | 34ms | 5ms | 17.11
| getDrafts | avg | 16ms | 18ms | 2ms | 12.67
| autocompleteChannelsForTeamForSearch | avg | 68ms | 76ms | 8ms | 11.71
| createDirectChannel | avg | 562ms | 627ms | 65ms | 11.57
| updateChannelBookmarkSortOrder | avg | 36ms | 40ms | 4ms | 11.17
| getPostsForChannel | avg | 152ms | 166ms | 14ms | 9.19
| patchPost | avg | 117ms | 127ms | 10ms | 8.55
| searchPostsInTeam | avg | 326ms | 353ms | 27ms | 8.27
| listCPAValues | avg | 25ms | 27ms | 2ms | 7.90
| viewChannel | avg | 65ms | 69ms | 4ms | 6.19
| getPostThread | avg | 67ms | 71ms | 4ms | 6.00
| addChannelMember | avg | 525ms | 556ms | 31ms | 5.90
| followThreadByUser | avg | 61ms | 64ms | 3ms | 4.93
| updatePreferences | avg | 44ms | 46ms | 2ms | 4.51
| updateReadStateThreadByUser | avg | 137ms | 143ms | 6ms | 4.36
| createGroupChannel | avg | 962ms | 999ms | 37ms | 3.85
| removeUserCustomStatus | avg | 367ms | 381ms | 14ms | 3.82
| createPost | avg | 704ms | 727ms | 23ms | 3.27
| addTeamMember | avg | 1.391s | 1.409s | 18ms | 1.29
| createUser | avg | 410ms | 415ms | 5ms | 1.22
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmarkSortOrder | p99 | 96ms | 240ms | 144ms | 149.90
| getChannelMembers | p99 | 96ms | 232ms | 136ms | 141.67
| logout | p99 | 1.525s | 3.025s | 1.5s | 98.35
| getJobsByType | p99 | 95ms | 188ms | 93ms | 98.15
| createCategoryForTeamForUser | p99 | 243ms | 478ms | 235ms | 96.61
| deletePost | p99 | 469ms | 905ms | 436ms | 92.93
| getPreferences | p99 | 110ms | 139ms | 29ms | 26.46
| searchGroupChannels | p99 | 163ms | 198ms | 35ms | 21.42
| getTeamsForUser | p99 | 99ms | 118ms | 19ms | 19.12
| followThreadByUser | p99 | 685ms | 815ms | 130ms | 18.98
| getTeamMembersForUser | p99 | 124ms | 146ms | 22ms | 17.67
| getDrafts | p99 | 189ms | 221ms | 32ms | 16.93
| getPropertyFields | p99 | 210ms | 244ms | 34ms | 16.23
| setPostReminder | p99 | 1.585s | 1.78s | 195ms | 12.30
| viewChannel | p99 | 624ms | 697ms | 73ms | 11.71
| listChannelBookmarksForChannel | p99 | 147ms | 164ms | 17ms | 11.54
| autocompleteChannelsForTeamForSearch | p99 | 369ms | 410ms | 41ms | 11.10
| getUsersByIds | p99 | 48ms | 53ms | 5ms | 10.31
| patchPost | p99 | 901ms | 973ms | 72ms | 7.99
| getChannelMembersForTeamForUser | p99 | 171ms | 184ms | 13ms | 7.61
| getPostThread | p99 | 642ms | 690ms | 48ms | 7.48
| searchPostsInTeam | p99 | 4.173s | 4.462s | 289ms | 6.93
| unfollowThreadByUser | p99 | 415ms | 443ms | 28ms | 6.74
| getPostsForChannel | p99 | 2.108s | 2.242s | 134ms | 6.36
| getAllTeams | p99 | 148ms | 157ms | 9ms | 6.08
| getPublicChannelsForTeam | p99 | 221ms | 234ms | 13ms | 5.88
| getUsersByNames | p99 | 172ms | 182ms | 10ms | 5.80
| getUserStatusesByIds | p99 | 87ms | 92ms | 5ms | 5.75
| deleteDraft | p99 | 198ms | 209ms | 11ms | 5.56
| createSchedulePost | p99 | 153ms | 161ms | 8ms | 5.22
| getChannelsForTeamForUser | p99 | 181ms | 190ms | 9ms | 4.96
| autocompleteUsers | p99 | 357ms | 372ms | 15ms | 4.20
| getChannelStats | p99 | 127ms | 132ms | 5ms | 3.95
| upsertDraft | p99 | 201ms | 208ms | 7ms | 3.49
| getPostsForChannelAroundLastUnread | p99 | 478ms | 494ms | 16ms | 3.34
| getTeamScheduledPosts | p99 | 210ms | 217ms | 7ms | 3.33
| listCPAFields | p99 | 219ms | 226ms | 7ms | 3.19
| getServerLimits | p99 | 96ms | 99ms | 3ms | 3.12
| getFileThumbnail | p99 | 357ms | 367ms | 10ms | 2.80
| getTeamsUnreadForUser | p99 | 230ms | 236ms | 6ms | 2.61
| getThreadsForUser | p99 | 197ms | 202ms | 5ms | 2.53
| createGroupChannel | p99 | 4.501s | 4.614s | 113ms | 2.51
| addTeamMember | p99 | 8.387s | 8.586s | 199ms | 2.37
| saveReaction | p99 | 423ms | 433ms | 10ms | 2.37
| createPost | p99 | 4.395s | 4.471s | 76ms | 1.73
| getFilePreview | p99 | 398ms | 404ms | 6ms | 1.51
| getCategoriesForTeamForUser | p99 | 215ms | 218ms | 3ms | 1.39
| getClientConfig | p99 | 232ms | 235ms | 3ms | 1.29
| getChannelMember | p99 | 232ms | 235ms | 3ms | 1.29
| getUsers | p99 | 236ms | 239ms | 3ms | 1.27
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -123.28
| deleteScheduledPost | avg | 10ms | 0s | -10ms | -101.61
| getRolesByNames | avg | 7ms | 0s | -7ms | -100.81
| getUsersByGroupChannelIds | avg | 36ms | 0s | -36ms | -100.63
| getSystemPropertyValues | avg | 22ms | 0s | -22ms | -99.29
| channelMemberCountsByGroup | avg | 20ms | 0s | -20ms | -97.88
| getPrevTrialLicense | avg | 34ms | 5ms | -29ms | -85.37
| deleteChannelBookmark | avg | 83ms | 16ms | -67ms | -81.16
| getProductNotices | avg | 119ms | 27ms | -92ms | -77.14
| updateReadStateAllThreadsByUser | avg | 27ms | 8ms | -19ms | -71.41
| getGroups | avg | 23ms | 12ms | -11ms | -48.80
| handleCheckCWSConnection | avg | 70ms | 48ms | -22ms | -31.22
| getFilteredUsersStats | avg | 23ms | 16ms | -7ms | -30.75
| createChannel | avg | 616ms | 442ms | -174ms | -28.26
| updateChannelBookmark | avg | 70ms | 56ms | -14ms | -19.97
| getAnalytics | avg | 180ms | 153ms | -27ms | -14.97
| login | avg | 202ms | 173ms | -29ms | -14.34
| updateCategoriesForTeamForUser | avg | 214ms | 187ms | -27ms | -12.64
| getProfileImage | avg | 80ms | 73ms | -7ms | -8.80
| createChannelBookmark | avg | 54ms | 51ms | -3ms | -5.54
| uploadFileStream | avg | 572ms | 549ms | -23ms | -4.02
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| deleteScheduledPost | p99 | 10ms | 0s | -10ms | -100.50
| getUsersByGroupChannelIds | p99 | 50ms | 0s | -50ms | -100.50
| getSystemPropertyValues | p99 | 201ms | 0s | -201ms | -100.25
| channelMemberCountsByGroup | p99 | 208ms | 0s | -208ms | -100.12
| updateReadStateAllThreadsByUser | p99 | 229ms | 24ms | -205ms | -89.52
| getRolesByNames | p99 | 48ms | 5ms | -43ms | -89.12
| getProductNotices | p99 | 249ms | 50ms | -199ms | -80.08
| deleteChannelBookmark | p99 | 246ms | 49ms | -197ms | -80.00
| getPrevTrialLicense | p99 | 99ms | 25ms | -74ms | -74.75
| handleCheckCWSConnection | p99 | 246ms | 99ms | -147ms | -59.70
| createChannel | p99 | 2.372s | 988ms | -1.384s | -58.34
| updateCategoriesForTeamForUser | p99 | 2.015s | 989ms | -1.026s | -50.92
| getAnalytics | p99 | 492ms | 249ms | -243ms | -49.34
| getFilteredUsersStats | p99 | 49ms | 25ms | -24ms | -48.73
| getGroups | p99 | 49ms | 25ms | -24ms | -48.60
| login | p99 | 1.732s | 976ms | -756ms | -43.66
| createChannelBookmark | p99 | 398ms | 243ms | -155ms | -38.99
| getChannelMembersForUser | p99 | 121ms | 100ms | -21ms | -17.34
| getTeamMember | p99 | 136ms | 131ms | -5ms | -3.67
| getChannel | p99 | 239ms | 233ms | -6ms | -2.51
| updateChannelBookmark | p99 | 245ms | 240ms | -5ms | -2.04
| uploadFileStream | p99 | 2.257s | 2.216s | -41ms | -1.82
| getProfileImage | p99 | 484ms | 477ms | -7ms | -1.45
| updatePreferences | p99 | 376ms | 371ms | -5ms | -1.33
| searchAllChannels | p99 | 246ms | 243ms | -3ms | -1.22
| listCPAValues | p99 | 248ms | 245ms | -3ms | -1.21
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 88ms| 89ms | 1ms | 1.135
| BotStore.Get |  Avg| 4ms| 11ms | 7ms | 177.106
| |  P99| 24ms| 184ms | 160ms | 671.423
| ChannelBookmarkStore.Delete |  Avg| 24ms| 19ms | -5ms | -20.965
| |  P99| 96ms| 95ms | -1ms | -1.042
| ChannelBookmarkStore.Get |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 95ms| 94ms | -1ms | -1.055
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 116ms | 17ms | 17.127
| ChannelBookmarkStore.Save |  Avg| 39ms| 39ms | 0s | 0.000
| |  P99| 238ms| 242ms | 4ms | 1.678
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 16ms| 23ms | 7ms | 44.016
| |  P99| 95ms| 96ms | 1ms | 1.053
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 76ms| 77ms | 1ms | 1.316
| ChannelStore.AnalyticsCountAll |  Avg| 56ms| 30ms | -26ms | -46.521
| |  P99| 99ms| 50ms | -49ms | -49.495
| ChannelStore.Autocomplete |  Avg| 52ms| 53ms | 1ms | 1.941
| |  P99| 243ms| 242ms | -1ms | -0.411
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 68ms| 76ms | 8ms | 11.745
| |  P99| 369ms| 405ms | 36ms | 9.750
| ChannelStore.CreateDirectChannel |  Avg| 86ms| 97ms | 11ms | 12.744
| |  P99| 489ms| 717ms | 228ms | 46.647
| ChannelStore.CreateInitialSidebarCategories |  Avg| 43ms| 44ms | 1ms | 2.333
| |  P99| 375ms| 388ms | 13ms | 3.468
| ChannelStore.CreateSidebarCategory |  Avg| 49ms| 101ms | 52ms | 105.598
| |  P99| 237ms| 477ms | 240ms | 101.480
| ChannelStore.Get |  Avg| 20ms| 22ms | 2ms | 9.873
| |  P99| 222ms| 226ms | 4ms | 1.803
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 14ms | 1ms | 7.484
| |  P99| 115ms| 132ms | 17ms | 14.795
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 22ms | 2ms | 9.847
| |  P99| 221ms| 224ms | 3ms | 1.358
| ChannelStore.GetBoardChannel |  Avg| 12ms| 13ms | 1ms | 8.498
| |  P99| 138ms| 154ms | 16ms | 11.595
| ChannelStore.GetByName |  Avg| 12ms| 13ms | 1ms | 8.048
| |  P99| 114ms| 123ms | 9ms | 7.883
| ChannelStore.GetChannelUnread |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 178ms| 179ms | 1ms | 0.562
| ChannelStore.GetChannels |  Avg| 14ms| 15ms | 1ms | 7.284
| |  P99| 171ms| 180ms | 9ms | 5.278
| ChannelStore.GetChannelsByUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 96ms | 1ms | 1.050
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 11ms | 1ms | 10.055
| |  P99| 100ms| 117ms | 17ms | 17.045
| ChannelStore.GetFileCount |  Avg| 12ms| 13ms | 1ms | 8.199
| |  P99| 98ms| 130ms | 32ms | 32.517
| ChannelStore.GetForPost |  Avg| 17ms| 18ms | 1ms | 5.956
| |  P99| 188ms| 194ms | 6ms | 3.191
| ChannelStore.GetGuestCount |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 127ms| 128ms | 1ms | 0.785
| ChannelStore.GetMany |  Avg| 27ms| 22ms | -5ms | -18.802
| |  P99| 222ms| 273ms | 51ms | 23.025
| ChannelStore.GetMember |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 96ms | 3ms | 3.228
| ChannelStore.GetMemberCount |  Avg| 34ms| 35ms | 1ms | 2.913
| |  P99| 218ms| 221ms | 3ms | 1.376
| ChannelStore.GetMemberCountsByGroup |  Avg| 17ms| 0s | -17ms | -98.129
| |  P99| 171ms| 0s | -171ms | -99.776
| ChannelStore.GetMemberForPost |  Avg| 38ms| 39ms | 1ms | 2.611
| |  P99| 220ms| 225ms | 5ms | 2.272
| ChannelStore.GetMemberLastViewedAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 93ms | 2ms | 2.197
| ChannelStore.GetMembers |  Avg| 18ms| 23ms | 5ms | 28.147
| |  P99| 96ms| 232ms | 136ms | 141.667
| ChannelStore.GetMembersForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 160ms| 175ms | 15ms | 9.359
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 13ms| 8ms | -5ms | -39.541
| |  P99| 107ms| 25ms | -82ms | -76.288
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 104ms| 98ms | -6ms | -5.789
| ChannelStore.GetPinnedPostCount |  Avg| 11ms| 13ms | 2ms | 17.743
| |  P99| 119ms| 169ms | 50ms | 41.929
| ChannelStore.GetPublicChannelsForTeam |  Avg| 27ms| 33ms | 6ms | 21.915
| |  P99| 211ms| 234ms | 23ms | 10.912
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 205ms| 210ms | 5ms | 2.445
| ChannelStore.GetSidebarCategory |  Avg| 32ms| 28ms | -4ms | -12.318
| |  P99| 379ms| 246ms | -133ms | -35.115
| ChannelStore.GetTeamChannels |  Avg| 45ms| 46ms | 1ms | 2.203
| |  P99| 225ms| 237ms | 12ms | 5.345
| ChannelStore.IncrementMentionCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 91ms| 92ms | 1ms | 1.099
| ChannelStore.Save |  Avg| 49ms| 49ms | 0s | 0.000
| |  P99| 344ms| 449ms | 105ms | 30.545
| ChannelStore.SaveMember |  Avg| 73ms| 75ms | 2ms | 2.737
| |  P99| 550ms| 609ms | 59ms | 10.728
| ChannelStore.SearchGroupChannels |  Avg| 15ms| 17ms | 2ms | 13.143
| |  P99| 155ms| 193ms | 38ms | 24.482
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 12ms | 1ms | 8.715
| |  P99| 90ms| 91ms | 1ms | 1.111
| ChannelStore.UpdateSidebarCategories |  Avg| 133ms| 121ms | -12ms | -9.013
| |  P99| 919ms| 875ms | -44ms | -4.787
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 9ms| 10ms | 1ms | 10.749
| |  P99| 91ms| 93ms | 2ms | 2.187
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 16ms| 17ms | 1ms | 6.349
| |  P99| 100ms| 184ms | 84ms | 84.183
| CommandWebhookStore.Cleanup |  Avg| 18ms| 13ms | -5ms | -27.218
| |  P99| 97ms| 97ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 4ms| 537ms | 533ms | 13889.113
| |  P99| 5ms| 992ms | 987ms | 19932.484
| DesktopTokensStore.DeleteOlderThan |  Avg| 12ms| 39ms | 27ms | 221.333
| |  P99| 25ms| 50ms | 25ms | 100.604
| DraftStore.Delete |  Avg| 13ms| 14ms | 1ms | 7.850
| |  P99| 98ms| 99ms | 1ms | 1.020
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 18ms| 19ms | 1ms | 5.646
| |  P99| 94ms| 49ms | -45ms | -47.957
| DraftStore.Get |  Avg| 14ms| 15ms | 1ms | 6.926
| |  P99| 181ms| 194ms | 13ms | 7.187
| DraftStore.GetDraftsForUser |  Avg| 15ms| 16ms | 1ms | 6.785
| |  P99| 163ms| 199ms | 36ms | 22.062
| DraftStore.Upsert |  Avg| 14ms| 15ms | 1ms | 7.057
| |  P99| 102ms| 115ms | 13ms | 12.769
| EmojiStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 124ms| 132ms | 8ms | 6.429
| EmojiStore.GetMultipleByName |  Avg| 7ms| 13ms | 6ms | 81.299
| |  P99| 47ms| 92ms | 45ms | 95.744
| FileInfoStore.AttachToPost |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 201ms| 193ms | -8ms | -3.977
| FileInfoStore.DeleteForPost |  Avg| 147ms| 0s | -147ms | -100.268
| |  P99| 249ms| 0s | -249ms | -100.201
| FileInfoStore.Get |  Avg| 12ms| 13ms | 1ms | 8.520
| |  P99| 145ms| 158ms | 13ms | 8.969
| FileInfoStore.GetByIds |  Avg| 13ms| 12ms | -1ms | -7.981
| |  P99| 183ms| 169ms | -14ms | -7.648
| FileInfoStore.GetForPost |  Avg| 11ms| 9ms | -2ms | -18.157
| |  P99| 99ms| 90ms | -9ms | -9.061
| FileInfoStore.Save |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 124ms| 103ms | -21ms | -16.976
| FileInfoStore.SetContent |  Avg| 26ms| 25ms | -1ms | -3.916
| |  P99| 230ms| 224ms | -6ms | -2.614
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 92ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 89ms | -2ms | -2.192
| GroupStore.GetGroups |  Avg| 11ms| 12ms | 1ms | 8.794
| |  P99| 132ms| 148ms | 16ms | 12.086
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 20ms| 56ms | 36ms | 178.827
| |  P99| 99ms| 100ms | 1ms | 1.015
| JobStore.GetAllByStatus |  Avg| 14ms| 15ms | 1ms | 7.004
| |  P99| 191ms| 179ms | -12ms | -6.291
| JobStore.GetAllByTypePage |  Avg| 13ms| 16ms | 3ms | 22.972
| |  P99| 95ms| 188ms | 93ms | 98.153
| JobStore.GetCountByStatusAndType |  Avg| 11ms| 13ms | 2ms | 18.212
| |  P99| 97ms| 95ms | -2ms | -2.063
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 9ms | 1ms | 11.907
| |  P99| 89ms| 105ms | 16ms | 17.915
| JobStore.Save |  Avg| 11ms| 13ms | 2ms | 17.483
| |  P99| 155ms| 177ms | 22ms | 14.216
| JobStore.UpdateOptimistically |  Avg| 12ms| 11ms | -1ms | -8.552
| |  P99| 96ms| 98ms | 2ms | 2.075
| JobStore.UpdateStatus |  Avg| 13ms| 10ms | -3ms | -23.273
| |  P99| 97ms| 76ms | -21ms | -21.580
| JobStore.UpdateStatusOptimistically |  Avg| 11ms| 13ms | 2ms | 18.920
| |  P99| 68ms| 142ms | 74ms | 108.425
| LicenseStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 142.132
| LinkMetadataStore.Get |  Avg| 9ms| 10ms | 1ms | 10.683
| |  P99| 111ms| 135ms | 24ms | 21.682
| LinkMetadataStore.Save |  Avg| 5ms| 10ms | 5ms | 91.585
| |  P99| 23ms| 69ms | 46ms | 199.566
| PostAcknowledgementStore.GetForPost |  Avg| 8ms| 9ms | 1ms | 11.985
| |  P99| 99ms| 121ms | 22ms | 22.191
| PostAcknowledgementStore.GetForPosts |  Avg| 15ms| 16ms | 1ms | 6.564
| |  P99| 223ms| 231ms | 8ms | 3.588
| PostPersistentNotificationStore.DeleteExpired |  Avg| 7ms| 11ms | 4ms | 56.988
| |  P99| 89ms| 140ms | 51ms | 57.303
| PostPersistentNotificationStore.Get |  Avg| 7ms| 11ms | 4ms | 57.234
| |  P99| 84ms| 88ms | 4ms | 4.790
| PostPersistentNotificationStore.GetSingle |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 112ms | 13ms | 13.091
| PostPriorityStore.GetForPostWithContext |  Avg| 8ms| 9ms | 1ms | 11.875
| |  P99| 99ms| 119ms | 20ms | 20.196
| PostPriorityStore.GetForPosts |  Avg| 16ms| 17ms | 1ms | 6.239
| |  P99| 225ms| 233ms | 8ms | 3.556
| PostStore.AnalyticsPostCount |  Avg| 257ms| 514ms | 257ms | 99.860
| |  P99| 497ms| 990ms | 493ms | 99.262
| PostStore.AnalyticsPostCountByTeam |  Avg| 10ms| 13ms | 3ms | 29.588
| |  P99| 49ms| 25ms | -24ms | -48.979
| PostStore.Delete |  Avg| 46ms| 67ms | 21ms | 46.098
| |  P99| 454ms| 405ms | -49ms | -10.799
| PostStore.Get |  Avg| 28ms| 30ms | 2ms | 7.219
| |  P99| 242ms| 246ms | 4ms | 1.655
| PostStore.GetEtag |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 155ms| 167ms | 12ms | 7.745
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 70ms| 70ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 88ms | 2ms | 2.325
| PostStore.GetPostReminderMetadata |  Avg| 13ms| 16ms | 3ms | 22.629
| |  P99| 96ms| 106ms | 10ms | 10.381
| PostStore.GetPostReminders |  Avg| 6ms| 9ms | 3ms | 51.051
| |  P99| 24ms| 77ms | 53ms | 222.689
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 87ms | -1ms | -1.139
| PostStore.GetPostsAfter |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 157ms| 165ms | 8ms | 5.096
| PostStore.GetPostsBefore |  Avg| 14ms| 15ms | 1ms | 7.123
| |  P99| 158ms| 173ms | 15ms | 9.481
| PostStore.GetPostsByThread |  Avg| 15ms| 16ms | 1ms | 6.484
| |  P99| 141ms| 148ms | 7ms | 4.964
| PostStore.GetPostsSince |  Avg| 28ms| 29ms | 1ms | 3.572
| |  P99| 220ms| 225ms | 5ms | 2.268
| PostStore.GetSingle |  Avg| 9ms| 10ms | 1ms | 10.897
| |  P99| 105ms| 131ms | 26ms | 24.673
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 41ms| 43ms | 2ms | 4.821
| |  P99| 365ms| 379ms | 14ms | 3.838
| PostStore.SearchPostsForUser |  Avg| 298ms| 323ms | 25ms | 8.402
| |  P99| 3.902s| 4.347s | 445ms | 11.405
| PostStore.SetPostReminder |  Avg| 34ms| 33ms | -1ms | -2.944
| |  P99| 235ms| 236ms | 1ms | 0.426
| PostStore.Update |  Avg| 40ms| 37ms | -3ms | -7.445
| |  P99| 301ms| 240ms | -61ms | -20.277
| PreferenceStore.DeleteCategoryAndName |  Avg| 12ms| 14ms | 2ms | 16.216
| |  P99| 94ms| 81ms | -13ms | -13.854
| PreferenceStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 122ms| 138ms | 16ms | 13.138
| PreferenceStore.GetAll |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 109ms | 11ms | 11.197
| PreferenceStore.Save |  Avg| 32ms| 33ms | 1ms | 3.099
| |  P99| 243ms| 243ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 59ms| 42ms | -17ms | -28.653
| |  P99| 99ms| 50ms | -49ms | -49.370
| ProductNoticesStore.GetViews |  Avg| 14ms| 15ms | 1ms | 7.069
| |  P99| 49ms| 50ms | 1ms | 2.030
| ProductNoticesStore.View |  Avg| 114ms| 114ms | 0s | 0.000
| |  P99| 858ms| 861ms | 3ms | 0.350
| PropertyFieldStore.SearchPropertyFields |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 93ms | 1ms | 1.088
| PropertyGroupStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 96ms| 99ms | 3ms | 3.111
| PropertyValueStore.SearchPropertyValues |  Avg| 11ms| 12ms | 1ms | 9.043
| |  P99| 140ms| 139ms | -1ms | -0.714
| ReactionStore.GetForPost |  Avg| 10ms| 11ms | 1ms | 9.668
| |  P99| 135ms| 97ms | -38ms | -28.065
| RetentionPolicyStore.GetAll |  Avg| 9ms| 0s | -9ms | -103.448
| |  P99| 10ms| 0s | -10ms | -100.503
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -100.009
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 10ms| 14ms | 4ms | 39.814
| |  P99| 50ms| 91ms | 41ms | 82.696
| RoleStore.GetByNames |  Avg| 15ms| 26ms | 11ms | 71.842
| |  P99| 91ms| 153ms | 62ms | 67.813
| ScheduledPostStore.CreateScheduledPost |  Avg| 11ms| 14ms | 3ms | 27.663
| |  P99| 68ms| 99ms | 31ms | 45.755
| ScheduledPostStore.Get |  Avg| 3ms| 0s | -3ms | -103.879
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 12ms| 17ms | 5ms | 41.200
| |  P99| 90ms| 182ms | 92ms | 102.222
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 95ms | 2ms | 2.153
| ScheduledPostStore.PermanentlyDeleteScheduledPosts |  Avg| 4ms| 0s | -4ms | -101.771
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 8ms| 9ms | 1ms | 12.876
| |  P99| 80ms| 77ms | -3ms | -3.750
| SchemeStore.GetAllPage |  Avg| 6ms| 1ms | -5ms | -79.741
| |  P99| 10ms| 5ms | -5ms | -50.251
| SessionStore.Get |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 210ms| 215ms | 5ms | 2.380
| SessionStore.GetLRUSessions |  Avg| 8ms| 7ms | -1ms | -13.329
| |  P99| 89ms| 90ms | 1ms | 1.125
| SessionStore.GetSessionsExpired |  Avg| 13ms| 6ms | -7ms | -53.049
| |  P99| 92ms| 45ms | -47ms | -51.087
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 9ms| 10ms | 1ms | 10.527
| |  P99| 111ms| 135ms | 24ms | 21.610
| SessionStore.Remove |  Avg| 11ms| 12ms | 1ms | 9.145
| |  P99| 152ms| 80ms | -72ms | -47.215
| SessionStore.Save |  Avg| 16ms| 17ms | 1ms | 6.105
| |  P99| 174ms| 177ms | 3ms | 1.725
| SessionStore.UpdateLastActivityAt |  Avg| 11ms| 12ms | 1ms | 8.966
| |  P99| 90ms| 91ms | 1ms | 1.114
| StatusStore.Get |  Avg| 10ms| 11ms | 1ms | 9.548
| |  P99| 128ms| 143ms | 15ms | 11.714
| StatusStore.GetByIds |  Avg| 16ms| 17ms | 1ms | 6.431
| |  P99| 193ms| 204ms | 11ms | 5.697
| StatusStore.SaveOrUpdate |  Avg| 13ms| 14ms | 1ms | 7.729
| |  P99| 98ms| 99ms | 1ms | 1.017
| StatusStore.SaveOrUpdateMany |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 208ms| 208ms | 0s | 0.000
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 14ms| 15ms | 1ms | 7.196
| |  P99| 100ms| 165ms | 65ms | 65.140
| StatusStore.UpdateLastActivityAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 88ms | 1ms | 1.153
| TeamStore.AnalyticsTeamCount |  Avg| 3ms| 13ms | 10ms | 296.362
| |  P99| 10ms| 25ms | 15ms | 152.976
| TeamStore.Get |  Avg| 9ms| 10ms | 1ms | 11.544
| |  P99| 99ms| 126ms | 27ms | 27.157
| TeamStore.GetActiveMemberCount |  Avg| 74ms| 77ms | 3ms | 4.063
| |  P99| 242ms| 243ms | 1ms | 0.414
| TeamStore.GetAllPage |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 99ms | 1ms | 1.025
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 102ms | 3ms | 3.017
| TeamStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 88ms | 2ms | 2.319
| TeamStore.GetTeamsByUserId |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 104ms | 6ms | 6.148
| TeamStore.GetTeamsForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 99ms | 2ms | 2.066
| TeamStore.GetTotalMemberCount |  Avg| 68ms| 70ms | 2ms | 2.931
| |  P99| 242ms| 244ms | 2ms | 0.828
| TeamStore.SaveMember |  Avg| 46ms| 47ms | 1ms | 2.153
| |  P99| 248ms| 248ms | 0s | 0.000
| TemporaryPostStore.GetExpiredPosts |  Avg| 21ms| 11ms | -10ms | -48.527
| |  P99| 96ms| 49ms | -47ms | -48.958
| ThreadStore.Get |  Avg| 9ms| 11ms | 2ms | 21.653
| |  P99| 100ms| 152ms | 52ms | 52.086
| ThreadStore.GetMembershipForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 129ms| 152ms | 23ms | 17.783
| ThreadStore.GetTeamsUnreadForUser |  Avg| 13ms| 14ms | 1ms | 7.562
| |  P99| 178ms| 192ms | 14ms | 7.852
| ThreadStore.GetThreadFollowers |  Avg| 10ms| 11ms | 1ms | 9.734
| |  P99| 127ms| 140ms | 13ms | 10.208
| ThreadStore.GetThreadForUser |  Avg| 19ms| 20ms | 1ms | 5.358
| |  P99| 218ms| 227ms | 9ms | 4.137
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 18ms| 19ms | 1ms | 5.566
| |  P99| 167ms| 167ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 15ms| 16ms | 1ms | 6.534
| |  P99| 176ms| 183ms | 7ms | 3.968
| ThreadStore.GetTotalThreads |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 98ms | 1ms | 1.029
| ThreadStore.GetTotalUnreadMentions |  Avg| 9ms| 10ms | 1ms | 10.583
| |  P99| 99ms| 115ms | 16ms | 16.180
| ThreadStore.GetTotalUnreadThreads |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 97ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 23ms| 24ms | 1ms | 4.372
| |  P99| 222ms| 226ms | 4ms | 1.801
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 11ms | 1ms | 9.697
| |  P99| 89ms| 97ms | 8ms | 9.010
| ThreadStore.MarkAllAsReadByTeam |  Avg| 18ms| 8ms | -10ms | -55.270
| |  P99| 96ms| 24ms | -72ms | -74.611
| ThreadStore.MarkAsRead |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 91ms| 89ms | -2ms | -2.207
| ThreadStore.UpdateMembership |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.111
| TokenStore.Cleanup |  Avg| 13ms| 14ms | 1ms | 7.455
| |  P99| 97ms| 97ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 11ms| 15ms | 4ms | 36.636
| |  P99| 92ms| 189ms | 97ms | 105.435
| UserStore.AnalyticsActiveCount |  Avg| 40ms| 38ms | -2ms | -5.019
| |  P99| 98ms| 50ms | -48ms | -48.980
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 32ms| 18ms | -14ms | -44.087
| |  P99| 244ms| 49ms | -195ms | -79.918
| UserStore.AutocompleteUsersInChannel |  Avg| 73ms| 74ms | 1ms | 1.369
| |  P99| 336ms| 339ms | 3ms | 0.893
| UserStore.Count |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 157ms| 166ms | 9ms | 5.722
| UserStore.Get |  Avg| 11ms| 12ms | 1ms | 9.233
| |  P99| 117ms| 137ms | 20ms | 17.149
| UserStore.GetAllProfiles |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 85ms | 5ms | 6.235
| UserStore.GetAllProfilesInChannel |  Avg| 396ms| 412ms | 16ms | 4.042
| |  P99| 2.154s| 2.201s | 47ms | 2.182
| UserStore.GetByUsername |  Avg| 12ms| 13ms | 1ms | 8.223
| |  P99| 138ms| 155ms | 17ms | 12.286
| UserStore.GetForLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 95ms | 1ms | 1.063
| UserStore.GetMany |  Avg| 10ms| 11ms | 1ms | 10.217
| |  P99| 92ms| 94ms | 2ms | 2.168
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 22ms| 3ms | -19ms | -87.227
| |  P99| 50ms| 5ms | -45ms | -90.909
| UserStore.GetProfileByIds |  Avg| 13ms| 14ms | 1ms | 7.631
| |  P99| 161ms| 174ms | 13ms | 8.095
| UserStore.GetProfilesByUsernames |  Avg| 13ms| 14ms | 1ms | 7.451
| |  P99| 155ms| 167ms | 12ms | 7.724
| UserStore.GetProfilesInChannel |  Avg| 22ms| 10ms | -12ms | -54.424
| |  P99| 392ms| 79ms | -313ms | -79.747
| UserStore.GetProfilesNotInChannel |  Avg| 16ms| 11ms | -5ms | -31.803
| |  P99| 94ms| 91ms | -3ms | -3.180
| UserStore.GetUnreadCount |  Avg| 10ms| 11ms | 1ms | 10.245
| |  P99| 115ms| 140ms | 25ms | 21.713
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.073
| UserStore.Save |  Avg| 178ms| 173ms | -5ms | -2.815
| |  P99| 558ms| 523ms | -35ms | -6.276
| UserStore.Search |  Avg| 48ms| 50ms | 2ms | 4.124
| |  P99| 237ms| 239ms | 2ms | 0.844
| UserStore.Update |  Avg| 27ms| 26ms | -1ms | -3.674
| |  P99| 215ms| 226ms | 11ms | 5.113
| UserStore.UpdateFailedPasswordAttempts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 88ms| 89ms | 1ms | 1.132
| UserStore.UpdateLastLogin |  Avg| 10ms| 11ms | 1ms | 9.779
| |  P99| 77ms| 80ms | 3ms | 3.875
| UserStore.UpdateUpdateAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 78ms| 79ms | 1ms | 1.279
| UserTermsOfServiceStore.GetByUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 98ms | 3ms | 3.143
| WebhookStore.GetOutgoingByTeam |  Avg| 16ms| 17ms | 1ms | 6.349
| |  P99| 187ms| 199ms | 12ms | 6.425
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 525ms| 556ms | 31ms | 5.905
| | P99| 2.468s| 2.461s | -7ms | -0.284
| addTeamMember | Avg| 1.391s| 1.409s | 18ms | 1.294
| | P99| 8.387s| 8.586s | 199ms | 2.373
| autocompleteChannelsForTeamForSearch | Avg| 68ms| 76ms | 8ms | 11.711
| | P99| 369ms| 410ms | 41ms | 11.104
| autocompleteUsers | Avg| 69ms| 70ms | 1ms | 1.453
| | P99| 357ms| 372ms | 15ms | 4.202
| channelMemberCountsByGroup | Avg| 20ms| 0s | -20ms | -97.883
| | P99| 208ms| 0s | -208ms | -100.121
| createCategoryForTeamForUser | Avg| 59ms| 115ms | 56ms | 94.792
| | P99| 243ms| 478ms | 235ms | 96.608
| createChannel | Avg| 616ms| 442ms | -174ms | -28.259
| | P99| 2.372s| 988ms | -1.384s | -58.335
| createChannelBookmark | Avg| 54ms| 51ms | -3ms | -5.543
| | P99| 398ms| 243ms | -155ms | -38.993
| createDirectChannel | Avg| 562ms| 627ms | 65ms | 11.575
| | P99| 2.432s| 2.447s | 15ms | 0.617
| createEmoji | Avg| 6ms| 5ms | -1ms | -17.881
| | P99| 10ms| 10ms | 0s | 0.000
| createGroupChannel | Avg| 962ms| 999ms | 37ms | 3.845
| | P99| 4.501s| 4.614s | 113ms | 2.510
| createPost | Avg| 704ms| 727ms | 23ms | 3.267
| | P99| 4.395s| 4.471s | 76ms | 1.729
| createSchedulePost | Avg| 16ms| 19ms | 3ms | 18.614
| | P99| 153ms| 161ms | 8ms | 5.220
| createUser | Avg| 410ms| 415ms | 5ms | 1.220
| | P99| 2.26s| 2.28s | 20ms | 0.885
| deleteChannelBookmark | Avg| 83ms| 16ms | -67ms | -81.162
| | P99| 246ms| 49ms | -197ms | -80.001
| deleteDraft | Avg| 16ms| 17ms | 1ms | 6.437
| | P99| 198ms| 209ms | 11ms | 5.564
| deletePost | Avg| 76ms| 129ms | 53ms | 69.992
| | P99| 469ms| 905ms | 436ms | 92.930
| deleteScheduledPost | Avg| 10ms| 0s | -10ms | -101.608
| | P99| 10ms| 0s | -10ms | -100.503
| followThreadByUser | Avg| 61ms| 64ms | 3ms | 4.933
| | P99| 685ms| 815ms | 130ms | 18.977
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 148ms| 157ms | 9ms | 6.078
| getAnalytics | Avg| 180ms| 153ms | -27ms | -14.973
| | P99| 492ms| 249ms | -243ms | -49.340
| getCategoriesForTeamForUser | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 215ms| 218ms | 3ms | 1.393
| getChannel | Avg| 23ms| 28ms | 5ms | 21.902
| | P99| 239ms| 233ms | -6ms | -2.511
| getChannelMember | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 232ms| 235ms | 3ms | 1.294
| getChannelMembers | Avg| 19ms| 27ms | 8ms | 43.094
| | P99| 96ms| 232ms | 136ms | 141.667
| getChannelMembersForTeamForUser | Avg| 14ms| 15ms | 1ms | 7.176
| | P99| 171ms| 184ms | 13ms | 7.608
| getChannelMembersForUser | Avg| 11ms| 10ms | -1ms | -9.315
| | P99| 121ms| 100ms | -21ms | -17.339
| getChannelStats | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 127ms| 132ms | 5ms | 3.948
| getChannelUnread | Avg| 15ms| 16ms | 1ms | 6.533
| | P99| 200ms| 199ms | -1ms | -0.500
| getChannelsForTeamForUser | Avg| 14ms| 15ms | 1ms | 7.019
| | P99| 181ms| 190ms | 9ms | 4.961
| getChannelsForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 98ms| 97ms | -1ms | -1.021
| getClientConfig | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 232ms| 235ms | 3ms | 1.294
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 16ms| 18ms | 2ms | 12.669
| | P99| 189ms| 221ms | 32ms | 16.927
| getFilePreview | Avg| 77ms| 76ms | -1ms | -1.304
| | P99| 398ms| 404ms | 6ms | 1.507
| getFileThumbnail | Avg| 71ms| 70ms | -1ms | -1.417
| | P99| 357ms| 367ms | 10ms | 2.803
| getFilteredUsersStats | Avg| 23ms| 16ms | -7ms | -30.753
| | P99| 49ms| 25ms | -24ms | -48.731
| getGroups | Avg| 23ms| 12ms | -11ms | -48.796
| | P99| 49ms| 25ms | -24ms | -48.601
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -123.278
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 13ms| 16ms | 3ms | 22.718
| | P99| 95ms| 188ms | 93ms | 98.153
| getPostThread | Avg| 67ms| 71ms | 4ms | 6.003
| | P99| 642ms| 690ms | 48ms | 7.477
| getPostsForChannel | Avg| 152ms| 166ms | 14ms | 9.190
| | P99| 2.108s| 2.242s | 134ms | 6.358
| getPostsForChannelAroundLastUnread | Avg| 53ms| 54ms | 1ms | 1.892
| | P99| 478ms| 494ms | 16ms | 3.344
| getPreferences | Avg| 10ms| 11ms | 1ms | 9.787
| | P99| 110ms| 139ms | 29ms | 26.455
| getPrevTrialLicense | Avg| 34ms| 5ms | -29ms | -85.374
| | P99| 99ms| 25ms | -74ms | -74.748
| getProductNotices | Avg| 119ms| 27ms | -92ms | -77.139
| | P99| 249ms| 50ms | -199ms | -80.080
| getProfileImage | Avg| 80ms| 73ms | -7ms | -8.798
| | P99| 484ms| 477ms | -7ms | -1.447
| getPropertyFields | Avg| 20ms| 43ms | 23ms | 112.606
| | P99| 210ms| 244ms | 34ms | 16.229
| getPublicChannelsForTeam | Avg| 29ms| 34ms | 5ms | 17.109
| | P99| 221ms| 234ms | 13ms | 5.875
| getRolesByNames | Avg| 7ms| 0s | -7ms | -100.809
| | P99| 48ms| 5ms | -43ms | -89.119
| getServerLimits | Avg| 35ms| 42ms | 7ms | 19.983
| | P99| 96ms| 99ms | 3ms | 3.125
| getSystemPropertyValues | Avg| 22ms| 0s | -22ms | -99.285
| | P99| 201ms| 0s | -201ms | -100.247
| getTeamMember | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 136ms| 131ms | -5ms | -3.673
| getTeamMembersForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 124ms| 146ms | 22ms | 17.671
| getTeamScheduledPosts | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 210ms| 217ms | 7ms | 3.327
| getTeamStats | Avg| 81ms| 81ms | 0s | 0.000
| | P99| 244ms| 244ms | 0s | 0.000
| getTeamsForUser | Avg| 9ms| 10ms | 1ms | 10.777
| | P99| 99ms| 118ms | 19ms | 19.124
| getTeamsUnreadForUser | Avg| 19ms| 20ms | 1ms | 5.308
| | P99| 230ms| 236ms | 6ms | 2.607
| getThreadsForUser | Avg| 16ms| 17ms | 1ms | 6.192
| | P99| 197ms| 202ms | 5ms | 2.534
| getUser | Avg| 17ms| 18ms | 1ms | 5.784
| | P99| 243ms| 245ms | 2ms | 0.825
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 87ms| 92ms | 5ms | 5.746
| getUsers | Avg| 16ms| 17ms | 1ms | 6.288
| | P99| 236ms| 239ms | 3ms | 1.271
| getUsersByGroupChannelIds | Avg| 36ms| 0s | -36ms | -100.627
| | P99| 50ms| 0s | -50ms | -100.503
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 48ms| 53ms | 5ms | 10.312
| getUsersByNames | Avg| 14ms| 15ms | 1ms | 7.060
| | P99| 172ms| 182ms | 10ms | 5.804
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 70ms| 48ms | -22ms | -31.223
| | P99| 246ms| 99ms | -147ms | -59.695
| listCPAFields | Avg| 18ms| 19ms | 1ms | 5.673
| | P99| 219ms| 226ms | 7ms | 3.190
| listCPAValues | Avg| 25ms| 27ms | 2ms | 7.898
| | P99| 248ms| 245ms | -3ms | -1.211
| listChannelBookmarksForChannel | Avg| 11ms| 12ms | 1ms | 8.925
| | P99| 147ms| 164ms | 17ms | 11.540
| login | Avg| 202ms| 173ms | -29ms | -14.343
| | P99| 1.732s| 976ms | -756ms | -43.656
| logout | Avg| 131ms| 161ms | 30ms | 22.987
| | P99| 1.525s| 3.025s | 1.5s | 98.355
| patchPost | Avg| 117ms| 127ms | 10ms | 8.547
| | P99| 901ms| 973ms | 72ms | 7.989
| removeUserCustomStatus | Avg| 367ms| 381ms | 14ms | 3.819
| | P99| 2.069s| 2.057s | -12ms | -0.580
| root | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 177ms| 176ms | -1ms | -0.563
| saveReaction | Avg| 63ms| 64ms | 1ms | 1.599
| | P99| 423ms| 433ms | 10ms | 2.366
| searchAllChannels | Avg| 53ms| 54ms | 1ms | 1.895
| | P99| 246ms| 243ms | -3ms | -1.219
| searchGroupChannels | Avg| 16ms| 17ms | 1ms | 6.432
| | P99| 163ms| 198ms | 35ms | 21.425
| searchPostsInTeam | Avg| 326ms| 353ms | 27ms | 8.273
| | P99| 4.173s| 4.462s | 289ms | 6.926
| searchUsers | Avg| 51ms| 52ms | 1ms | 1.980
| | P99| 240ms| 242ms | 2ms | 0.833
| setPostReminder | Avg| 121ms| 143ms | 22ms | 18.209
| | P99| 1.585s| 1.78s | 195ms | 12.304
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 62ms| 63ms | 1ms | 1.611
| | P99| 415ms| 443ms | 28ms | 6.741
| updateCategoriesForTeamForUser | Avg| 214ms| 187ms | -27ms | -12.640
| | P99| 2.015s| 989ms | -1.026s | -50.918
| updateChannelBookmark | Avg| 70ms| 56ms | -14ms | -19.966
| | P99| 245ms| 240ms | -5ms | -2.042
| updateChannelBookmarkSortOrder | Avg| 36ms| 40ms | 4ms | 11.172
| | P99| 96ms| 240ms | 144ms | 149.895
| updatePreferences | Avg| 44ms| 46ms | 2ms | 4.512
| | P99| 376ms| 371ms | -5ms | -1.329
| updateReadStateAllThreadsByUser | Avg| 27ms| 8ms | -19ms | -71.411
| | P99| 229ms| 24ms | -205ms | -89.519
| updateReadStateThreadByUser | Avg| 137ms| 143ms | 6ms | 4.365
| | P99| 974ms| 981ms | 7ms | 0.719
| updateUserCustomStatus | Avg| 0s| 1ms | 1ms | 692.430
| | P99| 5ms| 6ms | 1ms | 20.067
| uploadFileStream | Avg| 572ms| 549ms | -23ms | -4.023
| | P99| 2.257s| 2.216s | -41ms | -1.816
| upsertDraft | Avg| 18ms| 19ms | 1ms | 5.473
| | P99| 201ms| 208ms | 7ms | 3.491
| viewChannel | Avg| 65ms| 69ms | 4ms | 6.190
| | P99| 624ms| 697ms | 73ms | 11.707

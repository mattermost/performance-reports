### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.ChannelHigherScopedPermissions | avg | 9ms | 67ms | 58ms | 647.82
| SessionStore.GetSessionsExpired | avg | 7ms | 25ms | 18ms | 272.07
| PreferenceStore.DeleteCategoryAndName | avg | 7ms | 17ms | 10ms | 139.42
| RoleStore.GetByNames | avg | 27ms | 55ms | 28ms | 104.46
| ScheduledPostStore.CreateScheduledPost | avg | 10ms | 17ms | 7ms | 66.96
| ChannelStore.GetMembers | avg | 18ms | 30ms | 12ms | 65.53
| PostPersistentNotificationStore.Get | avg | 9ms | 14ms | 5ms | 54.50
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 14ms | 21ms | 7ms | 50.08
| JobStore.UpdateStatusOptimistically | avg | 12ms | 17ms | 5ms | 40.48
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 22ms | 28ms | 6ms | 26.84
| SessionStore.Remove | avg | 11ms | 14ms | 3ms | 26.16
| ChannelStore.GetMany | avg | 20ms | 25ms | 5ms | 25.26
| ChannelStore.UpdateSidebarCategories | avg | 97ms | 120ms | 23ms | 23.62
| ThreadStore.MarkAllAsReadByChannels | avg | 11ms | 13ms | 2ms | 17.88
| UserAccessTokenStore.GetByToken | avg | 13ms | 15ms | 2ms | 15.27
| CommandWebhookStore.Cleanup | avg | 19ms | 21ms | 2ms | 10.66
| UserStore.Update | avg | 28ms | 30ms | 2ms | 7.24
| ChannelStore.Save | avg | 48ms | 50ms | 2ms | 4.13
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.ChannelHigherScopedPermissions | p99 | 48ms | 440ms | 392ms | 814.55
| SessionStore.GetSessionsExpired | p99 | 46ms | 231ms | 185ms | 402.17
| PreferenceStore.DeleteCategoryAndName | p99 | 46ms | 219ms | 173ms | 372.71
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 78ms | 189ms | 111ms | 141.40
| PostPersistentNotificationStore.Get | p99 | 154ms | 350ms | 196ms | 127.26
| ChannelStore.UpdateSidebarCategories | p99 | 530ms | 1.18s | 650ms | 122.65
| JobStore.UpdateStatusOptimistically | p99 | 97ms | 209ms | 112ms | 115.46
| ScheduledPostStore.CreateScheduledPost | p99 | 84ms | 170ms | 86ms | 101.93
| PostStore.AnalyticsPostCount | p99 | 498ms | 980ms | 482ms | 96.88
| ChannelBookmarkStore.Save | p99 | 234ms | 450ms | 216ms | 92.21
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 230ms | 406ms | 176ms | 76.63
| ChannelStore.GetSidebarCategory | p99 | 233ms | 405ms | 172ms | 73.69
| RoleStore.GetByNames | p99 | 151ms | 242ms | 91ms | 60.26
| ChannelStore.GetMany | p99 | 161ms | 233ms | 72ms | 44.58
| ChannelStore.AutocompleteInTeamForSearch | p99 | 304ms | 419ms | 115ms | 37.81
| ThreadStore.MarkAllAsReadByChannels | p99 | 110ms | 147ms | 37ms | 33.73
| PostStore.Update | p99 | 243ms | 303ms | 60ms | 24.64
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 96ms | 116ms | 20ms | 20.82
| PostPriorityStore.GetForPostWithContext | p99 | 115ms | 138ms | 23ms | 20.04
| PostAcknowledgementStore.GetForPost | p99 | 115ms | 137ms | 22ms | 19.10
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 130ms | 152ms | 22ms | 16.99
| TeamStore.Get | p99 | 124ms | 143ms | 19ms | 15.38
| PostStore.Get | p99 | 276ms | 318ms | 42ms | 15.23
| UserStore.IsEmpty | p99 | 49ms | 56ms | 7ms | 14.17
| PostStore.GetSingle | p99 | 136ms | 153ms | 17ms | 12.52
| ChannelStore.GetPinnedPostCount | p99 | 177ms | 198ms | 21ms | 11.86
| LinkMetadataStore.Get | p99 | 146ms | 162ms | 16ms | 10.95
| PostPersistentNotificationStore.GetSingle | p99 | 110ms | 122ms | 12ms | 10.94
| TeamStore.GetTeamsForUser | p99 | 130ms | 144ms | 14ms | 10.73
| UserStore.GetUnreadCount | p99 | 147ms | 162ms | 15ms | 10.19
| ChannelStore.Save | p99 | 431ms | 471ms | 40ms | 9.28
| PostStore.GetPostsByThread | p99 | 163ms | 178ms | 15ms | 9.20
| ThreadStore.GetThreadFollowers | p99 | 137ms | 148ms | 11ms | 8.05
| ChannelStore.SearchGroupChannels | p99 | 208ms | 223ms | 15ms | 7.23
| UserStore.GetForLogin | p99 | 120ms | 128ms | 8ms | 6.67
| ThreadStore.GetThreadUnreadReplyCount | p99 | 190ms | 201ms | 11ms | 5.79
| StatusStore.Get | p99 | 178ms | 188ms | 10ms | 5.62
| EmojiStore.GetByName | p99 | 162ms | 171ms | 9ms | 5.55
| FileInfoStore.AttachToPost | p99 | 212ms | 221ms | 9ms | 4.25
| DraftStore.Get | p99 | 218ms | 227ms | 9ms | 4.13
| UserStore.AutocompleteUsersInChannel | p99 | 375ms | 390ms | 15ms | 4.00
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 173ms | 179ms | 6ms | 3.46
| ChannelStore.Get | p99 | 236ms | 244ms | 8ms | 3.39
| TeamStore.GetTeamsByUserId | p99 | 136ms | 140ms | 4ms | 2.94
| ChannelStore.GetMembersForUserWithPagination | p99 | 140ms | 144ms | 4ms | 2.86
| ChannelStore.GetForPost | p99 | 217ms | 223ms | 6ms | 2.76
| GroupStore.GetGroups | p99 | 154ms | 158ms | 4ms | 2.60
| UserStore.GetProfileByIds | p99 | 202ms | 207ms | 5ms | 2.48
| UserStore.Save | p99 | 618ms | 633ms | 15ms | 2.43
| PostPersistentNotificationStore.DeleteExpired | p99 | 84ms | 86ms | 2ms | 2.38
| ThreadStore.GetMembershipForUser | p99 | 178ms | 182ms | 4ms | 2.25
| StatusStore.GetByIds | p99 | 227ms | 232ms | 5ms | 2.21
| PostAcknowledgementStore.GetForPosts | p99 | 228ms | 233ms | 5ms | 2.19
| UserStore.GetAllProfiles | p99 | 92ms | 94ms | 2ms | 2.19
| TemporaryPostStore.GetExpiredPosts | p99 | 92ms | 94ms | 2ms | 2.17
| TeamStore.GetTotalMemberCount | p99 | 231ms | 236ms | 5ms | 2.16
| PostStore.GetPosts | p99 | 93ms | 95ms | 2ms | 2.15
| ChannelStore.GetMembers | p99 | 96ms | 98ms | 2ms | 2.07
| PreferenceStore.Get | p99 | 198ms | 202ms | 4ms | 2.02
| PostStore.GetEtag | p99 | 202ms | 206ms | 4ms | 1.98
| ThreadStore.GetTeamsUnreadForUser | p99 | 202ms | 206ms | 4ms | 1.98
| ProductNoticesStore.View | p99 | 885ms | 902ms | 17ms | 1.92
| ThreadStore.GetThreadsForUser | p99 | 213ms | 217ms | 4ms | 1.88
| WebhookStore.GetOutgoingByTeam | p99 | 214ms | 218ms | 4ms | 1.87
| SessionStore.Get | p99 | 228ms | 232ms | 4ms | 1.75
| PostPriorityStore.GetForPosts | p99 | 232ms | 236ms | 4ms | 1.73
| UserStore.Count | p99 | 189ms | 192ms | 3ms | 1.59
| PostStore.GetPostsBefore | p99 | 205ms | 208ms | 3ms | 1.47
| UserStore.GetProfilesByUsernames | p99 | 207ms | 210ms | 3ms | 1.45
| ChannelStore.GetChannels | p99 | 210ms | 213ms | 3ms | 1.43
| PostStore.Delete | p99 | 392ms | 397ms | 5ms | 1.27
| UserStore.Update | p99 | 242ms | 245ms | 3ms | 1.24
| ChannelStore.Autocomplete | p99 | 244ms | 247ms | 3ms | 1.23
| FileInfoStore.GetForPost | p99 | 185ms | 187ms | 2ms | 1.08
| SessionStore.Save | p99 | 192ms | 194ms | 2ms | 1.04
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.UpdatedScheduledPost | avg | 10ms | 0s | -10ms | -103.59
| DesktopTokensStore.DeleteOlderThan | avg | 50ms | 0s | -50ms | -100.57
| BotStore.Get | avg | 29ms | 6ms | -23ms | -79.22
| ChannelStore.CreateSidebarCategory | avg | 121ms | 26ms | -95ms | -78.79
| ScheduledPostStore.GetPendingScheduledPosts | avg | 43ms | 11ms | -32ms | -75.16
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 19ms | 5ms | -14ms | -72.95
| ChannelBookmarkStore.Delete | avg | 44ms | 15ms | -29ms | -65.37
| ChannelBookmarkStore.UpdateSortOrder | avg | 112ms | 42ms | -70ms | -62.53
| PostStore.GetPostReminders | avg | 14ms | 6ms | -8ms | -55.52
| UserStore.GetProfilesNotInChannel | avg | 24ms | 11ms | -13ms | -54.46
| JobStore.Save | avg | 13ms | 7ms | -6ms | -47.87
| TokenStore.Cleanup | avg | 24ms | 14ms | -10ms | -41.55
| PostStore.GetPostReminderMetadata | avg | 19ms | 12ms | -7ms | -37.09
| StatusStore.UpdateExpiredDNDStatuses | avg | 25ms | 16ms | -9ms | -35.54
| PostStore.SetPostReminder | avg | 34ms | 23ms | -11ms | -32.11
| ThreadStore.Get | avg | 13ms | 9ms | -4ms | -31.97
| ProductNoticesStore.ClearOldNotices | avg | 59ms | 41ms | -18ms | -30.71
| UserStore.GetByUsername | avg | 17ms | 12ms | -5ms | -30.06
| UserStore.GetMany | avg | 17ms | 12ms | -5ms | -29.36
| ReactionStore.GetForPost | avg | 14ms | 10ms | -4ms | -28.95
| UserStore.GetProfilesInChannel | avg | 21ms | 15ms | -6ms | -28.78
| JobStore.GetNewestJobByStatusesAndType | avg | 11ms | 8ms | -3ms | -26.83
| ChannelBookmarkStore.Get | avg | 24ms | 18ms | -6ms | -25.37
| ChannelStore.GetTeamChannels | avg | 50ms | 38ms | -12ms | -23.88
| JobStore.GetAllByStatus | avg | 19ms | 16ms | -3ms | -16.10
| JobStore.UpdateStatus | avg | 13ms | 11ms | -2ms | -15.79
| PostStore.Delete | avg | 51ms | 43ms | -8ms | -15.78
| ClusterDiscoveryStore.SetLastPingAt | avg | 20ms | 17ms | -3ms | -14.73
| JobStore.GetCountByStatusAndType | avg | 14ms | 12ms | -2ms | -13.86
| ChannelStore.AutocompleteInTeamForSearch | avg | 55ms | 49ms | -6ms | -10.87
| DraftStore.GetDraftsForUser | avg | 19ms | 17ms | -2ms | -10.55
| PostStore.AnalyticsPostCount | avg | 347ms | 314ms | -33ms | -9.52
| ChannelStore.CreateDirectChannel | avg | 97ms | 89ms | -8ms | -8.28
| TeamStore.GetActiveMemberCount | avg | 69ms | 64ms | -5ms | -7.23
| PostStore.Update | avg | 34ms | 32ms | -2ms | -5.97
| PostStore.SearchPostsForUser | avg | 71ms | 67ms | -4ms | -5.65
| ChannelStore.CreateInitialSidebarCategories | avg | 37ms | 35ms | -2ms | -5.45
| PostStore.Save | avg | 40ms | 38ms | -2ms | -4.96
| TeamStore.SaveMember | avg | 43ms | 41ms | -2ms | -4.68
| UserStore.GetAllProfilesInChannel | avg | 373ms | 360ms | -13ms | -3.48
| ProductNoticesStore.View | avg | 99ms | 96ms | -3ms | -3.02
| UserStore.Save | avg | 175ms | 172ms | -3ms | -1.71
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | p99 | 50ms | 0s | -50ms | -100.50
| ScheduledPostStore.UpdatedScheduledPost | p99 | 10ms | 0s | -10ms | -100.50
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 805ms | 48ms | -757ms | -94.04
| BotStore.Get | p99 | 405ms | 42ms | -363ms | -89.63
| UserStore.GetProfilesNotInChannel | p99 | 437ms | 86ms | -351ms | -80.23
| TokenStore.Cleanup | p99 | 241ms | 48ms | -193ms | -80.08
| PostStore.GetPostReminders | p99 | 193ms | 46ms | -147ms | -76.17
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 191ms | 46ms | -145ms | -75.72
| JobStore.Save | p99 | 187ms | 46ms | -141ms | -75.20
| ChannelBookmarkStore.Delete | p99 | 243ms | 95ms | -148ms | -60.84
| LinkMetadataStore.Save | p99 | 186ms | 76ms | -110ms | -59.30
| EmojiStore.GetMultipleByName | p99 | 240ms | 98ms | -142ms | -59.11
| PostStore.GetPostReminderMetadata | p99 | 219ms | 100ms | -119ms | -54.37
| JobStore.GetNewestJobByStatusesAndType | p99 | 204ms | 96ms | -108ms | -52.99
| ThreadStore.Get | p99 | 189ms | 90ms | -99ms | -52.28
| ChannelStore.CreateSidebarCategory | p99 | 489ms | 238ms | -251ms | -51.36
| ChannelBookmarkStore.UpdateSortOrder | p99 | 488ms | 239ms | -249ms | -51.08
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 50ms | -49ms | -49.37
| SessionStore.Remove | p99 | 181ms | 95ms | -86ms | -47.51
| ReactionStore.GetForPost | p99 | 188ms | 99ms | -89ms | -47.24
| ChannelStore.GetTeamChannels | p99 | 438ms | 240ms | -198ms | -45.26
| UserStore.GetMany | p99 | 362ms | 198ms | -164ms | -45.24
| UserStore.GetByUsername | p99 | 226ms | 147ms | -79ms | -35.01
| StatusStore.UpdateExpiredDNDStatuses | p99 | 220ms | 160ms | -60ms | -27.25
| JobStore.UpdateOptimistically | p99 | 157ms | 115ms | -42ms | -26.75
| PropertyFieldStore.SearchPropertyFields | p99 | 131ms | 98ms | -33ms | -25.13
| JobStore.UpdateStatus | p99 | 204ms | 169ms | -35ms | -17.20
| TeamStore.SaveMember | p99 | 300ms | 252ms | -48ms | -16.00
| ChannelStore.IncrementMentionCount | p99 | 130ms | 110ms | -20ms | -15.41
| UserStore.GetProfilesInChannel | p99 | 228ms | 201ms | -27ms | -11.83
| JobStore.GetAllByStatus | p99 | 233ms | 207ms | -26ms | -11.14
| UserAccessTokenStore.GetByToken | p99 | 175ms | 158ms | -17ms | -9.71
| PreferenceStore.GetAll | p99 | 169ms | 153ms | -16ms | -9.47
| DraftStore.GetDraftsForUser | p99 | 224ms | 204ms | -20ms | -8.94
| PostStore.SearchPostsForUser | p99 | 2.028s | 1.847s | -181ms | -8.93
| JobStore.GetCountByStatusAndType | p99 | 202ms | 186ms | -16ms | -7.91
| ChannelStore.GetByName | p99 | 152ms | 140ms | -12ms | -7.89
| UserTermsOfServiceStore.GetByUser | p99 | 129ms | 120ms | -9ms | -7.00
| UserStore.UpdateLastLogin | p99 | 87ms | 81ms | -6ms | -6.92
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 107ms | 100ms | -7ms | -6.52
| ThreadStore.GetTotalUnreadThreads | p99 | 141ms | 132ms | -9ms | -6.40
| ThreadStore.GetTotalThreads | p99 | 142ms | 133ms | -9ms | -6.32
| ChannelStore.GetMember | p99 | 128ms | 120ms | -8ms | -6.25
| ChannelStore.GetGuestCount | p99 | 172ms | 162ms | -10ms | -5.81
| ChannelStore.GetChannelUnread | p99 | 213ms | 201ms | -12ms | -5.62
| PropertyValueStore.SearchPropertyValues | p99 | 205ms | 195ms | -10ms | -4.89
| ClusterDiscoveryStore.SetLastPingAt | p99 | 217ms | 207ms | -10ms | -4.61
| ChannelStore.GetMemberLastViewedAt | p99 | 109ms | 104ms | -5ms | -4.60
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 142ms | 136ms | -6ms | -4.21
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 155ms | 149ms | -6ms | -3.88
| FileInfoStore.GetByIds | p99 | 210ms | 202ms | -8ms | -3.81
| ChannelStore.CreateDirectChannel | p99 | 881ms | 849ms | -32ms | -3.63
| StatusStore.SaveOrUpdate | p99 | 168ms | 162ms | -6ms | -3.56
| PostStore.SetPostReminder | p99 | 237ms | 229ms | -8ms | -3.37
| TeamStore.GetActiveMemberCount | p99 | 238ms | 230ms | -8ms | -3.37
| TeamStore.GetMember | p99 | 91ms | 88ms | -3ms | -3.30
| FileInfoStore.Save | p99 | 197ms | 191ms | -6ms | -3.04
| DraftStore.Upsert | p99 | 187ms | 182ms | -5ms | -2.67
| PostStore.GetPostIdAfterTime | p99 | 78ms | 76ms | -2ms | -2.57
| ChannelBookmarkStore.Get | p99 | 212ms | 207ms | -5ms | -2.35
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 92ms | 90ms | -2ms | -2.17
| PostStore.GetPostsAfter | p99 | 187ms | 183ms | -4ms | -2.14
| ThreadStore.MaintainMembership | p99 | 238ms | 233ms | -5ms | -2.10
| DraftStore.Delete | p99 | 145ms | 142ms | -3ms | -2.07
| ChannelStore.UpdateLastViewedAt | p99 | 102ms | 100ms | -2ms | -1.95
| ChannelStore.GetFileCount | p99 | 174ms | 171ms | -3ms | -1.72
| ChannelStore.GetAllChannelMembersForUser | p99 | 183ms | 180ms | -3ms | -1.64
| PostStore.Save | p99 | 410ms | 404ms | -6ms | -1.46
| TeamStore.GetAllPage | p99 | 141ms | 139ms | -2ms | -1.42
| UserStore.Get | p99 | 182ms | 180ms | -2ms | -1.10
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 19ms | 41ms | 22ms | 116.06
| listCPAValues | avg | 16ms | 31ms | 15ms | 93.77
| createSchedulePost | avg | 13ms | 25ms | 12ms | 93.38
| deleteChannelBookmark | avg | 36ms | 65ms | 29ms | 80.59
| listCPAFields | avg | 11ms | 19ms | 8ms | 73.14
| createChannelBookmark | avg | 63ms | 81ms | 18ms | 28.77
| updateCategoriesForTeamForUser | avg | 164ms | 194ms | 30ms | 18.25
| logout | avg | 142ms | 165ms | 23ms | 16.25
| deletePost | avg | 83ms | 86ms | 3ms | 3.62
| getPostThread | avg | 74ms | 76ms | 2ms | 2.68
| createGroupChannel | avg | 927ms | 946ms | 19ms | 2.05
| getPostsForChannel | avg | 152ms | 155ms | 3ms | 1.98
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createSchedulePost | p99 | 97ms | 247ms | 150ms | 153.85
| getChannelMembers | p99 | 96ms | 238ms | 142ms | 147.15
| updateCategoriesForTeamForUser | p99 | 922ms | 2.06s | 1.138s | 123.47
| createChannel | p99 | 2.437s | 4.325s | 1.888s | 77.46
| listCPAValues | p99 | 215ms | 372ms | 157ms | 72.96
| logout | p99 | 923ms | 1.585s | 662ms | 71.70
| patchPost | p99 | 947ms | 1.335s | 388ms | 40.98
| listCPAFields | p99 | 172ms | 237ms | 65ms | 37.81
| updateReadStateThreadByUser | p99 | 974ms | 1.284s | 310ms | 31.82
| autocompleteChannelsForTeamForSearch | p99 | 332ms | 433ms | 101ms | 30.41
| createGroupChannel | p99 | 4.575s | 5.383s | 808ms | 17.66
| viewChannel | p99 | 510ms | 592ms | 82ms | 16.07
| getPostThread | p99 | 698ms | 802ms | 104ms | 14.90
| getPublicChannelsForTeam | p99 | 242ms | 260ms | 18ms | 7.43
| searchGroupChannels | p99 | 212ms | 227ms | 15ms | 7.06
| updatePreferences | p99 | 418ms | 440ms | 22ms | 5.27
| getPostsForChannelAroundLastUnread | p99 | 541ms | 566ms | 25ms | 4.62
| deleteDraft | p99 | 224ms | 234ms | 10ms | 4.46
| getChannelMembersForUser | p99 | 147ms | 152ms | 5ms | 3.39
| getPostsForChannel | p99 | 2.103s | 2.17s | 67ms | 3.19
| getChannel | p99 | 323ms | 333ms | 10ms | 3.09
| saveReaction | p99 | 450ms | 462ms | 12ms | 2.66
| getTeamMembersForUser | p99 | 172ms | 176ms | 4ms | 2.33
| deleteChannelBookmark | p99 | 240ms | 245ms | 5ms | 2.09
| getChannelsForTeamForUser | p99 | 214ms | 218ms | 4ms | 1.87
| getThreadsForUser | p99 | 220ms | 224ms | 4ms | 1.81
| getTeamStats | p99 | 238ms | 242ms | 4ms | 1.68
| createPost | p99 | 4.534s | 4.607s | 73ms | 1.61
| getUsersByNames | p99 | 213ms | 216ms | 3ms | 1.41
| getTeamsForUser | p99 | 147ms | 149ms | 2ms | 1.36
| getChannelStats | p99 | 157ms | 159ms | 2ms | 1.28
| deletePost | p99 | 785ms | 795ms | 10ms | 1.27
| getChannelMember | p99 | 242ms | 245ms | 3ms | 1.24
| searchUsers | p99 | 243ms | 246ms | 3ms | 1.23
| searchAllChannels | p99 | 246ms | 249ms | 3ms | 1.22
| getUser | p99 | 272ms | 275ms | 3ms | 1.10
| listChannelBookmarksForChannel | p99 | 191ms | 193ms | 2ms | 1.05
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateScheduledPost | avg | 15ms | 0s | -15ms | -97.72
| createCategoryForTeamForUser | avg | 143ms | 29ms | -114ms | -79.97
| updateChannelBookmarkSortOrder | avg | 161ms | 59ms | -102ms | -63.54
| updateChannelBookmark | avg | 180ms | 71ms | -109ms | -60.59
| followThreadByUser | avg | 107ms | 70ms | -37ms | -34.70
| unfollowThreadByUser | avg | 72ms | 60ms | -12ms | -16.74
| getDrafts | avg | 21ms | 18ms | -3ms | -14.54
| createChannel | avg | 697ms | 596ms | -101ms | -14.50
| autocompleteChannelsForTeamForSearch | avg | 56ms | 49ms | -7ms | -12.57
| login | avg | 222ms | 195ms | -27ms | -12.14
| setPostReminder | avg | 94ms | 83ms | -11ms | -11.70
| patchPost | avg | 126ms | 115ms | -11ms | -8.71
| removeUserCustomStatus | avg | 369ms | 339ms | -30ms | -8.14
| addChannelMember | avg | 533ms | 509ms | -24ms | -4.50
| autocompleteUsers | avg | 70ms | 67ms | -3ms | -4.28
| addTeamMember | avg | 1.378s | 1.324s | -54ms | -3.92
| createDirectChannel | avg | 605ms | 582ms | -23ms | -3.80
| createUser | avg | 403ms | 391ms | -12ms | -2.97
| getTeamStats | avg | 73ms | 71ms | -2ms | -2.74
| getFilePreview | avg | 77ms | 75ms | -2ms | -2.61
| getProfileImage | avg | 81ms | 79ms | -2ms | -2.47
| searchPostsInTeam | avg | 101ms | 99ms | -2ms | -1.99
| createPost | avg | 720ms | 706ms | -14ms | -1.94
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateScheduledPost | p99 | 25ms | 0s | -25ms | -100.60
| updateChannelBookmark | p99 | 965ms | 246ms | -719ms | -74.51
| createCategoryForTeamForUser | p99 | 493ms | 238ms | -255ms | -51.78
| updateChannelBookmarkSortOrder | p99 | 488ms | 242ms | -246ms | -50.46
| followThreadByUser | p99 | 913ms | 775ms | -138ms | -15.11
| login | p99 | 2.18s | 1.858s | -322ms | -14.77
| searchPostsInTeam | p99 | 2.122s | 1.945s | -177ms | -8.34
| getPreferences | p99 | 179ms | 165ms | -14ms | -7.84
| setPostReminder | p99 | 785ms | 725ms | -60ms | -7.64
| createDirectChannel | p99 | 2.67s | 2.49s | -180ms | -6.74
| getDrafts | p99 | 234ms | 219ms | -15ms | -6.41
| addChannelMember | p99 | 3.259s | 3.121s | -138ms | -4.23
| removeUserCustomStatus | p99 | 2.071s | 1.99s | -81ms | -3.91
| unfollowThreadByUser | p99 | 485ms | 467ms | -18ms | -3.71
| getUsersByIds | p99 | 62ms | 60ms | -2ms | -3.23
| getChannelsForUser | p99 | 148ms | 144ms | -4ms | -2.71
| getChannelUnread | p99 | 227ms | 222ms | -5ms | -2.20
| getTeamMember | p99 | 179ms | 176ms | -3ms | -1.68
| getTeamScheduledPosts | p99 | 229ms | 226ms | -3ms | -1.31
| getAllTeams | p99 | 185ms | 183ms | -2ms | -1.08
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.016
| BotStore.Get |  Avg| 29ms| 6ms | -23ms | -79.223
| |  P99| 405ms| 42ms | -363ms | -89.630
| ChannelBookmarkStore.Delete |  Avg| 44ms| 15ms | -29ms | -65.365
| |  P99| 243ms| 95ms | -148ms | -60.843
| ChannelBookmarkStore.Get |  Avg| 24ms| 18ms | -6ms | -25.373
| |  P99| 212ms| 207ms | -5ms | -2.353
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 164ms| 164ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 49ms| 48ms | -1ms | -2.031
| |  P99| 234ms| 450ms | 216ms | 92.206
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 112ms| 42ms | -70ms | -62.532
| |  P99| 488ms| 239ms | -249ms | -51.077
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 80ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 244ms| 247ms | 3ms | 1.230
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 55ms| 49ms | -6ms | -10.874
| |  P99| 304ms| 419ms | 115ms | 37.808
| ChannelStore.CreateDirectChannel |  Avg| 97ms| 89ms | -8ms | -8.283
| |  P99| 881ms| 849ms | -32ms | -3.634
| ChannelStore.CreateInitialSidebarCategories |  Avg| 37ms| 35ms | -2ms | -5.453
| |  P99| 406ms| 410ms | 4ms | 0.986
| ChannelStore.CreateSidebarCategory |  Avg| 121ms| 26ms | -95ms | -78.793
| |  P99| 489ms| 238ms | -251ms | -51.355
| ChannelStore.Get |  Avg| 23ms| 24ms | 1ms | 4.290
| |  P99| 236ms| 244ms | 8ms | 3.386
| ChannelStore.GetAllChannelMembersForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 183ms| 180ms | -3ms | -1.636
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 22ms| 28ms | 6ms | 26.843
| |  P99| 230ms| 406ms | 176ms | 76.628
| ChannelStore.GetByName |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 152ms| 140ms | -12ms | -7.887
| ChannelStore.GetChannelUnread |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 213ms| 201ms | -12ms | -5.624
| ChannelStore.GetChannels |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 210ms| 213ms | 3ms | 1.431
| ChannelStore.GetChannelsByUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 136ms| 135ms | -1ms | -0.737
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 173ms| 179ms | 6ms | 3.459
| ChannelStore.GetFileCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 174ms| 171ms | -3ms | -1.725
| ChannelStore.GetForPost |  Avg| 19ms| 18ms | -1ms | -5.405
| |  P99| 217ms| 223ms | 6ms | 2.763
| ChannelStore.GetGuestCount |  Avg| 13ms| 12ms | -1ms | -7.952
| |  P99| 172ms| 162ms | -10ms | -5.811
| ChannelStore.GetMany |  Avg| 20ms| 25ms | 5ms | 25.264
| |  P99| 161ms| 233ms | 72ms | 44.583
| ChannelStore.GetMember |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 128ms| 120ms | -8ms | -6.255
| ChannelStore.GetMemberCount |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 229ms| 229ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 220ms| 219ms | -1ms | -0.455
| ChannelStore.GetMemberLastViewedAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 109ms| 104ms | -5ms | -4.603
| ChannelStore.GetMembers |  Avg| 18ms| 30ms | 12ms | 65.530
| |  P99| 96ms| 98ms | 2ms | 2.073
| ChannelStore.GetMembersForUser |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 204ms| 205ms | 1ms | 0.491
| ChannelStore.GetMembersForUserWithPagination |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 140ms| 144ms | 4ms | 2.864
| ChannelStore.GetPinnedPostCount |  Avg| 12ms| 13ms | 1ms | 8.379
| |  P99| 177ms| 198ms | 21ms | 11.864
| ChannelStore.GetPublicChannelsForTeam |  Avg| 32ms| 31ms | -1ms | -3.109
| |  P99| 235ms| 237ms | 2ms | 0.850
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 222ms| 221ms | -1ms | -0.451
| ChannelStore.GetSidebarCategory |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 233ms| 405ms | 172ms | 73.690
| ChannelStore.GetTeamChannels |  Avg| 50ms| 38ms | -12ms | -23.880
| |  P99| 438ms| 240ms | -198ms | -45.256
| ChannelStore.IncrementMentionCount |  Avg| 10ms| 9ms | -1ms | -10.263
| |  P99| 130ms| 110ms | -20ms | -15.412
| ChannelStore.Save |  Avg| 48ms| 50ms | 2ms | 4.130
| |  P99| 431ms| 471ms | 40ms | 9.278
| ChannelStore.SaveMember |  Avg| 69ms| 68ms | -1ms | -1.439
| |  P99| 625ms| 620ms | -5ms | -0.800
| ChannelStore.SearchGroupChannels |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 208ms| 223ms | 15ms | 7.226
| ChannelStore.UpdateLastViewedAt |  Avg| 12ms| 11ms | -1ms | -8.693
| |  P99| 102ms| 100ms | -2ms | -1.952
| ChannelStore.UpdateSidebarCategories |  Avg| 97ms| 120ms | 23ms | 23.621
| |  P99| 530ms| 1.18s | 650ms | 122.645
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 8ms| 9ms | 1ms | 11.971
| |  P99| 96ms| 116ms | 20ms | 20.824
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 20ms| 17ms | -3ms | -14.729
| |  P99| 217ms| 207ms | -10ms | -4.608
| CommandWebhookStore.Cleanup |  Avg| 19ms| 21ms | 2ms | 10.656
| |  P99| 97ms| 97ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 50ms| 0s | -50ms | -100.570
| |  P99| 50ms| 0s | -50ms | -100.503
| DraftStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 145ms| 142ms | -3ms | -2.072
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 14ms| 21ms | 7ms | 50.075
| |  P99| 78ms| 189ms | 111ms | 141.402
| DraftStore.Get |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 218ms| 227ms | 9ms | 4.128
| DraftStore.GetDraftsForUser |  Avg| 19ms| 17ms | -2ms | -10.554
| |  P99| 224ms| 204ms | -20ms | -8.943
| DraftStore.Upsert |  Avg| 16ms| 15ms | -1ms | -6.361
| |  P99| 187ms| 182ms | -5ms | -2.672
| EmojiStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 162ms| 171ms | 9ms | 5.550
| EmojiStore.GetMultipleByName |  Avg| 32ms| 33ms | 1ms | 3.145
| |  P99| 240ms| 98ms | -142ms | -59.105
| FileInfoStore.AttachToPost |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 212ms| 221ms | 9ms | 4.254
| FileInfoStore.Get |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 198ms| 197ms | -1ms | -0.505
| FileInfoStore.GetByIds |  Avg| 15ms| 14ms | -1ms | -6.468
| |  P99| 210ms| 202ms | -8ms | -3.815
| FileInfoStore.GetForPost |  Avg| 13ms| 12ms | -1ms | -7.939
| |  P99| 185ms| 187ms | 2ms | 1.078
| FileInfoStore.Save |  Avg| 17ms| 16ms | -1ms | -5.790
| |  P99| 197ms| 191ms | -6ms | -3.044
| FileInfoStore.SetContent |  Avg| 23ms| 24ms | 1ms | 4.389
| |  P99| 225ms| 223ms | -2ms | -0.889
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 90ms | -2ms | -2.168
| GroupStore.GetByName |  Avg| 8ms| 9ms | 1ms | 11.988
| |  P99| 97ms| 97ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 154ms| 158ms | 4ms | 2.599
| JobStore.GetAllByStatus |  Avg| 19ms| 16ms | -3ms | -16.103
| |  P99| 233ms| 207ms | -26ms | -11.143
| JobStore.GetCountByStatusAndType |  Avg| 14ms| 12ms | -2ms | -13.857
| |  P99| 202ms| 186ms | -16ms | -7.906
| JobStore.GetNewestJobByStatusesAndType |  Avg| 11ms| 8ms | -3ms | -26.827
| |  P99| 204ms| 96ms | -108ms | -52.993
| JobStore.Save |  Avg| 13ms| 7ms | -6ms | -47.869
| |  P99| 187ms| 46ms | -141ms | -75.200
| JobStore.UpdateOptimistically |  Avg| 11ms| 10ms | -1ms | -9.211
| |  P99| 157ms| 115ms | -42ms | -26.748
| JobStore.UpdateStatus |  Avg| 13ms| 11ms | -2ms | -15.786
| |  P99| 204ms| 169ms | -35ms | -17.199
| JobStore.UpdateStatusOptimistically |  Avg| 12ms| 17ms | 5ms | 40.482
| |  P99| 97ms| 209ms | 112ms | 115.460
| LinkMetadataStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 146ms| 162ms | 16ms | 10.947
| LinkMetadataStore.Save |  Avg| 10ms| 9ms | -1ms | -10.025
| |  P99| 186ms| 76ms | -110ms | -59.298
| PostAcknowledgementStore.GetForPost |  Avg| 8ms| 9ms | 1ms | 12.116
| |  P99| 115ms| 137ms | 22ms | 19.103
| PostAcknowledgementStore.GetForPosts |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 228ms| 233ms | 5ms | 2.192
| PostPersistentNotificationStore.DeleteExpired |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 84ms| 86ms | 2ms | 2.381
| PostPersistentNotificationStore.Get |  Avg| 9ms| 14ms | 5ms | 54.496
| |  P99| 154ms| 350ms | 196ms | 127.256
| PostPersistentNotificationStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 110ms| 122ms | 12ms | 10.941
| PostPriorityStore.GetForPostWithContext |  Avg| 8ms| 9ms | 1ms | 11.975
| |  P99| 115ms| 138ms | 23ms | 20.041
| PostPriorityStore.GetForPosts |  Avg| 16ms| 17ms | 1ms | 6.108
| |  P99| 232ms| 236ms | 4ms | 1.727
| PostStore.AnalyticsPostCount |  Avg| 347ms| 314ms | -33ms | -9.519
| |  P99| 498ms| 980ms | 482ms | 96.884
| PostStore.Delete |  Avg| 51ms| 43ms | -8ms | -15.777
| |  P99| 392ms| 397ms | 5ms | 1.274
| PostStore.Get |  Avg| 33ms| 32ms | -1ms | -3.074
| |  P99| 276ms| 318ms | 42ms | 15.231
| PostStore.GetEtag |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 202ms| 206ms | 4ms | 1.980
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 78ms| 76ms | -2ms | -2.572
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 93ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 19ms| 12ms | -7ms | -37.088
| |  P99| 219ms| 100ms | -119ms | -54.369
| PostStore.GetPostReminders |  Avg| 14ms| 6ms | -8ms | -55.520
| |  P99| 193ms| 46ms | -147ms | -76.166
| PostStore.GetPosts |  Avg| 8ms| 9ms | 1ms | 11.826
| |  P99| 93ms| 95ms | 2ms | 2.154
| PostStore.GetPostsAfter |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 187ms| 183ms | -4ms | -2.142
| PostStore.GetPostsBefore |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 205ms| 208ms | 3ms | 1.466
| PostStore.GetPostsByThread |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 163ms| 178ms | 15ms | 9.199
| PostStore.GetPostsSince |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 230ms| 232ms | 2ms | 0.870
| PostStore.GetSingle |  Avg| 9ms| 10ms | 1ms | 10.718
| |  P99| 136ms| 153ms | 17ms | 12.517
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 40ms| 38ms | -2ms | -4.955
| |  P99| 410ms| 404ms | -6ms | -1.462
| PostStore.SearchPostsForUser |  Avg| 71ms| 67ms | -4ms | -5.652
| |  P99| 2.028s| 1.847s | -181ms | -8.927
| PostStore.SetPostReminder |  Avg| 34ms| 23ms | -11ms | -32.113
| |  P99| 237ms| 229ms | -8ms | -3.374
| PostStore.Update |  Avg| 34ms| 32ms | -2ms | -5.965
| |  P99| 243ms| 303ms | 60ms | 24.641
| PreferenceStore.DeleteCategoryAndName |  Avg| 7ms| 17ms | 10ms | 139.418
| |  P99| 46ms| 219ms | 173ms | 372.711
| PreferenceStore.Get |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 198ms| 202ms | 4ms | 2.022
| PreferenceStore.GetAll |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 169ms| 153ms | -16ms | -9.470
| PreferenceStore.Save |  Avg| 30ms| 29ms | -1ms | -3.344
| |  P99| 297ms| 298ms | 1ms | 0.337
| ProductNoticesStore.ClearOldNotices |  Avg| 59ms| 41ms | -18ms | -30.715
| |  P99| 99ms| 50ms | -49ms | -49.370
| ProductNoticesStore.View |  Avg| 99ms| 96ms | -3ms | -3.024
| |  P99| 885ms| 902ms | 17ms | 1.922
| PropertyFieldStore.SearchPropertyFields |  Avg| 9ms| 8ms | -1ms | -10.709
| |  P99| 131ms| 98ms | -33ms | -25.135
| PropertyValueStore.SearchPropertyValues |  Avg| 15ms| 14ms | -1ms | -6.758
| |  P99| 205ms| 195ms | -10ms | -4.889
| ReactionStore.GetForPost |  Avg| 14ms| 10ms | -4ms | -28.947
| |  P99| 188ms| 99ms | -89ms | -47.239
| RoleStore.ChannelHigherScopedPermissions |  Avg| 9ms| 67ms | 58ms | 647.823
| |  P99| 48ms| 440ms | 392ms | 814.545
| RoleStore.GetByNames |  Avg| 27ms| 55ms | 28ms | 104.461
| |  P99| 151ms| 242ms | 91ms | 60.265
| ScheduledPostStore.CreateScheduledPost |  Avg| 10ms| 17ms | 7ms | 66.956
| |  P99| 84ms| 170ms | 86ms | 101.927
| ScheduledPostStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 43ms| 11ms | -32ms | -75.161
| |  P99| 805ms| 48ms | -757ms | -94.037
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 9ms| 8ms | -1ms | -11.547
| |  P99| 107ms| 100ms | -7ms | -6.524
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 19ms| 5ms | -14ms | -72.946
| |  P99| 191ms| 46ms | -145ms | -75.718
| ScheduledPostStore.UpdatedScheduledPost |  Avg| 10ms| 0s | -10ms | -103.591
| |  P99| 10ms| 0s | -10ms | -100.503
| SessionStore.Get |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 228ms| 232ms | 4ms | 1.751
| SessionStore.GetLRUSessions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 96ms| 96ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 7ms| 25ms | 18ms | 272.072
| |  P99| 46ms| 231ms | 185ms | 402.165
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 130ms| 152ms | 22ms | 16.985
| SessionStore.Remove |  Avg| 11ms| 14ms | 3ms | 26.158
| |  P99| 181ms| 95ms | -86ms | -47.513
| SessionStore.Save |  Avg| 16ms| 15ms | -1ms | -6.443
| |  P99| 192ms| 194ms | 2ms | 1.042
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 96ms | -1ms | -1.035
| StatusStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 178ms| 188ms | 10ms | 5.621
| StatusStore.GetByIds |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 227ms| 232ms | 5ms | 2.207
| StatusStore.SaveOrUpdate |  Avg| 14ms| 13ms | -1ms | -7.339
| |  P99| 168ms| 162ms | -6ms | -3.563
| StatusStore.SaveOrUpdateMany |  Avg| 24ms| 25ms | 1ms | 4.094
| |  P99| 237ms| 236ms | -1ms | -0.422
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 25ms| 16ms | -9ms | -35.539
| |  P99| 220ms| 160ms | -60ms | -27.254
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 9ms | -1ms | -10.111
| |  P99| 98ms| 97ms | -1ms | -1.025
| SystemStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 97ms| 96ms | -1ms | -1.031
| TeamStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 124ms| 143ms | 19ms | 15.377
| TeamStore.GetActiveMemberCount |  Avg| 69ms| 64ms | -5ms | -7.229
| |  P99| 238ms| 230ms | -8ms | -3.368
| TeamStore.GetAllPage |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 141ms| 139ms | -2ms | -1.417
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 155ms| 149ms | -6ms | -3.881
| TeamStore.GetMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 91ms| 88ms | -3ms | -3.299
| TeamStore.GetTeamsByUserId |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 136ms| 140ms | 4ms | 2.943
| TeamStore.GetTeamsForUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 130ms| 144ms | 14ms | 10.729
| TeamStore.GetTotalMemberCount |  Avg| 62ms| 61ms | -1ms | -1.606
| |  P99| 231ms| 236ms | 5ms | 2.162
| TeamStore.SaveMember |  Avg| 43ms| 41ms | -2ms | -4.677
| |  P99| 300ms| 252ms | -48ms | -16.003
| TemporaryPostStore.GetExpiredPosts |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 92ms| 94ms | 2ms | 2.173
| ThreadStore.Get |  Avg| 13ms| 9ms | -4ms | -31.973
| |  P99| 189ms| 90ms | -99ms | -52.283
| ThreadStore.GetMembershipForUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 178ms| 182ms | 4ms | 2.252
| ThreadStore.GetTeamsUnreadForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 202ms| 206ms | 4ms | 1.976
| ThreadStore.GetThreadFollowers |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 137ms| 148ms | 11ms | 8.052
| ThreadStore.GetThreadForUser |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 230ms| 232ms | 2ms | 0.868
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 21ms| 22ms | 1ms | 4.673
| |  P99| 190ms| 201ms | 11ms | 5.788
| ThreadStore.GetThreadsForUser |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 213ms| 217ms | 4ms | 1.876
| ThreadStore.GetTotalThreads |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 142ms| 133ms | -9ms | -6.323
| ThreadStore.GetTotalUnreadMentions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 144ms| 144ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 141ms| 132ms | -9ms | -6.401
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 142ms| 136ms | -6ms | -4.213
| ThreadStore.MaintainMembership |  Avg| 21ms| 20ms | -1ms | -4.740
| |  P99| 238ms| 233ms | -5ms | -2.099
| ThreadStore.MarkAllAsReadByChannels |  Avg| 11ms| 13ms | 2ms | 17.882
| |  P99| 110ms| 147ms | 37ms | 33.727
| ThreadStore.MarkAllAsReadByTeam |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 97ms| 97ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 10ms| 9ms | -1ms | -10.281
| |  P99| 94ms| 93ms | -1ms | -1.065
| ThreadStore.UpdateMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 94ms | 1ms | 1.072
| TokenStore.Cleanup |  Avg| 24ms| 14ms | -10ms | -41.552
| |  P99| 241ms| 48ms | -193ms | -80.083
| UserAccessTokenStore.GetByToken |  Avg| 13ms| 15ms | 2ms | 15.268
| |  P99| 175ms| 158ms | -17ms | -9.714
| UserStore.AutocompleteUsersInChannel |  Avg| 76ms| 75ms | -1ms | -1.318
| |  P99| 375ms| 390ms | 15ms | 3.996
| UserStore.Count |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 189ms| 192ms | 3ms | 1.590
| UserStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 182ms| 180ms | -2ms | -1.100
| UserStore.GetAllProfiles |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 94ms | 2ms | 2.185
| UserStore.GetAllProfilesInChannel |  Avg| 373ms| 360ms | -13ms | -3.485
| |  P99| 2.121s| 2.1s | -21ms | -0.990
| UserStore.GetByUsername |  Avg| 17ms| 12ms | -5ms | -30.063
| |  P99| 226ms| 147ms | -79ms | -35.014
| UserStore.GetForLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 120ms| 128ms | 8ms | 6.671
| UserStore.GetMany |  Avg| 17ms| 12ms | -5ms | -29.360
| |  P99| 362ms| 198ms | -164ms | -45.243
| UserStore.GetProfileByIds |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 202ms| 207ms | 5ms | 2.480
| UserStore.GetProfilesByUsernames |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 207ms| 210ms | 3ms | 1.451
| UserStore.GetProfilesInChannel |  Avg| 21ms| 15ms | -6ms | -28.778
| |  P99| 228ms| 201ms | -27ms | -11.829
| UserStore.GetProfilesNotInChannel |  Avg| 24ms| 11ms | -13ms | -54.459
| |  P99| 437ms| 86ms | -351ms | -80.229
| UserStore.GetUnreadCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 147ms| 162ms | 15ms | 10.188
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 56ms | 7ms | 14.171
| UserStore.Save |  Avg| 175ms| 172ms | -3ms | -1.712
| |  P99| 618ms| 633ms | 15ms | 2.429
| UserStore.Search |  Avg| 49ms| 50ms | 1ms | 2.024
| |  P99| 241ms| 243ms | 2ms | 0.830
| UserStore.Update |  Avg| 28ms| 30ms | 2ms | 7.239
| |  P99| 242ms| 245ms | 3ms | 1.240
| UserStore.UpdateFailedPasswordAttempts |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 98ms | 1ms | 1.032
| UserStore.UpdateLastLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 81ms | -6ms | -6.923
| UserStore.UpdateUpdateAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 82ms| 81ms | -1ms | -1.221
| UserTermsOfServiceStore.GetByUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 129ms| 120ms | -9ms | -6.996
| WebhookStore.GetOutgoingByTeam |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 214ms| 218ms | 4ms | 1.873
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 533ms| 509ms | -24ms | -4.500
| | P99| 3.259s| 3.121s | -138ms | -4.234
| addTeamMember | Avg| 1.378s| 1.324s | -54ms | -3.919
| | P99| 8.63s| 8.574s | -56ms | -0.649
| autocompleteChannelsForTeamForSearch | Avg| 56ms| 49ms | -7ms | -12.570
| | P99| 332ms| 433ms | 101ms | 30.409
| autocompleteUsers | Avg| 70ms| 67ms | -3ms | -4.275
| | P99| 389ms| 390ms | 1ms | 0.257
| createCategoryForTeamForUser | Avg| 143ms| 29ms | -114ms | -79.973
| | P99| 493ms| 238ms | -255ms | -51.777
| createChannel | Avg| 697ms| 596ms | -101ms | -14.499
| | P99| 2.437s| 4.325s | 1.888s | 77.456
| createChannelBookmark | Avg| 63ms| 81ms | 18ms | 28.775
| | P99| 457ms| 461ms | 4ms | 0.874
| createDirectChannel | Avg| 605ms| 582ms | -23ms | -3.801
| | P99| 2.67s| 2.49s | -180ms | -6.742
| createGroupChannel | Avg| 927ms| 946ms | 19ms | 2.049
| | P99| 4.575s| 5.383s | 808ms | 17.661
| createPost | Avg| 720ms| 706ms | -14ms | -1.945
| | P99| 4.534s| 4.607s | 73ms | 1.610
| createSchedulePost | Avg| 13ms| 25ms | 12ms | 93.378
| | P99| 97ms| 247ms | 150ms | 153.847
| createUser | Avg| 403ms| 391ms | -12ms | -2.974
| | P99| 2.266s| 2.255s | -11ms | -0.485
| deleteChannelBookmark | Avg| 36ms| 65ms | 29ms | 80.589
| | P99| 240ms| 245ms | 5ms | 2.088
| deleteDraft | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 224ms| 234ms | 10ms | 4.463
| deletePost | Avg| 83ms| 86ms | 3ms | 3.617
| | P99| 785ms| 795ms | 10ms | 1.274
| followThreadByUser | Avg| 107ms| 70ms | -37ms | -34.704
| | P99| 913ms| 775ms | -138ms | -15.110
| getAllTeams | Avg| 12ms| 11ms | -1ms | -8.584
| | P99| 185ms| 183ms | -2ms | -1.081
| getCategoriesForTeamForUser | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 229ms| 229ms | 0s | 0.000
| getChannel | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 323ms| 333ms | 10ms | 3.092
| getChannelMember | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 242ms| 245ms | 3ms | 1.238
| getChannelMembers | Avg| 19ms| 41ms | 22ms | 116.061
| | P99| 96ms| 238ms | 142ms | 147.150
| getChannelMembersForTeamForUser | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 207ms| 209ms | 2ms | 0.964
| getChannelMembersForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 147ms| 152ms | 5ms | 3.394
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 157ms| 159ms | 2ms | 1.275
| getChannelUnread | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 227ms| 222ms | -5ms | -2.202
| getChannelsForTeamForUser | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 214ms| 218ms | 4ms | 1.868
| getChannelsForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 148ms| 144ms | -4ms | -2.711
| getClientConfig | Avg| 23ms| 22ms | -1ms | -4.255
| | P99| 246ms| 245ms | -1ms | -0.406
| getDrafts | Avg| 21ms| 18ms | -3ms | -14.541
| | P99| 234ms| 219ms | -15ms | -6.407
| getFilePreview | Avg| 77ms| 75ms | -2ms | -2.609
| | P99| 443ms| 441ms | -2ms | -0.451
| getFileThumbnail | Avg| 72ms| 71ms | -1ms | -1.388
| | P99| 418ms| 418ms | 0s | 0.000
| getPostThread | Avg| 74ms| 76ms | 2ms | 2.685
| | P99| 698ms| 802ms | 104ms | 14.895
| getPostsForChannel | Avg| 152ms| 155ms | 3ms | 1.977
| | P99| 2.103s| 2.17s | 67ms | 3.187
| getPostsForChannelAroundLastUnread | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 541ms| 566ms | 25ms | 4.624
| getPreferences | Avg| 12ms| 11ms | -1ms | -8.480
| | P99| 179ms| 165ms | -14ms | -7.839
| getProfileImage | Avg| 81ms| 79ms | -2ms | -2.472
| | P99| 488ms| 491ms | 3ms | 0.614
| getPublicChannelsForTeam | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 242ms| 260ms | 18ms | 7.434
| getTeamMember | Avg| 13ms| 12ms | -1ms | -7.685
| | P99| 179ms| 176ms | -3ms | -1.676
| getTeamMembersForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 172ms| 176ms | 4ms | 2.332
| getTeamScheduledPosts | Avg| 18ms| 17ms | -1ms | -5.624
| | P99| 229ms| 226ms | -3ms | -1.309
| getTeamStats | Avg| 73ms| 71ms | -2ms | -2.742
| | P99| 238ms| 242ms | 4ms | 1.684
| getTeamsForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 147ms| 149ms | 2ms | 1.357
| getTeamsUnreadForUser | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 241ms| 242ms | 1ms | 0.415
| getThreadsForUser | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 220ms| 224ms | 4ms | 1.814
| getUser | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 272ms| 275ms | 3ms | 1.103
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 98ms| 97ms | -1ms | -1.021
| getUsers | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 244ms| 245ms | 1ms | 0.409
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 62ms| 60ms | -2ms | -3.235
| getUsersByNames | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 213ms| 216ms | 3ms | 1.407
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 11ms| 19ms | 8ms | 73.140
| | P99| 172ms| 237ms | 65ms | 37.811
| listCPAValues | Avg| 16ms| 31ms | 15ms | 93.775
| | P99| 215ms| 372ms | 157ms | 72.957
| listChannelBookmarksForChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 191ms| 193ms | 2ms | 1.045
| login | Avg| 222ms| 195ms | -27ms | -12.142
| | P99| 2.18s| 1.858s | -322ms | -14.774
| logout | Avg| 142ms| 165ms | 23ms | 16.254
| | P99| 923ms| 1.585s | 662ms | 71.697
| patchPost | Avg| 126ms| 115ms | -11ms | -8.706
| | P99| 947ms| 1.335s | 388ms | 40.978
| removeUserCustomStatus | Avg| 369ms| 339ms | -30ms | -8.139
| | P99| 2.071s| 1.99s | -81ms | -3.911
| root | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 228ms| 228ms | 0s | 0.000
| saveReaction | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 450ms| 462ms | 12ms | 2.664
| searchAllChannels | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 246ms| 249ms | 3ms | 1.217
| searchGroupChannels | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 212ms| 227ms | 15ms | 7.064
| searchPostsInTeam | Avg| 101ms| 99ms | -2ms | -1.989
| | P99| 2.122s| 1.945s | -177ms | -8.343
| searchUsers | Avg| 51ms| 52ms | 1ms | 1.949
| | P99| 243ms| 246ms | 3ms | 1.235
| setPostReminder | Avg| 94ms| 83ms | -11ms | -11.700
| | P99| 785ms| 725ms | -60ms | -7.643
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 72ms| 60ms | -12ms | -16.741
| | P99| 485ms| 467ms | -18ms | -3.714
| updateCategoriesForTeamForUser | Avg| 164ms| 194ms | 30ms | 18.247
| | P99| 922ms| 2.06s | 1.138s | 123.472
| updateChannelBookmark | Avg| 180ms| 71ms | -109ms | -60.595
| | P99| 965ms| 246ms | -719ms | -74.507
| updateChannelBookmarkSortOrder | Avg| 161ms| 59ms | -102ms | -63.543
| | P99| 488ms| 242ms | -246ms | -50.461
| updatePreferences | Avg| 42ms| 43ms | 1ms | 2.357
| | P99| 418ms| 440ms | 22ms | 5.267
| updateReadStateAllThreadsByUser | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 97ms| 97ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 148ms| 149ms | 1ms | 0.677
| | P99| 974ms| 1.284s | 310ms | 31.818
| updateScheduledPost | Avg| 15ms| 0s | -15ms | -97.717
| | P99| 25ms| 0s | -25ms | -100.604
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -153.244
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 597ms| 592ms | -5ms | -0.838
| | P99| 2.334s| 2.339s | 5ms | 0.214
| upsertDraft | Avg| 21ms| 20ms | -1ms | -4.791
| | P99| 228ms| 228ms | 0s | 0.000
| viewChannel | Avg| 56ms| 56ms | 0s | 0.000
| | P99| 510ms| 592ms | 82ms | 16.067

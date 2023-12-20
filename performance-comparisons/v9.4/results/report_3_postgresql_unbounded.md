### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 25ms | 23ms | 1292.95
| ChannelStore.GetByNameIncludeDeleted | avg | 2ms | 20ms | 18ms | 852.26
| TokenStore.Cleanup | avg | 3ms | 28ms | 25ms | 743.51
| CommandWebhookStore.Cleanup | avg | 4ms | 28ms | 24ms | 682.66
| UserStore.AnalyticsGetInactiveUsersCount | avg | 1ms | 5ms | 4ms | 339.89
| UserAccessTokenStore.GetByToken | avg | 3ms | 12ms | 9ms | 257.73
| SessionStore.GetSessionsExpired | avg | 2ms | 6ms | 4ms | 193.42
| PostStore.Delete | avg | 44ms | 78ms | 34ms | 76.99
| PreferenceStore.DeleteCategoryAndName | avg | 9ms | 14ms | 5ms | 58.32
| ChannelStore.GetMember | avg | 5ms | 8ms | 3ms | 57.66
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 6ms | 2ms | 53.57
| StatusStore.UpdateExpiredDNDStatuses | avg | 6ms | 9ms | 3ms | 46.26
| FileInfoStore.AttachToPost | avg | 13ms | 15ms | 2ms | 15.14
| ProductNoticesStore.ClearOldNotices | avg | 36ms | 41ms | 5ms | 13.95
| ChannelStore.UpdateSidebarCategories | avg | 137ms | 154ms | 17ms | 12.43
| UserStore.Update | avg | 20ms | 22ms | 2ms | 9.98
| StatusStore.SaveOrUpdate | avg | 83ms | 91ms | 8ms | 9.64
| PostStore.SearchPostsForUser | avg | 244ms | 261ms | 17ms | 6.98
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 50ms | 45ms | 909.09
| TokenStore.Cleanup | p99 | 10ms | 99ms | 89ms | 898.89
| CommandWebhookStore.Cleanup | p99 | 10ms | 99ms | 89ms | 898.89
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 25ms | 20ms | 403.60
| SessionStore.GetSessionsExpired | p99 | 5ms | 24ms | 19ms | 383.84
| ThreadStore.Get | p99 | 71ms | 163ms | 92ms | 129.12
| UserAccessTokenStore.GetByToken | p99 | 43ms | 92ms | 49ms | 114.14
| PostPersistentNotificationStore.DeleteExpired | p99 | 23ms | 47ms | 24ms | 103.23
| StatusStore.UpdateExpiredDNDStatuses | p99 | 44ms | 89ms | 45ms | 101.69
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 10ms | 5ms | 100.91
| PostAcknowledgementStore.GetForPost | p99 | 52ms | 104ms | 52ms | 99.68
| PreferenceStore.DeleteCategoryAndName | p99 | 47ms | 92ms | 45ms | 94.99
| ChannelStore.CreateSidebarCategory | p99 | 247ms | 480ms | 233ms | 94.33
| PostStore.Delete | p99 | 239ms | 458ms | 219ms | 91.44
| ChannelStore.UpdateSidebarCategories | p99 | 487ms | 922ms | 435ms | 89.31
| ChannelStore.GetMember | p99 | 48ms | 84ms | 36ms | 75.68
| FileInfoStore.AttachToPost | p99 | 97ms | 133ms | 36ms | 37.24
| PostPriorityStore.GetForPosts | p99 | 99ms | 125ms | 26ms | 26.26
| ChannelStore.CreateInitialSidebarCategories | p99 | 277ms | 340ms | 63ms | 22.77
| ChannelStore.GetSidebarCategory | p99 | 229ms | 275ms | 46ms | 20.09
| PostAcknowledgementStore.GetForPosts | p99 | 97ms | 115ms | 18ms | 18.47
| JobStore.UpdateOptimistically | p99 | 81ms | 94ms | 13ms | 16.04
| GroupStore.GetGroups | p99 | 69ms | 80ms | 11ms | 15.85
| UserStore.Get | p99 | 65ms | 75ms | 10ms | 15.36
| PostPersistentNotificationStore.GetSingle | p99 | 61ms | 70ms | 9ms | 14.70
| ThreadStore.GetThreadForUser | p99 | 135ms | 150ms | 15ms | 11.10
| ThreadStore.GetThreadFollowers | p99 | 66ms | 73ms | 7ms | 10.59
| TeamStore.GetMember | p99 | 38ms | 42ms | 4ms | 10.55
| UserStore.GetUnreadCount | p99 | 76ms | 84ms | 8ms | 10.51
| TeamStore.Get | p99 | 67ms | 74ms | 7ms | 10.39
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 50ms | 55ms | 5ms | 10.00
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 62ms | 68ms | 6ms | 9.70
| ChannelStore.GetFileCount | p99 | 83ms | 91ms | 8ms | 9.58
| PostStore.Get | p99 | 187ms | 203ms | 16ms | 8.55
| ThreadStore.MaintainMembership | p99 | 178ms | 193ms | 15ms | 8.41
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 68ms | 73ms | 5ms | 7.32
| ThreadStore.MarkAsRead | p99 | 69ms | 74ms | 5ms | 7.24
| ChannelStore.Get | p99 | 86ms | 92ms | 6ms | 6.94
| PostStore.GetSingle | p99 | 73ms | 78ms | 5ms | 6.87
| ThreadStore.GetTotalUnreadThreads | p99 | 75ms | 80ms | 5ms | 6.69
| LinkMetadataStore.Get | p99 | 77ms | 82ms | 5ms | 6.47
| PostPriorityStore.GetForPost | p99 | 79ms | 84ms | 5ms | 6.29
| ComplianceStore.MessageExport | p99 | 94ms | 99ms | 5ms | 5.32
| ThreadStore.GetTotalThreads | p99 | 76ms | 80ms | 4ms | 5.25
| PostStore.GetPostsByThread | p99 | 87ms | 91ms | 4ms | 4.62
| TeamStore.GetTeamsByUserId | p99 | 72ms | 75ms | 3ms | 4.18
| SessionStore.UpdateLastActivityAt | p99 | 73ms | 76ms | 3ms | 4.13
| ChannelStore.IncrementMentionCount | p99 | 75ms | 78ms | 3ms | 3.98
| ThreadStore.GetTotalUnreadMentions | p99 | 76ms | 79ms | 3ms | 3.97
| PostStore.Save | p99 | 234ms | 243ms | 9ms | 3.85
| FileInfoStore.SetContent | p99 | 183ms | 190ms | 7ms | 3.82
| ThreadStore.GetMembershipForUser | p99 | 80ms | 83ms | 3ms | 3.75
| FileInfoStore.GetForPost | p99 | 81ms | 84ms | 3ms | 3.72
| ProductNoticesStore.View | p99 | 475ms | 492ms | 17ms | 3.58
| ThreadStore.GetThreadUnreadReplyCount | p99 | 97ms | 100ms | 3ms | 3.09
| ChannelStore.SaveMember | p99 | 389ms | 401ms | 12ms | 3.09
| UserTermsOfServiceStore.GetByUser | p99 | 66ms | 68ms | 2ms | 3.03
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 78ms | 80ms | 2ms | 2.55
| ChannelStore.UpdateLastViewedAt | p99 | 79ms | 81ms | 2ms | 2.53
| PreferenceStore.Save | p99 | 203ms | 208ms | 5ms | 2.47
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 83ms | 85ms | 2ms | 2.41
| ChannelStore.GetChannelUnread | p99 | 87ms | 89ms | 2ms | 2.31
| FileInfoStore.Get | p99 | 89ms | 91ms | 2ms | 2.24
| PreferenceStore.Get | p99 | 89ms | 91ms | 2ms | 2.24
| FileInfoStore.Save | p99 | 91ms | 93ms | 2ms | 2.19
| WebhookStore.GetOutgoingByTeam | p99 | 92ms | 94ms | 2ms | 2.18
| PostStore.GetPostsBefore | p99 | 92ms | 94ms | 2ms | 2.18
| ThreadStore.GetThreadsForUser | p99 | 93ms | 95ms | 2ms | 2.16
| StatusStore.SaveOrUpdate | p99 | 937ms | 956ms | 19ms | 2.03
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 18ms | 0s | -18ms | -99.94
| UserStore.GetRecentlyActiveUsersForTeam | avg | 129ms | 0s | -129ms | -99.79
| EmojiStore.GetMultipleByName | avg | 9ms | 0s | -9ms | -97.06
| UserStore.GetNewUsersForTeam | avg | 5ms | 0s | -5ms | -96.59
| FileInfoStore.Search | avg | 13ms | 0s | -13ms | -96.48
| DraftStore.Delete | avg | 4ms | 0s | -4ms | -96.16
| ChannelStore.GetMembers | avg | 244ms | 22ms | -222ms | -91.09
| DraftStore.Get | avg | 5ms | 1ms | -4ms | -85.42
| BotStore.Get | avg | 15ms | 5ms | -10ms | -68.73
| PluginStore.List | avg | 40ms | 14ms | -26ms | -65.26
| PluginStore.Get | avg | 13ms | 5ms | -8ms | -63.67
| UserStore.AnalyticsActiveCount | avg | 106ms | 41ms | -65ms | -61.11
| DraftStore.Upsert | avg | 10ms | 5ms | -5ms | -51.62
| JobStore.GetCountByStatusAndType | avg | 12ms | 6ms | -6ms | -50.07
| SessionStore.Remove | avg | 10ms | 5ms | -5ms | -50.00
| JobStore.GetNewestJobByStatusesAndType | avg | 10ms | 5ms | -5ms | -48.34
| ChannelStore.GetMembersForUserWithPagination | avg | 82ms | 43ms | -39ms | -47.83
| ChannelStore.GetTeamChannels | avg | 63ms | 33ms | -30ms | -47.39
| JobStore.GetAllByTypePage | avg | 17ms | 9ms | -8ms | -46.71
| TeamStore.AnalyticsTeamCount | avg | 17ms | 9ms | -8ms | -46.39
| ChannelStore.AnalyticsTypeCount | avg | 36ms | 20ms | -16ms | -44.94
| PostStore.SetPostReminder | avg | 22ms | 13ms | -9ms | -41.00
| RoleStore.ChannelHigherScopedPermissions | avg | 10ms | 6ms | -4ms | -40.67
| UserStore.Count | avg | 57ms | 35ms | -22ms | -38.79
| JobStore.Save | avg | 8ms | 5ms | -3ms | -37.97
| JobStore.Get | avg | 15ms | 10ms | -5ms | -33.34
| PostStore.GetPostReminderMetadata | avg | 13ms | 9ms | -4ms | -31.36
| LicenseStore.GetAll | avg | 14ms | 10ms | -4ms | -27.86
| LinkMetadataStore.Save | avg | 11ms | 8ms | -3ms | -26.91
| UserStore.GetProfilesInChannel | avg | 370ms | 271ms | -99ms | -26.78
| ChannelStore.CreateSidebarCategory | avg | 122ms | 90ms | -32ms | -26.28
| ChannelStore.CreateDirectChannel | avg | 67ms | 50ms | -17ms | -25.30
| PostStore.GetPostReminders | avg | 15ms | 12ms | -3ms | -19.83
| ChannelStore.Save | avg | 41ms | 33ms | -8ms | -19.37
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 168ms | 137ms | -31ms | -18.41
| StatusStore.GetByIds | avg | 12ms | 10ms | -2ms | -17.36
| ChannelStore.GetChannelsByUser | avg | 12ms | 10ms | -2ms | -17.20
| PostStore.GetPostsAfter | avg | 12ms | 10ms | -2ms | -16.44
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 33ms | 28ms | -5ms | -15.28
| ChannelStore.GetPublicChannelsForTeam | avg | 38ms | 34ms | -4ms | -10.55
| ChannelStore.Autocomplete | avg | 75ms | 69ms | -6ms | -7.96
| UserStore.Search | avg | 66ms | 61ms | -5ms | -7.52
| UserStore.AutocompleteUsersInChannel | avg | 96ms | 89ms | -7ms | -7.27
| PostStore.Update | avg | 28ms | 26ms | -2ms | -7.12
| PostStore.AnalyticsPostCount | avg | 570ms | 547ms | -23ms | -4.03
| UserStore.GetAllProfilesInChannel | avg | 454ms | 436ms | -18ms | -3.97
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Delete | p99 | 5ms | 0s | -5ms | -100.91
| FileInfoStore.Search | p99 | 25ms | 0s | -25ms | -100.60
| UserStore.GetNewUsersForTeam | p99 | 10ms | 0s | -10ms | -100.44
| ChannelStore.GetMemberCountsByGroup | p99 | 97ms | 0s | -97ms | -100.26
| UserStore.GetRecentlyActiveUsersForTeam | p99 | 249ms | 0s | -249ms | -100.20
| EmojiStore.GetMultipleByName | p99 | 95ms | 0s | -95ms | -99.48
| ChannelStore.GetMembers | p99 | 938ms | 97ms | -841ms | -89.67
| DraftStore.Get | p99 | 24ms | 5ms | -19ms | -79.33
| TeamStore.AnalyticsTeamCount | p99 | 96ms | 24ms | -72ms | -75.00
| PluginStore.Get | p99 | 93ms | 24ms | -69ms | -74.19
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.667s | 437ms | -1.23s | -73.77
| BotStore.Get | p99 | 88ms | 24ms | -64ms | -73.14
| JobStore.Save | p99 | 70ms | 23ms | -47ms | -66.67
| JobStore.GetAllByTypePage | p99 | 222ms | 86ms | -136ms | -61.40
| ChannelStore.GetTeamChannels | p99 | 243ms | 98ms | -145ms | -59.79
| UserStore.Count | p99 | 237ms | 98ms | -139ms | -58.77
| RetentionPolicyStore.GetAll | p99 | 24ms | 10ms | -14ms | -57.38
| UserStore.GetProfilesInChannel | p99 | 1.713s | 832ms | -881ms | -51.44
| JobStore.GetCountByStatusAndType | p99 | 91ms | 45ms | -46ms | -50.72
| JobStore.GetNewestJobByStatusesAndType | p99 | 91ms | 46ms | -45ms | -49.45
| ChannelStore.AnalyticsTypeCount | p99 | 97ms | 49ms | -48ms | -49.42
| PostPersistentNotificationStore.Get | p99 | 82ms | 45ms | -37ms | -44.85
| RoleStore.ChannelHigherScopedPermissions | p99 | 64ms | 36ms | -28ms | -43.75
| PluginStore.List | p99 | 242ms | 150ms | -92ms | -38.02
| ChannelStore.GetAllChannelMembersForUser | p99 | 47ms | 30ms | -17ms | -36.36
| ChannelStore.Save | p99 | 365ms | 247ms | -118ms | -32.33
| ChannelStore.Autocomplete | p99 | 392ms | 291ms | -101ms | -25.75
| LinkMetadataStore.Save | p99 | 88ms | 69ms | -19ms | -21.65
| ChannelStore.GetMembersForUserWithPagination | p99 | 245ms | 205ms | -40ms | -16.34
| UserStore.GetByUsername | p99 | 93ms | 80ms | -13ms | -13.95
| StatusStore.Get | p99 | 58ms | 50ms | -8ms | -13.76
| PostStore.GetPostReminderMetadata | p99 | 87ms | 77ms | -10ms | -11.56
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 524ms | 465ms | -59ms | -11.26
| JobStore.Get | p99 | 99ms | 89ms | -10ms | -10.12
| TeamStore.GetByName | p99 | 81ms | 73ms | -8ms | -9.93
| PostStore.SetPostReminder | p99 | 98ms | 89ms | -9ms | -9.20
| UserStore.GetMany | p99 | 44ms | 40ms | -4ms | -9.03
| GroupStore.GetByName | p99 | 70ms | 64ms | -6ms | -8.60
| ClusterDiscoveryStore.SetLastPingAt | p99 | 92ms | 85ms | -7ms | -7.61
| PostStore.Update | p99 | 219ms | 203ms | -16ms | -7.32
| ChannelStore.GetPublicChannelsForTeam | p99 | 201ms | 187ms | -14ms | -6.97
| UserStore.GetForLogin | p99 | 72ms | 67ms | -5ms | -6.93
| ChannelStore.CreateDirectChannel | p99 | 442ms | 413ms | -29ms | -6.56
| ChannelStore.GetChannelsByUser | p99 | 93ms | 87ms | -6ms | -6.45
| SystemStore.GetByName | p99 | 64ms | 60ms | -4ms | -6.20
| PostStore.GetPosts | p99 | 67ms | 63ms | -4ms | -5.98
| UserStore.IsEmpty | p99 | 35ms | 33ms | -2ms | -5.69
| PostStore.GetPostReminders | p99 | 94ms | 89ms | -5ms | -5.31
| JobStore.GetAllByStatus | p99 | 98ms | 93ms | -5ms | -5.10
| ChannelStore.SearchGroupChannels | p99 | 101ms | 96ms | -5ms | -4.96
| AuditStore.Save | p99 | 71ms | 68ms | -3ms | -4.24
| SessionStore.Remove | p99 | 48ms | 46ms | -2ms | -4.14
| ReactionStore.GetUniqueCountForPost | p99 | 79ms | 76ms | -3ms | -3.81
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 228ms | 220ms | -8ms | -3.51
| JobStore.UpdateStatus | p99 | 71ms | 69ms | -2ms | -2.82
| UserStore.AnalyticsActiveCount | p99 | 247ms | 241ms | -6ms | -2.42
| ReactionStore.ExistsOnPost | p99 | 85ms | 83ms | -2ms | -2.35
| ThreadStore.GetTeamsUnreadForUser | p99 | 95ms | 93ms | -2ms | -2.11
| UserStore.Search | p99 | 249ms | 245ms | -4ms | -1.60
| PostStore.GetPostsSince | p99 | 219ms | 216ms | -3ms | -1.37
| SessionStore.Get | p99 | 159ms | 157ms | -2ms | -1.26
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 0s | 7ms | 7ms | 4980.62
| deletePost | avg | 75ms | 127ms | 52ms | 69.76
| updateCategoriesForTeamForUser | avg | 217ms | 235ms | 18ms | 8.30
| searchPostsInTeam | avg | 272ms | 285ms | 13ms | 4.78
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | p99 | 5ms | 224ms | 219ms | 4424.24
| deletePost | p99 | 245ms | 915ms | 670ms | 272.91
| unfollowThreadByUser | p99 | 268ms | 520ms | 252ms | 94.20
| updateCategoriesForTeamForUser | p99 | 961ms | 1.795s | 834ms | 86.76
| patchPost | p99 | 917ms | 1.705s | 788ms | 85.89
| setPostReminder | p99 | 240ms | 443ms | 203ms | 84.50
| updateReadStateThreadByUser | p99 | 583ms | 715ms | 132ms | 22.62
| createUser | p99 | 497ms | 583ms | 86ms | 17.29
| viewChannel | p99 | 247ms | 286ms | 39ms | 15.81
| addTeamMember | p99 | 4.842s | 5.462s | 620ms | 12.81
| updatePreferences | p99 | 232ms | 243ms | 11ms | 4.75
| getTeamMember | p99 | 87ms | 91ms | 4ms | 4.60
| getPostThread | p99 | 383ms | 400ms | 17ms | 4.44
| getTeamsForUser | p99 | 74ms | 77ms | 3ms | 4.05
| getFilePreview | p99 | 322ms | 335ms | 13ms | 4.03
| getUser | p99 | 163ms | 169ms | 6ms | 3.69
| login | p99 | 940ms | 966ms | 26ms | 2.76
| getUsersByNames | p99 | 92ms | 94ms | 2ms | 2.17
| getThreadsForUser | p99 | 96ms | 98ms | 2ms | 2.08
| getChannelUnread | p99 | 97ms | 99ms | 2ms | 2.07
| saveReaction | p99 | 467ms | 476ms | 9ms | 1.93
| uploadFileStream | p99 | 1.967s | 1.994s | 27ms | 1.37
| getLicenseSelfServeStatus | p99 | 246ms | 249ms | 3ms | 1.22
| getFileThumbnail | p99 | 246ms | 249ms | 3ms | 1.22
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| handleCheckCWSConnection | avg | 45ms | 0s | -45ms | -100.12
| updateUserCustomStatus | avg | 317ms | 0s | -317ms | -100.05
| enablePlugin | avg | 4.812s | 0s | -4.812s | -99.99
| channelMemberCountsByGroup | avg | 19ms | 0s | -19ms | -98.40
| searchFiles | avg | 17ms | 0s | -17ms | -97.27
| getEmojisByNames | avg | 10ms | 0s | -10ms | -96.67
| getPrevTrialLicense | avg | 15ms | 3ms | -12ms | -80.90
| deleteDraft | avg | 12ms | 3ms | -9ms | -77.02
| upsertDraft | avg | 18ms | 7ms | -11ms | -60.47
| patchPost | avg | 817ms | 332ms | -485ms | -59.36
| getFilteredUsersStats | avg | 42ms | 21ms | -21ms | -50.23
| createChannel | avg | 63ms | 33ms | -30ms | -47.27
| getJobsByType | avg | 17ms | 9ms | -8ms | -46.08
| createPost | avg | 1.312s | 819ms | -493ms | -37.58
| createCategoryForTeamForUser | avg | 175ms | 111ms | -64ms | -36.64
| getAnalytics | avg | 109ms | 75ms | -34ms | -31.13
| setPostReminder | avg | 54ms | 41ms | -13ms | -23.98
| getChannelsForUser | avg | 12ms | 10ms | -2ms | -17.08
| getChannelUnread | avg | 13ms | 11ms | -2ms | -15.52
| unfollowThreadByUser | avg | 67ms | 57ms | -10ms | -14.97
| getCategoriesForTeamForUser | avg | 33ms | 29ms | -4ms | -12.07
| getPostsForChannel | avg | 100ms | 88ms | -12ms | -11.97
| getChannel | avg | 18ms | 16ms | -2ms | -11.36
| removeUserCustomStatus | avg | 304ms | 270ms | -34ms | -11.17
| addChannelMember | avg | 483ms | 432ms | -51ms | -10.55
| createDirectChannel | avg | 422ms | 379ms | -43ms | -10.20
| getProfileImage | avg | 99ms | 89ms | -10ms | -10.09
| getPublicChannelsForTeam | avg | 40ms | 36ms | -4ms | -10.05
| searchUsers | avg | 70ms | 63ms | -7ms | -10.03
| createGroupChannel | avg | 709ms | 645ms | -64ms | -9.03
| getPostsForChannelAroundLastUnread | avg | 45ms | 41ms | -4ms | -8.96
| searchAllChannels | avg | 76ms | 70ms | -6ms | -7.90
| followThreadByUser | avg | 41ms | 38ms | -3ms | -7.35
| getFilePreview | avg | 74ms | 69ms | -5ms | -6.79
| autocompleteUsers | avg | 81ms | 76ms | -5ms | -6.18
| getPostThread | avg | 50ms | 47ms | -3ms | -6.02
| uploadFileStream | avg | 483ms | 456ms | -27ms | -5.59
| logout | avg | 149ms | 141ms | -8ms | -5.37
| saveReaction | avg | 76ms | 72ms | -4ms | -5.24
| getFileThumbnail | avg | 59ms | 56ms | -3ms | -5.09
| addTeamMember | avg | 1.258s | 1.221s | -37ms | -2.94
| updateReadStateThreadByUser | avg | 121ms | 119ms | -2ms | -1.66
| createUser | avg | 135ms | 133ms | -2ms | -1.48
| login | avg | 145ms | 143ms | -2ms | -1.38
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | p99 | 25ms | 0s | -25ms | -100.60
| handleCheckCWSConnection | p99 | 99ms | 0s | -99ms | -100.50
| channelMemberCountsByGroup | p99 | 98ms | 0s | -98ms | -100.17
| getEmojisByNames | p99 | 96ms | 0s | -96ms | -100.00
| enablePlugin | p99 | 4.975s | 0s | -4.975s | -100.00
| updateUserCustomStatus | p99 | 965ms | 5ms | -960ms | -99.51
| deleteDraft | p99 | 48ms | 5ms | -43ms | -89.12
| getPrevTrialLicense | p99 | 25ms | 5ms | -20ms | -80.97
| getFilteredUsersStats | p99 | 98ms | 25ms | -73ms | -74.11
| autocompleteChannelsForTeamForSearch | p99 | 1.667s | 437ms | -1.23s | -73.77
| getJobsByType | p99 | 222ms | 86ms | -136ms | -61.40
| upsertDraft | p99 | 25ms | 10ms | -15ms | -60.36
| createChannel | p99 | 243ms | 98ms | -145ms | -59.79
| getAnalytics | p99 | 477ms | 242ms | -235ms | -49.23
| createGroupChannel | p99 | 3.65s | 2.483s | -1.167s | -31.97
| searchAllChannels | p99 | 392ms | 291ms | -101ms | -25.75
| getChannel | p99 | 160ms | 125ms | -35ms | -21.82
| searchPostsInTeam | p99 | 3.087s | 2.491s | -596ms | -19.30
| createPost | p99 | 4.881s | 4.184s | -697ms | -14.28
| getUsersByIds | p99 | 36ms | 32ms | -4ms | -11.15
| createDirectChannel | p99 | 2.171s | 1.958s | -213ms | -9.81
| searchUsers | p99 | 270ms | 247ms | -23ms | -8.51
| getChannelsForUser | p99 | 93ms | 88ms | -5ms | -5.35
| followThreadByUser | p99 | 235ms | 223ms | -12ms | -5.11
| removeUserCustomStatus | p99 | 995ms | 949ms | -46ms | -4.62
| getPostsForChannel | p99 | 911ms | 870ms | -41ms | -4.50
| getChannelStats | p99 | 186ms | 178ms | -8ms | -4.30
| searchGroupChannels | p99 | 101ms | 97ms | -4ms | -3.97
| getCategoriesForTeamForUser | p99 | 229ms | 222ms | -7ms | -3.05
| createCategoryForTeamForUser | p99 | 495ms | 480ms | -15ms | -3.03
| addChannelMember | p99 | 2.167s | 2.102s | -65ms | -3.00
| getPublicChannelsForTeam | p99 | 201ms | 197ms | -4ms | -1.99
| getProfileImage | p99 | 481ms | 476ms | -5ms | -1.04
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 71ms| 68ms | -3ms | -4.237
| BotStore.Get |  Avg| 15ms| 5ms | -10ms | -68.731
| |  P99| 88ms| 24ms | -64ms | -73.143
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 168ms| 137ms | -31ms | -18.412
| |  P99| 524ms| 465ms | -59ms | -11.263
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 36ms| 20ms | -16ms | -44.942
| |  P99| 97ms| 49ms | -48ms | -49.419
| ChannelStore.Autocomplete |  Avg| 75ms| 69ms | -6ms | -7.965
| |  P99| 392ms| 291ms | -101ms | -25.747
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 139ms| 138ms | -1ms | -0.720
| |  P99| 1.667s| 437ms | -1.23s | -73.766
| ChannelStore.CreateDirectChannel |  Avg| 67ms| 50ms | -17ms | -25.302
| |  P99| 442ms| 413ms | -29ms | -6.564
| ChannelStore.CreateInitialSidebarCategories |  Avg| 36ms| 37ms | 1ms | 2.747
| |  P99| 277ms| 340ms | 63ms | 22.768
| ChannelStore.CreateSidebarCategory |  Avg| 122ms| 90ms | -32ms | -26.284
| |  P99| 247ms| 480ms | 233ms | 94.331
| ChannelStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 86ms| 92ms | 6ms | 6.944
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 1ms | -1ms | -44.834
| |  P99| 47ms| 30ms | -17ms | -36.359
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 44ms| 43ms | -1ms | -2.249
| |  P99| 244ms| 242ms | -2ms | -0.819
| ChannelStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 75ms| 76ms | 1ms | 1.333
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 20ms | 18ms | 852.259
| |  P99| 5ms| 25ms | 20ms | 403.597
| ChannelStore.GetChannelUnread |  Avg| 11ms| 10ms | -1ms | -9.402
| |  P99| 87ms| 89ms | 2ms | 2.311
| ChannelStore.GetChannels |  Avg| 10ms| 9ms | -1ms | -10.110
| |  P99| 90ms| 91ms | 1ms | 1.111
| ChannelStore.GetChannelsByUser |  Avg| 12ms| 10ms | -2ms | -17.200
| |  P99| 93ms| 87ms | -6ms | -6.446
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 83ms| 85ms | 2ms | 2.411
| ChannelStore.GetFileCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 83ms| 91ms | 8ms | 9.582
| ChannelStore.GetGuestCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 85ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 5ms| 8ms | 3ms | 57.663
| |  P99| 48ms| 84ms | 36ms | 75.676
| ChannelStore.GetMemberCount |  Avg| 38ms| 37ms | -1ms | -2.627
| |  P99| 225ms| 224ms | -1ms | -0.444
| ChannelStore.GetMemberCountsByGroup |  Avg| 18ms| 0s | -18ms | -99.944
| |  P99| 97ms| 0s | -97ms | -100.258
| ChannelStore.GetMemberForPost |  Avg| 13ms| 12ms | -1ms | -7.440
| |  P99| 89ms| 89ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 244ms| 22ms | -222ms | -91.089
| |  P99| 938ms| 97ms | -841ms | -89.673
| ChannelStore.GetMembersForUser |  Avg| 11ms| 10ms | -1ms | -8.996
| |  P99| 90ms| 91ms | 1ms | 1.116
| ChannelStore.GetMembersForUserWithPagination |  Avg| 82ms| 43ms | -39ms | -47.830
| |  P99| 245ms| 205ms | -40ms | -16.343
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 8ms | -1ms | -11.287
| |  P99| 87ms| 87ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 38ms| 34ms | -4ms | -10.552
| |  P99| 201ms| 187ms | -14ms | -6.965
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 33ms| 28ms | -5ms | -15.278
| |  P99| 228ms| 220ms | -8ms | -3.510
| ChannelStore.GetSidebarCategory |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 229ms| 275ms | 46ms | 20.087
| ChannelStore.GetTeamChannels |  Avg| 63ms| 33ms | -30ms | -47.393
| |  P99| 243ms| 98ms | -145ms | -59.794
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 75ms| 78ms | 3ms | 3.984
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 41ms| 33ms | -8ms | -19.368
| |  P99| 365ms| 247ms | -118ms | -32.329
| ChannelStore.SaveMember |  Avg| 54ms| 53ms | -1ms | -1.837
| |  P99| 389ms| 401ms | 12ms | 3.087
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 12ms | -1ms | -7.797
| |  P99| 101ms| 96ms | -5ms | -4.958
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 79ms| 81ms | 2ms | 2.530
| ChannelStore.UpdateSidebarCategories |  Avg| 137ms| 154ms | 17ms | 12.425
| |  P99| 487ms| 922ms | 435ms | 89.307
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 68ms | 6ms | 9.698
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 9ms | -1ms | -9.652
| |  P99| 92ms| 85ms | -7ms | -7.609
| CommandWebhookStore.Cleanup |  Avg| 4ms| 28ms | 24ms | 682.660
| |  P99| 10ms| 99ms | 89ms | 898.892
| ComplianceStore.MessageExport |  Avg| 14ms| 15ms | 1ms | 7.197
| |  P99| 94ms| 99ms | 5ms | 5.318
| DraftStore.Delete |  Avg| 4ms| 0s | -4ms | -96.157
| |  P99| 5ms| 0s | -5ms | -100.914
| DraftStore.Get |  Avg| 5ms| 1ms | -4ms | -85.420
| |  P99| 24ms| 5ms | -19ms | -79.325
| DraftStore.Upsert |  Avg| 10ms| 5ms | -5ms | -51.622
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 9ms| 0s | -9ms | -97.058
| |  P99| 95ms| 0s | -95ms | -99.477
| FileInfoStore.AttachToPost |  Avg| 13ms| 15ms | 2ms | 15.144
| |  P99| 97ms| 133ms | 36ms | 37.242
| FileInfoStore.Get |  Avg| 10ms| 9ms | -1ms | -10.491
| |  P99| 89ms| 91ms | 2ms | 2.241
| FileInfoStore.GetForPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 81ms| 84ms | 3ms | 3.717
| FileInfoStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 91ms| 93ms | 2ms | 2.186
| FileInfoStore.Search |  Avg| 13ms| 0s | -13ms | -96.477
| |  P99| 25ms| 0s | -25ms | -100.604
| FileInfoStore.SetContent |  Avg| 20ms| 19ms | -1ms | -5.059
| |  P99| 183ms| 190ms | 7ms | 3.819
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 5ms | 1ms | 22.299
| |  P99| 50ms| 55ms | 5ms | 10.004
| GroupStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 70ms| 64ms | -6ms | -8.602
| GroupStore.GetGroups |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 69ms| 80ms | 11ms | 15.849
| JobStore.Get |  Avg| 15ms| 10ms | -5ms | -33.337
| |  P99| 99ms| 89ms | -10ms | -10.124
| JobStore.GetAllByStatus |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 93ms | -5ms | -5.100
| JobStore.GetAllByTypePage |  Avg| 17ms| 9ms | -8ms | -46.706
| |  P99| 222ms| 86ms | -136ms | -61.399
| JobStore.GetCountByStatusAndType |  Avg| 12ms| 6ms | -6ms | -50.069
| |  P99| 91ms| 45ms | -46ms | -50.717
| JobStore.GetNewestJobByStatusesAndType |  Avg| 10ms| 5ms | -5ms | -48.335
| |  P99| 91ms| 46ms | -45ms | -49.451
| JobStore.Save |  Avg| 8ms| 5ms | -3ms | -37.967
| |  P99| 70ms| 23ms | -47ms | -66.667
| JobStore.UpdateOptimistically |  Avg| 11ms| 10ms | -1ms | -9.513
| |  P99| 81ms| 94ms | 13ms | 16.038
| JobStore.UpdateStatus |  Avg| 7ms| 8ms | 1ms | 15.324
| |  P99| 71ms| 69ms | -2ms | -2.818
| JobStore.UpdateStatusOptimistically |  Avg| 10ms| 11ms | 1ms | 10.365
| |  P99| 70ms| 69ms | -1ms | -1.429
| LicenseStore.GetAll |  Avg| 14ms| 10ms | -4ms | -27.861
| |  P99| 49ms| 49ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 82ms | 5ms | 6.470
| LinkMetadataStore.Save |  Avg| 11ms| 8ms | -3ms | -26.913
| |  P99| 88ms| 69ms | -19ms | -21.652
| PluginStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PluginStore.Get |  Avg| 13ms| 5ms | -8ms | -63.667
| |  P99| 93ms| 24ms | -69ms | -74.187
| PluginStore.List |  Avg| 40ms| 14ms | -26ms | -65.262
| |  P99| 242ms| 150ms | -92ms | -38.017
| PluginStore.SetWithOptions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 87ms | 1ms | 1.159
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 8ms | 1ms | 14.782
| |  P99| 52ms| 104ms | 52ms | 99.680
| PostAcknowledgementStore.GetForPosts |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 115ms | 18ms | 18.472
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 6ms | 2ms | 53.565
| |  P99| 23ms| 47ms | 24ms | 103.228
| PostPersistentNotificationStore.Get |  Avg| 5ms| 6ms | 1ms | 21.143
| |  P99| 82ms| 45ms | -37ms | -44.852
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 61ms| 70ms | 9ms | 14.699
| PostPriorityStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -13.169
| |  P99| 79ms| 84ms | 5ms | 6.289
| PostPriorityStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 99ms| 125ms | 26ms | 26.262
| PostStore.AnalyticsPostCount |  Avg| 570ms| 547ms | -23ms | -4.033
| |  P99| 2.47s| 2.47s | 0s | 0.000
| PostStore.Delete |  Avg| 44ms| 78ms | 34ms | 76.995
| |  P99| 239ms| 458ms | 219ms | 91.441
| PostStore.Get |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 187ms| 203ms | 16ms | 8.546
| PostStore.GetEtag |  Avg| 10ms| 9ms | -1ms | -10.476
| |  P99| 91ms| 91ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 54ms| 54ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 79ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 13ms| 9ms | -4ms | -31.357
| |  P99| 87ms| 77ms | -10ms | -11.561
| PostStore.GetPostReminders |  Avg| 15ms| 12ms | -3ms | -19.829
| |  P99| 94ms| 89ms | -5ms | -5.305
| PostStore.GetPosts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 67ms| 63ms | -4ms | -5.985
| PostStore.GetPostsAfter |  Avg| 12ms| 10ms | -2ms | -16.436
| |  P99| 91ms| 90ms | -1ms | -1.098
| PostStore.GetPostsBefore |  Avg| 12ms| 11ms | -1ms | -8.418
| |  P99| 92ms| 94ms | 2ms | 2.182
| PostStore.GetPostsByThread |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 87ms| 91ms | 4ms | 4.622
| PostStore.GetPostsSince |  Avg| 29ms| 28ms | -1ms | -3.439
| |  P99| 219ms| 216ms | -3ms | -1.372
| PostStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 73ms| 78ms | 5ms | 6.868
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 26ms| 27ms | 1ms | 3.843
| |  P99| 234ms| 243ms | 9ms | 3.847
| PostStore.SearchPostsForUser |  Avg| 244ms| 261ms | 17ms | 6.976
| |  P99| 2.482s| 2.463s | -19ms | -0.765
| PostStore.SetPostReminder |  Avg| 22ms| 13ms | -9ms | -41.001
| |  P99| 98ms| 89ms | -9ms | -9.199
| PostStore.Update |  Avg| 28ms| 26ms | -2ms | -7.119
| |  P99| 219ms| 203ms | -16ms | -7.316
| PreferenceStore.DeleteCategoryAndName |  Avg| 9ms| 14ms | 5ms | 58.318
| |  P99| 47ms| 92ms | 45ms | 94.987
| PreferenceStore.Get |  Avg| 10ms| 9ms | -1ms | -10.501
| |  P99| 89ms| 91ms | 2ms | 2.240
| PreferenceStore.GetAll |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 81ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 203ms| 208ms | 5ms | 2.468
| ProductNoticesStore.ClearOldNotices |  Avg| 36ms| 41ms | 5ms | 13.955
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 475ms| 492ms | 17ms | 3.583
| ReactionStore.ExistsOnPost |  Avg| 9ms| 8ms | -1ms | -10.843
| |  P99| 85ms| 83ms | -2ms | -2.353
| ReactionStore.GetForPost |  Avg| 9ms| 8ms | -1ms | -11.724
| |  P99| 82ms| 83ms | 1ms | 1.221
| ReactionStore.GetUniqueCountForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 76ms | -3ms | -3.810
| ReactionStore.Save |  Avg| 26ms| 25ms | -1ms | -3.840
| |  P99| 229ms| 227ms | -2ms | -0.872
| RetentionPolicyStore.GetAll |  Avg| 4ms| 5ms | 1ms | 25.484
| |  P99| 24ms| 10ms | -14ms | -57.377
| RetentionPolicyStore.GetCount |  Avg| 4ms| 5ms | 1ms | 26.427
| |  P99| 10ms| 10ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 10ms| 6ms | -4ms | -40.675
| |  P99| 64ms| 36ms | -28ms | -43.749
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 25ms | 23ms | 1292.946
| |  P99| 5ms| 50ms | 45ms | 909.091
| SessionStore.Get |  Avg| 13ms| 12ms | -1ms | -7.640
| |  P99| 159ms| 157ms | -2ms | -1.261
| SessionStore.GetSessionsExpired |  Avg| 2ms| 6ms | 4ms | 193.416
| |  P99| 5ms| 24ms | 19ms | 383.838
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 68ms| 73ms | 5ms | 7.320
| SessionStore.Remove |  Avg| 10ms| 5ms | -5ms | -49.998
| |  P99| 48ms| 46ms | -2ms | -4.136
| SessionStore.Save |  Avg| 13ms| 12ms | -1ms | -7.965
| |  P99| 98ms| 97ms | -1ms | -1.016
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 9ms | 1ms | 11.797
| |  P99| 73ms| 76ms | 3ms | 4.134
| StatusStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 58ms| 50ms | -8ms | -13.757
| StatusStore.GetByIds |  Avg| 12ms| 10ms | -2ms | -17.365
| |  P99| 94ms| 93ms | -1ms | -1.068
| StatusStore.SaveOrUpdate |  Avg| 83ms| 91ms | 8ms | 9.638
| |  P99| 937ms| 956ms | 19ms | 2.029
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 9ms | 3ms | 46.261
| |  P99| 44ms| 89ms | 45ms | 101.695
| StatusStore.UpdateLastActivityAt |  Avg| 7ms| 8ms | 1ms | 13.357
| |  P99| 72ms| 73ms | 1ms | 1.398
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 64ms| 60ms | -4ms | -6.203
| SystemStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 17ms| 9ms | -8ms | -46.390
| |  P99| 96ms| 24ms | -72ms | -74.997
| TeamStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 67ms| 74ms | 7ms | 10.390
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.358
| TeamStore.GetByName |  Avg| 7ms| 6ms | -1ms | -14.756
| |  P99| 81ms| 73ms | -8ms | -9.927
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 78ms| 78ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 3ms| 4ms | 1ms | 29.679
| |  P99| 38ms| 42ms | 4ms | 10.553
| TeamStore.GetTeamsByUserId |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 72ms| 75ms | 3ms | 4.175
| TeamStore.GetTeamsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 79ms | -1ms | -1.249
| TeamStore.SaveMember |  Avg| 40ms| 39ms | -1ms | -2.510
| |  P99| 229ms| 231ms | 2ms | 0.874
| ThreadStore.Get |  Avg| 10ms| 11ms | 1ms | 10.403
| |  P99| 71ms| 163ms | 92ms | 129.124
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 83ms | 3ms | 3.746
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 10ms | -1ms | -9.302
| |  P99| 95ms| 93ms | -2ms | -2.110
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 7ms | -1ms | -13.087
| |  P99| 66ms| 73ms | 7ms | 10.595
| ThreadStore.GetThreadForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 135ms| 150ms | 15ms | 11.102
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 97ms| 100ms | 3ms | 3.088
| ThreadStore.GetThreadsForUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 93ms| 95ms | 2ms | 2.161
| ThreadStore.GetTotalThreads |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 80ms | 4ms | 5.245
| ThreadStore.GetTotalUnreadMentions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 79ms | 3ms | 3.969
| ThreadStore.GetTotalUnreadThreads |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 75ms| 80ms | 5ms | 6.686
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 7ms | -1ms | -13.086
| |  P99| 78ms| 80ms | 2ms | 2.552
| ThreadStore.MaintainMembership |  Avg| 15ms| 16ms | 1ms | 6.506
| |  P99| 178ms| 193ms | 15ms | 8.409
| ThreadStore.MarkAllAsReadByChannels |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 81ms| 82ms | 1ms | 1.233
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 69ms| 74ms | 5ms | 7.236
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 68ms| 69ms | 1ms | 1.461
| TokenStore.Cleanup |  Avg| 3ms| 28ms | 25ms | 743.505
| |  P99| 10ms| 99ms | 89ms | 898.892
| UserAccessTokenStore.GetByToken |  Avg| 3ms| 12ms | 9ms | 257.730
| |  P99| 43ms| 92ms | 49ms | 114.143
| UserStore.AnalyticsActiveCount |  Avg| 106ms| 41ms | -65ms | -61.107
| |  P99| 247ms| 241ms | -6ms | -2.425
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 5ms | 4ms | 339.894
| |  P99| 5ms| 10ms | 5ms | 100.913
| UserStore.AutocompleteUsersInChannel |  Avg| 96ms| 89ms | -7ms | -7.266
| |  P99| 452ms| 454ms | 2ms | 0.442
| UserStore.Count |  Avg| 57ms| 35ms | -22ms | -38.790
| |  P99| 237ms| 98ms | -139ms | -58.774
| UserStore.Get |  Avg| 6ms| 7ms | 1ms | 17.526
| |  P99| 65ms| 75ms | 10ms | 15.359
| UserStore.GetAllProfiles |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.051
| UserStore.GetAllProfilesInChannel |  Avg| 454ms| 436ms | -18ms | -3.967
| |  P99| 2.227s| 2.228s | 1ms | 0.045
| UserStore.GetByUsername |  Avg| 10ms| 9ms | -1ms | -10.101
| |  P99| 93ms| 80ms | -13ms | -13.951
| UserStore.GetForLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 72ms| 67ms | -5ms | -6.933
| UserStore.GetMany |  Avg| 5ms| 6ms | 1ms | 19.739
| |  P99| 44ms| 40ms | -4ms | -9.035
| UserStore.GetNewUsersForTeam |  Avg| 5ms| 0s | -5ms | -96.591
| |  P99| 10ms| 0s | -10ms | -100.444
| UserStore.GetProfileByIds |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 90ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 91ms| 92ms | 1ms | 1.104
| UserStore.GetProfilesInChannel |  Avg| 370ms| 271ms | -99ms | -26.782
| |  P99| 1.713s| 832ms | -881ms | -51.445
| UserStore.GetRecentlyActiveUsersForTeam |  Avg| 129ms| 0s | -129ms | -99.788
| |  P99| 249ms| 0s | -249ms | -100.201
| UserStore.GetUnreadCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 76ms| 84ms | 8ms | 10.508
| UserStore.IsEmpty |  Avg| 3ms| 2ms | -1ms | -39.483
| |  P99| 35ms| 33ms | -2ms | -5.692
| UserStore.Save |  Avg| 81ms| 81ms | 0s | 0.000
| |  P99| 247ms| 248ms | 1ms | 0.405
| UserStore.Search |  Avg| 66ms| 61ms | -5ms | -7.524
| |  P99| 249ms| 245ms | -4ms | -1.604
| UserStore.Update |  Avg| 20ms| 22ms | 2ms | 9.982
| |  P99| 205ms| 207ms | 2ms | 0.975
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 71ms| 72ms | 1ms | 1.411
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.102
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 5ms | -1ms | -18.165
| |  P99| 66ms| 68ms | 2ms | 3.027
| WebhookStore.GetOutgoingByTeam |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 92ms| 94ms | 2ms | 2.183
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 483ms| 432ms | -51ms | -10.550
| | P99| 2.167s| 2.102s | -65ms | -3.000
| addTeamMember | Avg| 1.258s| 1.221s | -37ms | -2.941
| | P99| 4.842s| 5.462s | 620ms | 12.806
| autocompleteChannelsForTeamForSearch | Avg| 139ms| 138ms | -1ms | -0.720
| | P99| 1.667s| 437ms | -1.23s | -73.766
| autocompleteUsers | Avg| 81ms| 76ms | -5ms | -6.185
| | P99| 423ms| 427ms | 4ms | 0.946
| channelMemberCountsByGroup | Avg| 19ms| 0s | -19ms | -98.405
| | P99| 98ms| 0s | -98ms | -100.170
| createCategoryForTeamForUser | Avg| 175ms| 111ms | -64ms | -36.636
| | P99| 495ms| 480ms | -15ms | -3.030
| createChannel | Avg| 63ms| 33ms | -30ms | -47.270
| | P99| 243ms| 98ms | -145ms | -59.794
| createDirectChannel | Avg| 422ms| 379ms | -43ms | -10.198
| | P99| 2.171s| 1.958s | -213ms | -9.810
| createGroupChannel | Avg| 709ms| 645ms | -64ms | -9.028
| | P99| 3.65s| 2.483s | -1.167s | -31.973
| createPost | Avg| 1.312s| 819ms | -493ms | -37.578
| | P99| 4.881s| 4.184s | -697ms | -14.281
| createUser | Avg| 135ms| 133ms | -2ms | -1.478
| | P99| 497ms| 583ms | 86ms | 17.292
| deleteDraft | Avg| 12ms| 3ms | -9ms | -77.017
| | P99| 48ms| 5ms | -43ms | -89.119
| deletePost | Avg| 75ms| 127ms | 52ms | 69.764
| | P99| 245ms| 915ms | 670ms | 272.913
| enablePlugin | Avg| 4.812s| 0s | -4.812s | -99.993
| | P99| 4.975s| 0s | -4.975s | -100.000
| followThreadByUser | Avg| 41ms| 38ms | -3ms | -7.353
| | P99| 235ms| 223ms | -12ms | -5.106
| getAllTeams | Avg| 8ms| 7ms | -1ms | -13.049
| | P99| 90ms| 91ms | 1ms | 1.112
| getAnalytics | Avg| 109ms| 75ms | -34ms | -31.131
| | P99| 477ms| 242ms | -235ms | -49.234
| getCategoriesForTeamForUser | Avg| 33ms| 29ms | -4ms | -12.066
| | P99| 229ms| 222ms | -7ms | -3.052
| getChannel | Avg| 18ms| 16ms | -2ms | -11.358
| | P99| 160ms| 125ms | -35ms | -21.824
| getChannelMember | Avg| 19ms| 18ms | -1ms | -5.296
| | P99| 210ms| 210ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 12ms| 11ms | -1ms | -8.622
| | P99| 92ms| 93ms | 1ms | 1.083
| getChannelStats | Avg| 11ms| 10ms | -1ms | -9.085
| | P99| 186ms| 178ms | -8ms | -4.305
| getChannelUnread | Avg| 13ms| 11ms | -2ms | -15.524
| | P99| 97ms| 99ms | 2ms | 2.069
| getChannelsForTeamForUser | Avg| 11ms| 10ms | -1ms | -9.360
| | P99| 94ms| 95ms | 1ms | 1.066
| getChannelsForUser | Avg| 12ms| 10ms | -2ms | -17.082
| | P99| 93ms| 88ms | -5ms | -5.355
| getClientConfig | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 203ms| 204ms | 1ms | 0.491
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getEmojisByNames | Avg| 10ms| 0s | -10ms | -96.673
| | P99| 96ms| 0s | -96ms | -100.000
| getFilePreview | Avg| 74ms| 69ms | -5ms | -6.791
| | P99| 322ms| 335ms | 13ms | 4.034
| getFileThumbnail | Avg| 59ms| 56ms | -3ms | -5.092
| | P99| 246ms| 249ms | 3ms | 1.217
| getFilteredUsersStats | Avg| 42ms| 21ms | -21ms | -50.229
| | P99| 98ms| 25ms | -73ms | -74.112
| getJobsByType | Avg| 17ms| 9ms | -8ms | -46.083
| | P99| 222ms| 86ms | -136ms | -61.399
| getLicenseSelfServeStatus | Avg| 107ms| 106ms | -1ms | -0.936
| | P99| 246ms| 249ms | 3ms | 1.222
| getPostThread | Avg| 50ms| 47ms | -3ms | -6.024
| | P99| 383ms| 400ms | 17ms | 4.438
| getPostsForChannel | Avg| 100ms| 88ms | -12ms | -11.967
| | P99| 911ms| 870ms | -41ms | -4.499
| getPostsForChannelAroundLastUnread | Avg| 45ms| 41ms | -4ms | -8.960
| | P99| 414ms| 411ms | -3ms | -0.726
| getPreferences | Avg| 8ms| 7ms | -1ms | -12.926
| | P99| 85ms| 85ms | 0s | 0.000
| getPrevTrialLicense | Avg| 15ms| 3ms | -12ms | -80.900
| | P99| 25ms| 5ms | -20ms | -80.972
| getProfileImage | Avg| 99ms| 89ms | -10ms | -10.092
| | P99| 481ms| 476ms | -5ms | -1.038
| getPublicChannelsForTeam | Avg| 40ms| 36ms | -4ms | -10.050
| | P99| 201ms| 197ms | -4ms | -1.990
| getRolesByNames | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getTeamMember | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 87ms| 91ms | 4ms | 4.602
| getTeamMembersForUser | Avg| 9ms| 8ms | -1ms | -11.016
| | P99| 95ms| 95ms | 0s | 0.000
| getTeamsForUser | Avg| 7ms| 6ms | -1ms | -15.292
| | P99| 74ms| 77ms | 3ms | 4.052
| getTeamsUnreadForUser | Avg| 14ms| 13ms | -1ms | -7.309
| | P99| 159ms| 158ms | -1ms | -0.629
| getThreadsForUser | Avg| 13ms| 12ms | -1ms | -7.887
| | P99| 96ms| 98ms | 2ms | 2.084
| getUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 163ms| 169ms | 6ms | 3.691
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getUsers | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 200ms| 198ms | -2ms | -0.999
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 36ms| 32ms | -4ms | -11.152
| getUsersByNames | Avg| 11ms| 10ms | -1ms | -9.323
| | P99| 92ms| 94ms | 2ms | 2.168
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 45ms| 0s | -45ms | -100.123
| | P99| 99ms| 0s | -99ms | -100.504
| login | Avg| 145ms| 143ms | -2ms | -1.380
| | P99| 940ms| 966ms | 26ms | 2.765
| logout | Avg| 149ms| 141ms | -8ms | -5.366
| | P99| 466ms| 463ms | -3ms | -0.643
| patchPost | Avg| 817ms| 332ms | -485ms | -59.364
| | P99| 917ms| 1.705s | 788ms | 85.886
| removeUserCustomStatus | Avg| 304ms| 270ms | -34ms | -11.173
| | P99| 995ms| 949ms | -46ms | -4.622
| root | Avg| 0s| 7ms | 7ms | 4980.619
| | P99| 5ms| 224ms | 219ms | 4424.242
| saveReaction | Avg| 76ms| 72ms | -4ms | -5.239
| | P99| 467ms| 476ms | 9ms | 1.927
| searchAllChannels | Avg| 76ms| 70ms | -6ms | -7.900
| | P99| 392ms| 291ms | -101ms | -25.747
| searchFiles | Avg| 17ms| 0s | -17ms | -97.266
| | P99| 25ms| 0s | -25ms | -100.604
| searchGroupChannels | Avg| 13ms| 12ms | -1ms | -7.749
| | P99| 101ms| 97ms | -4ms | -3.966
| searchPostsInTeam | Avg| 272ms| 285ms | 13ms | 4.783
| | P99| 3.087s| 2.491s | -596ms | -19.304
| searchUsers | Avg| 70ms| 63ms | -7ms | -10.034
| | P99| 270ms| 247ms | -23ms | -8.511
| setPostReminder | Avg| 54ms| 41ms | -13ms | -23.977
| | P99| 240ms| 443ms | 203ms | 84.495
| unfollowThreadByUser | Avg| 67ms| 57ms | -10ms | -14.967
| | P99| 268ms| 520ms | 252ms | 94.204
| updateCategoriesForTeamForUser | Avg| 217ms| 235ms | 18ms | 8.303
| | P99| 961ms| 1.795s | 834ms | 86.762
| updatePreferences | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 232ms| 243ms | 11ms | 4.751
| updateReadStateAllThreadsByUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 121ms| 119ms | -2ms | -1.659
| | P99| 583ms| 715ms | 132ms | 22.624
| updateUserCustomStatus | Avg| 317ms| 0s | -317ms | -100.049
| | P99| 965ms| 5ms | -960ms | -99.512
| uploadFileStream | Avg| 483ms| 456ms | -27ms | -5.590
| | P99| 1.967s| 1.994s | 27ms | 1.373
| upsertDraft | Avg| 18ms| 7ms | -11ms | -60.469
| | P99| 25ms| 10ms | -15ms | -60.362
| viewChannel | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 247ms| 286ms | 39ms | 15.811
